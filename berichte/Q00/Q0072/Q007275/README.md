[English](README.md) · [Deutsch](README.de.md)

# Extracting Concepts from GPT-4

Report Q007275 · Source openai.com · Date 2024-06-06 · [Open original](https://openai.com/index/extracting-concepts-from-gpt-4/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet über Sparse Autoencoder, mit denen das Unternehmen nach eigener Darstellung 16 Millionen Merkmale in GPT‑4-Aktivierungen gefunden hat, darunter Muster, die sich als menschlich deutbare Konzepte lesen lassen könnten. Viele Merkmale sind jedoch schwer zu interpretieren, die Methode erfasst nicht das gesamte Modellverhalten und erklärt noch nicht, wie Merkmale berechnet oder weiterverwendet werden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 35 / 55 % | 93 / 99 % | – | 83 / 92 % | 20 / 50 % | 11 / 28 % | 15 / 34 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 26 / 51 % | 82 / 93 % | – | 76 / 88 % | 14 / 46 % | 14 / 37 % | 7 / 21 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 19 / 44 % | 0 / 0 % | – | 73 / 88 % | 18 / 35 % | 10 / 19 % | 5 / 12 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 30 / 68 % | – | 63 / 86 % | 7 / 23 % | 0 / 0 % | 1 / 9 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 32 / 56 % | 34 / 86 % | – | 44 / 78 % | 31 / 65 % | 28 / 55 % | 14 / 34 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 57 % | – | 44 / 56 % | 4 / 11 % | 0 / 0 % | 1 / 5 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 21 / 50 % | 31 / 69 % | – | 41 / 82 % | 11 / 42 % | 11 / 34 % | 3 / 18 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 20 / 57 % | – | 7 / 46 % | 5 / 13 % | 0 / 0 % | 1 / 4 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 19 / 47 % | 6 / 22 % | 0 / 0 % | 1 / 7 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 16 / 60 % | – | 0 / 0 % | 6 / 18 % | 9 / 20 % | 2 / 9 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 41 % | 15 / 72 % | – | 0 / 0 % | 5 / 13 % | 5 / 9 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 14 / 30 % | 7 / 27 % | 8 / 16 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 13 / 47 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 4 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 12 / 56 % | – | 3 / 42 % | 10 / 44 % | 10 / 31 % | 5 / 18 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 9 / 50 % | – | 3 / 37 % | 0 / 0 % | 6 / 14 % | 2 / 7 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 8 / 18 % | 1 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | – | 2 / 27 % | 7 / 23 % | 6 / 14 % | 1 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 21 % | 5 / 14 % | 1 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 21 % | 0 / 0 % | 1 / 5 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 7 / 50 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 6 / 13 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 5 / 8 % | 1 / 3 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 4 / 75 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 2 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 3 % |
