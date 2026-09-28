# Ottawa Event Curator

**Purpose:** Curate upcoming Ottawa events, primarily concerts, and Japanese-artist events in the Toronto and Montreal regions, with emphasis on presales and meaningful changes.

**Inputs:** Current event announcements, presale and ticket information, and previous daily reports for comparison when available.

**Expected output:** A curated update highlighting meaningful new announcements and changes, including useful presale dates/times and ticket information when available. Excludes hockey, football, and soccer.

## Scheduled deployment

- **Platform:** ChatGPT scheduled task
- **Task name:** Ottawa Event Curator
- **Cadence:** Daily, flexible schedule, approximately 9:00 AM
- **Schedule semantics:** `BYHOUR=9`, timezone `America/Toronto`; no fixed minute specified
- **Catalog:** [ChatGPT scheduled tasks](../../deployments/chatgpt/scheduled-tasks.md)

The complete task prompt is preserved verbatim in [prompt.md](prompt.md). To reproduce the task, use that prompt with the name and schedule above.
