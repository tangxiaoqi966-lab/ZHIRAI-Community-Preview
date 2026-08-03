<p align="center">
  <img src="./icons.svg" alt="ZHIRAI Logo" width="120" />
</p>

# ZHIRAI Community Preview

## AI Short Drama Studio

> An AI-powered end-to-end short drama and story-to-video production platform.
>
> From an idea to a story. From a story to a world. From a world to a film.

---

## 中文说明

`ZHIRAI Community Preview` 是 `AI Short Drama Studio` 的公开预览仓库。

这是一个正在积极开发中的 AI 短剧与 AI 故事视频创作平台。

项目的目标，是让用户只需要提供一个简单的主题、创意或故事设定，系统就能够通过 AI 辅助完成从故事构思、剧本创作、角色设计、场景设计、分镜规划，到视频、音频、字幕以及最终成片的完整创作流程。

这个仓库当前主要用于：

- 公开项目开发进度
- 获取社区反馈
- 收集 Bug 和功能建议
- 与 AI 开发者、独立开发者和创作者交流
- 探索 AI 内容创作的自动化工作流
- 欢迎开发者参与改进和讨论

### 项目愿景

目前很多 AI 视频工具更偏向于这样一条链路：

```text
Prompt
  -> Generate Video
```

而 `AI Short Drama Studio` 想探索的是一条更完整的 AI 内容生产路径：

```text
用户创意 / 主题
  -> AI 故事构思
  -> 故事大纲
  -> 用户确认
  -> 创建项目
  -> AI 剧本创作
  -> 角色设计
  -> 角色视觉生成
  -> 场景设计
  -> 场景视觉生成
  -> 分镜规划
  -> 镜头生成
  -> AI 视频生成
  -> AI 配音 / 音频
  -> 字幕生成
  -> 视频剪辑与合成
  -> 画质增强 / 超分辨率
  -> 最终成片
```

我们希望建立的不只是一个“生成视频”的工具，而是一条真正意义上的：

```text
Idea -> Story -> Script -> Character -> Scene -> Shot -> Video -> Audio -> Subtitle -> Final Movie
```

AI 内容生产 Pipeline。

### 当前状态

项目目前仍处于早期开发阶段，功能、工作流和系统结构都还在持续完善中。

它现在不是一个已经完成的商业产品，而是一个正在快速迭代、持续打磨的实验性项目。

如果你对这些方向感兴趣，欢迎关注这个项目：

- AI 短剧
- AI 电影
- AI 故事生成
- AI 视频生成
- AI 内容自动化
- AI Agent
- AI Workflow
- 多模型 AI Pipeline
- AI 视频后期处理
- 角色一致性
- 场景一致性

### 项目预览

![登录页](./docs/images/zhirai-login-preview.svg)
![控制台](./docs/images/zhirai-dashboard-preview.svg)
![设置页](./docs/images/zhirai-settings-preview.svg)

### 核心流程

#### 1. Idea & Story Generation

用户输入一个简单主题、故事创意或基础设定，AI 生成：

- 故事概念
- 故事背景
- 主要冲突
- 故事大纲
- 发展方向
- 主要角色

用户可以在正式创建项目之前，先查看并确认故事大纲。

#### 2. Project Creation

用户确认故事大纲之后，系统创建独立项目，并统一管理整个创作过程：

```text
Project
├── Story
├── Script
├── Characters
├── Locations
├── Scenes
├── Shots
├── Images
├── Videos
├── Audio
├── Subtitles
└── Final Render
```

#### 3. Script Generation

系统根据已确认的故事设定继续生成完整剧本，包括：

- 剧情结构
- 场景内容
- 角色对白
- 动作描述
- 镜头信息
- 情绪与节奏信息

#### 4. Character & Scene Design

系统根据剧本生成角色设定和场景设定，并逐步扩展角色视觉、场景视觉以及更稳定的一致性能力。

#### 5. Storyboard & Shot Planning

系统根据剧本拆分镜头，规划镜头类型、镜头时长、动作、机位、场景和表现方式，让视频生成逐步从单条 Prompt 走向更加结构化的流程。

#### 6. Video, Audio, Subtitle & Final Composition

后续流程将围绕视频生成、音频生成、字幕生成、视频合成与增强逐步完善，最终形成完整成片。

### 当前仓库定位

这个仓库当前更适合作为：

- 一个持续开发中的项目主页
- 一个记录迭代过程的公开窗口
- 一个欢迎建议、测试、Issue 和 PR 的社区入口

这里最重要的不是“已经全部做完”，而是：

> 这是一个个人开发者正在认真推进、目标明确、愿意持续打磨、并欢迎社区参与的 AI 项目。

### 欢迎参与

如果你愿意参与，欢迎通过这些方式帮助项目变得更好：

- 提交 Bug 报告
- 提出功能建议
- 分享工作流思路
- 提出架构建议
- 参与模型接入讨论
- 提交 UI / UX 改进建议
- 提交 PR

即使你不直接写代码，你的反馈、想法和测试结果也同样有价值。

### 开发理念

这个项目想探索一种新的 AI 内容创作方式：

> AI 不只是一个生成工具，而是整个内容生产流程中的协作伙伴。

用户负责：

```text
Idea
Creativity
Direction
Decision
```

AI 负责：

```text
Planning
Writing
Generation
Automation
Production
```

最终通过人与 AI 的协作完成完整内容创作。

### 路线图

更详细的开发计划请查看 [ROADMAP.md](ROADMAP.md)。

### 贡献方式

如果你希望参与这个项目，请查看 [CONTRIBUTING.md](CONTRIBUTING.md)。

### 许可证

本仓库当前以非商用 Community Preview 的形式发布。

请在使用、修改或传播之前先阅读：

