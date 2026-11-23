[English](README.md) · [Deutsch](README.de.md)

# Project Swap: What happens when agents trade for us?

Report Q001286 · Source anthropic.com · Date 2026-09-24 · [Open original](https://www.anthropic.com/research/project-swap)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropics Project Swap untersuchte, wie Claude-Agenten für 201 Beschäftigte Bücher tauschen. Die Studie berichtet, dass ungenaue Einschätzungen der Vorlieben den größten Teil der Lücke zum bestmöglichen Ergebnis erklärten; Modellwahl beeinflusste den Handel stärker als die Agentenanweisungen, während die Zufriedenheit unter den Befragten relativ hoch war. Die Ergebnisse sind wegen der Beschäftigten-Stichprobe, der begrenzten Rückmeldungen und der ausschließlich kooperativen Agenten nur eingeschränkt verallgemeinerbar.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 33 / 51 % | 82 / 99 % | 99 / 100 % | 56 / 78 % | 19 / 41 % | 51 / 71 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 33 / 51 % | 75 / 94 % | 98 / 99 % | 44 / 70 % | 19 / 42 % | 41 / 67 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 27 / 51 % | 96 / 99 % | 96 / 98 % | 67 / 84 % | 40 / 63 % | 67 / 82 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 44 % | 44 / 74 % | 88 / 91 % | 24 / 51 % | 8 / 19 % | 18 / 35 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 25 / 89 % | 81 / 90 % | 12 / 32 % | 0 / 0 % | 12 / 24 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 35 / 68 % | 79 / 86 % | 54 / 75 % | 12 / 27 % | 26 / 44 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 79 / 99 % | 64 / 80 % | 40 / 65 % | 12 / 27 % | 17 / 33 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 2 / 34 % | 78 / 93 % | 7 / 21 % | 2 / 12 % | 7 / 19 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 27 / 50 % | 55 / 94 % | 75 / 90 % | 59 / 79 % | 18 / 43 % | 46 / 69 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 15 / 84 % | 72 / 87 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 44 / 99 % | 64 / 85 % | 7 / 22 % | 2 / 9 % | 7 / 18 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 11 / 46 % | 55 / 72 % | 21 / 44 % | 0 / 0 % | 8 / 18 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 31 / 77 % | 47 / 61 % | 16 / 37 % | 7 / 19 % | 18 / 35 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 5 / 73 % | 37 / 57 % | 7 / 17 % | 1 / 4 % | 5 / 9 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 4 / 36 % | 32 / 69 % | 10 / 23 % | 0 / 0 % | 6 / 12 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 18 / 68 % | 4 / 24 % | 7 / 19 % | 4 / 15 % | 0 / 0 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 16 / 32 % | 0 / 0 % | 4 / 27 % | 10 / 28 % | 0 / 0 % | 8 / 17 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 4 / 50 % | 13 / 43 % | 6 / 12 % | 0 / 0 % | 2 / 3 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 13 / 46 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 2 / 75 % | 0 / 0 % | 11 / 30 % | 7 / 18 % | 11 / 24 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 23 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 2 / 8 % | 5 / 9 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 3 / 44 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 8 / 54 % | 8 / 23 % | 8 / 19 % | 4 / 14 % | 9 / 21 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 3 / 8 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 14 % | 0 / 4 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 4 % | 7 / 15 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 3 / 5 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 2 / 67 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 7 / 12 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 5 / 9 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 2 / 49 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | – | – |
