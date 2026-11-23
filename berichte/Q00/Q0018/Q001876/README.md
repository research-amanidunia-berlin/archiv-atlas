[English](README.md) · [Deutsch](README.de.md)

# Review of the Anthropic Sabotage Risk Report: Claude Opus 4.6

Report Q001876 · Source metr.org · Date 2026-03-12 · [Open original](https://metr.org/blog/2026-03-12-sabotage-risk-report-opus-4-6-review/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Auszug fasst METRs Prüfung zweier Fassungen von Anthropics Risikobericht zu Claude Opus 4.6 zusammen. METR hält das Risiko katastrophaler, durch Fehlanpassung ermöglichter Folgen für sehr niedrig, aber nicht vernachlässigbar, sieht Schwächen in Teilen der Analyse und mögliche blinde Flecken bei der Ausrichtungsbewertung. Empfohlen werden weitere Untersuchungen; die öffentliche Nutzung ohne größere Vorfälle beeinflusst METRs Zuversicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 52 / 71 % | 69 / 95 % | 95 / 98 % | 51 / 75 % | 47 / 73 % | 69 / 82 % | 68 / 87 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 45 / 65 % | 87 / 96 % | 80 / 91 % | 51 / 75 % | 49 / 70 % | 60 / 78 % | 27 / 55 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 57 % | 50 / 93 % | 87 / 95 % | 33 / 62 % | 13 / 38 % | 39 / 65 % | 11 / 39 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 47 / 68 % | 40 / 83 % | 60 / 82 % | 62 / 81 % | 49 / 73 % | 69 / 81 % | 29 / 55 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 61 / 81 % | 6 / 18 % | 2 / 7 % | 0 / 0 % | 1 / 6 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 26 / 50 % | 30 / 63 % | 60 / 74 % | 34 / 60 % | 14 / 29 % | 34 / 52 % | 6 / 23 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 42 / 66 % | 26 / 67 % | 50 / 67 % | 30 / 59 % | 22 / 43 % | 48 / 64 % | 7 / 26 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 29 / 58 % | 20 / 54 % | 49 / 76 % | 9 / 26 % | 5 / 19 % | 25 / 47 % | 7 / 33 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 43 / 66 % | 19 / 47 % | 8 / 23 % | 0 / 0 % | 2 / 8 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 39 / 63 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 32 / 59 % | 0 / 0 % | 0 / 0 % | 32 / 59 % | 22 / 45 % | 18 / 37 % | 5 / 19 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 24 / 45 % | 0 / 0 % | 10 / 29 % | 14 / 39 % | 7 / 19 % | 18 / 35 % | 2 / 11 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 36 % | 21 / 54 % | 0 / 0 % | 8 / 25 % | 2 / 9 % | 7 / 16 % | 1 / 5 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 45 % | 0 / 0 % | 5 / 20 % | 10 / 27 % | 2 / 9 % | 7 / 14 % | 1 / 8 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 19 / 38 % | 8 / 26 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 47 % | 12 / 62 % | 8 / 36 % | 13 / 45 % | 5 / 17 % | 13 / 33 % | 2 / 13 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 18 / 38 % | 6 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 16 / 32 % | 11 / 37 % | 3 / 11 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 35 % | 3 / 13 % | 14 / 31 % | 1 / 7 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 39 % | 13 / 43 % | 0 / 0 % | 9 / 33 % | 2 / 10 % | 8 / 20 % | 1 / 6 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 13 / 36 % | 0 / 0 % | 11 / 35 % | 1 / 5 % | 0 / 0 % | 1 / 5 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 12 / 32 % | 6 / 18 % | 1 / 7 % | 4 / 12 % | 0 / 3 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 2 / 10 % | 11 / 23 % | 0 / 2 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 9 / 31 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 31 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 1 / 7 % | 6 / 13 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 1 / 9 % | 7 / 24 % | 1 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 5 / 28 % | 7 / 18 % | 1 / 6 % | 5 / 15 % | 0 / 2 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 5 % | 0 / 0 % | 0 / 2 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 1 / 7 % | 0 / 0 % | 0 / 3 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 0 / 0 % | 0 / 2 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
