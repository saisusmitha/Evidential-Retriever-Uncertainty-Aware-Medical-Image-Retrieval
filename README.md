# Evidential-Retriever-Uncertainty-Aware-Medical-Image-Retrieval
Developed an Retriever model utilizing foundation models (BiomedCLIP, RAD-DINO) to extract reliable uncertainty estimates alongside predictive features. Built reproducible computational pipelines to evaluate on large-scale, heterogeneous datasets (CheXpert, NIH-14), providing quantifiable confidence scores for safe, AI-enabled clinical diagnostics.


[Accepted at MIDL 2026]

Abstract:

Medical image retrieval systems could play a vital role in clinical decision support by enabling physicians to find visually and semantically similar cases from large medical databases. However, deep learning-based retrieval models often overlook uncertainty in their predictions. To address this, we propose the Evidential Retriever, a novel architecture that combines evidential deep learning principles with transformer-based image representations to achieve more accurate and calibrated retrieval. Built upon a Swin Transformer backbone, our model features a dual-headed design: a retrieval head that performs metric learning for robust image embeddings, and an evidential head that models predictive uncertainty. We use a unified dual-loss, combining a regularized contrastive loss with an evidential loss. Experiments on five diverse medical imaging datasets: CheXpert, NIH-14, ISIC17, COVID-QU-Ex, and KVASIR - demonstrate that our method outperforms state-of-the-art retrieval models in retrieval accuracy and uncertainty estimation. Furthermore, we demonstrate that our evidential framework is architecture-agnostic and can be used to improve the calibration of large-scale Foundation Models.
