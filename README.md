# GPT-based Developer Toolkit

- [localGPT]() — localGPT 可使用 GPT 模型在本地设备上进行聊天，数据在本地运行，且 100% 保密。这个项目的灵感来自于最初的 privateGPT。这个模型用 Vicuna-7B 模型替换了 GPT4ALL 模型，使用 InstructorEmbeddings 而不是原始 privateGPT 中使用的 LlamaEmbeddings。Embeddings 和 LLM 都将在 GPU 而不是 CPU 上运行。
- [DB-GPT]() — DB-GPT 是一个开源的以数据库为基础的 GPT 实验项目，使用本地化的 GPT 大模型与数据和环境进行交互，无数据泄露风险，100% 私密，100% 安全。DB-GPT 为所有以数据库为基础的场景，构建了一套完整的私有大模型解决方案。此方案因为支持本地部署，所以不仅仅可以应用于独立私有环境，而且还可以根据业务模块独立部署隔离，让大模型的能力绝对私有、安全、可控。
- [AudioGPT]() — AudioGPT 是一个借助大语言模型 (LLM) 处理音频的工具。AudioGPT 在收到用户请求时使用 ChatGPT 进行任务分析，根据语音基础模型中可用的功能描述选择模型，用选定的语音基础模型执行用户指令，并根据执行结果汇总响应。借助 ChatGPT 强大的语言能力和众多的语音基础模型，AudioGPT 能够完成几乎所有语音领域的任务。具体来说，AudioGPT 运行过程可以分成 4 个阶段：模态转化、任务分析、模型分配和回复生成。
- [Auto-GPT]() — Auto-GPT 是基于 GPT-4 的实验性项目，目的是让 GPT-4 完全自动化运行。除了能够自动联网搜索、搜集各种数据之外，它还能尝试访问当下的主流网站和平台，利用 GPT 进行文件存储和总结。
- [AgentGPT]() — AgentGPT 用于在浏览器通过可视化方式中部署一个 AutoGPT，开发者自己定义目标，然后让 GPT4 来按照目标持续执行、修正、存储历史数据，最终达成目标。特性 - 可以联网 - 长时间记忆 - 与网站或用户交互。
- [MiniGPT-4]() — MiniGPT-4 使用高级大型语言模型增强视觉语言理解。
- [K8sGPT]() — k8sgpt 是一个扫描 Kubernetes 集群、诊断和分类问题的工具。它将 SRE 经验录入其分析器，并通过 AI 帮助提取并丰富相关的信息。
- [PentestGPT]() — PentestGPT 是基于 GPT4 的自动化渗透测试工具，目前已实现简单的辅助渗透，可提升效率。PentestGPT 旨在自动化渗透测试过程。它基于 ChatGPT 构建，通过 GPT 互动方式，指引渗透测试人员的整体进程和具体操作。
- [Visual ChatGPT]() — Visual ChatGPT 将 ChatGPT 和一系列视觉基础模型 (Visual Foundation Models, VFM) 连接了起来，以支持在聊天过程中发送和接收图像。
- [DoctorGPT]() — DoctorGPT 是一个将 GPT 带入生产，用于错误诊断的工具，它可以监控你的应用程序日志中的问题并对其进行诊断。
- [Chart-GPT]() — Chart-GPT 是一个基于文本输入构建图表的 AI 工具，可在几秒钟内将文本转换为漂亮的图表。
- [DocsGPT]() — DocsGPT 是一种 AI 文档解决方案，可简化在项目文档中查找信息的过程。通过集成强大的 GPT 模型，开发人员可以轻松地提出有关项目的问题，并获得准确的答案。
- [JavaGPT]() — JavaGPT 是一个调用 ChatGPT API 接口的 Java GUI。
- [yakGPT]() — yakGPT 是一个简单的、本地运行的 ChatGPT 用户界面，不需要安装任何应用程序，使你的文本生成速度更快。yakGPT 所有状态都存储在本地的 localStorage 中，因此没有分析或外部服务调用。
- [CodeGPT]() — CodeGPT 是一款Visual Studio Code 扩展，可以通过官方的OpenAI API 使用GPT-3 (预训练生成式转换器) 模型，在多种编程语言中生成、解释、重构和文档化代码片段。 CodeGPT 可用于各种任务，例如代码自动完成、生成和格式化。
- [Codeium]() —  Codeium是一款免费的智能编程助手，类似Github Copilot，目前Codeium提供超过40种语言的代码完成工具，具有闪电般的速度和最先进的建议质量。
