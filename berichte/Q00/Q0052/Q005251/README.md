[English](README.md) · [Deutsch](README.de.md)

# Harness, Loops, Graphs: What 217 Real Agent Loops Are Missing (Full Guide)

Report Q005251 · Source x.com · Date 2026-11-05 · [Open original](https://x.com/iiiichigo_chan/status/2118397992239571196)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht empfiehlt, Coding-Agenten nicht bloß zeitgesteuert laufen zu lassen, sondern sie mit unabhängigen Prüfungen, aussagekräftigem Feedback, gespeichertem Zustand, festen Abbruchgrenzen und menschlicher Kontrolle einzurahmen. Für komplexe Aufgaben sollen explizite Arbeitsgraphen genutzt werden; die angeführten Studien lassen laut Beitrag jedoch erkennen, dass mehrere Agenten je nach Aufgabe helfen oder schaden können. Die zugrunde liegende Repository-Zählung erfasst nur öffentliche Standardzweige, und die Beispielskripte wurden laut Autor nur mit einem Platzhalter-Agenten geprüft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 100 / 100 % | 100 / 100 % | 44 / 66 % | 30 / 49 % | 38 / 56 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 46 / 60 % | 99 / 100 % | 100 / 100 % | 75 / 86 % | 62 / 78 % | 64 / 79 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 70 / 82 % | 100 / 100 % | 100 / 100 % | 87 / 93 % | 73 / 86 % | 76 / 85 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 48 / 63 % | 95 / 99 % | 99 / 99 % | 72 / 85 % | 30 / 51 % | 57 / 77 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 51 / 67 % | 94 / 100 % | 98 / 99 % | 77 / 88 % | 67 / 84 % | 83 / 91 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 77 / 95 % | 98 / 99 % | 12 / 28 % | 13 / 24 % | 16 / 31 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 61 / 93 % | 95 / 98 % | 13 / 27 % | 0 / 0 % | 10 / 16 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 26 / 46 % | 92 / 97 % | 44 / 64 % | 32 / 54 % | 17 / 30 % | 37 / 57 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 76 / 99 % | 91 / 96 % | 35 / 62 % | 0 / 0 % | 30 / 55 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 46 / 86 % | 90 / 94 % | 8 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 80 / 85 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 79 / 96 % | 67 / 77 % | 38 / 62 % | 32 / 47 % | 35 / 55 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 12 / 62 % | 73 / 80 % | 13 / 29 % | 0 / 0 % | 12 / 19 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 66 / 87 % | 0 / 0 % | 59 / 79 % | 24 / 40 % | 44 / 63 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 13 / 69 % | 56 / 70 % | 10 / 21 % | 0 / 0 % | 5 / 7 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 34 / 58 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 26 / 43 % | 7 / 14 % | 0 / 0 % | 5 / 9 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 40 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 16 / 34 % | 5 / 10 % | 1 / 2 % | 6 / 10 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 14 / 50 % | 0 / 0 % | 13 / 28 % | 0 / 0 % | 7 / 12 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 3 / 7 % | 13 / 26 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 13 / 54 % | 12 / 33 % | 12 / 25 % | 7 / 15 % | 9 / 17 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 14 % | 0 / 0 % | 10 / 15 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 3 % | 9 / 15 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 7 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 4 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 6 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 89 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
