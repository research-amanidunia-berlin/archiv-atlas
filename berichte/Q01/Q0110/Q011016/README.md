[English](README.md) · [Deutsch](README.de.md)

# Meta’s New Local AI Agent Hallucinates 82% of the Time

Report Q011016 · Source medium.com · Date 2026-08-15 · [Open original](https://medium.com/data-science-collective/metas-new-local-ai-agent-hallucinates-82-of-the-time-04cf80c09013)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht würdigt Muse Glimmers kompakte Bauweise und seine guten Ergebnisse bei der Werkzeugauswahl, kritisiert aber eine laut Artificial Analysis sehr hohe Halluzinationsrate von 82 Prozent. Der Autor hält das Modell deshalb für unbeaufsichtigte Arbeit mit persönlichen Dateien für zu riskant, räumt jedoch ein, dass der Bericht keine Tests mit Abrufsystemen und strenger Werkzeugvalidierung enthält.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 49 % | 77 / 97 % | 26 / 67 % | 100 / 100 % | 52 / 75 % | 20 / 50 % | 46 / 68 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 31 / 50 % | 18 / 70 % | 12 / 32 % | 93 / 95 % | 35 / 62 % | 14 / 38 % | 25 / 52 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 40 % | 40 / 75 % | 3 / 12 % | 92 / 97 % | 42 / 68 % | 10 / 26 % | 15 / 30 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 48 % | 51 / 86 % | 9 / 31 % | 92 / 96 % | 36 / 63 % | 25 / 49 % | 41 / 66 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 25 / 47 % | 77 / 95 % | 26 / 67 % | 91 / 97 % | 58 / 78 % | 18 / 45 % | 29 / 55 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 32 % | 3 / 36 % | 2 / 8 % | 90 / 92 % | 26 / 51 % | 9 / 22 % | 27 / 45 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 14 / 34 % | 57 / 84 % | 1 / 5 % | 90 / 95 % | 11 / 30 % | 2 / 8 % | 7 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 62 / 91 % | 0 / 2 % | 88 / 93 % | 12 / 33 % | 4 / 15 % | 16 / 28 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 28 / 52 % | 55 / 90 % | 12 / 28 % | 86 / 95 % | 46 / 69 % | 13 / 33 % | 35 / 47 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 24 / 77 % | 0 / 0 % | 84 / 90 % | 7 / 14 % | 2 / 7 % | 6 / 11 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 83 / 88 % | 20 / 43 % | 3 / 10 % | 8 / 15 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 22 / 41 % | 25 / 69 % | 2 / 5 % | 81 / 87 % | 13 / 33 % | 4 / 14 % | 11 / 20 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 26 / 45 % | 43 / 80 % | 11 / 31 % | 75 / 84 % | 49 / 73 % | 17 / 45 % | 43 / 65 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 14 / 31 % | 0 / 0 % | 0 / 0 % | 48 / 54 % | 8 / 19 % | 2 / 8 % | 11 / 21 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 22 / 47 % | 8 / 32 % | 9 / 30 % | 43 / 65 % | 18 / 45 % | 10 / 27 % | 24 / 51 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 35 % | 30 / 87 % | 2 / 8 % | 14 / 38 % | 22 / 47 % | 11 / 30 % | 14 / 28 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 50 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 36 % | 0 / 0 % | 26 / 41 % | 14 / 36 % | 8 / 18 % | 16 / 32 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 40 % | 7 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 13 / 29 % | 0 / 0 % | 1 / 7 % | 8 / 26 % | 19 / 42 % | 4 / 12 % | 8 / 18 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 16 / 40 % | 4 / 10 % | 10 / 17 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 3 / 8 % | 11 / 19 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 30 % | 4 / 31 % | 0 / 1 % | 0 / 0 % | 7 / 16 % | 1 / 4 % | 8 / 15 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 12 / 23 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 12 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 6 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 10 / 22 % | 10 / 25 % | 4 / 14 % | 6 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 9 / 16 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 8 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 5 % | 5 / 8 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 2 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 5 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 7 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 0 / 0 % |
