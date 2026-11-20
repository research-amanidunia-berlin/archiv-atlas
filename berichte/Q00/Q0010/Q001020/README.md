[English](README.md) · [Deutsch](README.de.md)

# Implementing and Evaluating a Basic Per-Action Monitor for Safer Evals

Report Q001020 · Source metr.org · Date 2026-09-27 · [Open original](https://metr.org/notes/2026-09-27-implementing-a-basic-blocking-action-monitor/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR beschreibt einen Monitor, der riskante Werkzeugaktionen vor der Ausführung anhält und zur menschlichen Prüfung vorlegt. Erste Tests sind ermutigend, doch die Belege sind begrenzt: Überwachungslücken, unvollständige Nutzungsprotokolle, mögliche Umgehungen und fehlende Absicherung der menschlichen Prüfung lassen die tatsächliche Wirksamkeit offen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 42 / 58 % | 100 / 100 % | 53 / 75 % | 100 / 100 % | 74 / 86 % | 37 / 62 % | 56 / 72 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 54 / 66 % | 100 / 100 % | 84 / 95 % | 100 / 100 % | 78 / 89 % | 81 / 91 % | 86 / 92 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 47 / 61 % | 96 / 100 % | 52 / 80 % | 100 / 100 % | 72 / 86 % | 51 / 73 % | 74 / 86 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 62 / 77 % | 99 / 100 % | 88 / 96 % | 100 / 100 % | 88 / 94 % | 62 / 82 % | 83 / 90 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 51 / 65 % | 84 / 96 % | 73 / 85 % | 98 / 99 % | 83 / 91 % | 68 / 84 % | 85 / 92 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 34 / 50 % | 0 / 0 % | 11 / 33 % | 97 / 98 % | 49 / 72 % | 0 / 0 % | 31 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 52 % | 96 / 99 % | 12 / 29 % | 83 / 89 % | 48 / 74 % | 14 / 31 % | 49 / 71 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 82 / 95 % | 2 / 9 % | 96 / 98 % | 22 / 49 % | 14 / 30 % | 22 / 39 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 43 / 61 % | 10 / 25 % | 52 / 65 % | 55 / 78 % | 0 / 0 % | 72 / 84 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 24 / 44 % | 38 / 80 % | 4 / 16 % | 69 / 77 % | 18 / 46 % | 0 / 0 % | 16 / 29 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 28 / 52 % | 55 / 94 % | 14 / 40 % | 67 / 84 % | 27 / 52 % | 12 / 30 % | 38 / 62 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 60 / 72 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 55 / 82 % | 5 / 16 % | 22 / 51 % | 29 / 57 % | 8 / 20 % | 26 / 52 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 45 / 81 % | 6 / 20 % | 50 / 62 % | 29 / 54 % | 6 / 17 % | 16 / 33 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 33 / 52 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 22 / 45 % | 0 / 0 % | 41 / 55 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 2 / 8 % | 41 / 55 % | 21 / 45 % | 0 / 0 % | 14 / 28 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 35 / 57 % | 0 / 2 % | 0 / 0 % | 10 / 24 % | 0 / 0 % | 11 / 21 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 34 / 51 % | 28 / 54 % | 0 / 0 % | 13 / 26 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 3 / 14 % | 30 / 51 % | 26 / 55 % | 9 / 20 % | 20 / 39 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 26 / 82 % | 0 / 3 % | 12 / 36 % | 11 / 30 % | 0 / 0 % | 6 / 12 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 26 / 38 % | 0 / 0 % | 1 / 6 % | 12 / 26 % | 17 / 42 % | 0 / 0 % | 14 / 31 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 17 / 46 % | 1 / 5 % | 26 / 31 % | 16 / 33 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 1 / 1 % | 0 / 0 % | 25 / 45 % | 6 / 15 % | 12 / 17 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 25 / 46 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 15 / 35 % | 0 / 0 % | 24 / 41 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 19 / 31 % | 8 / 20 % | 0 / 0 % | 7 / 13 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 35 % | 7 / 14 % | 0 / 0 % | 6 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 7 / 35 % | 13 / 36 % | 7 / 21 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 30 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 8 / 14 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 7 / 40 % | 0 / 2 % | 7 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
