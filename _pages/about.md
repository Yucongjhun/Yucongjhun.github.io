---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🥰 Welcome!
喻聪，1989年12月生，博士，<span style="font-weight:bold; color:#E34234;">**副教授（绿色通道晋升）**</span>。近年来，承担了国家自然科学基金、工信部 “互联网+民爆安全生产”试点课题、湖北省重点实验室开放课题、湖北省企校联合创新中心基金等项目，<span style="font-weight:bold; color:#E34234;">**2项研究成果被鉴定为国际先进水平,获中国电力创新奖二等奖1项、能源创新奖二等奖1项**</span>。发表论文30余篇、专利8项、软件著作权3件，代表性论文发表于Energy、Applied Thermal Engineering、中国电机工程学报等国内外权威期刊，担任Energy and AI、Asia-Pacific Journal of Chemical Engineering、Canadian Journal of Chemical Engineering等期刊审稿人，获江汉大学“五四”表彰先进个人等荣誉。
欢迎感兴趣的同学可加入我们的研究团队，具有机械、能源、自动化、计算机等背景及数值模拟、仿真、编程基础优先考虑。

# 🔥 News
- *2024.12*: &nbsp;🎉🎉与湖北凯龙化工集团股份有限公司合作开发的<b style="color: #000000;">工业互联网+民用爆炸物品生产及仓储智能化安全监控系统</b>被中国工信部鉴定为<span style="font-weight:bold; color:#E34234;">国际先进水平</span>.
- *2024.06*: &nbsp;🎊🎊 <a href="http://news.cnhubei.com/content/2024-06/25/content_18090027.html" target="_blank" rel="noopener">"挺膺担当新征程，逐梦扬帆再起航"</a>相关事迹被学校媒体机构宣传.
- *2024.01*: &nbsp;🎉🎉 Our new journal article, <b style="color: #000000;">*Mechanism-enhanced data-driven method for the joint optimization of boiler combustion and selective catalytic reduction systems considering gas temperature deviations*</b>, Accepted by <span style="font-weight:bold; color:#E34234;">*Energy* (Q1,IF=9)</span>. Reviewers praised its innovative approach and high quality.
- *2023.06*: &nbsp;🎊🎊 Our new journal article, <b style="color: #000000;">*A novel NOx emission prediction model for multimodal operational utility boilers considering local features and prior knowledge*</b> Accepted by <span style="font-weight:bold; color:#E34234;">*Energy* (Q1,IF=9)</span>.

# 📝 Publications 
## 📄 Papers and Conferences
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FRL 2025</div><img src='images/P5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1016/j.frl.2025.107196" target="_blank" rel="noopener">
    Does multi-scale GARCH information enhance volatility prediction?
  </a>
