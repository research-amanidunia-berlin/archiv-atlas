[English](README.md) · [Deutsch](README.de.md)

# Building AI for cyber defenders

Report Q001829 · Source anthropic.com · Date 2025-09-29 · [Open original](https://www.anthropic.com/research/building-ai-cyber-defenders)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, Claude Sonnet 4.5 habe bei Benchmarks zur Schwachstellensuche und -analyse frühere Claude-Modelle übertroffen; bei wiederholten Versuchen stiegen die Erfolgsraten deutlich. Die Patch-Ergebnisse sind vorläufig, die Benchmarks bilden reale Sicherheitsarbeit nur teilweise ab, und Anthropic räumt ein, dass das Modell Fachleute und etablierte Abläufe noch nicht erreicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 69 / 78 % | 98 / 99 % | 100 / 100 % | 72 / 80 % | 78 / 88 % | 87 / 91 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 58 % | 92 / 99 % | 99 / 100 % | 60 / 80 % | 54 / 73 % | 72 / 84 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 45 % | 67 / 93 % | 94 / 97 % | 43 / 69 % | 11 / 28 % | 37 / 59 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 9 / 69 % | 86 / 93 % | 54 / 76 % | 10 / 22 % | 15 / 31 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 44 % | 42 / 81 % | 82 / 90 % | 19 / 46 % | 5 / 16 % | 25 / 46 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 76 / 81 % | 14 / 38 % | 4 / 9 % | 12 / 22 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 23 / 72 % | 61 / 77 % | 19 / 47 % | 12 / 24 % | 19 / 36 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 33 / 63 % | 60 / 83 % | 21 / 43 % | 4 / 14 % | 13 / 25 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 27 / 41 % | 59 / 92 % | 42 / 75 % | 23 / 52 % | 3 / 16 % | 16 / 34 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 59 / 73 % | 6 / 11 % | 1 / 4 % | 4 / 8 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 29 % | 58 / 91 % | 43 / 68 % | 12 / 39 % | 3 / 13 % | 13 / 31 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 16 / 46 % | 0 / 0 % | 48 / 72 % | 20 / 47 % | 5 / 16 % | 10 / 18 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 21 / 37 % | 11 / 61 % | 23 / 52 % | 47 / 70 % | 9 / 25 % | 37 / 54 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 35 / 88 % | 37 / 62 % | 10 / 31 % | 3 / 13 % | 8 / 18 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 22 / 61 % | 35 / 66 % | 9 / 31 % | 2 / 12 % | 7 / 23 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 28 / 59 % | 26 / 42 % | 33 / 57 % | 7 / 23 % | 20 / 32 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 16 / 38 % | 32 / 90 % | 9 / 59 % | 31 / 59 % | 9 / 25 % | 18 / 44 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 10 / 67 % | 31 / 51 % | 12 / 36 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 28 / 86 % | 29 / 65 % | 17 / 44 % | 4 / 14 % | 13 / 32 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 29 / 76 % | 4 / 17 % | 11 / 31 % | 3 / 13 % | 7 / 19 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 28 / 45 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 10 / 41 % | 28 / 63 % | 8 / 23 % | 2 / 8 % | 8 / 18 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 16 / 71 % | 10 / 38 % | 20 / 51 % | 4 / 13 % | 11 / 29 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 41 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 19 / 49 % | 10 / 33 % | 4 / 16 % | 7 / 21 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 18 / 65 % | 1 / 14 % | 12 / 40 % | 1 / 8 % | 10 / 27 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 18 / 80 % | 2 / 9 % | 9 / 23 % | 5 / 15 % | 8 / 18 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 26 % | 15 / 58 % | 4 / 17 % | 10 / 26 % | 3 / 11 % | 11 / 22 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 6 / 64 % | 10 / 30 % | 11 / 31 % | 5 / 17 % | 13 / 30 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 30 % | 1 / 6 % | 11 / 23 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 1 / 34 % | 1 / 16 % | 8 / 28 % | 2 / 9 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 5 % | 5 / 12 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 7 % | 0 / 0 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 5 % | 4 / 8 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 5 / 12 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 5 / 10 % | – | – |
