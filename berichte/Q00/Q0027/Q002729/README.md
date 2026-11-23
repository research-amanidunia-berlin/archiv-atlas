[English](README.md) · [Deutsch](README.de.md)

# Challenges in red teaming AI systems

Report Q002729 · Source anthropic.com · Date 2024-06-12 · [Open original](https://www.anthropic.com/news/challenges-in-red-teaming-ai-systems)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt ausgewählte Red-Teaming-Methoden von Anthropic – von fachgeleiteten und mehrsprachigen Tests bis zu automatisierten, multimodalen und gemeinschaftlichen Prüfungen – und plädiert für gemeinsame Standards. Er empfiehlt einen iterativen Übergang von qualitativen Tests zu automatisierten Auswertungen; vergleichende Wirksamkeitsdaten liefert der Text nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 24 / 54 % | 16 / 91 % | 93 / 97 % | 28 / 59 % | 13 / 33 % | 17 / 46 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 38 / 68 % | 85 / 99 % | 90 / 99 % | 47 / 72 % | 64 / 81 % | 75 / 86 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 56 % | 84 / 99 % | 89 / 99 % | 55 / 81 % | 52 / 75 % | 61 / 81 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 54 % | 54 / 95 % | 82 / 95 % | 46 / 75 % | 20 / 46 % | 38 / 70 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 21 / 52 % | 63 / 95 % | 81 / 91 % | 28 / 55 % | 10 / 26 % | 16 / 41 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 43 % | 54 / 97 % | 77 / 94 % | 54 / 78 % | 24 / 48 % | 54 / 76 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 13 / 44 % | 71 / 85 % | 36 / 76 % | 38 / 65 % | 11 / 24 % | 27 / 42 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 52 % | 65 / 98 % | 71 / 93 % | 40 / 67 % | 25 / 50 % | 35 / 58 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 29 / 56 % | 71 / 93 % | 44 / 69 % | 51 / 73 % | 36 / 53 % | 54 / 72 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 19 / 43 % | 66 / 90 % | 68 / 88 % | 23 / 49 % | 14 / 31 % | 27 / 49 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 31 % | 57 / 90 % | 20 / 39 % | 11 / 34 % | 4 / 15 % | 11 / 29 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 28 / 68 % | 56 / 80 % | 8 / 25 % | 3 / 10 % | 5 / 12 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 32 % | 55 / 92 % | 37 / 71 % | 16 / 42 % | 8 / 23 % | 9 / 36 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 24 / 53 % | 48 / 98 % | 31 / 69 % | 34 / 65 % | 16 / 34 % | 30 / 54 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 12 / 41 % | 45 / 98 % | 17 / 58 % | 28 / 60 % | 10 / 24 % | 22 / 54 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 15 / 87 % | 10 / 44 % | 44 / 71 % | 10 / 25 % | 10 / 26 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 25 / 52 % | 44 / 98 % | 36 / 80 % | 29 / 62 % | 13 / 36 % | 26 / 63 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 23 / 90 % | 30 / 56 % | 38 / 70 % | 19 / 42 % | 43 / 69 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 30 / 78 % | 6 / 41 % | 11 / 32 % | 4 / 12 % | 5 / 19 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 29 % | 17 / 96 % | 25 / 45 % | 7 / 23 % | 3 / 14 % | 7 / 16 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 20 / 88 % | 0 / 0 % | 9 / 28 % | 2 / 10 % | 8 / 20 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 19 / 54 % | 13 / 35 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 44 % | 3 / 63 % | 8 / 23 % | 12 / 43 % | 6 / 16 % | 18 / 42 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 17 / 52 % | 2 / 24 % | 6 / 21 % | 3 / 8 % | 9 / 21 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 14 / 85 % | 10 / 48 % | 7 / 21 % | 2 / 6 % | 7 / 18 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 14 / 52 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 30 % | 13 / 90 % | 0 / 5 % | 8 / 26 % | 4 / 13 % | 10 / 27 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 34 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 4 / 12 % | 8 / 19 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 12 / 68 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 5 / 11 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 10 / 60 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 6 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 9 / 77 % | 1 / 10 % | 6 / 21 % | 1 / 8 % | 4 / 13 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 28 % | 4 / 12 % | 5 / 14 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 9 / 24 % | 7 / 20 % | 2 / 8 % | 6 / 14 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 25 % | 1 / 6 % | 5 / 16 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 7 / 70 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 14 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 2 / 13 % | 5 / 14 % | 3 / 12 % | 5 / 12 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 10 % | 5 / 14 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 5 / 16 % | – | – |
