[English](README.md) · [Deutsch](README.de.md)

# Review of the Anthropic Summer 2025 Pilot Sabotage Risk Report

Report Q002130 · Source metr.org · Date 2025-10-28 · [Open original](https://metr.org/blog/2025-10-28-sabotage-report-review/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorgelegte Text ist nur die Executive Summary einer METR-Prüfung, nicht der vollständige Bericht. METR teilt grundsätzlich Anthropics Einschätzung, dass das Risiko katastrophaler Sabotage durch Opus 4 und 4.1 gering ist, merkt aber an, die Begründung könne die Möglichkeit unauffälliger fehlgeleiteter Überlegungen und die Zuverlässigkeit von Überwachung zu optimistisch beurteilen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 56 % | 63 / 96 % | 96 / 98 % | 38 / 65 % | 18 / 44 % | 43 / 68 % | 20 / 57 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 50 / 69 % | 85 / 98 % | 89 / 95 % | 56 / 79 % | 56 / 77 % | 69 / 83 % | 60 / 87 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 45 / 64 % | 75 / 97 % | 86 / 95 % | 57 / 79 % | 56 / 74 % | 46 / 69 % | 43 / 70 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 26 / 50 % | 56 / 87 % | 73 / 80 % | 41 / 64 % | 16 / 30 % | 30 / 50 % | 7 / 25 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 47 / 66 % | 16 / 74 % | 58 / 81 % | 68 / 84 % | 61 / 78 % | 72 / 84 % | 44 / 70 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 41 / 64 % | 32 / 84 % | 55 / 71 % | 34 / 62 % | 24 / 43 % | 49 / 66 % | 10 / 41 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 27 / 56 % | 6 / 46 % | 54 / 78 % | 5 / 14 % | 9 / 26 % | 30 / 54 % | 10 / 43 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 29 / 50 % | 13 / 42 % | 43 / 65 % | 29 / 57 % | 7 / 19 % | 25 / 43 % | 7 / 28 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 42 / 66 % | 24 / 51 % | 12 / 27 % | 0 / 0 % | 4 / 15 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 38 / 61 % | 3 / 9 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 34 / 59 % | 0 / 0 % | 37 / 46 % | 37 / 62 % | 28 / 51 % | 21 / 42 % | 9 / 31 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 35 / 52 % | 9 / 27 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 34 / 54 % | 7 / 15 % | 1 / 4 % | 8 / 16 % | 1 / 4 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 19 / 48 % | 32 / 73 % | 11 / 41 % | 17 / 45 % | 7 / 21 % | 16 / 34 % | 3 / 16 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 30 / 45 % | 14 / 41 % | 5 / 14 % | 11 / 23 % | 1 / 6 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 23 / 49 % | 27 / 69 % | 26 / 55 % | 14 / 35 % | 2 / 9 % | 10 / 20 % | 2 / 16 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 29 % | 4 / 14 % | 18 / 39 % | 2 / 10 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 45 % | 17 / 57 % | 9 / 23 % | 9 / 28 % | 3 / 13 % | 9 / 19 % | 0 / 3 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 15 / 25 % | 16 / 45 % | 7 / 18 % | 9 / 26 % | 2 / 8 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 3 / 11 % | 15 / 31 % | 1 / 6 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 8 / 32 % | 7 / 30 % | 13 / 41 % | 1 / 8 % | 11 / 23 % | 1 / 7 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 13 / 34 % | 6 / 18 % | 1 / 5 % | 5 / 12 % | 0 / 5 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 11 / 37 % | 6 / 15 % | 1 / 5 % | 5 / 14 % | 0 / 2 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 6 / 19 % | 9 / 28 % | 2 / 10 % | 10 / 22 % | 1 / 5 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 40 % | 10 / 37 % | 2 / 17 % | 8 / 24 % | 2 / 9 % | 9 / 21 % | 1 / 7 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 1 / 9 % | 10 / 33 % | 3 / 13 % | 0 / 0 % | 1 / 5 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 3 / 15 % | 7 / 17 % | 1 / 7 % | 6 / 11 % | 0 / 2 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 4 % | 5 / 11 % | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 4 % | 6 / 12 % | 0 / 3 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 5 % | 3 / 8 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 2 / 6 % | 6 / 20 % | 2 / 8 % | 5 / 12 % | 0 / 3 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % | 0 / 3 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 4 % | 3 / 5 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 3 / 9 % | 0 / 0 % | – |
