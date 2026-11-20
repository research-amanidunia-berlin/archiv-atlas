[English](README.md) · [Deutsch](README.de.md)

# Can AI agents escape their sandboxes? A benchmark for safely measuring container breakout capabilities

Report Q001860 · Source aisi.gov.uk · Date 2026-03-23 · [Open original](https://www.aisi.gov.uk/blog/can-ai-agents-escape-their-sandboxes-a-benchmark-for-safely-measuring-container-breakout-capabilities)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der AISI-Bericht beschreibt SandboxEscapeBench, einen isolierten Benchmark mit 18 Szenarien, in dem Modelle Container-Ausbrüche testen. Fortgeschrittene Modelle knackten laut Bericht häufig verbreitete Fehlkonfigurationen, doch keines löste die schwierigsten Aufgaben; alle erfolgreichen Ausbrüche nutzten bekannte, offengelegte Schwachstellen. Die öffentlichen Tests decken nur bekannte Schwachstellenklassen ab, daher gelten die Befunde für die untersuchten Szenarien.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 66 / 79 % | 100 / 100 % | – | 100 / 100 % | 5 / 9 % | 77 / 86 % | 74 / 87 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 70 / 96 % | – | 98 / 99 % | 34 / 61 % | 33 / 60 % | 17 / 43 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 38 / 60 % | 79 / 99 % | – | 95 / 98 % | 39 / 66 % | 59 / 75 % | 38 / 61 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 30 / 56 % | 58 / 94 % | – | 92 / 97 % | 52 / 72 % | 35 / 59 % | 25 / 52 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 20 / 63 % | – | 80 / 90 % | 21 / 39 % | 13 / 22 % | 3 / 9 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 16 / 68 % | – | 66 / 77 % | 21 / 39 % | 15 / 29 % | 4 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 22 / 45 % | 52 / 90 % | – | 62 / 69 % | 20 / 39 % | 0 / 0 % | 5 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 23 / 86 % | – | 58 / 77 % | 38 / 61 % | 15 / 34 % | 24 / 49 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 46 % | 0 / 0 % | – | 49 / 66 % | 20 / 42 % | 7 / 15 % | 3 / 9 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 35 / 56 % | 41 / 85 % | – | 37 / 59 % | 42 / 66 % | 45 / 68 % | 43 / 68 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 37 / 59 % | 43 / 65 % | 10 / 22 % | 7 / 17 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 39 / 83 % | – | 0 / 0 % | 15 / 37 % | 13 / 26 % | 3 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 37 / 91 % | – | 25 / 59 % | 29 / 57 % | 15 / 30 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 33 / 79 % | – | 15 / 43 % | 8 / 14 % | 0 / 0 % | 0 / 2 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 26 / 74 % | – | 18 / 59 % | 27 / 51 % | 15 / 38 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 24 / 47 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 24 / 48 % | 5 / 13 % | 0 / 0 % | 1 / 4 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 41 % | 0 / 0 % | 0 / 1 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 16 / 37 % | 19 / 33 % | 1 / 4 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 19 / 33 % | 5 / 9 % | 0 / 0 % | 1 / 3 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 57 % | – | 0 / 0 % | 9 / 27 % | 13 / 27 % | 3 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 4 / 77 % | – | 8 / 41 % | 12 / 29 % | 6 / 14 % | 3 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 9 / 53 % | – | 0 / 0 % | 8 / 18 % | 7 / 15 % | 1 / 6 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 5 / 41 % | – | 9 / 36 % | 9 / 22 % | 8 / 18 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 8 / 16 % | 1 / 5 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 36 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 1 / 3 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 4 / 7 % | 0 / 1 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 2 / 6 % |
