---
name: jin-chibi-15s
description: Create, revise, and diagnose short social-video concepts and final video prompts for JIN's complete chibi universe, led by Phoebe with Nuonuo, Guga, Q-version Sera, and a POV keeper when requested. Default to 15 seconds when duration is unspecified. Do not use for adult Sera, homeworld canon, or long-form worldbuilding.
---

# JIN Chibi 15s

为 JIN 的完整 Q 版宇宙制作可直接生成的短视频提示词。菲比是默认主角，但不把糯糯、咕嘎、Q 版 Sera 或 keeper 自动塞进每条视频；只有当前题材需要或用户点名时才加入。

## 边界

- 本 Skill 可以完成：选题讨论、15 秒小事件设计、完整视频提示词、成片复查与最小修订。
- 本 Skill 不维护成女 Sera 的世界观，不把 Q 版声音规则带入成女 Sera。
- 不复制通用长篇导演百科。复杂战斗、长镜头、多场景连续剧情或 30 秒以上内容，应改用通用视频导演 Skill。
- 用户已接受的提示词或成片优先保护；除非明确要求修改，不主动“优化”通过版本。

## 规则级别

- **HARD**：当前角色身份、实体数量、声音权限、道具归属、已确认连续性与用户最新要求。
- **DEFAULT**：15 秒、9:16、真实手机 POV、轻量资产流程；用户可覆盖。
- **OPTIONAL**：反转、特定内容结构、精确时间戳、Sera 后景 OB。
- **TEST**：只来自少量样本、尚未完成单变量验证的传播或模型经验。

不得把 DEFAULT、OPTIONAL 或 TEST 写成平台铁律。

## 按需读取

只读取当前任务需要的文件：

- 出现菲比、糯糯、咕嘎、Q 版 Sera、keeper 或多人声音时，读 [references/character-and-audio-bible.md](references/character-and-audio-bible.md)。
- 新写或修订 8–15 秒完整提示词时，读 [references/15s-production-method.md](references/15s-production-method.md)。
- 用户需要选题、结构变化或爆款样本启发时，读 [references/validated-content-patterns.md](references/validated-content-patterns.md)。
- 只有 Sera 被指定为后景彩蛋／活水印时，读 [references/sera-background-ob.md](references/sera-background-ob.md)。

不要为了普通菲比单人视频读取全部参考文件。

## 核心执行原则

1. 先用一句话确认本条唯一中心事件及结束画面。
2. 把动作写成可见状态变化：起始信号 → 过程／接触 → 减速或衰减 → 稳定结果。
3. 只写会影响动作、视线、移动或连续性的空间锚点，不把普通房间写成建筑图。
4. POV 只因开门、走动、低头、蹲下、伸手、被碰撞等真实原因移动，不因“可爱”而自动抖动或变焦。
5. 巴掌大角色必须有尺度、重量、接地阴影、接触阴影及与真实物体的物理反馈，不能像贴纸或漂浮图层。
6. 多角色围绕同一目标做不同选择；不要让所有角色同步冲、同步喊、同步挥手。
7. 核心道具始终是同一实体；交接、打开、放下或离场只按剧情需要发生一次。
8. 策划秒数用于判断内容是否装得下，不自动变成模型必须严格执行的时间戳。
9. 失败保险只保护本条真正容易坏的身份、数量、时序、道具和 POV 因果，不规定固定条数。
10. 不强制 cinematic、8K、每镜 3–5 句、镜头／焦段／角度配额或不同平台的重复版本。

## 工作流

### 新视频

1. 确认时长、比例、出镜角色、参考素材、中心事件、最终状态和声音权限。
2. 若用户未指定时长，默认 15 秒；若指定其他时长，以用户要求为准。
3. 普通日常题材已有角色身份资产时，直接写提示词；没有具体失败证据时，不额外索要组合场景图、动作图或故事板。
4. 先规划几个必要状态变化，再决定一段连续生成还是多个镜头；不按固定节点数凑内容。
5. 为每张参考图分配职责：锁什么、不继承什么、冲突时谁优先。
6. 写一份干净、可复制的最终提示词。若用户只要提示词，不附长篇理论。

### 成片复查

按以下顺序输出：

> 预期 → 实际可见 → 唯一主故障 → 一个修正杠杆 → 保持不变项

一次只改一个主变量。若只是局部失效，给最小补丁，不整份推翻。

## 输出要求

最终提示词使用中文导演描述。角色实际发出的精确拟声或台词按当前角色权限保留。没有真实素材标签时不虚构 `@角色名`；使用全程一致的普通角色名。

交付优先级：

- 新写：完整提示词优先；
- 修订：保留有效结构并交付完整修订版；
- 审核：区分通过项、阻塞项和建议项；
- 诊断：只指出一个主故障；
- 通过：冻结，不修改。
