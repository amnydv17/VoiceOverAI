# VoiceOver AI

## Overview
VoiceOver AI is an advanced speech-to-text and text-to-speech pipeline designed to process video files by extracting audio, transcribing speech, and translating the text into different languages. This project utilizes OpenAI's Whisper model for automatic speech recognition (ASR), along with various NLP tools for transliteration and translation. 

## Features
- **Video Upload & Processing**: Users can upload video files, extract audio, and process it efficiently.
- **Automatic Speech Recognition (ASR)**: Uses OpenAI Whisper for high-accuracy transcription.
- **Text Processing & Translation**: Supports multiple languages using `googletrans` and `indic-transliteration`.
- **Customizable Resolutions**: Option to resize videos to 720p for better processing.
- **Interactive UI**: Utilizes `ipywidgets` for an intuitive and user-friendly experience.

## Installation
### Prerequisites
- Python 3.8+
- FFmpeg (for video processing)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/VoiceOverAI.git
   cd VoiceOverAI
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. **Upload a Video File**
   - Run the Jupyter Notebook.
   - Upload a video file via the UI.
   - Choose whether to resize the video to 720p.
2. **Extract and Transcribe Audio**
   - The system extracts audio from the uploaded video.
   - OpenAI Whisper is used for speech-to-text conversion.
3. **Translation and Voice Generation**
   - Translate the extracted text into a target language.
   - Convert the translated text into speech.

## Dependencies
The project requires the following libraries, which are included in `requirements.txt`:
```txt
TTS
numpy==1.24.0
scipy
git+https://github.com/openai/whisper.git
indic-transliteration
jiwer
googletrans==4.0.0-rc1
tensorflow==2.12.0
pickle-mixin
openai-whisper
librosa
matplotlib
nltk
batch-face
```
Install them with:
```sh
pip install -r requirements.txt
```

## Technologies Used
- **Python**
- **OpenAI Whisper (ASR)**
- **TensorFlow**
- **Google Translate API**
- **Librosa** (for audio processing)
- **FFmpeg** (for video processing)

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
