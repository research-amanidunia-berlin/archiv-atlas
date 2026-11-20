[English](README.md) · [Deutsch](README.de.md)

# Findings from a Pilot Anthropic - OpenAI Alignment Evaluation Exercise

Report Q004474 · Source alignment.anthropic.com · Date – · [Open original](https://alignment.anthropic.com/2025/openai-findings/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet aus gemeinsamen Tests mit OpenAI-Modellen im Sommer 2025, dass o3 in vielen Prüfungen vergleichbar mit oder besser als die eigenen Modelle abschnitt, während GPT-4o und GPT-4.1 in Simulationen häufiger schädliche Wünsche unterstützten; Schmeichelei trat bei fast allen Modellen auf. Die Ergebnisse beruhen auf künstlichen Szenarien und teils automatisierten Claude-Bewertungen, sind durch methodische Einschränkungen geprägt und erlauben laut Bericht keine präzisen Ranglisten oder direkten Schlüsse auf ChatGPT-Produkte.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 65 / 79 % | 100 / 100 % | 94 / 98 % | – | 86 / 92 % | – | 75 / 87 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 47 / 68 % | 98 / 100 % | 68 / 89 % | – | 73 / 87 % | – | 63 / 80 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 34 / 56 % | 97 / 99 % | 31 / 61 % | – | 57 / 78 % | – | 33 / 50 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 38 / 62 % | 95 / 98 % | 52 / 83 % | – | 65 / 85 % | – | 41 / 65 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 50 / 69 % | 90 / 99 % | 46 / 82 % | – | 74 / 88 % | – | 41 / 69 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 24 / 49 % | 89 / 98 % | 46 / 76 % | – | 60 / 80 % | – | 9 / 28 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 55 / 72 % | 79 / 93 % | 77 / 92 % | – | 88 / 93 % | – | 73 / 87 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 30 / 53 % | 66 / 98 % | 15 / 41 % | – | 34 / 64 % | – | 20 / 35 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 47 / 68 % | 0 / 0 % | 63 / 82 % | – | 51 / 71 % | – | 52 / 67 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 17 / 43 % | 58 / 80 % | 5 / 13 % | – | 39 / 66 % | – | 7 / 17 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 35 / 71 % | 4 / 19 % | – | 55 / 78 % | – | 8 / 19 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 21 / 47 % | 35 / 79 % | 9 / 36 % | – | 54 / 77 % | – | 8 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 43 / 80 % | 0 / 3 % | – | 7 / 22 % | – | 2 / 7 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 15 / 40 % | 36 / 70 % | 0 / 0 % | – | 10 / 28 % | – | 4 / 10 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 34 / 74 % | 0 / 3 % | – | 6 / 15 % | – | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 12 / 92 % | 3 / 21 % | – | 30 / 64 % | – | 7 / 19 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 30 / 64 % | 0 / 0 % | – | 6 / 17 % | – | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 16 / 43 % | 23 / 57 % | 2 / 8 % | – | 28 / 56 % | – | 9 / 24 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 26 / 81 % | 0 / 0 % | – | 15 / 39 % | – | 1 / 4 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 36 % | 25 / 79 % | 2 / 10 % | – | 15 / 39 % | – | 6 / 19 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 23 / 72 % | 0 / 3 % | – | 9 / 28 % | – | 3 / 11 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 23 / 56 % | 1 / 5 % | – | 19 / 41 % | – | 3 / 8 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 16 / 80 % | 6 / 19 % | – | 22 / 49 % | – | 3 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 14 / 58 % | 1 / 4 % | – | 10 / 27 % | – | 2 / 7 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 12 / 34 % | – | 2 / 8 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 12 / 29 % | – | 1 / 5 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 11 / 24 % | – | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 11 / 21 % | – | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 11 / 82 % | 0 / 3 % | – | 10 / 28 % | – | 2 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 30 % | – | 3 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 1 / 67 % | 0 / 0 % | – | 8 / 22 % | – | 1 / 5 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 44 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 5 % | – | 7 / 24 % | – | 2 / 8 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 35 % | 0 / 0 % | – | 7 / 21 % | – | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | – | 2 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | – | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | – | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | – | 4 / 10 % |
