[English](README.md) · [Deutsch](README.de.md)

# Building safeguards for Claude

Report Q002194 · Source anthropic.com · Date 2025-08-12 · [Open original](https://www.anthropic.com/news/building-safeguards-for-claude)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic beschreibt ein Schutzkonzept für Claude aus Richtlinienarbeit, Training, Vorabtests, Echtzeit-Erkennung und fortlaufender Analyse möglicher Missbrauchsmuster. Der Bericht nennt Beispiele für daraus abgeleitete Maßnahmen, enthält aber keine Erfolgsquoten oder unabhängige Gesamtbewertung ihrer Wirksamkeit.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 55 / 71 % | 94 / 99 % | – | 100 / 100 % | 85 / 91 % | 84 / 91 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 59 % | 92 / 97 % | – | 99 / 100 % | 68 / 86 % | 78 / 88 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 24 / 47 % | 88 / 95 % | – | 97 / 99 % | 46 / 68 % | 59 / 74 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 49 / 67 % | 53 / 84 % | – | 95 / 99 % | 73 / 87 % | 47 / 64 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 39 / 63 % | 85 / 95 % | – | 94 / 99 % | 44 / 66 % | 61 / 77 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 51 % | 93 / 100 % | – | 94 / 99 % | 67 / 85 % | 64 / 82 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 16 / 39 % | 80 / 98 % | – | 92 / 97 % | 52 / 72 % | 44 / 61 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 24 / 49 % | 72 / 98 % | – | 91 / 96 % | 71 / 86 % | 77 / 89 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 25 / 47 % | 90 / 95 % | – | 84 / 92 % | 66 / 83 % | 59 / 70 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 31 / 53 % | 81 / 93 % | – | 83 / 90 % | 67 / 82 % | 52 / 67 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 25 / 47 % | 45 / 84 % | – | 80 / 87 % | 40 / 64 % | 16 / 31 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 26 / 48 % | 66 / 93 % | – | 59 / 77 % | 65 / 81 % | 78 / 86 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 16 / 40 % | 69 / 98 % | – | 46 / 89 % | 40 / 68 % | 30 / 59 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 19 / 36 % | 45 / 86 % | – | 69 / 90 % | 28 / 52 % | 33 / 54 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 28 / 59 % | – | 69 / 85 % | 9 / 28 % | 9 / 18 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 22 / 37 % | 54 / 86 % | – | 59 / 77 % | 29 / 55 % | 28 / 49 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 59 / 87 % | – | 6 / 22 % | 13 / 33 % | 10 / 22 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 11 / 25 % | 0 / 0 % | – | 57 / 85 % | 12 / 33 % | 11 / 26 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 41 / 87 % | – | 50 / 77 % | 22 / 52 % | 20 / 47 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 26 % | 47 / 81 % | – | 12 / 30 % | 9 / 25 % | 10 / 22 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 39 / 97 % | – | 44 / 68 % | 18 / 47 % | 22 / 49 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 44 / 88 % | – | 41 / 77 % | 19 / 45 % | 23 / 42 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 43 / 65 % | 9 / 15 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 16 / 75 % | – | 40 / 71 % | 34 / 60 % | 11 / 25 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 15 / 44 % | 0 / 0 % | – | 0 / 0 % | 38 / 63 % | 23 / 47 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 10 / 75 % | – | 30 / 60 % | 12 / 37 % | 11 / 21 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 29 / 79 % | – | 0 / 7 % | 6 / 15 % | 6 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 10 / 26 % | 11 / 83 % | – | 4 / 26 % | 26 / 51 % | 11 / 33 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 15 / 37 % | 0 / 0 % | – | 0 / 0 % | 13 / 34 % | 25 / 56 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 16 / 56 % | – | 17 / 42 % | 10 / 27 % | 15 / 38 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 24 % | 17 / 90 % | – | 10 / 29 % | 12 / 31 % | 10 / 23 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 5 / 19 % | 12 / 28 % | 17 / 32 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 25 % | 6 / 67 % | – | 16 / 35 % | 7 / 20 % | 8 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 21 % | 0 / 7 % | – | 0 / 0 % | 8 / 22 % | 12 / 26 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 8 / 63 % | – | 11 / 39 % | 11 / 28 % | 11 / 23 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 10 / 22 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 1 / 15 % | 8 / 20 % | 9 / 22 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 19 % | 6 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 16 % | 7 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 1 / 10 % | 0 / 0 % | 7 / 16 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 6 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 5 / 11 % |
