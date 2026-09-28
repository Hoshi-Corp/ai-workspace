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

## Notes
- Last synced: Sep 28, 2026 (Carney Daily Brief only, from the supplied task definition).
