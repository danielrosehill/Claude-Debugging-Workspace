# Generate Debugging Summary

Create a comprehensive summary of the debugging effort to date.

## Your Task

Generate a summary document suitable for:
- Handing off to another person/agent
- Archiving for future reference
- Understanding the full debugging journey

## Steps

1. **Gather all information** from:
   - `/context/` - Problem definition and background
   - `/debug-log/` - Chronological debugging history
   - `/outputs/analysis/` - Analysis documents
   - `/outputs/attempts/` - Remediation attempts
   - `/outputs/resolution/` - Resolution docs (if resolved)
   - `/inputs/` - What evidence was provided

2. **Synthesize the narrative** of the debugging process

## Output Format

Create a markdown document with:

### Executive Summary
2-3 sentences: What was the problem? Was it resolved? Key finding?

### Problem Statement
Clear description of the original problem

### Timeline
Chronological list of key events:
- [Date]: Problem first reported
- [Date]: Key discovery
- [Date]: Resolution (if applicable)

### Investigation Summary

#### Hypotheses Explored
| Hypothesis | Result | Key Finding |
|------------|--------|-------------|
| ... | Excluded/Confirmed | ... |

#### Key Discoveries
Bullet points of important findings during investigation

### Resolution
If resolved:
- **Root Cause**: What was actually wrong
- **Solution**: What fixed it
- **Prevention**: How to prevent recurrence

If unresolved:
- **Current State**: Where the investigation stands
- **Recommended Next Steps**: What to try next
- **Open Questions**: What remains unknown

### Lessons Learned
What was learned from this debugging effort that might help in the future?

### Appendix
- List of input files provided
- List of output documents generated

## Save Location

Save the summary to `/outputs/analysis/debugging-summary-YYYY-MM-DD.md`
