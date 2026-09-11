# agent-with-tools

Learning project: agent loop with 3 tiny tools

Started as a weekend hack, grew on me.

## Getting started

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Examples

```bash
python agent.py "how many words in my note called todo?"
```

## What it does

- Works with any OpenAI-compatible model
- Tool schemas declared next to the functions
- Three tools: calculator, word count, note lookup
- Plain loop: plan -> call -> observe -> answer

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── agent.py
└── requirements.txt
```

## Notes

- mostly stable, edge cases remain
