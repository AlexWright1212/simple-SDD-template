# {{cookiecutter.project_name}}

{{cookiecutter.project_description}}

## Overview

## Quick Start

## How it Works

## File Structure

```
{{cookiecutter.project_name}}/
├── .cursor/
│   ├── commands/
│   │   ├── overlord_example.md   # Reference overlord from template
│   │   └── overlord_guide.md     # Guide for writing your own overlord
│   └── rules/
│       ├── agent.mdc             # Agent guidelines (always applied)
│       ├── constraints.mdc       # Environment constraints (always applied)
│       └── versioning.mdc        # Git workflow rules (always applied)
├── docs/                         # Project documentation
├── spec/
│   ├── spec_example.md           # Reference spec from template
│   └── spec_guide.md             # Guide for writing your own spec
├── src/                          # Source code
├── scripts/
│   └── update_docs.py            # Appends session logs to project.md
├── .env.example                  # Environment variable template
├── .gitignore
├── CLAUDE.md                     # Instructions for Claude Code
├── project.md                    # Session logs and status updates
├── pyproject.toml                # Poetry project config
└── README.md
```
