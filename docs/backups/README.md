# Board backups

The Nexus Board disappears after 7 days without activity. This folder keeps a copy of the cards, one per release and before any long pause.

Each backup is a folder named by date:

```
docs/backups/YYYY-MM-DD/
  cards.json   # output of the nexus-board skill's `state` command
  cards.md     # readable summary: number, title, tag, description and decisions
```

To restore an expired board, follow "Board backup" in [AGENTS.md](../../AGENTS.md).
