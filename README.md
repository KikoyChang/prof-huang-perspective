# Prof. Huang Perspective Skill

这个仓库打包了一个 Codex Skill，用于从黄孙权 / Prof. Huang 相关的公共思想框架出发，辅助分析、批评和规划问题。（Claude code 和其他的agent理论上也可以学习）

这个 skill 适用于网络社会、空间生产、社会性艺术、田野行动、出版与档案基础设施、AI 供应链、协议政治、Web3/P2P、研究设计和学术写作方法等主题。

它不代表Prof. Huang本人观点，而是一个基于研究所的课程框架材料、网络社会研究所网站以及heterotopias、网络公开材料和研究笔记整理出来的结构化思考工具。

## 功能

- 拯救笨蛋学生，尝试以prof.Huang的视角分析技术、艺术、空间、网络、政治经济、行动、档案、物质地图和研究设计等视角回答或分析问题。
- 帮助笨蛋学生把一个普通问题转成“网络社会 / 空间生产 / 政治经济 / 行动方案 / 田野 / 基础设施”的分析，并把宽泛主题转化为可研究的问题意识、文献地图、案例逻辑、方法论和论文结构。
- 做研究写作指导，比如论文选题、文献综述、方法论、案例研究、问题意识、理论提升。
- 评价艺术与社会项目时，关注它是否生产了新的关系、公共性和行动，而不只是形式是否精致。
- 分析 AI 时不会只谈模型能力，而会追问芯片、算力、数据中心、训练劳动、法律梯度、全球南方、供应链。


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

把这个文件夹复制到你的 Claude/Codex skills 目录：

```powershell
Copy-Item -Recurse -Force .\prof-huang-perspective "$env:USERPROFILE\.codex\skills\prof-huang-perspective"
```
或者你也可以尝试
```powershell
git clone https://github.com/KikoyChang/prof-huang-perspective.git 
```

然后开启一个新的对话，并通过 skill 名称调用：
```text
Use the prof-huang-perspective skill to analyze this problem:
[在这里粘贴你的问题]
```

也可以直接用中文调用：

```text
请使用 prof-huang-perspective skill，用黄孙权 / Prof. Huang 的公共思想框架分析下面的问题：
[你的问题]
```

## 示范指令
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
## 说明
所有素材均来自网研所，但是由于缺少空间生产的内容以及笔记的局限性，所以如果能够提供新的相关材料并据此扩展参考资料、分析框架和使用方式，欢迎维护和更新这个 skill。

## 致谢
本skill的蒸馏灵感源于女娲skill（[nuwa-skill）](https://github.com/alchaincyf/nuwa-skill) 
把人的思维框架变成可运行的代码。
不是让 AI 模仿某个人说话，而是提炼他们 怎么想问题。

**同时感谢prof.Huang的鼓励**
