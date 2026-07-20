<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-20
- 运行时间：2026-07-20 21:05:44 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：8
- 速读区：11

### 今日简报（AI）
今日精选19篇长上下文与KV缓存压缩领域论文，核心聚焦无训练变速率压缩及智能体推理的缓存淘汰策略。最值得关注的是满分论文《VarRate》的免训练变速率KV压缩方案和9分《MemDecay》的区域感知缓存淘汰机制，分别攻克大模型长文本效率与智能体长期记忆瓶颈。建议优先精读这两篇，实践中尝试将变速率压缩与区域淘汰策略结合，兼顾精度与推理速度。
- 详情：[/202607/20/README](/202607/20/README)

### 精读区论文标签
1. [VarRate: Training-Free Variable-Rate KV Cache Compression for Long-Context LLMs](/202607/20/2607.15498v1-varrate-training-free-variable-rate-kv-cache-compression-for-long-context-llms)  
   标签：评分：10.0/10、query:evlm
   evidence：长上下文LLM的KV缓存压缩
2. [MemDecay: Region-Aware KV Cache Eviction for Efficient LLM Agent Inference](/202607/20/2607.10582v1-memdecay-region-aware-kv-cache-eviction-for-efficient-llm-agent-inference)  
   标签：评分：9.0/10、query:evlm
   evidence：KV缓存驱逐用于高效LLM智能体推理
3. [Generalizable VLA Finetuning via Representation Anchoring and Language-Action Alignment](/202607/20/2607.13429v1-generalizable-vla-finetuning-via-representation-anchoring-and-language-action-alignment)  
   标签：评分：9.0/10、query:evlm
   evidence：提出Anchor-Align方法防止VLA微调中预训练表征退化
4. [Are All Tokens Necessary for Visual Place Recognition? An Empirical Study of Token Reduction for Efficient Inference](/202607/20/2607.15563v1-are-all-tokens-necessary-for-visual-place-recognition-an-empirical-study-of-token-reduction-for-efficient-inference)  
   标签：评分：9.0/10、query:evlm
   evidence：针对视觉位置识别的token剪枝与合并系统基准测试
5. [GoStop: Reinforcement Learning for Adaptive Temporal Aggregation in Event-Based Feature Tracking](/202607/20/2607.15699v1-gostop-reinforcement-learning-for-adaptive-temporal-aggregation-in-event-based-feature-tracking)  
   标签：评分：9.0/10、query:ev-cam
   evidence：基于事件相机的特征跟踪与自适应时间聚合
6. [Event3R: Asynchronous-to-Global 3D Reconstruction from Event Camera via Spatial-Temporal Feature Aggregation](/202607/20/2607.15727v1-event3r-asynchronous-to-global-3d-reconstruction-from-event-camera-via-spatial-temporal-feature-aggregation)  
   标签：评分：9.0/10、query:ev-cam
   evidence：事件相机3D重建，利用时空特征聚合
7. [On the Geometry of Learned Representations in Event-Based Multi-Modal Egomotion Estimation](/202607/20/2607.15794v1-on-the-geometry-of-learned-representations-in-event-based-multi-modal-egomotion-estimation)  
   标签：评分：9.0/10、query:ev-cam
   evidence：基于事件的视觉和多模态自运动估计，使用事件张量
8. [CLIFE: Camera-LiDAR Fusion Framework for Edge-Deployable Roadside VRU Perception](/202607/20/2607.16154v1-clife-camera-lidar-fusion-framework-for-edge-deployable-roadside-vru-perception)  
   标签：评分：9.0/10、query:mm-trf
   evidence：面向交通场景的路侧VRU感知，边缘部署的相机-激光雷达融合框架

### 速读区论文标签
1. [AVQ-Attention: Adaptive Vector-Quantized Attention](/202607/20/2607.12789v1-avq-attention-adaptive-vector-quantized-attention)  
   标签：评分：8.0/10、query:evlm
   evidence：自适应向量量化注意力以提升Transformer效率
2. [Efficient Frame Selection for Long Videos at Test Time with Attention-Based MLLM Selectors](/202607/20/2607.15689v1-efficient-frame-selection-for-long-videos-at-test-time-with-attention-based-mllm-selectors)  
   标签：评分：8.0/10、query:evlm
   evidence：利用MLLM注意力的高效帧选择，与token选择效率相关
3. [Extending LLM Context via Associative Recurrent Memory](/202607/20/2607.11614v1-extending-llm-context-via-associative-recurrent-memory)  
   标签：评分：7.0/10、query:evlm
   evidence：通过关联递归记忆实现高效长上下文LLM，与高效VLM推理相关
4. [Variational Inference for Bird's Eye View Segmentation in Autonomous Driving](/202607/20/2607.14710v1-variational-inference-for-birds-eye-view-segmentation-in-autonomous-driving)  
   标签：评分：7.0/10、query:mm-trf
   evidence：基于变分推理的自动驾驶鸟瞰图分割
5. [Cache-Aware Prompt Compression:A Two-Tier Cost Model for LLM API Caching](/202607/20/2607.15516v1-cache-aware-prompt-compressiona-two-tier-cost-model-for-llm-api-caching)  
   标签：评分：7.0/10、query:evlm
   evidence：提出提示压缩和缓存的成本模型
6. [Modularized Dynamic-Granularity Video LLM for Multi-Event Long Video Understanding](/202607/20/2607.15778v1-modularized-dynamic-granularity-video-llm-for-multi-event-long-video-understanding)  
   标签：评分：7.0/10、query:evlm
   evidence：模块化动态粒度框架，自适应分配视频LLM中的token预算
7. [PRISA: Proactive Infrastructure LiDAR Framework for Intersection Safety Assessment](/202607/20/2607.16156v1-prisa-proactive-infrastructure-lidar-framework-for-intersection-safety-assessment)  
   标签：评分：7.0/10、query:mm-trf
   evidence：用于交叉口安全评估的基础设施LiDAR框架
8. [DeGuNet: Depth-Guided Ultra-Compact Backbones for Efficient LiDAR-Camera 3D Detection](/202607/20/2607.12419v1-degunet-depth-guided-ultra-compact-backbones-for-efficient-lidar-camera-3d-detection)  
   标签：评分：6.0/10、query:mm-trf
   evidence：面向自动驾驶的LiDAR-相机超紧凑骨干网络
9. [ViCo3D: Empowering LiDAR-based Collaborative 3D Object Detection with Vision Foundation Models](/202607/20/2607.12959v1-vico3d-empowering-lidar-based-collaborative-3d-object-detection-with-vision-foundation-models)  
   标签：评分：6.0/10、query:mm-trf
   evidence：利用视觉基础模型增强交通场景三维目标检测
10. [AdaTurn: Budget-Aware Test-Time Scaling for Active Visual Perception Agents](/202607/20/2607.14547v1-adaturn-budget-aware-test-time-scaling-for-active-visual-perception-agents)  
   标签：评分：6.0/10、query:evlm
   evidence：预算感知测试时缩放，提升主动视觉代理推理效率
11. [SceneBind: Binding What and Where Across Vision, Audio and Language](/202607/20/2607.15265v1-scenebind-binding-what-and-where-across-vision-audio-and-language)  
   标签：评分：6.0/10、query:mm-trf
   evidence：全模态场景表示用于语义-空间理解


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
