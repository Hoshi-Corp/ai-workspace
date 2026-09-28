# workflows

Reusable multi-step prompt workflows — something you run repeatedly with the same shape (e.g. a weekly review).

Each workflow gets its own folder:

```
workflows/<slug>/
├── README.md      # purpose, inputs, expected output
├── prompt.md      # the reusable instructions
└── examples/      # sample inputs and good outputs
```

See `templates/workflow-template/` for a starting point.

## Current workflows

- [Ottawa Event Curator](ottawa-event-curator/README.md) — daily event curation for Ottawa and Japanese-artist events in the Toronto and Montreal regions.
