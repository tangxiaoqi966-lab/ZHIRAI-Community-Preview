<p align="center">
  <img src="./icons.svg" alt="ZHIRAI Logo" width="120" />
</p>

# AI Short Drama Studio

### by ZHIRAI

Repository: `ZHIRAI-Community-Preview`

AI Short Drama Studio 是一个面向 AI 短剧生产的创作控制台，目标是把“主题 -> 大纲 -> 项目 -> 剧本 -> 角色 -> 视频 -> 配音 -> 字幕 -> 合成”整条流程串成一个可执行的工作流。

AI Short Drama Studio is a creative control console for AI short-drama production. It is designed to turn the full path from "topic -> outline -> project -> script -> character -> video -> voice -> subtitle -> final composition" into an executable workflow.

当前仓库定位为：

This repository is positioned as a public-facing preview under the `ZHIRAI` brand:

- `Community Preview`
- `Early Development / WIP`
- `非商用公开展示版`

这不是完整商业版。部分核心流程、关键 Prompt、商业化能力、私有调度逻辑和敏感部署细节仍保留在本地，不在公开范围内。

This is not the full commercial edition. Some core workflows, key prompts, commercial capabilities, private orchestration logic, and sensitive deployment details are intentionally kept local and are not part of the public scope.

## 项目定位 / Project Positioning

- 项目名称：`AI Short Drama Studio`
- 品牌名称：`ZHIRAI`
- 仓库名称：`ZHIRAI-Community-Preview`

- Project title: `AI Short Drama Studio`
- Brand: `ZHIRAI`
- Repository name: `ZHIRAI-Community-Preview`

## 当前展示 / Preview

![ZHIRAI 登录页](docs/images/zhirai-login.png)
![ZHIRAI 控制台](docs/images/zhirai-dashboard.png)
![ZHIRAI 系统设置](docs/images/zhirai-settings.png)

## 核心流程 / Core Workflow

```text
用户输入主题
  -> AI 生成故事大纲
  -> 用户确认
  -> 自动创建项目
  -> AI 生成剧本
  -> 角色设计 / 角色图
  -> 场景与镜头编排
  -> 视频生成
  -> 语音 / 字幕 / BGM
  -> 合成与增强
  -> 输出成片
```

```text
User provides a topic
  -> AI generates a story outline
  -> User confirms the outline
  -> Project is created automatically
  -> AI generates the script
  -> Character design / character images
  -> Scene and shot planning
  -> Video generation
  -> Voice / subtitles / BGM
  -> Composition and enhancement
  -> Final output
```

## 当前已实现 / Implemented

- `ZHIRAI` 品牌化控制台、登录页、设置页基础界面
- 主智能体对话入口
- 大纲生成与项目创建主链路
- 短剧 pipeline 主骨架
- 基础模型配置与模型广场入口
- 运行时状态查询、启动、停止的基础控制接口
- 按步骤调度模型的后端基础能力
- 前端对 pipeline 进度和富消息的基础展示

English summary:

- `ZHIRAI` branded console, login page, and settings basics
- Primary agent chat entry
- Outline generation and project creation main flow
- Core short-drama pipeline skeleton
- Model configuration page and model market entry
- Basic runtime status, start, and stop control endpoints
- Backend foundations for step-based model orchestration
- Frontend progress and rich-message display for the pipeline

## 当前未完成 / 未完全开放 / Not Yet Finished or Not Fully Public

- 完整本地模型自动部署脚本
- 全量视频模型、语音模型、音乐模型的一键拉起
- 高级角色一致性与场景一致性
- 口型同步的完整高质量链路
- 商业版功能：计费、支付、套餐、用户权益系统
- 云端 GPU 调度、成本控制、任务优先级、完整失败重试策略
- 关键 Prompt 完整版本
- 部分高级工作流编排细节

English summary:

- Full local model auto-deployment scripts
- One-click bootstrapping for all video, voice, and music models
- Advanced character and scene consistency systems
- Full high-quality lip-sync pipeline
- Commercial features such as billing, payment, plans, and user rights
- Cloud GPU orchestration, cost control, job priority, and full retry strategies
- Full versions of key prompts
- Some advanced workflow orchestration details

## 公开范围说明 / Public Scope

本仓库用于展示项目方向、产品结构、基础代码组织和当前开发进度。

This repository is used to present the project direction, product structure, public-facing code organization, and current development progress.

公开内容优先包含：

Public content mainly includes:

- 产品思路
- 工作流结构
- 基础前后端实现
- 部分可展示的 AI 生产链路
- 路线图与开发进度
- 可公开的界面截图

以下内容默认不在公开授权范围内，或不随公开版完整提供：

The following items are not included in the public authorization scope by default, or are intentionally not fully provided in the public edition:

- 商业化模块
- 私有部署脚本
- 核心 Prompt 完整版
- 私有调度策略
- API 密钥、环境变量、敏感配置
- 未公开的重要流程细节

## 路线图 / Roadmap

详见 [ROADMAP.md](ROADMAP.md)。

See [ROADMAP.md](ROADMAP.md) for the detailed roadmap.

## 贡献方式 / Contributing

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution details.

## 欢迎参与 / Welcome

如果你也对下面这些方向感兴趣，欢迎来一起交流、提建议、提 Issue，或者直接提交改进方案：

If you are interested in any of the directions below, you are very welcome to share ideas, open issues, or submit improvements:

- AI 内容创作工作流
- 短剧生成与视频自动化
- 多模型调度与本地部署
- UI / UX 优化
- 提示词工程与 Agent 设计
- 性能优化、稳定性修复、体验改进

无论你是开发者、设计师、内容创作者，还是对 AI 工作流感兴趣的朋友，都欢迎参与 `AI Short Drama Studio` 公开部分的建设。

Whether you are a developer, designer, content creator, or simply interested in AI workflows, you are welcome to contribute to the public-facing part of AI Short Drama Studio.

哪怕只是一个小建议、一个交互想法、一个模型适配经验，或者一条 Bug 反馈，对 `ZHIRAI` 都很有价值。

Even a small suggestion, a UX idea, a model integration experience, or a bug report can be genuinely valuable to `ZHIRAI`.

欢迎提交：

You are welcome to contribute:

- Bug 报告
- 功能建议
- 模型适配建议
- 性能优化建议
- 文档改进

## 许可证与权利 / Licensing and Rights

本项目采用“多层授权”方式，且默认保护 `ZHIRAI` 的品牌与后续商业化权益：

This project uses a layered licensing approach and is designed to protect the `ZHIRAI` brand and its future commercial rights by default:

- 代码：`PolyForm Noncommercial 1.0.0` 风格的非商用约束
- 文档与展示素材：`CC BY-NC-SA 4.0` 风格的非商用共享约束
- 品牌名 `ZHIRAI`、标识、未公开核心内容、商业化扩展能力：`保留全部权利`

请先阅读：

Please read the following first:

- [LICENSE](LICENSE)
- [NOTICE.md](NOTICE.md)

## 重要声明 / Important Notice

你可以在非商用前提下学习、研究、修改、修复本项目的公开部分。

You may study, research, modify, and fix the public parts of this project for non-commercial purposes.

你不能：

You may not:

- 将本项目或其衍生版本用于商业用途
- 直接售卖、转售、收费托管、收费部署
- 以本项目公开内容为基础进行商业交付
- 冒用 `ZHIRAI` 品牌、名称或标识
- 主张获得未公开部分的授权

版权所有者与权利主体：`ZHIRAI`

Copyright owner and rights holder: `ZHIRAI`
