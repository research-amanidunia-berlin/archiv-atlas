[English](README.md) · [Deutsch](README.de.md)

# Open vs. closed AI: How behind are open models?

Report Q005049 · Source epoch.ai · Date 2024-11-04 · [Open original](https://epoch.ai/publications/open-models-report)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Quelltext enthält den Hauptteil des Berichts, aber nicht die Anhänge vollständig. Epoch AI schätzt, dass offene Modelle den besten geschlossenen bei Benchmarks meist fünf bis 22 Monate und beim Trainingsrechenaufwand etwa 15 Monate hinterherlagen; insgesamt liege der Rückstand bei ungefähr einem Jahr. Wie sich der Abstand entwickelt, ist ungewiss: Die größten offenen Modelle hielten mit, die breitere Gruppe fiel zurück, und eine mögliche Annäherung durch Llama 4 ist an Bedingungen geknüpft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 38 / 62 % | 91 / 100 % | 32 / 80 % | 98 / 99 % | 42 / 70 % | 32 / 54 % | 11 / 29 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 19 / 45 % | 60 / 97 % | 7 / 21 % | 86 / 94 % | 28 / 60 % | 40 / 62 % | 13 / 36 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 42 / 66 % | 82 / 99 % | 52 / 90 % | 80 / 97 % | 61 / 81 % | 71 / 84 % | 25 / 46 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 22 / 91 % | 3 / 11 % | 77 / 89 % | 23 / 54 % | 10 / 22 % | 3 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 27 / 44 % | 36 / 81 % | 57 / 62 % | 26 / 45 % | 58 / 75 % | 72 / 80 % | 13 / 30 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 20 / 45 % | 65 / 97 % | 1 / 5 % | 55 / 71 % | 24 / 56 % | 19 / 36 % | 4 / 13 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 23 / 45 % | 21 / 96 % | 3 / 15 % | 60 / 82 % | 18 / 45 % | 21 / 41 % | 3 / 14 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 44 % | 48 / 87 % | 1 / 6 % | 59 / 76 % | 18 / 50 % | 17 / 38 % | 4 / 14 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 3 / 42 % | 3 / 18 % | 54 / 79 % | 9 / 34 % | 6 / 17 % | 2 / 9 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 48 / 90 % | 0 / 2 % | 31 / 56 % | 8 / 29 % | 5 / 10 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 31 / 54 % | 41 / 92 % | 7 / 20 % | 21 / 53 % | 45 / 70 % | 32 / 47 % | 7 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 42 / 83 % | 0 / 0 % | 42 / 64 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 27 / 78 % | 1 / 7 % | 40 / 69 % | 15 / 42 % | 0 / 0 % | 2 / 9 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 39 / 81 % | 1 / 5 % | 36 / 71 % | 8 / 29 % | 7 / 17 % | 2 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 16 / 42 % | 35 / 79 % | 2 / 9 % | 8 / 36 % | 22 / 53 % | 12 / 27 % | 4 / 15 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 35 / 96 % | 1 / 8 % | 19 / 52 % | 10 / 33 % | 7 / 16 % | 2 / 7 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 30 % | 25 / 65 % | 6 / 11 % | 31 / 53 % | 18 / 38 % | 16 / 28 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 22 / 77 % | 2 / 9 % | 29 / 51 % | 9 / 31 % | 13 / 31 % | 3 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 24 / 69 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 21 / 83 % | 1 / 5 % | 15 / 37 % | 9 / 27 % | 12 / 23 % | 4 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 13 / 86 % | 1 / 4 % | 17 / 47 % | 18 / 51 % | 9 / 25 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 18 / 72 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 13 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 13 / 38 % | 4 / 60 % | 1 / 7 % | 0 / 0 % | 10 / 33 % | 11 / 20 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 1 / 10 % | 0 / 0 % | 11 / 31 % | 9 / 18 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 7 % | 6 / 13 % | 10 / 19 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 10 / 19 % | 1 / 4 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 5 / 11 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 9 / 51 % | 0 / 0 % | 0 / 0 % | 7 / 25 % | 9 / 18 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 6 / 13 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 79 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 6 / 10 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 4 / 62 % | 0 / 0 % | 1 / 6 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 8 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 8 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 3 / 68 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
