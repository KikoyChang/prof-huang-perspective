# Prof. Huang Perspective Skill

This repository packages a Codex skill for analyzing, critiquing, and planning from a Prof. Huang / Huang SunQuan-inspired public intellectual framework.

The skill is intended for questions around network society, spatial production, social art, fieldwork, publishing and archive infrastructure, AI supply chains, protocol politics, Web3/P2P, research design, and academic writing methodology.

It does not claim to represent Huang SunQuan himself. It is a structured thinking aid based on public materials and derived research notes.

## What It Does

- Answers or analyzes problems through space, network, subject, political economy, action, archive, material-map, and research-design lenses.
- Helps transform broad topics into researchable problematics, literature maps, case-study logic, methodology, and paper structures.
- Reviews technology and AI issues beyond product capability, including chips, data centers, training labor, legal gradients, public trust, and supply chains.
- Evaluates art and social projects by whether they produce relationships, publicness, and action, not only by aesthetic polish.
- Provides a reference structure for maintaining or extending the skill with new source material.

## Repository Structure

```text
prof-huang-perspective/
  SKILL.md
  agents/
  references/
    operating-system-full.md
    research/
  scripts/
```

## Install In Codex

Copy this folder into your Codex skills directory:

```powershell
Copy-Item -Recurse -Force .\prof-huang-perspective "$env:USERPROFILE\.codex\skills\prof-huang-perspective"
```

Then start a new Codex conversation and invoke the skill by name:

```text
Use the prof-huang-perspective skill to analyze this problem:
[paste your question here]
```

## Share Prompt For Other Agent Users

Use this instruction when sharing the skill with another agent user:

```text
Please use the `prof-huang-perspective` skill for this task. Treat it as a Huang SunQuan / Prof. Huang-inspired analytical framework, not as Huang SunQuan's own statement. Route the answer through at least three of these lenses: space, network, subject, political economy, action, archive/publishing, material map, annual-conference genealogy, and research design. For current facts, institutions, markets, policies, technologies, or artworks, verify sources first and do not invent quotes or attributions. End with a concrete next move such as fieldwork, a relation map, material map, source audit, prototype, public discussion, archive plan, or research problem framing.

My task is:
[paste task here]
```

## Suggested User-Facing Invocation

```text
[$prof-huang-perspective](path/to/prof-huang-perspective/SKILL.md) 用黄孙权 / Prof. Huang 的公共思想框架分析下面的问题：
[你的问题]
```

## Publishing Notes

Before making the GitHub repository public, review the reference notes for source attribution and choose a license that matches your intended use. If the repository includes substantial research notes, consider separating the skill logic from reference materials or using a content license appropriate for prose notes.
