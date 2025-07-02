# Self-Supervised-HSI-Classification

# Self-Supervised HSI Classification Repository

This repository collects key research papers on **self-supervised learning for hyperspectral image (HSI) classification**, supporting our problem statement of leveraging unlabeled data and minimal annotations for robust pixel-wise classification.


## Selected Papers

1. **Self Supervised Learning for Few Shot Hyperspectral Image Classification** (Ait Ali Braham *et al.*, 2022)

   * Barlow-Twins pre-training + few-shot fine-tuning for HSI classification.

2. **Nearest Neighboring Self-Supervised Learning for Hyperspectral Image Classification** (Qin *et al.*, 2022)

   * BYOL-based framework with nearest-neighbor sampling for contrastive SSL on HSI.

3. **Self-Supervised Learning With Adaptive Distillation for Hyperspectral Image Classification** (Yue *et al.*, 2023)

   * Dual SSL modules: geometric transforms and soft-label distillation.

4. **Self-Supervised Feature Learning Based on Spectral Masking for Hyperspectral Image Classification** (IEEE, 2022)

   * Masked-band reconstruction with transformer encoder–decoder.

5. **Hyperspectral Image Classification With Contrastive Self-Supervised Learning Under Limited Labeled Samples** (IEEE, 2023)

   * Contrastive SSL with spectral–spatial augmentations + few-sample fine-tuning.

6. **Self-Supervised Learning With Prediction of Image Scale and Spectral Order for Hyperspectral Image Classification** (IEEE, 2023)

   * Pretext tasks: image scale prediction and spectral band order recovery.

7. **Few-Shot Hyperspectral Image Classification With Self-Supervised Learning** (IEEE, 2024)

   * Combines SSL pre-training (Barlow-Twins, rotation, masked recon) with few-shot meta-learning.

8. **A Unified Self-Supervised Learning Framework for Hyperspectral Image Classification** (IEEE, 2023)

   * Joint contrastive learning + masked image modeling in an asymmetric Siamese transformer.

9. **S3L: Spectrum Transformer for Self-Supervised Learning in Hyperspectral Image Classification** (Remote Sensing, 2022)

   * Masking + spectral transformer with GRU pre-training + few-shot fine-tuning.

10. **Self-Supervised Learning With a Dual-Branch ResNet for Hyperspectral Image Classification** (IEEE, 2022)

    * Dual-branch pretext tasks: spectral-group classification & patch-based spectral reconstruction.
    

11. **Deep Self-Supervised Learning for Few-Shot Hyperspectral Image Classification** (Yu Li, Lei Zhang, Wei Wei & Yanning Zhang; IGARSS 2020, DOI:10.1109/IGARSS39084.2020.9323305)

   * Employs a two-branch deep network: a cube-wise classification branch and a cube-pair self-supervised branch sharing a feature extractor. The cube-pair branch regularizes the main branch under few-shot settings by learning intra-cube relationships, improving classification with limited labeled samples.

12. **Self-Supervised Learning for Few-Shot Hyperspectral Image Classification** (Nassim Ait Ali Braham, Lichao Mou, Jocelyn Chanussot, Julien Mairal & Xiao Xiang Zhu; IGARSS 2022, DOI:10.1109/IGARSS46834.2022.9884494)

   * Pre-trains an encoder on unlabeled hyperspectral pixels using the Barlow-Twins algorithm, then fine-tunes with a handful (K=5–10) of labeled samples per class for classification.

13. **Progressive Self-Supervised Pretraining for Hyperspectral Image Classification** (Peiyan Guan & Edmund Y. Lam; IEEE TGRS 2024, DOI:10.1109/TGRS.2024.3397740)

   * Introduces a Progressive Self-Supervised Pretraining (PSP) framework that sequentially pretrains an encoder on datasets of increasing similarity (from general vision to target HSI), and uses Self-Supervised Elastic Weight Consolidation (SS-EWC) to mitigate catastrophic forgetting, enhancing convergence speed and representation quality.

14. **Self-Supervised Feature Learning With CRF Embedding for Hyperspectral Image Classification** (Wang, Mei, Zhang, Zhang, Zhu & Li; IEEE TGRS 2019, DOI: 10.1109/TGRS.2018.2875943)

    * HSINet-CRF: a three-layer deep and multi-feature CNN with embedded CRF for self-supervised feature learning via likelihood maximization across subpixel, pixel, and superpixel levels.
    
