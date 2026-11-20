[English](README.md) · [Deutsch](README.de.md)

# Transcript analysis for AI agent evaluations

Report Q002546 · Source aisi.gov.uk · Date 2025-10-10 · [Open original](https://www.aisi.gov.uk/blog/transcript-analysis-for-ai-agent-evaluations)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Das AISI berichtet, dass Erfolgsquoten allein nicht zeigen, warum KI-Agenten scheitern oder wie sicherheitsrelevantes Verhalten und technische Prüfungsfehler die Ergebnisse beeinflussen. In 6.390 Protokollen aus Cyberaufgaben fand es unter anderem Ablehnungen, häufiges Aufgeben und geringe Befolgung einer Werkzeugvorgabe; die ausführliche Auswertung steht laut Beitrag in einer separaten Fallstudie.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 42 / 65 % | 88 / 95 % | – | 99 / 100 % | 51 / 75 % | 51 / 73 % | 59 / 77 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 54 / 76 % | 70 / 95 % | – | 85 / 97 % | 5 / 12 % | 37 / 62 % | 61 / 77 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 46 % | 47 / 75 % | – | 84 / 92 % | 20 / 41 % | 12 / 30 % | 17 / 32 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 43 / 62 % | 57 / 98 % | – | 81 / 93 % | 72 / 86 % | 63 / 78 % | 67 / 81 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 31 / 58 % | 43 / 83 % | – | 81 / 94 % | 46 / 70 % | 9 / 25 % | 33 / 55 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 27 / 52 % | 46 / 85 % | – | 74 / 78 % | 32 / 53 % | 9 / 20 % | 34 / 47 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 33 / 53 % | 36 / 78 % | – | 66 / 88 % | 30 / 61 % | 12 / 36 % | 28 / 55 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 28 / 51 % | 0 / 0 % | – | 47 / 80 % | 41 / 67 % | 13 / 31 % | 16 / 31 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 39 / 61 % | 33 / 93 % | – | 47 / 77 % | 38 / 66 % | 24 / 46 % | 27 / 53 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 24 / 47 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 21 / 41 % | 0 / 0 % | – | 3 / 25 % | 22 / 50 % | 7 / 22 % | 17 / 31 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 20 / 53 % | 0 / 0 % | – | 0 / 0 % | 21 / 48 % | 7 / 19 % | 11 / 21 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 9 / 38 % | 20 / 61 % | – | 0 / 15 % | 12 / 38 % | 3 / 16 % | 13 / 28 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 19 / 44 % | 14 / 60 % | – | 10 / 26 % | 9 / 28 % | 4 / 12 % | 11 / 22 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 7 / 67 % | – | 10 / 50 % | 15 / 45 % | 4 / 13 % | 13 / 28 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 15 / 40 % | 7 / 16 % | 1 / 4 % | 5 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 35 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 4 / 10 % | 8 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 1 / 5 % | 10 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 33 % | 0 / 0 % | – | 0 / 0 % | 8 / 25 % | 1 / 6 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 28 % | 1 / 3 % | 10 / 20 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 32 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 3 / 10 % | 9 / 20 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 9 / 35 % | 5 / 13 % | 1 / 5 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 12 % | 8 / 21 % | 1 / 4 % | 5 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 0 / 2 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 3 % | 3 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 1 / 5 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 3 / 9 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 19 % | 1 / 6 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 2 / 21 % | 5 / 10 % | 0 / 1 % | 5 / 9 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 1 / 4 % | 5 / 10 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 1 / 5 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 1 / 4 % | 5 / 10 % |
