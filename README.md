# VoiceOver AI

## Project Overview
VoiceOver AI is a comprehensive application designed for processing videos to extract audio, transcribe it, translate the text, and generate dubbed videos with synchronized lip movements. The application leverages advanced machine learning models and libraries to provide a seamless experience for users looking to create voiceovers or translations for video content.

## Key Features
- **Video Upload**: Users can upload videos for processing.
- **Audio Extraction**: Extracts audio from uploaded videos.
- **Speech Recognition**: Utilizes Whisper for transcribing audio to text.
- **Translation**: Translates transcribed text into target languages.
- **Text-to-Speech**: Converts translated text back into speech.
- **Lip Syncing**: Generates dubbed videos with synchronized lip movements using Wav2Lip.
- **User Interface**: Provides an interactive interface using Gradio for easy access to functionalities.

## Installation
To install the project dependencies, run:

```bash
pip install -r requirements.txt
```

## Usage
1. Upload a video file.
2. Choose to transcribe the audio or translate the text.
3. Generate a dubbed video with synchronized audio.

## Dependencies
This project uses the following libraries:
- TTS
- numpy
- scipy
- whisper
- indic-transliteration
- jiwer
- googletrans
- tensorflow
- librosa
- matplotlib
- nltk
- batch-face

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
