[English](README.md) · [Deutsch](README.de.md)

# Mapping the misuse of generative AI

Report Q002918 · Source deepmind.google · Date 2024-08-02 · [Open original](https://deepmind.google/blog/mapping-the-misuse-of-generative-ai/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Eine Untersuchung von knapp 200 Medienberichten aus Januar 2023 bis März 2024 ordnet KI-Missbrauch in die Ausnutzung von KI-Fähigkeiten und die Kompromittierung von Systemen ein; in dieser Auswahl überwogen Identitätsnachahmung, Betrug und andere Nutzungen frei zugänglicher Werkzeuge. Die Forschenden nennen Meinungsbeeinflussung und finanziellen Gewinn als häufige Ziele, betonen aber, dass die Medienauswahl keine repräsentative Gesamtschau ist und traditionelle Manipulation nicht direkt verglichen wurde.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 52 / 68 % | 96 / 100 % | 95 / 99 % | 78 / 88 % | 67 / 81 % | 80 / 88 % | 88 / 95 % | 61 / 84 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 47 % | 68 / 98 % | 95 / 99 % | 37 / 66 % | 11 / 31 % | 40 / 67 % | 13 / 47 % | 27 / 53 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 63 / 94 % | 77 / 89 % | 19 / 43 % | 11 / 29 % | 29 / 54 % | 5 / 14 % | 21 / 45 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 38 / 97 % | 70 / 93 % | 24 / 55 % | 8 / 26 % | 15 / 38 % | 14 / 39 % | 33 / 62 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 31 % | 4 / 71 % | 62 / 88 % | 15 / 44 % | 5 / 19 % | 9 / 34 % | 2 / 19 % | 8 / 33 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 45 % | 12 / 87 % | 51 / 71 % | 17 / 49 % | 11 / 30 % | 25 / 56 % | 4 / 15 % | 10 / 25 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 32 / 52 % | 6 / 36 % | 45 / 57 % | 27 / 51 % | 25 / 41 % | 11 / 21 % | 0 / 0 % | 21 / 41 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 15 / 65 % | 41 / 74 % | 11 / 35 % | 4 / 13 % | 8 / 22 % | 1 / 8 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 14 / 30 % | 35 / 96 % | 37 / 75 % | 10 / 31 % | 5 / 21 % | 11 / 45 % | 2 / 11 % | 12 / 35 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 36 / 55 % | 7 / 36 % | 8 / 21 % | 25 / 52 % | 14 / 29 % | 15 / 28 % | 6 / 14 % | 11 / 30 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 2 / 49 % | 34 / 65 % | 11 / 35 % | 0 / 0 % | 8 / 25 % | 0 / 4 % | 10 / 25 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 12 / 35 % | 22 / 74 % | 31 / 70 % | 14 / 39 % | 8 / 22 % | 17 / 40 % | 6 / 20 % | 17 / 47 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 30 / 78 % | 9 / 36 % | 12 / 35 % | 4 / 15 % | 12 / 27 % | 2 / 10 % | 6 / 22 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 26 / 70 % | 28 / 72 % | 13 / 44 % | 3 / 14 % | 8 / 38 % | 1 / 13 % | 8 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 8 / 87 % | 12 / 55 % | 8 / 25 % | 5 / 14 % | 8 / 15 % | 1 / 8 % | 26 / 52 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 26 % | 1 / 6 % | 6 / 20 % | 1 / 9 % | 5 / 16 % | 1 / 9 % | 26 / 51 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 11 / 30 % | 4 / 91 % | 23 / 47 % | 6 / 21 % | 3 / 12 % | 6 / 17 % | 0 / 2 % | 13 / 33 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 5 / 72 % | 23 / 52 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 22 / 72 % | 4 / 25 % | 11 / 33 % | 3 / 14 % | 8 / 22 % | 0 / 4 % | 8 / 30 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 19 / 72 % | 1 / 14 % | 6 / 16 % | 3 / 13 % | 6 / 18 % | 0 / 5 % | 17 / 43 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 1 / 28 % | 18 / 46 % | 9 / 29 % | 3 / 11 % | 6 / 15 % | 1 / 6 % | 6 / 23 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 29 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 3 / 74 % | 14 / 55 % | 8 / 24 % | 2 / 10 % | 4 / 18 % | 0 / 4 % | 9 / 33 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 0 / 0 % | 14 / 30 % | 1 / 5 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 4 % | 5 / 13 % | 0 / 1 % | 11 / 29 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 9 / 63 % | 1 / 15 % | 8 / 25 % | 3 / 10 % | 6 / 17 % | 1 / 9 % | 6 / 24 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 1 / 42 % | 0 / 0 % | 7 / 23 % | 1 / 9 % | 8 / 22 % | 1 / 5 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 6 / 58 % | 3 / 20 % | 7 / 18 % | 2 / 9 % | 7 / 17 % | 1 / 5 % | 8 / 28 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 29 % | 2 / 10 % | 6 / 18 % | 1 / 6 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 7 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 7 / 52 % | 1 / 13 % | 6 / 18 % | 3 / 11 % | 7 / 21 % | 0 / 4 % | 6 / 25 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 71 % | 1 / 21 % | 7 / 23 % | 2 / 11 % | 6 / 21 % | 0 / 7 % | 4 / 21 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 2 / 7 % | 6 / 10 % | 0 / 2 % | 5 / 23 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 5 / 12 % | 1 / 7 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 7 % | 4 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | 0 / 0 % |
