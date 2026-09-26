# wondelai-skills — Agent Skills & Metaskills Library

One job: Provide 68 business, marketing, UX, systems architecture, and coding framework skills and metaskills.

## Contract
- **Role**: Multi-Agent Skills Collection & Marketplace (`agentskills.io` compatible)
- **Inputs**: 54 individual skill folders, 14 metaskill folders, `CLAUDE.md`, `.claude-plugin/marketplace.json`.
- **Process**: Package skills for Claude Code, Codex, Cursor, Hermes, and Antigravity, validate frontmatter and stage handoffs.
- **Outputs**: Discoverable and installable agent skills across 10 plugin collections and an all-in-one bundle.
- **Human check**: Test individual skill invocation (e.g. `/plugin install ux-design@wondelai-skills`) and confirm interactive guidance stages.

## Directory Structure
```
wondelai-skills/
├── .claude-plugin/
│   └── marketplace.json
├── [54 domain skill folders]/
├── [14 metaskill folders]/
├── CLAUDE.md
├── EXAMPLES.md
├── README.md
└── CONTEXT.md
```
