[English](README.md) · [Deutsch](README.de.md)

# Introducing Claude Sonnet 5

Report Q003674 · Source anthropic.com · Date 2026-06-30 · [Open original](https://www.anthropic.com/news/claude-sonnet-5)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge verbessert Claude Sonnet 5 die agentischen Fähigkeiten von Sonnet 4.6 deutlich und erreicht bei manchen Aufgaben Opus 4.8 zu geringeren Kosten. Die Sicherheitsprüfungen zeigen Fortschritte gegenüber Sonnet 4.6, aber schwächere Ergebnisse als Opus 4.8 bei bestimmten Audits; bei Cybertests gab es keine vollständigen Firefox-Exploits, jedoch etwas häufiger Teilerfolge als beim Vorgänger. Der Bericht nennt einen dauerhaften Preis von 2 US-Dollar je Million Eingabetoken und 10 je Million Ausgabetoken und weist auf nachträglich korrigierte Benchmarkangaben hin.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 52 / 69 % | 82 / 93 % | 99 / 100 % | 8 / 22 % | 35 / 56 % | 73 / 83 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 58 % | 93 / 99 % | 99 / 100 % | 53 / 76 % | 47 / 67 % | 70 / 83 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 56 % | 90 / 98 % | 99 / 100 % | 71 / 85 % | 30 / 59 % | 65 / 82 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 32 / 50 % | 92 / 97 % | 96 / 97 % | 72 / 85 % | 43 / 66 % | 76 / 87 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 37 / 54 % | 95 / 99 % | 92 / 96 % | 60 / 80 % | 35 / 58 % | 51 / 73 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 28 / 48 % | 81 / 96 % | 94 / 99 % | 63 / 81 % | 10 / 28 % | 51 / 68 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 26 / 45 % | 79 / 95 % | 90 / 94 % | 28 / 54 % | 13 / 29 % | 24 / 42 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 43 / 82 % | 82 / 91 % | 10 / 32 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 18 / 49 % | 78 / 85 % | 40 / 64 % | 9 / 21 % | 8 / 16 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 35 / 67 % | 65 / 80 % | 10 / 25 % | 1 / 5 % | 5 / 11 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 33 / 81 % | 62 / 73 % | 7 / 19 % | 2 / 7 % | 5 / 10 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 18 / 42 % | 58 / 75 % | 8 / 20 % | 0 / 0 % | 5 / 9 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 15 / 41 % | 37 / 74 % | 0 / 0 % | 11 / 32 % | 1 / 6 % | 8 / 18 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 32 / 46 % | 0 / 0 % | 33 / 55 % | 36 / 61 % | 6 / 15 % | 15 / 26 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 35 / 53 % | 8 / 17 % | 1 / 3 % | 4 / 7 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 33 / 48 % | 6 / 16 % | 1 / 5 % | 3 / 7 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 25 / 70 % | 27 / 49 % | 29 / 57 % | 4 / 11 % | 13 / 30 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 53 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 34 % | 26 / 54 % | 0 / 0 % | 22 / 44 % | 9 / 21 % | 27 / 42 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 19 / 54 % | 2 / 12 % | 10 / 26 % | 1 / 4 % | 5 / 11 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 42 % | 2 / 6 % | 7 / 14 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 25 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 2 / 6 % | 9 / 18 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 11 / 36 % | 2 / 17 % | 9 / 22 % | 2 / 6 % | 6 / 11 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 2 / 5 % | 9 / 21 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 8 / 18 % | 8 / 15 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 1 / 4 % | 9 / 21 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 26 % | 2 / 9 % | 5 / 11 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 1 % | 6 / 11 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 1 % | 4 / 7 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 1 / 4 % | 5 / 8 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 5 / 44 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 4 / 6 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 6 % | 3 / 6 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % | – | – |
