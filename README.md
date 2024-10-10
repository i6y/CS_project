# Dependencies

#### Program must run on a device with an x86_64 chipset

#### ffmpeg

#### whisper [PyPI page](https://pypi.org/project/openai-whisper/)

#### gpt4free/g4f [PyPI page](https://pypi.org/project/g4f/)
 ```sh
  - pip install -U g4f[all]
 ```


#### Use either an mp3 or mp4 file. If you have a trancript and you just want to create notes you can just replace the definition of the 'text' variable with your transcript, and then, to save time, you can also delete the lines that actually use the whisper library.
