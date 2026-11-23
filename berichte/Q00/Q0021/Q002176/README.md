[English](README.md) · [Deutsch](README.de.md)

# MALT: A Dataset of Natural and Prompted Behaviors That Threaten Eval Integrity

Report Q002176 · Source metr.org · Date 2025-10-14 · [Open original](https://metr.org/blog/2025-10-14-malt-dataset-of-natural-and-prompted-behaviors/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR stellt MALT vor, einen Datensatz mit 10.919 Agententranskripten zur Prüfung von Monitoren für Reward Hacking und Sandbagging. Die besten Monitore erzielten hohe Erkennungswerte, doch natürliche Beispiele sind selten, künstlich erzeugte Fälle womöglich unrealistisch und subtile Minderleistung oft nicht aus Einzeltranskripten erkennbar. METR empfiehlt daher, die Ergebnisse als einen Baustein der Risikobewertung zu verstehen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 49 / 66 % | 100 / 100 % | 99 / 100 % | 74 / 86 % | 59 / 76 % | 65 / 81 % | 62 / 86 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 58 % | 56 / 95 % | 91 / 96 % | 42 / 71 % | 15 / 36 % | 44 / 71 % | 11 / 42 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 88 / 96 % | 77 / 88 % | 49 / 73 % | 13 / 30 % | 20 / 37 % | 11 / 33 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 49 / 66 % | 57 / 81 % | 84 / 91 % | 76 / 87 % | 39 / 62 % | 76 / 86 % | 30 / 61 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 39 / 73 % | 77 / 86 % | 16 / 44 % | 7 / 16 % | 17 / 31 % | 1 / 8 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 62 % | 74 / 98 % | 76 / 88 % | 62 / 82 % | 25 / 46 % | 53 / 72 % | 25 / 61 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 50 / 88 % | 73 / 86 % | 23 / 53 % | 0 / 0 % | 12 / 24 % | 1 / 9 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 13 / 58 % | 72 / 84 % | 31 / 59 % | 7 / 16 % | 0 / 0 % | 1 / 5 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 29 / 55 % | 31 / 60 % | 68 / 83 % | 56 / 76 % | 7 / 19 % | 21 / 40 % | 11 / 42 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 38 / 60 % | 64 / 87 % | 67 / 82 % | 38 / 64 % | 14 / 33 % | 41 / 64 % | 9 / 28 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 24 / 48 % | 0 / 0 % | 50 / 68 % | 13 / 32 % | 4 / 9 % | 12 / 22 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 34 / 84 % | 39 / 57 % | 11 / 35 % | 5 / 13 % | 11 / 25 % | 1 / 6 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 27 / 65 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 46 % | 0 / 0 % | 0 / 0 % | 24 / 53 % | 0 / 0 % | 10 / 19 % | 1 / 7 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 11 / 31 % | 23 / 48 % | 0 / 0 % | 11 / 21 % | 1 / 5 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 45 % | 13 / 60 % | 0 / 0 % | 9 / 28 % | 2 / 8 % | 10 / 21 % | 0 / 2 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 17 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 17 / 46 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 16 / 64 % | 0 / 0 % | 9 / 24 % | 0 / 0 % | 7 / 16 % | 0 / 2 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 40 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 3 / 8 % | 12 / 22 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 2 / 8 % | 0 / 0 % | 1 / 4 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 8 / 27 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
