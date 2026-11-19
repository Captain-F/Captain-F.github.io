{% comment %}
统一编辑文件。下方“首页章节”的标题和正文对应首页显示内容。
增加章节：添加“## 标题 {#唯一锚点}”，在下面写段落或列表。
删除章节：删除该标题及其正文，直到下一个二级标题之前。
调整顺序：将标题及正文一起移动。
教育经历与论文在文件开头的共享区域编辑。
论文页显示共享论文列表，简历页显示与首页相同的章节。
{% endcomment %}

{% comment %}共享教育经历正文{% endcomment %}
{% capture education_content %}
- Ph.D. in Information Science, 2020.09 – 2024.06<br>
  School of Information Management, Nanjing University
- Visiting Ph.D. student (Funded by CSC), 2022.10 – 2023.10<br>
  Digital Humanities Center, University of Bern
- M.S. in Information Science, 2017.09 – 2020.04<br>
  School of Economics and Management, Nanjing University of Science and Technology
- Bachelor in Information Management and Information Systems, 2013.09 – 2017.06<br>
  School of Economics and Management, China Jiliang University
{% endcapture %}

{% comment %}共享论文正文{% endcomment %}
{% capture publications_content %}
### Journal articles

1. <strong>Fan T</strong>, Wang H. Research of Chinese intangible cultural heritage knowledge graph construction and attribute value extraction with graph attention network[J]. Information Processing & Management, 2022, 59(1): 102753. (SCI/SSCI 1区; 国际信息科学领域权威期刊)
2. <strong>Fan T</strong>, Wang H, Hodel T. α&#124;D&#12297;+β&#124;H&#12297;: Exploration of Quantum Deep Learning on Humanities Data from the Perspective of Digital Humanities[J]. Social Science Computer Review, 2026, OnlineFirst. [DOI: 10.1177/08944393261416783](https://doi.org/10.1177/08944393261416783). (SCI/SSCI 1区; 国际信息科学领域权威期刊)
3. <strong>Fan T</strong>, Wang H, Zhao Y, et al. When MLLMs Meet ICH: A Visual Retrieval-Augmented Generation-based Method for Intangible Cultural Heritage Image Recognition—Take Shadow Puppetry As a Case[J]. Information Processing & Management, 2026, 63(3):104481. (SCI/SSCI 1区; 国际信息科学领域权威期刊)
4. <strong>Fan T</strong>, Wang H, Zhao Y, et al. Multimodal Cultural Heritage Image Recognition Based on Quantum and Classical Multimodal Fusion Network[J]. npj Heritage Science, 14(1), 160, 2026. (SCI/A&HCI 1区; 国际文化遗产领域权威期刊)
5. <strong>Fan T</strong>, Wang H, Deng S. Intangible cultural heritage image classification with multimodal attention and hierarchical fusion[J]. Expert Systems With Applications, 2023, 231:120555. (SCI 1区; IF=7.5; 国际人工智能领域权威期刊)
6. <strong>Fan T</strong>, Wang H, Hodel T. Multimodal knowledge graph construction of Chinese traditional operas and sentiment and genre recognition[J]. Journal of Cultural Heritage, 2023, 62: 32-44. (SCI/A&HCI 1区; 国际文化遗产领域权威期刊)
7. <strong>Fan T</strong>, Wang H, Hodel T. CICHMKG: a large-scale and comprehensive Chinese intangible cultural heritage multimodal knowledge graph[J]. Heritage Science, 2023, 11(1): 1-18.  (SCI/A&HCI 1区; 国际文化遗产领域权威期刊)
8. <strong>Fan T</strong>, Wang H. Multimodal sentiment analysis of intangible cultural heritage songs with strengthened audio features-guided attention[J]. Journal of Information Science, 2024, 50(4): 1063-1081. (SCI/SSCI Q2; 教育部认定的 A 类期刊; FMS B)
9. Zhao Y, Zhang L, Zeng C, Lu W, Chen Y, <strong>Fan T</strong>*. Construction of an aspect-level sentiment analysis model for online medical reviews[J]. Information Processing & Management, 2023, 60(6): 103513. (唯一通讯作者; SCI/SSCI 1区; IF=7.4; 国际信息科学领域权威期刊)
10. <strong>Fan T</strong>, Wang H, Wu P, et al. Multimodal sentiment analysis for social media contents during public emergencies[J]. Journal of Data and Information Science, 2023, 8(3): 61-87.  (CSCD)
11. <strong>范涛</strong>,王昊,陈玥彤. 基于深度迁移学习的地方志多模态命名实体识别研究[J].情报学报, 2022, 41(04):412-423. (国家自然科学基金委管理学部认定的A类期刊; CSSCI; FMS T1 期刊)
12. <strong>范涛</strong>,吴鹏,王昊,凌晨. 基于多模态联合注意力机制的网民情感分析研究[J].情报学报, 2021, 40(6): 656-665. (国家自然科学基金委管理学部认定的A类期刊; CSSCI; FMS T1 期刊)
13. <strong>范涛</strong>,王昊. 基于非遗多模态知识图谱的智能问答模型研究[J].图书馆杂志, 2026. (CSSCI; 已录用)
14. <strong>范涛</strong>, 王昊, 张卫, 李晓敏. 基于机器阅读理解的非遗文本实体抽取研究[J].数据分析与知识发现, 2022, 6(12):70-79. (CSSCI)
15. <strong>范涛</strong>, 王昊, 林克柔, 刘渊晨. 基于视觉的网络舆情事件中网民情感分析研究[J].情报资料工作, 2022, 43(4): 83-91. (CSSCI)
16. <strong>范涛</strong>, 王昊, 李跃艳, 邓三鸿. 基于多模态融合的非遗图片分类研究[J]. 数据分析与知识发现, 2022, 6(2/3): 329-337. (CSSCI)
17. <strong>范涛</strong>, 王昊, 张宝隆. 基于远程监督和深度学习的非物质文化遗产文本属性抽取研究[J]. 情报理论与实践,2021,44(10):1-7+17. (CSSCI)
18. <strong>范涛</strong>, 王昊, 吴鹏. 基于图卷积神经网络和依存句法分析的网民负面情感分析研究[J]. 数据分析与知识发现, 2021, 5(9): 97-106. (CSSCI)
19. <strong>范涛</strong>, 王昊, 郝琳娜, 王诗琴. 基于视频上下文和高维融合的突发事件中网民情感分析研究[J]. 情报科学,2021,39(05):176-183. (CSSCI)
20. <strong>范涛</strong>, 吴鹏, 曹琪. 基于深度学习的多模态融合网民情感识别研究[J]. 信息资源管理学报, 2020, 10(1): 39-48. (CSSCI)
21. 阿德里安·德姆莱特纳,尤金·菲斯特,托拜厄斯·霍德尔,<strong>范涛</strong>*.保存原生性数字文化遗产：电子游戏研究中计算方法的应用及挑战[J].数字人文研究,2025,5(01):38-53.（唯一通讯作者）
22. Shi B, Zheng X, <strong>Fan T</strong>, et al. MSAO: Multi-stage aggregation optimization for knowledge graph embedding[J]. Information Processing & Management, 2026, 63(2): 104467. (SCI/SSCI 1区; 国际信息科学领域权威期刊)
23. Zhou S, Xuan Y, Ao Y, <strong>Fan T</strong>, Wang H. DynKGRAG: A framework for dynamic knowledge graph construction and multi-hop querying over numerical and textual data[J]. Neurocomputing, 2026: 134094. (SCI 1区; 国际人工智能领域权威期刊)
24. Tan Y, Wang H, Zhao Z, <strong>Fan T</strong>. A Joint Entity-Relation Detection and Generalization Method Based on Syntax and Semantics for Chinese Intangible Cultural Heritage Texts[J]. ACM Journal on Computing and Cultural Heritage, 2024, 17(1):1-20. (SCI / A&HCI)
25. 李佩琪, 王昊, 任秋彤, <strong>范涛</strong>. 融合结构特性的语义增强式古籍句读识别方法研究[J]. 情报学报, 2023, 42(2): 150-163. (国家自然科学基金委管理学部认定的A类期刊; CSSCI; FMS T1 期刊)
26. 周凝,闵超,<strong>范涛</strong>,等.基于大语言模型的科学问题自动生成研究[J].现代情报,2026,46(03):3-17. （CSSCI）
27. 黄建伟,任晓晓,<strong>范涛</strong>.GAI技术治理：“奥本海默时刻”如何走出“科林格里奇困境”？——述评与反思[J].行政与法,2026,(01):1-22.
28. 陈锟, 裴雷, <strong>范涛</strong>. 基于多模态融合的突发事件分类研究[J]. 现代情报,2023,43(06):24-34.（CSSCI）
29. 王昊, 龚丽娟, 周泽聿, <strong>范涛</strong>, 王永生. 融合语义增强的社交媒体虚假信息检测方法研究[J]. 数据分析与知识发现, 2023, 7(2): 48-60. (CSSCI)
30. 周泽聿, 王昊, 张小琴, <strong>范涛</strong>, 任秋彤. 基于 Xception-TD 的中华传统刺绣分类模型构建[J]. 数据分析与知识发现, 2022, 6(Z1):338-347. (CSSCI)
31. 张卫, 王昊, 陈玥彤, <strong>范涛</strong>, 邓三鸿. 融合迁移学习与文本增强的中文成语隐喻知识识别与关联研究[J]. 数据分析与知识发现, 2022, 6(Z1):167-183. (CSSCI)
32. 任秋彤, 王昊, 熊欣, <strong>范涛</strong>. 融合 GCN 远距离约束的非遗戏剧术语抽取模型构建及其应用研究[J]. 数据分析与知识发现,2021,5(12):123-136. (CSSCI)
33. 王昊, 邓三鸿, 朱立平, 王鑫芸, <strong>范涛</strong>. 大数据环境下政务数据的情报价值及其利用研究——以海关报关商品归类风险规避为例[J]. 科技情报研究, 2020,2(04):74-89.
{:.publication-list}

