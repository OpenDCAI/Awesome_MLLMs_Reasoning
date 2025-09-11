# Awesome_MLLMs_Reasoning

In this repository, we will continuously update the latest papers, projects, and other valuable resources that advance MLLM reasoning, making learning more efficient for everyone!

<!-- omit in toc -->
## 📢 Updates

- **2025.03**: We released this repo. Feel free to open [pull requests](https://github.com/Open-DataFlow/Awesome_MLLMs_Reasoning/pulls).

<!-- omit in toc -->
## 📚 Table of Contents
- [Awesome_MLLMs_Reasoning](#-awesome_mllms_reasoning)
  - 
  - [1. Technical Report](#-1technical-report)
  - [2. Generated Data Guided Post-Training](#-2generated-data-guided-post-training)
  - [3. Test-time Scaling](#-3test-time-scaling)
  - [4. Collaborative Reasoning](#-4collaborative-reasoning)
  - [5. MLLM Reward Model](#-5mllm-reward-model)
  - [6. Benchmarks](#-6benchmarks)
  - [7. Applications](#-7applications)
- [Open-Source Projects](#️-open-source-projects)



## 📖 Papers

### 📝  1.Technical Report
We also feature some well-known technical reports on Large Language Models (LLMs) reasoning.
* [2507] [GLM-4.1V-Thinking: Towards Versatile Multimodal Reasoning with Scalable Reinforcement Learning] (GLM-V Team) [Technical Report](https://arxiv.org/pdf/2507.01006)

* [2506] [MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention] (MiniMax Team) [Technical Report](https://arxiv.org/pdf/2506.13585)

* [2506] [MiMo-VL Technical Report] (LLM-Core Xiaomi) [Technical Report](https://www.arxiv.org/pdf/2506.03569)

* [2504] [Kimi-VL Technical Report] (Kimi Team) [Technical Report](https://arxiv.org/pdf/2504.07491)
  
* [2503] [Skywork R1V: Pioneering Multimodal Reasoning with Chain-of-Thought] (SkyWork AI) [Technical Report](https://github.com/SkyworkAI/Skywork-R1V/blob/main/Skywork_R1V.pdf) [Model](https://huggingface.co/Skywork/Skywork-R1V-38B)

* [2503] [Phi-4-Mini Technical Report: Compact yet Powerful Multimodal Language Models via Mixture-of-LoRAs] (Microsoft) [Technical Report](https://arxiv.org/pdf/2503.01743)

* [2503] [QwQ-32B: Embracing the Power of Reinforcement Learning](Qwen Team) [Technical Report](https://qwenlm.github.io/blog/qwq-32b/) [Code](https://huggingface.co/Qwen/QwQ-32B)[Model](https://huggingface.co/Qwen/QwQ-32B-Preview)

* [2501] [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](DeepSeek Team) [Technical Report](https://arxiv.org/pdf/2501.12948)

* [2501] [Kimi k1.5: Scaling Reinforcement Learning with LLMs](Kimi Team) [Technical Report](https://arxiv.org/pdf/2501.12599)

### 📌 2.Generated Data Guided Post-Training 
| Title |    Date    |                                                  Code/Huggingface                                                  | Taxonomy |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------: | :----------------------------------------------------------------------------------------------------: | -------- |
| ![Star](https://img.shields.io/github/stars/multimodal-reasoning-lab/Bagel-Zebra-CoT.svg?style=social&label=Star)<br>[**Zebra-CoT: A Dataset for Interleaved Vision-Language Reasoning**](https://arxiv.org/abs/2507.16746) | 2025.07 | [Github](https://github.com/multimodal-reasoning-lab/Bagel-Zebra-CoT) [Huggingface](https://huggingface.co/datasets/multimodal-reasoning-lab/Zebra-CoT) | SFT |
| <!-- Star --><br>[**Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing**](https://arxiv.org/pdf/2506.09965) | 2025.06 | [Paper](https://arxiv.org/pdf/2506.09965) | RL |
| <!-- Star --><br>[**SynthRL: Scaling Visual Reasoning with Verifiable Data Synthesis**](https://arxiv.org/pdf/2506.02096) | 2025.06 | [Paper](https://arxiv.org/pdf/2506.02096) | RL |
| ![Star](https://img.shields.io/github/stars/Leo-ssl/RAP.svg?style=social&label=Star)<br>[**Truth in the Few: High-Value Data Selection for Efficient Multi-Modal Reasoning**](https://arxiv.org/pdf/2506.04755) | 2025.06 | [Github](https://github.com/Leo-ssl/RAP) | RL |
| <!-- Star --><br>[**GRIT: Teaching MLLMs to Think with Images**](https://arxiv.org/pdf/2505.15879) | 2025.05 | [Paper](https://arxiv.org/pdf/2505.15879) | SFT |
| <!-- Star --><br>[**DeepEyes: Incentivizing “Thinking with Images” via Reinforcement Learning**](https://arxiv.org/pdf/2505.14362) | 2025.05 | [Paper](https://arxiv.org/pdf/2505.14362) | RL |
| <!-- Star --><br>[**Chain-of-Focus: Adaptive Visual Search and Zooming for Multimodal Reasoning via RL**](https://arxiv.org/pdf/2505.15436) | 2025.05 | [Paper](https://arxiv.org/pdf/2505.15436) | RL |
| <!-- Star --><br>[**SoTA with Less: MCTS-Guided Sample Selection for Data-Efficient Visual Reasoning Self-Improvement**](https://arxiv.org/pdf/2504.07934) | 2025.04 | [Paper](https://arxiv.org/pdf/2504.07934) | RL |
| ![Star](https://img.shields.io/github/stars/zwq2018/embodied_reasoner.svg?style=social&label=Star)<br>[**Embodied-Reasoner: Synergizing Visual Search, Reasoning, and Action for Embodied Interactive Tasks**](https://arxiv.org/abs/2503.21696) | 2025.03 | [Paper](https://arxiv.org/abs/2503.21696) [Code](https://github.com/zwq2018/embodied_reasoner) | RL |
| <!-- Star --><br>[**Reason-RFT: Reinforcement Fine-Tuning for Visual Reasoning**](https://arxiv.org/abs/2503.20752) | 2025.03 | [Paper](https://arxiv.org/abs/2503.20752) | RL |
| <!-- Star --><br>[**R1-VL: Learning to Reason with Multimodal Large Language Models via Step-wise Group Relative Policy Optimization**](https://arxiv.org/pdf/2503.12937) | 2025.03 | [Paper](https://arxiv.org/pdf/2503.12937) | RL |
| ![Star](https://img.shields.io/github/stars/Fancy-MLLM/R1-Onevision.svg?style=social&label=Star)<br>[**R1-Onevision: Advancing Generalized Multimodal Reasoning through Cross-Modal Formalization**](https://arxiv.org/abs/2503.10615) | 2025.03 | [Github](https://github.com/Fancy-MLLM/R1-Onevision) [Huggingface](https://huggingface.co/datasets/Fancy-MLLM/R1-Onevision) | RL |
| ![Star](https://img.shields.io/github/stars/ModalMinds/MM-EUREKA.svg?style=social&label=Star)<br>[**MM-EUREKA: Exploring the Frontiers of Multimodal Reasoning with Rule-Based Reinforcement Learning**](https://arxiv.org/pdf/2503.07365) | 2025.03 | [Github](https://github.com/ModalMinds/MM-EUREKA) [Huggingface](https://huggingface.co/datasets/FanqingM/MMK12) | RL |
| <!-- Star --><br>[**Vision-R1: Incentivizing Reasoning Capability in Multimodal Large Language Models**](https://arxiv.org/pdf/2503.06749) | 2025.03 | [Paper](https://arxiv.org/pdf/2503.06749) | RL |
| ![Star](https://img.shields.io/github/stars/turningpoint-ai/VisualThinker-R1-Zero.svg?style=social&label=Star)<br>[**R1-Zero’s “Aha Moment” in Visual Reasoning on a 2B Non-SFT Model**](https://arxiv.org/pdf/2503.05132) | 2025.03 | [Paper](https://arxiv.org/pdf/2503.05132) [Blog](https://turningpointai.notion.site/the-multimodal-aha-moment-on-2b-model) [Code](https://github.com/turningpoint-ai/VisualThinker-R1-Zero) | RL |
| ![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star)<br>[**Visual-RFT: Visual Reinforcement Fine-Tuning**](https://arxiv.org/abs/2503.01785) | 2025.03 | [Paper](https://arxiv.org/abs/2503.01785) [Code](https://github.com/Liuziyu77/Visual-RFT) | RL |
| ![Star](https://img.shields.io/github/stars/PhoenixZ810/OmniAlign-V.svg?style=social&label=Star)<br>[**OmniAlign-V: Towards Enhanced Alignment of MLLMs with Human Preference**](https://arxiv.org/pdf/2502.18411) | 2025.02 | [Paper](https://arxiv.org/pdf/2502.18411) [Code](https://github.com/PhoenixZ810/OmniAlign-V) | RLHF |
| ![Star](https://img.shields.io/github/stars/Aurora-slz/MM-Verify.svg?style=social&label=Star)<br>[**MM-Verify: Enhancing Multimodal Reasoning with Chain-of-Thought Verification**](https://arxiv.org/pdf/2502.13383) | 2025.02 | [Paper](https://arxiv.org/pdf/2502.13383) [Code](https://github.com/Aurora-slz/MM-Verify) | RL |
| ![Star](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF.svg?style=social&label=Star)<br>[**MM-RLHF: The Next Step Forward in Multimodal LLM Alignment**](https://arxiv.org/pdf/2502.10391) | 2025.02 | [Paper](https://arxiv.org/pdf/2502.10391) [Code](https://github.com/Kwai-YuanQi/MM-RLHF) | RLHF |
| <!-- Star --><br>[**Can We Generate Images with CoT? Let’s Verify and Reinforce Image Generation Step by Step**](https://arxiv.org/pdf/2501.13926) | 2025.01 | [Paper](https://arxiv.org/pdf/2501.13926) [Code](https://github.com/ZiyuGuo99/Image-Generation-CoT) | RL |
| <!-- Star --><br>[**Imagine while Reasoning in Space: Multimodal Visualization-of-Thought**](https://arxiv.org/pdf/2501.07542) | 2025.01 | [Paper](https://arxiv.org/pdf/2501.07542) | RL |
| <!-- Star --><br>[**LlamaV-o1: Rethinking Step-by-step Visual Reasoning in LLMs**](https://arxiv.org/pdf/2501.06186) | 2025.01 | [Paper](https://arxiv.org/pdf/2501.06186) | RL |
| <!-- Star --><br>[**URSA: Understanding and Verifying Chain-of-thought Reasoning in Multimodal Mathematics**](https://arxiv.org/pdf/2501.04686) | 2025.01 | [Paper](https://arxiv.org/pdf/2501.04686) | RL |
| <!-- Star --><br>[**Technical Report on Slow Thinking with LLMs: Visual Reasoning**](https://arxiv.org/pdf/2501.01904) | 2025.01 | [Paper](https://arxiv.org/pdf/2501.01904) | RL |
| <!-- Star --><br>[**Progressive Multimodal Reasoning via Active Retrieval**](https://arxiv.org/pdf/2412.14835) | 2024.12 | [Paper](https://arxiv.org/pdf/2412.14835) | RL |
| <!-- Star --><br>[**Diving into Self-Evolving Training for Multimodal Reasoning**](https://arxiv.org/pdf/2412.17451) | 2024.12 | [Paper](https://arxiv.org/pdf/2412.17451) | RL |
| <!-- Star --><br>[**TACO: Learning Multi-modal Action Models with Synthetic Chains-of-Thought-and-Action**](https://arxiv.org/pdf/2412.05479) | 2024.12 | [Paper](https://arxiv.org/pdf/2412.05479) | RL |
| <!-- Star --><br>[**Scaling Inference-Time Search with Vision Value Model for Improved Visual Comprehension**](https://arxiv.org/pdf/2412.03704) | 2024.12 | [Paper](https://arxiv.org/pdf/2412.03704) | RL |
| <!-- Star --><br>[**MAmmoTH-VL: Eliciting Multimodal Reasoning with Instruction Tuning at Scale**](https://arxiv.org/pdf/2412.05237) | 2024.12 | [Paper](https://arxiv.org/pdf/2412.05237) | SFT |
| <!-- Star --><br>[**Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization**](https://arxiv.org/pdf/2411.10442) | 2024.11 | [Paper](https://arxiv.org/pdf/2411.10442) | RLHF |
| <!-- Star --><br>[**Critic-V: VLM Critics Help Catch VLM Errors in Multimodal Reasoning**](https://arxiv.org/pdf/2411.18203) | 2024.11 | [Paper](https://arxiv.org/pdf/2411.18203) | RL |
| <!-- Star --><br>[**Insight-V: Exploring Long-Chain Visual Reasoning with Multimodal Large Language Models**](https://arxiv.org/pdf/2411.14432) | 2024.11 | [Paper](https://arxiv.org/pdf/2411.14432) | RL |
| <!-- Star --><br>[**AtomThink: A Slow Thinking Framework for Multimodal Mathematical Reasoning**](https://arxiv.org/pdf/2411.11930) | 2024.11 | [Paper](https://arxiv.org/pdf/2411.11930) | RL |
| <!-- Star --><br>[**LLaVA-o1: Let Vision Language Models Reason Step-by-Step**](https://arxiv.org/pdf/2411.10440v1) | 2024.11 | [Paper](https://arxiv.org/pdf/2411.10440v1) | SFT |
| <!-- Star --><br>[**Vision-Language Models Can Self-Improve Reasoning via Reflection**](https://arxiv.org/pdf/2411.00855) | 2024.11 | [Paper](https://arxiv.org/pdf/2411.00855) | RL |
| ![Star](https://img.shields.io/github/stars/RifleZhang/LLaVA-Reasoner-DPO.svg?style=social&label=Star)<br>[**Improve Vision Language Model Chain-of-thought Reasoning**](https://arxiv.org/pdf/2410.16198) | 2024.10 | [Github](https://github.com/RifleZhang/LLaVA-Reasoner-DPO) [Huggingface](https://huggingface.co/datasets/Share4oReasoning/sft_data) | SFT & RL |
| <!-- Star --><br>[**Visual CoT: Unleashing Chain-of-Thought Reasoning in Multi-Modal Language Models**](https://arxiv.org/pdf/2403.16999) | 2024.03 | [Paper](https://arxiv.org/pdf/2403.16999) | SFT |
| <!-- Star --><br>[**Shikra: Unleashing Multimodal LLM’s Referential Dialogue Magic**](https://arxiv.org/pdf/2306.15195) | 2023.06 | [Paper](https://arxiv.org/pdf/2306.15195) | SFT |
[⬆️ Back to Top](#-table-of-contents)

### 🚀 3.Test-time Scaling
* [2502] [Boosting Multimodal Reasoning with MCTS-Automated Structured Thinking] (THU) [Paper](https://arxiv.org/pdf/2502.02339)
  
* [2502] [MLLMs Know Where to Look: Training-free Perception of Small Visual Details with Multimodal LLMs] (USC) [Paper](https://arxiv.org/pdf/2502.17422)
  
* [2412] [Scaling Inference-Time Search with Vision Value Model for Improved Visual Comprehension] (University of Maryland) [Paper](https://arxiv.org/pdf/2412.03704)
  
* [2411] [Vision-Language Models Can Self-Improve Reasoning via Reflection] (NJU) [Paper](https://arxiv.org/pdf/2411.00855) [Code](https://github.com/njucckevin/MM-Self-Improve)
  
* [2402] [Scaffolding Coordinates to Promote Vision-Language Coordination in Large Multi-Modal Models] (THU) [Paper](https://arxiv.org/pdf/2402.12058) [Code](https://github.com/leixy20/Scaffold)
  
* [2402] [V-STaR: Training Verifiers for Self-Taught Reasoners] (Mila, Universite de Montreal) [Paper](https://arxiv.org/pdf/2402.06457) 

[⬆️ Back to Top](#-table-of-contents)

### 🚀 4.Collaborative Reasoning
This kind of method aims to use small models(tool or visual expert) or multiple MLLMs to do collaborative reasoning.

* [2412] [Scaling Inference-Time Search with Vision Value Model for Improved Visual Comprehension] (University of Maryland) [Paper](https://arxiv.org/pdf/2412.03704)
  
* [2410] [VipAct: Visual-Perception Enhancement via Specialized VLM Agent Collaboration and Tool-use] (Dartmouth College) [Paper](https://arxiv.org/pdf/2410.16400)
  
* [2406] [Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models] (University of Washington) [Paper](https://arxiv.org/pdf/2406.09403)
  
* [2409] [Visual Agents as Fast and Slow Thinkers] (UCLA) [Paper](https://openreview.net/pdf?id=ncCuiD3KJQ)
  
* [2312] [Visual Program Distillation: Distilling Tools and Programmatic Reasoning into Vision-Language Models] (Google Research) [Paper](https://arxiv.org/pdf/2312.03052)
  
* [2211] [Visual Programming: Compositional visual reasoning without training] (Allen Institute for AI) [Paper](https://arxiv.org/abs/2211.11559) 

[⬆️ Back to Top](#-table-of-contents)


### 💰 5.MLLM Reward Model
* [2505] [R1-Reward: Training Multimodal Reward Model Through Stable Reinforcement Learning](CASIS) [Paper](https://arxiv.org/pdf/2505.02835)

* [2503] [VisualPRM: An Effective Process Reward Model for Multimodal Reasoning](Shanghai AI Lab) [Paper](https://huggingface.co/papers/2503.10291) [Blog](https://internvl.github.io/blog/2025-03-13-VisualPRM/)

* [2503] [Unified Reward Model for Multimodal Understanding and Generation] (Shanghai AI Lab) [Paper](https://arxiv.org/pdf/2503.05236)

* [2502] [Preference VLM: Leveraging VLMs for Scalable Preference-Based Reinforcement Learning] (University of California, Riverside) [Paper](https://arxiv.org/pdf/2502.01616)
  
* [2501] [InternLM-XComposer2.5-Reward: A Simple Yet Effective Multi-Modal Reward Model] (Shanghai AI Lab) [Paper](https://arxiv.org/pdf/2501.12368)
  
* [2410] [TLDR: Token-Level Detective Reward Model for Large Vision Language Models] (Meta) [Paper](https://arxiv.org/pdf/2410.04734)
  
* [2410] [FINE-GRAINED VERIFIERS: PREFERENCE MODELING AS NEXT-TOKEN PREDICTION IN VISION-LANGUAGE  ALIGNMENT] (NUS) [Paper](https://arxiv.org/abs/2410.14148)
  
* [2410] [LLaVA-Critic: Learning to Evaluate Multimodal Models] (ByteDance) [Paper](https://arxiv.org/pdf/2410.02712) [Code](https://llava-vl.github.io/blog/2024-10-03-llava-critic/)

[⬆️ Back to Top](#-table-of-contents)

### 📊 6.Benchmarks
Benchmark Papers:

* [2503] [CrossWordBench: Evaluating the Reasoning Capabilities of LLMs and LVLMs with Controllable Puzzle Generation] (CMU) [Paper](https://arxiv.org/pdf/2504.00043)

* [2503] [reWordBench: Benchmarking and Improving the Robustness of Reward Models with Transformed Inputs] (Meta) [Paper](https://arxiv.org/pdf/2503.11751)

* [2503] [How Do Multimodal Large Language Models Handle Complex Multimodal Reasoning? Placing Them in An Extensible Escape Game] (THU) [Paper](https://arxiv.org/pdf/2503.10042v1)
  
* [2502] [Multimodal RewardBench: Holistic Evaluation of Reward Models for Vision Language Models] (FAIR) [Paper](https://arxiv.org/pdf/2502.14191) [Code](https://github.com/facebookresearch/multimodal_rewardbench)
  
* [2502] [ZeroBench: An Impossible* Visual Benchmark for Contemporary Large Multimodal Models] (University of Cambridge) [Paper](https://arxiv.org/pdf/2502.09696) [Code](https://zerobench.github.io/)
  
* [2502] [MM-IQ: Benchmarking Human-Like Abstraction and Reasoning in Multimodal Models] (Tencent Hunyuan Team) [Paper](https://arxiv.org/pdf/2502.00698) [Code](https://acechq.github.io/MMIQ-benchmark/)
  
* [2502] [MME-CoT: Benchmarking Chain-of-Thought in Large Multimodal Models for Reasoning Quality, Robustness, and Efficiency] (CUHK MMLab) [Paper](https://arxiv.org/pdf/2502.09621) [Code](https://mmecot.github.io/)
  
* [2410] [HumanEval-V: Benchmarking High-Level Visual Reasoning with Complex Diagrams in Coding Tasks] (CityU HK) [Paper](https://arxiv.org/abs/2410.12381) [Homepage](https://humaneval-v.github.io/)
  
* [2406] [(CV-Bench)Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs] (NYU) [Paper](https://arxiv.org/pdf/2406.16860) [Code](https://github.com/cambrian-mllm/cambrian)
  
* [2404] [BLINK: Multimodal Large Language Models Can See but Not Perceive] (University of Pennsylvania) [Paper](https://arxiv.org/pdf/2404.12390)
  
* [2401] [(MMVP) Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs] (NYU) [Paper](https://arxiv.org/pdf/2401.06209)
  
* [2312] [(V∗Bench) V∗: Guided Visual Search as a Core Mechanism in Multimodal LLMs] (UCSD) [Paper](https://arxiv.org/pdf/2312.14135)

[⬆️ Back to Top](#-table-of-contents)

### 📦 7.Applications
* [2503] [Med-R1: Reinforcement Learning for Generalizable Medical Reasoning in Vision-Language Models] (Emory University) [Paper](https://arxiv.org/pdf/2503.13939)

[⬆️ Back to Top](#-table-of-contents)

## 🛠️ Open-Source Projects
* [MetaSpatial: Reinforcing 3D Spatial Reasoning in VLMs for the Metaverse] [Code](https://github.com/PzySeere/MetaSpatial) ![MetaSpatial Stars](https://img.shields.io/github/stars/PzySeere/MetaSpatial)
  
* [R1-Omni: Explainable Omni-Multimodal Emotion Recognition with Reinforcement Learning] [Code](https://github.com/HumanMLLM/R1-Omni) ![R1-Omni Stars](https://img.shields.io/github/stars/HumanMLLM/R1-Omni)

* [R1-V: Reinforcing Super Generalization Ability in Vision Language Models with Less Than $3] [Code](https://github.com/Deep-Agent/R1-V) ![R1-V Stars](https://img.shields.io/github/stars/Deep-Agent/R1-V) [Report](https://deepagent.notion.site/rlvr-in-vlms)
  
* [EasyR1: An Efficient, Scalable, Multi-Modality RL Training Framework] [Code](https://github.com/hiyouga/EasyR1) ![EasyR1 Stars](https://img.shields.io/github/stars/hiyouga/EasyR1)
  
* [R1-Onevision：An Open-Source Multimodal Large Language Model Capable of Deep Reasoning] [Paper](https://arxiv.org/pdf/2503.10615) [Code](https://github.com/Fancy-MLLM/R1-Onevision) ![R1-Onevision Stars](https://img.shields.io/github/stars/Fancy-MLLM/R1-Onevision)
  
* [LMM-R1] [Code](https://github.com/TideDra/lmm-r1) [Paper](https://arxiv.org/pdf/2503.07536) ![LMM-R1 Stars](https://img.shields.io/github/stars/TideDra/lmm-r1)
  
* [VLM-R1: A stable and generalizable R1-style Large Vision-Language Model] [Code](https://github.com/om-ai-lab/VLM-R1) ![VLM-R1 Stars](https://img.shields.io/github/stars/om-ai-lab/VLM-R1)
  
* [Multi-modal Open R1] [Code](https://github.com/EvolvingLMMs-Lab/open-r1-multimodal) ![Multi-modal Open R1 Stars](https://img.shields.io/github/stars/EvolvingLMMs-Lab/open-r1-multimodal)
  
* [Video-R1: Towards Super Reasoning Ability in Video Understanding] [Code](https://github.com/tulerfeng/Video-R1) ![Video-R1 Stars](https://img.shields.io/github/stars/tulerfeng/Video-R1)
  
* [Open-R1-Video] [Code](https://github.com/Wang-Xiaodong1899/Open-R1-Video) ![Open-R1-Video Stars](https://img.shields.io/github/stars/Wang-Xiaodong1899/Open-R1-Video)
  
* [R1-Vision: Let's first take a look at the image] [Code](https://github.com/yuyq96/R1-Vision) ![R1-Vision Stars](https://img.shields.io/github/stars/yuyq96/R1-Vision)


[⬆️ Back to Top](#-table-of-contents)

## 🤝 Contributing

You’re welcome to submit new resources or paper links. Please initiate a [Pull Request](https://github.com/Open-DataFlow/Awesome_MLLMs_Reasoning/pulls) directly.

