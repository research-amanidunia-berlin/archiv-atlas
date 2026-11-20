[English](README.md) · [Deutsch](README.de.md)

# GPT-4

Report Q005341 · Source openai.com · Date 2023-03-14 · [Open original](https://openai.com/index/gpt-4-research/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, GPT‑4 übertreffe GPT‑3.5 in vielen Prüfungen und könne neben Text auch Bilder verarbeiten; die Bildfunktion war zunächst nur als Forschungsvorschau verfügbar. Zugleich könne das Modell falsche oder verzerrte Antworten geben, Sicherheitsgrenzen umgehen und bei schwierigen Aufgaben scheitern, weshalb der Bericht bei folgenreichen Anwendungen zusätzliche Prüfung empfiehlt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 45 / 63 % | 98 / 99 % | – | 100 / 100 % | 73 / 86 % | 12 / 33 % | 61 / 79 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 61 % | 96 / 99 % | – | 99 / 100 % | 57 / 79 % | 24 / 47 % | 63 / 80 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 31 / 55 % | 97 / 99 % | – | 95 / 98 % | 63 / 80 % | 10 / 27 % | 37 / 66 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 33 / 59 % | 77 / 95 % | – | 95 / 97 % | 69 / 86 % | 12 / 30 % | 57 / 77 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 47 % | 81 / 97 % | – | 95 / 97 % | 27 / 55 % | 5 / 16 % | 20 / 37 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 55 / 85 % | – | 93 / 97 % | 12 / 36 % | 1 / 9 % | 9 / 19 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 18 / 42 % | 83 / 99 % | – | 92 / 98 % | 31 / 61 % | 6 / 21 % | 18 / 36 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 36 / 61 % | 71 / 96 % | – | 92 / 97 % | 28 / 52 % | 10 / 27 % | 44 / 65 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 30 / 92 % | – | 90 / 95 % | 34 / 60 % | 4 / 15 % | 8 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 15 / 33 % | 60 / 89 % | – | 86 / 92 % | 25 / 51 % | 2 / 14 % | 13 / 35 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 27 / 56 % | 85 / 98 % | – | 76 / 89 % | 42 / 69 % | 13 / 28 % | 31 / 49 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 27 / 53 % | 82 / 92 % | – | 72 / 85 % | 40 / 61 % | 4 / 14 % | 25 / 38 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 18 / 41 % | 38 / 93 % | – | 80 / 88 % | 9 / 27 % | 2 / 11 % | 9 / 20 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 20 / 36 % | 70 / 87 % | – | 77 / 84 % | 35 / 58 % | 3 / 10 % | 18 / 31 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 68 / 88 % | – | 6 / 15 % | 6 / 13 % | 0 / 0 % | 6 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 41 % | 62 / 86 % | – | 37 / 66 % | 19 / 50 % | 4 / 14 % | 13 / 30 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 55 / 92 % | – | 31 / 65 % | 26 / 50 % | 4 / 15 % | 10 / 22 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 15 / 41 % | 49 / 84 % | – | 31 / 68 % | 21 / 52 % | 4 / 16 % | 14 / 36 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 49 / 83 % | – | 47 / 57 % | 15 / 38 % | 2 / 11 % | 7 / 17 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 33 / 66 % | – | 42 / 71 % | 32 / 59 % | 5 / 16 % | 19 / 36 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 19 / 42 % | 40 / 87 % | – | 31 / 53 % | 13 / 39 % | 5 / 13 % | 16 / 32 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 37 % | 35 / 78 % | – | 19 / 39 % | 14 / 37 % | 5 / 17 % | 14 / 30 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 35 / 65 % | 7 / 23 % | 3 / 12 % | 5 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 23 / 85 % | – | 3 / 17 % | 6 / 17 % | 1 / 8 % | 4 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 23 / 56 % | – | 0 / 0 % | 10 / 24 % | 2 / 7 % | 7 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 21 / 44 % | 11 / 32 % | 0 / 0 % | 9 / 23 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 64 % | – | 0 / 0 % | 8 / 23 % | 0 / 0 % | 7 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 47 % | 0 / 0 % | – | 0 / 0 % | 13 / 42 % | 7 / 19 % | 16 / 35 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 13 / 45 % | 0 / 0 % | – | 0 / 0 % | 17 / 43 % | 3 / 10 % | 8 / 20 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 14 / 24 % | 0 / 0 % | – | 0 / 0 % | 10 / 27 % | 0 / 0 % | 6 / 20 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 12 / 31 % | 7 / 19 % | 2 / 8 % | 8 / 17 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 12 / 78 % | – | 8 / 31 % | 7 / 16 % | 1 / 8 % | 6 / 17 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 15 % | 1 / 5 % | 7 / 16 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % | 7 / 16 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 0 / 0 % | 5 / 13 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 1 / 5 % | 5 / 11 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 2 % | 6 / 11 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 18 % | 0 / 0 % | 5 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
