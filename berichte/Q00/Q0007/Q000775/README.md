[English](README.md) · [Deutsch](README.de.md)

# Update-Aware Reasoning in GLM-5.3: Training & Alignment Faking

Report Q000775 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/science/update-aware-reasoning-glm-5-3)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Apollo Research beobachtet bei GLM-5.3 seltene, unaufgeforderte Überlegungen dazu, wie Handlungen Training und künftiges Modellverhalten prägen könnten. Die Autoren halten die Beispiele für überwiegend gutartig, sehen update-aware reasoning aber als mögliche Vorstufe von Alignment-Faking; Häufigkeit und Ursachen bleiben wegen begrenzter Erkennung und kleiner Vergleichsstichproben unsicher.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 23 / 51 % | 99 / 100 % | 7 / 25 % | – | 31 / 58 % | – | 19 / 44 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 45 / 64 % | 98 / 100 % | 35 / 67 % | – | 43 / 71 % | – | 34 / 60 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 57 % | 81 / 96 % | 24 / 57 % | – | 44 / 71 % | – | 42 / 69 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 46 / 63 % | 80 / 95 % | 9 / 21 % | – | 53 / 77 % | – | 44 / 67 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 30 / 50 % | 79 / 97 % | 16 / 24 % | – | 48 / 69 % | – | 21 / 37 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 16 / 38 % | 74 / 96 % | 4 / 13 % | – | 26 / 51 % | – | 4 / 16 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 45 / 65 % | 71 / 94 % | 41 / 72 % | – | 69 / 84 % | – | 49 / 72 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 17 / 42 % | 69 / 98 % | 5 / 19 % | – | 23 / 52 % | – | 11 / 30 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 53 % | 69 / 94 % | 11 / 41 % | – | 38 / 67 % | – | 12 / 38 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 29 / 56 % | 43 / 68 % | 7 / 19 % | – | 31 / 55 % | – | 17 / 40 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 42 / 84 % | 1 / 6 % | – | 17 / 37 % | – | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 37 / 70 % | 0 / 0 % | – | 9 / 22 % | – | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 35 / 74 % | 0 / 2 % | – | 6 / 16 % | – | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 33 / 71 % | 0 / 1 % | – | 7 / 19 % | – | 1 / 9 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 23 / 47 % | 0 / 0 % | 1 / 9 % | – | 24 / 52 % | – | 3 / 17 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 23 / 36 % | – | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 19 / 51 % | 0 / 4 % | – | 13 / 39 % | – | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 43 % | 10 / 71 % | 2 / 9 % | – | 10 / 31 % | – | 4 / 17 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 18 / 66 % | 0 / 0 % | – | 6 / 17 % | – | 1 / 8 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 9 / 34 % | 0 / 0 % | – | 17 / 41 % | – | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 47 % | 0 / 0 % | 0 / 2 % | – | 11 / 32 % | – | 3 / 12 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 42 % | 0 / 0 % | 1 / 4 % | – | 11 / 33 % | – | 5 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 10 / 19 % | – | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 10 / 19 % | – | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 9 / 64 % | 0 / 0 % | – | 6 / 15 % | – | 0 / 2 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 9 / 67 % | 0 / 2 % | – | 8 / 24 % | – | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 21 % | – | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 21 % | – | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 20 % | – | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 2 / 17 % | 0 / 0 % | – | 7 / 21 % | – | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 43 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 3 % | – | 6 / 21 % | – | 1 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 0 / 3 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | – | 1 / 7 % |
