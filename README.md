# 美团运营知识与决策助手

<p align="center">
  <img src="assets/meituan-ops-banner.svg" alt="美团运营知识与决策助手" width="100%" />
</p>

<p align="center"><strong>把培训资料，变成可执行的门店增长动作。</strong></p>

> 把零散的培训资料、店铺案例和运营经验，整理成一套可以持续更新的美团商家运营方法库。

![Meituan Operations](https://img.shields.io/badge/Agent%20Skill-Meituan%20Operations-e63946?style=for-the-badge)
![Knowledge Base](https://img.shields.io/badge/Knowledge%20Base-16%20sources-1d3557?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Continuously%20updated-2a9d8f?style=for-the-badge)

<p align="center">
  <img src="assets/ops-loop.svg" alt="运营增长闭环" width="680" />
</p>

## 它能解决什么问题

美团运营建议很容易散落在课程、截图、聊天和个人经验里。这个 skill 把它们整理成可调用的工作框架，帮助商家和运营人员从“店铺哪里有问题”走到“下一步具体做什么”。

```mermaid
flowchart LR
    A[店铺资料] --> B[定位与页面]
    B --> C[团购与商品]
    C --> D[自然流量 / 推广通]
    D --> E[履约与评价]
    E --> F[数据复盘]
    F --> B
```

## 适合谁

- 美团商家老板和店长
- 本地生活运营、代运营和咨询团队
- 需要批量诊断门店的新手运营
- 想把培训资料沉淀成个人方法论的操盘手

## 可以做什么

| 场景 | 输出 |
|---|---|
| 店铺装修 | 基础信息、入口图、头图、相册、视频和页面承接建议 |
| 团购设计 | 引流款、主推款、利润款、价格梯度和服务限制 |
| 流量增长 | 自然流量、关键词、推广通测试和漏斗诊断 |
| 服务口碑 | 在线咨询、评价管理、差评处理和服务闭环 |
| 数据经营 | 经营评分、经营参谋、指标口径和实验计划 |
| 风险控制 | 履约、虚假购买、流量炒作和评价合规检查 |
| 客户方案 | 诊断、优先级、负责人、截止时间和成功指标 |

## Skill 目录

`skill/` 是可直接安装或复制到 Agent Skills 目录的完整 skill：

- `SKILL.md`：核心框架和章节路由
- `chapters/`：7 个专题章节
- `glossary.md`：运营术语表
- `patterns.md`：可复用方法与反模式
- `cheatsheet.md`：装修、组品、投放和复盘速查表

## 使用示例

```text
假如我是洗鞋店，帮我设计美团店铺首页和三个团购套餐。

我的店铺曝光不少，但点击很低，应该先查什么？

帮我做一个 14 天的美团运营测试计划，并给出每项成功指标。
```

## 资料原则

skill 会区分平台规则、培训方法、门店事实和待验证推断。涉及当前费用、处罚、功能入口、评分权重、活动资格和广告机制时，应以当前官方规则或商家后台为准。

本仓库中的内容是基于用户提供资料生成的结构化总结，不包含培训课件原文的完整复制，也不承诺排名、销量或 ROI。

## 来源与更新

当前版本基于 16 份用户提供的美团运营 Markdown 资料生成。新增课程、截图摘录、行业案例或后台数据后，可继续折入 skill，更新章节、术语和速查表。