</span>
Rentian Yu, Haotian Xiao, **Yukun Zhu**, Gongqiu Zhang📧
{% assign doi = "10.1016/j.frl.2025.107196" %}
[**Project**](https://doi.org/10.1016/j.frl.2025.107196)｜
<span class="project-with-badge">
  <a class="gs-citation-badge disabled"
     href="https://scholar.google.com/scholar?cites={{ doi }}"
     target="_blank"
     rel="noopener">
    <span class="gs-badge-left">
      <span class="gs-emoji" aria-hidden="true">🎓️</span>
      <span class="gs-badge-text">Citations</span>
    </span>
    <span class="gs-badge-right">
      {{ site.data.ss_data[doi] | default: 0 }}
    </span>
  </a>
</span>｜
<span style="font-weight:bold; color:#E34234;">*Finance Research Letters* (Q1,IF=7.4)</span>

- We integrate GARCH information with a multi-scale network for volatility prediction.
- The GENSHIN outperforms other deep learning models for Chinese volatility indices.
- The results highlight the multi-scale information in improving volatility prediction.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACS OMEGA 2024</div><img src='images/P4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1021/acsomega.4c05009" target="_blank" rel="noopener">
    Forecast of NOx Emissions for a 660MW Coal-Fired Boiler with Multilayered Gradient Boosting Decision Tree Considering Multiple Operating Modes
  </a>
</span>

Ziwei Wang, Yongzan Zhou, **Yukun Zhu**, Haiquan Yu, Wei Fan📧
{% assign doi = "10.1021/acsomega.4c05009" %}
[**Project**](https://doi.org/10.1021/acsomega.4c05009)｜
<span class="project-with-badge">
  <a class="gs-citation-badge disabled"
     href="https://scholar.google.com/scholar?cites={{ doi }}"
     target="_blank"
     rel="noopener">
    <span class="gs-badge-left">
      <span class="gs-emoji" aria-hidden="true">🎓️</span>
      <span class="gs-badge-text">Citations</span>
    </span>
    <span class="gs-badge-right">
      {{ site.data.ss_data[doi] | default: 0 }}
    </span>
  </a>
</span>｜
<span style="font-weight:bold; color:#E34234;">*ACS OMEGA* (Q2,IF=3.7)</span>

- **Feature extraction & fusion**: Use KICA to remove nonlinear correlations, then fuse independent components with key physics-based variables.
- **Multimode segmentation**: Apply RGMM to identify distinct boiler operating modes and split data accordingly.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Energy 2024</div><img src='images/P1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1016/j.energy.2024.130432" target="_blank" rel="noopener">
    Mechanism-enhanced data-driven method for the joint optimization of boiler combustion and selective catalytic reduction systems considering gas temperature deviations
  </a>
</span>

**Yukun Zhu**, Cong Yu📧, Wei Jin📧, Ling Shi, Bo Chen, Pei Xu
{% assign doi = "10.1016/j.energy.2024.130432" %}
[**Project**](https://doi.org/10.1016/j.energy.2024.130432)｜
<span class="project-with-badge">
  <a class="gs-citation-badge disabled"
     href="https://scholar.google.com/scholar?cites={{ doi }}"
     target="_blank"
     rel="noopener">
    <span class="gs-badge-left">
      <span class="gs-emoji" aria-hidden="true">🎓️</span>
      <span class="gs-badge-text">Citations</span>
    </span>
    <span class="gs-badge-right">
      {{ site.data.ss_data[doi] | default: 0 }}
    </span>
  </a>
</span>｜
<span style="font-weight:bold; color:#E34234;">*Energy* (Q1,IF=9)</span>

- A novel framework was proposed for the joint optimization of boiler subsystems.
- Mechanism relationships were integrated into the data-driven characteristic models.
- Effect of incorporating prior knowledge on modeling and optimization was validated.
- A trade-off between eliminating gas temperature deviation and reducing NOx was found.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JTICE 2023</div><img src='images/P3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1016/j.jtice.2023.105252" target="_blank" rel="noopener">
    NOx formation model for utility boilers using robust two-step steady-state detection and multimodal residual convolutional auto-encoder
  </a>
</span>

Shuo Chen, Cong Yu📧, **Yukun Zhu**,Wei Fan, Haiquan Yu, Tihua Zhang
{% assign doi = "10.1016/j.jtice.2023.105252" %}
[**Project**](https://doi.org/10.1016/j.jtice.2023.105252)｜
<span class="project-with-badge">
  <a class="gs-citation-badge disabled"
     href="https://scholar.google.com/scholar?cites={{ doi }}"
     target="_blank"
     rel="noopener">
    <span class="gs-badge-left">
      <span class="gs-emoji" aria-hidden="true">🎓️</span>
      <span class="gs-badge-text">Citations</span>
    </span>
    <span class="gs-badge-right">
      {{ site.data.ss_data[doi] | default: 0 }}
    </span>
  </a>
</span>｜
<span style="font-weight:bold; color:#E34234;">*Journal of the Taiwan Institute of Chemical Engineers* (Q1,IF=5.5)</span>



- A novel data-driven NOx modelling framework towards peak-shaving utility boilers was proposed.
- A robust two-step steady-state detection approach was proposed to obtain high-quality steady-state training samples from the operational data.
- A multimodal residual convolutional auto-encoder was developed to learn the particular data distribution and feature contributions of each operating mode.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Energy 2023</div><img src='images/P2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1016/j.energy.2023.128128" target="_blank" rel="noopener">
      A novel NOx emission prediction model for multimodal operational utility boilers considering local features and prior knowledge
  </a>
</span>

**Yukun Zhu**, Cong Yu📧, Wei Fan, Haiquan Yu, Wei Jin, Shuo Chen, Xia Liu
{% assign doi = "10.1016/j.energy.2023.128128" %}
[**Project**](https://doi.org/10.1016/j.energy.2023.128128)｜
<span class="project-with-badge">
  <a class="gs-citation-badge disabled"
     href="https://scholar.google.com/scholar?cites={{ doi }}"
     target="_blank"
     rel="noopener">
    <span class="gs-badge-left">
      <span class="gs-emoji" aria-hidden="true">🎓️</span>
      <span class="gs-badge-text">Citations</span>
    </span>
    <span class="gs-badge-right">
      {{ site.data.ss_data[doi] | default: 0 }}
    </span>
  </a>
</span>｜
<span style="font-weight:bold; color:#E34234;">*Energy* (Q1,IF=9)</span>



- The monotonous LightGBM model fits better and presents a more stable performance in the single factor variation experiment than the model without prior information.
- The robust multivariate steady-state algorithm can effectively reduce the impacts of outliers and accurately distinguish the boundaries between the steady-state interval and the non-steady-state interval

</div>
</div>

- [Multi-Shadow Scenarios Tennis Ball Detection by an Improved RTMdet-Light Model](https://doi.org/10.1049/ipr2.70054), **Yukun Zhu**, Yanxia Peng, Cong Yu, <span style="font-weight:bold; color:#E34234;">*IET Image Processing (Q3, IF = 2)*</span>, **2025**

- [Quick Combustion Optimization for Utility Boilers Using a Novel Adaptive Hybrid Case Library](https://doi.org/10.3390/pr13020469), Cong Yu, Shuo Chen, Haiquan Yu, **Yukun Zhu**, Qiang Wang, Guangting Liao, Ling Shi, <span style="font-weight:bold; color:#E34234;">*Processes (Q2, IF = 2.8)*</span>, **2025**
- [Dynamic NOx Emission Modeling in a Utility Circulating Fluidized Bed Boiler Considering Denoising and Multi-Frequency Domain Information](https://doi.org/10.3390/en18040790), Qianyu Li, Guanglong Wang, Xian Li, Qing Bao, Wei Li, **Yukun Zhu**, Cong Yu, Huan Ma, <span style="font-weight:bold; color:#E34234;">*Energies (Q3, IF = 3)*</span>, **2025**

- [A Novel End-to-end Framework for A-share Stock Market Portfolio Optimization Considering Risk Measure and Feature Exposure](https://doi.org/10.1145/3698300.3698317), Nanxi Xu, Haotian Xiao, **Yukun Zhu**, Xiaochi Chen, Yixuan Li, Xiaoli Hu, <span style="font-weight:bold; color:#E34234;">*ICBDT (Conference,EI)*</span>, **2024**

- [基于BO-WT-VMD组合模型的钢丝绳的损伤信号降噪方法](https://kns.cnki.net/kcms2/article/abstract?v=laPQaQ7a6TLR7oJIP8Kmnjfkwn535lXocem97IdO397VrEP1BrAr2McElKl5JY_H5X35J4XlxPf1RY4CqrR1JUhomYm55p9a1vXLj11xHhU3CEPCBnW1VtMGByhKU6llbRKQCOOiqxmzAs6uL_JQTTL4q-PSY0wvWjSyVKWFe30zXyGaWGM47A==&uniplatform=NZKPT&language=CHS), **朱宇坤**，黎恒，吴文俊，柯圆圆, <span style="font-weight:bold; color:#E34234;">*江汉大学学报(自然科学版)*</span>, **2024**

- [基于可解释性的多模型融合的古代玻璃成分分析及亚分类方法](https://kns.cnki.net/kcms2/article/abstract?v=laPQaQ7a6TLMUbW0k_U8nda6dU4fmSyRTCg6rk2jsGwz6GGiJ1UxDQpVvmHbEQKzcV-jKegukWtolZPE8-skXxgM2ZxZuH49qSsCQkxEq6qD-eeDRBXHJbo69E-ITxx1PQHXTY6mWq7TEX5u4UMDPUB1rHCMuhXCBDZKeuJSyumCOi31TaRhQQ==&uniplatform=NZKPT&language=CHS), 汤思远, 黎恒，邱诗睿，**朱宇坤**, 柯圆圆, <span style="font-weight:bold; color:#E34234;">*江汉大学学报(自然科学版)*</span>, **2024**

- [基于熵权-TOPSIS-DE模型对生产类原材料采购问题的研究](https://kns.cnki.net/kcms2/article/abstract?v=laPQaQ7a6TL9t8tzu88drtWW781FCijuNN7TbBbry4XcN-FGXrfDoSjCEMp0pv0xFL8aIqyUy7EeCzClaF_cmG8kVTnbfwtF9fulQ2J4c8Jo6qnzHfQH0nBbk9VFhV5gflTnPJJGNtlcPUfVFRdHIH6WzuueLMML-jpDBk6xD4ojzkhJk5lnlQ==&uniplatform=NZKPT&language=CHS), **朱宇坤**, 黎恒, 梁怡恬, 熊昕, <span style="font-weight:bold; color:#E34234;">*江汉大学学报(自然科学版)*</span>, **2023**

- [基于大容量样本挖掘及贝叶斯堆栈泛化集成算法的电站锅炉NOx稳态建模](http://kns.cnki.net/kcms2/article/abstractv=laPQaQ7a6TKeapZz_FqlIie1OfkwCODwsHp_8Z_qVju3L2H0BrVvTznO7XZeWTeqwQyiEGnfqSxqO1nzgV5GxmWF1NVs7_GJVshWzphA-XXiyEg5FuiKpMRkxBD6xb7FSsJXv53FE5ZhfFUVvviYnLczvAimFvesEyS8vjxIWXdcDtHnhDYQ6g==&uniplatform=NZKPT&language=CHS), **朱宇坤**, 喻聪, 张梯华, 刘红娇, 司风琪, <span style="font-weight:bold; color:#E34234;">*热力发电，中国T1核心期刊*</span>, **2022**

## 🧑‍🔬 Patents and Softwares
- [A method for online diagnosis of combustion performance in power plant boilers considering mode migration and subspace prior knowledge](https://patents.google.com/patent/CN115495976A/zh?oq=CN115495976A),Cong Yu, **Yukun Zhu**, Shuo Chen, Tihua Zhang.(<span style="font-weight:bold; color:#E34234;">*Chinese Patent, CN115495976A*</span>, **2022**)

- [A method for constructing a set of probabilities for deactivation of SCR catalyst in power plant considering local operational habits and coal quality influences](https://patents.google.com/patent/CN115455809A/zh?oq=CN115455809A), Cong Yu, Tihua Zhang, **Yukun Zhu**, Xiangyun Meng, Fang Hu.(<span style="font-weight:bold; color:#E34234;">*Chinese Patent, CN115455809A*</span>, **2022**)

- [A method for predicting the deactivation rate of SCR denitration catalyst considering coupled wear deformation and heterogeneous reaction](https://patents.google.com/patent/CN115458084A/zh?oq=CN115458084A), Cong Yu, Haojie Cui, Jing Cheng, Zuyun Liu, **Yukun Zhu**.(<span style="font-weight:bold; color:#E34234;">*Chinese Patent, CN115458084A*</span>, **2022**)

- Power Plant SCR Denitration System High-Capacity Sample Mining and Catalyst Life Prediction Software V1.0, Cong Yu, Ziliang Wang, **Yukun Zhu**, Tihua Zhang, Shuo Chen.(<span style="font-weight:bold; color:#E34234;">*Software*</span>, **2022**)

# 🎖 Research Projects
- 企业项目（湖北中烟工业有限责任公司武汉卷烟厂）：基于二维码的卷烟质量追溯能力提升的研究与应用, <span style="font-weight:bold; color:#E34234;">*核心成员*</span>，2024.08-2025.10，在研
- 东南大学外委项目：循环流化床锅炉燃烧过程数值模拟平台开发及试验测试分析，<span style="font-weight:bold; color:#E34234;">*核心成员*</span>，2024.08-2025.12，在研
- 企业项目（湖北凯龙化工集团股份有限公司）：工业互联网+民用爆炸物品生产及仓储智能化安全监控系统，<span style="font-weight:bold; color:#E34234;">*核心成员*</span>，2023.06-2026.06，结题<span style="font-weight:bold; color:#E34234;">*(工信部鉴定, 国际领先水平)*</span>
- 工业烟尘污染控制湖北省重点实验室开放课题（重点项目）：物理启发机器学习助力深调燃煤锅炉氮氧化物迁移行为预测与调控，<span style="font-weight:bold; color:#E34234;">*核心成员*</span>，2023.09-2025.08，结题；
- 湖北省环保型汽车油管智能制造企校联合创新中心基金：基于层析成像的高温炉精准光学测温技术及其数字化平台研发，<span style="font-weight:bold; color:#E34234;">*核心成员*</span>，2022.8-2025.12，结题；
-  国家自然科学基金：煤粉富氧燃烧锅炉火焰稳定性与蒸发受热管热力特性的耦合机制研究，<span style="font-weight:bold; color:#E34234;">*核心成员*</span>，2021.1-2023.12，结题；
-  江汉大学高层次人才科研项目：数据与机理融合驱动的燃煤电站脱硝催化剂寿命预测模型研究，<span style="font-weight:bold; color:#E34234;">*核心成员*</span>，2021.1-2023.12，结题；

# 🎖 Honors and Awards


# 📖 Educations
- *2025.04 - 2025 (now)*, MScR of Digital Conmmunications, University of Edinburgh
- *2020.09 - 2024.06*, Bachelor of Process Equipment & Control Engineering, Jianghan University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->