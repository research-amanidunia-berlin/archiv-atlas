[English](README.md) · [Deutsch](README.de.md)

# GPT-6.1 Sol hilft CodeRabbit, die Sicherheit komplexer Codebasen zu verbessern

Report Q009533 · Source openai.com · Date – · [Open original](https://openai.com/index/gpt-6-1-sol-coderabbit-code-security/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht zufolge nutzt CodeRabbit GPT‑6.1 Sol, um Sicherheitsrisiken über einzelne Codeänderungen hinaus zu erkennen und Repositorys samt Abhängigkeiten zu untersuchen. Das System kann ausgewählte Befunde in einer Sandbox prüfen und Korrekturvorschläge vorbereiten; Menschen behalten die Freigabe. Der Text nennt keine unabhängigen Wirksamkeitsnachweise oder konkreten Vergleichsdaten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 22 / 43 % | 43 / 78 % | 98 / 99 % | 45 / 68 % | 12 / 28 % | 22 / 44 % | 26 / 56 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 82 / 90 % | 5 / 10 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 58 / 86 % | 77 / 81 % | 15 / 39 % | 13 / 29 % | 11 / 25 % | 3 / 9 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 67 / 85 % | 10 / 27 % | 3 / 8 % | 7 / 15 % | 1 / 5 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 23 / 39 % | 8 / 51 % | 60 / 77 % | 25 / 52 % | 7 / 19 % | 21 / 46 % | 4 / 16 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 12 / 22 % | 30 / 64 % | 44 / 64 % | 10 / 29 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 21 / 40 % | 4 / 59 % | 22 / 30 % | 38 / 61 % | 20 / 37 % | 19 / 39 % | 5 / 13 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 5 / 39 % | 33 / 48 % | 6 / 20 % | 1 / 3 % | 5 / 10 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 14 / 35 % | 23 / 83 % | 12 / 49 % | 15 / 37 % | 4 / 11 % | 9 / 24 % | 1 / 8 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 19 / 32 % | 8 / 59 % | 0 / 0 % | 9 / 33 % | 7 / 19 % | 15 / 35 % | 1 / 5 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 19 / 35 % | 9 / 28 % | 4 / 13 % | 6 / 16 % | 1 / 5 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 16 / 67 % | 11 / 30 % | 7 / 20 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 10 / 30 % | 0 / 0 % | 12 / 32 % | 6 / 14 % | 16 / 27 % | 1 / 4 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 15 / 34 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 3 / 10 % | 6 / 15 % | 1 / 8 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 25 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 0 / 0 % | 13 / 28 % | 1 / 9 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 1 / 23 % | 13 / 29 % | 7 / 20 % | 1 / 4 % | 5 / 9 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 25 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 2 / 38 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 6 / 14 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 47 % | 0 / 0 % | 6 / 15 % | 1 / 5 % | 4 / 11 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 5 / 8 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 3 % | 4 / 7 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 4 / 9 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
