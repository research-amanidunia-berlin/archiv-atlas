[English](README.md) · [Deutsch](README.de.md)

# Best practices for deploying language models

Report Q009029 · Source openai.com · Date 2022-06-02 · [Open original](https://openai.com/index/best-practices-for-deploying-language-models/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Drei Unternehmen empfehlen, Sprachmodelle durch klare Nutzungsregeln, technische Schutzmaßnahmen, Modellprüfungen und die Dokumentation bekannter Schwächen sicherer einzusetzen. Sie werben außerdem für vielfältige Teams, den Austausch von Erkenntnissen und faire Arbeitsbedingungen; die Empfehlungen sind vorläufig, sollen weiterentwickelt werden und werden im Bericht nicht durch Wirksamkeitsmessungen belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 60 / 73 % | 100 / 100 % | – | 100 / 100 % | 86 / 92 % | 80 / 88 % | 75 / 88 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 29 / 50 % | 88 / 96 % | – | 61 / 80 % | 53 / 72 % | 41 / 61 % | 41 / 63 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 20 / 45 % | 68 / 94 % | – | 87 / 93 % | 41 / 66 % | 17 / 42 % | 10 / 29 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 15 / 40 % | 77 / 91 % | – | 59 / 82 % | 29 / 56 % | 16 / 38 % | 9 / 27 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 21 / 43 % | 76 / 98 % | – | 62 / 91 % | 27 / 61 % | 29 / 62 % | 23 / 51 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 36 % | 11 / 58 % | – | 74 / 92 % | 15 / 42 % | 10 / 36 % | 4 / 17 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 26 / 63 % | – | 70 / 82 % | 23 / 58 % | 17 / 49 % | 6 / 21 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 17 / 40 % | 51 / 89 % | – | 61 / 86 % | 34 / 63 % | 16 / 40 % | 8 / 26 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 34 % | 61 / 89 % | – | 50 / 83 % | 18 / 45 % | 13 / 50 % | 8 / 27 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 33 % | 59 / 91 % | – | 4 / 29 % | 12 / 35 % | 10 / 29 % | 4 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 12 / 28 % | 54 / 88 % | – | 21 / 46 % | 15 / 47 % | 15 / 41 % | 5 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 43 / 81 % | – | 51 / 77 % | 7 / 23 % | 7 / 19 % | 1 / 8 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 16 / 45 % | 23 / 80 % | – | 50 / 84 % | 17 / 52 % | 11 / 42 % | 3 / 19 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 42 / 73 % | – | 31 / 61 % | 10 / 30 % | 8 / 22 % | 4 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 36 % | 40 / 91 % | – | 41 / 70 % | 9 / 29 % | 7 / 25 % | 3 / 15 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 8 / 35 % | 37 / 71 % | – | 9 / 35 % | 5 / 15 % | 5 / 11 % | 0 / 4 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 13 / 34 % | 35 / 69 % | – | 11 / 45 % | 10 / 27 % | 7 / 20 % | 3 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 10 / 24 % | 34 / 68 % | – | 5 / 20 % | 7 / 24 % | 6 / 15 % | 2 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 7 / 33 % | 29 / 75 % | – | 34 / 78 % | 17 / 50 % | 10 / 36 % | 9 / 29 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 6 / 30 % | 28 / 82 % | – | 21 / 71 % | 9 / 32 % | 7 / 23 % | 1 / 10 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 28 / 73 % | – | 0 / 0 % | 6 / 16 % | 5 / 11 % | 1 / 5 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 10 / 28 % | 26 / 82 % | – | 10 / 45 % | 14 / 33 % | 11 / 28 % | 2 / 12 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 24 / 68 % | – | 8 / 36 % | 8 / 25 % | 4 / 12 % | 2 / 6 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 6 / 29 % | 24 / 82 % | – | 4 / 24 % | 7 / 24 % | 5 / 16 % | 1 / 9 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 9 / 38 % | 24 / 52 % | – | 11 / 34 % | 9 / 31 % | 6 / 18 % | 2 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 22 / 55 % | – | 1 / 9 % | 6 / 14 % | 6 / 16 % | 2 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 19 / 83 % | – | 0 / 12 % | 6 / 16 % | 5 / 9 % | 1 / 8 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 17 / 31 % | 0 / 0 % | – | 17 / 53 % | 13 / 43 % | 10 / 34 % | 3 / 11 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 17 / 50 % | – | 1 / 15 % | 10 / 24 % | 6 / 11 % | 4 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 12 / 39 % | 14 / 47 % | – | 7 / 29 % | 11 / 32 % | 8 / 27 % | 3 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 14 / 46 % | – | 0 / 0 % | 6 / 19 % | 6 / 18 % | 0 / 3 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 12 / 28 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 8 / 21 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 27 % | 4 / 28 % | – | 0 / 1 % | 6 / 18 % | 6 / 17 % | 1 / 7 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 1 / 13 % | 6 / 19 % | 3 / 10 % | 1 / 5 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 8 % | 6 / 15 % | 4 / 11 % | 1 / 4 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 6 / 27 % | 0 / 0 % | – | 0 / 6 % | 6 / 14 % | 5 / 12 % | 1 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 6 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 2 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 5 / 19 % | 1 / 5 % |