- [LICENSE](LICENSE)
- [NOTICE.md](NOTICE.md)

### 关于 ZHIRAI

`ZHIRAI` 是一个专注于 AI、软件开发与智能内容创作探索的个人技术品牌。

`AI Short Drama Studio` 是 `ZHIRAI` 旗下正在持续开发中的实验性项目之一。

### 支持项目

如果你觉得这个项目有价值，欢迎：

- Star 这个仓库
- Watch 项目更新
- 提交 Issue
- 分享建议
- 参与讨论
- 提交代码

你的每一个 Star、Issue 和建议，都会帮助这个项目继续往前走。

---

## English

`ZHIRAI Community Preview` is the public preview repository for `AI Short Drama Studio`.

This is an actively evolving AI-powered platform for short-drama and story-to-video creation.

The goal is to let a user start with a simple topic, idea, or story setup, and then use AI to assist the full creative path from story ideation, script writing, character design, scene design, and storyboard planning to video, audio, subtitles, and final production.

This repository is mainly used to:

- Share public development progress
- Collect community feedback
- Gather bug reports and feature ideas
- Connect with AI developers, indie builders, and creators
- Explore automated AI content production workflows
- Welcome contributors who want to improve the project

### Project Vision

Many AI video tools today still focus on a path like this:

```text
Prompt
  -> Generate Video
```

`AI Short Drama Studio` aims to explore a more complete AI content production path:

```text
Idea / Topic
  -> AI story ideation
  -> Story outline
  -> User confirmation
  -> Project creation
  -> AI script writing
  -> Character design
  -> Character visual generation
  -> Scene design
  -> Scene visual generation
  -> Storyboard planning
  -> Shot generation
  -> AI video generation
  -> AI voice / audio
  -> Subtitle generation
  -> Editing and composition
  -> Enhancement / upscaling
  -> Final output
```

The goal is not just to generate a video, but to gradually build a real:

```text
Idea -> Story -> Script -> Character -> Scene -> Shot -> Video -> Audio -> Subtitle -> Final Movie
```

AI production pipeline.

### Current Status

The project is still in an early stage, and the features, workflows, and overall system structure are actively being refined.

It is not a finished commercial product. It is an experimental project that is being built and iterated on quickly.

If you are interested in any of the following areas, you are very welcome to follow the project:

- AI short drama
- AI film
- AI story generation
- AI video generation
- AI content automation
- AI agents
- AI workflows
- multi-model AI pipelines
- AI video post-production
- character consistency
- scene consistency

### Preview

![Login](./docs/images/zhirai-login-preview.svg)
![Dashboard](./docs/images/zhirai-dashboard-preview.svg)
![Settings](./docs/images/zhirai-settings-preview.svg)

### Core Workflow

#### 1. Idea & Story Generation

The user starts with a simple topic, story idea, or basic setting. AI then generates:

- story concept
- story background
- major conflict
- story outline
- development direction
- main characters

The user can review and confirm the outline before creating a formal project.

#### 2. Project Creation

After the outline is confirmed, the system creates a dedicated project and manages the whole production flow in one place:

```text
Project
├── Story
├── Script
├── Characters
├── Locations
├── Scenes
├── Shots
├── Images
├── Videos
├── Audio
├── Subtitles
└── Final Render
```

#### 3. Script Generation

Based on the confirmed story setup, the system expands into a fuller script structure, including:

- plot structure
- scenes
- character dialogue
- action descriptions
- shot information
- emotion and pacing cues

#### 4. Character & Scene Design

The system generates character definitions and scene definitions from the script, then gradually extends into character visuals, scene visuals, and stronger consistency control.

#### 5. Storyboard & Shot Planning

The system breaks scripts into shots, planning shot type, timing, movement, actions, camera perspective, and scene context, so video generation becomes more structured than a single prompt flow.

#### 6. Video, Audio, Subtitle & Final Composition

Later stages focus on video generation, audio generation, subtitle generation, composition, and enhancement, with the goal of producing a complete final piece.

### What This Repository Is

Right now, this repository is best understood as:

- a public home page for the project
- a development log in progress
- a community entry point for ideas, testing, issues, and pull requests

The key message is not "everything is finished".

It is this:

> This is a serious long-term AI project built by an individual developer who is actively working on it, refining it, and welcoming community participation.

### Community Preview

If you want to participate, you are welcome to help in any of the following ways:

- report bugs
- suggest features
- share workflow ideas
- discuss architecture
- discuss model integration
- suggest UI / UX improvements
- submit pull requests

Even if you do not contribute code directly, your feedback, testing, and ideas still matter.

### Development Philosophy

This project explores a new way of thinking about AI-assisted content creation:

> AI is not just a generation tool. It is a collaborative partner in the full content production process.

The user provides:

```text
Idea
Creativity
Direction
Decision
```

AI helps with:

```text
Planning
Writing
Generation
Automation
Production
```

The end goal is complete content creation through human-AI collaboration.

### Roadmap

For a more detailed development plan, see [ROADMAP.md](ROADMAP.md).

### Contributing

If you would like to contribute, please read [CONTRIBUTING.md](CONTRIBUTING.md).

### License

This repository is currently released as a non-commercial community preview.

Please read the following before using, modifying, or redistributing any public content:

- [LICENSE](LICENSE)
- [NOTICE.md](NOTICE.md)

### About ZHIRAI

`ZHIRAI` is a personal technology brand focused on AI, software development, and intelligent content creation.

`AI Short Drama Studio` is one of the ongoing experimental projects under the `ZHIRAI` brand.

### Support the Project

If you think this project is valuable, you are welcome to:

- star the repository
- watch the project
- open issues
- share ideas
- join discussions
- contribute code

Every star, issue, and piece of feedback helps move the project forward.
