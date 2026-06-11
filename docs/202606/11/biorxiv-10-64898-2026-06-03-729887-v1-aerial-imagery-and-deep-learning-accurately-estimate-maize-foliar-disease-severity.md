---
title: Aerial imagery and deep learning accurately estimate maize foliar disease severity
title_zh: 航空影像与深度学习准确估算玉米叶部病害严重程度
authors: "Hammett, C. H., Rumley, K., Balint-Kurti, P., Gage, J. L."
date: 2026-06-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.03.729887v1.full.pdf"
tags: ["query:rs-fusion"]
score: 7.0
evidence: 基于无人机的遥感影像进行病害严重度估计
tldr: 玉米南方叶枯病(SLB)导致全球减产，传统人工目测评分费时且主观。本研究利用三年田间无人机图像和专家评分，训练九种深度学习模型，其中EVA-02-B模型跨年泛化最佳(R²=0.697)。误差分析表明模型性能受病害季节进展和评分时间偏移影响，最终实现与专家相当的自动化严重度评估，为抗病遗传研究提供高通量表型工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统人工目测玉米叶枯病严重程度耗时、主观且劳动密集，亟需自动化高精度替代方法。
method: 采集三年无人机航拍小区图像并同步专家评分，训练EVA-02-B等九种深度学习模型回归估计严重度。
result: 最佳模型EVA-02-B跨年测试R²=0.697，误差主要源于病害季节进展和图像评分时间偏移，精度与专家相当。
conclusion: 无人机与深度学习可自动评估玉米SLB严重度，精度媲美专家，适用于遗传研究的表型高通量分析。
---

## 摘要
南枯叶病（SLB）是一种由坏死性真菌病原体 Cochliobolus heterostrophus 引起的玉米（Zea mays L.）叶部病害。遗传抗性是控制 SLB 最有效的方法。培育抗病玉米品系需要田间试验，在此期间必须通过视觉评估病害表型。使用无人机的遥感是一种新兴技术，可用于高通量表型分析病害严重程度，否则该方法将劳动密集且主观。本项目采用深度学习方法，从无人机影像中估算单行玉米小区的 SLB 病害严重程度。三个生长季飞行产生的超过 26,000 个小区级图像，由专家评定员同时进行的田间视觉评分进行了标注。环境条件的变化使得标注图像数据集反映了农艺田间实验的复杂性。我们评估了来自三个架构家族的九种深度学习模型估算病害严重程度的能力。表现最佳的模型 EVA-02-B 实现了强大的跨年泛化能力（R² = 0.697）。误差分析发现，性能与季节性病害进展和飞行评分时间偏移的关联性比与图像级噪声更强。基于无人机的深度学习估算的 SLB 严重程度与专家评定员的精确度相当。本研究为将自动化表型整合到抗病性遗传研究中奠定了基础。

通俗语言摘要：玉米南枯叶病是一种导致全球产量损失的病害，开发抗性品种是控制该病害的最佳希望。研究 SLB 抗性需要植物病理学家在田间进行视觉评分，这是一种劳动密集型且需要专业知识的方法。为应对这些挑战，我们探究了是否可以使用无人机图像和人工智能（AI）自动进行 SLB 严重程度评分。我们使用三年的图像和评分数据训练 AI 模型，然后将结果与五位植物病理学家的视觉评分进行比较。表现最佳的 AI 模型显示出与专家相似的一致性水平，并证明能够对病害严重程度进行评分，尽管存在影响田间成像实验的不可预测和不可控条件（如杂草或阴影）。这些发现提供了一种经过验证的方法，提高了玉米病害研究的效率，这是农业可持续性和生产力的关键研究领域。

## Abstract
Southern leaf blight (SLB) is a foliar disease of maize (Zea mays L.) caused by the necrotrophic fungal pathogen Cochliobolus heterostrophus. Genetic resistance is the most effective control method for SLB. Developing disease resistant maize lines requires field trials during which disease phenotypes must be visually assessed. Remote sensing using drones is an emerging technology that can be leveraged for high-throughput phenotyping of disease severity that is otherwise labor-intensive and subjective. This project used a deep learning approach to estimate SLB disease severity of single-row maize plots from drone imagery. Over 26,000 plot-level images produced from flights conducted across three growing seasons were labeled with in-field visual scores taken contemporaneously by expert raters. Variation in environmental conditions contributed to a labeled image dataset that reflects the complexity of agronomic field experiments. We assessed the ability of nine deep learning models from three architectural families to estimate disease severity. The best-performing model, EVA-02-B, achieved strong cross year generalization (R2 = 0.697). Error analysis found that performance was more strongly associated with seasonal disease progression and flight-score time offset than with image-level noise. UAV-based deep learning estimated SLB severity with comparable precision to expert raters. This study lays the groundwork for integrating automated phenotypes into genetic studies of disease resistance.

PLAIN LANGUAGE SUMMARYSouthern leaf blight (SLB) of maize is a disease that causes yield loss worldwide and developing resistant varieties offers the best hope for controlling the disease. Studying SLB resistance requires plant pathologists to visually score severity in the field, a labor-intensive method that requires expertise. To address these challenges, we asked whether SLB severity scoring could be automated using drone images and artificial intelligence (AI). We trained AI models using three years of image and score data then compared the results to visual scores taken by five plant pathologists. The best performing AI model showed a similar level of consistency to the experts and proved capable of scoring severity despite unpredictable and uncontrollable conditions that affect field imaging experiments such as weeds or shadows. These findings provide a validated method that improves the efficiency of maize disease research, a critical area of study for agricultural sustainability and productivity.