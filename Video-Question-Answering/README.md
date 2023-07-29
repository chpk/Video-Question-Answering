# Transcribe YouTube Videos with Whisper

Example on how to transcribe YouTube videos with OpenAI's Whisper language model.

## Install

Install the Python packages for Whisper, PyTube and Pandas. Whisper requires Python 3.7 or later.

```sh
pip install git+https://github.com/openai/whisper.git 
pip install git+https://github.com/pytube/pytube.git
pip install pandas
```

## Usage
Specify YouTube video URL with `--video` option. The URL must be valid watch URL.

```sh
python3 main.py --video "https://www.youtube.com/watch?v=oHWuv1Aqrzk"
```