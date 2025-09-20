# Notes

This directory contains project notes, meeting minutes, research findings, and other documentation.

## Organization Structure

```
notes/
├── meetings/           # Meeting minutes and notes
├── research/          # Research findings and investigations
├── decisions/         # Architectural Decision Records (ADRs)
├── brainstorming/     # Ideas and brainstorming sessions
└── retrospectives/    # Sprint/project retrospectives
```

## Note Categories

### Meeting Notes (`meetings/`)
Format: `YYYY-MM-DD-meeting-topic.md`

**Template**:
```markdown
# Meeting: [Topic]

**Date**: YYYY-MM-DD
**Attendees**: [Names]
**Facilitator**: [Name]

## Agenda
1. Item 1
2. Item 2

## Discussion Points
- Point 1
- Point 2

## Decisions Made
- Decision 1
- Decision 2

## Action Items
- [ ] @person - Task description - Due date
- [ ] @person - Task description - Due date

## Next Steps
- Next step 1
- Next step 2
```

### Research Notes (`research/`)
Format: `YYYY-MM-DD-research-topic.md`

**Template**:
```markdown
# Research: [Topic]

**Date**: YYYY-MM-DD
**Researcher(s)**: [Names]

## Objective
What we're trying to learn or solve

## Background
Context and why this research is needed

## Findings
### Finding 1
Description and evidence

### Finding 2
Description and evidence

## Recommendations
Based on findings, we recommend...

## Resources
- [Link to resource 1]
- [Link to resource 2]

## Further Investigation Needed
- Question 1
- Question 2
```

### Architecture Decision Records (`decisions/`)
Format: `ADR-NNNN-short-description.md`

**Template**:
```markdown
# ADR-NNNN: [Title]

**Date**: YYYY-MM-DD
**Status**: Proposed | Accepted | Deprecated | Superseded
**Deciders**: [Names]

## Context
The issue motivating this decision

## Decision
The change we're proposing/have agreed to

## Consequences
### Positive
- Consequence 1
- Consequence 2

### Negative
- Consequence 1
- Consequence 2

### Neutral
- Consequence 1
- Consequence 2

## Alternatives Considered
1. Alternative 1 - Why not chosen
2. Alternative 2 - Why not chosen

## Related
- ADR-XXXX - Related decision
- Issue #XXX - Related issue
```

### Brainstorming Notes (`brainstorming/`)
Format: `YYYY-MM-DD-topic.md`

**Template**:
```markdown
# Brainstorming: [Topic]

**Date**: YYYY-MM-DD
**Participants**: [Names]

## Goal
What we're brainstorming about

## Ideas
### Idea 1: [Name]
Description

**Pros**:
- Pro 1
- Pro 2

**Cons**:
- Con 1
- Con 2

### Idea 2: [Name]
Description

**Pros**:
- Pro 1
- Pro 2

**Cons**:
- Con 1
- Con 2

## Next Steps
- [ ] Action item 1
- [ ] Action item 2

## Parking Lot
Ideas for future consideration:
- Idea 1
- Idea 2
```

### Retrospective Notes (`retrospectives/`)
Format: `YYYY-MM-DD-sprint-X-retro.md`

**Template**:
```markdown
# Retrospective: [Sprint/Period]

**Date**: YYYY-MM-DD
**Participants**: [Names]
**Facilitator**: [Name]

## What Went Well
- Success 1
- Success 2

## What Could Be Improved
- Challenge 1
- Challenge 2

## What We'll Try Next
- Experiment 1
- Experiment 2

## Action Items
- [ ] @person - Action - Due date
- [ ] @person - Action - Due date

## Metrics
- Velocity: X
- Issues Closed: Y
- Customer Satisfaction: Z

## Follow-up from Last Retro
- Action 1: [Status]
- Action 2: [Status]
```

## Best Practices

1. **Date Everything**: Always include dates in filenames and document headers
2. **Be Descriptive**: Use clear, descriptive filenames
3. **Link Related Content**: Cross-reference related notes, issues, and PRs
4. **Keep It Organized**: Place notes in the appropriate subdirectory
5. **Regular Cleanup**: Archive old notes that are no longer relevant
6. **Searchable Content**: Use consistent formatting and keywords

## Quick Links

- [Proposals](/proposals) - Formal feature proposals
- [Issues](../../issues) - GitHub issues
- [Pull Requests](../../pulls) - GitHub PRs

## Index

<!-- This section can be used to maintain an index of important notes -->

### Recent Notes
<!-- Last 5-10 notes added -->

### Important Decisions
<!-- Links to key ADRs -->

### Ongoing Research
<!-- Active research topics -->