# Knowledge Graph Search Engine
##基于知识图谱技术的搜素引擎研发


----------


**项目简介**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;研发基于知识图谱的知识库搜索引擎，该搜索引擎主要包含以下功能模块及研究内容：
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（1）搜索模块：该模块定时的向百度百科，中文本体网等百科类网站执行“网络爬虫”程序，获取百科类网站中的结构化数据。该模块又可以分为网页/数据的爬取解析、清洗、消重（歧）三个小模块。
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（2）图数据库：该模块运用数据挖据能力将散落在互联网上碎片化的知识整合起来，先以“知识卡片”的形式将与关键词相关的知识体系系统化的归纳在一起，然后以“图谱”的形式将含有语义关系的“知识卡片”连接在一起并存储构建成图数据库。
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（3）检索模块：以“语义理解”技术为核心，首先对用户输入的搜索信息进行语义分析，试图理解用户的搜索意图，并将分析结果传入检索库，检索模块根据此结果在知识图谱上进行挖掘，主要的过程包含推理（Reasoning或Inference），实体重要性排序，相关实体挖掘三个过程。最后得出的结果展示到客户端。
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（4）用户交互网站：用户交互网站是用来接纳用户查询，显示查询结果，提供个性化的查询服务的前端显示界面。

