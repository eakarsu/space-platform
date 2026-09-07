# Feature status — Space operations & simulation

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 147 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 1 | 0 | Native records/view |
| Activity & audit trail | audit | 3 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Bookmarks | records | 1 | 0 | Native records/view |
| Map | records | 1 | 0 | Native records/view |
| Compare | records | 1 | 0 | Native records/view |
| Change detection | records | 1 | 0 | Native records/view |
| Timeline | records | 1 | 0 | Native records/view |
| Vegetation index | records | 1 | 0 | Native records/view |
| Area calculation | records | 1 | 0 | Native records/view |
| Object detection | records | 1 | 0 | Native records/view |
| Temporal analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| automated change detection | records | 1 | 0 | Native records/view |
| ai asset inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| crop health monitoring | records | 1 | 0 | Native records/view |
| urban planning intelligence | records | 1 | 0 | Native records/view |
| disaster damage assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| environmental monitoring | records | 1 | 0 | Native records/view |
| changedetection beforeafter | records | 1 | 0 | Native records/view |
| objectdetection buildings roads vehicles | records | 1 | 0 | Native records/view |
| vegetationindex ndvi crop health | records | 1 | 0 | Native records/view |
| cloudremoval | records | 1 | 0 | Native records/view |
| temporalanalysis multidate trends | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| areacalculation measure features | records | 1 | 0 | Native records/view |
| segmentationclassification models | records | 1 | 0 | Native records/view |
| map integration leafletmapbox backend lay | integration | 1 | 0 | Provider request records only |
| geospatial export geotiff shapefiles | records | 1 | 0 | Native records/view |
| layer managementoverlay system | records | 1 | 0 | Native records/view |
| roi drawingmeasurement persistence | records | 1 | 0 | Native records/view |
| imagery provider api planet maxar sentine | records | 1 | 0 | Native records/view |
| webhook delivery for completed batch jobs | integration | 1 | 0 | Provider request records only |
| Space Objects | records | 2 | 0 | Native records/view |
| Satellites | records | 2 | 0 | Native records/view |
| Conjunction Events | records | 1 | 0 | Native records/view |
| Launch Windows | records | 2 | 0 | Native records/view |
| Debris Removal | records | 2 | 0 | Native records/view |
| Collision Probability | records | 2 | 0 | Native records/view |
| Orbital Decay | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Maneuver Planning | records | 2 | 0 | Native records/view |
| Debris Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Launch Optimization | records | 2 | 0 | Native records/view |
| Orbital Map (SGP4) | records | 1 | 0 | Native records/view |
| Conjunction Alerts | records | 1 | 0 | Native records/view |
| Debris Characterize | records | 1 | 0 | Native records/view |
| Collision Clustering | records | 1 | 0 | Native records/view |
| Rendezvous Optimization | records | 1 | 0 | Native records/view |
| Regulatory Compliance | records | 1 | 0 | Native records/view |
| TLE Sync | records | 1 | 0 | Native records/view |
| predictive collision clustering by likely fragmentation parent with | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| sensor fusion combining optical radar observations via ml | records | 1 | 0 | Native records/view |
| multi mission optimizer recommending constellation reconfigurations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| active debris removal logistics with payload capacity cost | records | 1 | 0 | Native records/view |
| regulatory compliance scoring against national international guidelines | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time conjunction alerting via webhooks and pager style escalation | integration | 1 | 0 | Provider request records only |
| ai driven debris characterization from limited observations frontend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi target rendezvous optimization endpoint | records | 1 | 0 | Native records/view |
| sensor fusion ml for observation confidence | records | 1 | 0 | Native records/view |
| webhooks or push notifications for real time conjunction | integration | 1 | 0 | Provider request records only |
| integration with norad tle feeds or jspoc | integration | 1 | 0 | Provider request records only |
| 3d visualization of debris clouds at the | records | 1 | 0 | Native records/view |
| regulatory compliance tracking backend outer space treaty | records | 1 | 0 | Native records/view |
| multi tenant operator support | records | 1 | 0 | Native records/view |
| Missions | records | 2 | 0 | Native records/view |
| Launch Vehicles | records | 1 | 0 | Native records/view |
| Range Assignments | records | 1 | 0 | Native records/view |
| Range Safety Zones | records | 1 | 0 | Native records/view |
| Debris Conjunctions | records | 1 | 0 | Native records/view |
| Comms Links | records | 1 | 0 | Native records/view |
| Payloads | records | 1 | 0 | Native records/view |
| Fuel Inventory | records | 1 | 0 | Native records/view |
| Weather Briefs | records | 1 | 0 | Native records/view |
| Anomalies | records | 1 | 0 | Native records/view |
| Telemetry | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Recovery Assets | records | 1 | 0 | Native records/view |
| Ground Systems | records | 1 | 0 | Native records/view |
| Regulatory Approvals | records | 1 | 0 | Native records/view |
| Post-Flight Reports | records | 1 | 0 | Native records/view |
| AI · Launch Window Optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Weather Window Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Mission Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Recovery Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Fuel Loadout Calc | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Payload Trajectory Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Ground Systems Checklist | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · NGS Link Budget | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Range Safety Assess | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Conjunction Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Anomaly Triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Debris Mitigation Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Post-Flight Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Draft Press Release | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Regulatory Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payload integration checklist | integration | 1 | 0 | Provider request records only |
| Sonic boom forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tenant comms | records | 1 | 0 | Native records/view |
| Customer portfolio | records | 1 | 0 | Native records/view |
| Marine clearance | records | 1 | 0 | Native records/view |
| Webhooks | integration | 1 | 0 | Provider request records only |
| Chips | records | 1 | 0 | Native records/view |
| Deployments | records | 1 | 0 | Native records/view |
| Tests | records | 1 | 0 | Native records/view |
| Manufacturers | records | 1 | 0 | Native records/view |
| Research | records | 1 | 0 | Native records/view |
| Rad test campaigns | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Orbit environments | records | 1 | 0 | Native records/view |
| Upscreen lots | records | 1 | 0 | Native records/view |
| Subsystem budgets | records | 1 | 0 | Native records/view |
| Rad hard foundries | records | 1 | 0 | Native records/view |
| Exports | records | 1 | 0 | Native records/view |
| Quality lots | records | 1 | 0 | Native records/view |
| thermal envelope solver | records | 1 | 0 | Native records/view |
| mass budget optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| single event upset | records | 1 | 0 | Native records/view |
| derating advisor | records | 1 | 0 | Native records/view |
| test coverage gap | records | 1 | 0 | Native records/view |
| eda cad upload | records | 1 | 0 | Native records/view |
| tier2 suppliers | records | 1 | 0 | Native records/view |
| itar flags | records | 1 | 0 | Native records/view |
| chamber scheduling | records | 1 | 0 | Native records/view |
| orbit telemetry ingest | records | 1 | 0 | Native records/view |
| chip digital twin | records | 1 | 0 | Native records/view |
| itar collaboration | records | 1 | 0 | Native records/view |
| rad test plan gen | records | 1 | 0 | Native records/view |
| mission derating | records | 1 | 0 | Native records/view |
| rad hard marketplace | records | 1 | 0 | Native records/view |
| Extraction Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resource Valuation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mission Planning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mining Yield | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regolith Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| EVA Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply Prioritizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Print jobs | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 147 feature pages were visited in the browser; 145 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 41 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

41 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
