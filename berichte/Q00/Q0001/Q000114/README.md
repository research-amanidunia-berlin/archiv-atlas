[English](README.md) · [Deutsch](README.de.md)

# Red-Teaming OpenAI's Internal Agent Monitoring Systems

Report Q000114 · Source metr.org · Date 2026-10-22 · [Open original](https://metr.org/blog/2026-10-22-red-teaming-openai-agent-monitoring/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Text ist ein Auszug: Er meldet mehrere Schwachstellen in OpenAIs damaligem internen Agenten-Monitoring, nennt aber keine konkreten Beispiele. METR und Redwood konnten spätere Änderungen und OpenAIs Angaben zu Reparaturen nicht überprüfen; ihre Empfehlungen betreffen unter anderem regelmäßige Überwachung, Protokollabgleich, Red-Team-Prüfungen und die Trennung von Agenten und Monitoren.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 50 / 68 % | 81 / 95 % | 40 / 67 % | 99 / 100 % | 71 / 85 % | 75 / 85 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 37 / 59 % | 82 / 99 % | 32 / 60 % | 99 / 100 % | 68 / 82 % | 63 / 75 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 57 / 75 % | 93 / 99 % | 85 / 94 % | 97 / 99 % | 81 / 90 % | 85 / 91 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 51 / 72 % | 78 / 93 % | 69 / 87 % | 95 / 99 % | 75 / 87 % | 61 / 76 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 50 / 71 % | 67 / 88 % | 46 / 73 % | 95 / 97 % | 64 / 79 % | 58 / 74 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 60 / 78 % | 88 / 99 % | 48 / 77 % | 93 / 97 % | 75 / 87 % | 80 / 88 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 22 / 41 % | 58 / 87 % | 2 / 10 % | 84 / 91 % | 29 / 57 % | 18 / 36 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 62 % | 55 / 93 % | 7 / 28 % | 81 / 92 % | 48 / 72 % | 48 / 68 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 40 % | 43 / 83 % | 3 / 13 % | 74 / 90 % | 11 / 29 % | 17 / 33 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 38 / 88 % | 12 / 35 % | 74 / 84 % | 55 / 76 % | 30 / 54 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 35 / 66 % | 13 / 28 % | 71 / 81 % | 42 / 70 % | 22 / 46 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 35 / 55 % | 5 / 55 % | 7 / 24 % | 0 / 0 % | 51 / 74 % | 69 / 82 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 27 / 52 % | 63 / 97 % | 29 / 55 % | 29 / 53 % | 56 / 77 % | 59 / 74 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 62 / 78 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 40 / 92 % | 2 / 8 % | 45 / 74 % | 19 / 45 % | 13 / 29 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 5 / 22 % | 41 / 65 % | 19 / 43 % | 18 / 32 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 49 % | 37 / 75 % | 0 / 4 % | 25 / 50 % | 12 / 34 % | 13 / 30 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 37 / 58 % | 7 / 13 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 23 / 53 % | 0 / 0 % | 33 / 48 % | 10 / 25 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 29 / 56 % | 3 / 16 % | 16 / 45 % | 25 / 56 % | 20 / 42 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 29 / 54 % | 6 / 14 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 25 / 61 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 5 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 11 / 31 % | 19 / 39 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 37 % | 9 / 19 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 13 / 25 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 24 % | 13 / 33 % | 11 / 21 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 1 / 13 % | 10 / 25 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 10 / 31 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 6 / 11 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 7 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
