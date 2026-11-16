# 高中化学试卷解析

面向教师和学生的 Codex 技能，适用于高考、模拟考、校考和日常练习。可上传 PDF、截图或照片，也可以直接粘贴题目。

- 整卷先给答案速览，再按原卷顺序逐题讲解。选择题逐个解释选项为什么成立或哪里有误，非选择题逐小问展开推导。
- 默认采用人民教育出版社《普通高中教科书·化学》2019 年审定系列。在相应的选项或小问旁标注教材册次、章节和经核实的印刷页码。暂时无法核实的页码会标为待核。
- 随卷上传参考答案可核对分歧，上传学生作答可定位失分步骤。题面或图表有缺损时，先解析能够确定的部分并指出需补充的位置。

## 安装

1. 从 [GitHub Release v1.0.0](https://github.com/11145145325/chemistry-exam-analysis/releases/tag/v1.0.0) 下载 `chemistry-exam-analysis-v1.0.0.zip`。
2. 解压后，将完整的 `chemistry-exam-analysis` 文件夹放入个人主目录下的 `.agents/skills/`。放好后，入口文件应位于 `~/.agents/skills/chemistry-exam-analysis/SKILL.md`。Windows 上的 `~` 对应当前用户的个人文件夹。
3. 在 Codex 中打开新聊天，上传试卷并输入下面的提示词。

```text
用 $chemistry-exam-analysis 解析这份高中化学试卷。先给答案速览，再按题号逐题详解。选择题解释每个选项，非选择题展开每个小问。涉及教材的考点请写明人教版册次、章节和经核实的印刷页码，并核对随附的参考答案。
```

## 示例与教材

- [南昌零模化学解析示例](examples/nanchang-zero-chemistry.md)展示第 2 题和第 17 题第（4）问②的讲解。
- [人教版高中化学教材索引](references/textbook-index.md)列出五册里常考知识点对应的章节和印刷页码。
