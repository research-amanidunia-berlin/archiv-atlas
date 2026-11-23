[English](README.md) · [Deutsch](README.de.md)

# 7 Rules for Self-Improving AI Agent Loops Every AI Engineer Should Know

Report Q011219 · Source medium.com · Date 2026-08-16 · [Open original](https://medium.com/coding-nexus/7-rules-for-self-improving-ai-agent-loops-every-ai-engineer-should-know-721b348206c2)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Code Coup zufolge hängt die Qualität selbstverbessernder Agenten vor allem davon ab, was ihre Tests und Bewertungsmaßstäbe belohnen. Der Beitrag empfiehlt konkrete, schrittweise Tests, erklärende Bewertungen, geschützte Kriterien und eine Diagnose der Fehler, bevor Prompts optimiert werden; die Regeln werden als Empfehlungen dargestellt, nicht durch Vergleichsdaten belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 29 / 56 % | 91 / 99 % | 98 / 100 % | 49 / 72 % | 27 / 56 % | 44 / 66 % | 18 / 56 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 53 % | 68 / 96 % | 96 / 98 % | 36 / 64 % | 16 / 39 % | 24 / 48 % | 12 / 38 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 93 / 100 % | 94 / 97 % | 11 / 29 % | 6 / 14 % | 10 / 18 % | 19 / 42 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 15 / 41 % | 92 / 96 % | 7 / 16 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 55 % | 78 / 96 % | 90 / 93 % | 36 / 64 % | 23 / 47 % | 27 / 53 % | 23 / 62 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 25 / 52 % | 64 / 95 % | 84 / 94 % | 28 / 54 % | 5 / 21 % | 12 / 29 % | 9 / 39 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 26 / 84 % | 78 / 94 % | 17 / 41 % | 4 / 14 % | 10 / 22 % | 2 / 13 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 36 / 71 % | 65 / 80 % | 6 / 13 % | 1 / 4 % | 5 / 14 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 39 / 96 % | 57 / 80 % | 14 / 45 % | 4 / 14 % | 12 / 30 % | 2 / 11 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 42 / 97 % | 54 / 85 % | 14 / 36 % | 6 / 20 % | 14 / 31 % | 2 / 10 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 24 / 48 % | 34 / 65 % | 54 / 73 % | 33 / 62 % | 10 / 30 % | 28 / 52 % | 4 / 16 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 12 / 40 % | 11 / 69 % | 37 / 75 % | 7 / 26 % | 5 / 18 % | 8 / 20 % | 1 / 8 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 11 / 49 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 37 % | 1 / 56 % | 0 / 0 % | 8 / 22 % | 4 / 16 % | 7 / 19 % | 0 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 33 % | 2 / 43 % | 10 / 27 % | 8 / 26 % | 1 / 9 % | 4 / 13 % | 0 / 4 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 4 / 10 % | 8 / 16 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 1 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 3 / 7 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 2 / 4 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 3 / 57 % | 0 / 0 % | 5 / 10 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 3 / 5 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 45 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
