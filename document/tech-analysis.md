# 技术方案分析文档

时间 | 版本号 | 修订人 | 修订内容
----|-----|------|-----
2018-08-20 | 0.1 | xx | 初始化

## 一. 需求介绍

[需求介绍主要描述需求的背景、目标、范围等]

## 二. 需求分析

[需求分析主要全方位地描述需求相关的信息]

[5W 指 Who、When、What、Why、Where]

- Who：需求利益干系人，包括开发者、使用者、购买者、决策者等。
- When：需求使用时间，包括季节、时间、里程碑等。
- What：需求的产出是什么，包括系统、数据、文件、开发库、平台等。
- Where：需求的应用场景，包括国家、地点、环境等，例如测试平台只会在测试环境使用。
- Why：需求需要解决的问题，通常和需求背景相关]

1H

[这里的 How 不是设计方案也不是架构方案，而是关键业务流程。如果是复杂的业务系统，这部分也可以独立成“用例文档”]

8C

[8C 指的是 8 个约束和限制，即 Constraints，包括性能 Performance、成本 Cost、时间 Time、可靠性 Reliability、安全性 Security、合规性 Compliance、技术性 Technology、兼容性 Compatibility]

注：需求中涉及的性能、成本、可靠性等仅仅是利益关联方提出的诉求，不一定准确；如果经过分析有的约束没有必要，或成本太高、难度太大，这些约束是可以调整的。

## 三. 复杂度分析

[分析需求的复杂度，复杂度常见的有高可用、高性能、可扩展等]

注：实际操作的时候每个约束和限制都要有详细的逻辑推导，避免完全拍脑袋式决策。

## 四. 方案
[方案设计，至少 3 个备选方案，每个备选方案需要描述关键的实现，无须描述具体的实现细节。]

方案 1：xxx

[此处省略方案描述]

方案 2：xxx

[此处省略方案描述]

方案 3：xxx

[此处省略方案描述]

## 五. 方案评估

[备选方案 360 度环评。列出我们需要关注的质量属性点，分别从这些质量属性的维度去评估每个方案形成对比表格，再综合挑选适合当时情况的最优方案。常见的方案质量属性点有：性能、可用性、硬件成本、项目投入、复杂度、安全性、可扩展性等。注意备选方案评估的内容会根据评估会议的结果进行修改，也就是说架构师首先给出自己的备选方案评估，然后举行备选方案评估会议，再根据会议结论修改备选方案文档]

质量属性 | 方案一|方案二|方案三
---|---|---|---
性能|
复杂度|
硬件成本|
可运维性|
可靠性|
可用性|
可扩展性|
人力投入|