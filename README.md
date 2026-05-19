# 大语言模型知识机制研究论文集（Draft）
# A Survey of Knowledge Mechanisms in Large Language Models
近三年hf daily paper上的知识机制相关论文，各类别的voting top 100 paper

## TODO
- 更精炼和细分的列表
- 非daily paper的论文

## 目录

- [知识获取 (Knowledge Acquisition)](#知识获取) (100篇)
- [知识表征 (Knowledge Representation)](#知识表征) (100篇)
- [知识利用 (Knowledge Utilization)](#知识利用) (100篇)
- [知识演化 (Knowledge Evolution)](#知识演化) (77篇)
- [知识迁移 (Knowledge Transfer)](#知识迁移) (100篇)
- [知识评测 (Knowledge Evaluation)](#知识评测) (100篇)

---

## 知识获取 (Knowledge Acquisition)

> 研究模型在训练阶段如何获得知识：训练方法（预训练、持续预训练、SFT、对齐、RL与LRM）、训练数据（Scaling、质量、类型、混合策略）、模型架构与规模（知识容量、架构差异、MoE）。

### 2026

- [Programming with Data: Test-Driven Data Engineering for Self-Improving LLMs from Raw Corpora](https://arxiv.org/abs/2604.24819)
- [Why Fine-Tuning Encourages Hallucinations and How to Fix It](https://arxiv.org/abs/2604.15574)
- [GFT: From Imitation to Reward Fine-Tuning with Unbiased Group Advantages and Dynamic Coefficient Rectification](https://arxiv.org/abs/2604.14258)
- [KnowRL: Boosting LLM Reasoning via Reinforcement Learning with Minimal-Sufficient Knowledge Guidance](https://arxiv.org/abs/2604.12627)
- [Watch Before You Answer: Learning from Visually Grounded Post-Training](https://arxiv.org/abs/2604.05117)
- [InCoder-32B-Thinking: Industrial Code World Model for Thinking](https://arxiv.org/abs/2604.03144)
- [Adam's Law: Textual Frequency Law on Large Language Models](https://arxiv.org/abs/2604.02176)
- [SKILL0: In-Context Agentic Reinforcement Learning for Skill Internalization](https://arxiv.org/abs/2604.02268)
- [Learning to Retrieve from Agent Trajectories](https://arxiv.org/abs/2604.04949)
- [Make Geometry Matter for Spatial Reasoning](https://arxiv.org/abs/2603.26639)
- [Complementary Reinforcement Learning](https://arxiv.org/abs/2603.17621)
- [OpenResearcher: A Fully Open Pipeline for Long-Horizon Deep Research Trajectory Synthesis](https://arxiv.org/abs/2603.20278)
- [MOOSE-Star: Unlocking Tractable Training for Scientific Discovery by Breaking the Complexity Barrier](https://arxiv.org/abs/2603.03756)
- [Self-Improving World Modelling with Latent Actions](https://arxiv.org/abs/2602.06130)
- [Reinforcement World Model Learning for LLM-based Agents](https://arxiv.org/abs/2602.05842)
- [Reinforced Attention Learning](https://arxiv.org/abs/2602.04884)
- [Shaping capabilities with token-level data filtering](https://arxiv.org/abs/2601.21571)
- [Self-Distillation Enables Continual Learning](https://arxiv.org/abs/2601.19897)
- [Teaching Models to Teach Themselves: Reasoning at the Edge of Learnability](https://arxiv.org/abs/2601.18778)
- [Scientific Image Synthesis: Benchmarking, Methodologies, and Downstream Utility](https://arxiv.org/abs/2601.17027)
- [Entropy-Adaptive Fine-Tuning: Resolving Confident Conflicts to Mitigate Forgetting](https://arxiv.org/abs/2601.02151)

### 2025

- [Nested Learning: The Illusion of Deep Learning Architectures](https://arxiv.org/abs/2512.24695)
- [Latent Implicit Visual Reasoning](https://arxiv.org/abs/2512.21218)
- [Physics of Language Models: Part 4.1, Architecture Design and the Magic of Canon Layers](https://arxiv.org/abs/2512.17351)
- [QwenLong-L1.5: Post-Training Recipe for Long-Context Reasoning and Memory Management](https://arxiv.org/abs/2512.12967)
- [Scaling Agent Learning via Experience Synthesis](https://arxiv.org/abs/2511.03773)
- [Spatial-SSRL: Enhancing Spatial Understanding via Self-Supervised
  Reinforcement Learning](https://arxiv.org/abs/2510.27606)
- [Scaling Latent Reasoning via Looped Language Models](https://arxiv.org/abs/2510.25741)
- [MR-Align: Meta-Reasoning Informed Factuality Alignment for Large
  Reasoning Models](https://arxiv.org/abs/2510.24794)
- [LoongRL:Reinforcement Learning for Advanced Reasoning over Long Contexts](https://arxiv.org/abs/2510.19363)
- [Chem-R: Learning to Reason as a Chemist](https://arxiv.org/abs/2510.16880)
- [RL makes MLLMs see better than SFT](https://arxiv.org/abs/2510.16333)
- [ERA: Transforming VLMs into Embodied Agents via Embodied Prior Learning
  and Online Reinforcement Learning](https://arxiv.org/abs/2510.12693)
- [Spotlight on Token Perception for Multimodal Reinforcement Learning](https://arxiv.org/abs/2510.09285)
- [Learning to See Before Seeing: Demystifying LLM Visual Priors from
  Language Pre-training](https://arxiv.org/abs/2509.26625)
- [TruthRL: Incentivizing Truthful LLMs via Reinforcement Learning](https://arxiv.org/abs/2509.25760)
- [MemMamba: Rethinking Memory Patterns in State Space Model](https://arxiv.org/abs/2510.03279)
- [Front-Loading Reasoning: The Synergy between Pretraining and
  Post-Training Data](https://arxiv.org/abs/2510.03264)
- [WebSailor-V2: Bridging the Chasm to Proprietary Agents via Synthetic
  Data and Scalable Reinforcement Learning](https://arxiv.org/abs/2509.13305)
- [EchoX: Towards Mitigating Acoustic-Semantic Gap via Echo Training for
  Speech-to-Speech LLMs](https://arxiv.org/abs/2509.09174)
- [Visual Representation Alignment for Multimodal Large Language Models](https://arxiv.org/abs/2509.07979)
- [LMEnt: A Suite for Analyzing Knowledge in Language Models from
  Pretraining Data to Representations](https://arxiv.org/abs/2509.03405)
- [Open Data Synthesis For Deep Research](https://arxiv.org/abs/2509.00375)
- [Think in Games: Learning to Reason in Games via Reinforcement Learning
  with Large Language Models](https://arxiv.org/abs/2508.21365)
- [Beyond Ten Turns: Unlocking Long-Horizon Agentic Search with Large-Scale
  Asynchronous RL](https://arxiv.org/abs/2508.07976)
- [ChemDFM-R: An Chemical Reasoner LLM Enhanced with Atomized Chemical
  Knowledge](https://arxiv.org/abs/2507.21990)
- [The Invisible Leash: Why RLVR May Not Escape Its Origin](https://arxiv.org/abs/2507.14843)
- [A Systematic Analysis of Hybrid Linear Attention](https://arxiv.org/abs/2507.06457)
- [Where to find Grokking in LLM Pretraining? Monitor
  Memorization-to-Generalization without Test](https://arxiv.org/abs/2506.21551)
- [Revisiting Reinforcement Learning for LLM Reasoning from A Cross-Domain
  Perspective](https://arxiv.org/abs/2506.14965)
- [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical
  Understanding and Reasoning](https://arxiv.org/abs/2506.07044)
- [Is Extending Modality The Right Path Towards Omni-Modality?](https://arxiv.org/abs/2506.01872)
- [ProRL: Prolonged Reinforcement Learning Expands Reasoning Boundaries in
  Large Language Models](https://arxiv.org/abs/2505.24864)
- [Fixing Data That Hurts Performance: Cascading LLMs to Relabel Hard
  Negatives for Robust Information Retrieval](https://arxiv.org/abs/2505.16967)
- [Visual Agentic Reinforcement Fine-Tuning](https://arxiv.org/abs/2505.14246)
- [ZeroSearch: Incentivize the Search Capability of LLMs without Searching](https://arxiv.org/abs/2505.04588)
- [Grokking in the Wild: Data Augmentation for Real-World Multi-Hop
  Reasoning with Transformers](https://arxiv.org/abs/2504.20752)
- [Scaling Analysis of Interleaved Speech-Text Language Models](https://arxiv.org/abs/2504.02398)
- [Cosmos-Reason1: From Physical Common Sense To Embodied Reasoning](https://arxiv.org/abs/2503.15558)
- [DeepPerception: Advancing R1-like Cognitive Visual Perception in MLLMs
  for Knowledge-Intensive Visual Grounding](https://arxiv.org/abs/2503.12797)
- [GKG-LLM: A Unified Framework for Generalized Knowledge Graph
  Construction](https://arxiv.org/abs/2503.11227)
- [How Much Knowledge Can You Pack into a LoRA Adapter without Harming LLM?](https://arxiv.org/abs/2502.14502)
- [Mol-LLaMA: Towards General Understanding of Molecules in Large Molecular
  Language Model](https://arxiv.org/abs/2502.13449)
- [LLM Pretraining with Continuous Concepts](https://arxiv.org/abs/2502.08524)
- [LIMO: Less is More for Reasoning](https://arxiv.org/abs/2502.03387)
- [Self-supervised Quantized Representation for Seamlessly Integrating
  Knowledge Graphs with Large Language Models](https://arxiv.org/abs/2501.18119)
- [SFT Memorizes, RL Generalizes: A Comparative Study of Foundation Model
  Post-training](https://arxiv.org/abs/2501.17161)
- [Learn-by-interact: A Data-Centric Framework for Self-Adaptive Agents in
  Realistic Environments](https://arxiv.org/abs/2501.10893)

### 2024

- [Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via
  Collective Monte Carlo Tree Search](https://arxiv.org/abs/2412.18319)
- [Search, Verify and Feedback: Towards Next Generation Post-training
  Paradigm of Foundation Models via Verifier Engineering](https://arxiv.org/abs/2411.11504)
- [What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A
  Gradient Perspective](https://arxiv.org/abs/2410.23743)
- [SemiEvol: Semi-supervised Fine-tuning for LLM Adaptation](https://arxiv.org/abs/2410.14745)
- [Personalized Visual Instruction Tuning](https://arxiv.org/abs/2410.07113)
- [To Code, or Not To Code? Exploring Impact of Code in Pre-training](https://arxiv.org/abs/2408.10914)
- [Improving Text Embeddings for Smaller Language Models Using Contrastive
  Fine-tuning](https://arxiv.org/abs/2408.00690)
- [A Large Encoder-Decoder Family of Foundation Models For Chemical
  Language](https://arxiv.org/abs/2407.20267)
- [VILA^2: VILA Augmented VILA](https://arxiv.org/abs/2407.17453)
- [Data Mixture Inference: What do BPE Tokenizers Reveal about their
  Training Data?](https://arxiv.org/abs/2407.16607)
- [Understanding Alignment in Multimodal LLMs: A Comprehensive Study](https://arxiv.org/abs/2407.02477)
- [The FineWeb Datasets: Decanting the Web for the Finest Text Data at
  Scale](https://arxiv.org/abs/2406.17557)
- [PIN: A Knowledge-Intensive Dataset for Paired and Interleaved Multimodal
  Documents](https://arxiv.org/abs/2406.13923)
- [How Do Large Language Models Acquire Factual Knowledge During
  Pretraining?](https://arxiv.org/abs/2406.11813)
- [3D-GRAND: A Million-Scale Dataset for 3D-LLMs with Better Grounding and
  Less Hallucination](https://arxiv.org/abs/2406.05132)
- [Transformers Can Do Arithmetic with the Right Embeddings](https://arxiv.org/abs/2405.17399)
- [Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to
  the Edge of Generalization](https://arxiv.org/abs/2405.15071)
- [MoRA: High-Rank Updating for Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2405.12130)
- [LoRA Learns Less and Forgets Less](https://arxiv.org/abs/2405.09673)
- [FLAME: Factuality-Aware Alignment for Large Language Models](https://arxiv.org/abs/2405.01525)
- [Make Your LLM Fully Utilize the Context](https://arxiv.org/abs/2404.16811)
- [No "Zero-Shot" Without Exponential Data: Pretraining Concept Frequency
  Determines Multimodal Model Performance](https://arxiv.org/abs/2404.04125)
- [Getting it Right: Improving Spatial Consistency in Text-to-Image Models](https://arxiv.org/abs/2404.01197)
- [Aurora-M: The First Open Source Multilingual Language Model Red-teamed
  according to the U.S. Executive Order](https://arxiv.org/abs/2404.00399)
- [Simple and Scalable Strategies to Continually Pre-train Large Language
  Models](https://arxiv.org/abs/2403.08763)
- [StructLM: Towards Building Generalist Models for Structured Knowledge
  Grounding](https://arxiv.org/abs/2402.16671)
- [Instruction-tuned Language Models are Better Knowledge Learners](https://arxiv.org/abs/2402.12847)
- [Data Engineering for Scaling Language Models to 128K Context](https://arxiv.org/abs/2402.10171)
- [Tag-LLM: Repurposing General-Purpose LLMs for Specialized Domains](https://arxiv.org/abs/2402.05140)
- [Large Language Models are Superpositions of All Characters: Attaining
  Arbitrary Role-play via Self-Alignment](https://arxiv.org/abs/2401.12474)
- [DeepSeekMoE: Towards Ultimate Expert Specialization in
  Mixture-of-Experts Language Models](https://arxiv.org/abs/2401.06066)
- [LLaMA Pro: Progressive LLaMA with Block Expansion](https://arxiv.org/abs/2401.02415)

## 知识表征 (Knowledge Representation)

> 研究知识在模型内部以何种形式存在和组织（存储→激活→行为）：参数化记忆（键值记忆、知识神经元、注意力头、MoE专家、跨层分布）、表征空间（线性表示假说、SAE、残差流分析）、知识电路（电路发现、因果追踪、注意力头协作、单跳/多跳召回回路）。

### 2026

- [Rethinking State Tracking in Recurrent Models Through Error Control Dynamics](https://arxiv.org/abs/2605.07755)
- [Auto-Rubric as Reward: From Implicit Preferences to Explicit Multimodal Generative Criteria](https://arxiv.org/abs/2605.08354)
- [LLM Safety From Within: Detecting Harmful Content with Internal Representations](https://arxiv.org/abs/2604.18519)
- [Maximal Brain Damage Without Data or Optimization: Disrupting Neural Networks via Sign-Bit Flips](https://arxiv.org/abs/2502.07408)
- [Pseudo-Unification: Entropy Probing Reveals Divergent Information Patterns in Unified Multimodal Models](https://arxiv.org/abs/2604.10949)
- [The Geometric Alignment Tax: Tokenization vs. Continuous Geometry in Scientific Foundation Models](https://arxiv.org/abs/2604.04155)
- [Therefore I am. I Think](https://arxiv.org/abs/2604.01202)
- [The Universal Normal Embedding](https://arxiv.org/abs/2603.21786)
- [Are Audio-Language Models Listening? Audio-Specialist Heads for Adaptive Audio Steering](https://arxiv.org/abs/2603.06854)
- [MSA: Memory Sparse Attention for Efficient End-to-End Memory Model Scaling to 100M Tokens](https://arxiv.org/abs/2603.23516)
- [Imagination Helps Visual Reasoning, But Not Yet in Latent Space](https://arxiv.org/abs/2602.22766)
- [Revisiting the Platonic Representation Hypothesis: An Aristotelian View](https://arxiv.org/abs/2602.14486)
- [Sanity Checks for Sparse Autoencoders: Do SAEs Beat Random Baselines?](https://arxiv.org/abs/2602.14111)
- [What does RL improve for Visual Reasoning? A Frankenstein-Style Analysis](https://arxiv.org/abs/2602.12395)
- [Internalizing Meta-Experience into Memory for Guided Reinforcement Learning in Large Language Models](https://arxiv.org/abs/2602.10224)
- [AudioSAE: Towards Understanding of Audio-Processing Models with Sparse AutoEncoders](https://arxiv.org/abs/2602.05027)
- [Why Steering Works: Toward a Unified View of Language Model Parameter Dynamics](https://arxiv.org/abs/2602.02343)
- [Sparse Reward Subsystem in Large Language Models](https://arxiv.org/abs/2602.00986)
- [LatentLens: Revealing Highly Interpretable Visual Tokens in LLMs](https://arxiv.org/abs/2602.00462)
- [Do Reasoning Models Enhance Embedding Models?](https://arxiv.org/abs/2601.21192)
- [Linear representations in language models can change dramatically over a conversation](https://arxiv.org/abs/2601.20834)
- [Locate, Steer, and Improve: A Practical Survey of Actionable Mechanistic Interpretability in Large Language Models](https://arxiv.org/abs/2601.14004)
- [The Illusion of Specialization: Unveiling the Domain-Invariant "Standing Committee" in Mixture-of-Experts Models](https://arxiv.org/abs/2601.03425)
- [KV-Embedding: Training-free Text Embedding via Internal KV Re-routing in Decoder-only LLMs](https://arxiv.org/abs/2601.01046)

### 2025

- [Can LLMs Predict Their Own Failures? Self-Awareness via Internal Circuits](https://arxiv.org/abs/2512.20578)
- [UCoder: Unsupervised Code Generation by Internal Probing of Large Language Models](https://arxiv.org/abs/2512.17385)
- [Flowing Backwards: Improving Normalizing Flows via Reverse Representation Alignment](https://arxiv.org/abs/2511.22345)
- [The Curious Case of Analogies: Investigating Analogical Reasoning in Large Language Models](https://arxiv.org/abs/2511.20344)
- [Where Culture Fades: Revealing the Cultural Gap in Text-to-Image Generation](https://arxiv.org/abs/2511.17282)
- [Unveiling Intrinsic Dimension of Texts: from Academic Abstract to Creative Story](https://arxiv.org/abs/2511.15210)
- [Don't Blind Your VLA: Aligning Visual Representations for OOD
  Generalization](https://arxiv.org/abs/2510.25616)
- [Language Models are Injective and Hence Invertible](https://arxiv.org/abs/2510.15511)
- [TokDrift: When LLM Speaks in Subwords but Code Speaks in Grammar](https://arxiv.org/abs/2510.14972)
- [Reasoning in Space via Grounding in the World](https://arxiv.org/abs/2510.13800)
- [Scaling Language-Centric Omnimodal Representation Learning](https://arxiv.org/abs/2510.11693)
- [Large Language Models Do NOT Really Know What They Don't Know](https://arxiv.org/abs/2510.09033)
- [Which Heads Matter for Reasoning? RL-Guided KV Cache Compression](https://arxiv.org/abs/2510.08525)
- [Memory Retrieval and Consolidation in Large Language Models through
  Function Tokens](https://arxiv.org/abs/2510.08203)
- [GRACE: Generative Representation Learning via Contrastive Policy
  Optimization](https://arxiv.org/abs/2510.04506)
- [Why Can't Transformers Learn Multiplication? Reverse-Engineering Reveals
  Long-Range Dependency Pitfalls](https://arxiv.org/abs/2510.00184)
- [The Dragon Hatchling: The Missing Link between the Transformer and
  Models of the Brain](https://arxiv.org/abs/2509.26507)
- [Understanding Language Prior of LVLMs by Contrasting Chain-of-Embedding](https://arxiv.org/abs/2509.23050)
- [OrtSAE: Orthogonal Sparse Autoencoders Uncover Atomic Features](https://arxiv.org/abs/2509.22033)
- [NER Retriever: Zero-Shot Named Entity Retrieval with Type-Aware
  Embeddings](https://arxiv.org/abs/2509.04011)
- [Beyond Transcription: Mechanistic Interpretability in ASR](https://arxiv.org/abs/2508.15882)
- [Persona Vectors: Monitoring and Controlling Character Traits in Language
  Models](https://arxiv.org/abs/2507.21509)
- [Teach Old SAEs New Domain Tricks with Boosting](https://arxiv.org/abs/2507.12990)
- [On the rankability of visual embeddings](https://arxiv.org/abs/2507.03683)
- [ProtoReasoning: Prototypes as the Foundation for Generalizable Reasoning
  in LLMs](https://arxiv.org/abs/2506.15211)
- [Language Surgery in Multilingual Large Language Models](https://arxiv.org/abs/2506.12450)
- [Resa: Transparent Reasoning Models via SAEs](https://arxiv.org/abs/2506.09967)
- [Large Language Models are Locally Linear Mappings](https://arxiv.org/abs/2505.24293)
- [Train Sparse Autoencoders Efficiently by Utilizing Features Correlation](https://arxiv.org/abs/2505.22255)
- [Let's Predict Sentence by Sentence](https://arxiv.org/abs/2505.22202)
- [What Makes for Text to 360-degree Panorama Generation with Stable
  Diffusion?](https://arxiv.org/abs/2505.22129)
- [How does Alignment Enhance LLMs' Multilingual Capabilities? A Language
  Neurons Perspective](https://arxiv.org/abs/2505.21505)
- [Exploring the Latent Capacity of LLMs for One-Step Text Generation](https://arxiv.org/abs/2505.21189)
- [Beyond Prompt Engineering: Robust Behavior Control in LLMs via Steering
  Target Atoms](https://arxiv.org/abs/2505.20322)
- [Geospatial Mechanistic Interpretability of Large Language Models](https://arxiv.org/abs/2505.03368)
- [Analyzing LLMs' Knowledge Boundary Cognition Across Languages Through
  the Lens of Internal Representations](https://arxiv.org/abs/2504.13816)
- [M3: 3D-Spatial MultiModal Memory](https://arxiv.org/abs/2503.16413)
- [How to Steer LLM Latents for Hallucination Detection?](https://arxiv.org/abs/2503.01917)
- [LLM-Microscope: Uncovering the Hidden Role of Punctuation in Context
  Memory of Transformers](https://arxiv.org/abs/2502.15007)
- [Does Time Have Its Place? Temporal Heads: Where Language Models Recall
  Time-specific Information](https://arxiv.org/abs/2502.14258)
- [MoM: Linear Sequence Modeling with Mixture-of-Memories](https://arxiv.org/abs/2502.13685)
- [SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and
  Object Manipulation](https://arxiv.org/abs/2502.13143)
- [FoNE: Precise Single-Token Number Embeddings via Fourier Features](https://arxiv.org/abs/2502.09741)
- [Can this Model Also Recognize Dogs? Zero-Shot Model Search from Weights](https://arxiv.org/abs/2502.09619)
- [We Can't Understand AI Using our Existing Vocabulary](https://arxiv.org/abs/2502.07586)
- [Linear Correlation in LM's Compositional Generalization and
  Hallucination](https://arxiv.org/abs/2502.04520)
- [ConceptAttention: Diffusion Transformers Learn Highly Interpretable
  Features](https://arxiv.org/abs/2502.04320)
- [Analyze Feature Flow to Enhance Interpretation and Steering in Language
  Models](https://arxiv.org/abs/2502.03032)
- [SliderSpace: Decomposing the Visual Capabilities of Diffusion Models](https://arxiv.org/abs/2502.01639)
- [Concept Steerers: Leveraging K-Sparse Autoencoders for Controllable
  Generations](https://arxiv.org/abs/2501.19066)
- [Enhancing Automated Interpretability with Output-Centric Feature
  Descriptions](https://arxiv.org/abs/2501.08319)

### 2024

- [Frame Representation Hypothesis: Multi-Token LLM Interpretability and
  Concept-Guided Text Generation](https://arxiv.org/abs/2412.07334)
- [Monet: Mixture of Monosemantic Experts for Transformers](https://arxiv.org/abs/2412.04139)
- [Do I Know This Entity? Knowledge Awareness and Hallucinations in
  Language Models](https://arxiv.org/abs/2411.14257)
- [Controlling Language and Diffusion Models by Transporting Activations](https://arxiv.org/abs/2410.23054)
- [Task Vectors are Cross-Modal](https://arxiv.org/abs/2410.22330)
- [Unpacking SDXL Turbo: Interpreting Text-to-Image Models with Sparse
  Autoencoders](https://arxiv.org/abs/2410.22366)
- [Your Mixture-of-Experts LLM Is Secretly an Embedding Model For Free](https://arxiv.org/abs/2410.10814)
- [Attention Heads of Large Language Models: A Survey](https://arxiv.org/abs/2409.03752)
- [SEA: Supervised Embedding Alignment for Token-Level Visual-Textual
  Integration in MLLMs](https://arxiv.org/abs/2408.11813)
- [Towards flexible perception with visual memory](https://arxiv.org/abs/2408.08172)
- [Scaling Diffusion Transformers to 16 Billion Parameters](https://arxiv.org/abs/2407.11633)
- [T-FREE: Tokenizer-Free Generative LLMs via Sparse Representations for
  Memory-Efficient Embeddings](https://arxiv.org/abs/2406.19223)
- [Semantic Entropy Probes: Robust and Cheap Hallucination Detection in
  LLMs](https://arxiv.org/abs/2406.15927)
- [Cognitive Map for Language Models: Optimal Planning via Verbally
  Representing the World Model](https://arxiv.org/abs/2406.15275)
- [Complexity of Symbolic Representation in Working Memory of Transformer
  Correlates with the Complexity of a Task](https://arxiv.org/abs/2406.14213)
- [Interpreting the Weight Space of Customized Diffusion Models](https://arxiv.org/abs/2406.09413)
- [Not All Language Model Features Are Linear](https://arxiv.org/abs/2405.14860)
- [ALPINE: Unveiling the Planning Capability of Autoregressive Learning in
  Language Models](https://arxiv.org/abs/2405.09220)
- [Beyond Scaling Laws: Understanding Transformer Performance with
  Associative Memory](https://arxiv.org/abs/2405.08707)
- [Probing the 3D Awareness of Visual Foundation Models](https://arxiv.org/abs/2404.08636)
- [Localizing Paragraph Memorization in Language Models](https://arxiv.org/abs/2403.19851)
- [The Unreasonable Ineffectiveness of the Deeper Layers](https://arxiv.org/abs/2403.17887)
- [Do Large Language Models Latently Perform Multi-Hop Reasoning?](https://arxiv.org/abs/2402.16837)
- [EmerDiff: Emerging Pixel-level Semantic Knowledge in Diffusion Models](https://arxiv.org/abs/2401.11739)
- [Patchscope: A Unifying Framework for Inspecting Hidden Representations
  of Language Models](https://arxiv.org/abs/2401.06102)

## 知识利用 (Knowledge Utilization)

> 研究模型在推理阶段如何使用知识（召回→增强→冲突）：知识召回（隐式/显式推理、召回失败与幻觉）、知识增强（ICL、RAG、工具使用与Agent、领域知识应用）、知识冲突（冲突类型、仲裁机制、解决方法）。

### 2026

- [δ-mem: Efficient Online Memory for Large Language Models](https://arxiv.org/abs/2605.12357)
- [Do Enterprise Systems Need Learned World Models? The Importance of Context to Infer Dynamics](https://arxiv.org/abs/2605.12178)
- [MemPrivacy: Privacy-Preserving Personalized Memory Management for Edge-Cloud Agents](https://arxiv.org/abs/2605.09530)
- [MiA-Signature: Approximating Global Activation for Long-Context Understanding](https://arxiv.org/abs/2605.06416)
- [OpenSearch-VL: An Open Recipe for Frontier Multimodal Search Agents](https://arxiv.org/abs/2605.05185)
- [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://arxiv.org/abs/2605.03042)
- [From Context to Skills: Can Language Models Learn from Context Skillfully?](https://arxiv.org/abs/2604.27660)
- [Beyond Semantic Similarity: Rethinking Retrieval for Agentic Search via Direct Corpus Interaction](https://arxiv.org/abs/2605.05242)
- [Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering](https://arxiv.org/abs/2604.08224)
- [Act Wisely: Cultivating Meta-Cognitive Tool Use in Agentic Multimodal Models](https://arxiv.org/abs/2604.08545)
- [Memory Intelligence Agent](https://arxiv.org/abs/2604.04503)
- [Unify-Agent: A Unified Multimodal Agent for World-Grounded Image Synthesis](https://arxiv.org/abs/2603.29620)
- [Gen-Searcher: Reinforcing Agentic Search for Image Generation](https://arxiv.org/abs/2603.28767)
- [GEMS: Agent-Native Multimodal Generation with Memory and Skills](https://arxiv.org/abs/2603.28088)
- [Why Does Self-Distillation (Sometimes) Degrade the Reasoning Capability of LLMs?](https://arxiv.org/abs/2603.24472)
- [PersonaVLM: Long-Term Personalized Multimodal LLMs](https://arxiv.org/abs/2604.13074)
- [Memento-Skills: Let Agents Design Agents](https://arxiv.org/abs/2603.18743)
- [TRUST-SQL: Tool-Integrated Multi-Turn Reinforcement Learning for Text-to-SQL over Unknown Schemas](https://arxiv.org/abs/2603.16448)
- [Grounding World Simulation Models in a Real-World Metropolis](https://arxiv.org/abs/2603.15583)
- [Thinking to Recall: How Reasoning Unlocks Parametric Knowledge in LLMs](https://arxiv.org/abs/2603.09906)
- [Thinking in Uncertainty: Mitigating Hallucinations in MLRMs with Latent Entropy-Aware Decoding](https://arxiv.org/abs/2603.13366)
- [In-Context Reinforcement Learning for Tool Use in Large Language Models](https://arxiv.org/abs/2603.08068)
- [DARE: Aligning LLM Agents with the R Statistical Ecosystem via Distribution-Aware Retrieval](https://arxiv.org/abs/2603.04743)
- [SkillNet: Create, Evaluate, and Connect AI Skills](https://arxiv.org/abs/2603.04448)
- [Query-focused and Memory-aware Reranker for Long Context Processing](https://arxiv.org/abs/2602.12192)
- [MARS: Modular Agent with Reflective Search for Automated AI Research](https://arxiv.org/abs/2602.02660)
- [MemSkill: Learning and Evolving Memory Skills for Self-Evolving Agents](https://arxiv.org/abs/2602.02474)
- [UniReason 1.0: A Unified Reasoning Framework for World Knowledge Aligned Image Generation and Editing](https://arxiv.org/abs/2602.02437)
- [FS-Researcher: Test-Time Scaling for Long-Horizon Research Tasks with File-System-Based Agents](https://arxiv.org/abs/2602.01566)
- [Idea2Story: An Automated Pipeline for Transforming Research Concepts into Complete Scientific Narratives](https://arxiv.org/abs/2601.20833)
- [Paper2Rebuttal: A Multi-Agent Framework for Transparent Author Response Assistance](https://arxiv.org/abs/2601.14171)
- [MemGovern: Enhancing Code Agents through Learning from Governed Human Experiences](https://arxiv.org/abs/2601.06789)
- [Chaining the Evidence: Robust Reinforcement Learning for Deep Search Agents with Citation-Aware Rubric Rewards](https://arxiv.org/abs/2601.06021)

### 2025

- [Improving Multi-step RAG with Hypergraph-based Memory for Long-Context Complex Relational Modeling](https://arxiv.org/abs/2512.23959)
- [Mindscape-Aware Retrieval Augmented Generation for Improved Long Context Understanding](https://arxiv.org/abs/2512.17220)
- [Memory in the Age of AI Agents](https://arxiv.org/abs/2512.13564)
- [ARM-Thinker: Reinforcing Multimodal Generative Reward Models with Agentic Tool Use and Visual Reasoning](https://arxiv.org/abs/2512.05111)
- [Wikontic: Constructing Wikidata-Aligned, Ontology-Aware Knowledge Graphs with Large Language Models](https://arxiv.org/abs/2512.00590)
- [Deep Research: A Systematic Survey](https://arxiv.org/abs/2512.02038)
- [General Agentic Memory Via Deep Research](https://arxiv.org/abs/2511.18423)
- [DoPE: Denoising Rotary Position Embedding](https://arxiv.org/abs/2511.09146)
- [Adaptive Multi-Agent Response Refinement in Conversational Systems](https://arxiv.org/abs/2511.08319)
- [IterResearch: Rethinking Long-Horizon Agents via Markovian State
  Reconstruction](https://arxiv.org/abs/2511.07327)
- [GroupRank: A Groupwise Reranking Paradigm Driven by Reinforcement Learning](https://arxiv.org/abs/2511.11653)
- [DeepEyesV2: Toward Agentic Multimodal Model](https://arxiv.org/abs/2511.05271)
- [Tongyi DeepResearch Technical Report](https://arxiv.org/abs/2510.24701)
- [LightMem: Lightweight and Efficient Memory-Augmented Generation](https://arxiv.org/abs/2510.18866)
- [RAG-Anything: All-in-One RAG Framework](https://arxiv.org/abs/2510.12323)
- [When Thoughts Meet Facts: Reusable Reasoning for Long-Context LMs](https://arxiv.org/abs/2510.07499)
- [Agentic Context Engineering: Evolving Contexts for Self-Improving
  Language Models](https://arxiv.org/abs/2510.04618)
- [Fathom-DeepResearch: Unlocking Long Horizon Information Retrieval and
  Synthesis for SLMs](https://arxiv.org/abs/2509.24107)
- [From What to Why: A Multi-Agent System for Evidence-based Chemical
  Reaction Condition Reasoning](https://arxiv.org/abs/2509.23768)
- [ReSum: Unlocking Long-Horizon Search Intelligence via Context
  Summarization](https://arxiv.org/abs/2509.13313)
- [WebWeaver: Structuring Web-Scale Evidence with Dynamic Outlines for
  Open-Ended Deep Research](https://arxiv.org/abs/2509.13312)
- [WebResearcher: Unleashing unbounded reasoning capability in Long-Horizon
  Agents](https://arxiv.org/abs/2509.13309)
- [Paper2Agent: Reimagining Research Papers As Interactive and Reliable AI
  Agents](https://arxiv.org/abs/2509.06917)
- [AgentFly: Fine-tuning LLM Agents without Fine-tuning LLMs](https://arxiv.org/abs/2508.16153)
- [SSRL: Self-Search Reinforcement Learning](https://arxiv.org/abs/2508.10874)
- [ComoRAG: A Cognitive-Inspired Memory-Organized RAG for Stateful Long
  Narrative Reasoning](https://arxiv.org/abs/2508.10419)
- [Is Chain-of-Thought Reasoning of LLMs a Mirage? A Data Distribution Lens](https://arxiv.org/abs/2508.01191)
- [Deep Researcher with Test-Time Diffusion](https://arxiv.org/abs/2507.16075)
- [A Survey of Context Engineering for Large Language Models](https://arxiv.org/abs/2507.13334)
- [Towards Agentic RAG with Deep Reasoning: A Survey of RAG-Reasoning
  Systems in LLMs](https://arxiv.org/abs/2507.09477)
- [Thinking with Images for Multimodal Reasoning: Foundations, Methods, and
  Future Frontiers](https://arxiv.org/abs/2506.23918)
- [MMSearch-R1: Incentivizing LMMs to Search](https://arxiv.org/abs/2506.20670)
- [Xolver: Multi-Agent Reasoning with Holistic Experience Learning Just
  Like an Olympiad Team](https://arxiv.org/abs/2506.14234)
- [DoTA-RAG: Dynamic of Thought Aggregation RAG](https://arxiv.org/abs/2506.12571)
- [Feedback Friction: LLMs Struggle to Fully Incorporate External Feedback](https://arxiv.org/abs/2506.11930)
- [Code Graph Model (CGM): A Graph-Integrated Large Language Model for
  Repository-Level Software Engineering Tasks](https://arxiv.org/abs/2505.16901)
- [WebThinker: Empowering Large Reasoning Models with Deep Research
  Capability](https://arxiv.org/abs/2504.21776)
- [UniversalRAG: Retrieval-Augmented Generation over Multiple Corpora with
  Diverse Modalities and Granularities](https://arxiv.org/abs/2504.20734)
- [ReasonIR: Training Retrievers for Reasoning Tasks](https://arxiv.org/abs/2504.20595)
- [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://arxiv.org/abs/2504.19413)
- [T1: Tool-integrated Self-verification for Test-time Compute Scaling in
  Small Language Models](https://arxiv.org/abs/2504.04718)
- [DeepSeek-R1 Thoughtology: Let's <think> about LLM Reasoning](https://arxiv.org/abs/2504.07128)
- [ScholarCopilot: Training Large Language Models for Academic Writing with
  Accurate Citations](https://arxiv.org/abs/2504.00824)
- [Open Deep Search: Democratizing Search with Open-source Reasoning Agents](https://arxiv.org/abs/2503.20201)
- [Search-R1: Training LLMs to Reason and Leverage Search Engines with
  Reinforcement Learning](https://arxiv.org/abs/2503.09516)
- [HoT: Highlighted Chain of Thought for Referencing Supporting Facts from
  Inputs](https://arxiv.org/abs/2503.02003)
- [Retrieval-augmented Large Language Models for Financial Time Series
  Forecasting](https://arxiv.org/abs/2502.05878)
- [Chain-of-Retrieval Augmented Generation](https://arxiv.org/abs/2501.14342)
- [OmniThink: Expanding Knowledge Boundaries in Machine Writing through
  Thinking](https://arxiv.org/abs/2501.09751)
- [Search-o1: Agentic Search-Enhanced Large Reasoning Models](https://arxiv.org/abs/2501.05366)

### 2024

- [Progressive Multimodal Reasoning via Active Retrieval](https://arxiv.org/abs/2412.14835)
- [Generative World Explorer](https://arxiv.org/abs/2411.11844)
- [Large Language Models Orchestrating Structured Reasoning Achieve Kaggle
  Grandmaster Level](https://arxiv.org/abs/2411.03562)
- [HtmlRAG: HTML is Better Than Plain Text for Modeling Retrieved Knowledge
  in RAG Systems](https://arxiv.org/abs/2411.02959)
- [LLMtimesMapReduce: Simplified Long-Sequence Processing using Large
  Language Models](https://arxiv.org/abs/2410.09342)
- [WALL-E: World Alignment by Rule Learning Improves World Model-based LLM
  Agents](https://arxiv.org/abs/2410.07484)
- [Writing in the Margins: Better Inference Pattern for Long Context
  Retrieval](https://arxiv.org/abs/2408.14906)
- [RAG Foundry: A Framework for Enhancing LLMs for Retrieval Augmented
  Generation](https://arxiv.org/abs/2408.02545)
- [MindSearch: Mimicking Human Minds Elicits Deep AI Searcher](https://arxiv.org/abs/2407.20183)
- [Internal Consistency and Self-Feedback in Large Language Models: A
  Survey](https://arxiv.org/abs/2407.14507)
- [AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge
  Bases](https://arxiv.org/abs/2407.12784)
- [Human-like Episodic Memory for Infinite Context LLMs](https://arxiv.org/abs/2407.09450)
- [LongRAG: Enhancing Retrieval-Augmented Generation with Long-context LLMs](https://arxiv.org/abs/2406.15319)
- [RAFT: Adapting Language Model to Domain Specific RAG](https://arxiv.org/abs/2403.10131)
- [Gemini 1.5: Unlocking multimodal understanding across millions of tokens
  of context](https://arxiv.org/abs/2403.05530)
- [In Search of Needles in a 10M Haystack: Recurrent Memory Finds What LLMs
  Miss](https://arxiv.org/abs/2402.10790)
- [RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval](https://arxiv.org/abs/2401.18059)

## 知识演化 (Knowledge Evolution)

> 研究如何对模型已有知识进行定向修改和更新：知识编辑（Locate-and-Edit、外部记忆方法）、知识遗忘（概念擦除、机器遗忘）、演化副作用与缓解（模型崩溃、能力退化、涟漪效应、灾难性遗忘）。

### 2026

- [Useful Memories Become Faulty When Continuously Updated by LLMs](https://arxiv.org/abs/2605.12978)
- [NanoResearch: Co-Evolving Skills, Memory, and Policy for Personalized Research Automation](https://arxiv.org/abs/2605.10813)
- [Geometry Conflict: Explaining and Controlling Forgetting in LLM Continual Post-Training](https://arxiv.org/abs/2605.09608)
- [SkillOS: Learning Skill Curation for Self-Evolving Agents](https://arxiv.org/abs/2605.06614)
- [Training LLM Agents for Spontaneous, Reward-Free Self-Evolution via World Knowledge Exploration](https://arxiv.org/abs/2604.18131)
- [SkillClaw: Let Skills Evolve Collectively with Agentic Evolver](https://arxiv.org/abs/2604.08377)
- [In-Place Test-Time Training](https://arxiv.org/abs/2604.06169)
- [Can Large Language Models Reinvent Foundational Algorithms?](https://arxiv.org/abs/2604.05716)
- [Brainstacks: Cross-Domain Cognitive Capabilities via Frozen MoE-LoRA Stacks for Continual LLM Learning](https://arxiv.org/abs/2604.01152)
- [REVERE: Reflective Evolving Research Engineer for Scientific Workflows](https://arxiv.org/abs/2603.20667)
- [MetaClaw: Just Talk -- An Agent That Meta-Learns and Evolves in the Wild](https://arxiv.org/abs/2603.17187)
- [Online Experiential Learning for Language Models](https://arxiv.org/abs/2603.16856)
- [Spatial-TTT: Streaming Visual-based Spatial Intelligence with Test-Time Training](https://arxiv.org/abs/2603.12255)
- [PureCC: Pure Learning for Text-to-Image Concept Customization](https://arxiv.org/abs/2603.07561)
- [UMEM: Unified Memory Extraction and Management Framework for Generalizable Memory](https://arxiv.org/abs/2602.10652)
- [SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning](https://arxiv.org/abs/2602.08234)
- [Locas: Your Models are Principled Initializers of Locally-Supported Parametric Memories](https://arxiv.org/abs/2602.05085)
- [Position: Agentic Evolution is the Path to Evolving LLMs](https://arxiv.org/abs/2602.00359)
- [Continual GUI Agents](https://arxiv.org/abs/2601.20732)
- [Yunjue Agent Tech Report: A Fully Reproducible, Zero-Start In-Situ Self-Evolving Agent System for Open-Ended Tasks](https://arxiv.org/abs/2601.18226)
- [Privacy Collapse: Benign Fine-Tuning Can Break Contextual Privacy in Language Models](https://arxiv.org/abs/2601.15220)
- [TwinBrainVLA: Unleashing the Potential of Generalist VLMs for Embodied Tasks via Asymmetric Mixture-of-Transformers](https://arxiv.org/abs/2601.14133)
- [Knowledge is Not Enough: Injecting RL Skills for Continual Adaptation](https://arxiv.org/abs/2601.11258)
- [Evolving Programmatic Skill Networks](https://arxiv.org/abs/2601.03509)

### 2025

- [MemEvolve: Meta-Evolution of Agent Memory Systems](https://arxiv.org/abs/2512.18746)
- [Reinforcement Learning for Self-Improving Agent with Skill Library](https://arxiv.org/abs/2512.17102)
- [Mitigating Catastrophic Forgetting in Target Language Adaptation of LLMs via Source-Shielded Updates](https://arxiv.org/abs/2512.04844)
- [EtCon: Edit-then-Consolidate for Reliable Knowledge Editing](https://arxiv.org/abs/2512.04753)
- [Agentic Learner with Grow-and-Refine Multimodal Semantic Memory](https://arxiv.org/abs/2511.21678)
- [FLEX: Continuous Agent Evolution via Forward Learning from Experience](https://arxiv.org/abs/2511.06449)
- [RECALL: REpresentation-aligned Catastrophic-forgetting ALLeviation via
  Hierarchical Model Merging](https://arxiv.org/abs/2510.20479)
- [KORE: Enhancing Knowledge Injection for Large Multimodal Models via
  Knowledge-Oriented Augmentations and Constraints](https://arxiv.org/abs/2510.19316)
- [ACE: Attribution-Controlled Knowledge Editing for Multi-hop Factual
  Recall](https://arxiv.org/abs/2510.07896)
- [REPAIR: Robust Editing via Progressive Adaptive Intervention and
  Reintegration](https://arxiv.org/abs/2510.01879)
- [Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents](https://arxiv.org/abs/2509.26354)
- [Fine-tuning Done Right in Model Editing](https://arxiv.org/abs/2509.22072)
- [Scrub It Out! Erasing Sensitive Memorization in Code Language Models via
  Machine Unlearning](https://arxiv.org/abs/2509.13755)
- [CRISP: Persistent Concept Unlearning via Sparse Autoencoders](https://arxiv.org/abs/2508.13650)
- [Unlearning Comparator: A Visual Analytics System for Comparative
  Evaluation of Machine Unlearning Methods](https://arxiv.org/abs/2508.12730)
- [GeRe: Towards Efficient Anti-Forgetting in Continual Learning of LLM via
  General Samples Replay](https://arxiv.org/abs/2508.04676)
- [A Survey of Self-Evolving Agents: On Path to Artificial Super
  Intelligence](https://arxiv.org/abs/2507.21046)
- [The Landscape of Memorization in LLMs: Mechanisms, Measurement, and
  Mitigation](https://arxiv.org/abs/2507.05578)
- [MemOS: A Memory OS for AI System](https://arxiv.org/abs/2507.03724)
- [SAMed-2: Selective Memory Enhanced Medical Segment Anything Model](https://arxiv.org/abs/2507.03698)
- [ReCode: Updating Code API Knowledge with Reinforcement Learning](https://arxiv.org/abs/2506.20495)
- [LLM Unlearning Should Be Form-Independent](https://arxiv.org/abs/2506.07795)
- [Adapt before Continual Learning](https://arxiv.org/abs/2506.03956)
- [The Hallucination Tax of Reinforcement Finetuning](https://arxiv.org/abs/2505.13988)
- [Unilogit: Robust Machine Unlearning for LLMs Using Uniform-Target
  Self-Distillation](https://arxiv.org/abs/2505.06027)
- [ZJUKLAB at SemEval-2025 Task 4: Unlearning via Model Merging](https://arxiv.org/abs/2503.21088)
- [CaKE: Circuit-aware Editing Enables Generalizable Knowledge Learners](https://arxiv.org/abs/2503.16356)
- [BiasEdit: Debiasing Stereotyped Language Models via Model Editing](https://arxiv.org/abs/2503.08588)
- [ReLearn: Unlearning via Learning for Large Language Models](https://arxiv.org/abs/2502.11190)
- [Precise Parameter Localization for Textual Generation in Diffusion
  Models](https://arxiv.org/abs/2502.09935)
- [Lifelong Sequential Knowledge Editing without Model Degradation](https://arxiv.org/abs/2502.01636)
- [SAeUron: Interpretable Concept Unlearning in Diffusion Models with
  Sparse Autoencoders](https://arxiv.org/abs/2501.18052)
- [Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks](https://arxiv.org/abs/2501.11733)
- [Control LLM: Controlled Evolution for Intelligence Retention in LLM](https://arxiv.org/abs/2501.10979)

### 2024

- [CLEAR: Character Unlearning in Textual and Visual Modalities](https://arxiv.org/abs/2410.18057)
- [Erasing Conceptual Knowledge from Language Models](https://arxiv.org/abs/2410.02760)
- [CURLoRA: Stable LLM Continual Fine-Tuning and Catastrophic Forgetting
  Mitigation](https://arxiv.org/abs/2408.14572)
- [BRAT: Bonus oRthogonAl Token for Architecture Agnostic Textual Inversion](https://arxiv.org/abs/2408.04785)
- [Knowledge Mechanisms in Large Language Models: A Survey and Perspective](https://arxiv.org/abs/2407.15017)
- [Practical Unlearning for Large Language Models](https://arxiv.org/abs/2407.10223)
- [Learning to Refuse: Towards Mitigating Privacy Risks in LLMs](https://arxiv.org/abs/2407.10058)
- [Safe Unlearning: A Surprisingly Effective and Generalizable Solution to
  Defend Against Jailbreak Attacks](https://arxiv.org/abs/2407.02855)
- [UnUnlearning: Unlearning is not sufficient for content regulation in
  advanced generative AI](https://arxiv.org/abs/2407.00106)
- [Unlocking Continual Learning Abilities in Language Models](https://arxiv.org/abs/2406.17245)
- [In-Context Editing: Learning Knowledge from Self-Induced Distributions](https://arxiv.org/abs/2406.11194)
- [Breaking Boundaries: Investigating the Effects of Model Editing on
  Cross-linguistic Performance](https://arxiv.org/abs/2406.11139)
- [Large Language Model Unlearning via Embedding-Corrupted Prompts](https://arxiv.org/abs/2406.07933)
- [Is Bigger Edit Batch Size Always Better? -- An Empirical Study on Model
  Editing with Llama-3](https://arxiv.org/abs/2405.00664)
- [Larimar: Large Language Models with Episodic Memory Control](https://arxiv.org/abs/2403.11901)
- [A Tale of Tails: Model Collapse as a Change of Scaling Laws](https://arxiv.org/abs/2402.07043)
- [Model Editing with Canonical Examples](https://arxiv.org/abs/2402.06155)
- [Tuning Language Models by Proxy](https://arxiv.org/abs/2401.08565)
- [A Comprehensive Study of Knowledge Editing for Large Language Models](https://arxiv.org/abs/2401.01286)

## 知识迁移 (Knowledge Transfer)

> 研究知识如何在不同实体间传递：跨模型迁移（知识蒸馏）、跨语言迁移、跨模态迁移、跨任务迁移。

### 2026

- [EVOCHAMBER: Test-Time Co-evolution of Multi-Agent System at Individual, Team, and Population Scales](https://arxiv.org/abs/2605.11136)
- [The Many Faces of On-Policy Distillation: Pitfalls, Mechanisms, and Fixes](https://arxiv.org/abs/2605.11182)
- [UniSD: Towards a Unified Self-Distillation Framework for Large Language Models](https://arxiv.org/abs/2605.06597)
- [Turning the TIDE: Cross-Architecture Distillation for Diffusion Large Language Models](https://arxiv.org/abs/2604.26951)
- [Understanding and Enforcing Weight Disentanglement in Task Arithmetic](https://arxiv.org/abs/2604.17078)
- [Memory Transfer Learning: How Memories are Transferred Across Domains in Coding Agents](https://arxiv.org/abs/2604.14004)
- [Rethinking On-Policy Distillation of Large Language Models: Phenomenology, Mechanism, and Recipe](https://arxiv.org/abs/2604.13016)
- [Cross-Tokenizer LLM Distillation through a Byte-Level Interface](https://arxiv.org/abs/2604.07466)
- [The Master Key Hypothesis: Unlocking Cross-Model Capability Transfer via Linear Subspace Alignment](https://arxiv.org/abs/2604.06377)
- [SkillX: Automatically Constructing Skill Knowledge Bases for Agents](https://arxiv.org/abs/2604.04804)
- [Beyond Hard Negatives: The Importance of Score Distribution in Knowledge Distillation for Dense Retrieval](https://arxiv.org/abs/2604.04734)
- [Training a Student Expert via Semi-Supervised Foundation Model Distillation](https://arxiv.org/abs/2604.03841)
- [BidirLM: From Text to Omnimodal Bidirectional Encoders by Adapting and Composing Causal LLMs](https://arxiv.org/abs/2604.02045)
- [A Survey of On-Policy Distillation for Large Language Models](https://arxiv.org/abs/2604.00626)
- [Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills](https://arxiv.org/abs/2603.25158)
- [SpatialBoost: Enhancing Visual Representation through Language-Guided Reasoning](https://arxiv.org/abs/2603.22057)
- [Generation Models Know Space: Unleashing Implicit 3D Priors for Scene Understanding](https://arxiv.org/abs/2603.19235)
- [LLM2Vec-Gen: Generative Embeddings from Large Language Models](https://arxiv.org/abs/2603.10913)
- [Reinforcement-aware Knowledge Distillation for LLM Reasoning](https://arxiv.org/abs/2602.22495)
- [jina-embeddings-v5-text: Task-Targeted Embedding Distillation](https://arxiv.org/abs/2602.15547)
- [Zooming without Zooming: Region-to-Image Distillation for Fine-Grained Multimodal Perception](https://arxiv.org/abs/2602.11858)
- [Privileged Information Distillation for Language Models](https://arxiv.org/abs/2602.04942)
- [Rethinking Selective Knowledge Distillation](https://arxiv.org/abs/2602.01395)
- [OVD: On-policy Verbal Distillation](https://arxiv.org/abs/2601.21968)
- [Which Reasoning Trajectories Teach Students to Reason Better? A Simple Metric of Informative Alignment](https://arxiv.org/abs/2601.14249)
- [LaViT: Aligning Latent Visual Thoughts for Multi-modal Reasoning](https://arxiv.org/abs/2601.10129)

### 2025

- [From Next-Token to Next-Block: A Principled Adaptation Path for Diffusion LLMs](https://arxiv.org/abs/2512.06776)
- [ProPhy: Progressive Physical Alignment for Dynamic World Simulation](https://arxiv.org/abs/2512.05564)
- [MemLoRA: Distilling Expert Adapters for On-Device Memory Systems](https://arxiv.org/abs/2512.04763)
- [Model Merging with Functional Dual Anchors](https://arxiv.org/abs/2510.21223)
- [Directional Reasoning Injection for Fine-Tuning MLLMs](https://arxiv.org/abs/2510.15050)
- [Cache-to-Cache: Direct Semantic Communication Between Large Language
  Models](https://arxiv.org/abs/2510.03215)
- [EmbeddingGemma: Powerful and Lightweight Text Representations](https://arxiv.org/abs/2509.20354)
- [Reasoning Vectors: Transferring Chain-of-Thought Capabilities via Task
  Arithmetic](https://arxiv.org/abs/2509.01363)
- [Rep-MTL: Unleashing the Power of Representation-level Task Saliency for
  Multi-Task Learning](https://arxiv.org/abs/2507.21049)
- [Agent KB: Leveraging Cross-Domain Experience for Agentic Problem Solving](https://arxiv.org/abs/2507.06229)
- [Does Math Reasoning Improve General LLM Capabilities? Understanding
  Transferability of LLM Reasoning](https://arxiv.org/abs/2507.00432)
- [RelationAdapter: Learning and Transferring Visual Relation with
  Diffusion Transformers](https://arxiv.org/abs/2506.02528)
- [Improving Knowledge Distillation Under Unknown Covariate Shift Through
  Confidence-Guided Data Augmentation](https://arxiv.org/abs/2506.02294)
- [Harnessing Negative Signals: Reinforcement Distillation from Teacher
  Data for LLM Reasoning](https://arxiv.org/abs/2505.24850)
- [Cascading Adversarial Bias from Injection to Distillation in Language
  Models](https://arxiv.org/abs/2505.24842)
- [Enabling Flexible Multi-LLM Integration for Scalable Knowledge
  Aggregation](https://arxiv.org/abs/2505.23844)
- [The Quest for Efficient Reasoning: A Data-Centric Benchmark to CoT
  Distillation](https://arxiv.org/abs/2505.18759)
- [Distilling LLM Agent into Small Models with Retrieval and Code Tools](https://arxiv.org/abs/2505.17612)
- [Training-Free Reasoning and Reflection in MLLMs](https://arxiv.org/abs/2505.16151)
- [Not All Correct Answers Are Equal: Why Your Distillation Source Matters](https://arxiv.org/abs/2505.14464)
- [Crosslingual Reasoning through Test-Time Scaling](https://arxiv.org/abs/2505.05408)
- [Breaking the Modality Barrier: Universal Embedding Learning with
  Multimodal LLMs](https://arxiv.org/abs/2504.17432)
- [Trillion 7B Technical Report](https://arxiv.org/abs/2504.15431)
- [Kuwain 1.5B: An Arabic SLM via Language Injection](https://arxiv.org/abs/2504.15120)
- [Antidistillation Sampling](https://arxiv.org/abs/2504.13146)
- [SkillWeaver: Web Agents can Self-Improve by Discovering and Honing
  Skills](https://arxiv.org/abs/2504.07079)
- [Efficient Model Development through Fine-tuning Transfer](https://arxiv.org/abs/2503.20110)
- [Sparse Logit Sampling: Accelerating Knowledge Distillation in LLMs](https://arxiv.org/abs/2503.16870)
- [TinyR1-32B-Preview: Boosting Accuracy with Branch-Merge Distillation](https://arxiv.org/abs/2503.04872)
- [On the Acquisition of Shared Grammatical Representations in Bilingual
  Language Models](https://arxiv.org/abs/2503.03962)
- [The Lottery LLM Hypothesis, Rethinking What Abilities Should LLM
  Compression Preserve?](https://arxiv.org/abs/2502.17535)
- [LLM Modules: Knowledge Transfer from a Large to a Small Model using
  Enhanced Cross-Attention](https://arxiv.org/abs/2502.08213)
- [On Teacher Hacking in Language Model Distillation](https://arxiv.org/abs/2502.02671)
- [Activation-Informed Merging of Large Language Models](https://arxiv.org/abs/2502.02421)
- [TAID: Temporally Adaptive Interpolated Distillation for Efficient
  Knowledge Transfer in Language Models](https://arxiv.org/abs/2501.16937)
- [ARWKV: Pretrain is not what we need, an RNN-Attention-Based Language
  Model Born from Transformer](https://arxiv.org/abs/2501.15570)
- [Virgo: A Preliminary Exploration on Reproducing o1-like MLLM](https://arxiv.org/abs/2501.01904)
- [LUSIFER: Language Universal Space Integration for Enhanced Multilingual
  Embeddings with Large Language Models](https://arxiv.org/abs/2501.00874)

### 2024

- [Facilitating large language model Russian adaptation with Learned
  Embedding Propagation](https://arxiv.org/abs/2412.21140)
- [Chimera: Improving Generalist Model with Domain-Specific Experts](https://arxiv.org/abs/2412.05983)
- [Moto: Latent Motion Token as the Bridging Language for Robot
  Manipulation](https://arxiv.org/abs/2412.04445)
- [O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple
  Distillation, Big Progress or Bitter Lesson?](https://arxiv.org/abs/2411.16489)
- [SAMPart3D: Segment Any Part in 3D Objects](https://arxiv.org/abs/2411.07184)
- [Distill Visual Chart Reasoning Ability from LLMs to MLLMs](https://arxiv.org/abs/2410.18798)
- [MiniPLM: Knowledge Distillation for Pre-Training Language Models](https://arxiv.org/abs/2410.17215)
- [Pre-training Distillation for Large Language Models: A Design Space
  Exploration](https://arxiv.org/abs/2410.16215)
- [IGOR: Image-GOal Representations are the Atomic Control Units for
  Foundation Models in Embodied AI](https://arxiv.org/abs/2411.00785)
- [PHI-S: Distribution Balancing for Label-Free Multi-Teacher Distillation](https://arxiv.org/abs/2410.01680)
- [Selective Aggregation for Low-Rank Adaptation in Federated Learning](https://arxiv.org/abs/2410.01463)
- [Layer Swapping for Zero-Shot Cross-Lingual Transfer in Large Language
  Models](https://arxiv.org/abs/2410.01335)
- [beeFormer: Bridging the Gap Between Semantic and Interaction Similarity
  in Recommender Systems](https://arxiv.org/abs/2409.10309)
- [Leveraging Open Knowledge for Advancing Task Expertise in Large Language
  Models](https://arxiv.org/abs/2408.15915)
- [LLaVA-MoD: Making LLaVA Tiny via MoE Knowledge Distillation](https://arxiv.org/abs/2408.15881)
- [LlamaDuo: LLMOps Pipeline for Seamless Migration from Service LLMs to
  Small-Scale Local LLMs](https://arxiv.org/abs/2408.13467)
- [FuseChat: Knowledge Fusion of Chat Models](https://arxiv.org/abs/2408.07990)
- [Trans-Tokenization and Cross-lingual Vocabulary Transfers: Language
  Adaptation of LLMs for Low-Resource NLP](https://arxiv.org/abs/2408.04303)
- [DDK: Distilling Domain Knowledge for Efficient Large Language Models](https://arxiv.org/abs/2407.16154)
- [Compact Language Models via Pruning and Knowledge Distillation](https://arxiv.org/abs/2407.14679)
- [Training Task Experts through Retrieval Based Distillation](https://arxiv.org/abs/2407.05463)
- [Knowledge Composition using Task Vectors with Learned Anisotropic
  Scaling](https://arxiv.org/abs/2407.02880)
- [DogeRM: Equipping Reward Models with Domain Knowledge through Model
  Merging](https://arxiv.org/abs/2407.01470)
- [Direct Preference Knowledge Distillation for Large Language Models](https://arxiv.org/abs/2406.19774)
- [Aligning Teacher with Student Preferences for Tailored Training Data
  Generation](https://arxiv.org/abs/2406.19227)
- [PLaD: Preference-based Large Language Model Distillation with
  Pseudo-Preference Pairs](https://arxiv.org/abs/2406.02886)
- [Dynamic data sampler for cross-language transfer learning in large
  language models](https://arxiv.org/abs/2405.10626)
- [SambaLingo: Teaching Large Language Models New Languages](https://arxiv.org/abs/2404.05829)
- [Gecko: Versatile Text Embeddings Distilled from Large Language Models](https://arxiv.org/abs/2403.20327)
- [Chart-based Reasoning: Transferring Capabilities from LLMs to VLMs](https://arxiv.org/abs/2403.12596)
- [ELLA: Equip Diffusion Models with LLM for Enhanced Semantic Alignment](https://arxiv.org/abs/2403.05135)
- [FuseChat: Knowledge Fusion of Chat Models](https://arxiv.org/abs/2402.16107)
- [Open-Vocabulary SAM: Segment and Recognize Twenty-thousand Classes
  Interactively](https://arxiv.org/abs/2401.02955)
- [Progressive Knowledge Distillation Of Stable Diffusion XL Using Layer
  Level Loss](https://arxiv.org/abs/2401.02677)
- [Multilingual Instruction Tuning With Just a Pinch of Multilinguality](https://arxiv.org/abs/2401.01854)
- [LLaMA Beyond English: An Empirical Study on Language Capability Transfer](https://arxiv.org/abs/2401.01055)

## 知识评测 (Knowledge Evaluation)

> 研究如何系统地度量和评估模型的知识能力：知识能力评测（MMLU等综合基准、领域知识测试）、知识动态评测（编辑/遗忘后的行为变化、时效性、防污染）、知识利用评测（幻觉检测、事实验证、推理能力）。

### 2026

- [MemEye: A Visual-Centric Evaluation Framework for Multimodal Agent Memory](https://arxiv.org/abs/2605.15128)
- [Rethinking Reasoning-Intensive Retrieval: Evaluating and Advancing Retrievers in Agentic Search Systems](https://arxiv.org/abs/2605.04018)
- [Visual Generation in the New Era: An Evolution from Atomic Mapping to Agentic World Modeling](https://arxiv.org/abs/2604.28185)
- [ReVSI: Rebuilding Visual Spatial Intelligence Evaluation for Accurate Assessment of VLM 3D Reasoning](https://arxiv.org/abs/2604.24300)
- [FORGE:Fine-grained Multimodal Evaluation for Manufacturing Scenarios](https://arxiv.org/abs/2604.07413)
- [How Well Do Agentic Skills Work in the Wild: Benchmarking LLM Skill Usage in Realistic Settings](https://arxiv.org/abs/2604.04323)
- [FileGram: Grounding Agent Personalization in File-System Behavioral Traces](https://arxiv.org/abs/2604.04901)
- [MiroEval: Benchmarking Multimodal Deep Research Agents in Process and Outcome](https://arxiv.org/abs/2603.28407)
- [LIBERO-Para: A Diagnostic Benchmark and Metrics for Paraphrase Robustness in VLA Models](https://arxiv.org/abs/2603.28301)
- [WildWorld: A Large-Scale Dataset for Dynamic World Modeling with Actions and Explicit State toward Generative ARPG](https://arxiv.org/abs/2603.23497)
- [Omni-WorldBench: Towards a Comprehensive Interaction-Centric Evaluation for World Models](https://arxiv.org/abs/2603.22212)
- [LMEB: Long-horizon Memory Embedding Benchmark](https://arxiv.org/abs/2603.12572)
- [Strategic Navigation or Stochastic Search? How Agents and Humans Reason Over Document Collections](https://arxiv.org/abs/2603.12180)
- [Lost in Stories: Consistency Bugs in Long Story Generation by LLMs](https://arxiv.org/abs/2603.05890)
- [T2S-Bench & Structure-of-Thought: Benchmarking and Prompting Comprehensive Text-to-Structure Reasoning](https://arxiv.org/abs/2603.03790)
- [UniG2U-Bench: Do Unified Models Advance Multimodal Understanding?](https://arxiv.org/abs/2603.03241)
- [BeyondSWE: Can Current Code Agent Survive Beyond Single-Repo Bug Fixing?](https://arxiv.org/abs/2603.03194)
- [Enhancing Spatial Understanding in Image Generation via Reward Modeling](https://arxiv.org/abs/2602.24233)
- [The Trinity of Consistency as a Defining Principle for General World Models](https://arxiv.org/abs/2602.23152)
- [SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks](https://arxiv.org/abs/2602.12670)
- [OdysseyArena: Benchmarking Large Language Models For Long-Horizon, Active and Inductive Interactions](https://arxiv.org/abs/2602.05843)
- [WildGraphBench: Benchmarking GraphRAG with Wild-Source Corpora](https://arxiv.org/abs/2602.02053)
- [CAR-bench: Evaluating the Consistency and Limit-Awareness of LLM Agents under Real-World Uncertainty](https://arxiv.org/abs/2601.22027)
- [Everything in Its Place: Benchmarking Spatial Intelligence of Text-to-Image Models](https://arxiv.org/abs/2601.20354)
- [MMDeepResearch-Bench: A Benchmark for Multimodal Deep Research Agents](https://arxiv.org/abs/2601.12346)
- [DeepResearchEval: An Automated Framework for Deep Research Task Construction and Agentic Evaluation](https://arxiv.org/abs/2601.09688)
- [A^3-Bench: Benchmarking Memory-Driven Scientific Reasoning via Anchor and Attractor Activation](https://arxiv.org/abs/2601.09274)
- [KnowMe-Bench: Benchmarking Person Understanding for Lifelong Digital Companions](https://arxiv.org/abs/2601.04745)

### 2025

- [SpatialTree: How Spatial Abilities Branch Out in MLLMs](https://arxiv.org/abs/2512.20617)
- [Probing Scientific General Intelligence of LLMs with Scientist-Aligned Workflows](https://arxiv.org/abs/2512.16969)
- [MMGR: Multi-Modal Generative Reasoning](https://arxiv.org/abs/2512.14691)
- [Finch: Benchmarking Finance & Accounting across Spreadsheet-Centric Enterprise Workflows](https://arxiv.org/abs/2512.13168)
- [How Far Are We from Genuinely Useful Deep Research Agents?](https://arxiv.org/abs/2512.01948)
- [AraLingBench A Human-Annotated Benchmark for Evaluating Arabic Linguistic Capabilities of Large Language Models](https://arxiv.org/abs/2511.14295)
- [WEAVE: Unleashing and Benchmarking the In-context Interleaved Comprehension and Generation](https://arxiv.org/abs/2511.11434)
- [HaluMem: Evaluating Hallucinations in Memory Systems of Agents](https://arxiv.org/abs/2511.03506)
- [InteractComp: Evaluating Search Agents With Ambiguous Queries](https://arxiv.org/abs/2510.24668)
- [UniGenBench++: A Unified Semantic Evaluation Benchmark for Text-to-Image
  Generation](https://arxiv.org/abs/2510.18701)
- [When Models Lie, We Learn: Multilingual Span-Level Hallucination
  Detection with PsiloQA](https://arxiv.org/abs/2510.04849)
- [ReviewScore: Misinformed Peer Review Detection with Large Language
  Models](https://arxiv.org/abs/2509.21679)
- [Symbolic Graphics Programming with Large Language Models](https://arxiv.org/abs/2509.05208)
- [Why Language Models Hallucinate](https://arxiv.org/abs/2509.04664)
- [Inverse IFEval: Can LLMs Unlearn Stubborn Training Conventions to Follow
  Real Instructions?](https://arxiv.org/abs/2509.04292)
- [From Scores to Skills: A Cognitive Diagnosis Framework for Evaluating
  Financial Large Language Models](https://arxiv.org/abs/2508.13491)
- [FutureX: An Advanced Live Benchmark for LLM Agents in Future Prediction](https://arxiv.org/abs/2508.11987)
- [PRELUDE: A Benchmark Designed to Require Global Comprehension and
  Reasoning over Long Contexts](https://arxiv.org/abs/2508.09848)
- [Seeing, Listening, Remembering, and Reasoning: A Multimodal Agent with
  Long-Term Memory](https://arxiv.org/abs/2508.09736)
- [WideSearch: Benchmarking Agentic Broad Info-Seeking](https://arxiv.org/abs/2508.07999)
- [BrowseComp-Plus: A More Fair and Transparent Evaluation Benchmark of
  Deep-Research Agent](https://arxiv.org/abs/2508.06600)
- [DeepPHY: Benchmarking Agentic VLMs on Physical Reasoning](https://arxiv.org/abs/2508.05405)
- [CompassVerifier: A Unified and Robust Verifier for LLMs Evaluation and
  Outcome Reward](https://arxiv.org/abs/2508.03686)
- [Reasoning or Memorization? Unreliable Results of Reinforcement Learning
  Due to Data Contamination](https://arxiv.org/abs/2507.10532)
- [Traceable Evidence Enhanced Visual Grounded Reasoning: Evaluation and
  Methodology](https://arxiv.org/abs/2507.07999)
- [OST-Bench: Evaluating the Capabilities of MLLMs in Online
  Spatio-temporal Scene Understanding](https://arxiv.org/abs/2507.07984)
- [Mind2Web 2: Evaluating Agentic Search with Agent-as-a-Judge](https://arxiv.org/abs/2506.21506)
- [MultiFinBen: A Multilingual, Multimodal, and Difficulty-Aware Benchmark
  for Financial LLM Evaluation](https://arxiv.org/abs/2506.14028)
- [Scientists' First Exam: Probing Cognitive Abilities of MLLM via
  Perception, Understanding, and Reasoning](https://arxiv.org/abs/2506.10521)
- [Geopolitical biases in LLMs: what are the "good" and the "bad" countries
  according to contemporary language models](https://arxiv.org/abs/2506.06751)
- [FinMME: Benchmark Dataset for Financial Multi-Modal Reasoning Evaluation](https://arxiv.org/abs/2505.24714)
- [CSVQA: A Chinese Multimodal Benchmark for Evaluating STEM Reasoning
  Capabilities of VLMs](https://arxiv.org/abs/2505.24120)
- [Will It Still Be True Tomorrow? Multilingual Evergreen Question
  Classification to Improve Trustworthy QA](https://arxiv.org/abs/2505.21115)
- [KRIS-Bench: Benchmarking Next-Level Intelligent Image Editing Models](https://arxiv.org/abs/2505.16707)
- [Embodied Agents Meet Personalization: Exploring Memory Utilization for
  Personalized Assistance](https://arxiv.org/abs/2505.16348)
- [PhyX: Does Your Model Have the "Wits" for Physical Reasoning?](https://arxiv.org/abs/2505.15929)
- [ColorBench: Can VLMs See and Understand the Colorful World? A
  Comprehensive Benchmark for Color Perception, Reasoning, and Robustness](https://arxiv.org/abs/2504.10514)
- [OLMoTrace: Tracing Language Model Outputs Back to Trillions of Training
  Tokens](https://arxiv.org/abs/2504.07096)
- [Have we unified image generation and understanding yet? An empirical
  study of GPT-4o's image generation ability](https://arxiv.org/abs/2504.08003)
- [GPT-ImgEval: A Comprehensive Benchmark for Diagnosing GPT4o in Image
  Generation](https://arxiv.org/abs/2504.02782)
- [Inside-Out: Hidden Factual Knowledge in LLMs](https://arxiv.org/abs/2503.15299)
- [Creation-MMBench: Assessing Context-Aware Creative Intelligence in MLLM](https://arxiv.org/abs/2503.14478)
- [EgoLife: Towards Egocentric Life Assistant](https://arxiv.org/abs/2503.03803)
- [SuperGPQA: Scaling LLM Evaluation across 285 Graduate Disciplines](https://arxiv.org/abs/2502.14739)
- [The Stochastic Parrot on LLM's Shoulder: A Summative Assessment of
  Physical Concept Understanding](https://arxiv.org/abs/2502.08946)
- [Expect the Unexpected: FailSafe Long Context QA for Finance](https://arxiv.org/abs/2502.06329)
- [Humanity's Last Exam](https://arxiv.org/abs/2501.14249)

### 2024

- [On the Compositional Generalization of Multimodal LLMs for Medical
  Imaging](https://arxiv.org/abs/2412.20070)
- [OmniEval: An Omnidirectional and Automatic RAG Evaluation Benchmark in
  Financial Domain](https://arxiv.org/abs/2412.13018)
- [Unraveling the Complexity of Memory in RL Agents: an Approach for
  Classification and Evaluation](https://arxiv.org/abs/2412.06531)
- [M-Longdoc: A Benchmark For Multimodal Super-Long Document Understanding
  And A Retrieval-Aware Tuning Framework](https://arxiv.org/abs/2411.06176)
- [Both Text and Images Leaked! A Systematic Analysis of Multimodal LLM
  Data Contamination](https://arxiv.org/abs/2411.03823)
- [CORAL: Benchmarking Multi-turn Conversational Retrieval-Augmentation
  Generation](https://arxiv.org/abs/2410.23090)
- [Can Knowledge Editing Really Correct Hallucinations?](https://arxiv.org/abs/2410.16251)
- [LOKI: A Comprehensive Synthetic Data Detection Benchmark using Large
  Multimodal Models](https://arxiv.org/abs/2410.09732)
- [Toward General Instruction-Following Alignment for Retrieval-Augmented
  Generation](https://arxiv.org/abs/2410.09584)
- [MMSearch: Benchmarking the Potential of Large Models as Multi-modal
  Search Engines](https://arxiv.org/abs/2409.12959)
- [GroUSE: A Benchmark to Evaluate Evaluators in Grounded Question
  Answering](https://arxiv.org/abs/2409.06595)
- [LongCite: Enabling LLMs to Generate Fine-grained Citations in
  Long-context QA](https://arxiv.org/abs/2409.02897)
- [SWE-bench-java: A GitHub Issue Resolving Benchmark for Java](https://arxiv.org/abs/2408.14354)
- [KAN or MLP: A Fairer Comparison](https://arxiv.org/abs/2407.16674)
- [NeedleBench: Can LLMs Do Retrieval and Reasoning in 1 Million Context
  Window?](https://arxiv.org/abs/2407.11963)
- [Summary of a Haystack: A Challenge to Long-Context LLMs and RAG Systems](https://arxiv.org/abs/2407.01370)
- [Judging the Judges: Evaluating Alignment and Vulnerabilities in
  LLMs-as-Judges](https://arxiv.org/abs/2406.12624)
- [BABILong: Testing the Limits of LLMs with Long Context
  Reasoning-in-a-Haystack](https://arxiv.org/abs/2406.10149)
- [Needle In A Multimodal Haystack](https://arxiv.org/abs/2406.07230)
- [CRAG -- Comprehensive RAG Benchmark](https://arxiv.org/abs/2406.04744)
- [Are We Done with MMLU?](https://arxiv.org/abs/2406.04127)
- [MMLU-Pro: A More Robust and Challenging Multi-Task Language
  Understanding Benchmark](https://arxiv.org/abs/2406.01574)
- [RULER: What's the Real Context Size of Your Long-Context Language
  Models?](https://arxiv.org/abs/2404.06654)
- [MathVerse: Does Your Multi-modal LLM Truly See the Diagrams in Visual
  Math Problems?](https://arxiv.org/abs/2403.14624)
- [Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion
  Tokens](https://arxiv.org/abs/2401.17377)
