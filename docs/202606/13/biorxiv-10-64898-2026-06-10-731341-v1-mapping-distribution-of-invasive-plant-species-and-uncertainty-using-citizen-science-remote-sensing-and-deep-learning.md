---
title: "Mapping distribution of invasive plant species and uncertainty using citizen science, remote sensing, and deep learning"
title_zh: 利用公民科学、遥感和深度学习绘制入侵植物物种分布及不确定性图
authors: "Qiang, X., Gillespie, L. E., Xi, J., Gounaridis, D., Zhu, K."
date: 2026-06-12
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.10.731341v1.full.pdf"
tags: ["query:rs-fusion"]
score: 6.0
evidence: 利用遥感和深度学习进行入侵物种分布制图
tldr: "入侵植物威胁生态与经济，气候变化可能加速其扩散。本研究利用公民科学、遥感数据与深度学习框架Deepbiosphere，在密歇根州预测了1553种维管植物分布，对两种入侵物种的建模精度提升超56%。未来气候情景下，鼠李（Rhamnus cathartica）和臭椿（Ailanthus altissima）均将北扩，其中臭椿扩张显著。研究还揭示了以全球环流模型为主的不确定性来源，并生成高分辨率风险-不确定性图，为管理决策提供关键支持。"
source: biorxiv
selection_source: fresh_fetch
motivation: 传统物种分布模型多依赖传统机器学习，缺乏对入侵物种的多物种预测及气候不确定性分析，亟需更精准且考虑不确定性的方法。
method: 采用深度学习框架Deepbiosphere，整合公民科学观测、遥感数据与未来气候情景，在全州尺度预测本地与入侵植物分布，并量化不确定性来源。
result: "Deepbiosphere在1553种植物中AUC-ROC达0.79，优于基线模型10.98%；对鼠李与臭椿的精度分别提高56.41%和74.99%，预测两者向北扩展。"
conclusion: Deepbiosphere有效提升入侵物种分布预测能力；不确定性主要来自气候模型，高分辨率风险-不确定性图可辅助气候变化下的精准管理。
---

## 摘要
入侵植物构成重大环境问题，威胁生物多样性、改变生态系统功能并造成经济损失。气候变化正在改变环境条件，可能促进入侵植物物种的扩散，对生态系统管理和生物多样性保护构成挑战。因此，准确预测入侵物种分布对于有效监测和早期干预至关重要。物种分布模型已成为预测物种栖息地的重要工具，但许多研究依赖传统机器学习方法，集中于单一物种预测，并忽略了与未来气候情景相关的不确定性。本研究旨在评估基于深度学习的物种分布模型框架Deepbiosphere在区域尺度（美国密歇根州）预测本土和入侵植物物种分布的性能，并评估气候情景不确定性如何影响入侵物种风险的空间预测，特别是针对两种重点入侵物种。结果表明，Deepbiosphere在1553种维管植物上的平均AUC-ROC为0.79，平均比其他基线模型高出10.98%。对于两种入侵物种Rhamnus cathartica和Ailanthus altissima，Deepbiosphere分别将建模精度平均提高了56.41%和74.99%，表明其对入侵物种具有更强的预测能力。当前预测显示，R. cathartica在密歇根州大部分地区已广泛适宜，而A. altissima目前更局限于南部地区。在未来气候情景下，两种物种均预计向北扩张，其中A. altissima的扩张信号尤为强烈。预测不确定性在空间上存在异质性，其中全球环流模型是该州大部分地区不确定性的主要来源。通过整合公民科学、遥感和深度学习，我们生成了关键入侵物种的高分辨率风险-不确定性地图，并强调了明确绘制不确定性以支持气候变化下更明智入侵物种管理的重要性。

## Abstract
Invasive plants pose a major environmental problem, threatening biodiversity, altering ecosystem functions, and causing economic loss. Climate change is altering environmental conditions, potentially facilitating the spread of invasive plant species, posing challenges for ecosystem management and biodiversity conservation. Accurate predictions of invasive species distributions are therefore essential for effective monitoring and early intervention. Species distribution models (SDMs) have become an important tool for predicting species habitats, but many studies rely on traditional machine learning approaches, focus on single-species predictions and overlook uncertainty associated with future climate scenarios. This study aims to evaluate the performance of a deep learning-based SDM framework, Deepbiosphere, for predicting both native and invasive plant species distributions on a regional scale, the US state of Michigan, and to assess how climate scenario uncertainty influences spatial predictions of invasive species risk particularly on two focal invasive species. Results show that Deepbiosphere outcompeted other baseline models by on average of 10.98% with a mean AUC-ROC of 0.79 across 1553 vascular plant species. For two invasive species Rhamnus cathartica and Ailanthus altissima, Deepbiosphere respectively improved modeling accuracy by an average of 56.41% and 74.99%, suggesting its enhanced predictive capability for invasive species. Current predictions indicated that R. cathartica is already broadly suitable across much of Michigan, whereas A. altissima is currently more restricted to southern regions. Under future climate scenarios, both species were projected to expand northward, with a particularly strong expansion signal for A. altissima. Prediction uncertainty was spatially heterogeneous, where general circulation models (GCMs) were the dominant source of uncertainty across most of the state. By integrating citizen science, remote sensing, and deep learning, we produced high-resolution risk-uncertainty maps for key invasive species and highlighted the importance of explicitly mapping uncertainty to support more informed invasive species management under climate change.