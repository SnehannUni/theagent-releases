# theAgent releases

Installers and update manifests for theAgent on Windows, and the model files its installer downloads. The source lives in a private repository.

## Voice model

The release `voice-phonon-40m-de` holds the voice theAgent's assistant speaks with:

- Phonon 40M DE by [Gradium](https://huggingface.co/gradium/phonon-40m-de), licensed [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): `config.json`, `tokenizer.json`, `model.q8.gguf`, `default-voice.safetensors`, unchanged. Non-commercial use only.
- `SKaMrKh4pNVD5dLg.safetensors`: the assistant's voice, designed in Gradium Studio.

Speech recognition (Whisper large-v3-turbo) is downloaded from [ggerganov/whisper.cpp](https://huggingface.co/ggerganov/whisper.cpp), not from here.
