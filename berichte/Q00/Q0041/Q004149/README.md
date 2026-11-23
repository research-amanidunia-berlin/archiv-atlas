[English](README.md) · [Deutsch](README.de.md)

# Techniques to Make Large Language Models Smaller: An Explainer

Report Q004149 · Source cset.georgetown.edu · Date 2023-10-11 · [Open original](https://cset.georgetown.edu/publication/techniques-to-make-large-language-models-smaller-an-explainer/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Textauszug beschreibt drei Wege, große Sprachmodelle zu verkleinern: Parameter mit weniger Bits darstellen, Wissen durch Ausgaben eines großen Modells auf ein kleineres übertragen und wenig wichtige Parameter entfernen. Kleinere offene Modelle seien meist weniger leistungsfähig, könnten aber Forschung und Zugang erleichtern; zugleich könnten ihre zunehmende Verbreitung und die unklare Übertragbarkeit allgemeiner Fähigkeiten Kontrolle und Regulierung erschweren. Vier zusätzlich angekündigte Effizienzverfahren werden im Auszug nicht erläutert.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 28 / 53 % | 83 / 99 % | 98 / 100 % | 25 / 57 % | 9 / 29 % | 13 / 39 % | 15 / 58 % | 47 / 73 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 14 / 37 % | 50 / 95 % | 24 / 61 % | 34 / 61 % | 14 / 25 % | 16 / 34 % | 10 / 22 % | 6 / 22 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 24 / 52 % | 41 / 87 % | 6 / 52 % | 36 / 64 % | 5 / 19 % | 19 / 42 % | 19 / 51 % | 18 / 52 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 23 / 52 % | 31 / 90 % | 39 / 85 % | 23 / 51 % | 7 / 23 % | 11 / 37 % | 7 / 46 % | 40 / 67 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 13 / 34 % | 17 / 90 % | 27 / 69 % | 9 / 28 % | 2 / 12 % | 6 / 21 % | 2 / 11 % | 39 / 65 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 33 / 77 % | 14 / 51 % | 6 / 21 % | 0 / 5 % | 7 / 20 % | 0 / 3 % | 17 / 45 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 28 / 70 % | 7 / 29 % | 3 / 16 % | 5 / 18 % | 3 / 15 % | 4 / 20 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 27 / 78 % | 0 / 3 % | 5 / 11 % | 1 / 9 % | 4 / 9 % | 0 / 0 % | 3 / 17 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 9 / 99 % | 26 / 78 % | 11 / 35 % | 4 / 16 % | 5 / 18 % | 1 / 9 % | 10 / 34 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 24 / 73 % | 18 / 63 % | 8 / 24 % | 2 / 14 % | 4 / 14 % | 0 / 3 % | 10 / 33 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 18 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 15 / 68 % | 16 / 46 % | 9 / 35 % | 2 / 11 % | 7 / 19 % | 1 / 7 % | 11 / 29 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 16 / 73 % | 3 / 24 % | 6 / 17 % | 1 / 7 % | 2 / 8 % | 0 / 4 % | 16 / 42 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 36 % | 5 / 57 % | 1 / 15 % | 7 / 22 % | 1 / 7 % | 7 / 14 % | 1 / 7 % | 6 / 26 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 12 / 43 % | 14 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 13 / 68 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 2 / 8 % | 0 / 2 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 53 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 5 / 9 % | 0 / 0 % | 2 / 11 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 4 / 67 % | 1 / 22 % | 7 / 21 % | 2 / 9 % | 8 / 18 % | 0 / 5 % | 4 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 7 / 35 % | 0 / 0 % | 5 / 12 % | 1 / 7 % | 3 / 8 % | 0 / 0 % | 3 / 15 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 5 / 65 % | 0 / 0 % | 6 / 17 % | 1 / 5 % | 4 / 12 % | 0 / 2 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 6 / 13 % | 0 / 3 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 3 / 65 % | 4 / 30 % | 6 / 18 % | 2 / 9 % | 4 / 9 % | 0 / 4 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 2 / 9 % | 4 / 10 % | 1 / 9 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 6 / 66 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 4 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 4 / 10 % | 0 / 2 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 49 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 5 / 22 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 2 / 5 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 4 % | 3 / 6 % | 0 / 4 % | 0 / 0 % |
