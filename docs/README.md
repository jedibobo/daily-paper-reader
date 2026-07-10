<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-10
- 运行时间：2026-07-10 20:13:08 UTC
- 运行状态：成功
- 本次总论文数：18
- 精读区：7
- 速读区：11

### 今日简报（AI）
今日深度研读 18 篇论文，核心突破集中在大模型推理效率提升与端侧视觉感知。
重点推荐 Akashic 的低开销推理架构与 MiLSD 微型检测器，两者在性能与资源平衡上表现卓越。
建议关注 Apple Silicon 原生加速及 Sub-1-bit KV 缓存量化技术，探索极致的端侧部署可能。
- 详情：[/202607/10/README](/202607/10/README)

### 精读区论文标签
1. [Akashic: A Low-Overhead LLM Inference Service with MemAttention](/202607/10/2607.05708v1-akashic-a-low-overhead-llm-inference-service-with-memattention)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对大模型推理的软硬件协同设计内存布局
2. [MiLSD: A Micro Line-Segment Detector for Resource-Constrained Devices](/202607/10/2607.06600v1-milsd-a-micro-line-segment-detector-for-resource-constrained-devices)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对亚MB级MCU内存约束的微型检测器自动化设计
3. [Smart Scissor: Coupling Spatial Redundancy Reduction and CNN Compression for Embedded Hardware](/202607/10/2607.06915v1-smart-scissor-coupling-spatial-redundancy-reduction-and-cnn-compression-for-embedded-hardware)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对嵌入式硬件的CNN压缩与空间冗余减少
4. [CRIMP: Compact & Reliable DNN Inference on In-Memory Processing via Crossbar-Aligned Compression and Non-ideality Adaptation](/202607/10/2607.08015v1-crimp-compact--reliable-dnn-inference-on-in-memory-processing-via-crossbar-aligned-compression-and-non-ideality-adaptation)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对内存处理的硬件友好型DNN自动设计
5. [Rethinking Small VLM Quantization: From Component-Wise Analysis to Hardware-Aware Edge Deployment](/202607/10/2607.08029v1-rethinking-small-vlm-quantization-from-component-wise-analysis-to-hardware-aware-edge-deployment)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对VLM的硬件感知边缘部署和组件级量化分析
6. [FPGN: Redefining Ultra-Fast Programmable Gate-based Neural Acceleration with Differentiable LUTs](/202607/10/2607.08427v1-fpgn-redefining-ultra-fast-programmable-gate-based-neural-acceleration-with-differentiable-luts)  
   标签：评分：9.0/10、query:hwnas
   evidence：针对FPGA加速器的可微分查找表神经架构搜索
7. [ZipDepth: Bringing Lightweight Zero-Shot Monocular Depth Anywhere, on Any Device](/202607/10/2607.08771v1-zipdepth-bringing-lightweight-zero-shot-monocular-depth-anywhere-on-any-device)  
   标签：评分：9.0/10、query:hwnas
   evidence：适用于移动设备的高效可重参数化编解码器

### 速读区论文标签
1. [BaseRT: Best-in-Class LLM Inference on Apple Silicon via Native Metal](/202607/10/2607.00501v1-basert-best-in-class-llm-inference-on-apple-silicon-via-native-metal)  
   标签：评分：8.0/10、query:hwnas
   evidence：针对Apple Silicon的统一内存感知优化
2. [MosaicKV: Serving Long-Context LLM with Dynamic Two-D KV Cache Compression](/202607/10/2607.00760v1-mosaickv-serving-long-context-llm-with-dynamic-two-d-kv-cache-compression)  
   标签：评分：8.0/10、query:hwnas
   evidence：动态KV缓存压缩以减少GPU显存耗尽
3. [GSRQ: Gain-Shape Residual Quantization for Sub-1-bit KV Cache](/202607/10/2607.01065v1-gsrq-gain-shape-residual-quantization-for-sub-1-bit-kv-cache)  
   标签：评分：8.0/10、query:hwnas
   evidence：用于sub-1-bit KV缓存内存减少的残差量化
4. [Physically-Aware Preemptive Virtual Channels for Deadlock-Free AXI Networks-on-Chip](/202607/10/2607.01430v1-physically-aware-preemptive-virtual-channels-for-deadlock-free-axi-networks-on-chip)  
   标签：评分：8.0/10、query:hwnas
   evidence：维持日益增长的高内存带宽
5. [Mixture-of-Parallelisms: Towards Memory-Efficient Training Stack for Mixture-of-Experts Models](/202607/10/2607.01844v1-mixture-of-parallelisms-towards-memory-efficient-training-stack-for-mixture-of-experts-models)  
   标签：评分：7.0/10、query:hwnas
   evidence：最大化GPU显存和通信带宽利用率的内存高效训练栈
6. [LiZAD: A Lightweight Zero-Shot Anomaly Detection Framework for Industrial Manufacturing](/202607/10/2607.01949v1-lizad-a-lightweight-zero-shot-anomaly-detection-framework-for-industrial-manufacturing)  
   标签：评分：7.0/10、query:hwnas
   evidence：资源受限边缘设备上的实时异常检测轻量级框架
7. [Towards Load-Aware Prefill Deflection for Disaggregated LLM Serving](/202607/10/2607.02043v1-towards-load-aware-prefill-deflection-for-disaggregated-llm-serving)  
   标签：评分：7.0/10、query:hwnas
   evidence：最大化LLM推理集群的计算利用率
8. [Electronic Bursting Neuron: design, equations and hardware implementation](/202607/10/2607.02122v1-electronic-bursting-neuron-design-equations-and-hardware-implementation)  
   标签：评分：7.0/10、query:hwnas
   evidence：脉冲神经网络电子神经元的硬件实现
9. [SCAPE: Accurate and Efficient LLM Training with Extreme Sparse Communication](/202607/10/2607.01678v1-scape-accurate-and-efficient-llm-training-with-extreme-sparse-communication)  
   标签：评分：6.0/10、query:hwnas
   evidence：用于大语言模型训练的通信高效分布式优化器
10. [CamoNAS: Neural Architecture Search for Enhanced Camouflaged Object Detection](/202607/10/2607.01870v1-camonas-neural-architecture-search-for-enhanced-camouflaged-object-detection)  
   标签：评分：6.0/10、query:hwnas
   evidence：针对特定视觉任务的神经网络架构搜索框架
11. [RadiomicNet: A Hybrid Radiomics-Guided Lightweight Architecture for Interpretable Medical Image Segmentation](/202607/10/2607.02185v1-radiomicnet-a-hybrid-radiomics-guided-lightweight-architecture-for-interpretable-medical-image-segmentation)  
   标签：评分：6.0/10、query:hwnas
   evidence：基于MobileNetV2的轻量级架构以减少参数需求


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
