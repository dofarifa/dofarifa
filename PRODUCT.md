# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

GitHub 上访问个人主页的技术同行、潜在合作者和招聘者。他们需要快速了解 dofarifa 的技术方向、能力范围与近期 GitHub 活动。

## Product Purpose

将 GitHub Profile README 作为一张清晰、可靠的个人技术名片：先说明身份和关注方向，再展示技术栈、公开活动与联系入口。成功意味着访客无需浏览大量仓库，也能迅速判断共同兴趣和合作可能。

## Positioning

以无人机、STM32 嵌入式、机器人和 Web 为交叉定位，呈现软硬件结合的个人技术兴趣，而不是通用的开发者卡片集合。

## Operating Context

主页由 GitHub 渲染 Markdown 和受限 HTML。动态内容依赖公开图片服务及 GitHub Actions，因此第三方可用性、移动端缩放和生成资源分支是长期维护约束。

## Capabilities and Constraints

- 仓库名与 GitHub 用户名均为 `dofarifa`，满足 Profile README 展示条件。
- 使用中英双语内容。
- 贡献蛇由 GitHub Actions 定时生成并发布到 `output` 分支。
- 动态卡片必须使用已验证的服务；避免重复、价值较低或已知不稳定的组件。
- 仅陈述仓库和用户已提供的事实，不虚构履历、组织关系或项目成果。

## Brand Commitments

- 对外名称保留 `kkkk`，GitHub 用户名保留 `dofarifa`。
- 保留粉色与云彩的个人记忆点，以及现有引用文字。
- 保留无人机、嵌入式、Web 和机器人四个关注方向。

## Evidence on Hand

- 当前个人介绍与技术栈：[README.md](README.md)
- 公开 GitHub 活动数据：GitHub 用户 `dofarifa`
- 个人主页：<https://dofarifa.github.io>
- 未提供职业经历、客户证明或可量化成果，后续设计不得代为编造。

## Product Principles

- 身份与方向先于装饰性数据。
- 每个动态组件都应提供新信息，并且可验证、可维护。
- 保持中英双语，但避免同一信息重复两遍造成阅读负担。
- 让软硬件交叉能力成为主页的主要辨识度。
- 在桌面和移动端都保持清晰的阅读顺序。

## Accessibility & Inclusion

所有图片提供有意义的替代文本；不依赖颜色单独传达信息；动态 SVG 尊重服务自身的减弱动画设置，并确保正文在资源加载失败时仍可理解。
