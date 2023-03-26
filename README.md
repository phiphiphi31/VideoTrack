# VideoTrack

# VideoTrack: Learning to Track Objects via Video Transformer

## Authors: Fei Xie, Lei Chu, Jiahao Li, Yan Lu and Chao Ma 

### This work was done when Fei Xie was an intern at Microsoft Research Asia

Existing Siamese tracking methods, which are built onpair-wise matching between two single frames, heavily rely on additional sophisticated mechanism to exploit temporal information among successive video frames, hindering them from efficiency and industrial deployments. In this work, we resort to sequence-level target matching that can
encode temporal contexts into the spatial features through a neat feedforward video model. Specifically, we adapt the standard video transformer architecture to visual tracking by enabling spatiotemporal feature learning directly from frame-level patch sequences. To better adapt to the tracking task, we carefully blend the spatiotemporal information in the video clips through sequential multi-branch triplet blocks, which formulates a video transformer backbone. Our experimental study compares different model variants, such as tokenization strategies, hierarchical structures, and video attention schemes. Then, we propose a disentangled dual-template mechanism that decouples static and dynamic appearance clues over time, and reduces temporal redundancy in video frames. Extensive experiments show that our method, named as VideoTrack, achieves state-of-the-art results while running in real-time.

# Our paper is accepted by CVPR2023 !

@inproceedings{
anonymous2023videotrack, \\
title={VideoTrack: Learning to Track Objects via Video Transformer},\\
author={Fei Xie, Lei Chu, Jiahao Li, Yan Lu, Chao Ma },\\
booktitle={Conference on Computer Vision and Pattern Recognition 2023},\\
year={2023},
}
