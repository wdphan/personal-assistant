# AI Personal Assistant

This repository uses `pyttsx3`, `SpeechRecognition` and `OpenAI`'s api to generate audio responses.

## Installation

To install `pyttsx3` and `OpenAI`, use the commands below.

    pip3 install pyttsx3
    pip3 install openai
    pip3 install SpeechRecognition

## Usage

The following command will prompt the text "Say 'Genius' to start recording your question", in which you can speak into the mic to ask for a response.

    python3 genius.py

It will recognize the voice, recognize the audio as input and transcribes it to text, then provides a response from the chatgpt3 api.

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
