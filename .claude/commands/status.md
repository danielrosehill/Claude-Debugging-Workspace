# Debugging Status Report

Generate a status report of the current debugging effort.

## Your Task

Review the workspace and provide a comprehensive status update.

## Steps

1. **Read the problem summary** from `/context/problem-summary.md` (if it exists)

2. **Review the debug log** in `/debug-log/` to understand:
   - What hypotheses have been tested
   - What causes have been excluded
   - What attempts have been made
   - Current state of investigation

3. **Check outputs** in `/outputs/`:
   - Any analysis documents
   - Remediation attempts and their outcomes
   - Resolution documentation (if resolved)

4. **Check for new inputs** in `/inputs/` that haven't been analyzed yet

## Output Format

Provide a status report including:

### Problem Summary
Brief reminder of what we're debugging

### Current Status
- Active hypothesis being investigated
- Progress percentage estimate (rough)
- Blockers or waiting items

### Hypotheses Status
| Hypothesis | Status | Notes |
|------------|--------|-------|
| ... | Excluded/Active/Confirmed | ... |

### Recent Progress
- What was done in the last session(s)
- Key findings

### Next Steps
- Recommended actions to continue debugging

### New Inputs to Process
- Any files in `/inputs/` that need analysis
