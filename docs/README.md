<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-07
- 运行时间：2026-08-07 01:34:25 UTC
- 运行状态：成功
- 本次总论文数：14
- 精读区：3
- 速读区：11

### 今日简报（AI）
今日精读聚焦流体物理与生成模型交叉前沿，重点分析卫星洪水合成及湍流降阶预测两篇高分论文；速读则覆盖流匹配分位数耦合、扩散模型KL散度与反射扩散边界学习。最值得关注的是将物理一致性融入扩散生成框架（FlowForm）以及结合本征正交分解的湍流预测新范式。建议普通读者优先浏览洪水合成与湍流建模两篇精读，感受物理先验如何提升AI生成可靠性。
- 详情：[/202608/07/README](/202608/07/README)

### 精读区论文标签
1. [FlowForm: Synergizing Fluid Physics with Topological Consistency for Satellite Flood Synthesis](/202608/07/2608.03822v1-flowform-synergizing-fluid-physics-with-topological-consistency-for-satellite-flood-synthesis)  
   标签：评分：9.0/10、query:genmod-fluid
   evidence：基于扩散的生成模型，利用浅水方程正则化合成卫星洪水影像
2. [A hybrid proper orthogonal decomposition and diffusion framework for reduced-order forecasting of turbulent flow dynamics](/202608/07/2608.04728v1-a-hybrid-proper-orthogonal-decomposition-and-diffusion-framework-for-reduced-order-forecasting-of-turbulent-flow-dynamics)  
   标签：评分：9.0/10、query:genmod-fluid
   evidence：显式将扩散生成模型用于湍流预测与降阶建模，直接对应流体动力学中的扩散模型应用。
3. [Multimodal Spatiotemporal Atmospheric Data Assimilation with Latent Flow-matching](/202608/07/2608.05103v1-multimodal-spatiotemporal-atmospheric-data-assimilation-with-latent-flow-matching)  
   标签：评分：9.0/10、query:genmod-fluid
   evidence：利用隐空间流匹配进行大气数据同化，将流匹配方法应用于流体动力学问题

### 速读区论文标签
1. [One-Sided Quantile Coupling for Flow Matching](/202608/07/2608.00978v1-one-sided-quantile-coupling-for-flow-matching)  
   标签：评分：7.0/10、query:genmod-fluid
   evidence：通用的流匹配耦合方法，可应用于流体流动生成
2. [A Unified Kullback--Leibler Divergence Analysis of Generative Diffusion Models via Entropy Production Rate](/202608/07/2608.02406v1-a-unified-kullback--leibler-divergence-analysis-of-generative-diffusion-models-via-entropy-production-rate)  
   标签：评分：7.0/10、query:genmod-fluid
   evidence：生成扩散模型的统一误差分析，改进分数近似与离散化
3. [Should the Boundary Term Be Learned in Reflected Diffusion? Conormal Trace and Reflection Masking](/202608/07/2608.03469v1-should-the-boundary-term-be-learned-in-reflected-diffusion-conormal-trace-and-reflection-masking)  
   标签：评分：7.0/10、query:genmod-fluid
   evidence：有界域反射扩散的分数学习，对带边界约束的基于分数的生成模型直接可用
4. [Existence-Field Diffusion Model for Spatial Point Processes with Variable Cardinality](/202608/07/2607.26428v1-existence-field-diffusion-model-for-spatial-point-processes-with-variable-cardinality)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：面向可变基数点过程的存在场扩散模型，可迁移至基于粒子的流体模拟
5. [Flow Matching with Missing Data](/202608/07/2607.28698v1-flow-matching-with-missing-data)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：将流匹配推广至缺失数据场景，适用于流体数据不完整的情况
6. [WaiT for the Signal: Simple Frequency-Aware Flow-Matching](/202608/07/2607.28760v1-wait-for-the-signal-simple-frequency-aware-flow-matching)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：提出频率感知的流匹配生成方法，可应用于多尺度流动合成。
7. [Safe Vision Language Action Models via Barrier Enhanced Flow Matching](/202608/07/2607.29569v1-safe-vision-language-action-models-via-barrier-enhanced-flow-matching)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：势垒增强的流匹配提供安全保证的生成，可迁移到约束感知的流体流动生成中
8. [SPARE: Structural Parameter-Free Affinity Regularization for Flow Matching](/202608/07/2608.01990v1-spare-structural-parameter-free-affinity-regularization-for-flow-matching)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：无参数的结构正则化加速流匹配训练，对流体流动生成模型有用
9. [Computational and Statistical Guarantees of the \textit{c}-Rectified flow](/202608/07/2608.02487v1-computational-and-statistical-guarantees-of-the-textitc-rectified-flow)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：为整流流（一种流匹配方法）提供计算与统计保证，强化了流匹配用于流体模拟的理论基础。
10. [Discretization and Statistical Consistency of Functional Flow Matching](/202608/07/2608.04531v1-discretization-and-statistical-consistency-of-functional-flow-matching)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：关于函数流匹配的理论一致性分析，方法可直接迁移到流体流动生成
11. [Rethinking Pixel Mean Flows via Interval Denoiser](/202608/07/2608.04818v1-rethinking-pixel-mean-flows-via-interval-denoiser)  
   标签：评分：6.0/10、query:genmod-fluid
   evidence：用于流匹配ODE的通用区间去噪器，可改进流体流动图像的无潜在生成建模


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
