[English](README.md) · [Deutsch](README.de.md)

# Evaluating frontier models for stealth and situational awareness

Report Q001016 · Source deepmind.google · Date 2026-07-15 · [Open original](https://deepmind.google/research/publications/157938/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Bericht ist nur ein Auszug. Er beschreibt Prüfungen zu Situationsbewusstsein und dem Umgehen von Aufsicht als mögliche Voraussetzungen für heimliches, fehlgeleitetes Verhalten von KI-Modellen; die Autor:innen sehen ein Scheitern an diesen Prüfungen als Hinweis gegen erfolgreiche Täuschung und führen Gemini als Beispiel an. Konkrete Tests und Ergebnisse fehlen im Auszug.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 56 % | 41 / 90 % | 10 / 39 % | 87 / 95 % | 32 / 62 % | 29 / 55 % | 16 / 43 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 33 / 62 % | 62 / 96 % | 57 / 81 % | 84 / 93 % | 5 / 10 % | 27 / 48 % | 11 / 30 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 43 / 65 % | 13 / 94 % | 76 / 89 % | 62 / 83 % | 66 / 82 % | 78 / 86 % | 66 / 82 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 47 / 69 % | 78 / 99 % | 62 / 82 % | 74 / 94 % | 59 / 79 % | 77 / 85 % | 67 / 82 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 4 / 16 % | 69 / 86 % | 27 / 54 % | 0 / 0 % | 4 / 12 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 59 % | 58 / 92 % | 40 / 72 % | 56 / 83 % | 45 / 71 % | 54 / 71 % | 41 / 69 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 47 / 68 % | 9 / 25 % | 0 / 0 % | 5 / 13 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 16 / 44 % | 27 / 85 % | 2 / 14 % | 41 / 82 % | 15 / 37 % | 6 / 14 % | 3 / 11 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 22 / 48 % | 14 / 60 % | 7 / 27 % | 33 / 80 % | 31 / 59 % | 17 / 34 % | 7 / 19 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 25 / 50 % | 0 / 0 % | 5 / 22 % | 19 / 54 % | 28 / 55 % | 20 / 40 % | 4 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 46 % | 22 / 58 % | 0 / 3 % | 11 / 40 % | 7 / 17 % | 5 / 11 % | 2 / 10 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 19 / 52 % | 0 / 0 % | 12 / 47 % | 9 / 26 % | 0 / 0 % | 1 / 3 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 17 / 51 % | 0 / 0 % | 1 / 7 % | 0 / 0 % | 13 / 36 % | 0 / 0 % | 1 / 7 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 27 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 52 % | 0 / 6 % | 0 / 0 % | 8 / 24 % | 9 / 17 % | 3 / 9 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 9 / 51 % | 0 / 4 % | 0 / 0 % | 8 / 24 % | 9 / 21 % | 3 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 6 / 44 % | 0 / 3 % | 0 / 0 % | 8 / 24 % | 5 / 12 % | 2 / 9 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 40 % | 0 / 0 % | 0 / 0 % | 0 / 2 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 7 / 16 % | 1 / 6 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 36 % | 0 / 0 % | 0 / 0 % | 0 / 1 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 1 / 5 % | 6 / 18 % | 0 / 0 % | 1 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 28 % | 5 / 15 % | 0 / 0 % | 1 / 3 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 3 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 2 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 3 % |
