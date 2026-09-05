# JIN Chibi Topic Director

这个仓库不是生图 Prompt 仓库，也不是视频 Prompt 仓库。

它专门研究：

> **Q版 / Chibi 内容今天值得做什么题材。**

工作流：

```text
JIN 想做 Q版内容
→ 本 Skill 生成 / 研究题材
→ JIN 选择、修改、否决
→ 形成创意任务单
→ 再交给生图 Skill / 视频提示词 Skill
```

## 仓库结构

```text
SKILL.md
references/
  viral-baselines.md       # JIN 已确认的爆款案例
  topic-tracker.md         # 已做题材去重、当前选中主题与继续入口
research/
  pending-review.md        # 外部研究与 AI 新发现，等待 JIN 审核
knowledge/
  approved.md              # 只有 JIN 明确批准后才能进入
```

## 最重要的规则

外部搜索、AI 归纳、别人案例、论文文章、趋势观察都可以拿来学习，甚至可以每天研究。

但：

> **未经 JIN 明确批准，不得写入正式知识库。**

研究结果先进入审核状态，向 JIN 说明：

- 学到了什么；
- 证据是什么；
- 为什么可能有用；
- 有什么风险 / 未验证点；
- 建议加入、只留案例，还是不要加入。

JIN 决定以后再处理。

当前正式爆款基线见 `references/viral-baselines.md`。
