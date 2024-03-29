---
{"dg-publish":true,"permalink":"/产品知识库/产品经理怎么用好 Prompt/","noteIcon":"","created":"2023-08-26T16:39:04.027+08:00"}
---


第一次使用前先了解：[[学习笔记/简单入门 Prompt\|简单入门 Prompt]]，本文都是基于该入门教程深入应用

以下内容来自[1个Prompt框架+4个公式，讲清产品经理如何用ChatGPT让工作效率翻倍](https://www.woshipm.com/pmd/5802132.html)，我会再根据自己工作实战，继续补充

### 撰写文案文档
可用来写产品说明、推广文案、用户手册、项目申报材料、市场调研报告、竞品分析报告、PRD文档等等

==prompt 框架==
>【**背景**：产品/项目介绍】+
>【**指令**：撰写/修改 + 文案/文档类型】+
>【**输入数据**：模仿对象内容/修改内容（可选）】+
>【**输出指示**：关于主题/产品的要点 + 结构/字数等】

🌰以写产品说明文档为例，假设要做一个在线教育平台，可以这么提问：
>我要做一个在线教育平台（背景），请写一篇产品说明文档（指令），核心功能包括在线课程、实时答疑、学习社群，按照介绍、功能、优势三个部分组织内容，不超过1000字（输出指示）

### 协助竞品分析
==prompt 框架==
>【**背景**：竞品领域/行业】+
>【**指令**：进行竞品分析/提供竞品列表/分析报告】+
>【**输入数据**：提供参考大纲结构/产品内容（可选）】+
>【**输出指示**：分析类型/关注点 + 格式要求（表格/列表/段落）等】

1. 🌰首先我们获取竞品列表，以知识付费产品为例，可以这么问：
>我们准备进入知识付费行业（背景），列出目前市场上的知识付费产品（指令），提供产品名称和简要介绍的列表（输出指示）

2. 🌰明确目标竞品后，我们先问下可以从哪些维度进行，让 ChatGPT 输出一份竞品分析的大纲，我们即可参考这些维度自己分析，也可以逐一向它提问。比如，进一步问：“某竞品的优势和不足是什么？”、“某竞品的用户评价如何？”等等
3. 🌰现在我们指定某个竞品进行具体分析，可以这样问它
>我正在研究在线教育行业中的竞争对手（背景），（指令）请对（输入数据）得到APP、极客时间、樊登读书、喜马拉雅进行竞品分析，分析各竞品的竞品定位与核心价值、产品特点与功能、用户评价与反馈（输出指示）

需要注意的是，虽然 ChatGPT 可以帮我们快速找到竞品信息，理清分析思路，但我们还是**要亲自体验竞品，与竞品的用户交流，思考竞品「为什么这样做」、「为什么不那样做」等问题，以获得第一手信息与深度思考**。

在获取 ChatGPT 的分析结果后，我们再**结合自己的实际经验和思考，对其进行核实、调整与整合，确保竞品分析的准确性与实用性。**

### 协助产品设计
1. 对于熟练的、有大量产品参考经验的产品经理来说，可快速产出设计方案；但是对于没有经验的，可通过chatgpt快速产出设计方案

==prompt 框架==
>待补充······

2. 在完成产品功能设计后，我们可以利用 ChatGPT 来检查设计方案的合理性，并提出优化建议

==prompt 框架==
>【**背景**：产品类型/现状】+
>【**指令**：获取设计建议/优化方案】+
>【**输入数据**：参考案例辅助说明等（可选）】+
>【**输出指示**：设计元素/参考案例 + 格式要求（图文/列表/段落）等】

🌰现在假设要做一个在线教育平台的用户积分体系，尝试写提问：

>我们在做一个在线教育平台（背景），希望增加用户参与度和活跃度，（指令）请为在线教育平台提供用户积分体系的设计建议，列出积分体系的关键要素和激励措施（输出指示）

	用好 ChatGPT，即可帮我们启发思路，还能避免盲区，完善设计方案。

### 协助数据分析
通过分析用户数据，我们可以更好地了解用户行为、发现问题、挖掘需求，进而优化产品。

==prompt 框架==
>【**背景**：数据类型/业务场景】+
>【**指令**：发现原因/趋势/优化建议】+
>【**输入数据**：要分析的数据】+
>【**输出指示**：问题/现象描述 + 格式要求（图表/列表/段落）等】

🌰举个例子，产品日活数据下跌，让它帮忙分析，我先把简单的日活数据发给它：
>我正在做一款知识付费产品（背景），近期发现产品的日活数据下降，（指令）请帮我分析下这些数据，看是否正常，有没有问题？（输出指示）列出数据特点，如有问题，分析可能的原因，并提供优化建议；（输入数据）以下是具体的日活数据：日期 日活
>
>![日活|](https://s2.loli.net/2023/08/26/o6HTGlt5I8NVghr.png)

### 结尾
我在文中并没有展示具体的对话，大家可以亲自使用，感受chatgpt的强大性，以及能够带给我们的工作带来显著的效率提升。

> [!WARNING] 注意！！！
>在使用过程中需要遵守公司制度，不要把敏感信息传到网络