### Conference papers

34. <strong>Fan T</strong>, Wang H, Hodel T. Multimodal genre recognition of Chinese operas with hybrid fusion[C]. Digital Humanities, 370-372.（国际数字人文领域重要会议; 作口头汇报）
35. <strong>Fan T</strong>, Wu P, Zhu P. The sentiment recognition of online users based on DNNs multimodal fusion[J]. Proceedings of the Association for Information Science and Technology, 2019, 56(1): 89-97.（国际信息科学国际重要会议; 作口头汇报）
36. Zhou S, Xuan Y, Ao Y, Wang X, <strong>Fan T</strong>, Wang H. MERIT: Multi-Agent Collaboration for Unsupervised Time Series Representation Learning[C]//Findings of the Association for Computational Linguistics: ACL 2025. 2025: 24011-24028. (人工智能权威会议)
37. Zhou S, Ao Y, Xuan Y, Wang X, <strong>Fan T</strong>, Wang H. Inference Scaling Law for Retrieval Augmented Generation[C]//In Proceedings of the AAAI Conference on Artificial Intelligence, 2026, 16522-16530. (人工智能权威会议；CCF-A)
38. Zhou S, Song Y, Leng J, Wang X, <strong>Fan T</strong>, Wang H. Cascaded Verification Framework: A Progressive Approach for Mitigating Hallucinations in Large Language Models[C]//Proceedings of the ACM Web Conference 2026. 2026: 8333-8336. (人工智能权威会议；CCF-A)
39. Zhou S, Song Y, Leng J, Wang X, <strong>Fan T</strong>, Wang H. Activation Caching for Retrieval-Augmented Generation[C]//Proceedings of the ACM Web Conference 2026. 2026: 8341-8344. (人工智能权威会议；CCF-A)
40. Zhou S, Song Y, Leng J, Wang X, <strong>Fan T</strong>, Wang H. Cascaded Verification Framework: A Progressive Approach for Mitigating Hallucinations in Large Language Models[C]//Proceedings of the ACM Web Conference 2026. 2026: 8333-8336. (人工智能权威会议；CCF-A)
{:.publication-list start="34"}
{% endcapture %}

{% comment %}独立论文页章节{% endcomment %}
{% if page.url contains '/publications/' %}

## Publications {#publication}

{{ publications_content }}

{% else %}
{% comment %}首页章节：在本区域增删标题与正文，章节顺序即网页显示顺序{% endcomment %}

## Research interests {#research}

My research focuses on multimodal machine learning and knowledge graphs for digital humanities, particularly the documentation and analysis of intangible cultural heritage. I also work on natural language processing and sentiment analysis.

## Experience {#experience}

- Lecturer, 2024.08 – present<br>
  School of Public Administration, Nanjing University of Finance and Economics
- Associate Researcher, 2023.10 – present<br>
  Digital Humanities Center, University of Bern

## Education {#education}

{{ education_content }}

## Publications {#publication}

{{ publications_content }}

## Research project {#projects}

I lead an NSFC Young Scientists Fund project (72504122, 2026–2028) on building knowledge graphs for intangible cultural heritage using multimodal representation learning.

{% endif %}
