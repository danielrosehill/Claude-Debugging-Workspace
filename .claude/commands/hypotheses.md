# Hypotheses Review

Review and manage the current debugging hypotheses.

## Your Task

Provide a detailed view of all hypotheses - current, excluded, and confirmed.

## Steps

1. **Scan the debug log** in `/debug-log/` for all mentioned hypotheses

2. **Categorize each hypothesis**:
   - **Active**: Still being investigated
   - **Excluded**: Tested and ruled out (with reason)
   - **Confirmed**: Identified as the cause
   - **Pending**: Not yet tested

3. **Assess evidence** for each hypothesis

## Output Format

### Active Hypotheses

For each active hypothesis:
- **Hypothesis**: [Description]
- **Likelihood**: High/Medium/Low
- **Evidence For**: [What supports this]
- **Evidence Against**: [What contradicts this]
- **Next Test**: [How to confirm or exclude]

### Excluded Hypotheses

For each excluded hypothesis:
- **Hypothesis**: [Description]
- **Excluded On**: [Date]
- **Reason**: [Why it was ruled out]
- **Test Performed**: [What proved it wrong]

### Confirmed Cause(s)

If any hypothesis has been confirmed:
- **Confirmed Cause**: [Description]
- **Confirmed On**: [Date]
- **Evidence**: [What confirmed it]
- **Remediation Status**: [In progress/Complete]

### Suggested New Hypotheses

Based on the evidence so far, suggest any new hypotheses worth considering.

## After Review

Ask the user if they want to:
1. Add new hypotheses
2. Update the status of existing ones
3. Prioritize which to investigate next
