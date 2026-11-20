[English](README.md) · [Deutsch](README.de.md)

# Introducing upgrades to Codex

Report Q006797 · Source openai.com · Date 2025-09-15 · [Open original](https://openai.com/index/introducing-upgrades-to-codex/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI stellt GPT‑5‑Codex als Programmiermodell für Codex vor und berichtet über Verbesserungen bei langen Entwicklungsaufgaben, Code-Reviews und Cloud-Leistung; die Leistungswerte stammen aus unternehmenseigenen Tests. CLI, IDE-, Cloud- und GitHub-Funktionen werden erweitert, während OpenAI trotz Sandbox und Schutzvorkehrungen empfiehlt, Ergebnisse zu prüfen und menschliche Reviews fortzuführen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 58 / 73 % | 99 / 100 % | – | 100 / 100 % | 83 / 90 % | 81 / 88 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 51 % | 93 / 99 % | – | 97 / 98 % | 64 / 82 % | 58 / 74 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 26 / 41 % | 87 / 92 % | – | 93 / 95 % | 54 / 73 % | 52 / 63 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 65 / 92 % | – | 93 / 96 % | 10 / 28 % | 9 / 18 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 49 / 85 % | – | 87 / 91 % | 14 / 42 % | 21 / 38 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 40 % | 78 / 94 % | – | 16 / 33 % | 17 / 44 % | 21 / 38 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 21 / 69 % | – | 78 / 90 % | 12 / 35 % | 12 / 21 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 41 % | 0 / 0 % | – | 77 / 82 % | 26 / 56 % | 46 / 65 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 76 / 87 % | 7 / 19 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 16 / 34 % | 0 / 0 % | – | 68 / 75 % | 9 / 27 % | 15 / 29 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 39 / 58 % | 67 / 96 % | – | 30 / 49 % | 54 / 75 % | 65 / 77 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 46 / 94 % | – | 56 / 72 % | 14 / 43 % | 9 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 54 / 68 % | 20 / 46 % | 7 / 13 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 19 / 37 % | 51 / 79 % | – | 27 / 58 % | 12 / 28 % | 22 / 37 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 22 / 56 % | – | 49 / 61 % | 13 / 31 % | 17 / 27 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 43 / 91 % | – | 0 / 0 % | 13 / 36 % | 11 / 26 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 19 / 30 % | 16 / 51 % | – | 39 / 64 % | 25 / 50 % | 19 / 31 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 25 / 82 % | – | 38 / 55 % | 8 / 21 % | 5 / 10 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 35 / 89 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 29 / 62 % | – | 0 / 0 % | 8 / 20 % | 5 / 9 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 20 / 65 % | – | 16 / 31 % | 17 / 40 % | 10 / 20 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 35 % | 3 / 6 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 30 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 22 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 9 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 9 / 74 % | – | 0 / 0 % | 6 / 14 % | 2 / 4 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 26 % | 5 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 20 % | 5 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 7 / 13 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 4 / 43 % | – | 0 / 0 % | 0 / 0 % | 7 / 13 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 6 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 4 / 7 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 5 / 8 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 6 / 11 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 7 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
