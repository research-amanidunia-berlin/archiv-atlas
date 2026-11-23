[English](README.md) · [Deutsch](README.de.md)

# Example autonomy evaluation protocol

Report Q002902 · Source metr.org · Date 2024-03-15 · [Open original](https://metr.org/blog/2024-03-15-example-autonomy-evaluation-protocol/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR schlägt ein vorläufiges Prüfverfahren für KI-Fähigkeiten vor, die autonome Risiken ermöglichen könnten: Aufgaben verschiedener Schwierigkeit werden getestet und zu einem „Zeithorizont“-Wert zusammengefasst, der zusammen mit einer Bedrohungsanalyse Schutzmaßnahmen informieren soll. Das Verfahren deckt andere Risikotypen nicht ab; seine Metrik, Aufgabenauswahl und Schwellenwerte sind laut Bericht noch unsicher und nicht ausreichend validiert.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 63 / 78 % | 100 / 100 % | 99 / 100 % | 88 / 94 % | 81 / 92 % | 91 / 94 % | 96 / 99 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 57 / 73 % | 98 / 99 % | 100 / 100 % | 72 / 87 % | 77 / 90 % | 88 / 93 % | 91 / 97 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 78 / 87 % | 92 / 94 % | 99 / 100 % | 85 / 93 % | 88 / 94 % | 86 / 91 % | 97 / 99 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 25 / 46 % | 96 / 99 % | 70 / 84 % | 41 / 68 % | 21 / 41 % | 30 / 49 % | 11 / 36 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 59 % | 87 / 97 % | 93 / 97 % | 39 / 67 % | 29 / 53 % | 56 / 75 % | 31 / 72 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 49 % | 91 / 99 % | 40 / 78 % | 44 / 71 % | 12 / 42 % | 60 / 76 % | 16 / 32 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 49 / 67 % | 83 / 96 % | 86 / 94 % | 70 / 85 % | 29 / 56 % | 81 / 89 % | 58 / 86 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 26 / 46 % | 75 / 96 % | 83 / 89 % | 29 / 58 % | 13 / 31 % | 24 / 42 % | 8 / 22 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 29 / 59 % | 49 / 82 % | 78 / 90 % | 20 / 44 % | 16 / 39 % | 22 / 44 % | 14 / 41 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 44 / 63 % | 50 / 91 % | 74 / 88 % | 61 / 81 % | 34 / 62 % | 22 / 45 % | 23 / 61 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 21 / 47 % | 73 / 95 % | 48 / 78 % | 29 / 53 % | 2 / 8 % | 16 / 29 % | 6 / 12 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 30 / 53 % | 64 / 96 % | 45 / 62 % | 33 / 61 % | 11 / 29 % | 42 / 65 % | 11 / 40 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 26 / 54 % | 60 / 92 % | 37 / 77 % | 32 / 58 % | 8 / 28 % | 41 / 62 % | 14 / 53 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 33 % | 0 / 0 % | 60 / 84 % | 10 / 35 % | 3 / 16 % | 9 / 24 % | 2 / 16 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 15 / 29 % | 58 / 89 % | 56 / 77 % | 24 / 53 % | 5 / 16 % | 12 / 27 % | 5 / 16 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 15 / 43 % | 53 / 93 % | 34 / 62 % | 30 / 57 % | 11 / 32 % | 36 / 58 % | 9 / 26 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 51 / 80 % | 23 / 50 % | 20 / 45 % | 5 / 14 % | 11 / 21 % | 2 / 9 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 12 / 33 % | 45 / 80 % | 41 / 59 % | 18 / 46 % | 5 / 17 % | 7 / 19 % | 1 / 7 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 10 / 42 % | 40 / 62 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 39 / 82 % | 21 / 40 % | 18 / 47 % | 5 / 19 % | 10 / 23 % | 5 / 15 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 73 % | 0 / 7 % | 6 / 17 % | 0 / 0 % | 6 / 15 % | 0 / 5 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 20 / 43 % | 0 / 0 % | 9 / 22 % | 12 / 35 % | 3 / 11 % | 26 / 48 % | 1 / 7 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 25 / 67 % | 1 / 20 % | 8 / 25 % | 2 / 10 % | 5 / 12 % | 1 / 5 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 19 / 40 % | 0 / 0 % | 0 / 0 % | 17 / 43 % | 6 / 16 % | 24 / 43 % | 3 / 13 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 21 / 56 % | 16 / 33 % | 9 / 24 % | 0 / 0 % | 3 / 7 % | 0 / 1 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 14 / 34 % | 15 / 36 % | 3 / 11 % | 10 / 18 % | 1 / 2 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 12 / 66 % | 0 / 0 % | 12 / 34 % | 0 / 0 % | 15 / 39 % | 1 / 6 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 10 / 26 % | 13 / 58 % | 0 / 0 % | 6 / 17 % | 2 / 9 % | 5 / 12 % | 0 / 0 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 11 / 44 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 28 % | 2 / 10 % | 7 / 22 % | 0 / 4 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 10 / 51 % | 0 / 0 % | 6 / 18 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 72 % | 1 / 9 % | 6 / 18 % | 0 / 0 % | 6 / 11 % | 0 / 1 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
