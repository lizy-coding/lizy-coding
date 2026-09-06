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

* Bluetooth / BLE / USB 等设备通信
* Android、macOS、Windows 平台能力接入
* Platform Channel 与原生插件开发
* 设备状态监听、事件流与生命周期管理
* 文件系统、网络、数据库和系统 IO
* Flutter 桌面端与移动端业务适配

这些经历让我持续关注一个问题：

> 如何把依赖设备、平台和异步状态的复杂需求，  
> 转化为边界清晰、可以验证、能够持续交付的业务能力。

当前，我正在将这套经验进一步扩展到 **AI Agent 驱动的软件开发流程**：

* 使用 Agent 辅助插件与基础能力建设
* 使用工程契约约束 AI 生成和修改代码
* 使用编排系统拆解、执行和验证业务任务
* 让 Agent 从单次代码生成走向可治理的持续交付

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

* [pc_connect](https://github.com/lizy-coding/pc_connect) — macOS 和 Windows 的 Bluetooth、Wi-Fi 硬件状态检测与管理插件。
* [flutter_battery](https://github.com/lizy-coding/flutter_battery) — Android 电池监听、低电量监控与通知能力实践。
* [ble_chat_flutter](https://github.com/lizy-coding/ble_chat_flutter) — 基于 Flutter 与 Kotlin 的跨平台 BLE 点对点通信实践。
* [webview_plugin](https://github.com/lizy-coding/webview_plugin) — Android、iOS 和 Windows WebView 业务组件适配。

> 设备能力必须被组织成可复用、可测试、可持续维护的工程边界。

---

# 🤖 AI-assisted Plugin Engineering

在当前阶段，我仍然持续借助 AI Agent 建设 Flutter 插件和跨平台基础能力。

Agent 可以显著提高实现速度，但平台插件涉及原生 API、生命周期、线程、权限和系统差异，不能只依赖代码生成结果。因此，我更关注如何让 Agent 在明确的工程约束中工作。

### 🧩 Agent 辅助开发

* 分析 Dart API 与原生平台接口
* 生成 Flutter Plugin 基础结构
* 补充 MethodChannel / EventChannel 实现
* 梳理平台支持范围和降级策略
* 生成单元测试、Widget 测试与集成测试
* 检查异步订阅、资源释放和生命周期
* 辅助定位构建、依赖和跨平台兼容问题

### 🛡 工程约束

Agent 输出必须经过明确验证：

* API 边界是否稳定
* 平台声明是否准确
* 异步资源是否正确释放
* 不支持的平台是否安全降级
* 静态分析和自动化测试是否通过
* 真实构建与运行结果是否符合预期

### 📦 相关项目

* [file_picker_bridge](https://github.com/lizy-coding/file_picker_bridge) — 面向 macOS 和 Windows 文件管理器的统一文件选择桥接能力。
* [flutterguard](https://github.com/lizy-coding/flutterguard) — Flutter 工程扫描与质量约束工具。
* [flutter_forge](https://github.com/lizy-coding/flutter_forge) — 持续维护平台能力、业务模块、质量门禁和发布流程的 Flutter 工程验证工作区。

> 让 Agent 承担可重复的工程执行，  
> 让开发者负责架构边界、业务判断和最终验收。

---

# 🧭 Agent Orchestration Development

最近一个月，我的主要工作重心已经从单项基础设施建设，转向 **Agent 编排驱动的业务开发**。

相比让一个 Agent 直接修改整个项目，我更倾向于将开发过程拆分成边界明确、可以独立检查的阶段：

```text
业务目标
  ↓
上下文与约束解析
  ↓
能力盘点与任务拆解
  ↓
Agent / Worker 执行
  ↓
范围检查与质量验证
  ↓
评审、集成与交付
```

### 🧠 业务任务建模

在执行前明确：

* 业务目标与验收标准
* 可修改的仓库和目录范围
* 模块依赖与平台边界
* 架构规则和禁止事项
* 必须执行的测试与质量门禁
* 需要保留的人工决策点

任务不再只是自然语言 Prompt，而是带有边界、上下文和验证要求的工程契约。

### 🕸 LangGraph 编排

通过 LangGraph 将复杂开发流程拆分为可观察的执行节点：

* Workspace Bootstrap
* Context Analysis
* Capability Analysis
* Migration Planning
* Development & Decomposition
* Review & Integration
* Release Hosting

每个节点负责有限职责，并通过结构化状态传递结果，降低长流程中上下文漂移和错误扩散的风险。

### 👷 Worker 执行与隔离

* 冻结任务输入和目标范围
* 在独立 worktree 中修改
* 检查实际 diff 和提交身份
* 阻止越界文件进入结果
* 执行项目规定的分析和测试
* 通过评审后再进入真实工程

Worker 的完成状态只是执行结果，不等于业务验收完成。

### ✅ 验证与交付闭环

我正在将以下环节纳入统一编排：

* 代码格式与静态分析
* 单元测试、Widget 测试和集成测试
* 平台构建与运行验收
* Agent 文档与项目契约同步
* Release artifact 检查
* GitHub Release 发布前置验证
* 失败恢复和人工接管边界

最终目标是让 Agent 开发具备三个属性：

* **可控制**：修改范围和权限明确
* **可验证**：结果能够通过代码、测试和运行证据检查
* **可持续**：流程可以重复执行，而不是依赖一次成功的对话

---

# 🔥 Currently Maintained

## 🧠 [Agent Hub](https://github.com/lizy-coding/agent-hub)

由项目注册表驱动的 LangGraph 工作区托管与开发编排平台，覆盖项目上下文、能力分析、任务拆解、Worker 派发、路径门禁、评审集成与发布托管。

Agent Hub 不替代业务仓库，而是为多个工程提供统一的编排、治理和执行控制面。

## 🛠 [Flutter Forge](https://github.com/lizy-coding/flutter_forge)

面向 Flutter 学习、模块开发和跨平台工程验证的持续演进项目。目前维护 Flutter 业务模块、桌面多窗口、Android 响应式适配、平台能力、质量门禁及多平台发布流程。

Flutter Forge 同时也是 Agent Hub 的主要业务落地与验证工程。

## 🎨 [G-code Core](https://github.com/lizy-coding/gcode_core)

面向 G-code 文件的解析、轨迹构建和图形渲染能力，当前聚焦场景建模、Canvas / Flutter GPU 渲染与 macOS 图形能力验证。

这个项目代表了我从工程编排进一步走向具体业务能力开发的实践。

## 🛡 [FlutterGuard](https://github.com/lizy-coding/flutterguard)

Flutter 项目分析和工程质量治理工具，将部分工程经验转换为可执行的检查规则，为 Agent 生成代码和持续集成提供质量边界。

---

# 🚀 Recent Focus

最近一个月，我主要推进了以下工作：

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

📚 [语雀](https://www.yuque.com/diligent_coding/flutter)

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
