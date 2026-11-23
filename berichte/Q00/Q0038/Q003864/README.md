[English](README.md) · [Deutsch](README.de.md)

# Imitating Interactive Intelligence

Report Q003864 · Source deepmind.google · Date 2020-12-11 · [Open original](https://deepmind.google/blog/imitating-interactive-intelligence/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag stellt eine virtuelle Spielumgebung und ein kombiniertes Trainingsverfahren vor, mit denen KI-Agenten lernen sollen, sprachliche Anweisungen zu verstehen und gemeinsam mit Menschen zu handeln. Die berichteten Ergebnisse zeigen Verbesserungen durch zusätzliche Lernverfahren, doch Menschen waren in den gezeigten Aufgaben erfolgreicher und die Agenten scheiterten noch an vielen Aufgaben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 80 / 93 % | 95 / 98 % | 10 / 30 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 39 % | 34 / 89 % | 85 / 93 % | 13 / 42 % | 2 / 10 % | 10 / 28 % | 1 / 7 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 7 / 39 % | 59 / 82 % | 9 / 29 % | 1 / 11 % | 7 / 22 % | 1 / 7 % | 16 / 32 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 22 % | 56 / 91 % | 10 / 26 % | 9 / 27 % | 1 / 6 % | 5 / 12 % | 0 / 4 % | 10 / 30 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 8 / 75 % | 23 / 51 % | 11 / 29 % | 1 / 7 % | 4 / 12 % | 1 / 10 % | 14 / 39 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 22 / 95 % | 0 / 0 % | 8 / 35 % | 1 / 11 % | 7 / 19 % | 0 / 4 % | 18 / 39 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 21 / 58 % | 0 / 0 % | 6 / 15 % | 1 / 7 % | 4 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 21 / 73 % | 0 / 0 % | 13 / 41 % | 2 / 11 % | 9 / 27 % | 1 / 7 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 13 / 81 % | 12 / 38 % | 12 / 36 % | 2 / 13 % | 7 / 27 % | 1 / 6 % | 20 / 39 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 12 / 69 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 9 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 11 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 9 / 42 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 3 / 13 % | 0 / 0 % | 9 / 28 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 14 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 1 / 6 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 20 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 2 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 24 % | 2 / 13 % | 6 / 20 % | 1 / 7 % | 2 / 9 % | 0 / 3 % | 3 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
