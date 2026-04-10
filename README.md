# research-frame

> 🇰🇷 [한국어 README](./README.ko.md)

**Systematic research framework with LIGHT and DEEP modes — breadth scan or full investigation pipeline.**

## Prerequisites

- **Claude Cowork or Claude Code** environment
- **Web search access** — recommended for DEEP mode research

## Goal

Research without structure wastes time on irrelevant details or misses critical insights. Research-Frame provides a three-axis methodology (WHY, HOW, SCOPE) that scales from quick breadth scans (LIGHT mode) to rigorous multi-phase investigations (DEEP mode), ensuring your findings are complete, bias-aware, and actionable.

## When & How to Use

Invoke LIGHT mode when you need a breadth scan with quick turnaround — it maintains wide scope while minimizing depth. Invoke DEEP mode when stakes are high or decisions are strategic — it runs a full pipeline with bias prevention gates and cross-axis validation. WHY frames the purpose and hypotheses; HOW structures the investigation axis-by-axis with bias checks; SCOPE sets boundaries and termination criteria. Choose your mode based on decision stakes.

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| Quick market sizing | `"LIGHT research: TAM of AI consulting in Southeast Asia"` | WHY (scope)→HOW (3 axes)→SCOPE (boundaries); breadth maintained, findings in 20 min |
| Deep policy analysis | `"DEEP research: regulatory impact of carbon tax on automotive"` | Full pipeline with bias gates, cross-axis validation, contradictions reconciled, 40+ sources |
| Competitive intelligence | `"research-frame LIGHT on competitor's go-to-market"` | WHY (intent)→HOW (positioning/pricing/channels)→SCOPE (100 companies); landscape mapped |
| Strategic hiring decision | `"DEEP on candidate's track record in scaling sales"` | Reputation axis→competency axis→cultural fit axis; counter-examples included; risk flags surfaced |
| Technology adoption study | `"LIGHT research on enterprise adoption barriers for blockchain"` | Purpose→key barriers hypothesis→3-axis scan; decision-ready in one session |

## Key Features

- Two-mode operation: LIGHT (breadth, minimal depth, fast) and DEEP (full pipeline with gates and cross-validation)
- Three-axis structure: WHY (purpose, hypotheses, framing), HOW (investigation methodology, bias prevention, cross-analysis), SCOPE (boundaries, resources, termination criteria)
- Built-in bias detection and prevention at each stage
- Cross-axis validation ensures contradictions are surfaced and reconciled
- Scales across domains: market research, policy analysis, competitive intelligence, hiring, technology assessment

## Works With

- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — planning-skill calls research-frame in P2 (Research phase)
- **[policy-planning](https://github.com/jasonnamii/policy-planning)** — policy-planning uses research-frame as its foundation phase
- **[person-profiler](https://github.com/jasonnamii/person-profiler)** — person-profiler can invoke DEEP mode for comprehensive candidate analysis
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — biz-skill pairs research-frame findings with strategic pattern matching

## Installation

```bash
git clone https://github.com/jasonnamii/research-frame.git ~/.claude/skills/research-frame
```

## Update

```bash
cd ~/.claude/skills/research-frame && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
