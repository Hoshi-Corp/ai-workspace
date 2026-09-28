# ChatGPT scheduled tasks

Catalog of recurring scheduled tasks running in ChatGPT. Claude can't read these directly — fill this in from ChatGPT's Tasks settings (chatgpt.com → Tasks, or ask ChatGPT to list them) and keep it updated here.

## Active

<!-- One entry per task, e.g.:

### <task name>
- **Schedule:** <cadence>
- **Purpose:** <what it does and why>
- **Notes:** <anything relevant>
-->

### Carney Daily Brief
- **Schedule:** Daily, flexible schedule, approximately 8:00 AM America/Toronto, starting 2026-09-17.
- **Purpose:** Concise, sourced daily summary of concrete actions by Mark Carney and his government, distinguishing announcements, implementation, and measurable outcomes.
- **Notes:** Definition preserved from the existing ChatGPT scheduled task; this catalog entry does not change the running automation. The timezone and flexible timing above accompany the original VEVENT below.

**VEVENT:**
```ical
BEGIN:VEVENT
DTSTART:20260917T080000
RRULE:FREQ=DAILY;BYHOUR=8
END:VEVENT
```

**Prompt:**
```text
Check the latest actions by Canadian Prime Minister Mark Carney and his government. Send me a concise daily summary focused on concrete actions rather than rhetoric. Cover international relations and trade diversification; investment in Canada's domestic economy; interprovincial trade; major infrastructure and industrial projects; defence-related industrial investment; measures affecting major economic sectors; immigration policy and implementation, including permanent and temporary immigration, international students, foreign workers, asylum/refugee policy, processing and integration when relevant; and health policy, including federal health funding, healthcare workforce, pharmacare, dental care, public health, provincial/federal initiatives, and measures that could materially affect access, capacity, wait times, or costs. Highlight credible evidence of economic, immigration, and healthcare outcomes when available. Clearly distinguish newly announced policies from measures actually implemented and from measurable outcomes. Include important developments since the previous brief, cite reliable current sources, and mention when there is no meaningful new development rather than padding the summary.
```

### Restaurant Curator
- **Schedule:** Weekly, every Thursday. Time of day and timezone were not specified in the source conversation.
- **Purpose:** Curate a selective set of culturally distinctive restaurants and food experiences, primarily in Ottawa and secondarily along the Toronto–Montreal corridor.
- **Definition:** [Workflow overview](../../workflows/restaurant-curator/README.md) · [Full task prompt](../../workflows/restaurant-curator/prompt.md)
- **Notes:** Preserved from the user's existing scheduled task in [Curate Ottawa Restaurants](https://chatgpt.com/c/6a9c8ed5-9c00-83e9-bf15-93aab586dd79). Recorded from the conversation on 2026-09-28; live task settings have not been independently verified. Regional depth and experiences such as Filipino Kamayan set the bar; exclude Ottawa Chinatown Night Market as a food discovery.

## Notes
- Restaurant Curator definition recorded on 2026-09-28 from the source conversation. Full Tasks-settings sync remains pending.
- Carney Daily Brief synced on 2026-09-28 from the supplied task definition.
