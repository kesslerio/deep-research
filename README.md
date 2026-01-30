# Deep Research Skill 🔬

A OpenClaw skill for conducting exhaustive, methodical research through structured investigation cycles with academic rigor.

## Overview

This skill enables systematic deep research with:
- Multi-phase investigation with user checkpoints
- Minimum two full research cycles per theme
- Academic-style APA citations (1-2 per paragraph)
- Narrative prose output (no bullet points)
- Explicit analysis between each tool use
- Contradiction documentation and resolution

## Installation

1. Copy this skill to your OpenClaw skills directory:
   ```bash
   cp -r deep-research /path/to/openclaw/skills/
   ```

2. The skill auto-registers on next OpenClaw restart.

## Usage

Trigger the skill by saying:
- `/research`
- "I need deep research on..."
- "Conduct an exhaustive analysis of..."

## Research Protocol

### Phase 1: Initial Engagement
Ask clarifying questions, confirm scope, **wait for user**.

### Phase 2: Research Planning  
Present themes and execution plan, **wait for approval**.

### Phase 3: Research Cycles (Auto-Execute)
For each theme, minimum two cycles:
1. **START:** `web_search` for landscape
2. **ANALYZE:** Sequential thinking to process
3. **DIVE:** `web_fetch` for depth
4. **PROCESS:** Sequential thinking to synthesize
5. **REPEAT:** Until theme exhausted

**Required:** Analysis between every tool call showing:
- Connection to previous findings
- Evolution of understanding
- Pattern changes
- Contradictions addressed

### Phase 4: Final Report
Present academic narrative with:
- Executive Summary
- Knowledge Development (evolution of understanding)
- Comprehensive Analysis (findings, patterns, contradictions)
- Practical Implications
- References (APA format)

Each section: 6-8+ substantial paragraphs, flowing prose, integrated citations.

## Research Standards

- Every conclusion cites **multiple sources**
- All **contradictions addressed**
- **Uncertainties acknowledged**
- **Limitations discussed**
- **Gaps identified**

## Writing Requirements

- Flowing narrative style (no lists/bullets)
- Academic but accessible
- Evidence integrated naturally
- Progressive logical development
- 1-2 APA citations per paragraph

## File Structure

```
deep-research/
├── SKILL.md       # Main skill definition
├── quickref.md    # One-page quick reference
└── example.md     # Complete workflow example
```

## Example Workflow

See [example.md](example.md) for a complete walkthrough researching "AI coding assistants for healthcare teams."

## License

Apache License 2.0 - See [LICENSE](LICENSE)

## Contributing

This is a OpenClaw skill. To contribute:
1. Fork the repository
2. Make changes
3. Submit a pull request

## Credits

Adapted from deep research protocols for OpenClaw's tool ecosystem.
