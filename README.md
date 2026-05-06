# Claude Code Plugins Marketplace

A Claude Code marketplace for XrmToolBox, Dynamics 365 / Dataverse development, data migration analysis, skill authoring, and productivity extensions.

## Available Plugins

| Plugin | Skills | Description |
|--------|--------|-------------|
| **xrmtoolbox** | `plugin-dev`, `testing`, `ui-review` | Build, deploy, pack, publish, scaffold tests, mock IOrganizationService, smoke tests, UI testing, and UI best practices review for XrmToolBox plugins. |
| **skill-authoring** | `skill-authoring`, `skill-review`, `activation-setup` | Create, write, and publish Claude Code skills to this marketplace. Scaffolding, best practices, CI/CD, marketplace registration, 9-dimension skill quality assessment, and activation infrastructure setup. |
| **skill-engine** | `setup`, `rules` | Hook-driven skill activation and guardrail enforcement. Reads skill-rules.json to suggest relevant skills on prompt and enforce guardrails on file edits. |
| **knbn** | `knbn`, `knbn-join`, `knbn-status` | Track work across multiple Claude Code CLI instances via a VS Enterprise kanban board. Register work items, smart-join existing cards, and post status updates. |
| **sherlock** | `migration-analyst`, `lineage-tracer`, `mapping-guide`, `pipeline-review` | ETL/data migration analysis — mapping document generation, data lineage tracing with column-level precision, and multi-agent pipeline review orchestration. Works with any ETL stack. |
| **cicd-safety** | `cicd-fortify`, `guard`, `safety-hooks` | CI/CD safety assessment, pre-commit guard reviews, and production safety hooks for Claude Code. |
| **refresh** | `refresh` | One-shot refresh of Claude Code marketplaces, plugin updates, and session reload. |
| **gantt** | `plan`, `schedule`, `sync`, `excel` | Project management — conversational planning with iterative discovery, deterministic date sequencing (weekend and US federal holiday aware), dependency tracking, critical path analysis, MS Project sync via mpp-mcp, and Excel export/import with Gantt chart visualization via excel-mcp. |

## Installation

### 1. Add this marketplace

```bash
claude plugin marketplace add HurleySk/claude-plugins-marketplace
```

### 2. Install a plugin

```bash
claude plugin install xrmtoolbox
```

## Related

- [XrmToolBox Plugin Template](https://github.com/HurleySk/XrmToolBox-Plugin-Template) - GitHub template for scaffolding new plugins
- [XrmToolBox Testing Toolkit](https://github.com/HurleySk/xrmtoolbox-testing-toolkit) - Standalone test harness for plugin UI testing
- [claude-xrmtoolbox-skill](https://github.com/HurleySk/claude-xrmtoolbox-skill) - The plugin source repo
