# Audio Deepfake Detection Literature

### Conference Papers

|Publication Date|Title|Paper|Code|
|:---|:---|---|---|
|2024/11|Multilevel semantic and adaptive actionness learning for weakly supervised temporal action localization, published in Neural Networks|[link](https://www.sciencedirect.com/science/article/abs/pii/S0893608024008347)
|2025/5/7|Weakly-supervised Audio Temporal Forgery Localization via Progressive Audio-language Co-learning Network|[link](https://arxiv.org/pdf/2505.01880)|
|2025/4/11|Robust Audio Deepfake Detection using Ensemble Confidence Calibration, published in ICASSP2025|[link](https://ieeexplore.ieee.org/document/10889972)|N/A|
|2024/12/17|Phoneme-Level Feature Discrepancies: A Key to Detecting Sophisticated Speech Deepfakes|[link](https://arxiv.org/abs/2412.12619)||
|2022/5/10|NaturalSpeech: End-to-End Text to Speech Synthesis with Human-Level Quality|[link](https://arxiv.org/abs/2205.04421)|[Samples](https://speechresearch.github.io/naturalspeech/)|
|2025/4/11|From Voices to Beats: Enhancing Music Deepfake Detection by Identifying Forgeries in Background, published in ICASSP2025|[link](https://ieeexplore.ieee.org/document/10890293)||
|2025/4/11|WaveSpect: A Hybrid Approach to Synthetic Audio Detection via Waveform and Spectrogram Analysis, published in ICASSP2025|[link](https://ieeexplore.ieee.org/document/10890188)||
|2025/4/11|Wave-Spectrogram Cross-Modal Aggregation for Audio Deepfake Detection, published in ICASSP2025|[link](https://ieeexplore.ieee.org/document/10890563?denied=)||
|2025/4/11|Fooling the Forgers: A Multi-Stage Framework for Audio Deepfake Detection, , published in ICASSP2025|[link](https://ieeexplore.ieee.org/document/10888175)||
|2022/2/28|Automatic speaker verification spoofing and deepfake detection using wav2vec 2.0 and data augmentation|[link](https://arxiv.org/abs/2202.12233)||
|2025/1/24|Generalizable Audio Deepfake Detection via Latent Space Refinement and Augmentation|[link](https://arxiv.org/abs/2501.14240)||
|2024/08/27, v4|Does Audio Deepfake Detection Generalize?|[link](https://arxiv.org/abs/2203.16263)||

### Survey
* 2024/12 From Audio Deepfake Detection to AI-Generated Music Detection – A Pathway and Overview[link](https://arxiv.org/pdf/2412.00571)
* 2024/10 Robust Deepfake Detection by Addressing Generalization and Trustworthiness Challenges: A Short Survey [link](https://dl.acm.org/doi/abs/10.1145/3689090.3689386)
* 2023/8 Audio Deepfake Detection: A Survey [link](https://arxiv.org/abs/2308.14970)


# Audio Deepfake Detection Implementation
### Datasets

## Spoofing and Speaker Verification
* ASVspoof2019 [link](https://datashare.ed.ac.uk/handle/10283/3336)
* ASVspoof2021 LA [link](https://zenodo.org/records/4837263#.YnDIinYzZhE)
* ASVspoof2021 DF [link](https://zenodo.org/records/4835108#.YnDIb3YzZhE)
* ASVspoof2021 dataset labels [link](https://www.asvspoof.org/index2021.html)
* CVoice,  X. Li, K. Li, Y. Zheng, C. Yan, X. Ji, and W. Xu, “Safeear: Content privacy-preserving audio deepfake detection,” arXiv:2409.09272, 2024.

## Multimodal Deepfake Detection
* MLAAD, N. M. Müller, P. Kawa, W. H. Choong, E. Casanova, E. Gölge, T. Müller, P. Syga, P. Sperl, and K. Böttinger, “Mlaad: The multi-language audio anti-spoofing dataset,” arXiv:2401.09512, 2024

## Rule-based replacement manipulation
* LAV-DF, Zhixi Cai, Kalin Stefanov, Abhinav Dhall, and Munawar Hayat. Do you really mean that? content driven audiovisual deepfake dataset and multimodal method for temporal forgery localization. In Proceedings of the International Conference on Digital Image Computing: Techniques and Applications, pages 1–10, 2022.
* HAD, Jiangyan Yi, Ye Bai, Jianhua Tao, Haoxin Ma, Zhengkun Tian, Chenglong Wang, Tao Wang, and Ruibo Fu. Halftruth: A partially fake audio detection dataset. In Proceedings of the Interspeech, pages 1654–1658, 2021.

## LLM-driven manipulation
* AV-Deepfake-1M, Zhixi Cai, Shreya Ghosh, Aman Pankaj Adatia, Munawar Hayat, Abhinav Dhall, Tom Gedeon, and kalin Stefanov. AV-Deepfake1M: A large-scale llm-driven audio-visual deepfake dataset. In Proceedings of the 32nd ACM International Conference on Multimedia, pages 7414–7423, 2024

## Environmental Sound Detection
* In-The-Wild, Nicolas M Muller, Pavel Czempin, Franziska Dieckmann, Adam Froghyar, and Konstantin Bottinger, “Does audio deepfake detection generalize?,” Interspeech, 2022.

## Pure Audio Deepfake Detection
* WaveFake,  J. Frank and L. Schönherr, “Wavefake: A data set to facilitate audio deepfake detection,” arXiv preprint arXiv:2111.02813, 2021.
* FakeOrReal, R. Reimao and V. Tzerpos, “For: A dataset for synthetic speech detection,” in 2019 International Conference on Speech Technology and Human-Computer Dialogue (SpeD). IEEE, 2019, pp. 1–10.
* FakeAVCelebV2, H. Khalid, S. Tariq, M. Kim, and S. S. Woo, “Fakeavceleb: A novel audio-video multimodal deepfake dataset,” arXiv:2108.05080, 2021.
* ADD series, J. Yi et al., “Add 2022: The first audio deepfake detection challenge,” in ICASSP, 2022. and H. Zhang et al., “Add 2023: Audio deepfake detection challenge,” in ICASSP, 2023.


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

