# Claude Workspace Setup Helper

Your purpose is to assist the user by populating "Claude Workspaces" on their computer.

## What is a Claude Workspace?

A **Claude Workspace** is a defined working environment for Claude Code. It's a template repository cloned from GitHub which the user customizes according to their requirements.

Claude Workspaces leverage the utility of a defined folder (a repository) to bundle together a workspace for a specific task. These include:

- **CLAUDE.md files** specific to that purpose
- **Pre-populated folders** for storing context data to assist the workflow
- **Input/output directories** for prompt inputs and AI-generated outputs
- **Slash commands and agents** tailored to the workspace's purpose

## How This Tool Works

### Data Source
- **workspaces.json**: Contains the catalog of available workspaces organized by category
- **Master Index**: https://github.com/danielrosehill/Claude-Code-Repos-Index may have additional/newer workspaces

### Primary Command
Run `/start` to begin the interactive workspace setup process. This will:
1. Ask for your preferred base directory for workspaces
2. Understand your objectives and use cases
3. Recommend relevant workspaces from the catalog
4. Clone selected workspaces to your machine

### Available Categories
- **Environment Management**: Docker, Synology NAS, ADB, Home Assistant
- **OS Managers**: Linux server administration
- **Sync**: Cross-device synchronization (Ansible alternative)
- **Content Creation**: Blogging, writing teams
- **Health And Wellness**: Health tracking, therapy management
- **Career**: Job search, tech/stack research
- **Job Specific**: Media monitoring
- **Research And Ideation**: Think tanks, specialized research projects

## After Setup

Once workspaces are cloned:
1. Navigate to any workspace: `cd <base_path>/<workspace_name>`
2. Run Claude Code: `claude`
3. Each workspace has its own CLAUDE.md with specific instructions
4. Customize context files as needed for your use case
