# Audio Deepfake Detection Literature

### Conference Papers

|Publication Date|Title|Paper|Code|
|:---|:---|---|---|
|2024/12/17|Phoneme-Level Feature Discrepancies: A Key to Detecting Sophisticated Speech Deepfakes|[link](https://arxiv.org/abs/2412.12619)||
|2022/5/10|NaturalSpeech: End-to-End Text to Speech Synthesis with Human-Level Quality|[link](https://arxiv.org/abs/2205.04421)|[Samples](https://speechresearch.github.io/naturalspeech/)|

* From Voices to Beats: Enhancing Music Deepfake Detection by Identifying Forgeries in Background, published in ICASSP2025. [link](https://ieeexplore.ieee.org/document/10890293)
* WaveSpect: A Hybrid Approach to Synthetic Audio Detection via Waveform and Spectrogram Analysis, published in ICASSP2025. [link](https://ieeexplore.ieee.org/document/10890188)
* Wave-Spectrogram Cross-Modal Aggregation for Audio Deepfake Detection, published in ICASSP2025. [link](https://ieeexplore.ieee.org/document/10890563?denied=)
* Fooling the Forgers: A Multi-Stage Framework for Audio Deepfake Detection, , published in ICASSP2025. [link](https://ieeexplore.ieee.org/document/10888175)
* Automatic speaker verification spoofing and deepfake detection using wav2vec 2.0 and data augmentation [link](https://arxiv.org/abs/2202.12233)
* Generalizable Audio Deepfake Detection via Latent Space Refinement and Augmentation [link](https://arxiv.org/abs/2501.14240)
* Does Audio Deepfake Detection Generalize?  [link](https://arxiv.org/abs/2203.16263)

### Survey
* Audio Deepfake Detection: A Survey [link](https://arxiv.org/abs/2308.14970)
* Robust Deepfake Detection by Addressing Generalization and Trustworthiness Challenges: A Short Survey [link](https://dl.acm.org/doi/abs/10.1145/3689090.3689386)



# Audio Deepfake Detection Implementation
### Datasets
* ASVspoof2019 [link](https://datashare.ed.ac.uk/handle/10283/3336)
* ASVspoof2021 LA [link](https://zenodo.org/records/4837263#.YnDIinYzZhE)
* ASVspoof2021 DF [link](https://zenodo.org/records/4835108#.YnDIb3YzZhE)
* ASVspoof2021 dataset labels [link](https://www.asvspoof.org/index2021.html)
* In-The-Wild, Nicolas M Muller, Pavel Czempin, Franziska Dieckmann, Adam Froghyar, and Konstantin Bottinger, “Does audio deepfake detection generalize?,” Interspeech, 2022.

### Speech Synthesis
* Synthesis Methods:
    * Text-to-speech (TTS)
    * Voice conversion (VC) 

* Synthesis (an encoder-decoder framework):
    * Encoders: convert input into embeddings
    * Decoders: Mel spectrogram generator or vocoder 
    * Conditional variational autoencoder


### Models
Wav2vec xlsr: https://github.com/facebookresearch/fairseq/blob/main/examples/wav2vec/README.md


# Audio Signal Processing
* Librosa (Python Library) tutorial: https://github.com/prodramp/publiccode/blob/master/machine_learning/python_audio_tutorial/
* PyTorch (Audio library for PyTorch): https://github.com/prodramp/publiccode/blob/master/machine_learning/python_audio_tutorial/

