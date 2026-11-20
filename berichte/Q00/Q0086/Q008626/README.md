[English](README.md) · [Deutsch](README.de.md)

# Better language models and their implications

Report Q008626 · Source openai.com · Date 2019-02-14 · [Open original](https://openai.com/index/better-language-models/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, GPT‑2 könne aus großen Mengen Webtext kohärente Fortsetzungen erzeugen und einige Sprachaufgaben ohne spezielles Training bearbeiten, mache dabei aber weiterhin deutliche Fehler und liege bei spezialisierten Aufgaben zurück. Wegen möglicher Anwendungen für Desinformation und missbräuchliche Inhalte beschreibt der Bericht zunächst eine eingeschränkte, später eine gestufte Veröffentlichung; die tatsächlichen gesellschaftlichen Auswirkungen bleiben darin offen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 99 / 100 % | – | 98 / 99 % | 37 / 64 % | 26 / 43 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 64 / 79 % | 99 / 99 % | – | 99 / 100 % | 80 / 89 % | 73 / 81 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 49 % | 73 / 94 % | – | 94 / 98 % | 36 / 64 % | 45 / 65 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 48 % | 54 / 91 % | – | 93 / 96 % | 16 / 47 % | 37 / 62 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 49 / 73 % | – | 93 / 97 % | 7 / 19 % | 6 / 14 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 63 / 99 % | – | 91 / 96 % | 13 / 37 % | 14 / 30 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 87 / 96 % | – | 87 / 93 % | 33 / 59 % | 29 / 49 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 40 / 76 % | – | 85 / 92 % | 9 / 24 % | 6 / 14 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 14 / 33 % | 75 / 91 % | – | 85 / 94 % | 14 / 40 % | 19 / 47 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 27 / 76 % | – | 83 / 94 % | 17 / 45 % | 7 / 17 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 16 / 47 % | – | 82 / 88 % | 17 / 46 % | 26 / 45 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 28 / 50 % | 81 / 96 % | – | 66 / 90 % | 57 / 78 % | 59 / 77 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 42 / 73 % | – | 75 / 85 % | 8 / 24 % | 8 / 18 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 15 / 33 % | 68 / 91 % | – | 74 / 86 % | 19 / 43 % | 16 / 37 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 74 / 95 % | – | 1 / 16 % | 9 / 26 % | 11 / 26 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 26 % | 72 / 91 % | – | 47 / 75 % | 8 / 27 % | 11 / 24 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 70 / 95 % | – | 67 / 89 % | 17 / 48 % | 15 / 37 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 70 / 84 % | 12 / 37 % | 12 / 26 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 32 % | 5 / 42 % | – | 68 / 85 % | 17 / 45 % | 18 / 46 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 55 / 88 % | – | 0 / 0 % | 6 / 14 % | 6 / 14 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 33 % | 54 / 90 % | – | 20 / 48 % | 20 / 51 % | 22 / 37 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 45 / 80 % | – | 22 / 50 % | 12 / 31 % | 16 / 30 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 15 / 37 % | 44 / 81 % | – | 44 / 77 % | 15 / 39 % | 12 / 29 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 44 / 82 % | – | 16 / 59 % | 9 / 26 % | 7 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 41 / 93 % | – | 14 / 35 % | 23 / 45 % | 19 / 30 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 11 / 43 % | – | 40 / 61 % | 9 / 26 % | 7 / 21 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 31 / 61 % | – | 0 / 0 % | 7 / 17 % | 7 / 15 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 28 / 72 % | – | 0 / 0 % | 6 / 14 % | 11 / 21 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 24 / 63 % | – | 0 / 0 % | 12 / 34 % | 13 / 29 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 24 / 56 % | – | 0 / 0 % | 9 / 23 % | 6 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 23 / 52 % | – | 2 / 16 % | 8 / 22 % | 6 / 15 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 23 / 73 % | – | 2 / 13 % | 7 / 20 % | 7 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 39 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 16 / 65 % | – | 0 / 0 % | 6 / 16 % | 8 / 19 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 10 / 16 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 10 / 49 % | – | 0 / 0 % | 6 / 16 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 9 / 17 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 6 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 7 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 5 / 11 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 6 / 11 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % |
