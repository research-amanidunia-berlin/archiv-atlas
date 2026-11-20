[English](README.md) · [Deutsch](README.de.md)

# The Inspect Sandboxing Toolkit: Scalable and secure AI agent evaluations

Report Q001905 · Source aisi.gov.uk · Date 2025-08-07 · [Open original](https://www.aisi.gov.uk/blog/the-inspect-sandboxing-toolkit-scalable-and-secure-ai-agent-evaluations)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AISI stellt ein Inspect-Toolkit mit Docker-Compose-, Kubernetes- und Proxmox-Plugins vor, das KI-Agenten in anpassbar isolierten Umgebungen bewerten soll. Der Bericht beschreibt die Architektur und mögliche Risiken, liefert aber keine unabhängigen Wirksamkeitsmessungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 46 / 68 % | 95 / 99 % | – | 100 / 100 % | 79 / 89 % | 56 / 77 % | 78 / 87 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 54 % | 88 / 99 % | – | 99 / 100 % | 52 / 75 % | 34 / 62 % | 52 / 72 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 57 / 74 % | 61 / 97 % | – | 87 / 94 % | 67 / 84 % | 66 / 83 % | 74 / 85 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 46 / 69 % | 38 / 98 % | – | 84 / 97 % | 14 / 27 % | 68 / 83 % | 71 / 84 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 24 / 47 % | 79 / 91 % | – | 69 / 76 % | 36 / 56 % | 8 / 19 % | 31 / 46 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 58 % | 63 / 99 % | – | 53 / 84 % | 29 / 59 % | 30 / 52 % | 48 / 69 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 40 / 80 % | – | 52 / 77 % | 15 / 32 % | 2 / 5 % | 11 / 19 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 50 / 94 % | – | 37 / 67 % | 35 / 61 % | 26 / 52 % | 25 / 50 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 47 / 85 % | – | 0 / 0 % | 9 / 27 % | 0 / 3 % | 9 / 20 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 4 / 27 % | – | 0 / 0 % | 21 / 51 % | 8 / 22 % | 42 / 67 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 40 / 87 % | – | 0 / 0 % | 14 / 31 % | 2 / 6 % | 12 / 23 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 36 / 95 % | – | 8 / 45 % | 15 / 42 % | 8 / 22 % | 12 / 31 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 33 / 70 % | – | 14 / 35 % | 7 / 17 % | 1 / 5 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 28 / 85 % | – | 1 / 12 % | 7 / 17 % | 3 / 8 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 26 / 51 % | 12 / 86 % | – | 11 / 41 % | 17 / 45 % | 7 / 27 % | 22 / 49 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 6 / 62 % | – | 0 / 0 % | 25 / 50 % | 6 / 16 % | 9 / 22 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 32 % | 24 / 66 % | – | 0 / 0 % | 8 / 21 % | 1 / 6 % | 5 / 12 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 22 / 70 % | – | 14 / 56 % | 23 / 49 % | 9 / 24 % | 19 / 38 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 12 / 38 % | 23 / 52 % | – | 19 / 47 % | 18 / 42 % | 5 / 13 % | 9 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 22 / 59 % | – | 0 / 0 % | 8 / 17 % | 1 / 3 % | 5 / 10 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 22 / 50 % | 7 / 21 % | 2 / 7 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 20 / 45 % | 5 / 12 % | 0 / 3 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 17 / 36 % | 0 / 2 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 13 / 71 % | – | 0 / 0 % | 8 / 20 % | 3 / 9 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 10 / 78 % | – | 0 / 0 % | 9 / 26 % | 3 / 10 % | 12 / 24 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 10 / 55 % | – | 5 / 38 % | 12 / 30 % | 4 / 12 % | 6 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 24 % | 0 / 2 % | 5 / 10 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 7 % | 8 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 68 % | – | 0 / 0 % | 8 / 22 % | 2 / 7 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 5 % | 7 / 14 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 4 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 0 / 1 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 3 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 5 % | 6 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % |
