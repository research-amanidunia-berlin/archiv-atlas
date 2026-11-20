[English](README.md) · [Deutsch](README.de.md)

# GPT-Red: Unlocking Self-Improvement for Robustness

Report Q006453 · Source openai.com · Date 2026-07-15 · [Open original](https://openai.com/index/unlocking-self-improvement-gpt-red/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI stellt GPT‑Red als internes Angriffstestmodell vor, das Schwachstellen finden und Produktionsmodelle durch selbstverstärkendes Training robuster gegen Prompt-Injections machen soll. Das Unternehmen berichtet von deutlichen Verbesserungen bei GPT‑5.6 Sol, stützt diese Angaben aber auf bestimmte Testumgebungen und Benchmarks; GPT‑Red soll intern bleiben und weitere Schutzmaßnahmen ergänzen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 42 / 62 % | 99 / 100 % | – | 100 / 100 % | 69 / 83 % | 31 / 57 % | 75 / 84 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 33 / 54 % | 69 / 92 % | – | 99 / 100 % | 50 / 74 % | 14 / 38 % | 54 / 76 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 57 % | 79 / 97 % | – | 98 / 99 % | 54 / 76 % | 40 / 63 % | 62 / 79 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 29 / 55 % | 61 / 95 % | – | 95 / 98 % | 8 / 17 % | 18 / 40 % | 49 / 69 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 62 % | 94 / 100 % | – | 84 / 90 % | 63 / 81 % | 30 / 55 % | 59 / 76 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 84 / 90 % | 26 / 50 % | 4 / 11 % | 7 / 15 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 21 / 48 % | 62 / 90 % | – | 83 / 92 % | 47 / 68 % | 9 / 26 % | 31 / 55 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 43 / 76 % | – | 80 / 87 % | 15 / 39 % | 3 / 10 % | 16 / 30 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 14 / 58 % | – | 71 / 83 % | 7 / 15 % | 0 / 0 % | 4 / 8 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 30 / 52 % | 47 / 77 % | – | 53 / 67 % | 57 / 78 % | 24 / 47 % | 67 / 81 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 61 / 74 % | 13 / 34 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 13 / 70 % | – | 49 / 66 % | 54 / 74 % | 8 / 25 % | 19 / 46 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 20 / 37 % | 32 / 88 % | – | 51 / 79 % | 39 / 63 % | 0 / 0 % | 14 / 27 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 46 / 65 % | 13 / 29 % | 3 / 7 % | 6 / 11 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 46 / 71 % | – | 21 / 47 % | 8 / 17 % | 1 / 6 % | 5 / 11 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 35 / 78 % | – | 12 / 39 % | 22 / 49 % | 4 / 13 % | 10 / 23 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 84 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 35 % | 31 / 83 % | – | 6 / 22 % | 17 / 43 % | 3 / 9 % | 16 / 28 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 29 / 61 % | – | 18 / 43 % | 15 / 38 % | 0 / 0 % | 9 / 21 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 26 / 67 % | – | 25 / 42 % | 15 / 38 % | 6 / 13 % | 15 / 29 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 25 / 87 % | – | 0 / 0 % | 14 / 35 % | 5 / 17 % | 21 / 40 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 20 / 48 % | 3 / 9 % | 10 / 22 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 15 / 37 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 11 / 25 % | 14 / 37 % | 2 / 8 % | 11 / 21 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 35 % | 1 / 5 % | 5 / 10 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 25 % | 2 / 5 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 1 / 14 % | 10 / 25 % | 2 / 7 % | 5 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 1 / 4 % | 8 / 20 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 2 / 5 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 44 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 8 / 28 % | 6 / 14 % | 1 / 6 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 4 / 16 % | 7 / 16 % | 1 / 6 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 0 / 0 % | 3 / 7 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 1 / 6 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 23 % | – | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % |
