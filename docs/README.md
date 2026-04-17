<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-04-17
- 运行时间：2026-04-17 19:59:54 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日深度解析 17 篇前沿成果，聚焦 Flash Attention 优化与加速器语义自动抽象等底层架构突破。
VFA 通过预计算全局最大值显著缓解向量操作压力，ATLAAS 则实现了张量级硬件语义的自动化建模。
建议关注大模型推理的能效基准与边缘端实时深度伪造检测，探索软硬协同的 AI 落地最优解。
- 详情：[/202604/17/README](/202604/17/README)

### 精读区论文标签
1. [VFA: Relieving Vector Operations in Flash Attention with Global Maximum Pre-computation](/202604/17/2604.12798v1-vfa-relieving-vector-operations-in-flash-attention-with-global-maximum-pre-computation)  
   标签：评分：9.0/10、query:hwnas
   evidence：减少注意力机制内核中矢量受限延迟的硬件友好方法
2. [ATLAAS: Automatic Tensor-Level Abstraction of Accelerator Semantics](/202604/17/2604.13523v1-atlaas-automatic-tensor-level-abstraction-of-accelerator-semantics)  
   标签：评分：9.0/10、query:hwnas
   evidence：从加速器语义自动生成编译器后端
3. [Pushing the Limits of On-Device Streaming ASR: A Compact, High-Accuracy English Model for Low-Latency Inference](/202604/17/2604.14493v1-pushing-the-limits-of-on-device-streaming-asr-a-compact-high-accuracy-english-model-for-low-latency-inference)  
   标签：评分：9.0/10、query:hwnas
   evidence：在资源受限硬件上优化准确度、延迟和内存占用
4. [ELMoE-3D: Leveraging Intrinsic Elasticity of MoE for Hybrid-Bonding-Enabled Self-Speculative Decoding in On-Premises Serving](/202604/17/2604.14626v1-elmoe-3d-leveraging-intrinsic-elasticity-of-moe-for-hybrid-bonding-enabled-self-speculative-decoding-in-on-premises-serving)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对内存受限MoE模型的软硬件协同设计框架
5. [Nautilus: An Auto-Scheduling Tensor Compiler for Efficient Tiled GPU Kernels](/202604/17/2604.14825v1-nautilus-an-auto-scheduling-tensor-compiler-for-efficient-tiled-gpu-kernels)  
   标签：评分：9.0/10、query:hwnas
   evidence：用于GPU算子优化的自动调度张量编译器
6. [Breaking the KV Cache Bottleneck: Fan Duality Model Achieves O(1) Decode Memory with Superior Associative Recall](/202604/17/2604.07716v2-breaking-the-kv-cache-bottleneck-fan-duality-model-achieves-o1-decode-memory-with-superior-associative-recall)  
   标签：评分：8.0/10、query:hwnas
   evidence：序列建模中的O(1)解码内存架构

### 速读区论文标签
1. [DeFakeQ: Enabling Real-Time Deepfake Detection on Edge Devices via Adaptive Bidirectional Quantization](/202604/17/2604.08847v1-defakeq-enabling-real-time-deepfake-detection-on-edge-devices-via-adaptive-bidirectional-quantization)  
   标签：评分：8.0/10、query:hwnas
   evidence：通过量化在资源受限的边缘设备上实现实时推理
2. [Watt Counts: Energy-Aware Benchmark for Sustainable LLM Inference on Heterogeneous GPU Architectures](/202604/17/2604.09048v1-watt-counts-energy-aware-benchmark-for-sustainable-llm-inference-on-heterogeneous-gpu-architectures)  
   标签：评分：8.0/10、query:hwnas
   evidence：异构硬件上LLM推理的能效感知基准测试
3. [FlexVector: A SpMM Vector Processor with Flexible VRF for GCNs on Varying-Sparsity Graphs](/202604/17/2604.10113v1-flexvector-a-spmm-vector-processor-with-flexible-vrf-for-gcns-on-varying-sparsity-graphs)  
   标签：评分：8.0/10、query:hwnas
   evidence：基于向量处理器的GCN推理加速架构
4. [RF-LEGO: Modularized Signal Processing-Deep Learning Co-Design for RF Sensing via Deep Unrolling](/202604/17/2604.10183v1-rf-lego-modularized-signal-processing-deep-learning-co-design-for-rf-sensing-via-deep-unrolling)  
   标签：评分：8.0/10、query:hwnas
   evidence：通过深度展开进行信号处理与深度学习协同设计
5. [AsyncTLS: Efficient Generative LLM Inference with Asynchronous Two-level Sparse Attention](/202604/17/2604.07815v1-asynctls-efficient-generative-llm-inference-with-asynchronous-two-level-sparse-attention)  
   标签：评分：7.0/10、query:hwnas
   evidence：异步卸载引擎将KV缓存传输与计算重叠
6. [Initialisation Determines the Basin: Efficient Codebook Optimisation for Extreme LLM Quantization](/202604/17/2604.08118v1-initialisation-determines-the-basin-efficient-codebook-optimisation-for-extreme-llm-quantization)  
   标签：评分：7.0/10、query:hwnas
   evidence：针对高效边缘部署的极端大模型量化
7. [Alloc-MoE: Budget-Aware Expert Activation Allocation for Efficient Mixture-of-Experts Inference](/202604/17/2604.08133v1-alloc-moe-budget-aware-expert-activation-allocation-for-efficient-mixture-of-experts-inference)  
   标签：评分：7.0/10、query:hwnas
   evidence：资源受限场景下高效推理的预算感知专家激活
8. [FlowEqProp: Training Flow Matching Generative Models with Gradient Equilibrium Propagation](/202604/17/2604.08150v1-floweqprop-training-flow-matching-generative-models-with-gradient-equilibrium-propagation)  
   标签：评分：7.0/10、query:hwnas
   evidence：神经形态实现的硬件可行性
9. [SAT: Balancing Reasoning Accuracy and Efficiency with Stepwise Adaptive Thinking](/202604/17/2604.07922v1-sat-balancing-reasoning-accuracy-and-efficiency-with-stepwise-adaptive-thinking)  
   标签：评分：6.0/10、query:hwnas
   evidence：大推理模型中的逐步自适应剪枝以提高效率
10. [Wattlytics: A Web Platform for Co-Optimizing Performance, Energy, and TCO in HPC Clusters](/202604/17/2604.08182v1-wattlytics-a-web-platform-for-co-optimizing-performance-energy-and-tco-in-hpc-clusters)  
   标签：评分：6.0/10、query:hwnas
   evidence：在GPU加速系统中协同优化性能与能耗
11. [SMC-AI: Scaling Monte Carlo Simulation to Four Trillion Atoms with AI Accelerators](/202604/17/2604.08250v1-smc-ai-scaling-monte-carlo-simulation-to-four-trillion-atoms-with-ai-accelerators)  
   标签：评分：6.0/10、query:hwnas
   evidence：在包括NPU在内的AI加速器上进行高效模拟


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
