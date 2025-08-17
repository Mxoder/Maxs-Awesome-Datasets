# Max's Awesome Datasets
<p align="center">
  <img src="static/logo.png" alt="logo" /> </p>
<h3 align="center">
    一个有意思的数据集集合
</h3>



## 简介

这个仓库收录了我**个人自建**的数据集，所有数据集均已上传至 Hugging Face，欢迎使用和提出建议。

我的 Hugging Face 主页：[huggingface.co/Mxode](https://huggingface.co/Mxode)。

本仓库与数据集将会持续更新，如果你觉得我的数据集有用，可以点个 star 鼓励一下！




## News

[25/08/17] 发布了 [📷 CAMS](https://huggingface.co/datasets/Mxode/CAMS)，一个大规模、多方面、基于属性的中文摘要数据集

[25/05/09] 发布了 [Chinese-Instruct-Lite](https://huggingface.co/datasets/Mxode/Chinese-Instruct-Lite)，一个简化版本的中文指令数据集，主题广泛，涵盖代码、数学、通用等领域，数据量 8.1M+，**适合用于学习从零训练中文大模型**

[25/04/27] 发布了 [「十万个为什么」](https://huggingface.co/datasets/Mxode/I_Wonder_Why-Chinese)，一个中文百科开放问答数据集，涵盖**SFT 指令微调、DPO 偏好强化学习、R1 类推理蒸馏任务**，数据量超过 600 万，**非常适合用于学习从零训练中文大模型**

[25/04/23] 发布了 [Psychologist-psiholog-zh_ru](https://huggingface.co/datasets/Mxode/Psychologist-psiholog-zh_ru)，一个中俄双语心理咨询数据集

[25/04/23] 发布了 [Chinese-QA-Agriculture_Forestry_Animal_Husbandry_Fishery](https://huggingface.co/datasets/Mxode/Chinese-QA-Agriculture_Forestry_Animal_Husbandry_Fishery)，一个中文农林牧渔问答数据集

<details>
<summary>展开更多</summary>

[25/04/22] 清洗整理了 [IndustryInstruction-Chinese](https://huggingface.co/datasets/Mxode/IndustryInstruction-Chinese)，一个中文行业指令数据集

[25/04/21] 发布了 [Chinese-Reasoning-Distil-Data](https://huggingface.co/datasets/Mxode/Chinese-Reasoning-Distil-Data)，一个中文推理蒸馏数据集

[25/04/21] 像猫猫一样思考！发布了推理数据集 [Meow-Reasoning-100K](https://huggingface.co/datasets/Mxode/Meow-Reasoning-100K)，全部是猫猫的思考和回复

[25/04/21] 发布了 [Chinese-StackOverflow-QA-C_Language](https://huggingface.co/datasets/Mxode/Chinese-StackOverflow-QA-C_Language)，一个中文 StackOverflow C 语言问答数据集

[25/04/21] 发布了 [Chinese-OpenQA-Reasoning-50K](https://huggingface.co/datasets/Mxode/Chinese-OpenQA-Reasoning-50K)，一个中文开放式问答推理数据集

[25/04/21] 发布了 [Math-Chinese-DeepSeek-R1-10K](https://huggingface.co/datasets/Mxode/Math-Chinese-DeepSeek-R1-10K)，一个中文 DeepSeek-R1-Distil 数学指令微调数据集

[25/04/21] 发布了 [Chinese-Medical-Instruct-1M](https://huggingface.co/datasets/Mxode/Chinese-Medical-Instruct-1M)，一个中文医疗指令微调数据集

[25/04/19] 发布了 [Chinese-Instruct](https://huggingface.co/datasets/Mxode/Chinese-Instruct)，一个大规模、多领域的高质量中文微调数据集，目前数据量 3M+

[25/04/18] 抽取重整了 Fineweb-Edu-Chinese-V2.1 的两个子集

[24/09/09] 发布了大规模中英合成翻译数据集 [BiST](https://huggingface.co/datasets/Mxode/BiST)，目前数据量 50M+，未来将继续扩充

[24/09/07] 清洗重整了 IndustryCorpus 的子集，中英双语：[IndustryCorpus-Subset-zh-en](https://huggingface.co/datasets/Mxode/IndustryCorpus-Subset-zh-en)

[24/09/07] 发布了 Firefly-1.1M-Rephrased，包含[单轮数据集](https://huggingface.co/datasets/Mxode/Firefly-1.1M-Rephrased)和[多轮数据集](https://huggingface.co/datasets/Mxode/Firefly-Rephrased-Multiturn-300K)

[24/09/06] 发布了 [Magpie-Pro-10K-GPT4o-mini](https://huggingface.co/datasets/Mxode/Magpie-Pro-10K-GPT4o-mini)，一个英文指令微调数据集

[24/01/07] 发布了 [一只猫猫的说话语录](https://huggingface.co/datasets/Mxode/Meow-Instruct-34k)

[23/10/03] 发布了 [CSDN-Community-C-Language-3years](https://huggingface.co/datasets/Mxode/CSDN-Community-C-Language-3years)，为 CSDN - C 语言社区 2020.10.2 ~ 2023.10.2 的问答数据

[23/10/02] 发布了 [StackOverflow-QA-C-Language-40k](https://huggingface.co/datasets/Mxode/StackOverflow-QA-C-Language-40k)，为 StackOverflow 上关于 C 语言的问答数据，源语言为英文

</details>





## 数据集

下面列出了本仓库包含的数据集，其中标注了“🚧”的是仍在扩充中的。

### 🌟 Highlighted

> 一些精选的高质量数据集。

**Chinese-Instruct** 🚧

- 简介：大规模中文指令微调数据集，相较于已有的中文指令微调数据集，具备更高的质量、更多指令来源、更大的规模。
- 规模：4.5M+
- 链接：[Mxode/Chinese-Instruct](https://huggingface.co/datasets/Mxode/Chinese-Instruct)

**Chinese-Reasoning-Distil-Data** 🚧

- 简介：中文推理蒸馏数据集，包含指令、思考过程、回复，全新构造，非其他数据集的子集或翻译版本。
- 规模：180K
- 详情：[知乎文章 - 新的中文推理蒸馏数据集：Chinese-Reasoning-Distil-Data](https://zhuanlan.zhihu.com/p/1898405616860521535)
- 链接：[Mxode/Chinese-Reasoning-Distil-Data](https://huggingface.co/datasets/Mxode/Chinese-Reasoning-Distil-Data)

**BiST** (**Bi**lingual **S**ynthetic **T**ranslation dataset) 🚧

- 简介：大规模中英双语翻译数据集，采集真实语料，多步骤过滤、清洗、合成、校验。
- 规模：57M
- 详情：[知乎文章 - BiST](https://zhuanlan.zhihu.com/p/1898342192403163133)
- 链接：[Mxode/BiST](https://huggingface.co/datasets/Mxode/BiST)

**📷 CAMS** (**C**hinese **A**ttribute-based **M**ulti-faceted **S**ummarization Dataset)

- 简介：一个大规模、多方面、基于属性的中文摘要数据集，为推进长文本摘要研究而设计，具备多层次摘要和丰富的属性标注。
- 规模：1M
- 链接：[Mxode/CAMS](https://huggingface.co/datasets/Mxode/CAMS)

**I_Wonder_Why-Chinese**

- 简介：一个中文百科开放问答数据集，涵盖 SFT 指令微调、DPO 偏好强化学习、R1 类推理蒸馏任务，适合用于学习从零训练中文大模型
- 规模：超过 120 万条指令 + 超过 600 万条回复
- 详情：[知乎文章 - 可能是最适合用于学习从零训练中文大模型的数据集！](https://zhuanlan.zhihu.com/p/1899677366940328267)
- 链接：[Mxode/I_Wonder_Why-Chinese](https://huggingface.co/datasets/Mxode/I_Wonder_Why-Chinese)

**Chinese-Instruct-Lite**

- 简介：简化版本的大规模中文指令微调数据集（并非子集），涵盖代码、数学、通用等领域，适合用于学习从零训练中文大模型
- 规模：8.1M+
- 链接：[Mxode/Chinese-Instruct-Lite](https://huggingface.co/datasets/Mxode/Chinese-Instruct-Lite)

<details>
<summary>展开更多</summary>

**Math-Chinese-DeepSeek-R1-10K**

- 简介：中文 DeepSeek-R1-Distil 数学指令微调数据集，所有答案均经过正确性校验。
- 规模：10K
- 链接：[Mxode/Math-Chinese-DeepSeek-R1-10K](https://huggingface.co/datasets/Mxode/Math-Chinese-DeepSeek-R1-10K)

**Meow-Reasoning-100K**

- 简介：像猫猫一样思考！R1 格式的推理数据集，不同于一般的推理数据集，这里全部都是猫猫语气的思考和回复。
- 规模：100K
- 详情：[知乎文章 - 像猫猫一样思考！猫猫的推理数据集](https://zhuanlan.zhihu.com/p/1898515518887026761)
- 链接：[Mxode/Meow-Reasoning-100K](https://huggingface.co/datasets/Mxode/Meow-Reasoning-100K)

**Chinese-Medical-Instruct-1M**

- 简介：中文医疗指令微调数据集，回复依赖于真实参考源。
- 规模：1M
- 链接：[Mxode/Chinese-Medical-Instruct-1M](https://huggingface.co/datasets/Mxode/Chinese-Medical-Instruct-1M)




### 指令微调数据集（SFT）

> 一般的指令微调数据集。

**IndustryInstruction-Chinese**

- 简介：中文行业指令数据集，清洗自 [BAAI/IndustryInstruction](https://huggingface.co/datasets/BAAI/IndustryInstruction)，包含多轮与单轮对话。
- 规模：1M+
- 链接：[Mxode/IndustryInstruction-Chinese](https://huggingface.co/datasets/Mxode/IndustryInstruction-Chinese)

**Chinese-QA-Agriculture_Forestry_Animal_Husbandry_Fishery**

- 简介：中文农林牧渔问答数据集，涵盖农业、林业、畜牧业、渔业，数据量 900K+。
- 规模：900K+
- 链接：[Mxode/Chinese-QA-AFAF](https://huggingface.co/datasets/Mxode/Chinese-QA-Agriculture_Forestry_Animal_Husbandry_Fishery)

**Firefly-1.1M-Rephrased**

- 简介：中文指令微调数据集，对原 Firefly-1.1M 数据集做了清洗和增强。
- 规模：1.1M
- 链接：[Mxode/Firefly-1.1M-Rephrased](https://huggingface.co/datasets/Mxode/Firefly-1.1M-Rephrased)

**Firefly-Rephrased-Multiturn-300K**

- 简介：中文多轮指令微调数据集，由 Firefly-1.1M-Rephrased 合成。
- 规模：300K
- 链接：[Mxode/Firefly-Rephrased-Multiturn-300K](https://huggingface.co/datasets/Mxode/Firefly-Rephrased-Multiturn-300K)

**Chinese-StackOverflow-QA-C_Language**

- 简介：中文 StackOverflow C 语言问答数据集，包含原数据集的翻译版本和新合成的指令微调版本。
- 规模：200K（合成）+ 40K（翻译）
- 链接：[Mxode/Chinese-StackOverflow-QA-C_Language](https://huggingface.co/datasets/Mxode/Chinese-StackOverflow-QA-C_Language)

**Magpie-Pro-10K-GPT4o-mini**

- 简介：英文指令微调数据集，从原 Magpie 数据集挑选指令改写后，重新用 GPT4o-mini 合成回复。
- 规模：10K
- 链接：[Mxode/Magpie-Pro-10K-GPT4o-mini](https://huggingface.co/datasets/Mxode/Magpie-Pro-10K-GPT4o-mini)

**Meow-Instruct-34k**

- 简介：一只猫猫的说话语录。格式为一般的指令微调格式。
- 规模：34K
- 链接：[Mxode/Meow-Instruct-34k](https://huggingface.co/datasets/Mxode/Meow-Instruct-34k)




### 推理数据集（Reasoning）

> O1、R1 格式的推理数据集。

**Chinese-OpenQA-Reasoning-50K**

- 简介：中文开放式问答推理数据集，全新构造，非其他数据集的子集或翻译版本。
- 规模：50K
- 链接：[Mxode/Chinese-OpenQA-Reasoning-50K](https://huggingface.co/datasets/Mxode/Chinese-OpenQA-Reasoning-50K)

**School-Math-R1-Distil-Chinese-220K**

- 简介：难度很低的小学数学推理数据集。从[原数据集](https://huggingface.co/datasets/BelleGroup/school_math_0.25M)提取指令后，重新合成的回复。
- 规模：220K
- 链接：[Mxode/School-Math-R1-Distil-Chinese-220K](https://huggingface.co/datasets/Mxode/School-Math-R1-Distil-Chinese-220K)







### 基础数据集

> 一些整理清洗过滤的基础数据集。

**Fineweb-Edu-Chinese-V2.1-merged-score4_5**

- 简介：[Fineweb-Edu-Chinese-V2.1](https://huggingface.co/datasets/opencsg/Fineweb-Edu-Chinese-V2.1) 的评分为 4~5 的数据的子集，对原数据集的细切片进行了合并。
- 规模：17M+
- 链接：[Mxode/Fineweb-Edu-Chinese-V2.1-merged-score4_5](https://huggingface.co/datasets/Mxode/Fineweb-Edu-Chinese-V2.1-merged-score4_5)

**Fineweb-Edu-Chinese-V2_1-subset-5M**

- 简介：[Fineweb-Edu-Chinese-V2.1](https://huggingface.co/datasets/opencsg/Fineweb-Edu-Chinese-V2.1) 的一个子集，做了简单清洗过滤。
- 规模：5M
- 链接：[Mxode/Fineweb-Edu-Chinese-V2_1-subset-5M](https://huggingface.co/datasets/Mxode/Fineweb-Edu-Chinese-V2_1-subset-5M)

**IndustryCorpus-Subset-zh-en**

- 简介：[IndustryCorpus](https://huggingface.co/datasets/BAAI/IndustryCorpus) 的一个子集，包含各领域，做了简单清洗过滤。
- 规模：2.7M
- 链接：[Mxode/IndustryCorpus-Subset-zh-en](https://huggingface.co/datasets/Mxode/IndustryCorpus-Subset-zh-en)





### 其他数据集

> 其他类型的数据集。

**Psychologist-psiholog-zh_ru**

- 简介：中俄双语心理咨询数据集，源数据采集自 psiholog.ru，做了清洗整理翻译。
- 规模：17K+
- 链接：[Mxode/Psychologist-psiholog-zh_ru](https://huggingface.co/datasets/Mxode/Psychologist-psiholog-zh_ru)

**StackOverflow-QA-C-Language-40k**

- 简介：StackOverflow 上关于 C 语言的问答数据集，源语言为英文。
- 规模：40K
- 链接：[Mxode/StackOverflow-QA-C-Language-40k](https://huggingface.co/datasets/Mxode/StackOverflow-QA-C-Language-40k)

**CSDN-C_Language-2013_2023**

- 简介：CSDN 上关于 C 语言的问答数据集，时间跨度为 2013年 ~ 2023年。
- 规模：29K+
- 链接：[Mxode/CSDN-C_Language-2013_2023](https://huggingface.co/datasets/Mxode/CSDN-C_Language-2013_2023)







### 早期数据集

> 一些早期构造的数据集。

<details>
<summary>展开</summary>

**Chinese-Classics-Partial**

- 简介：古籍相关的文本，进行了简单清洗。
- 规模：200+篇 / 460K 行
- 链接：[Mxode/Chinese-Classics-Partial](https://huggingface.co/datasets/Mxode/Chinese-Classics-Partial)

**Baike-Astronomy-ZH**

- 简介：天文学百科，包含 8 个子目录。
- 规模：1K 条词条
- 链接：[Mxode/Baike-Astronomy-ZH](https://huggingface.co/datasets/Mxode/Baike-Astronomy-ZH)

**C-Language-Chat-Debug-Multiturn-Zh**

- 简介：C 语言场景的 user - assistant 多轮对话。
- 规模：1.3K
- 链接：[Mxode/C-Language-Chat-Debug-Multiturn-Zh](https://huggingface.co/datasets/Mxode/C-Language-Chat-Debug-Multiturn-Zh)

**DPO-arxiv_paraphrase**

- 简介：根据 arxiv 论文摘要，合成的改写偏好数据集，`chosen` 字段为摘要原文，`rejected` 字段为模型合成。
- 规模：200K
- 链接：[Mxode/DPO-arxiv_paraphrase](https://huggingface.co/datasets/Mxode/DPO-arxiv_paraphrase)

**University-News-Instruction-Zh**

- 简介：某高校校园新闻数据集，合成了三类任务：标题总结、栏目分类、新闻生成。
- 规模：65K * 3（类任务）
- 链接：[Mxode/University-News-Instruction-Zh](https://huggingface.co/datasets/Mxode/University-News-Instruction-Zh)

**Chinese-English-Parallel-Synonym-Corpus-75k**

- 简介：中英平行翻译改写语料对。
- 规模：75K
- 链接：[Mxode/Chinese-English-Parallel-Synonym-Corpus-75k](https://huggingface.co/datasets/Mxode/Chinese-English-Parallel-Synonym-Corpus-75k)

</details>

---



## 致谢

上面很多数据集工作都是受到社区已有工作启发，或者在已有工作上的二次开发，向所有开源工作衷心表达敬意！

如果有任何问题或建议，也欢迎提出！



## 引用

```bibtex
@misc{zhang2025maxawesomedatasets,
      title={Max's Awesome Datasets},
      author={Max Zhang},
      year={2025},
      howpublished = {\url{https://github.com/Mxoder/Maxs-Awesome-Datasets}},
}
```

