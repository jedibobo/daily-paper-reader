<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-09
- 运行时间：2026-05-09 19:56:17 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日聚焦分布式编译与 MoE 推理优化，深度解析 17 篇大模型算力前沿进展。
重点关注 DITRON 编译器对多级分块
- 详情：[/202605/09/README](/202605/09/README)

### 精读区论文标签
1. [DITRON: Distributed Multi-level Tiling Compiler for Parallel Tensor Programs](/202605/09/2605.02953v1-ditron-distributed-multi-level-tiling-compiler-for-parallel-tensor-programs)  
   标签：评分：9.0/10、query:hwnas
   evidence：用于将张量程序映射到异构硬件的分块编译器
2. [Relay Buffer Independent Communication over Pooled HBM for Efficient MoE Inference on Ascend](/202605/09/2605.06055v1-relay-buffer-independent-communication-over-pooled-hbm-for-efficient-moe-inference-on-ascend)  
   标签：评分：9.0/10、query:hwnas
   evidence：昇腾硬件上MoE的内存带宽与通信优化
3. [Efficient, VRAM-Constrained xLM Inference on Clients](/202605/09/2604.26334v1-efficient-vram-constrained-xlm-inference-on-clients)  
   标签：评分：8.0/10、query:hwnas
   evidence：在显存限制下最大化计算利用率的CPU-GPU混合调度
4. [Hierarchical adaptive control for real-time dynamic inference at the edge](/202605/09/2604.26470v1-hierarchical-adaptive-control-for-real-time-dynamic-inference-at-the-edge)  
   标签：评分：8.0/10、query:hwnas
   evidence：针对具有延迟、功耗和内存限制的边缘节点的动态机器学习模型
5. [Combined Dictionary Unfolding Network with Gradient-Adaptive Fidelity for Transferable Multi-Source Fusion](/202605/09/2605.00461v1-combined-dictionary-unfolding-network-with-gradient-adaptive-fidelity-for-transferable-multi-source-fusion)  
   标签：评分：8.0/10、query:hwnas
   evidence：针对资源受限边缘设备的轻量化网络设计
6. [Silicon Showdown: Performance, Efficiency, and Ecosystem Barriers in Consumer-Grade LLM Inference](/202605/09/2605.00519v1-silicon-showdown-performance-efficiency-and-ecosystem-barriers-in-consumer-grade-llm-inference)  
   标签：评分：8.0/10、query:hwnas
   evidence：分析英伟达和苹果芯片上大模型部署的软硬件权衡

### 速读区论文标签
1. [DUAL-BLADE: Dual-Path NVMe-Direct KV-Cache Offloading for Edge LLM Inference](/202605/09/2604.26557v1-dual-blade-dual-path-nvme-direct-kv-cache-offloading-for-edge-llm-inference)  
   标签：评分：8.0/10、query:hwnas
   evidence：针对边缘大模型推理的内存感知KV缓存卸载
2. [FACT: Compositional Kernel Synthesis with a Three-Stage Agentic Workflow](/202605/09/2604.26666v2-fact-compositional-kernel-synthesis-with-a-three-stage-agentic-workflow)  
   标签：评分：8.0/10、query:hwnas
   evidence：深度学习编译器的组合算子内核综合
3. [COPUS: Co-adaptive Parallelism and Batch Size Selection in Large Language Model Training](/202605/09/2604.26687v1-copus-co-adaptive-parallelism-and-batch-size-selection-in-large-language-model-training)  
   标签：评分：8.0/10、query:hwnas
   evidence：协同自适应并行和批大小选择以最大化硬件吞吐量
4. [Edge AI for Automotive Vulnerable Road User Safety: Deployable Detection via Knowledge Distillation](/202605/09/2604.26857v1-edge-ai-for-automotive-vulnerable-road-user-safety-deployable-detection-via-knowledge-distillation)  
   标签：评分：8.0/10、query:hwnas
   evidence：通过知识蒸馏和量化在边缘硬件上部署精确的目标检测
5. [Scalable Learning in Structured Recurrent Spiking Neural Networks without Backpropagation](/202605/09/2605.00402v1-scalable-learning-in-structured-recurrent-spiking-neural-networks-without-backpropagation)  
   标签：评分：7.0/10、query:hwnas
   evidence：具有硬件可扩展性的能效SNN架构
6. [Silicon Showdown: Performance, Efficiency, and Ecosystem Barriers in Consumer-Grade LLM Inference](/202605/09/2605.00519v2-silicon-showdown-performance-efficiency-and-ecosystem-barriers-in-consumer-grade-llm-inference)  
   标签：评分：7.0/10、query:hwnas
   evidence：LLM推理硬件-软件权衡的实证分析
7. [AGoQ: Activation and Gradient Quantization for Memory-Efficient Distributed Training of LLMs](/202605/09/2605.00539v1-agoq-activation-and-gradient-quantization-for-memory-efficient-distributed-training-of-llms)  
   标签：评分：7.0/10、query:hwnas
   evidence：通过层感知量化实现内存高效的分布式训练
8. [Make Your LVLM KV Cache More Lightweight](/202605/09/2605.00789v1-make-your-lvlm-kv-cache-more-lightweight)  
   标签：评分：7.0/10、query:hwnas
   evidence：通过减少KV缓存大小来解决LVLM中的GPU内存开销
9. [Sim-FA: A Simulator Frontend for Asynchronous Pipelines](/202605/09/2605.00555v1-sim-fa-a-simulator-frontend-for-asynchronous-pipelines)  
   标签：评分：6.0/10、query:hwnas
   evidence：针对异步流水线和线程束专业化的模拟器
10. [Sim-FA: A GPGPU Simulator Framework for Fine-Grained FlashAttention Pipeline Analysis](/202605/09/2605.00555v2-sim-fa-a-gpgpu-simulator-framework-for-fine-grained-flashattention-pipeline-analysis)  
   标签：评分：6.0/10、query:hwnas
   evidence：用于细粒度流水线分析和硬件特性的GPGPU模拟器
11. [Hierarchical Federated Learning for Networked AI: From Communication Saving to Architecture-Aware Design](/202605/09/2605.00931v1-hierarchical-federated-learning-for-networked-ai-from-communication-saving-to-architecture-aware-design)  
   标签：评分：6.0/10、query:hwnas
   evidence：网络化AI与联邦学习的架构感知设计


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
