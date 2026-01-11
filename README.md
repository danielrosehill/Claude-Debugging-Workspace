# Claude Debugging Workspace

A template repository for systematic debugging with Claude Code - for technical bugs *and beyond*.

## What is This?

This is a structured workspace for tackling **persistent problems** using the debugging methodology. While debugging is traditionally a technical concept, the systematic approach - forming hypotheses, testing them, excluding causes, and documenting progress - applies to any stubborn problem.

### What Can You Debug?

- **Technical Issues**: Software bugs, system failures, configuration problems, integration errors
- **Process Problems**: Workflow inefficiencies, recurring bottlenecks, automation failures
- **Life Challenges**: Persistent problems that resist simple solutions and benefit from systematic investigation
- **Creative Blocks**: Stuck projects, recurring obstacles, pattern-based challenges

The key is that it's a **persistent problem** that benefits from methodical investigation rather than a quick fix.

## Getting Started

1. Clone or use this template repository
2. Run `/onboarding` to describe your problem
3. Add relevant evidence to `/inputs/`
4. Use the debugging commands to work through the problem systematically

## Repository Structure

```
├── inputs/                  # User-provided evidence
│   ├── logs/               # System logs, error logs
│   ├── screenshots/        # Visual evidence
│   ├── recordings/         # Screen/audio recordings
│   └── data/               # Text data, configs, documents
├── outputs/                 # Agent-generated content
│   ├── analysis/           # Analysis documents
│   ├── attempts/           # Remediation attempt docs
│   └── resolution/         # Final resolution documentation
├── context/                 # Problem summary and background
├── debug-log/              # Chronological debugging history
└── .claude/
    ├── commands/           # Slash commands
    └── agents/             # Specialized agents
```

## Available Commands

| Command | Description |
|---------|-------------|
| `/onboarding` | Start a new debugging session |
| `/status` | Get current debugging status |
| `/hypotheses` | Review all hypotheses and their status |
| `/summarize` | Generate a comprehensive summary |

## Agents

- **Analyst**: Examines evidence and identifies patterns
- **Investigator**: Designs and executes tests on hypotheses

## The Debugging Protocol

1. **Document the problem** clearly in `/context/`
2. **Generate hypotheses** about potential causes
3. **Test hypotheses** systematically, one at a time
4. **Exclude causes** that don't hold up
5. **Log everything** chronologically in `/debug-log/`
6. **Document resolution** when the problem is solved

## Why This Approach?

Persistent problems persist because they resist simple solutions. The debugging methodology forces:
- **Clarity**: You must articulate what's actually wrong
- **Systematic thinking**: No jumping to conclusions
- **Documentation**: Progress is tracked, nothing is forgotten
- **Objectivity**: Hypotheses are tested, not assumed

## License

MIT - Use and adapt freely.
