[English](README.md) · [Deutsch](README.de.md)

# Jev AI Claims 193.6x Faster. I Checked the Math and Got 1.19x

Report Q011001 · Source medium.com · Date 2026-09-23 · [Open original](https://medium.com/ai-advances-briefs/jev-ai-claims-193-6x-faster-i-checked-the-math-and-got-1-19x-7f8437c45f73)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor hält Jevs große Geschwindigkeits- und Kostenvorteile für stark vom gewählten Vergleich und von der Aufgabe abhängig: In einem DSPy-Beispiel stieg die Gesamtgeschwindigkeit nur auf etwa 1,19-fach, während die Kosten um rund 30 Prozent sanken. Ein externer Phishing-Test fiel für Jevs direkte Einstufung schwächer aus als für Claude Haiku; gezielte Einzelabfragen mit zusätzlicher Auswertung erzielten dagegen bessere Werte, jedoch mit klaren Datensatz- und Versuchsgrenzen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 70 / 97 % | 100 / 100 % | 46 / 70 % | 17 / 36 % | 39 / 56 % | 17 / 36 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 43 / 85 % | 97 / 98 % | 15 / 40 % | 0 / 0 % | 12 / 25 % | 1 / 6 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 4 / 47 % | 95 / 97 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 2 / 22 % | 94 / 96 % | 13 / 37 % | 0 / 0 % | 9 / 18 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 16 / 75 % | 81 / 85 % | 19 / 45 % | 4 / 12 % | 16 / 27 % | 1 / 4 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 10 / 64 % | 69 / 76 % | 16 / 41 % | 4 / 11 % | 9 / 15 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 60 / 68 % | 18 / 42 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 38 / 74 % | 55 / 68 % | 22 / 49 % | 0 / 0 % | 12 / 21 % | 1 / 3 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 25 / 48 % | 55 / 66 % | 9 / 24 % | 0 / 0 % | 14 / 27 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 33 / 44 % | 7 / 17 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 3 / 33 % | 0 / 0 % | 17 / 46 % | 0 / 0 % | 19 / 32 % | 1 / 4 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 16 / 72 % | 0 / 0 % | 7 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 13 / 26 % | 15 / 37 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 36 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 2 / 26 % | 0 / 0 % | 12 / 28 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 10 / 16 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 5 % | 8 / 14 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 0 / 0 % | 6 / 9 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 4 / 7 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 47 % | 0 / 0 % | 7 / 20 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 1 / 22 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 5 / 8 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 3 / 7 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
