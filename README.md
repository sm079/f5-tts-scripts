# f5-tts nepali romanized

fine-tuning f5-tts model on romanized [[High quality TTS data for Nepali](https://www.openslr.org/43/)] dataset.  
**trained model**: https://huggingface.co/sm079/f5-tts-nepali-romanized-oslr43

## Dataset

The current model was trained on the [OpenSLR Nepali dataset](https://www.openslr.org/43/), which contains approximately 2 hours of transcribed audio. Due to the limited size of the dataset, the model quality may not be optimal. While other publicly available Nepali datasets exist, they tend to be noisy or lower in quality, requiring extensive cleaning and preprocessing for training. However, [these](https://www.iitm.ac.in/donlab/indictts/database) seem to be of decent quality and may yield better results:
- **Male Voice Dataset**: [7.24 hours](https://asr.iitm.ac.in/filedownload/download?path=/speech/sujitha/Database_IndicTTS-23/Nepali/Mono_Male&filename=Nepali_male_mono.zip)
- **Female Voice Dataset**: [10.32 hours](https://asr.iitm.ac.in/filedownload/download?path=/speech/sujitha/Database_IndicTTS-23/Nepali/Mono_Female&filename=Nepali_fem_mono.zip)


## Related

- **Base Repository**: [SWivid/F5-TTS](https://github.com/SWivid/F5-TTS)
- **Base Model**: [F5TTS_v1_Base](https://huggingface.co/SWivid/F5-TTS/tree/main/F5TTS_v1_Base)
