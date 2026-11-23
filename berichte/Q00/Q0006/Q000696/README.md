[English](README.md) · [Deutsch](README.de.md)

# Reasoning or Rationalization? Moral Robustness as a Frontier for Non-Verifiable Reasoning in LLMs

Report Q000696 · Source deepmind.google · Date 2026-06-10 · [Open original](https://deepmind.google/research/publications/250558/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht liegt nur als Abstract-Auszug vor. Darin berichten die Forschenden, dass zehn Sprachmodelle in 128.000 simulierten moralischen Beratungen zwar irrelevante Ablenkungen ignorierten, ihre Urteile und Begründungen aber teils an Nutzerposition, Argumentreihenfolge und Gesprächsdauer anpassten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 51 / 72 % | 98 / 100 % | 100 / 100 % | 83 / 91 % | 81 / 89 % | 83 / 89 % | 87 / 93 % | 53 / 71 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 44 / 64 % | 83 / 96 % | 98 / 99 % | 78 / 87 % | 76 / 86 % | 80 / 87 % | 79 / 91 % | 32 / 55 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 54 % | 56 / 86 % | 96 / 98 % | 32 / 61 % | 8 / 20 % | 17 / 36 % | 5 / 23 % | 26 / 44 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 78 / 84 % | 13 / 34 % | 5 / 14 % | 8 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 48 % | 36 / 62 % | 72 / 83 % | 20 / 49 % | 8 / 18 % | 16 / 32 % | 5 / 22 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 52 / 75 % | 7 / 21 % | 0 / 2 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 36 / 52 % | 10 / 28 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 31 / 57 % | 8 / 23 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 7 / 45 % | 28 / 49 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 24 / 54 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 25 % | 0 / 0 % | 5 / 11 % | 1 / 9 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 10 / 26 % | 9 / 26 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 10 / 47 % | 0 / 0 % | 6 / 15 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 2 / 6 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 4 / 6 % | 0 / 0 % | 0 / 0 % |
