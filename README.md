<h1 align="center">Note Identifier</h1>

A 2025 School Project to create an AI to detect Notes/Sound played in an audio stream using [skey](https://github.com/deezer/skey)in Python.

## Installation.
```bash
git clone https://github.com/SimplyTea/NoteIdentifier.git
```

CLI: Verify dependency downloads with pip
```bash
pip install pyserial pyaudio git+https://github.com/deezer/skey.git
```

Or install individually,
```bash
pip install pyserial
```
```bash
pip install pyaudio
```
```bash
pip install git+https://github.com/deezer/skey.git
```


## Resources used
-    Arduino Mega
-    Python
-    - pyserial
-    - pyaudio
-    - skey [mpmath, typing-extensions, sympy, setuptools, pycparser, numpy, networkx, MarkupSafe, fsspec, filelock, einops, colorama, tqdm, scipy, jinja2, cffi, torch, soundfile, torchaudio, nnAudio]

## Members
- [Me](https://github.com/SimplyTea) Research, Hardware.
- Adian Hardware.
- Jacob Software (AI)
- Jon Software
- [Kenzo](https://github.com/kenzoshin) Software

## Documentation
https://youtu.be/uS_u8WOfaFI?si=s0u3YgeL2hmWQiAP <- Example video

If you experience an error related to the Serial Port, please read the code comments above it. MacOS and Linux will have something like dev/usbmodem, while Windows will have COM3 or such.
If you have an error based on microphone input, change the RATE, FORMAT, and CHANNEL to match it. You will rarely need to change the CHUNK, but it exists there anyway. I would have made the program do it automatically, but minor adjustments and optimizations for a project that was more of a proof of concept are unnecessary. 

Below is an image of the pin layout needed for the software. This is the same one as shown in the video, just with different colors for ease.
![f73e5390-e2d6-4315-9534-8da1cb6c2630](https://github.com/user-attachments/assets/e76b029a-5981-4e3b-8fb0-73a83ab1bf58)
