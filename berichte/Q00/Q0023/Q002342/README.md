[English](README.md) · [Deutsch](README.de.md)

# Pre-deployment evaluation of Anthropic’s upgraded Claude 3.5 Sonnet

Report Q002342 · Source aisi.gov.uk · Date 2024-11-19 · [Open original](https://www.aisi.gov.uk/blog/pre-deployment-evaluation-of-anthropics-upgraded-claude-3-5-sonnet)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Überblick berichtet, dass das aktualisierte Claude 3.5 Sonnet je nach Testbereich ähnliche oder höhere Leistungen als die Vergleichsmodelle zeigte; bei biologischen Aufgaben war die Leistung des Modells allein meist deutlich unter gemessenen Expertenwerten. Beide Institute konnten die geprüften Schutzvorkehrungen regelmäßig durch Jailbreaks umgehen. Die Ergebnisse sind vorläufig und beruhen auf begrenzten Tests; der verlinkte technische Bericht ist im bereitgestellten Text nicht enthalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 69 / 83 % | 98 / 100 % | – | 99 / 100 % | 8 / 23 % | 81 / 89 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 51 / 70 % | 75 / 93 % | – | 98 / 99 % | 72 / 85 % | 60 / 74 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 52 % | 64 / 98 % | – | 95 / 98 % | 44 / 71 % | 36 / 64 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 61 / 78 % | 82 / 98 % | – | 94 / 96 % | 84 / 91 % | 72 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 56 % | 88 / 99 % | – | 92 / 96 % | 40 / 69 % | 52 / 73 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 29 / 91 % | – | 90 / 96 % | 56 / 76 % | 21 / 45 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 31 / 51 % | 88 / 96 % | – | 86 / 94 % | 39 / 62 % | 44 / 62 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 36 / 54 % | 38 / 95 % | – | 80 / 88 % | 53 / 73 % | 24 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 23 / 49 % | 50 / 85 % | – | 73 / 86 % | 54 / 77 % | 54 / 73 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 59 / 77 % | 7 / 18 % | 5 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 32 / 80 % | – | 55 / 76 % | 13 / 35 % | 10 / 20 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 33 / 56 % | 54 / 94 % | – | 37 / 60 % | 30 / 62 % | 18 / 35 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 38 / 59 % | 52 / 92 % | – | 20 / 57 % | 49 / 72 % | 48 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 12 / 61 % | – | 47 / 69 % | 39 / 66 % | 43 / 64 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 18 / 40 % | 24 / 88 % | – | 41 / 69 % | 36 / 61 % | 21 / 41 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 24 / 52 % | 39 / 95 % | – | 15 / 55 % | 30 / 62 % | 22 / 47 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 30 / 96 % | – | 38 / 71 % | 25 / 50 % | 17 / 37 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 38 / 56 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 25 / 51 % | 36 / 86 % | – | 17 / 52 % | 36 / 64 % | 36 / 60 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 19 / 43 % | 3 / 36 % | – | 32 / 61 % | 11 / 35 % | 10 / 23 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 18 / 57 % | – | 28 / 58 % | 8 / 23 % | 6 / 14 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 14 / 63 % | – | 11 / 38 % | 9 / 23 % | 7 / 19 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 12 / 29 % | 0 / 0 % | – | 0 / 0 % | 8 / 25 % | 9 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 34 % | 6 / 49 % | – | 0 / 0 % | 10 / 28 % | 12 / 28 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 9 / 92 % | – | 7 / 18 % | 11 / 31 % | 8 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 22 % | 1 / 61 % | – | 10 / 32 % | 11 / 27 % | 5 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 30 % | 10 / 23 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 8 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 23 % | 6 / 16 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 7 / 19 % | 7 / 19 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 5 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 5 / 11 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 5 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 4 % | 6 / 17 % | 6 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 3 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 5 / 9 % |
