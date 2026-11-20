[English](README.md) · [Deutsch](README.de.md)

# Introducing OpenAI o3 and o4-mini

Report Q006570 · Source openai.com · Date 2025-04-16 · [Open original](https://openai.com/index/introducing-o3-and-o4-mini/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt o3 und o4-mini als im April 2025 eingeführte Reasoning-Modelle vor, die laut OpenAI Werkzeuge wie Websuche, Python und Bildanalyse eigenständig kombinieren konnten. OpenAI berichtet von starken Benchmark- und Sicherheitsergebnissen, schränkt deren Aussagekraft jedoch unter anderem durch Werkzeugzugriff und konkrete Testbedingungen ein. Die damaligen Zugangsinformationen sind überholt: Der Bericht sagt, beide Modelle seien inzwischen aus ChatGPT entfernt und in der API abgekündigt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 52 % | 69 / 92 % | – | 98 / 99 % | 45 / 74 % | 10 / 26 % | 65 / 81 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 18 / 41 % | 71 / 86 % | – | 93 / 97 % | 46 / 72 % | 5 / 14 % | 39 / 57 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 25 / 45 % | 72 / 91 % | – | 93 / 98 % | 62 / 80 % | 7 / 20 % | 42 / 63 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 49 % | 13 / 79 % | – | 92 / 95 % | 54 / 78 % | 6 / 18 % | 52 / 74 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 44 % | 0 / 0 % | – | 85 / 90 % | 22 / 48 % | 3 / 9 % | 24 / 43 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 31 / 51 % | 57 / 78 % | – | 80 / 92 % | 34 / 63 % | 7 / 22 % | 52 / 71 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 20 / 40 % | 12 / 48 % | – | 77 / 84 % | 37 / 68 % | 6 / 17 % | 30 / 62 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 70 / 83 % | – | 25 / 37 % | 37 / 57 % | 3 / 8 % | 12 / 22 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 26 / 62 % | – | 69 / 85 % | 9 / 30 % | 1 / 5 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 3 / 25 % | – | 68 / 84 % | 7 / 20 % | 0 / 0 % | 5 / 10 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 64 / 76 % | 50 / 74 % | 4 / 13 % | 10 / 22 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 25 / 45 % | 36 / 83 % | – | 33 / 57 % | 52 / 76 % | 4 / 11 % | 36 / 59 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 23 / 45 % | 52 / 84 % | – | 21 / 42 % | 32 / 59 % | 1 / 6 % | 46 / 61 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 28 / 46 % | 0 / 0 % | – | 39 / 59 % | 42 / 68 % | 4 / 12 % | 23 / 40 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 20 / 45 % | 9 / 69 % | – | 40 / 54 % | 34 / 64 % | 3 / 12 % | 20 / 52 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 19 / 44 % | 0 / 0 % | – | 33 / 47 % | 14 / 34 % | 2 / 6 % | 17 / 27 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 28 % | – | 33 / 51 % | 6 / 20 % | 1 / 6 % | 8 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 30 / 49 % | 7 / 22 % | 1 / 6 % | 7 / 18 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 28 / 63 % | – | 0 / 0 % | 8 / 26 % | 1 / 3 % | 12 / 25 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 23 / 38 % | 11 / 32 % | 2 / 7 % | 5 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 27 % | 0 / 0 % | – | 8 / 24 % | 18 / 49 % | 2 / 7 % | 14 / 27 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 43 % | 0 / 0 % | – | 0 / 0 % | 12 / 40 % | 1 / 4 % | 14 / 36 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 47 % | 0 / 0 % | – | 0 / 0 % | 18 / 45 % | 1 / 5 % | 8 / 16 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 35 % | 0 / 0 % | – | 16 / 25 % | 11 / 30 % | 3 / 11 % | 17 / 34 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 10 / 27 % | 16 / 56 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 24 % | 0 / 0 % | – | 0 / 0 % | 6 / 18 % | 1 / 6 % | 5 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 1 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 0 / 2 % | 5 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 4 % | 4 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 1 / 5 % | 5 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 6 / 14 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 5 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 3 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 2 % | 5 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 14 % | 1 / 6 % | 0 / 0 % |