15. **Self-Supervised Contrastive Learning for Cross-Domain Hyperspectral Image Representation** (Hyungtae Lee & Heesung Kwon; ICASSP 2022, DOI: 10.1109/ICASSP43922.2022.9747010)

    * Leverages a cross-domain CNN and a contrastive self-supervised framework to learn shared representations across multiple HSI datasets by clustering neighboring spectral vectors from the same image and separating spectral vectors from different images, then evaluates the learned embeddings on downstream classification tasks.
   
16. **Self-Supervised Learning With Multiscale Densely Connected Network for Hyperspectral Image Classification** (Zhen Ye, Zhan Cao, Huan Liu, Haipeng Liu, Wei Li & Lin Bai; IEEE TGRS 2024, Vol. 62)

    * Proposes SS-MSDCNet: a two-stream self-supervised framework that generates positive pairs via spectral splitting augmentation and leverages a multiscale densely connected network with 3‑D densely connected modules and spatial attention to learn rich spatial–spectral features from unlabeled HSI data; fine-tuned on limited labeled samples for downstream classification.

17. **Self-Supervised Low-Rank Representation (SSLRR) for Hyperspectral Image Classification** (Yuebing Wang, Jie Mei, Liqiang Zhang, Bing Zhang, Anjian Li & Yibo Zheng; IEEE TGRS 2018, Vol. 56, Issue 10, DOI: 10.1109/TGRS.2018.2823750)

    * Develops SSLRR: integrates low-rank representation and spectral–spatial graph regularization as pixel-level and superpixel-level constraints to remove redundant and noisy information; solves via linearized alternating direction method with adaptive penalty; achieves state-of-the-art classification improvements on benchmark HSI datasets.
   
18. **Self-Supervised Convolutional Neural Network via Spectral Attention Module for Hyperspectral Image Classification** (Hong Huang, Liuyang Luo & Chunyu Pu; IEEE GRSL 2022, DOI: 10.1109/LGRS.2022.3141870)

    * Proposes SAS-CNN: an end-to-end self-supervised CNN with a spectral attention module (SAM) that adaptively emphasizes important spectral bands; employs an encoder–decoder architecture with multi-layer concatenation to learn discriminative spectral–spatial features by reconstructing input 3-D cubes without labels, then fine-tunes on small labeled sets for downstream classification.
   
19. **Cross-Dataset Model Training for Hyperspectral Image Classification Using Self-Supervised Learning** (Jing Bai, Zichen Zhou, Zheng Chen, Zhu Xiao, Erlong Wei & Yihong Wen; IEEE TGRS 2024, Vol. 62, DOI: 10.1109/TGRS.2024.3493969)

    * Introduces a cross-dataset self-supervised pretraining framework with an adaptive channel module and masked self-supervised learning to leverage multiple HSI datasets for generalized model training, enabling robust fine-tuning on downstream target datasets under spectral variability.

20. **Cross-Dataset Model Training for Hyperspectral Image Classification Using Self-Supervised Learning** (Jing Bai, Zichen Zhou, Zheng Chen, Zhu Xiao, Erlong Wei & Yihong Wen; IEEE TGRS 2024, Vol. 62, DOI: 10.1109/TGRS.2024.3493969)

    * Introduces a cross-dataset self-supervised pretraining framework with an adaptive channel module and masked self-supervised learning to leverage multiple HSI datasets for generalized model training, enabling robust fine-tuning on downstream target datasets under spectral variability.

21. **A Novel Knowledge Distillation Method for Self-Supervised Hyperspectral Image Classification** (Qiang Chi, Guohua Lv, Guixin Zhao & Xiangjun Dong; Remote Sens. 2022, 14, 4523; DOI: 10.3390/rs14184523)

    * Proposes a self-supervised knowledge distillation framework (SSKD) that adaptively generates soft labels via spectral–spatial similarity discrimination and nearest-neighbor matching, introduces a measure of soft label quality, and improves HSI classification with minimal labels.
   
22. **Hyperspectral Imagery Classification Based on Contrastive Learning** (Hou et al.; IEEE TGRS 2021, DOI: 10.1109/TGRS.2021.3139099)

    * Two-stage training: self-supervised contrastive pretraining on unlabeled HSI samples via positive/negative pair construction, followed by feature fine-tuning with limited labeled data.
