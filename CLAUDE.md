# Claude Debugging Workspace

This repository is intended to function as a workspace to assist the user with a specific debugging problem.

## What is a "Bug"?

While debugging is traditionally understood in a technical context (software errors, system failures, configuration issues), **the debugging methodology applies to any persistent problem**.

A "bug" in this workspace can be:
- **Technical**: Software errors, system failures, configuration issues, integration problems
- **Process**: Workflow inefficiencies, recurring bottlenecks, automation failures
- **Life/Personal**: Persistent problems that resist simple solutions and require systematic investigation
- **Creative**: Stuck projects, recurring blockers, pattern-based challenges

The key characteristic is that it's a **persistent problem that benefits from systematic investigation** - forming hypotheses, testing them, excluding causes, and documenting progress.

## Getting Started

The user will provide details of the problem they are experiencing by running the `/onboarding` command.

## Workflow Structure

This repository uses a folder structure to organize the debugging workflow, divided between user inputs and agent outputs.

### User Inputs (`/inputs/`)

- **logs/**: System logs, error logs, application logs
- **screenshots/**: Visual evidence of the problem
- **recordings/**: Screen recordings or audio context
- **data/**: Text data, configuration files, relevant documents

### Agent Outputs (`/outputs/`)

- **analysis/**: Analysis documents and findings
- **attempts/**: Documentation of remediation attempts
- **resolution/**: Final documentation when the issue is resolved

### Shared Context (`/context/`)

- Summary of the debugging challenge
- Background information
- Constraints and requirements

### Debug Log (`/debug-log/`)

Chronological documentation of debugging efforts, including:
- Hypothesized causes
- Tests performed
- Causes excluded
- Progress updates

## Debugging Protocol

This may be a significant debugging challenge that cannot be solved in a single run or turn. Therefore:

1. **Maintain a chronological log** of debugging efforts in `/debug-log/`
2. **Document suspected causes** as hypotheses to be tested
3. **Mark excluded causes** as debugging progresses
4. **Always include dates** to show the chronological sequence
5. **Create a summary** of the challenge in `/context/` for future reference

## Available Commands

- `/onboarding` - Start a new debugging session by describing the problem
- `/status` - Get current status of the debugging effort
- `/hypotheses` - Review current hypotheses and their status
- `/summarize` - Generate a summary of progress to date
