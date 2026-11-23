[English](README.md) · [Deutsch](README.de.md)

# Measuring AI agent autonomy in practice

Report Q001182 · Source anthropic.com · Date 2026-02-18 · [Open original](https://www.anthropic.com/research/measuring-agent-autonomy)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, dass Claude Code in den längsten Sitzungen zunehmend länger autonom arbeitet und erfahrene Nutzer häufiger automatische Freigaben mit gezielten Unterbrechungen verbinden. Die meisten untersuchten API-Aktionen seien risikoarm, doch die Studie beruht auf Anthropic-Daten, Claude-generierten Einschätzungen und einer nur teilweisen Sicht auf tatsächliche Abläufe.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 48 / 63 % | 99 / 100 % | 100 / 100 % | 79 / 89 % | 57 / 77 % | 75 / 86 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 75 / 86 % | 95 / 97 % | 100 / 100 % | 89 / 94 % | 67 / 86 % | 81 / 89 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 31 / 46 % | 89 / 95 % | 100 / 100 % | 34 / 62 % | 37 / 61 % | 44 / 66 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 17 / 35 % | 0 / 0 % | 94 / 97 % | 18 / 46 % | 6 / 18 % | 10 / 28 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 37 % | 81 / 99 % | 83 / 96 % | 32 / 63 % | 13 / 33 % | 30 / 55 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 55 % | 74 / 94 % | 80 / 87 % | 50 / 76 % | 38 / 60 % | 61 / 78 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 26 / 46 % | 20 / 95 % | 73 / 90 % | 65 / 82 % | 57 / 79 % | 76 / 86 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 40 / 78 % | 76 / 88 % | 8 / 23 % | 2 / 7 % | 7 / 13 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 45 / 78 % | 75 / 86 % | 44 / 71 % | 12 / 28 % | 22 / 47 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 30 / 48 % | 62 / 95 % | 72 / 88 % | 37 / 66 % | 7 / 21 % | 19 / 53 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 21 / 76 % | 55 / 81 % | 21 / 49 % | 6 / 18 % | 9 / 21 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 13 / 25 % | 50 / 85 % | 25 / 55 % | 11 / 31 % | 0 / 0 % | 8 / 16 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 49 / 83 % | 37 / 72 % | 19 / 48 % | 7 / 25 % | 17 / 40 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 42 / 79 % | 3 / 24 % | 11 / 35 % | 1 / 5 % | 10 / 24 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 42 / 83 % | 25 / 60 % | 14 / 39 % | 3 / 9 % | 6 / 14 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 16 / 41 % | 22 / 96 % | 36 / 72 % | 26 / 57 % | 14 / 39 % | 26 / 54 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 34 / 90 % | 5 / 33 % | 10 / 28 % | 4 / 12 % | 6 / 16 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 32 / 93 % | 24 / 46 % | 13 / 34 % | 7 / 13 % | 15 / 37 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 31 / 91 % | 16 / 56 % | 19 / 47 % | 8 / 22 % | 21 / 39 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 31 / 79 % | 3 / 15 % | 9 / 25 % | 7 / 17 % | 0 / 0 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 30 / 80 % | 13 / 31 % | 8 / 23 % | 4 / 12 % | 7 / 16 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 5 / 97 % | 28 / 58 % | 6 / 19 % | 3 / 10 % | 6 / 13 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 36 % | 0 / 0 % | 0 / 0 % | 11 / 36 % | 6 / 18 % | 20 / 43 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 19 / 89 % | 16 / 51 % | 0 / 0 % | 2 / 5 % | 8 / 13 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 19 / 96 % | 17 / 51 % | 17 / 44 % | 9 / 25 % | 10 / 25 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 14 / 22 % | 9 / 86 % | 17 / 61 % | 11 / 34 % | 2 / 6 % | 8 / 20 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 16 / 85 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 9 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 44 % | 8 / 19 % | 9 / 23 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 15 / 91 % | 0 / 7 % | 6 / 14 % | 3 / 11 % | 6 / 14 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 26 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 4 / 13 % | 14 / 26 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 12 / 37 % | 6 / 14 % | 2 / 7 % | 6 / 11 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 5 / 80 % | 0 / 0 % | 10 / 26 % | 2 / 7 % | 8 / 19 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 1 / 12 % | 9 / 24 % | 1 / 4 % | 10 / 16 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 1 / 7 % | 5 / 17 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 6 / 12 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 6 / 94 % | 5 / 36 % | 6 / 18 % | 2 / 6 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 5 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 66 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
