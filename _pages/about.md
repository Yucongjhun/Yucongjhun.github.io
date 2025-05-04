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
喻聪，1989年12月生，博士，<span style="font-weight:bold; color:#E34234;">**副教授（绿色通道晋升）**</span>。近年来，承担了国家自然科学基金、工信部 “互联网+民爆安全生产”试点课题、湖北省重点实验室开放课题、湖北省企校联合创新中心基金等项目，<span style="font-weight:bold; color:#E34234;">**2项研究成果被鉴定为国际先进水平,获中国电力创新奖二等奖1项、能源创新奖二等奖1项**</span>。发表论文30余篇、专利8项、软件著作权3件，代表性论文发表于Energy、Applied Thermal Engineering、中国电机工程学报等国内外权威期刊，担任Energy and AI、Asia-Pacific Journal of Chemical Engineering、Canadian Journal of Chemical Engineering等期刊审稿人，获江汉大学“五四”表彰先进个人等荣誉。<br/>

欢迎感兴趣的同学可加入我们的研究团队，具有机械、能源、自动化、计算机等背景及数值模拟、仿真、编程基础优先考虑。

# 🔥 News
- *2024.12*: &nbsp;🎉🎉与湖北凯龙化工集团股份有限公司合作开发的<b style="color: #000000;">工业互联网+民用爆炸物品生产及仓储智能化安全监控系统</b>被中国工信部鉴定为<span style="font-weight:bold; color:#E34234;">国际先进水平</span>.
- *2024.06*: &nbsp;🎊🎊 <a href="http://news.cnhubei.com/content/2024-06/25/content_18090027.html" target="_blank" rel="noopener">"挺膺担当新征程，逐梦扬帆再起航"</a>相关事迹被学校媒体机构宣传.
- *2024.01*: &nbsp;🎉🎉 Our new journal article, <b style="color: #000000;">*Mechanism-enhanced data-driven method for the joint optimization of boiler combustion and selective catalytic reduction systems considering gas temperature deviations*</b>, Accepted by <span style="font-weight:bold; color:#E34234;">*Energy* (Q1,IF=9)</span>. Reviewers praised its innovative approach and high quality.
- *2023.06*: &nbsp;🎊🎊 Our new journal article, <b style="color: #000000;">*A novel NOx emission prediction model for multimodal operational utility boilers considering local features and prior knowledge*</b> Accepted by <span style="font-weight:bold; color:#E34234;">*Energy* (Q1,IF=9)</span>.

# 📝 Publications 
## 📄 Papers and Conferences
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Energy 2024</div><img src='images/P1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1016/j.energy.2024.130432" target="_blank" rel="noopener">
    Mechanism-enhanced data-driven method for the joint optimization of boiler combustion and selective catalytic reduction systems considering gas temperature deviations
  </a>
</span>

Yukun Zhu, **Cong Yu**📧, Wei Jin📧, Ling Shi, Bo Chen, Pei Xu
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

Shuo Chen, **Cong Yu**📧, Yukun Zhu,Wei Fan, Haiquan Yu, Tihua Zhang
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

Yukun Zhu, **Cong Yu**📧, Wei Fan, Haiquan Yu, Wei Jin, Shuo Chen, Xia Liu
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ATE 2019</div><img src='images/ouhe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1016/j.applthermaleng.2019.03.074" target="_blank" rel="noopener">
    Numerical investigation of combustion optimization in a tangential firing boiler considering steam tube overheating
  </a>
</span>

