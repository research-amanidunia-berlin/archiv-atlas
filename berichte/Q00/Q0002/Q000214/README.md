[English](README.md) · [Deutsch](README.de.md)

# When AI Fails: Building Fault-Tolerant AI Systems

Report Q000214 · Source computer.org · Date 2026-10-30 · [Open original](https://www.computer.org/publications/tech-news/trends/fault-tolerance-for-ai)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Artikel empfiehlt, KI als störungsanfällige Abhängigkeit zu behandeln und neben technischen Fehlern auch falsche, aber plausibel wirkende Antworten abzusichern. Dafür nennt er Prüfungen, begrenzte Zeitbudgets und Wiederholungen, getrennte Ressourcen sowie vorab festgelegte Ausweichpfade bis hin zur menschlichen Prüfung oder zum sicheren Anhalten. Die Empfehlungen sind nicht durch quantitative Versuchsergebnisse im Text belegt, und die passende Ausfallstrategie hängt vom jeweiligen Einsatzfall ab.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 45 / 62 % | 92 / 98 % | 100 / 100 % | 66 / 82 % | 42 / 64 % | 51 / 73 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 72 / 86 % | 100 / 100 % | 100 / 100 % | 88 / 94 % | 89 / 95 % | 86 / 91 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 26 / 52 % | 94 / 99 % | 98 / 99 % | 60 / 80 % | 57 / 76 % | 61 / 78 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 96 / 99 % | 95 / 99 % | 58 / 78 % | 22 / 42 % | 27 / 45 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 55 / 93 % | 96 / 98 % | 5 / 12 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 81 / 95 % | 82 / 89 % | 7 / 21 % | 1 / 6 % | 7 / 16 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 28 / 48 % | 73 / 99 % | 39 / 82 % | 41 / 67 % | 13 / 25 % | 34 / 52 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 28 / 71 % | 69 / 87 % | 12 / 33 % | 3 / 10 % | 7 / 15 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 13 / 34 % | 60 / 88 % | 66 / 79 % | 33 / 55 % | 17 / 36 % | 28 / 52 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 52 / 85 % | 14 / 31 % | 14 / 43 % | 2 / 8 % | 10 / 22 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 20 / 85 % | 50 / 75 % | 11 / 39 % | 4 / 12 % | 16 / 39 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 31 / 63 % | 2 / 9 % | 6 / 19 % | 1 / 6 % | 8 / 15 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 19 / 60 % | 0 / 0 % | 25 / 54 % | 8 / 21 % | 28 / 50 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 24 / 45 % | 21 / 67 % | 0 / 0 % | 9 / 31 % | 9 / 19 % | 15 / 32 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 24 / 86 % | 0 / 0 % | 6 / 16 % | 0 / 1 % | 5 / 10 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 15 / 79 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 4 / 7 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 13 / 82 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 11 / 59 % | 0 / 0 % | 8 / 22 % | 1 / 4 % | 5 / 9 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 10 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 5 / 8 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 9 / 44 % | 0 / 0 % | 9 / 19 % | 2 / 8 % | 6 / 12 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 3 / 63 % | 0 / 0 % | 9 / 31 % | 0 / 2 % | 8 / 17 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 5 % | 6 / 13 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 8 / 46 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 4 / 7 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 46 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 7 / 13 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 6 / 13 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 3 / 52 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 4 / 7 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 4 / 40 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 44 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 1 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | – | – |
