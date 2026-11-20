[English](README.md) · [Deutsch](README.de.md)

# Introducing ChatGPT

Report Q008742 · Source openai.com · Date 2022-11-30 · [Open original](https://openai.com/index/chatgpt/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI stellte ChatGPT 2022 als dialogfähiges Modell vor, das mit menschlich erstellten Beispielen und Bewertungen sowie RLHF trainiert worden sei. Der Bericht nennt als Grenzen unter anderem falsche Antworten, schwankende Reaktionen auf Umformulierungen, übermäßige Ausführlichkeit und mögliche schädliche oder voreingenommene Ausgaben. Die Wirksamkeit der Verbesserungen und die beschriebenen Fähigkeiten werden im Text von OpenAI dargestellt, nicht unabhängig geprüft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 97 / 100 % | – | 96 / 99 % | 30 / 62 % | 6 / 21 % | 13 / 31 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 54 % | 74 / 99 % | – | 92 / 98 % | 47 / 73 % | 6 / 23 % | 34 / 62 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 46 / 85 % | – | 88 / 95 % | 27 / 59 % | 4 / 14 % | 22 / 48 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 61 / 97 % | – | 83 / 92 % | 32 / 62 % | 3 / 15 % | 18 / 48 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 37 / 69 % | – | 77 / 93 % | 8 / 29 % | 1 / 8 % | 5 / 11 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 24 / 48 % | 17 / 48 % | – | 72 / 85 % | 18 / 52 % | 5 / 15 % | 14 / 43 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 21 / 37 % | 60 / 85 % | – | 56 / 79 % | 21 / 45 % | 4 / 14 % | 15 / 30 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 37 / 89 % | – | 55 / 73 % | 11 / 32 % | 3 / 12 % | 10 / 22 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 43 / 71 % | – | 18 / 33 % | 15 / 42 % | 0 / 0 % | 12 / 26 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 36 % | 37 / 91 % | – | 27 / 59 % | 7 / 27 % | 0 / 0 % | 8 / 17 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 26 / 73 % | – | 35 / 59 % | 12 / 34 % | 3 / 11 % | 10 / 22 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 20 / 52 % | – | 27 / 60 % | 8 / 24 % | 1 / 4 % | 5 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 24 / 40 % | 6 / 17 % | 2 / 11 % | 6 / 12 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 24 / 61 % | – | 17 / 55 % | 23 / 46 % | 2 / 8 % | 7 / 15 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 31 % | 24 / 77 % | – | 2 / 17 % | 9 / 28 % | 3 / 13 % | 9 / 23 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 23 / 79 % | – | 12 / 42 % | 8 / 27 % | 1 / 5 % | 7 / 15 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 22 / 63 % | – | 0 / 0 % | 6 / 19 % | 1 / 8 % | 4 / 9 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 82 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 9 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 19 / 44 % | – | 10 / 36 % | 9 / 24 % | 1 / 8 % | 6 / 12 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 19 / 77 % | – | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 17 / 77 % | – | 7 / 32 % | 8 / 21 % | 1 / 7 % | 8 / 18 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 16 / 48 % | – | 0 / 0 % | 7 / 18 % | 1 / 4 % | 6 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 13 / 86 % | – | 14 / 33 % | 6 / 17 % | 1 / 7 % | 5 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 12 / 35 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 0 / 3 % | 9 / 19 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 8 / 46 % | – | 3 / 22 % | 11 / 38 % | 1 / 5 % | 7 / 15 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 34 % | 1 / 6 % | 10 / 24 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 8 / 59 % | – | 6 / 33 % | 8 / 28 % | 1 / 5 % | 5 / 12 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 8 / 33 % | 6 / 17 % | 1 / 7 % | 4 / 10 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 1 / 4 % | 7 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 7 / 63 % | – | 1 / 8 % | 5 / 15 % | 1 / 6 % | 3 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 6 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 23 % | 0 / 3 % | 4 / 8 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 2 % | 3 / 6 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 2 % | 3 / 6 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 1 / 4 % | 5 / 8 % |
