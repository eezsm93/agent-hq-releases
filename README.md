# Agent HQ for Windows

A 3D office to watch and orchestrate your Claude Code agents.

## Download

**[⬇ Download Agent HQ (Windows 10/11, 64-bit)](https://github.com/eezsm93/agent-hq-releases/releases/latest/download/AgentHQ-Setup.exe)**

This link always gets the latest version.

## Install

1. Run `AgentHQ-Setup.exe`.
2. If Windows shows "Windows protected your PC", click **More info → Run anyway**. The installer isn't code-signed yet; it's the same app published here.
3. It installs for your user only and doesn't need administrator rights.

## Before you start

Agent HQ runs its agents on **Claude Code**. Install it and sign in once:

```powershell
irm https://claude.ai/install.ps1 | iex
claude
```

## Updates

Agent HQ checks for updates when it opens and every 4 hours. A new version downloads in the background (you'll see the progress in the corner), and when it's ready Agent HQ asks to restart: it closes, installs and reopens by itself. You can also use **Agent HQ → Check for updates…** in the menu.

Your data (rooms, tasks, memory) lives in `%APPDATA%\Agent HQ` and is kept across updates and uninstalls.
