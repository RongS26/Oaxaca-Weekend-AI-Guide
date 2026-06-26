# AI 旅行手册工作流

[English](ai-travel-playbook-workflow.md) | [中文](ai-travel-playbook-workflow.zh-CN.md)

## 目标

用 AI 生成一种能提升文化理解、降低现场决策摩擦的旅行 artifact。

最终产物不应该只是 itinerary，而应该是一份真正能使用的 self-guided playbook。

## 输入 Brief

```text
目的地：
旅行日期 / 时长：
出发区域：
体力水平：
旅行风格：
必选兴趣：
限制条件：
语言需求：
输出格式：
```

## 工作流

### 1. Context First

先要求 AI 解释：

- 文化背景
- 街区逻辑
- 食物 / 市场 / 手工艺脉络
- 基本礼仪和安全注意事项
- 哪些地方被过度包装，哪些是真的值得体验

### 2. Route Logic

把 context 转化成：

- 核心停靠点
- 步行顺序
- 用餐时间
- 需要预约或时间敏感的事项
- 天气、疲劳和排队时的备选方案

### 3. Self-Guided Guide

生成双语 self-guided guide，包含：

- 去哪里
- 为什么值得去
- 到现场应该观察什么
- 累了可以跳过什么
- 必要时提供地图链接

### 4. Weekend Playbook

把 guide 继续转成 playbook：

- 时间块
- 决策点
- Plan A / Plan B
- 体力消耗预估
- 给未来自己的备注

### 5. Iteration

要求 AI 对比版本：

```text
v1 到 v2 改善了什么？
哪些地方更实用了？
哪些地方更有文化理解？
哪些内容太泛泛，应该删除？
```

### 6. Post-Trip Review

旅行结束后记录：

- 哪些判断准确
- 哪些信息错误
- 哪些内容真的帮助了文化理解
- 哪些 prompt pattern 值得复用

## 可复用 Prompt

```text
请帮我为 [目的地] 做一份 self-guided bilingual travel playbook。

不要只列景点。请先解释文化和街区逻辑。
然后生成一条包含时间、决策点、疲劳备选方案和地图链接的实用路线。
优先选择能帮助我理解这个地方的内容，而不是只为了打卡。
请用 [语言偏好] 输出，并让它适合离线使用。
```
