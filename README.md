# 🧰 AI 实战工具箱 · Awesome AI Skills (中文)

收集我在 X 上分享过的 GitHub AI skill、Agent skill、MCP server 和开源 AI 工具。每条都核实过用法，持续更新。

> ⭐ 数为收录当天的数字，仅供参考。

| 日期 | 项目 | 一句话说明 | 怎么装 / 怎么用 | ⭐（收录时） |
|---|---|---|---|---|
| 2026-10-12 | [mattpocock/skills](https://github.com/mattpocock/skills) | Agent skill 合集，`/grill-me` 先把需求问清楚再写代码 | 按仓库 README 安装 skill，对话里用 `/grill-me` | 286.2k |
| 2026-10-12 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 给 AI 编程助手装跨会话记忆 | `npx claude-mem install` | 99.7k |
| 2026-10-12 | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 用 HTML 写视频、渲染成 MP4，自带 agent skill | `npx hyperframes init` / `npx hyperframes render` | 61k |
| 2026-10-12 | [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | 给 agent 装 CAD skill：建模、工程图、DfAM、G-code | 以 Claude plugin 安装 | 19.3k |
| 2026-10-12 | [danyuchn/asd-ste100-skill](https://github.com/danyuchn/asd-ste100-skill) | 用航空维修「简明技术英语」规则改写提示词和报错 | `npx skills add danyuchn/asd-ste100-skill` | 约 4.5k |
| 2026-10-12 | [mvschwarz/openrig](https://github.com/mvschwarz/openrig) | 用 YAML 定义多 agent 团队（Claude Code + Codex） | `npm install -g @openrig/cli` 后 `rig up starter` | 约 7.0k |
| 2026-10-12 | [lyogavin/airllm](https://github.com/lyogavin/airllm) | 4GB 显存跑 70B 大模型，不量化、不蒸馏、不剪枝；DeepSeek-V3(671B) 约 12GB 跑 | pip install airllm | 36.8k |
| 2026-10-12 | [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code) | 把 Claude Code、Codex、Pi、OpenCode 等 11 个编程智能体接到 61 家免费 AI 服务商，每月 13 亿免费 token | 一条安装脚本 + 免费 NVIDIA NIM key，5 分钟搞定 | 58.2k |
| 2026-10-12 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 给 Claude Code/Codex/Copilot/Cursor/Pi 等编程智能体装上画图审美：说句人话就自动生成 44 种类型的编辑级 HTML+SVG 图表 | npx skills add cathrynlavery/diagram-design | 52.6k |
| 2026-10-12 | [morluto/rea](https://github.com/morluto/rea) | 给编程智能体装上逆向工程能力：一条 MCP 接入，没源码也能拆解 App/二进制/Electron/.NET/APK/网页，本地分析、结论带证据 | npx rea-agents setup（自动注册 MCP 到 Claude Code/Codex/Cursor/Gemini CLI 等；也可 npm install --global rea-agents 用终端 CLI） | 156.6k |
| 2026-10-12 | [mksglu/context-mode](https://github.com/mksglu/context-mode) | 给编程智能体装上上下文"瘦身器"：MCP 沙盒把工具输出锁在上下文之外（315KB 压成 5.4KB，砍掉 98%），会话压缩不失忆（本地 SQLite 存编辑记录/待办），17 个平台通用 | Claude Code：/plugin marketplace add mksglu/context-mode，再 /plugin install context-mode@context-mode；或 npm install -g context-mode；纯 MCP：claude mcp add context-mode -- npx -y context-mode | 27.3k |
| 2026-10-13 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | 给编程智能体装上语义搜代码能力：直接问一句人话（比如权限校验在哪做的），就把相关文件和源码摘录一次吐给 agent，不用逐个文件翻；实测 8/10 个 SWE-bench 任务通过，费用降近三成 | npm install -g @dzhng/jevgrep，然后 jg auth（需 Vercel AI Gateway/OpenRouter 等 provider key）、jg skill 装 skill（或 npx skills add dzhng/jevgrep --skill jevgrep） | 2.6k |
| 2026-10-13 | [joeseesun/qiaomu-download](https://github.com/joeseesun/qiaomu-download) | 给 AI 智能体装万能视频下载器：一句“下载这个+链接”搞定 YouTube/B站/X/抖音/小红书等 20+ 平台视频，还提 MP3、扒字幕、ffprobe 验真 | npx skills add joeseesun/qiaomu-download（需 Python 3.10+、yt-dlp、ffmpeg） | 395 |

---

新条目追加在表格末尾。欢迎 Star ⭐
