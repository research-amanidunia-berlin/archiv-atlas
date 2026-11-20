[English](README.md) · [Deutsch](README.de.md)

# Claude Fable 5 Turned a Two-Month Migration Into a Day’s Work. You Have Two Weeks to Try It.

Report Q011079 · Source medium.com · Date 2026-06-10 · [Open original](https://medium.com/data-science-collective/claude-fable-5-turned-a-two-month-migration-into-a-days-work-you-have-two-weeks-to-try-it-b4a83973d8c1)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor sieht in Fable 5s angeblich deutlich schnellerer Bearbeitung einer großen Stripe-Migration einen möglichen Wendepunkt für aufgeschobene Wartung, betont aber, dass die Zahl aus einer Hersteller-Fallstudie stammt und sorgfältige Prüfung sowie belastbare Tests weiterhin nötig sind. Er beschreibt weitere Fähigkeiten und die Sicherheitsfilter, Datenaufbewahrung sowie befristete Abo-Verfügbarkeit als Chancen und Einschränkungen, deren praktische Folgen besonders Entwickler sicherheitsnaher Systeme betreffen könnten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 44 % | 80 / 93 % | 29 / 59 % | 100 / 100 % | 65 / 82 % | 61 / 77 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 78 / 92 % | 2 / 11 % | 98 / 99 % | 13 / 36 % | 9 / 25 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 47 / 75 % | 0 / 3 % | 98 / 99 % | 10 / 24 % | 7 / 12 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 27 / 45 % | 43 / 71 % | 22 / 39 % | 95 / 98 % | 31 / 52 % | 51 / 69 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 51 / 79 % | 2 / 9 % | 95 / 97 % | 13 / 34 % | 8 / 18 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 16 / 32 % | 88 / 94 % | 23 / 31 % | 94 / 96 % | 40 / 63 % | 20 / 34 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 32 % | 50 / 81 % | 10 / 24 % | 93 / 96 % | 32 / 55 % | 23 / 41 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 46 % | 44 / 71 % | 11 / 26 % | 91 / 94 % | 42 / 67 % | 45 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 15 / 30 % | 39 / 66 % | 3 / 9 % | 88 / 92 % | 38 / 63 % | 40 / 57 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 32 / 50 % | 48 / 83 % | 13 / 40 % | 84 / 92 % | 45 / 67 % | 27 / 47 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 23 / 44 % | 29 / 71 % | 9 / 18 % | 79 / 86 % | 39 / 62 % | 32 / 51 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 75 / 83 % | 10 / 19 % | 4 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 5 / 13 % | 67 / 77 % | 23 / 45 % | 12 / 26 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 23 / 44 % | 51 / 78 % | 17 / 30 % | 62 / 73 % | 56 / 75 % | 49 / 65 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 10 % | 59 / 71 % | 9 / 23 % | 6 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 8 / 35 % | 1 / 5 % | 58 / 73 % | 24 / 47 % | 8 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 24 / 32 % | 2 / 4 % | 7 / 9 % | 27 / 40 % | 52 / 70 % | 43 / 52 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 40 % | 0 / 0 % | 5 / 17 % | 49 / 69 % | 32 / 55 % | 20 / 38 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 39 / 75 % | 2 / 7 % | 42 / 61 % | 21 / 47 % | 12 / 29 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 24 / 46 % | 18 / 54 % | 14 / 42 % | 41 / 56 % | 34 / 57 % | 26 / 43 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 32 % | 40 / 70 % | 1 / 8 % | 28 / 48 % | 13 / 33 % | 12 / 28 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 35 / 64 % | 0 / 2 % | 17 / 29 % | 9 / 21 % | 10 / 19 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 27 / 70 % | 1 / 6 % | 34 / 41 % | 16 / 35 % | 7 / 16 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 25 / 50 % | 1 / 4 % | 32 / 49 % | 10 / 23 % | 10 / 20 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 51 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 40 % | 7 / 13 % | 5 / 9 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 27 % | 6 / 12 % | 5 / 10 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 33 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 11 / 29 % | 14 / 28 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 2 / 6 % | 16 / 24 % | 12 / 28 % | 12 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 25 % | 9 / 19 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 12 / 28 % | 12 / 28 % | 5 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 6 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 5 / 17 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 8 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 6 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 14 % | 8 / 15 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 2 / 5 % | 8 / 18 % | 7 / 16 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 7 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 16 % | 6 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 5 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
