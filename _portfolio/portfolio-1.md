---
title: "Steered-Mixture-of-Experts (SMoE)"
excerpt: "Steered Mixtures-of-Experts (SMoE) is a regression framework for modeling and compression of 2D images, higher-dimensional imagery, including compression of light fields and light-field video, and 3D scenes.<br/><img src='/images/3DGS.png'>"
collection: portfolio
---

This PhD project investigates an explicit regression model aimed at reducing the number of computational primitives in both 2D image and 3D radiance field domains. The scope of this work includes developing methods to reduce computational primitives, investigating explicit regression for transparency and scalability, and evaluating these methods across 2D image and 3D radiance field domains. This thesis is subject to specific delimitations. First, traditional compression techniques, such as quantization, entropy coding, or transform-based representations, are excluded. These methods are useful for reducing memory either during training or after, but they do not address the structural modeling inefficiencies or change the main architecture. The focus of this thesis is to evaluate the effectiveness of the redesigned architecture. Second, implicit neural representations and deep networks, such as NeRF variants, transformers, diffusion models, or convolutional autoencoders, are not used as baselines or design foundations. These architectures often hide the modeling structure behind layers of nonlinearity and offer limited control over parameter allocation. This thesis instead emphasizes transparent, interpretable models with modular behavior. Third, the thesis works with 3D radiance fields. It omits alternative 3D representations such as point clouds, meshes, ray tracing, or light-field rendering. These modalities introduce separate concerns and would weaken the focus on the architecture and regression method.

## Articles

**3D SMoE Splatting for Edge-aware Realtime Radiance Field Rendering**  
Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Mårten Sjöström  
In the proceedings of Proceedings of the SIGGRAPH Asia 2025 Conference Papers, 2025.  
<https://doi.org/10.1145/3757377.3763899>  

**Adaptive Segmentation-Based Initialization for Steered Mixture of Experts Image Regression**  
Yi-Hsin Li, Sebastian Knorr, Marten Sjostrom, Thomas Sikora  
IEEE Transactions on Multimedia, 2025.  
<https://ieeexplore.ieee.org/document/11194262>  
