
# Voice-Controlled-Shell

## Introduction
Voice-Controlled Shell is a python based personal assistant to execute bash commands/scripts from voice.

## Pre-Requisites

 - Python 2.x/3.x
 - Google TTS
 - Speech_Recognition (Google STT)
 - PyAudio

## Installation
### For Debian-based systems:
Update system packages

    sudo apt-get update
    sudo apt-get upgrade

Install pip

    sudo apt-get install python-setuptools python-dev build-essential
    sudo easy_install pip
Install required libraries

    sudo apt-get install libasound-dev portaudio19-dev libportaudio2 libportaudiocpp0
    sudo apt-get install ffmpeg libav-tools
    sudo pip install pyaudio
    sudo pip install SpeechRecognition
    sudo pip install gTTS



### Valid commands
Dictionary contains all the commands which can be used to communicate with the application
