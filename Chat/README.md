## Chat
This uses ChatGPT and a speech-to-text (STT) model to enable conversations. The user can use a microphone as an input and the Colt will respond in text. The user is required to insert the OpenAI API key in "chatColt.py".

[![Video](https://img.youtube.com/vi/YzBJ_MfYKVk/0.jpg)](https://www.youtube.com/watch?v=https://youtu.be/YzBJ_MfYKVk)

### Demo

```
python chatColt.py
```

### Setup

This repo refers to the syntax developed by OpenAI and relys on the STT models developed in 

Follow the commands:  

```
python3 -m venv ./venv
source ./venv/bin/activate
pip install -r requirements.txt
```

For Ubuntu users, if an error exists when installing pyaudio, install the "portaudio19-dev" package.

```
sudo apt install portaudio19-dev
```
