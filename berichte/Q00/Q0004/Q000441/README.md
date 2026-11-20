[English](README.md) · [Deutsch](README.de.md)

# Control Room: A central system to track and stop model workloads across our research infrastructure

Report Q000441 · Source openai.com · Date – · [Open original](https://openai.com/index/control-room/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt Control Room als zentrale Sperre für Forschungsinferenz: Nach einem Stopp verweigern Engines weitere Anfragen des betroffenen Jobs, auch über andere Modelle hinweg. Laut OpenAI kann die Durchsetzung bis zu 35 Sekunden dauern; ein Ausfall des Dienstes soll Inferenz blockieren, und der Rollout dieser Ausfallsicherung war noch nicht für alle Forschungsjobs abgeschlossen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 53 / 66 % | 96 / 99 % | – | 100 / 100 % | 73 / 86 % | 59 / 76 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 85 / 91 % | 100 / 100 % | – | 100 / 100 % | 94 / 96 % | 88 / 92 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 35 / 56 % | 96 / 99 % | – | 63 / 93 % | 61 / 79 % | 55 / 72 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 50 / 68 % | 94 / 98 % | – | 87 / 94 % | 69 / 83 % | 41 / 60 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 88 / 91 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 15 / 39 % | 77 / 98 % | – | 86 / 93 % | 44 / 68 % | 24 / 49 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 60 % | 77 / 99 % | – | 83 / 92 % | 47 / 72 % | 50 / 69 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 29 / 44 % | 55 / 84 % | – | 82 / 90 % | 30 / 53 % | 12 / 21 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 66 / 88 % | – | 57 / 74 % | 16 / 36 % | 16 / 30 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 6 / 40 % | – | 61 / 84 % | 8 / 20 % | 13 / 26 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 19 / 45 % | 53 / 83 % | – | 29 / 49 % | 15 / 37 % | 24 / 44 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 25 / 42 % | 17 / 59 % | – | 19 / 35 % | 43 / 68 % | 48 / 65 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 42 / 75 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 26 / 53 % | – | 42 / 66 % | 5 / 13 % | 4 / 10 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 38 / 80 % | – | 6 / 29 % | 11 / 32 % | 14 / 26 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 37 / 67 % | – | 28 / 49 % | 6 / 13 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 25 / 44 % | 32 / 65 % | – | 33 / 52 % | 22 / 46 % | 12 / 23 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 24 / 46 % | 0 / 0 % | – | 0 / 0 % | 21 / 49 % | 32 / 51 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 28 / 50 % | 29 / 88 % | – | 22 / 48 % | 20 / 49 % | 20 / 41 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 27 / 53 % | 0 / 0 % | – | 0 / 0 % | 13 / 39 % | 20 / 34 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 25 / 83 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 23 / 61 % | – | 10 / 26 % | 17 / 45 % | 11 / 23 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 21 / 50 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 20 / 40 % | 19 / 66 % | – | 0 / 0 % | 9 / 23 % | 13 / 25 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 18 / 40 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 17 / 71 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 16 / 38 % | 5 / 11 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 12 / 29 % | 10 / 26 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 11 / 29 % | 11 / 62 % | – | 2 / 18 % | 8 / 19 % | 9 / 20 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 29 % | 6 / 10 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 7 % | 7 / 17 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 13 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % |
