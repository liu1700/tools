# Tools & Resources

## 工具资源精选

记录过去一段时间在AI产品开发中使用过的工具和资源，大部分产品提供免费试用或按需付费模式，适合快速启动项目。很多产品都有替代品，并且持续发展，选择适合你的工具。

### 核心原则
在项目初期使用到的SaaS服务免费额度通常足够，不要过早担心规模化问题。产品构建初期应选择最便捷的工具，特别是独立产品应避免过早使用AWS、Azure等复杂平台，遵循"从小而简开始"的原则。

### 欢迎推荐更多工具
如果你知道其他好用的AI、产品构建或生产力工具，欢迎在 [这里](https://github.com/liu1700/tools/issues) 提交建议，我会将它们添加到列表中。

### 🚀 快速启动推荐
- **Cursor + Vercel**：Next.js全栈项目开发部署的高效组合
- **Clerk**：用户注册登录系统，提供Next.js友好型SDK
- **Sentry**：生产环境监控与错误追踪利器
- **Mixpanel**：产品分析可视化工具

### 🤖 大模型集成方案
- **Modal**：通过Python SDK构建模型pipeline，并实现API调用
- **Replicate**：开箱即用的API服务，方便快速对接多种开源大模型
- **OpenRouter**：快速接入各种主流LLM，内置负载均衡和故障转移

（ChatGPT/Claude/Deepseek等基础工具不再赘述，根据实际可用性选择最优模型）


## Infrastructure & Hosting
- [Cloudflare](https://www.cloudflare.com/) - CDN、DNS与安全服务
  - **优点**：全面的网站托管服务，可作为Vercel的良好替代方案
  - **缺点**：Node.js运行时支持不如Vercel完善

- [Vercel](https://vercel.com/) - 网站部署与托管平台
  - **优点**：出色的Next.js集成，强大的Node.js运行时支持，全面的SDK，优秀的AI功能支持，快速实现原型的理想选择，包含数据分析、日志和监控功能

- [Vultr](https://vultr.com/) - 云基础设施与托管
  - **优点**：详尽的文档支持，接受加密货币支付
  - **缺点**：仅限于VPS服务，基础设施产品有限

- [Modal](https://modal.com/) - Serverless 平台
  - **优点**：无服务器平台，支持CPU和多种GPU类型，可以运行自定义模型pipeline，每月30美元免费额度
  - **缺点**：需要了解Modal SDK

## Development Tools
- [Cursor](https://cursor.com/) - 智能代码编辑器
  - **优点**：类VSCode的IDE体验，优秀的AI预测能力，实用的LLM编程助手和代码生成代理
  - **缺点**：免费额度有限，订阅价格较高，部分VSCode插件不兼容，测试功能偶现问题

- [Sentry](https://sentry.io/) - 错误追踪与监控
  - **优点**：丰富的SDK支持，轻松集成，完整的调试、追踪、告警功能，优秀的reply session功能
  - **缺点**：Free quota较少，定价较高

## Authentication & User Management
- [Clerk](https://clerk.com/) - 用户认证管理系统
  - **优点**：完整的认证功能，用户管理模块，友好的SDK

## AI Service Platforms & Tools
- [Boundary ML](https://www.boundaryml.com/) - LLM输出结构化工具
  - 使用BAML DSL实现结构化LLM输出

- [OpenRouter](https://openrouter.ai/) - AI模型路由平台
  - **优点**：接入主流大模型，内置负载均衡和故障转移，支持加密货币支付，快速适配新模型
  - **缺点**：仅限于文本模型

- [Replicate](https://replicate.com/)
  - **优点**：模型种类丰富，用户友好界面，适合模型实验
  - **缺点**：冷启动优化不如Modal，模型自定义能力有限

- [Jina AI](https://jina.ai/) - AI API服务
  - **优点**：核心API功能支持网页抓取、embedding、内容重排，内容分类
  - **缺点**：无法绕过反爬虫保护

- [Exa AI](https://exa.ai/) - 智能搜索与内容生成
  - **优点**：AI搜索引擎，网页爬虫，相似网站发现，内置摘要生成功能
  - **需更多测试才能全面评估**

- [ElevenLabs](https://elevenlabs.io/) - 文本转语音服务
  - **优点**：专注TTS领域，提供丰富语音选项（含社区贡献）
  - **缺点**：语音模型质量中等

- [HuggingFace Models](https://huggingface.co/models) - 机器学习模型库
  - **优点**：海量模型与数据集资源，优秀的共享平台，提供部署服务

- [Cerebras AI](https://cerebras.ai/) - AI推理服务
  - 高速AI推理，但支持的模型有限

## API & Integration
- [Serper](https://serper.dev/) - 谷歌搜索API
  - 程序化获取谷歌搜索结果

- [Algolia](https://algolia.com/) - 搜索与发现平台
  - **优点**：丰富的搜索、过滤、排序和分面功能，支持多数据源注入
  - **缺点**：文档质量一般，AI能力有限

- [DataImpulse](https://dataimpulse.com/) - HTTP代理服务
  - 支持加密货币支付的代理服务

- [Firecrawl](https://www.firecrawl.dev/) - 智能网页抓取工具
  - 可绕过部分反爬机制，测试响应速度快，目前还没投入自己的生产环境使用

## Project Management & Analytics
- [Linear](https://linear.app/) - 项目管理与问题追踪
  - 轻量级Jira替代方案

- [Mixpanel](https://mixpanel.com/) - 产品分析可视化工具
  - **优点**：优秀的文档支持，丰富的可视化选项

## Market Research & SEO & BI & Operations
- [Napkin AI](https://napkin.ai/) - 可视化内容生成
  - 文本转可视化工具，适合storytelling

- [SimilarWeb](https://www.similarweb.com/) - 网站流量分析
  - 免费版提供网站对比、基础流量数据、关键词分析

- [WhoIsMaking.Money](https://whoismaking.money/)
  - 一个有意思的网站，发现一些正在盈利的产品

- [BoringCashCow](https://boringcashcow.com/)
  - 展示一些"boring"但盈利的网站案例

- [Ahrefs](https://www.ahrefs.com/) - SEO工具与分析
  - 全面的SEO分析工具，但仅使用免费浏览器插件

- [SEMrush](https://www.semrush.com/) - 营销与SEO平台
  - 未实际使用，但据说是Ahrefs的流行替代品

- [ReplyGuy](https://replyguy.com/) - 自动回复生成
  - 关键词订阅与回复生成，但需手动复制粘贴回复内容

- [Thunderbit](https://thunderbit.com/) - 智能网页抓取工具
  - 无代码AI网页抓取，支持数据导出与格式化，可以chat with the website

- [Notebook LM](https://notebooklm.google.com/)
  - 集成Google AI，推荐播客生成功能


# GitHub Projects
## AI
- [mem0ai/mem0](https://github.com/mem0ai/mem0)
  - AI记忆系统构建

- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)
  - 开源AI代理框架，可以用来尝试一下AI agent的构建

## Visualization
- [mermaid-js/mermaid](https://github.com/mermaid-js/mermaid) - 文本到图表生成
  - 文本转图表渲染库，支持流程图、时序图、类图

- [markmap/markmap](https://github.com/markmap/markmap) - Markdown思维导图可视化
  - 文本转思维导图渲染库
