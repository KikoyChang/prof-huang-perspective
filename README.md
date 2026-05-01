# Prof. Huang Perspective Skill

这个仓库打包了一个 Codex Skill，用于从黄孙权 / Prof. Huang 相关的公共思想框架出发，辅助分析、批评和规划问题。

这个 skill 适用于网络社会、空间生产、社会性艺术、田野行动、出版与档案基础设施、AI 供应链、协议政治、Web3/P2P、研究设计和学术写作方法等主题。

它不声称代表黄孙权本人观点，而是一个基于公开材料和研究笔记整理出来的结构化思考工具。

## 功能

- 通过空间、网络、主体、政治经济、行动、档案、物质地图和研究设计等视角回答或分析问题。
- 帮助把宽泛主题转化为可研究的问题意识、文献地图、案例逻辑、方法论和论文结构。
- 分析技术和 AI 问题时，不只看产品能力，也会追问芯片、数据中心、训练劳动、法律梯度、公共信任和供应链。
- 评价艺术与社会项目时，关注它是否生产了新的关系、公共性和行动，而不只是形式是否精致。
- 为后续根据新材料维护或扩展这个 skill 提供参考结构。

## 仓库结构

```text
prof-huang-perspective/
  SKILL.md
  agents/
  references/
    operating-system-full.md
    research/
  scripts/
```

## 在 Codex 中安装

把这个文件夹复制到你的 Codex skills 目录：

```powershell
Copy-Item -Recurse -Force .\prof-huang-perspective "$env:USERPROFILE\.codex\skills\prof-huang-perspective"
```

然后开启一个新的 Codex 对话，并通过 skill 名称调用：

```text
Use the prof-huang-perspective skill to analyze this problem:
[在这里粘贴你的问题]
```

也可以直接用中文调用：

```text
请使用 prof-huang-perspective skill，用黄孙权 / Prof. Huang 的公共思想框架分析下面的问题：
[你的问题]
```

## 分享给其他 Agent 用户的指令

你可以把下面这段指令发给其他 agent 用户：

```text
请使用 `prof-huang-perspective` skill 完成这个任务。请把它视为一个受黄孙权 / Prof. Huang 公共思想框架启发的分析工具，而不是黄孙权本人的陈述。回答时至少穿过以下三个视角：空间、网络、主体、政治经济、行动、档案/出版、物质地图、年会谱系、研究设计。涉及当前事实、机构、市场、政策、技术或艺术作品时，请先核实来源，不要编造引文或归因。最后请给出一个具体的下一步行动，例如田野调查、关系图、物质地图、资料审计、原型、公共讨论、档案计划或研究问题框架。

我的任务是：
[在这里粘贴任务]
```

## 推荐调用方式

```text
[$prof-huang-perspective](path/to/prof-huang-perspective/SKILL.md) 用黄孙权 / Prof. Huang 的公共思想框架分析下面的问题：
[你的问题]
```

## 开源发布说明

在把这个仓库设为公开之前，建议先检查 `references/` 里的研究笔记是否需要补充来源说明，并选择与你预期用途匹配的 license。

如果仓库中包含较多研究性文字，可以考虑把 skill 逻辑和参考材料分开授权，或为文字内容选择更适合的内容许可协议，例如 CC BY 4.0 或 CC BY-NC 4.0。
