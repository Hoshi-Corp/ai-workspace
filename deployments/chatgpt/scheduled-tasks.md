# ChatGPT scheduled tasks

Catalog of recurring scheduled tasks running in ChatGPT. Claude can't read these directly — fill this in from ChatGPT's Tasks settings (chatgpt.com → Tasks, or ask ChatGPT to list them) and keep it updated here.

## Active

<!-- One entry per task, e.g.:

### <task name>
- **Schedule:** <cadence>
- **Purpose:** <what it does and why>
- **Notes:** <anything relevant>
-->

### Ottawa Event Curator
- **Schedule:** Daily at approximately 9:00 AM, timezone `America/Toronto`; flexible schedule with `BYHOUR=9` (no fixed minute specified).
- **Purpose:** Curate Ottawa concerts, festivals, and notable events, plus Japanese-artist events in the Toronto and Montreal regions, emphasizing presales and meaningful new announcements or changes.
- **Definition:** [Ottawa Event Curator workflow](../../workflows/ottawa-event-curator/README.md) · [Full task prompt](../../workflows/ottawa-event-curator/prompt.md)
- **Notes:** Schedule and prompt recorded from the user's current task definition. Local time follows Toronto daylight-saving changes.

### Restaurant Curator
- **Schedule:** Weekly, every Thursday. Time of day and timezone were not specified in the source conversation.
- **Purpose:** Curate a selective set of culturally distinctive restaurants and food experiences, primarily in Ottawa and secondarily along the Toronto–Montreal corridor.
- **Definition:** [Workflow overview](../../workflows/restaurant-curator/README.md) · [Full task prompt](../../workflows/restaurant-curator/prompt.md)
- **Notes:** Preserved from the user's existing scheduled task in [Curate Ottawa Restaurants](https://chatgpt.com/c/6a9c8ed5-9c00-83e9-bf15-93aab586dd79). Recorded from the conversation on 2026-09-28; live task settings have not been independently verified. Regional depth and experiences such as Filipino Kamayan set the bar; exclude Ottawa Chinatown Night Market as a food discovery.

## Notes
- Restaurant Curator definition recorded on 2026-09-28 from the source conversation. Full Tasks-settings sync remains pending.
- Ottawa Event Curator synced on 2026-09-28 from the user’s current task definition.
