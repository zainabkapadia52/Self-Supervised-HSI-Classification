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

12.**Self-Supervised Learning for Few-Shot Hyperspectral Image Classification** (Nassim Ait Ali Braham, Lichao Mou, Jocelyn Chanussot, Julien Mairal & Xiao Xiang Zhu; IGARSS 2022, DOI:10.1109/IGARSS46834.2022.9884494)

   * Pre-trains an encoder on unlabeled hyperspectral pixels using the Barlow-Twins algorithm, then fine-tunes with a handful (K=5–10) of labeled samples per class for classification.

13. **Progressive Self-Supervised Pretraining for Hyperspectral Image Classification** (Peiyan Guan & Edmund Y. Lam; IEEE TGRS 2024, DOI:10.1109/TGRS.2024.3397740)

   * Introduces a Progressive Self-Supervised Pretraining (PSP) framework that sequentially pretrains an encoder on datasets of increasing similarity (from general vision to target HSI), and uses Self-Supervised Elastic Weight Consolidation (SS-EWC) to mitigate catastrophic forgetting, enhancing convergence speed and representation quality.

14. **Self-Supervised Feature Learning With CRF Embedding for Hyperspectral Image Classification** (Wang, Mei, Zhang, Zhang, Zhu & Li; IEEE TGRS 2019, DOI: 10.1109/TGRS.2018.2875943)

    * HSINet-CRF: a three-layer deep and multi-feature CNN with embedded CRF for self-supervised feature learning via likelihood maximization across subpixel, pixel, and superpixel levels.

