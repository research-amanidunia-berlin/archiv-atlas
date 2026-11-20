[English](README.md) · [Deutsch](README.de.md)

# 13 Claude Lessons We Learned After 3,600 Hours

Report Q009615 · Source frank-andrade.medium.com · Date 2026-09-18 · [Open original](https://frank-andrade.medium.com/13-claude-lessons-we-learned-after-3-600-hours-afdde5199bd5)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag gibt zwölf praktische Empfehlungen für Claude Cowork und Claude Code: Arbeitsdateien von Anweisungen trennen, Aufgaben klar benennen, Abläufe vereinheitlichen, Anweisungen knapp und überprüfbar halten sowie Git, Modelle und Agenten gezielt einsetzen. Es handelt sich um Empfehlungen aus den Erfahrungen der Autoren, nicht um Ergebnisse einer systematischen Untersuchung; zudem nennt der Titel 13 Lektionen, während der Text zwölf aufzählt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 45 % | 94 / 97 % | 0 / 0 % | 97 / 98 % | 40 / 63 % | 18 / 33 % | 6 / 18 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 23 / 42 % | 89 / 95 % | 2 / 10 % | 95 / 97 % | 37 / 59 % | 13 / 27 % | 4 / 15 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 60 / 85 % | 0 / 0 % | 90 / 93 % | 12 / 32 % | 5 / 13 % | 1 / 7 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 23 / 52 % | 0 / 0 % | 90 / 94 % | 6 / 16 % | 5 / 10 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 9 / 19 % | 0 / 0 % | 54 / 64 % | 15 / 40 % | 6 / 14 % | 2 / 8 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 45 / 62 % | 0 / 0 % | 45 / 59 % | 6 / 12 % | 0 / 0 % | 1 / 3 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 14 / 27 % | 42 / 61 % | 0 / 0 % | 14 / 22 % | 23 / 42 % | 21 / 38 % | 6 / 22 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 24 / 45 % | 24 / 58 % | 0 / 0 % | 37 / 52 % | 27 / 51 % | 14 / 29 % | 5 / 15 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 34 / 61 % | 0 / 0 % | 30 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 29 % | 31 / 60 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 7 / 13 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 28 / 68 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 27 / 59 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 28 % | 9 / 15 % | 2 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 3 / 6 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 4 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 1 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 6 / 11 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 3 % | 0 / 1 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 4 % | 0 / 0 % |
