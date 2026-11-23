[English](README.md) · [Deutsch](README.de.md)

# Red-Teaming OpenAI's Internal Agent Monitoring Systems

Report Q000114 · Source metr.org · Date 2026-10-22 · [Open original](https://metr.org/blog/2026-10-22-red-teaming-openai-agent-monitoring/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Text ist ein Auszug: Er meldet mehrere Schwachstellen in OpenAIs damaligem internen Agenten-Monitoring, nennt aber keine konkreten Beispiele. METR und Redwood konnten spätere Änderungen und OpenAIs Angaben zu Reparaturen nicht überprüfen; ihre Empfehlungen betreffen unter anderem regelmäßige Überwachung, Protokollabgleich, Red-Team-Prüfungen und die Trennung von Agenten und Monitoren.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 50 / 68 % | 81 / 95 % | 99 / 100 % | 71 / 85 % | 54 / 76 % | 75 / 85 % | 40 / 67 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 37 / 59 % | 82 / 99 % | 99 / 100 % | 68 / 82 % | 50 / 68 % | 63 / 75 % | 32 / 60 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 57 / 75 % | 93 / 99 % | 97 / 99 % | 81 / 90 % | 83 / 91 % | 85 / 91 % | 85 / 94 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 51 / 72 % | 78 / 93 % | 95 / 99 % | 75 / 87 % | 28 / 54 % | 61 / 76 % | 69 / 87 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 50 / 71 % | 67 / 88 % | 95 / 97 % | 64 / 79 % | 62 / 78 % | 58 / 74 % | 46 / 73 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 60 / 78 % | 88 / 99 % | 93 / 97 % | 75 / 87 % | 67 / 82 % | 80 / 88 % | 48 / 77 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 22 / 41 % | 58 / 87 % | 84 / 91 % | 29 / 57 % | 9 / 23 % | 18 / 36 % | 2 / 10 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 62 % | 55 / 93 % | 81 / 92 % | 48 / 72 % | 35 / 58 % | 48 / 68 % | 7 / 28 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 40 % | 43 / 83 % | 74 / 90 % | 11 / 29 % | 8 / 19 % | 17 / 33 % | 3 / 13 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 38 / 88 % | 74 / 84 % | 55 / 76 % | 12 / 33 % | 30 / 54 % | 12 / 35 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 35 / 66 % | 71 / 81 % | 42 / 70 % | 17 / 38 % | 22 / 46 % | 13 / 28 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 35 / 55 % | 5 / 55 % | 0 / 0 % | 51 / 74 % | 33 / 57 % | 69 / 82 % | 7 / 24 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 27 / 52 % | 63 / 97 % | 29 / 53 % | 56 / 77 % | 28 / 55 % | 59 / 74 % | 29 / 55 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 62 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 40 / 92 % | 45 / 74 % | 19 / 45 % | 6 / 21 % | 13 / 29 % | 2 / 8 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 41 / 65 % | 19 / 43 % | 6 / 15 % | 18 / 32 % | 5 / 22 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 49 % | 37 / 75 % | 25 / 50 % | 12 / 34 % | 3 / 15 % | 13 / 30 % | 0 / 4 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 37 / 58 % | 7 / 13 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 23 / 53 % | 33 / 48 % | 10 / 25 % | 4 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 29 / 56 % | 16 / 45 % | 25 / 56 % | 0 / 0 % | 20 / 42 % | 3 / 16 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 29 / 54 % | 6 / 14 % | 1 / 6 % | 0 / 0 % | 0 / 2 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 25 / 61 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 5 / 12 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 31 % | 4 / 13 % | 19 / 39 % | 1 / 4 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 37 % | 1 / 5 % | 9 / 19 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 13 % | 13 / 25 % | 0 / 2 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 10 / 24 % | 13 / 33 % | 5 / 13 % | 11 / 21 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 13 % | 10 / 25 % | 1 / 5 % | 0 / 0 % | 0 / 3 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 31 % | 1 / 7 % | 0 / 0 % | 0 / 2 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 1 / 3 % | 7 / 16 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
