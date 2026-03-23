<div align="center">

# 🔬 Awesome Autoresearch

**A curated, high-signal index of autonomous improvement loops, research agents, and descendants inspired by** [**karpathy/autoresearch**](https://github.com/karpathy/autoresearch).

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/alvinunreal/awesome-autoresearch?style=flat-square&label=stars)](https://github.com/alvinunreal/awesome-autoresearch/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/alvinunreal/awesome-autoresearch?style=flat-square&label=updated)](https://github.com/alvinunreal/awesome-autoresearch/commits/main)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](./CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-blue.svg?style=flat-square)](./LICENSE)

<br />

<a href="https://github.com/alvinunreal/awesome-autoresearch">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=alvinunreal&repo=awesome-autoresearch&theme=transparent&hide_border=true&show_owner=false&description_lines_count=2" alt="Awesome Autoresearch repo card" />
</a>

</div>

> [!NOTE]
> **Autoresearch is bigger than one repo now.** The core pattern is simple and powerful: **pick a metric, constrain the scope, let an agent iterate, and keep only what improves**.

This list tracks repos that either:

- directly build on Karpathy's idea,
- explicitly reference `autoresearch`, or
- apply the same edit → verify → keep/revert loop in a clear adjacent domain.

## Contents

- [🛠️ General-purpose descendants](#️-general-purpose-descendants)
- [🔬 Research-agent systems](#-research-agent-systems)
- [💻 Platform ports and hardware forks](#-platform-ports-and-hardware-forks)
- [🎯 Domain-specific adaptations](#-domain-specific-adaptations)
- [📄 License](#-license)

## 🛠️ General-purpose descendants

- [uditgoenka/autoresearch](https://github.com/uditgoenka/autoresearch) — Claude Code skill that generalizes autoresearch into a reusable loop for software, docs, security, shipping, debugging, and other measurable goals.
- [leo-lilinxiao/codex-autoresearch](https://github.com/leo-lilinxiao/codex-autoresearch) — Codex-native autoresearch skill with resume support, lessons across runs, optional parallel experiments, and mode-specific workflows.
- [davebcn87/pi-autoresearch](https://github.com/davebcn87/pi-autoresearch) — `pi` extension plus dashboard for persistent experiment loops, live metrics, confidence tracking, and resumable autoresearch sessions.
- [drivelineresearch/autoresearch-claude-code](https://github.com/drivelineresearch/autoresearch-claude-code) — Claude Code plugin/skill port of `pi-autoresearch`, with a clean experiment-loop workflow and a concrete biomechanics case study.

## 🔬 Research-agent systems

- [aiming-lab/AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) — End-to-end research pipeline that turns a topic into literature review, experiments, analysis, peer review, and paper drafts; broader than autoresearch, but clearly in the same lineage.
- [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) — Markdown-first research workflows for Claude Code and other agents, centered on autonomous literature review, experiments, paper iteration, and cross-model critique.
- [Sibyl-Research-Team/AutoResearch-SibylSystem](https://github.com/Sibyl-Research-Team/AutoResearch-SibylSystem) — Fully autonomous AI scientist built on Claude Code, with explicit AutoResearch lineage, multi-agent research iteration, GPU experiment execution, and a self-evolving outer loop.

## 💻 Platform ports and hardware forks

- [miolini/autoresearch-macos](https://github.com/miolini/autoresearch-macos) — Widely adopted macOS fork that adapts upstream autoresearch for Apple Silicon / MPS while preserving the original loop shape.
- [trevin-creator/autoresearch-mlx](https://github.com/trevin-creator/autoresearch-mlx) — MLX-native Apple Silicon port that keeps the upstream fixed-budget `val_bpb` loop while removing the PyTorch/CUDA dependency entirely.
- [jsegov/autoresearch-win-rtx](https://github.com/jsegov/autoresearch-win-rtx) — Windows-native RTX fork focused on consumer NVIDIA GPUs, with explicit VRAM floors and a practical desktop setup path.

## 🎯 Domain-specific adaptations

- [RightNow-AI/autokernel](https://github.com/RightNow-AI/autokernel) — Applies the autoresearch loop to GPU kernel optimization: profile bottlenecks, edit one kernel, benchmark, keep or revert, repeat.

<div align="center">

## Star History

<a href="https://www.star-history.com/?type=date&repos=alvinunreal%2Fawesome-autoresearch">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/image?repos=alvinunreal/awesome-autoresearch&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/image?repos=alvinunreal/awesome-autoresearch&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/image?repos=alvinunreal/awesome-autoresearch&type=date&legend=top-left" />
 </picture>
</a>

## 📄 License

This list is released under [CC0-1.0](./LICENSE).
