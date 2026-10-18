# 庄智尧

<p align="center">
  <strong>庄智尧 CV </strong><br>
  中国海洋大学 · 药物化学硕士（AIDD）· 2024 - 2027 
</p>

<p align="center">
  <a href="https://github.com/Zzy522">
    <img src="https://img.shields.io/badge/GitHub-Zzy522-181717?style=flat-square&logo=github" alt="GitHub">
  </a>
  <a href="https://www.molgluedb.com/">
    <img src="https://img.shields.io/badge/MolGlueDB-Online-0a7b83?style=flat-square" alt="MolGlueDB">
  </a>
  <img src="https://img.shields.io/badge/Research-AI4S%20%7C%20AIDD-1f6feb?style=flat-square" alt="Research">
  <img src="https://img.shields.io/badge/Focus-Molecular%20Glue%20%7C%20MedChem%20Agent-6f42c1?style=flat-square" alt="Focus">
</p>

> 具备 AI4S 与药物化学交叉背景，专注于分子胶与 PROTAC 降解剂、药物化学文献信息抽取、分子性质预测和科研智能体。能够独立完成从数据构建、模型训练与评测，到 Agent 工作流开发、工具调用和系统部署的完整流程。

## 联系方式

- **邮箱**：944809681@qq.com
- **电话**：18686314912
- **GitHub**：[github.com/Zzy522](https://github.com/Zzy522/)
- **研究主页**：[MolGlueDB](https://www.molgluedb.com/)

## 教育背景

| 时间 | 经历 |
| --- | --- |
| 在读（预计 2027 年毕业） | **中国海洋大学**，药物化学硕士（AIDD），导师：秦冲 |
| 本科阶段 | **西南交通大学**，制药工程，导师：张岚 |
| 政治面貌 | 中共党员 |

## 科研项目

### MolGlueDB：分子胶在线数据库

[访问 MolGlueDB](https://www.molgluedb.com/) · **第一作者发表于 Nucleic Acids Research**

- 完成分子胶数据收集、清洗、标准化和结构信息整理，构建面向药物化学研究的专用数据资源。
- 采用 **Vue3 + Flask** 架构独立完成前后端系统设计、数据库构建、查询 API 开发和在线部署。
- 使用 **D3.js** 实现化合物、靶点和活性数据的交互式可视化。
- 平台上线后累计访问量超过 **22,000 次**，数据下载量超过 **2,500 次**，总互动人次超过 **10,000**。

### MedChem Agent & MolGlueDB-v2：智能体自主更新数据库

- 面向药物化学文献中的“结构—活性”信息获取问题，构建由 MedChem Agent 驱动的数据库自主更新系统。
- 基于 **LangGraph** 搭建包含 11 个专业子 Agent 的多智能体架构，覆盖文献解析、OCR 降噪、化合物结构识别、活性信息抽取、证据核验、数据去重和数据库更新。
- 打通“文献输入 → 结构化抽取 → 质量复核 → 数据入库 → 版本更新”全流程，支持分子胶数据库持续自动化维护。
- 将药物化学专家分析流程封装为可复用的 Agent Skills 与 Tools，实现 Tool Calling 和多工具协同。
- 构建包含 **13,500+ 条样本**的评测集，评估信息抽取准确率、工具调用准确率、响应延迟和 Token 成本。
- 通过工作流和提示词迭代，使核心信息提取效率较人工流程提升 **6 倍以上**。

### MG2Act：分子胶活性预测模型

[BioRxiv 预印本](https://doi.org/10.64898/2026.08.08.739980v1) · **第一作者，Nature Communications Under Review**

- 基于真实分子胶数据构建连续活性预测任务，融合分子结构表征与分子胶作用机制进行建模。
- 使用 **RDKit** 完成分子特征构建，基于 **PyTorch** 搭建深度学习预测模型。
- 在新靶点 Zero-shot 场景下开展候选分子筛选，获得 **2 个 nM 级候选分子胶**，其中最高 **Dmax 达到 95%**。

### 基于蛋白表面指纹 MaSIF 的非降解分子胶开发与靶点筛选

- 基于 MaSIF 蛋白表面表征方法，构建非降解分子胶的蛋白底物识别与靶点筛选模型。
- 面向候选蛋白开展前瞻性筛选，获得 **2 个具有显著作用的候选靶点蛋白**。
- 已通过三元组湿实验验证分子胶、靶蛋白及相关作用关系，进一步开展冷冻电镜实验解析结合模式。

### CK1α 分子胶降解剂设计筛选

- 以第一作者在《中国海洋药物》发表《基于人工智能的 CK1α 分子胶降解剂设计筛选及其活性评价》。
- 参与 AR-PROTAC 的设计与化学合成，相关成果发表于 **Journal of Medicinal Chemistry**。

## 实习与产品经历

### 上海深度势能科技有限公司｜科研 Agent 产品运营实习生（开发 + 产品）

- 开发精准文献推荐 Agent，参与 Agent Benchmark 的构建与测评。
- 负责将科研场景、数据资源和智能体工作流结合，推进科研 Agent 产品化。

### Lab Copilot 高校科研管理 Agent｜项目负责人

[访问 Lab Copilot](https://labcopai.com/) · **数据要素 × 山东省决赛路演优秀奖**

- 负责 0-1 完成 Agent 产品开发，融合多模态数据采集、多 Agent 协同和私域知识库迭代。
- 面向高校实验室科研管理场景，构建可持续迭代的实验室 Agent。

## 学术成果

- **MolGlueDB**：[分子胶在线数据库](https://www.molgluedb.com/)，第一作者，发表于 *Nucleic Acids Research*。
- **MG2Act**：[分子胶活性预测模型](https://doi.org/10.64898/2026.08.08.739980v1)，第一作者，发表于 bioRxiv。
- [基于人工智能的 CK1α 分子胶降解剂设计筛选及其活性评价](https://www.cpa.org.cn/index.php?cid=74102&do=info)，第一作者，发表于《中国海洋药物》。
- [Discovery of an Androgen Receptor Degrader Featuring a Pyridazinyl Glutarimide CRBN-Binding Motif for Transdermal Treatment of Androgenetic Alopecia](https://doi.org/10.1021/acs.jmedchem.5c03843)，参与分子设计与化学合成，发表于 *Journal of Medicinal Chemistry*。
- [Deciphering the multifunctional role of dual leucine zipper kinase (DLK) and its therapeutic potential in disease](https://doi.org/10.1016/j.ejmech.2023.115404)。*European Journal of Medicinal Chemistry*。

## 竞赛与奖项

| 赛事 | 角色 | 奖项 | 年份 |
| --- | --- | --- | --- |
| 中国研究生企业管理创新大赛（商业决策与运营管理类） | 队长 | **国家一等奖** | **2025** |
| 中国研究生企业管理创新大赛（商业决策与运营管理类） | 队长 | **国家二等奖** | **2024** |
| 全国大学生工程训练综合能力竞赛（跨学科系统工程类） | 队长 | **国家二等奖** | **2023** |
| 全国大学生工程训练综合能力竞赛 | 队长 | 四川省一等奖 | 2022、2023 |
| 中国大学生化工设计大赛—天正设计杯 | 队长 | 国家三等奖 | 2023 |
| 中国大学生化工设计大赛—天正设计杯 | 队长 | 西南赛区二等奖 | 2023 |
| 数据要素 × 山东省决赛路演 | 项目负责人 | 优秀奖 | 2026 |


## 研究方向

| 方向 | 关键词 |
| --- | --- |
| AI4S / AIDD | 分子胶降解剂、PROTAC、分子性质预测、候选分子筛选 |
| 科研智能体 | MedChem Agent、多智能体协同、LangGraph、Agent Skills、Tool Calling、Agent Benchmark |
| 数据与模型 | Python、PyTorch、RDKit、OCR、结构标准化、Agent开发与评测 |
| 系统开发 | Vue3、Flask、D3.js、查询 API、数据库构建、在线部署 |
| 证书与特长 | 英语六级、国家一级足球裁判员、腾讯云 AI 开发者认证 |

---

<p align="center">
  <sub>AI4S · AIDD · Molecular Glue · MedChem Agent</sub>
</p>
