[English](README.md) · [Deutsch](README.de.md)

# Finding Cloud Misconfigurations with Frontier AI: A Case Study

Report Q001383 · Source aisi.gov.uk · Date 2026-07-07 · [Open original](https://www.aisi.gov.uk/blog/finding-cloud-misconfigurations-with-frontier-ai-a-case-study)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AISI berichtet von einem zweiwöchigen Test, bei dem Frontier-KI-Modelle in einer von der Produktion getrennten AWS-Staging-Umgebung mehrere behebenswerte Schwachstellen fanden. Eine fünfstufige Angriffskette ermöglichte laut Bericht die Rechteausweitung und den Zugriff auf Daten anderer Nutzer; Quellcodeanalyse erzeugte viele Meldungen, aber auch erhebliches Rauschen, während autonomes Testen und Red-Teaming aussagekräftigere Funde lieferten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 56 % | 94 / 100 % | 97 / 99 % | 49 / 74 % | 30 / 53 % | 68 / 82 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 30 / 52 % | 69 / 90 % | 97 / 99 % | 63 / 80 % | 13 / 34 % | 47 / 68 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 51 / 70 % | 61 / 90 % | 95 / 99 % | 6 / 13 % | 53 / 72 % | 73 / 84 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 23 / 52 % | 95 / 97 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 48 % | 50 / 92 % | 92 / 96 % | 37 / 63 % | 12 / 33 % | 38 / 63 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 36 / 55 % | 58 / 79 % | 88 / 91 % | 49 / 68 % | 12 / 24 % | 42 / 56 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 51 / 86 % | 81 / 89 % | 26 / 48 % | 5 / 12 % | 21 / 37 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 15 / 44 % | 34 / 66 % | 77 / 87 % | 31 / 56 % | 4 / 14 % | 12 / 22 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 59 / 91 % | 34 / 66 % | 23 / 49 % | 6 / 16 % | 19 / 40 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 55 / 72 % | 8 / 18 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 50 / 86 % | 49 / 68 % | 41 / 63 % | 12 / 33 % | 38 / 62 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 29 / 46 % | 36 / 69 % | 41 / 75 % | 45 / 68 % | 9 / 23 % | 35 / 56 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 42 / 75 % | 43 / 66 % | 8 / 20 % | 10 / 22 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 12 / 64 % | 41 / 59 % | 15 / 42 % | 3 / 10 % | 16 / 29 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 11 / 65 % | 0 / 0 % | 28 / 52 % | 0 / 0 % | 12 / 21 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 48 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 28 / 52 % | 9 / 23 % | 2 / 7 % | 4 / 8 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 14 / 25 % | 8 / 61 % | 26 / 57 % | 14 / 36 % | 0 / 0 % | 6 / 13 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 25 / 67 % | 24 / 59 % | 20 / 49 % | 3 / 11 % | 12 / 26 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 12 / 33 % | 14 / 46 % | 3 / 19 % | 24 / 48 % | 8 / 25 % | 23 / 47 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 14 / 34 % | 4 / 85 % | 7 / 52 % | 23 / 45 % | 7 / 20 % | 14 / 32 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 21 / 51 % | 7 / 17 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 41 % | 2 / 6 % | 17 / 28 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 17 / 50 % | 7 / 16 % | 0 / 1 % | 10 / 17 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 28 % | 0 / 0 % | 14 / 44 % | 11 / 29 % | 1 / 7 % | 14 / 29 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 41 % | 0 / 0 % | 11 / 22 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 11 / 21 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 2 / 21 % | 7 / 23 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 2 / 6 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 4 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 7 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 0 / 0 % | – | – |
