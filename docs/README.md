<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-15
- 运行时间：2026-05-15 20:26:25 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日深挖 LLM 底层性能极限，重点解析了超越硬件峰值的矩阵乘法与专家级 CUDA 优化基准。
核心结论指出 FalconGEMM 可通过降低复杂度突破算力天花板，且 Apple 芯片上的 int4 KV 缓存已能跑赢 fp16。
建议开发者关注低比特量化与 MoE 硬件加速通信，这是提升端侧及多卡推理效率的关键。
- 详情：[/202605/15/README](/202605/15/README)

### 精读区论文标签
1. [FalconGEMM: Surpassing Hardware Peaks with Lower-Complexity Matrix Multiplication](/202605/15/2605.06057v2-falcongemm-surpassing-hardware-peaks-with-lower-complexity-matrix-multiplication)  
   标签：评分：9.0/10、query:hwnas
   evidence：通过性能模型最大化片上数据复用并选择最优算法
2. [CUDAHercules: Benchmarking Hardware-Aware Expert-level CUDA Optimization for LLMs](/202605/15/2605.08467v1-cudahercules-benchmarking-hardware-aware-expert-level-cuda-optimization-for-llms)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对大模型的架构感知CUDA优化基准测试
3. [Evolving Layer-Specific Scalar Functions for Hardware-Aware Transformer Adaptation](/202605/15/2605.14047v1-evolving-layer-specific-scalar-functions-for-hardware-aware-transformer-adaptation)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对边缘部署演化层特定标量函数的硬件感知框架
4. [A Hardware-Aware, Per-Layer Methodology for Post-Training Quantization of Large Language Models](/202605/15/2605.14929v1-a-hardware-aware-per-layer-methodology-for-post-training-quantization-of-large-language-models)  
   标签：评分：9.0/10、query:hwnas
   evidence：硬件感知的逐层量化和硬件高效的查找表格式
5. [Piper: Efficient Large-Scale MoE Training via Resource Modeling and Pipelined Hybrid Parallelism](/202605/15/2605.05049v1-piper-efficient-large-scale-moe-training-via-resource-modeling-and-pipelined-hybrid-parallelism)  
   标签：评分：8.0/10、query:hwnas
   evidence：针对计算和通信需求的资源建模
6. [EdgeServing: Deadline-Aware Multi-DNN Serving at the Edge](/202605/15/2605.05527v1-edgeserving-deadline-aware-multi-dnn-serving-at-the-edge)  
   标签：评分：8.0/10、query:hwnas
   evidence：边缘端多DNN服务及早退机制

### 速读区论文标签
1. [When Quantization Is Free: An int4 KV Cache That Outruns fp16 on Apple Silicon](/202605/15/2605.05699v1-when-quantization-is-free-an-int4-kv-cache-that-outruns-fp16-on-apple-silicon)  
   标签：评分：8.0/10、query:hwnas
   evidence：通过Apple Silicon上的int4 KV缓存进行内存带宽优化
2. [HCInfer: An Efficient Inference System via Error Compensation for Resource-Constrained Devices](/202605/15/2605.05819v1-hcinfer-an-efficient-inference-system-via-error-compensation-for-resource-constrained-devices)  
   标签：评分：8.0/10、query:hwnas
   evidence：针对资源受限设备的异构推理系统
3. [MoE-Hub: Taming Software Complexity for Seamless MoE Overlap with Hardware-Accelerated Communication on Multi-GPU Systems](/202605/15/2605.05888v1-moe-hub-taming-software-complexity-for-seamless-moe-overlap-with-hardware-accelerated-communication-on-multi-gpu-systems)  
   标签：评分：8.0/10、query:hwnas
   evidence：多GPU系统上的硬件加速通信
4. [VisMMOE: Exploiting Visual-Expert Affinity for Efficient Visual-Language MoE Offloading](/202605/15/2605.05899v1-vismmoe-exploiting-visual-expert-affinity-for-efficient-visual-language-moe-offloading)  
   标签：评分：8.0/10、query:hwnas
   evidence：内存受限的卸载与专家需求重塑
5. [Efficient event-driven retrieval in high-capacity kernel Hopfield networks](/202605/15/2605.05978v1-efficient-event-driven-retrieval-in-high-capacity-kernel-hopfield-networks)  
   标签：评分：7.0/10、query:hwnas
   evidence：针对神经形态硬件部署的能效检索优化
6. [Efficient event-driven retrieval in high-capacity kernel Hopfield networks](/202605/15/2605.05978v2-efficient-event-driven-retrieval-in-high-capacity-kernel-hopfield-networks)  
   标签：评分：7.0/10、query:hwnas
   evidence：神经形态硬件上的能效部署
7. [FluxShard: Motion-Aware Feature Cache Reuse for Collaborative Video Analytics in Mobile Edge Computing](/202605/15/2605.06027v1-fluxshard-motion-aware-feature-cache-reuse-for-collaborative-video-analytics-in-mobile-edge-computing)  
   标签：评分：7.0/10、query:hwnas
   evidence：移动边缘计算与视频分析中的特征缓存复用
8. [Normalized Architectures are Natively 4-Bit](/202605/15/2605.06067v1-normalized-architectures-are-natively-4-bit)  
   标签：评分：7.0/10、query:hwnas
   evidence：针对大模型4比特精度效率的架构设计
9. [Adding Thermal Awareness to Visual Systems in Real-Time via Distilled Diffusion Models](/202605/15/2605.06010v1-adding-thermal-awareness-to-visual-systems-in-real-time-via-distilled-diffusion-models)  
   标签：评分：6.0/10、query:hwnas
   evidence：专为低延迟边缘部署设计的实时图像融合模块
10. [Light-FMP: Lightweight Feature and Model Pruning for Enhanced Deep Recommender Systems](/202605/15/2605.06441v1-light-fmp-lightweight-feature-and-model-pruning-for-enhanced-deep-recommender-systems)  
   标签：评分：6.0/10、query:hwnas
   evidence：推荐系统中提高计算效率的轻量级模型剪枝
11. [CCL-Bench 1.0: A Trace-Based Benchmark for LLM Infrastructure](/202605/15/2605.06544v1-ccl-bench-10-a-trace-based-benchmark-for-llm-infrastructure)  
   标签：评分：6.0/10、query:hwnas
   evidence：针对硬件加速器和软件框架的计算性能基准测试


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
