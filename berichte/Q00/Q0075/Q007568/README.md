[English](README.md) · [Deutsch](README.de.md)

# Continuously hardening ChatGPT Atlas against prompt injection

Report Q007568 · Source openai.com · Date 2025-12-22 · [Open original](https://openai.com/index/hardening-atlas-against-prompt-injection/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, dass ein automatisierter, mit Reinforcement Learning trainierter Angreifer neue Prompt-Injection-Methoden für den Atlas-Browser-Agenten aufgedeckt habe. Ein daraufhin trainiertes Update sei ausgerollt worden und habe im gezeigten Beispiel eine manipulierte E-Mail erkannt. Prompt Injection bleibt laut OpenAI ein ungelöstes Risiko; begrenzter Zugriff, sorgfältige Bestätigungen und klare Aufgaben können es mindern, aber nicht beseitigen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 46 / 67 % | 99 / 100 % | – | 100 / 100 % | 74 / 86 % | 70 / 81 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 53 % | 72 / 96 % | – | 99 / 100 % | 62 / 80 % | 52 / 73 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 35 / 53 % | 96 / 100 % | – | 92 / 97 % | 56 / 76 % | 42 / 67 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 49 % | 60 / 94 % | – | 95 / 99 % | 52 / 75 % | 64 / 77 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 33 % | 68 / 93 % | – | 93 / 96 % | 19 / 42 % | 24 / 39 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 82 / 90 % | 13 / 32 % | 13 / 29 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 23 / 45 % | 9 / 73 % | – | 79 / 93 % | 30 / 55 % | 26 / 48 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 29 / 43 % | 61 / 89 % | – | 78 / 87 % | 22 / 42 % | 28 / 44 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 15 / 50 % | – | 71 / 90 % | 38 / 62 % | 16 / 30 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 51 / 80 % | – | 65 / 77 % | 45 / 70 % | 48 / 68 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 28 % | 56 / 95 % | – | 5 / 20 % | 22 / 45 % | 32 / 49 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 16 / 29 % | 38 / 72 % | – | 48 / 72 % | 17 / 43 % | 10 / 18 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 45 / 65 % | 7 / 15 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 32 / 78 % | – | 24 / 69 % | 17 / 44 % | 11 / 22 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 31 / 84 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 29 / 90 % | – | 7 / 43 % | 15 / 38 % | 11 / 24 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 8 / 64 % | – | 19 / 34 % | 27 / 52 % | 12 / 28 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 22 / 45 % | 7 / 18 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 22 / 41 % | 12 / 31 % | 6 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 14 / 37 % | 18 / 47 % | 9 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 17 / 38 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 71 % | – | 17 / 31 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 36 % | 0 / 0 % | – | 3 / 18 % | 7 / 17 % | 10 / 18 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 29 % | 0 / 0 % | – | 0 / 0 % | 9 / 27 % | 10 / 19 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 14 / 36 % | 7 / 14 % | 5 / 9 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 13 / 45 % | – | 0 / 0 % | 0 / 0 % | 4 / 6 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 35 % | 6 / 10 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 26 % | 10 / 47 % | – | 1 / 14 % | 9 / 24 % | 5 / 12 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 11 / 31 % | 5 / 12 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 9 / 35 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 8 / 16 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 47 % | – | 0 / 0 % | 6 / 13 % | 7 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 9 % | 7 / 17 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 2 / 14 % | 6 / 12 % | 5 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 3 / 5 % |
