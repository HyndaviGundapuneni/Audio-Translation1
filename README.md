# Audio-to-Text Translation App

The **Audio-to-Text Translation App** is a Streamlit-based web application that allows users to upload audio files, transcribe the audio to text, and translate the text into a selected language. The app also generates audio for the translated text and provides the option to listen to the translation.

Built using **SpeechRecognition**, **Google Translate API**, and **gTTS (Google Text-to-Speech)**, the app provides an interactive interface for audio-to-text translation with multilingual support.

## Features

- **Audio File Upload:** Upload audio files in **WAV**, **MP3**, or **OGG** format.
- **Speech Recognition:** Automatically transcribe the speech in the uploaded audio.
- **Text Translation:** Translate the transcribed text to a selected language.
- **Text-to-Speech:** Generate speech for the translated text and play it.
- **Multilingual Support:** Translate to and from a variety of languages.

## Supported Languages

The app supports a wide range of languages for translation. Some of the supported languages are:

- English
- Hindi
- Spanish
- French
- German
- Arabic
- Chinese (Simplified and Traditional)
- Russian
- Portuguese
- And many more...

A complete list of supported languages is provided in the app.

## Requirements

To run this app, you need to install the following Python libraries:

- `streamlit`
- `speechrecognition`
- `googletrans`
- `gtts`
- `pydub`
- `playsound`

You can install these libraries using `pip`:

```bash
pip install streamlit speechrecognition googletrans gtts pydub playsound
How to Run
Clone this repository or download the necessary files.

Install the required libraries as mentioned above.

Run the following command to start the Streamlit app:

bash
Copy code
streamlit run app.py
Open the app in your web browser (usually at http://localhost:8501).

Usage
Upload an Audio File: Click the "Upload an audio file" button to upload an audio file in WAV, MP3, or OGG format.
Choose the Translation Language: Select the target language for translation from the dropdown.
View Transcription and Translation: The app will display the transcribed text from the audio and the translated text in the selected language.
Listen to the Translation: Click the "Play translation" button to listen to the audio of the translated text.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Google Translate API: Used for translating the transcribed text.
Google Text-to-Speech (gTTS): Used for generating speech from the translated text.
SpeechRecognition: Used for transcribing speech from the uploaded audio file.
Streamlit: A framework for building interactive web applications with Python.
go
Copy code

This `README.md` provides an overview of the app, its features, installation instructions, usage guidelines, and credits.





