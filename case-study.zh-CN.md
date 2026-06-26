# 案例复盘：从旅行意图到 AI 周末 Playbook

[English](case-study.md) | [中文](case-study.zh-CN.md)

## 一句话总结

我用 AI 把一个 Oaxaca 周末旅行想法，转化成了双语自助旅行手册和可执行的 weekend playbook，并把过程抽象成一套可复用的旅行手册工作流。

## 起点

最初的需求很简单：

- 我想要一份 Oaxaca 周末旅行手册。
- 我希望它是 self-guided，而不只是景点清单。
- 我希望它是双语的，便于不同场景下阅读和使用。
- 我在意文化理解、路线逻辑和真实执行，而不只是打卡。

## 哪些地方有效

### 1. 先要 context，再要 itinerary

当 prompt 从：

```text
Give me a Oaxaca itinerary.
```

变成：

```text
先解释 Oaxaca 的文化和街区逻辑，再基于这些逻辑生成一条自助路线。
```

输出明显更有用。它不再只是 checklist，而更像一个帮助我理解城市的入口。

### 2. 迭代 artifact 类型

这次有效的迭代路径是：

```text
双语 guide
-> 修订版 self-guided guide
-> weekend playbook v1
-> weekend playbook v2
```

每个版本承担不同任务：

- Guide：解释什么值得理解。
- Self-guided version：让内容脱离人工讲解也能使用。
- Playbook：帮助旅行中做决策。
- V2：减少摩擦，让顺序和执行更自然。

### 3. 把 AI 当作格式伙伴

真正的价值不是 AI 知道多少 Oaxaca 信息。

更重要的是它帮助我组织了：

- 顺序
- 决策点
- 双语解释
- 地图和路线意识
- 离线可用性

## 下次可以改进什么

- 保留完整 prompt 历史。
- 为文化和行程判断补充来源链接。
- 增加一份 v1 到 v2 的差异说明。
- 旅行后做一次 post-trip review。
- 除 PDF 外，再导出 HTML 版本。

## 长期可沉淀的东西

生活类 AI 互动里，最值得沉淀的不是表层结果。

不存：

- 每个餐厅
- 每个开放时间
- 一次性的旅行 logistics

要存：

- 让结果变好的工作流
- 输出背后的个人偏好和品味
- 可以复用或展示的 artifact
- 能改善未来 AI 协作的反思

## 可迁移模式

```text
我不想要泛泛的旅行推荐。
我想要一份自助 artifact，帮助我理解这个地方，并在现场做决策。
请先讲文化逻辑，再讲路线逻辑，最后生成可执行 playbook。
```
