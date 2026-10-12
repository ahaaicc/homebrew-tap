# homebrew-tap

[AMTM](https://github.com/ahaaicc/amtm)（Agents Multi-Task Management）的 Homebrew Tap — 终端看板，管理多个 AI agent（Claude Code、Codex CLI、Droid）上的并行任务。

## 安装

```bash
brew install ahaaicc/tap/amtm
```

## 升级

```bash
brew update && brew upgrade amtm
```

旧名字 `mtm` 已改为 `amtm`：`formula_renames.json` 会让已安装 `ahaaicc/tap/mtm` 的机器在 `brew update` 后自动迁移到 `amtm`。

Formula 由 GoReleaser 在 [amtm 仓库](https://github.com/ahaaicc/amtm)打 tag 时自动更新，请勿手动编辑 `Formula/`。
