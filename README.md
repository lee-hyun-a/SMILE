## Explainable Smile Detection Through Semi-Supervised Learning with Generative Networks
Created by [Hyuna Lee](https://leehyuna.notion.site/af4caee250c74744a7f3a44ef143110c?pvs=4) from Hanyang University.

<img src="https://github.com/lee-hyun-a/SMILE/blob/main/doc/pipeline.png" width="700"/>

### Introduction
This repository is based on Hyuna Lee's master's thesis research, which proposes a novel method for smile detection and localization. You can also check [webpage](https://leehyuna.notion.site/949d1b5a841c4585a3051894ac8a242b?pvs=4) for a deeper introduction and full paper.

The proposed method is based on a basic theme of reconstruction-based anomaly detection using generative model. we used convolutional variational autoencoder(cVAE) for reconstruction.

In this repository, we release code for training a generative network on face annotation dataset. And we used [GENKI-4K dataset](https://inc.ucsd.edu/mplab/398/), which is a well-known benchmark dataset for smile detection.

### Smile localization example
<img src="https://github.com/lee-hyun-a/SMILE/blob/main/doc/smile_localization_result.png" width="800"/>
