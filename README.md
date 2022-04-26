# DFD-model
Near-InfraRed and VISual (NIR-VIS) face matching, as one of the most representative tasks in Heterogeneous Face Recognition (HFR), aims at retrieving a face image across different domains. With the development of deep learning and the growing demand for intelligent surveillance, it has aroused more and more research attention in the computer vision community. However, due to the dramatic modality gap between NIR and VIS images, the task of NIR-VIS face recognition becomes practically very challenging. In this paper, we propose a novel Domain-private Factor Detachment (DFD) network to disentangle domain-dependent factors and achieve identity information distillation. Our approach consists of three key components, including Domain-identity Representation Learning (DiRL), Cross-domain Factor Detachment (CdFD) and Cross-domain Aggregation Learning (CAL). Firstly, the proposed DiRL aims to achieve domain-specific information distillation and learn identity-related representations. Specifically, three sub-networks, i.e., NIR sub-Network (NIR-Net), VIS sub-Network (VIS-Net) and IDentity-dependent sub-Network (ID-Net) are designed to learn NIR facial representations, VIS facial representations and identity-dependent representations, respectively, and they can promote each other to facilitate the learning of identity-discriminative representations. Secondly, considering that the entangled modal components in face representations negatively affect the subsequent matching process, to reduce modality-related components, we model the cross-modal face matching problem into three parts, comprising Identity Variation (IV), Inter-Spectrum Variation (ISV) and Identity-Domain Variation (IDV). The CdFD is presented to eliminate ISV components and IDV components by introducing inter-spectrum invariant constraint and identity-domain invariant constraint, so that cross-modal face recognition can be performed under pure identity information differences without modal interference. Finally, the CAL is developed to learn modality-invariant yet discriminative representations by exploring within-class aggregation, negative pair separability and cross-domain positive pair compactness. Experimental results on multiple challenging databases demonstrate the effectiveness of the DFD approach.


# Requirements
tensorflow 1.3.0 + 

# Backbone network

# Note
Preparing to upload code.

# Reference
[1] Weipeng Hu, Haifeng Hu, Domain-private Factor Detachment Network for NIR-VIS Face Recognition, IEEE Trans. on Information Forensics and Security, vol. 17, pp. 1435-1449, 2022.


