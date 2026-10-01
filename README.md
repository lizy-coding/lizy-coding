<div align="center">

# 👋 Hi, I'm Lizy

### 🧠 IoT · Flutter · AI Agent Engineering

围绕 IoT 设备能力与跨平台业务场景，  
使用 AI Agent 连接需求拆解、工程实现、质量验证与持续交付。

Building IoT and Flutter applications through  
AI-assisted engineering and agent-orchestrated workflows.

</div>

---

# 🚀 关于我

我是一名长期从事 **IoT 与 Flutter 跨平台开发** 的工程师。

过往工作主要围绕设备连接、系统能力接入、平台插件和复杂状态治理展开：

**Flutter 与跨平台工程**

- Android、macOS、Windows 平台能力接入与业务适配。
- Flutter Plugin、MethodChannel / EventChannel 与原生接口封装。
- 原生能力向 Dart API 的稳定映射，以及平台差异与降级策略。
- 桌面窗口、文件选择、媒体播放与复杂界面交互。
- 异步状态、订阅和应用生命周期管理。

这些经历让我持续关注一个问题：

> 如何把依赖设备、平台和异步状态的复杂需求，  
> 转化为边界清晰、可以验证、能够持续交付的业务能力。

如今 LLM 提供了很多有效的工作流

**AI Agent 与工程实践**

- 使用 Agent 辅助需求拆解、插件开发、功能实现与问题定位。
- 用项目上下文、架构规则和任务契约约束代码修改。
- 探索基于 LangGraph 的任务编排、隔离执行与评审集成。
- 结合静态分析、自动化测试和真实平台运行验证开发结果。

---

# 📡 IoT & Cross-platform Experience

IoT 开发不只是连接设备，也包括设备状态、权限、生命周期、异常恢复和平台差异的系统治理。

### 🔌 设备与系统能力

* Bluetooth / BLE 设备发现与通信
* USB 设备枚举、权限申请和热插拔监听
* 电池状态、系统事件与后台任务
* Android 与桌面系统能力封装
* 设备事件流和 Flutter 状态同步

### 🖥 跨平台业务适配

* Android、macOS、Windows 差异治理
* Flutter Plugin 与 MethodChannel 设计
* 原生能力向 Dart API 的稳定映射
* 桌面文件选择、窗口和媒体能力
* 平台可用性、降级策略与异常边界

### 📦 相关项目

🛠 Flutter Forge

**把 Flutter 的底层机制、工程架构与跨平台能力，变成可以运行、交互和观察的学习现场。**

目前组织了 23 个学习模块，涵盖三棵树、事件循环、Stream、Isolate、状态管理、动效、3D，以及网络和平台能力。通过统一的模块目录与教学页面，将机制讲解和实际操作连接起来。

近期持续完善学习内容、响应式导航与跨平台适配，并提供 Web 在线体验；桌面端结合多窗口探索不同学习场景，平台受限能力也会给出明确说明。

[项目仓库](https://github.com/lizy-coding/flutter_forge) · [在线体验](https://lizy-coding.github.io/flutter_forge/)
<img width="1312" height="922" alt="image" src="https://github.com/user-attachments/assets/41f00c31-b0ba-46b6-9359-2ff8d16b81aa" />


🎨 G-code Core

**面向 Flutter 应用的 G-code 解析、轨迹构建、播放控制与图形可视化组件。**

从读取加工指令，到生成运动轨迹，再到场景绘制与播放，将文本指令转化为可以观察的加工过程，也为探索解析、交互与图形渲染提供了具体场景。

当前结合 Flutter GPU 实现可视化渲染，发布包支持 macOS 与 Android，持续打磨轨迹呈现和播放体验。

[项目仓库](https://github.com/lizy-coding/gcode_core)

![G-code Core 演示](https://raw.githubusercontent.com/lizy-coding/gcode_core/master/gcode_print.gif)
<img width="1314" height="1156" alt="image" src="https://github.com/user-attachments/assets/d8cade31-0200-420c-ba59-e7becdd018f1" />


🧠 Agent Hub

**基于 LangGraph 的工作区管理与开发任务编排实践。**

通过项目注册表组织工程上下文，将能力分析、任务拆解、Worker 执行、范围检查与结果验证连接起来。任务在受管 worktree 中执行，项目特有规则通过 Adapter 接入。

Flutter Forge 是主要落地与验证工程。我在这个过程中探索如何让 Agent 在明确的上下文和修改边界内完成任务，并用代码、检查与运行结果验证交付。

[项目仓库](https://github.com/lizy-coding/agent-hub)


---

# 🤖 AI-assisted Plugin Engineering

在当前阶段，我仍然持续借助 AI Agent 建设 Flutter 插件和跨平台基础能力。

Agent 可以显著提高实现速度，但平台插件涉及原生 API、生命周期、线程、权限和系统差异，不能只依赖代码生成结果。因此，我更关注如何让 Agent 在明确的工程约束中工作。


# 🚀 Recent Focus


- **学习与表达**：让 Flutter 的底层机制和工程经验更容易被观察、理解与复用。
- **跨平台实践**：探索图形渲染、设备通信与原生能力在实际应用中的落地。
- **Agent 工程**：将有效的开发经验沉淀为上下文约束、任务流程与验证工具。

我关注清晰的工程边界、可验证的结果，以及工具在实际项目中的价值。

### Agent 编排

* 建立项目注册表和项目级 Adapter
* 构建任务拆解、Worker 执行和集成流程
* 固化仓库路径、修改范围与架构边界
* 增加发布托管和安全执行通道
* 同步 Agent 契约、项目事实和任务状态

### Flutter 业务交付

* 推进 Flutter Forge 的桌面端与 Android 适配
* 建设模块脚手架和模块准入检查
* 完善响应式导航和平台能力边界
* 处理视频、USB、文件选择与多窗口能力
* 建立 macOS、Windows 和 Android 验收流程

### 图形业务能力

* 推进 G-code 解析与场景建模
* 将场景渲染统一到 Flutter GPU
* 增加 macOS GPU 场景验证与验收证据

> 从 IoT 与跨平台经验出发，  
> 借助 Agent 建设工程能力，  
> 再通过编排系统持续完成真实业务交付。

---

# 🧠 Engineering Philosophy

> AI Native ≠ Generate Everything
>
> AI Native =
>
> * Explicit Context
> * Clear Boundaries
> * Structured Execution
> * Verifiable Results
> * Human Accountability

我相信：

* IoT 业务首先需要尊重真实设备和平台边界
* Agent 可以提升执行效率，但不能跳过工程验证
* Prompt 只能表达意图，契约才能约束执行
* Worker 完成任务不代表业务已经验收
* 自动化测试不能完全替代真实平台验证
* 基础设施的价值最终必须通过业务交付体现
* 可持续的 AI 开发依赖编排、治理和反馈闭环

---

# ✍️ Technical Writing

我会持续记录 Flutter、IoT、跨平台 Plugin、Agent 编排、LangGraph、性能与稳定性治理相关实践。

📚 [掘金](https://juejin.cn/user/2085122730895063/posts)


---

# 📫 Contact

📧 [zhenyu_li1998@163.com](mailto:zhenyu_li1998@163.com)

---

<div align="center">

### From connected devices to orchestrated delivery.

IoT experience defines the boundaries.  
Engineering systems provide the foundation.  
Agent orchestration turns them into continuous delivery.

</div>
