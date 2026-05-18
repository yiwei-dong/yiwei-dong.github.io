---
title: "Improving multimodal reasoning models"
collection: publications
permalink: /publication/2026-04-27-improving-multimodal-reasoning-models
excerpt: 'Standard MLLMs encode visual input only once. As reasoning tokens accumulate, the visual signal fades and the model increasingly relies on language rather than the image — a structural bias that causes hallucinations on tasks requiring close spatial inspection.'
date: 2026-04-27
venue: "Master's thesis, School of Electrical and Electronic Engineering"
paperurl: 'https://hdl.handle.net/10356/214421'
citation: 'Dong, Yiwei. (2026). &quot;Improving multimodal reasoning models.&quot; <i>Master&#39;s thesis, School of Electrical and Electronic Engineering</i>.'
---

Standard MLLMs encode visual input only once. As reasoning tokens accumulate, the visual signal fades and the model increasingly relies on language rather than the image — a structural bias that causes hallucinations on tasks requiring close spatial inspection. Tool-augmented methods help, but they follow a single reasoning path: one early misjudgement propagates without any chance of recovery, and there is no effective way to evaluate whether each tool call was actually useful. This dissertation addresses both problems by reformulating visual reasoning as an episodic Markov Decision Process. A dynamic Beam Search maintains multiple candidate trajectories simultaneously. A multi-dimensional Heuristic Process Reward Model scores step-level information gain and prunes degenerate loops. A Closed-Loop Multimodal Judge then verifies that the final answer is grounded in the visual evidence gathered during the episode. Evaluated on the BLINK benchmark using Qwen2.5-VL-7B, the framework achieves 51.50% overall accuracy across 13 subtasks, outperforming the sequential tool-use baseline (45.67%) and the unaugmented base model (49.07%). This confirms that multi-path search with step-level evaluation effectively mitigates compounding perceptual errors and establishes a reliable and scalable paradigm for complex multimodal reasoning tasks.
