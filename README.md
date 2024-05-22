# ChatBot with Text-to-Speech (TTS)

This repository contains a Python-based chatbot that uses the DialoGPT model for conversational AI and Google Text-to-Speech (gTTS) for converting text responses into speech. The chatbot is designed to run in environments like Google Colab, where direct audio playback is not available. Instead, it generates audio files that can be played directly within the notebook.

## Features

- **Conversational AI**: Utilizes the `microsoft/DialoGPT-medium` model from Hugging Face Transformers to generate human-like responses.
- **Text-to-Speech**: Uses Google Text-to-Speech (`gTTS`) to convert text responses into speech and plays them using IPython's audio display.
- **Wake-Up Word**: The chatbot can be activated using its name (e.g., "GP").
- **Exit Commands**: The chatbot can recognize commands like "exit", "close", or "bye" to terminate the conversation.

## Setup

To get started with the chatbot, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/ChatBot-TTS.git
    cd ChatBot-TTS
    ```

2. **Install the required packages**:
    All packages have been  imported in the notebook and can be installed via pip.

3. **Run the chatbot**:
    Open the notebook in Google Colab or Jupyter Notebook and run the cells to start the chatbot.

## Notes

- The chatbot uses `gTTS` to generate an MP3 file for the spoken response.
- The MP3 file is played directly within the notebook using `IPython.display.Audio`.
- Ensure that you are running the notebook in an environment that supports audio playback, like Google Colab.
- In case of running the notebookon colab, comment out the pygame mixer initialization line to rpovide input via text.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

