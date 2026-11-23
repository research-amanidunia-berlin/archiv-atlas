[English](README.md) · [Deutsch](README.de.md)

# Claude Code Writes My Code. Codex Reviews It. The Arguing Is the Point.

Report Q011051 · Source medium.com · Date 2026-07-08 · [Open original](https://medium.com/codetodeploy/claude-code-writes-my-code-codex-reviews-it-the-arguing-is-the-point-d94029dae928)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor beschreibt einen Ablauf, in dem Claude Opus plant, Sonnet implementiert und Codex den Code unabhängig prüft; laut seinen Beispielen fand Codex Fehler mit möglichen Folgen wie Datenverlust, die Claude bei der Selbstprüfung übersehen hatte. Damit die Prüfung nützlich bleibt, begrenzt der Autor sie auf schwerwiegende Befunde und höchstens zwei Runden. Eine erwähnte Studie spricht allerdings für die umgekehrte Prüfrichtung, und der Bericht belegt nicht, welche Rollenverteilung allgemein am besten ist.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 41 % | 74 / 94 % | 100 / 100 % | 48 / 71 % | 12 / 28 % | 30 / 52 % | 7 / 27 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 10 / 46 % | 100 / 100 % | 9 / 22 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 98 / 100 % | 87 / 91 % | 10 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 5 / 30 % | 98 / 99 % | 10 / 29 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 26 / 47 % | 45 / 89 % | 97 / 98 % | 45 / 68 % | 8 / 23 % | 16 / 32 % | 5 / 16 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 38 % | 20 / 47 % | 95 / 97 % | 21 / 42 % | 0 / 0 % | 7 / 14 % | 3 / 16 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 22 / 71 % | 87 / 90 % | 30 / 54 % | 10 / 21 % | 8 / 16 % | 4 / 17 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 28 / 59 % | 85 / 90 % | 49 / 71 % | 12 / 26 % | 25 / 45 % | 2 / 8 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 45 / 85 % | 62 / 74 % | 22 / 50 % | 7 / 18 % | 9 / 18 % | 1 / 6 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 43 % | 13 / 44 % | 56 / 65 % | 27 / 53 % | 17 / 35 % | 14 / 29 % | 2 / 11 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 27 % | 56 / 70 % | 7 / 18 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 1 / 10 % | 49 / 64 % | 8 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 43 / 61 % | 10 / 24 % | 0 / 0 % | 5 / 8 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 35 % | 5 / 53 % | 32 / 52 % | 13 / 34 % | 8 / 21 % | 14 / 29 % | 0 / 4 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 27 / 39 % | 7 / 13 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 2 / 31 % | 17 / 35 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 30 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 3 / 14 % | 7 / 15 % | 0 / 3 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 3 / 9 % | 5 / 10 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 4 % | 7 / 12 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 4 / 5 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
