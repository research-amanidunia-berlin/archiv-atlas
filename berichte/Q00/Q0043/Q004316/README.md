[English](README.md) · [Deutsch](README.de.md)

# How Jump Trading is scaling quant research with ChatGPT

Report Q004316 · Source openai.com · Date 2026-10-06 · [Open original](https://openai.com/index/jump-trading/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Jump Trading berichtet, GPT‑6 Astra für Programmierung und umfangreiche quantitative Forschung einzusetzen; laut Lucas Baker können Agenten Analysen über längere Zeit durchführen und ihre Arbeit anhand vorgegebener Kriterien anpassen. Wegen möglicher finanzieller und regulatorischer Folgen setzt Jump nach seiner Darstellung auf klare Grenzen, Beobachtbarkeit und menschliche Prüfung. Die weitergehende autonome „Autoresearch“ ist eine Zukunftserwartung, und unabhängige Belege für die beschriebenen Erfolge enthält der Bericht nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 89 / 95 % | 100 / 100 % | 10 / 32 % | 11 / 26 % | 19 / 41 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 25 / 47 % | 93 / 96 % | 99 / 100 % | 43 / 68 % | 23 / 47 % | 53 / 69 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 48 % | 76 / 94 % | 99 / 100 % | 49 / 74 % | 44 / 71 % | 48 / 71 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 36 / 55 % | 94 / 98 % | 99 / 100 % | 68 / 85 % | 52 / 75 % | 61 / 77 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 42 / 67 % | 94 / 97 % | 10 / 31 % | 1 / 5 % | 11 / 23 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 66 / 97 % | 40 / 83 % | 11 / 33 % | 5 / 12 % | 11 / 33 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 15 / 32 % | 58 / 94 % | 40 / 68 % | 13 / 45 % | 2 / 11 % | 12 / 33 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 32 % | 43 / 87 % | 57 / 83 % | 19 / 49 % | 7 / 24 % | 12 / 36 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 26 / 44 % | 55 / 95 % | 57 / 85 % | 37 / 64 % | 13 / 26 % | 21 / 42 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 21 / 39 % | 55 / 92 % | 0 / 0 % | 12 / 40 % | 11 / 25 % | 18 / 43 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 36 % | 51 / 90 % | 40 / 78 % | 34 / 62 % | 28 / 55 % | 37 / 61 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 15 / 50 % | 38 / 55 % | 12 / 38 % | 2 / 6 % | 20 / 41 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 23 % | 25 / 64 % | 20 / 45 % | 4 / 13 % | 1 / 5 % | 5 / 14 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 22 / 42 % | 5 / 14 % | 0 / 2 % | 4 / 8 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 6 / 39 % | 16 / 41 % | 6 / 15 % | 1 / 5 % | 5 / 9 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 14 / 45 % | 6 / 17 % | 1 / 3 % | 5 / 12 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 14 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 4 / 7 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 12 / 33 % | 5 / 13 % | 1 / 5 % | 5 / 14 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 23 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 5 / 11 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 9 / 55 % | 0 / 0 % | 5 / 12 % | 0 / 1 % | 3 / 6 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 1 / 3 % | 6 / 15 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 7 / 18 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 2 / 7 % | 6 / 13 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 0 / 1 % | 2 / 5 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 2 % | 7 / 13 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 1 % | 5 / 11 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 6 / 16 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 5 % | 6 / 12 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 3 % | 5 / 12 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 3 / 6 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 1 % | 2 / 5 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 4 / 10 % | – | – |
