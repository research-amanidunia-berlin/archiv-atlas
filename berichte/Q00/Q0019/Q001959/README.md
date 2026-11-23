[English](README.md) · [Deutsch](README.de.md)

# Boundary Point Jailbreaking: A new way to break the strongest AI defences

Report Q001959 · Source aisi.gov.uk · Date 2026-02-17 · [Open original](https://www.aisi.gov.uk/blog/boundary-point-jailbreaking-a-new-way-to-break-the-strongest-ai-defences)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Das AI Security Institute berichtet, mit BPJ ein automatisiertes Black-Box-Verfahren entwickelt zu haben, das Schutzklassifikatoren von Anthropic und OpenAI umgehen konnte. Es kombiniert schrittweise Zwischenziele mit der Suche nach Klassifikator-Grenzpunkten und erzielte laut den beschriebenen Tests teils hohe Bewertungswerte. Die Aussagekraft ist auf diese Tests begrenzt; AISI veröffentlicht weder Angriffstexte noch Code und empfiehlt Überwachung über mehrere Interaktionen hinweg.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 33 / 51 % | 77 / 96 % | 99 / 100 % | 43 / 66 % | 5 / 16 % | 27 / 49 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 29 / 50 % | 40 / 75 % | 83 / 91 % | 6 / 13 % | 7 / 23 % | 25 / 47 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 50 % | 55 / 96 % | 83 / 89 % | 23 / 51 % | 10 / 27 % | 37 / 62 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 62 / 93 % | 82 / 87 % | 43 / 64 % | 7 / 16 % | 34 / 49 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 17 / 83 % | 80 / 89 % | 23 / 42 % | 4 / 14 % | 11 / 22 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 23 / 56 % | 71 / 81 % | 24 / 48 % | 4 / 15 % | 13 / 26 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 46 / 89 % | 70 / 81 % | 16 / 39 % | 5 / 14 % | 10 / 20 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 62 / 95 % | 70 / 75 % | 24 / 44 % | 5 / 13 % | 17 / 32 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 29 / 95 % | 55 / 69 % | 36 / 59 % | 0 / 0 % | 20 / 39 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 48 / 81 % | 4 / 14 % | 21 / 45 % | 3 / 11 % | 8 / 18 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 39 / 60 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 5 / 31 % | 37 / 55 % | 19 / 43 % | 2 / 9 % | 6 / 13 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 35 / 90 % | 26 / 61 % | 31 / 58 % | 4 / 17 % | 17 / 34 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 9 / 60 % | 33 / 72 % | 13 / 34 % | 2 / 10 % | 8 / 18 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 32 / 71 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 5 / 10 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 29 / 64 % | 6 / 17 % | 1 / 6 % | 4 / 10 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 6 / 48 % | 0 / 0 % | 21 / 47 % | 0 / 0 % | 19 / 35 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 19 / 89 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 18 / 49 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 18 / 34 % | 9 / 24 % | 1 / 7 % | 5 / 12 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 7 / 67 % | 0 / 0 % | 10 / 29 % | 2 / 10 % | 11 / 24 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 28 % | 1 / 5 % | 11 / 23 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 9 / 64 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 8 / 52 % | 4 / 24 % | 8 / 20 % | 1 / 5 % | 5 / 11 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 6 / 45 % | 0 / 0 % | 6 / 16 % | 1 / 6 % | 7 / 15 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 1 / 8 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 7 / 74 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 5 / 29 % | 6 / 13 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 10 % | – | – |
