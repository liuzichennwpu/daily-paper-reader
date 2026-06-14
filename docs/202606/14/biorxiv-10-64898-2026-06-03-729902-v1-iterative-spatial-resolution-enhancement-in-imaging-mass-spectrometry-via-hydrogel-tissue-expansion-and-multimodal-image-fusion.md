---
title: Iterative Spatial Resolution Enhancement in Imaging Mass Spectrometry via Hydrogel Tissue Expansion and Multimodal Image Fusion
title_zh: 通过水凝胶组织膨胀和多模态图像融合实现成像质谱中的迭代空间分辨率增强
authors: "Mayo, E., Samuel, J. M., Guo, Y., Ciccone, A. B., Liang, Z., Prentice, B. M."
date: 2026-06-08
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.03.729902v1.full.pdf"
tags: ["query:rs-fusion"]
score: 6.0
evidence: 多模态图像融合用于分辨率增强
tldr: 成像质谱的空间分辨率受限于探针直径和步长。ExFusion结合水凝胶组织膨胀（ExM）与多模态图像融合，将小鼠脑组织膨胀9.4倍后，利用荧光ExM和脂质ExIMS数据融合，以10 μm步长预测出~106 nm像素的MS图像，清晰显示了小脑浦肯野细胞内的脂质分布。
source: biorxiv
selection_source: fresh_fetch
motivation: 克服成像质谱空间分辨率受限于探针和步长的物理瓶颈，实现亚细胞级别的脂质成像。
method: 采用水凝胶膨胀组织（ExM）物理放大样本，结合荧光成像与质谱成像的多模态图像融合，对同一膨胀组织进行协同采样。
result: 在10 μm质谱步长下，通过10倍上采样融合，获得了约106 nm有效像素尺寸的高分辨脂质图像。
conclusion: ExFusion显著提升了成像质谱的分辨率，揭示了细胞内的脂质分布细节，为生物医学研究提供了新工具。
---

## 摘要
成像质谱（IMS）的像素大小受到多个因素的制约，包括入射探针直径和样品台的栅格步长。我们先前已证明，最初为显微镜（ExM）开发的水凝胶组织膨胀技术也可适用于成像质谱，以物理方式放大组织尺寸。膨胀成像质谱（ExIMS）利用超吸水水凝胶各向同性地膨胀薄组织切片，然后通过成像质谱进行采样，从而提高有效空间分辨率。此外，多模态图像融合通过将质谱强度值预测性地映射到同一组织切片的显微镜图像的更小像素尺寸上，以计算方式上采样成像质谱的有效空间分辨率。在此，我们提出ExFusion，这是一种统一的工作流程，通过计算融合从同一9.4倍膨胀的小鼠脑组织获得的具有结构细节的荧光ExM和具有化学细节的脂质ExIMS数据，将这两种方法结合起来。在图像融合的10倍上采样之后，多模态膨胀图像融合使我们在使用10微米栅格步长的商业质谱仪上预测出像素大小约为106纳米的质谱图像。在此分辨率下，小脑浦肯野细胞中的脂质被清晰定义，并具有细胞内分布。

## Abstract
The pixel size of imaging mass spectrometry (IMS) is fundamentally limited by several factors, including the diameter of the incident probe and the raster step size of the sample stage. We have previously demonstrated that hydrogel-based tissue expansion, originally developed for microscopy (ExM), can also be adapted for imaging mass spectrometry to physically magnify the size of the tissue. Expansion imaging mass spectrometry (ExIMS) uses a superabsorbent hydrogel to isotropically expand thin tissue sections, which can then be sampled via imaging mass spectrometry, resulting in improved effective spatial resolution. Separately, multimodal image fusion has been used to computationally upsample the effective spatial resolution in imaging mass spectrometry by predictively mapping mass spectrometric intensity values to the smaller diameter pixel sizes of a microscopy image of the same tissue section. Here, we present ExFusion, a unified workflow that combines these two approaches by computationally fusing structurally detailed fluorescent ExM and chemically detailed lipid ExIMS data obtained from the same 9.4-fold expanded mouse brain tissue. Following a 10-fold upsampling from image fusion, multimodal expansion image fusion enabled prediction of MS images at a [~]106 nm pixel size on a commercial mass spectrometer using a 10 m raster step size. At this resolution, lipids in the Purkinje cells of the cerebellum are clearly defined with intracellular distributions.