# Multi-Agent Systems Plugin

Parallel agent execution with Swarms and Get Shit Done (GSD). 28 commands, 2 skills. Dependency-aware planning, parallel waves, and atomic commits for complex multi-step projects.

## Installation

```bash
claude /plugin marketplace add Chipagosfinest/claude-multi-agent-systems
claude /plugin install multi-agent-systems
```

## Components

### Skills (2)

| Skill | Description |
|-------|-------------|
| `swarm-planner` | Creates dependency-aware implementation plans optimized for parallel multi-agent execution |
| `parallel-task` | Execute tasks in parallel waves with dependency tracking |

### Commands (28)

| Command | Description |
|---------|-------------|
| `/gsd:new-project` | Start a new GSD project with roadmap and milestones |
| `/gsd:new-milestone` | Add a new milestone to current project |
| `/gsd:plan-phase` | Create detailed plan for a phase |
| `/gsd:execute-phase` | Execute a planned phase |
| `/gsd:verify-work` | Verify completed work against requirements |
| `/gsd:progress` | Show project progress and status |
| `/gsd:help` | Get help with GSD commands |
| `/gsd:quick` | Quick task execution without full project setup |
| `/gsd:debug` | Debug issues with scientific method |
| `/gsd:map-codebase` | Analyze and map codebase architecture |
| `/gsd:add-phase` | Add a new phase to milestone |
| `/gsd:remove-phase` | Remove a phase from milestone |
| `/gsd:insert-phase` | Insert a phase at specific position |
| `/gsd:discuss-phase` | Discuss phase requirements |
| `/gsd:research-phase` | Research before planning a phase |
| `/gsd:audit-milestone` | Audit milestone completion |
| `/gsd:complete-milestone` | Mark milestone as complete |
| `/gsd:plan-milestone-gaps` | Identify gaps in milestone planning |
| `/gsd:list-phase-assumptions` | List assumptions for a phase |
| `/gsd:add-todo` | Add todo items |
| `/gsd:check-todos` | Check todo status |
| `/gsd:pause-work` | Pause current work |
| `/gsd:resume-work` | Resume paused work |
| `/gsd:settings` | Configure GSD settings |
| `/gsd:set-profile` | Set model profile |
| `/gsd:update` | Update GSD plugin |
| `/gsd:join-discord` | Join GSD Discord community |

## Usage

### Start a New Project

```bash
claude /gsd:new-project "Build a task management API"
```

### Plan and Execute

```bash
claude /gsd:plan-phase 1
claude /gsd:execute-phase 1
claude /gsd:verify-work
```

### Quick Tasks

```bash
claude /gsd:quick "Add input validation to signup form"
```

## Philosophy

**Get Shit Done (GSD)** is built on three principles:

1. **Dependency-Aware Planning** - Tasks explicitly declare dependencies, enabling maximum parallelization
2. **Atomic Commits** - Each task produces a single, reviewable commit
3. **Verification-First** - Goals are verified before marking work complete

## License

MIT
