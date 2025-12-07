# Claude-Workspace-Setup-Helper

[![Claude Code](https://img.shields.io/badge/Claude-Code-orange?logo=anthropic)](https://claude.ai/code)
[![Claude Code Projects Index](https://img.shields.io/badge/More%20Claude%20Code%20Projects-Index-blue)](https://github.com/danielrosehill/Claude-Code-Repos-Index)
[![GitHub Master Index](https://img.shields.io/badge/All%20Repos-Master%20Index-green)](https://github.com/danielrosehill/Github-Master-Index)

An interactive tool that helps you set up **Claude Workspaces** - pre-configured repository templates for various use cases with Claude Code.

## What is a Claude Workspace?

A **Claude Workspace** is a defined working environment for Claude Code. It's a template repository containing:

- **CLAUDE.md files** specific to that purpose
- **Pre-populated folders** for storing context data
- **Input/output directories** for prompt inputs and AI-generated outputs
- **Slash commands and agents** tailored to the workspace's purpose

## Getting Started

1. Clone this repository
2. Navigate to the directory
3. Run Claude Code: `claude`
4. Execute `/start` to begin the interactive setup

## Available Workspace Categories

| Category | Description |
|----------|-------------|
| **Environment Management** | Docker, Synology NAS, ADB, Home Assistant |
| **OS Managers** | Linux server administration |
| **Sync** | Cross-device synchronization (Ansible alternative) |
| **Content Creation** | Blogging, writing teams |
| **Health And Wellness** | Health tracking, therapy management |
| **Career** | Job search, tech/stack research |
| **Job Specific** | Media monitoring |
| **Research And Ideation** | Think tanks, specialized research projects |

## How It Works

The tool reads from `workspaces.json` which contains a catalog of available workspaces. When you run `/start`, it will:

1. Ask for your preferred base directory for workspaces
2. Understand your objectives and use cases
3. Recommend relevant workspaces from the catalog
4. Clone selected workspaces to your machine

## Master Index

For the most up-to-date list of Claude Code workspaces and projects, refer to the [Claude-Code-Repos-Index](https://github.com/danielrosehill/Claude-Code-Repos-Index).

---

To view an index of my Claude Code related projects, [click here](https://github.com/danielrosehill/Claude-Code-Repos-Index).
