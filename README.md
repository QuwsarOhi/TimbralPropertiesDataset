# TimbralPropertiesDataset

Contains 400 speech audio files of 0.3 seconds length. The audios were generated from [LibriSpeech clean dataset](http://www.openslr.org/12).

For each of the audio files seven timbral properties are extarcted which are:
* Boominess
* Brightness
* Depth
* Hardness
* Roughness
* Sharpness
* Warmth 

The timbral properties were fetched using the [Timbre Extraction Tool](https://github.com/AudioCommons/timbral_models) created by [AudioCommons](https://www.audiocommons.org/). The properties were then modified based on human intuition.

The naming of each file is generated as: personID_count.wav