**Cong Yu**, Wei Xiong, Huan Ma, Jianxin Zhou, Fengqi Si📧, Xiaoming Jiang, Xuwen Fang
{% assign doi = "10.1016/j.applthermaleng.2019.03.074" %}
[**Project**](https://doi.org/10.1016/j.applthermaleng.2019.03.074)｜
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
<span style="font-weight:bold; color:#E34234;">*Applied Thermal Engineering* (Q1,IF=6.1)</span>



- A comprehensive boiler model that coupled the furnace and steam sides was developed.
- A detailed mapping method was provided for the grid systems of different models.
- The effects of the SOFA tilt angle on boiler efficiency and NOx emissions were studied.
- The effects of the SOFA tilt angle on the tube outer surface temperature were studied.
- Combustion optimization was conducted under the constraint of tube overheating.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">中国电机工程学报 2019</div><img src='images/dianjin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size:1.1rem; font-weight:600; line-height:1.3;">
  <a href="https://doi.org/10.1016/j.applthermaleng.2019.03.074" target="_blank" rel="noopener">
	  电站锅炉低氮燃烧与高温受热面换热的联合模拟及分析
  </a>
</span>

**喻聪**; 司风琪; 熊尾; 周建新; 江晓明
{% assign doi = "10.1016/j.applthermaleng.2019.03.074" %}
[**Project**](https://doi.org/10.1016/j.applthermaleng.2019.03.074)｜
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
      {10}
    </span>
  </a>
</span>｜
<span style="font-weight:bold; color:#E34234;">*Applied Thermal Engineering* (Q1,IF=6.1)</span>



- 基于CFD和Matlab平台，建立了超临界切圆锅炉炉内燃烧与高温受热面换热的耦合模型，实现了壁温与热流在风烟侧和汽水侧的迭代计算。
- 针对不同管屏的形状特点，提出了Fluent结构和非结构化网格与Matlab离散微元的映射方法。
- 模拟结果表明，对于660MW超临界锅炉满负荷运行工况，上调SOFA风摆角能降低化学未完全燃烧损失且抑制NOx的生成，但燃尽风在炉内的消旋长度也减小，导致水平烟道烟温偏差和受热面局部高温区面积增加，使高温再热器炉内最高壁温难以始终维持在材料许用温度以内，对机组长期运行的安全性会产生影响。

</div>
</div>

- [Multi-Shadow Scenarios Tennis Ball Detection by an Improved RTMdet-Light Model](https://doi.org/10.1049/ipr2.70054), Yukun Zhu, Yanxia Peng, **Cong Yu**, <span style="font-weight:bold; color:#E34234;">*IET Image Processing (Q3, IF = 2)*</span>, **2025**

- [Quick Combustion Optimization for Utility Boilers Using a Novel Adaptive Hybrid Case Library](https://doi.org/10.3390/pr13020469), **Cong Yu**, Shuo Chen, Haiquan Yu, Yukun Zhu, Qiang Wang, Guangting Liao, Ling Shi, <span style="font-weight:bold; color:#E34234;">*Processes (Q2, IF = 2.8)*</span>, **2025**
- [Dynamic NOx Emission Modeling in a Utility Circulating Fluidized Bed Boiler Considering Denoising and Multi-Frequency Domain Information](https://doi.org/10.3390/en18040790), Qianyu Li, Guanglong Wang, Xian Li, Qing Bao, Wei Li, Yukun Zhu, **Cong Yu**, Huan Ma, <span style="font-weight:bold; color:#E34234;">*Energies (Q3, IF = 3)*</span>, **2025**

- [A Novel End-to-end Framework for A-share Stock Market Portfolio Optimization Considering Risk Measure and Feature Exposure](https://doi.org/10.1145/3698300.3698317), Nanxi Xu, Haotian Xiao, **Yukun Zhu**, Xiaochi Chen, Yixuan Li, Xiaoli Hu, <span style="font-weight:bold; color:#E34234;">*ICBDT (Conference,EI)*</span>, **2024**

- [基于大容量样本挖掘及贝叶斯堆栈泛化集成算法的电站锅炉NOx稳态建模](http://kns.cnki.net/kcms2/article/abstractv=laPQaQ7a6TKeapZz_FqlIie1OfkwCODwsHp_8Z_qVju3L2H0BrVvTznO7XZeWTeqwQyiEGnfqSxqO1nzgV5GxmWF1NVs7_GJVshWzphA-XXiyEg5FuiKpMRkxBD6xb7FSsJXv53FE5ZhfFUVvviYnLczvAimFvesEyS8vjxIWXdcDtHnhDYQ6g==&uniplatform=NZKPT&language=CHS), 朱宇坤, **喻聪**, 张梯华, 刘红娇, 司风琪, <span style="font-weight:bold; color:#E34234;">*热力发电，T1核心期刊*</span>, **2022**

- [机理与数据驱动的电站锅炉SCR催化剂寿命预测模型研究](https://kns.cnki.net/kcms2/article/abstract?v=laPQaQ7a6TLAeW-vG0L65G4CS52Qm9zx41llHh14iMF4Eyb-07LaahGzRO7VjkUSgDYSNiYYX4FkVCJhoeBzUY5-lggp9Wk0XLtrIejQrfM4rCL2F5Aq5IB0DGtcuBQLeZjIeDhEYO_Qqe83XKmwz5Nw5b9g4pcdps07wsiDikX74joRo_LJLw==&uniplatform=NZKPT&language=CHS), 胡佳颖, **喻聪**, 王子良, 司风琪, <span style="font-weight:bold; color:#E34234;">*能源研究与利用*</span>, **2022**

- [基于燃烧与水动力耦合模型的锅炉蒸汽管超温特性研究](https://kns.cnki.net/kcms2/article/abstract?v=laPQaQ7a6TJ5uZAtav2qVAEwyqB1GKRYR1RVnbQBpnSGZd40LYiyxMbdEf-iHnlWDdi1Z63cWjZmAISxlWJ2rv1Z-YTdYbXtD_PPN53aDW2_62OG_Lg8tqIEwPxzWBibddgRn4_i4W8nR0B3pWWL2XWxBli9Ac5IpFx_Vkko9hJjM9oGbalP5Q==&uniplatform=NZKPT&language=CHS), **喻聪**, 司风琪, 李敏, 吴翰林, <span style="font-weight:bold; color:#E34234;">*热能动力工程*</span>, **2021**

- [Numerical study of combustion and heat transfer in a composite heat carrier generator](https://iopscience.iop.org/article/10.1088/1742-6596/2085/1/012035), **Cong Yu**, Ling Shi, Jiangying Hu, Hongjiao Liu, <span style="font-weight:bold; color:#E34234;">*ISPECE,EI Conference*</span>, **2021**

- [Sensitivity analysis of several operational parameters on gas temperature deviation in a tangential firing boiler](https://www.e3s-conferences.org/articles/e3sconf/abs/2020/54/e3sconf_icaeer2020_01022/e3sconf_icaeer2020_01022.html), **Cong Yu**, Haiquan Yu, Wenpeng Hu, Hanlin Wu, <span style="font-weight:bold; color:#E34234;">*E3S Web of Conferences. EDP Sciences*</span>, **2020**

- [A machine learning NOx emission model for SCR system considering mechanism knowledge and catalyst deactivation](https://www.e3s-conferences.org/articles/e3sconf/abs/2020/54/e3sconf_icaeer2020_04064/e3sconf_icaeer2020_04064.html), Cong Yu, Wei Fan, Haiquan Yu, Fengqi Si, <span style="font-weight:bold; color:#E34234;">*E3S Web of Conferences. EDP Sciences*</span>, **2020**

- [燃煤电站SCR系统气固流动与催化剂磨损的混合数值模拟与优化](https://kns.cnki.net/kcms2/article/abstract?v=laPQaQ7a6TLEv7ly-bv56jWwAJqT3YN9FuOdqBBC9LvtizfslU6MGgxvaf8e6KT4HEP4JwJX-wyeC0O3n7Gv9G_tZiLagiGxsjctZMjW4Dh5bbQoGkG2nIvskRzjA05_FBcXyqs80KTkAZEze220FAw73mg-40vX46_YPxSW0dMvgvAJSVFTHg==&uniplatform=NZKPT&language=CHS), **喻聪**，司风琪，董云山，江晓明, <span style="font-weight:bold; color:#E34234;">*东南大学学报（自然科学版）*</span>, **2019**

- [Experimental and numerical predictions of ash particle erosion in SCR monolithic catalysts for coal-fired utility boilers](https://link.springer.com/article/10.1007/s11814-017-0001-9),  **Cong Yu**, Fengqi Si, Shaojun Ren, Xiaoming Jiang,  <span style="font-weight:bold; color:#E34234;">*Korean Journal of Chemical Engineering (Q2,IF=3)*</span>, **2017**



## 🧑‍🔬 Patents and Softwares
- [A method for online diagnosis of combustion performance in power plant boilers considering mode migration and subspace prior knowledge](https://patents.google.com/patent/CN115495976A/zh?oq=CN115495976A),**Cong Yu**, Yukun Zhu, Shuo Chen, Tihua Zhang.(<span style="font-weight:bold; color:#E34234;">*Chinese Patent, CN115495976A*</span>, **2022**)

- [A method for constructing a set of probabilities for deactivation of SCR catalyst in power plant considering local operational habits and coal quality influences](https://patents.google.com/patent/CN115455809A/zh?oq=CN115455809A), **Cong Yu**, Tihua Zhang, Yukun Zhu, Xiangyun Meng, Fang Hu.(<span style="font-weight:bold; color:#E34234;">*Chinese Patent, CN115455809A*</span>, **2022**)

- [A method for predicting the deactivation rate of SCR denitration catalyst considering coupled wear deformation and heterogeneous reaction](https://patents.google.com/patent/CN115458084A/zh?oq=CN115458084A), **Cong Yu**, Haojie Cui, Jing Cheng, Zuyun Liu, Yukun Zhu.(<span style="font-weight:bold; color:#E34234;">*Chinese Patent, CN115458084A*</span>, **2022**)

- Power Plant SCR Denitration System High-Capacity Sample Mining and Catalyst Life Prediction Software V1.0, **Cong Yu**, Ziliang Wang, Yukun Zhu, Tihua Zhang, Shuo Chen.(<span style="font-weight:bold; color:#E34234;">*Software*</span>, **2022**)

# 🎖 Research Projects
- 企业项目（湖北中烟工业有限责任公司武汉卷烟厂）：基于二维码的卷烟质量追溯能力提升的研究与应用, <span style="font-weight:bold; color:#E34234;">*主持人*</span>，2024.08-2025.10，在研
- 东南大学外委项目：循环流化床锅炉燃烧过程数值模拟平台开发及试验测试分析，<span style="font-weight:bold; color:#E34234;">*主持人*</span>，2024.08-2025.12，在研
- 企业项目（湖北凯龙化工集团股份有限公司）：工业互联网+民用爆炸物品生产及仓储智能化安全监控系统，<span style="font-weight:bold; color:#E34234;">*联络人*</span>，2023.06-2026.06，结题<span style="font-weight:bold; color:#E34234;">*(工信部鉴定, 国际领先水平，排名 3/15)*</span>
- 工业烟尘污染控制湖北省重点实验室开放课题（重点项目）：物理启发机器学习助力深调燃煤锅炉氮氧化物迁移行为预测与调控，<span style="font-weight:bold; color:#E34234;">*主持人*</span>，2023.09-2025.08，结题；
- 湖北省环保型汽车油管智能制造企校联合创新中心基金：基于层析成像的高温炉精准光学测温技术及其数字化平台研发，<span style="font-weight:bold; color:#E34234;">*主持人*</span>，2022.8-2025.12，结题；
-  国家自然科学基金：煤粉富氧燃烧锅炉火焰稳定性与蒸发受热管热力特性的耦合机制研究，<span style="font-weight:bold; color:#E34234;">*主持人*</span>，2021.1-2023.12，结题；
-  江汉大学高层次人才科研项目：数据与机理融合驱动的燃煤电站脱硝催化剂寿命预测模型研究，<span style="font-weight:bold; color:#E34234;">*主持人*</span>，2021.1-2023.12，结题；
-  2017年，中国能源研究会能源创新奖二等奖1项，中国电力企业联合会电力创新奖二等奖1项

# 🎖 Honors and Awards


# 📖 Educations
- *2024.11 - 至今*，江汉大学，智能制造学院，副教授
- *2019.11 - 2024.11*，江汉大学，智能制造学院，讲师
- *2019.07 - 2019.11*，中南电力设计院有限公司，发电公司，研究员
- *2012.09 - 2019.06*, 东南大学，动力工程及工程热物理,硕(博)士
- *2008.09 - 2012.06*, 江汉大学，过程装备与控制工程，学士

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->