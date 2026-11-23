[English](README.md) · [Deutsch](README.de.md)

# Building self-improving tax agents with Codex

Report Q006858 · Source openai.com · Date 2026-05-27 · [Open original](https://openai.com/index/building-self-improving-tax-agents-with-codex/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht schildert, wie OpenAI, Thrive Holdings und Crete Tax AI mithilfe fachlicher Korrekturen, detaillierter Produktionsdaten und Codex-gestützter Tests schrittweise verbessern. Laut den beteiligten Unternehmen stiegen Effizienz und Feldvollständigkeit im Pilotbetrieb deutlich; die genannten Kennzahlen sind jedoch Unternehmensangaben und belegen keine fehlerfreien Erklärungen oder unabhängige Überprüfung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 39 / 57 % | 99 / 99 % | 100 / 100 % | 69 / 83 % | 55 / 74 % | 60 / 72 % | 40 / 65 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 34 / 56 % | 83 / 94 % | 100 / 100 % | 66 / 81 % | 29 / 52 % | 43 / 61 % | 55 / 76 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 75 / 92 % | 100 / 100 % | 20 / 43 % | 17 / 33 % | 13 / 33 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 95 / 98 % | 81 / 89 % | 15 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 23 / 44 % | 35 / 78 % | 94 / 97 % | 31 / 57 % | 13 / 31 % | 29 / 48 % | 5 / 19 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 46 % | 87 / 97 % | 82 / 88 % | 38 / 65 % | 26 / 46 % | 35 / 55 % | 7 / 22 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 81 / 98 % | 65 / 87 % | 21 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 78 / 91 % | 17 / 36 % | 4 / 12 % | 7 / 14 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 71 / 82 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 38 / 74 % | 0 / 0 % | 13 / 32 % | 3 / 9 % | 5 / 10 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 22 / 87 % | 30 / 51 % | 6 / 16 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 16 / 41 % | 23 / 54 % | 0 / 0 % | 29 / 54 % | 15 / 34 % | 28 / 49 % | 4 / 12 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 28 / 75 % | 0 / 0 % | 10 / 25 % | 1 / 7 % | 6 / 15 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 40 % | 5 / 12 % | 7 / 17 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 36 % | 8 / 18 % | 14 / 26 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 30 % | 4 / 12 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 1 / 3 % | 11 / 23 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 8 / 18 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 3 / 9 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 6 / 11 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 3 % | 6 / 15 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
