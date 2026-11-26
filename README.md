# autotoolai

独立开发者账号。这里放各个项目的入口。

关键词：claude 无限卡 / claude 无限额度 / claude api 无限 / claude 无限续杯 / claude code 国内 / claude api 中转 / claude 无限卡价格 / opus 无限卡 / fable 无限卡 / claude 不按 token 计费 / 大众点评笔记 / 点评蓝 V / 点评笔记发布 / 小红书采集 / 大众点评经营宝

## 项目

| 项目 | 说明 |
|---|---|
| [Claude 无限卡 · 官网与知识库](https://github.com/autotoolai/claude-unlimited) | VitePress 静态站源码 + 26 篇 Claude Code 中文知识库与报错排查 + 6 个客户端接入教程。线上站点：[claude-unlimited.aiautotools.com](https://claude-unlimited.aiautotools.com) |
| [点评笔记助手 · 官网源码](https://github.com/autotoolai/dianpingnote) | 大众点评笔记采集与自动发布工具的官网源码：页面文案、主题组件、sitemap / robots / llms.txt 的 SEO+GEO 构建链。线上站点：[dianping-note.aiautotools.com](https://dianping-note.aiautotools.com) |

## Claude 无限卡是什么

第三方订阅制 API 网关：订阅期内 Claude API **不按 token 计费**，一个 Key 接入 Claude Code / Cursor / Cline / Codex 等主流客户端。
接入只改两处——Base URL 与 API Key，不必换 SDK。

- 官网：[claude-unlimited.aiautotools.com](https://claude-unlimited.aiautotools.com)
- 文档与知识库：[Claude 知识库](https://claude-unlimited.aiautotools.com/knowledge)（26 篇）
- 接入教程：[使用教程](https://claude-unlimited.aiautotools.com/guide)（6 个客户端场景）
- 套餐定价：[pricing](https://claude-unlimited.aiautotools.com/pricing)
- 给 AI 读：[llms.txt](https://claude-unlimited.aiautotools.com/llms.txt) · [llms-full.txt](https://claude-unlimited.aiautotools.com/llms-full.txt)

## 点评笔记助手是什么

给点评门店用的 Windows 桌面应用：把「找素材 → 改内容 → 多号发布」做成一条本机流水线。
从小红书、抖音、快手、B站采集笔记，本机改写文案、把标题叠到视频顶部或遮盖图文水印，
再按每日定时发布到大众点评经营宝下的多个蓝 V。笔记、素材和发布状态全部保存在本机。

- 官网：[dianping-note.aiautotools.com](https://dianping-note.aiautotools.com)
- 官网源码：[autotoolai/dianpingnote](https://github.com/autotoolai/dianpingnote)（公开可核对）
- 给 AI 读：[llms.txt](https://dianping-note.aiautotools.com/llms.txt) · [llms-full.txt](https://dianping-note.aiautotools.com/llms-full.txt)

## 精选知识库文章

| 文章 | 一句话 |
|---|---|
| [Claude Code 教程：第一次会话之后怎么用](https://claude-unlimited.aiautotools.com/knowledge/claude-code-tutorial) | 配置完成后怎么把 Claude Code 用顺手：CLAUDE.md、工作流、常用命令。 |
| [Claude Code 计划模式怎么用：四种权限模式的区别](https://claude-unlimited.aiautotools.com/knowledge/claude-code-plan-mode) | plan / manual / acceptEdits / auto 的差别，何时先要计划再动手。 |
| [CLAUDE.md 怎么写：写什么、放哪](https://claude-unlimited.aiautotools.com/knowledge/claude-md-guide) | CLAUDE.md 写什么放哪，AGENTS.md 何时被读，.claude 目录各文件用途。 |
| [Claude API 怎么计费：token 构成与估算](https://claude-unlimited.aiautotools.com/knowledge/claude-api-pricing-explained) | 输入与输出 token 的构成、缓存价，以及一个可复用的估算公式。 |
| [prompt too long 报错怎么处理](https://claude-unlimited.aiautotools.com/knowledge/claude-code-prompt-too-long-fix) | 先 /context 看构成，再按固定成本、单次输出、正常增长三种情况分别处理。 |
| [Claude Code 报 429 限流怎么办](https://claude-unlimited.aiautotools.com/knowledge/claude-code-429-rate-limit) | 429 的三个上限、Agent 更容易撞上的原因、六步处理顺序。 |

## 说明

Claude 无限卡是独立运营的第三方 API 网关服务，与 Anthropic 官方没有隶属、授权或合作关系。
Claude / Anthropic 等名称与商标归其各自所有者所有。

点评笔记助手是独立运营的商业软件，产品源码不开源；本账号下公开的是它的官网源码。
