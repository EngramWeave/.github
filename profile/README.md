<div align="center">

# EngramWeave

**你的知识，你来定稿。**

AI 编译，你定稿。面向长期学习与研究的个人知识编译系统。

[![Status](https://img.shields.io/badge/Status-Early%20Development-orange?style=flat-square)]()
[![Design](https://img.shields.io/badge/Design-Human--in--the--loop-7C3AED?style=flat-square)]()
[![Obsidian](https://img.shields.io/badge/Obsidian-Compatible-7C3AED?style=flat-square&logo=obsidian)](https://obsidian.md)

[主仓库](https://github.com/EngramWeave/EngramWeave) · [设计方案](./个人知识编译系统总体设计方案.md) · [讨论](https://github.com/EngramWeave/EngramWeave/discussions)

</div>

---

## 你一定经历过

**传统知识管理：收藏了，就等于学会了。**

收藏了几百篇文章，真正消化过的不超过十篇。当时保存时明明有想法，过三个月再看——完全不记得当初为什么觉得它重要。原网页改了、删了、404 了，你连 AI 当时读了什么都说不清。知识库里新旧笔记彼此孤立，维护交叉引用和检查矛盾变成了兼职工作，成本随笔记数量增长而急剧上升[reference:9]。

**LLM Wiki 路线：AI 全自动维护，你负责“拥有”。**

把资料喂给 AI，它帮你编译成结构化的 Wiki，自动建立交叉引用、检测矛盾、更新过时内容。听起来很美——你几乎不用动手。但几个月后你发现：Wiki 里的内容你从未真正读过，AI 替你做了编辑判断，重要细节被丢弃而你毫不知情[reference:10]。更危险的是，Wiki 过时的方式和数据库不同——数据库的空白看起来像“不知道”，Wiki 的过时看起来像“自信的错误信息”，你根本不会怀疑[reference:11]。你拥有了一个知识库，但它里面的知识不属于你。

---

## EngramWeave 怎么做

一句话：**AI 负责编译，你负责定稿。**

把你在网页、论文和实验中看到的内容，连同当时的想法、疑问与判断一起保存。AI 会阅读来源、提炼要点、发现关系、规划整合——但**它永远只能提案，不能拍板**。正式知识以普通 Markdown 文件存在你自己的 Obsidian 库里。

> **AI 认为** ≠ **我认可**
>
> 这是贯穿全篇的唯一设定，也是 EngramWeave 与传统知识管理和常见 LLM Wiki 路线的根本区别。

---

### 三条路线的本质差异

| | 传统知识管理（Obsidian / Notion） | LLM Wiki 常见工程实现（Karpathy 模式） | EngramWeave |
|---|---|---|---|
| **知识从哪来** | 你手动写笔记、建链接、分类 | AI 全自动编译，人几乎不写 | AI 编译草稿，**你逐条确认后才成为正式知识** |
| **AI 的角色** | 基本没有 | 知识库的**唯一作者和维护者** | 理解、建议、提案——**你才是作者** |
| **你的角色** | 全部手动劳动 | 提供素材和规则，**信任 AI 的判断** | 判断什么值得留下，**决定哪些关系成立** |
| **产出是什么** | 你的笔记文件 | AI 维护的 Wiki 页面 | **你认可的知识**，存在你自己的 Markdown 里 |
| **失效模式** | 维护成本过高，最终放弃 | AI 幻觉污染、自信的错误、知识归属感丧失 | 需要你投入判断——但**每一次投入都在塑造你自己的知识体系** |
| **长期结果** | 收藏夹，越积越不想打开 | 一个你“拥有”但没读过的 Wiki | **一个你真正理解、信任、能回忆的外置认知系统** |

---

## 三条不可妥协的约束

**🔐 数据主权**
正式知识以普通 Markdown 存在你自己的 Obsidian 库里，论文与引用以 Zotero 为准。系统内部只保存索引、草稿、任务与提案这类派生数据，**原则上都可重建**。

**🛡️ 权限**
AI 与外部工具默认只能读取与提案；所有正式知识的修改都**逐项确认**，并可完整回滚。

**🌱 长期演化**
维护只建议、不推送；检索可随时回取；不做任何强制复习与提醒。随时记录，随用随取。

---

<div align="center">

**如果这个项目对你有启发，欢迎 Star ⭐ 和参与共建。**

[主仓库](https://github.com/EngramWeave/EngramWeave) · [设计方案](https://github.com/EngramWeave/EngramWeave/blob/main/个人知识编译系统总体设计方案.md) · [讨论](https://github.com/EngramWeave/EngramWeave/discussions)

</div>
