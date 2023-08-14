---
layout: post
title: PUBLICATIONS
tags: [computer vision]
comments: true
---

## [A comparative analysis of SRGAN models](https://arxiv.org/abs/2307.09456)

In this study, we evaluate the performance of multiple state-of-the-art SRGAN (Super Resolution Generative Adversarial Network) models, ESRGAN, Real-ESRGAN and EDSR, on a benchmark dataset of real-world images which undergo degradation using a pipeline. Our results show that some models seem to significantly increase the resolution of the input images while preserving their visual quality, this is assessed using Tesseract OCR engine. We observe that EDSR-BASE model from huggingface outperforms the remaining candidate models in terms of both quantitative metrics and subjective visual quality assessments with least compute overhead. Specifically, EDSR generates images with higher peak signal-to-noise ratio (PSNR) and structural similarity index (SSIM) values and are seen to return high quality OCR results with Tesseract OCR engine. These findings suggest that EDSR is a robust and effective approach for single-image super-resolution and may be particularly well-suited for applications where high-quality visual fidelity is critical and optimized compute.

### BIBTEX 
```python
@misc{nikroo2023comparative,
      title={A comparative analysis of SRGAN models}, 
      author={Fatemeh Rezapoor Nikroo and Ajinkya Deshmukh and Anantha Sharma and Adrian Tam and Kaarthik Kumar and Cleo Norris and Aditya Dangi},
      year={2023},
      eprint={2307.09456},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```