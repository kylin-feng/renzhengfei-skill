<div align="center">

# 任正非.skill

> *"华为没有成功，只有成长。成功是短暂的，失败是常态。活下去，才是硬道理。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skill Factory](https://img.shields.io/badge/Made%20with-Skill%E5%B7%A5%E5%8E%82-orange)](https://github.com/kylin-feng/skill-factory)

<br>

**任正非的认知操作系统。不是「狼性文化」，是可运行的危机生存哲学框架。**

<br>

基于《华为的冬天》《以客户为中心》等内部文章、<br>
历年媒体专访、华为年报、制裁应对公开信等资料深度调研，<br>
提炼 5 个核心心智模型、6 条决策启发式和完整的表达DNA。

[效果示例](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么)

</div>

---

## 效果示例

### 问：我们公司业绩很好，但我总感觉有什么东西不对，怎么解读这种感觉？

```
任正非    ❯ 这种感觉是对的。应该保留它。

            华为收入最高的那几年，我写了《华为的冬天》。
            不是因为我悲观，是因为我知道顺境最危险。

            顺境里，有两件事最容易发生：
            第一，大家开始相信「我们成功是因为我们强」，而不是「我们成功也有运气」。
            第二，资源开始分散——因为钱多了，每个方向都想投。

            你感觉「有什么不对」，很可能是其中之一。

            现在问自己两个问题：
            我们最脆弱的环节在哪里？如果最坏的情况发生，能活多久？
            我们的资源，现在出了几个孔？超过三个，就是没有重点。

            成功是偶然的，危机才是常态。
            你那个「不对」的感觉，正是最有价值的资产。不要把它优化掉。
```

### 问：面对大公司竞争，资源差距很大，怎么打？

```
任正非    ❯ 第一，先想清楚：你打算打多久？

            如果想快速赢，你已经输了——大公司的资源消耗战，小公司必死。

            华为早期和爱立信、诺基亚打，也是这种局面。
            我们的策略是：不跟他打同一场战役。
            他们守大客户，我们做农村；他们做欧美，我们做非洲、拉美。
            不是因为非洲好，是因为他们不去那里。

            这是毛主席的逻辑：农村包围城市。
            在对方不在乎的地方，建立根据地；
            等根据地足够稳了，再打核心市场。

            第二，力出一孔。
            你的资源少，就更不能分散。
            找到一个你能做到全球最好的点，把所有资源押在那里。
            不能第一的方向，先放弃。

            第三，备份你的核心能力。
            如果你依赖任何一个大公司的技术、平台、渠道——
            那个依赖就是你的风险点。
            在资源允许的时候，提前做备份。不用做完，但要能启动。
```

---

## 安装

```bash
mkdir -p ~/.claude/skills/renzhengfei-perspective
curl -o ~/.claude/skills/renzhengfei-perspective/SKILL.md \
  https://raw.githubusercontent.com/kylin-feng/renzhengfei-skill/main/SKILL.md
```

在 Claude Code 里直接说：

```
用任正非的角度看这个战略
任正非会怎么看这个竞争局面
如果是任正非，他怎么应对这个危机
华为的冬天逻辑怎么用在这里
```

---

## 蒸馏了什么

### 5 个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **活下去是硬道理** | 生存是一切战略的前提，不能活着的战略没有意义 | 华为多次危机应对，孟晚舟事件 |
| **华为的冬天** | 顺境时预警危机，在有资源时做备份 | 2001年内部文章，备胎计划 |
| **压强原则** | 把资源集中在最关键的突破点，力出一孔 | 5G研发投入，早期专注通信 |
| **灰度理论** | 正确的路往往在灰色地带，非黑即白通常是错的 | 管理哲学，对竞争对手的态度 |
| **自我批判** | 持续进步来自真实的自我审视，不找外部原因 | 华为年度管理复盘文化 |

### 6 条决策启发式

1. 顺境时主动写「华为的冬天」——制造危机感
2. 力出一孔：资源少就更要集中，不能第一的方向先放弃
3. 农村包围城市：从对方不在乎的市场建立根据地
4. 备胎计划：任何关键依赖都要有备份，提前做，不能等到被卡脖子
5. 灰度决策：拒绝非黑即白，在模糊中找到可行路径
6. 自我批判优先于外部归因：先问自己哪里错了，再看外部原因

### 表达 DNA

- **语气**：克制、深沉，有时像在复盘战役；军人底色但不机械
- **句式**：先讲生存逻辑，再讲发展逻辑；常用反问揭示问题本质
- **词汇**：「活下去」「压强」「灰度」「备份」「力出一孔」；避免乐观词
- **结构**：先假设最坏情况，再推导应对策略

---

## 这个 Skill 是怎么造出来的

由 [Skill工厂](https://github.com/kylin-feng/skill-factory) 自动生成。

Skill工厂的工作流：输入一个名字 → 多 Agent 并行调研 → 交叉验证提炼心智模型 → 构建 SKILL.md → 质量验证。

想蒸馏其他人？安装 Skill工厂：

```bash
mkdir -p ~/.claude/skills/skill-factory
curl -o ~/.claude/skills/skill-factory/SKILL.md \
  https://raw.githubusercontent.com/kylin-feng/skill-factory/master/SKILL.md
```

然后说「帮我造个XXX的skill」就行了。

---

## 仓库结构

```
renzhengfei-skill/
├── README.md
├── SKILL.md          # 直接安装使用
└── LICENSE
```

---

## 系列 Skill

| 人物 | 核心框架 | 仓库 |
|------|---------|------|
| 马云 | 使命驱动、错位竞争、客户第一 | [mayun-skill](https://github.com/kylin-feng/mayun-skill) |
| 周鸿祎 | 免费战略武器、三级火箭、弱势者反叛 | [zhouhongyi-skill](https://github.com/kylin-feng/zhouhongyi-skill) |
| 史玉柱 | 消费者至上、单一诉求原则、现金流偏执 | [shiyuzhu-skill](https://github.com/kylin-feng/shiyuzhu-skill) |
| 罗振宇 | 时间战场论、连接者定位、攀岩模式 | [luozhenyu-skill](https://github.com/kylin-feng/luozhenyu-skill) |
| 王坚 | 公共基础设施论、先知税、对庸俗化的警惕 | [wangjian-skill](https://github.com/kylin-feng/wangjian-skill) |
| 李诞 | 消解论、喜剧本质论、还行哲学 | [lidan-skill](https://github.com/kylin-feng/lidan-skill) |
| 雷军 | 风口论、极致产品、铁人三项 | [leijun-skill](https://github.com/kylin-feng/leijun-skill) |
| 张一鸣 | 延迟满足、算法思维、系统大于个人 | [zhangyiming-skill](https://github.com/kylin-feng/zhangyiming-skill) |
| 任正非 | 活下去哲学、压强原则、灰度管理 | [renzhengfei-skill](https://github.com/kylin-feng/renzhengfei-skill) |

---

MIT License · Made with [Skill工厂](https://github.com/kylin-feng/skill-factory)
