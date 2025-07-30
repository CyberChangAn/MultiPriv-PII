# 🔐MultiPriv: A Multilingual & Multimodal Dataset of PII Entities and Prompts for LLM Privacy Risk Research

多语言多模态 PII 实体与 Prompt 数据集 —— MultiPriv 数据集（面向大模型的隐私风险研究）

The technical report is currently being written, including the specific details of the dataset, model testing, and references to other datasets.
技术报告正在撰写中，包括数据集具体情况以及模型测试，和对其他数据集的引用。

## 📖 Table of Contents | 目录

<!--toc:start-->

- [🔐MultiPriv: A Multilingual & Multimodal Dataset of PII Entities and Prompts for LLM Privacy Risk Research](#🔐multipriv-a-multilingual-multimodal-dataset-of-pii-entities-and-prompts-for-llm-privacy-risk-research)
  - [📌 Overview | 数据集简介](#📌-overview-数据集简介)
  - [🎯 Applications | 应用场景](#🎯-applications-应用场景)
  - [🛡️ Privacy & Ethics | 隐私与伦理声明](#🛡️-privacy-ethics-隐私与伦理声明)
  - [📄 License | 使用协议](#📄-license-使用协议)
  - [📣 Citation](#📣-citation)
  - [📬 Contact | 联系方式](#📬-contact-联系方式)
  <!--toc:end-->

## 📌 Overview | 数据集简介

**MultiPriv** is a multilingual (Chinese & English) and multimodal (text & image) dataset containing extensive **personally identifiable information (PII)**. It is built to support research on **privacy recognition**, **privacy-preserving generation**, and **privacy risk evaluation in LLMs**.

This dataset includes:

- Structured annotations of PII entities in text (English & Chinese)
- Image samples with visual privacy information (e.g., faces, ID numbers, license plates)
- Prompt-based user inputs embedding privacy risks, constructed to simulate real-world LLM usage

**MultiPriv** 是一个包含大量 **个人身份识别信息（PII）** 的中英文、多模态隐私数据集，旨在支持以下研究任务：

- 文本与图像中的 PII 实体识别
- 隐私感知的文本/图像生成任务
- 大模型中的隐私泄露风险建模与评估
- Prompt 注入与红队测试等安全性研究

## 🎯 Applications | 应用场景

| Task                                     | 说明                            |
| ---------------------------------------- | ------------------------------- |
| PII Named Entity Recognition (NER)       | 文本中识别敏感实体              |
| Multimodal Privacy Detection             | 图文结合的隐私识别任务          |
| Prompt Privacy Filtering & Redaction     | Prompt 中隐私识别与屏蔽         |
| LLM Privacy Risk Assessment              | 评估模型对 PII 的记忆与响应能力 |
| LLM Safety Alignment & Red Teaming       | 对齐训练、攻击模拟与响应拦截    |
| Privacy-Preserving Text/Image Generation | 支持隐私脱敏的生成系统构建      |

- ## 🛡️ Privacy & Ethics | 隐私与伦理声明

  - All data is **synthetically generated**, **anonymized**, or **legally sourced**.
    所有数据均为**合成生成**、**脱敏处理**或**合法采集**。
  - No real personal identity is exposed.
    不包含任何真实可识别的身份信息。
  - Dataset is intended **only for research and safety development**, not for commercial use.
    本数据集仅用于**研究用途与模型安全开发**，禁止商业用途或恶意使用。

## 📄 License | 使用协议

Released under the **CC BY-NC-SA 4.0 License**.
以 **署名-非商业性使用-相同方式共享 4.0 国际许可协议** 发布。

> ✅ You may share and adapt for non-commercial purposes with attribution.

## 📣 Citation

If you use this dataset, please cite:

```bibtex
@misc{your_dataset2025,
  title={Multilingual and Multimodal Privacy Entity Dataset},
  author={CyberChangan},
  year={2025},
  howpublished={\url{https://github.com/CyberChangAn/MutilPriv}}
}
```

## 📬 Contact | 联系方式

For questions, suggestions, or collaboration:
如有问题或合作意向，请联系：

Email: xtsun@stu.xidian.edu.cn
