[English](README.md) · [Deutsch](README.de.md)

# Transect: Making large-scale agentic evaluations easier to understand

Report Q000155 · Source aisi.gov.uk · Date 2026-10-07 · [Open original](https://www.aisi.gov.uk/blog/transect-making-large-scale-agentic-evaluations-easier-to-understand)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Transect soll lange KI-Agenten-Auswertungen durch interaktive Zeitleisten, Aktivitätslabels und verlinkte Transkriptstellen leichter prüfbar machen; ein Fallbeispiel zeigt dokumentenbasierte Zusammenarbeit zwischen Unteragenten. Die dargestellten Labels können falsch sein, Dateizugriffe beweisen keinen Einfluss, und die Zeitleiste bildet weder verstrichene Zeit noch Gleichzeitigkeit ab – verlässliche Schlüsse erfordern laut Bericht weiterhin menschliches Fachurteil.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 59 % | 97 / 100 % | – | 95 / 100 % | 44 / 72 % | 34 / 61 % | 51 / 75 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 18 / 52 % | 58 / 97 % | – | 80 / 95 % | 37 / 65 % | 8 / 29 % | 31 / 63 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 19 / 47 % | 72 / 98 % | – | 74 / 87 % | 23 / 48 % | 10 / 29 % | 31 / 52 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 25 / 50 % | 66 / 95 % | – | 73 / 94 % | 22 / 51 % | 11 / 32 % | 28 / 62 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 18 / 49 % | 61 / 92 % | – | 71 / 95 % | 36 / 63 % | 9 / 29 % | 26 / 55 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 43 / 90 % | – | 60 / 76 % | 8 / 21 % | 1 / 5 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 20 / 48 % | 51 / 84 % | – | 59 / 65 % | 22 / 44 % | 4 / 12 % | 14 / 28 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 33 / 67 % | – | 54 / 81 % | 31 / 62 % | 14 / 35 % | 23 / 52 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 15 / 46 % | 26 / 53 % | – | 53 / 75 % | 14 / 31 % | 2 / 6 % | 12 / 23 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 27 / 52 % | 25 / 91 % | – | 50 / 81 % | 38 / 69 % | 12 / 29 % | 44 / 66 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 20 / 55 % | 41 / 88 % | – | 26 / 72 % | 8 / 18 % | 7 / 24 % | 26 / 57 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 49 % | 39 / 94 % | – | 11 / 37 % | 18 / 46 % | 5 / 20 % | 15 / 35 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 26 / 50 % | 22 / 90 % | – | 20 / 75 % | 39 / 66 % | 18 / 41 % | 31 / 55 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 38 / 87 % | – | 24 / 56 % | 8 / 20 % | 1 / 5 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 25 / 51 % | 37 / 98 % | – | 23 / 63 % | 16 / 48 % | 0 / 0 % | 18 / 48 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 21 / 49 % | 3 / 68 % | – | 23 / 54 % | 28 / 58 % | 6 / 20 % | 8 / 21 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 20 / 47 % | 22 / 98 % | – | 27 / 64 % | 9 / 30 % | 4 / 15 % | 14 / 29 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 25 / 85 % | – | 4 / 45 % | 11 / 33 % | 0 / 0 % | 9 / 24 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 25 / 51 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 49 % | 11 / 62 % | – | 22 / 51 % | 15 / 42 % | 6 / 19 % | 8 / 19 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 20 / 70 % | – | 0 / 0 % | 9 / 25 % | 0 / 0 % | 8 / 17 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 19 / 72 % | – | 0 / 0 % | 6 / 15 % | 1 / 6 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 17 / 44 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 15 / 37 % | 0 / 0 % | – | 2 / 24 % | 13 / 37 % | 4 / 13 % | 10 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 35 % | 14 / 66 % | – | 1 / 17 % | 8 / 23 % | 3 / 13 % | 10 / 25 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 44 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 9 / 54 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 9 / 63 % | – | 1 / 15 % | 9 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 1 / 8 % | 8 / 20 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 1 / 4 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 13 % | 0 / 0 % | 5 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 3 / 18 % | 6 / 15 % | 1 / 5 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
