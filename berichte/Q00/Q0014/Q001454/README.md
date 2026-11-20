[English](README.md) · [Deutsch](README.de.md)

# More compute, more capability: Why AI agent evaluations need to account for test-time compute

Report Q001454 · Source aisi.gov.uk · Date 2026-07-02 · [Open original](https://www.aisi.gov.uk/blog/more-compute-more-capability-why-ai-agent-evals-need-to-account-for-test-time-compute)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Das AISI berichtet, dass feste Rechenbudgets die Fähigkeiten von KI-Agenten unterschätzen können, weil ihre Leistung bei vielen Aufgaben mit zusätzlichem Testzeitaufwand steigt und neuere Modelle davon stärker profitieren. Die Befunde sind jedoch nicht einheitlich: Bei HealthBench zeigte sich ein Plateau, und der Zusammenhang zwischen menschlicher Aufgabendauer und Agentenbudget wurde bislang nur für Cyber- und Softwareaufgaben untersucht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 65 % | 94 / 99 % | – | 95 / 98 % | 34 / 62 % | 43 / 69 % | 49 / 70 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 47 % | 70 / 91 % | – | 93 / 95 % | 13 / 35 % | 6 / 17 % | 9 / 24 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 66 / 78 % | 86 / 99 % | – | 91 / 97 % | 12 / 23 % | 54 / 73 % | 69 / 81 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 24 / 48 % | 62 / 92 % | – | 87 / 91 % | 20 / 42 % | 15 / 36 % | 14 / 29 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 17 / 84 % | – | 54 / 80 % | 57 / 78 % | 15 / 35 % | 18 / 37 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 24 / 49 % | 36 / 89 % | – | 53 / 58 % | 21 / 43 % | 4 / 13 % | 11 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 12 / 45 % | – | 53 / 74 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 51 / 77 % | 8 / 22 % | 4 / 14 % | 10 / 20 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 24 / 51 % | 41 / 95 % | – | 15 / 42 % | 24 / 54 % | 7 / 21 % | 11 / 26 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 39 % | 36 / 94 % | – | 0 / 0 % | 11 / 31 % | 1 / 9 % | 7 / 15 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 32 / 66 % | 7 / 23 % | 2 / 9 % | 4 / 11 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 31 / 92 % | – | 8 / 40 % | 7 / 18 % | 1 / 6 % | 5 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 27 / 45 % | 4 / 59 % | – | 10 / 44 % | 25 / 48 % | 8 / 24 % | 17 / 35 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 10 / 49 % | – | 25 / 41 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 52 % | 0 / 0 % | – | 0 / 0 % | 16 / 35 % | 9 / 26 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 45 % | 0 / 0 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 8 / 31 % | 19 / 74 % | – | 4 / 20 % | 10 / 27 % | 0 / 0 % | 6 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 18 / 39 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 17 / 28 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 17 / 45 % | 4 / 80 % | – | 0 / 0 % | 8 / 26 % | 5 / 14 % | 11 / 21 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 15 / 35 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 14 / 63 % | – | 2 / 32 % | 10 / 28 % | 2 / 6 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 4 / 57 % | – | 0 / 0 % | 8 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 28 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 2 / 7 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 3 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 2 / 23 % | – | 0 / 0 % | 8 / 20 % | 2 / 8 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 70 % | – | 0 / 0 % | 6 / 16 % | 1 / 7 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 1 / 4 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 9 % | 0 / 2 % | 4 / 10 % |
