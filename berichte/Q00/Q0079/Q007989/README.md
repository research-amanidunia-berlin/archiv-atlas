[English](README.md) · [Deutsch](README.de.md)

# From model to agent: Equipping the Responses API with a computer environment

Report Q007989 · Source openai.com · Date 2026-03-11 · [Open original](https://openai.com/index/equip-responses-api-computer-environment/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag beschreibt OpenAIs Kombination aus Responses API, Shell-Werkzeug, Container, kontrolliertem Netzwerk, wiederverwendbaren Skills und Kontextkomprimierung für längere Agentenabläufe. Die behaupteten Vorteile für Effizienz, Skalierbarkeit und Sicherheit werden im Text nicht durch unabhängige Prüfungen oder quantitative Vergleiche belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 54 / 75 % | 88 / 98 % | – | 100 / 100 % | 76 / 88 % | 74 / 85 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 48 % | 68 / 97 % | – | 99 / 100 % | 42 / 70 % | 38 / 62 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 21 / 46 % | 85 / 95 % | – | 69 / 76 % | 33 / 59 % | 32 / 49 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 25 / 49 % | 74 / 98 % | – | 37 / 62 % | 47 / 72 % | 58 / 77 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 19 / 78 % | – | 72 / 86 % | 7 / 24 % | 5 / 10 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 15 / 40 % | 32 / 94 % | – | 68 / 81 % | 34 / 61 % | 23 / 49 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 43 / 93 % | – | 0 / 0 % | 6 / 14 % | 2 / 4 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 34 / 91 % | – | 17 / 47 % | 8 / 20 % | 6 / 13 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 32 / 72 % | – | 30 / 50 % | 4 / 11 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 20 / 43 % | 0 / 0 % | – | 0 / 0 % | 6 / 25 % | 11 / 23 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 17 / 55 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 16 / 56 % | – | 0 / 0 % | 0 / 0 % | 2 / 4 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 14 / 48 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 13 / 90 % | – | 0 / 0 % | 7 / 25 % | 5 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 12 / 65 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 11 / 72 % | – | 7 / 27 % | 6 / 14 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 23 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 25 % | 9 / 16 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 92 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 6 / 12 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 4 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 2 % |
