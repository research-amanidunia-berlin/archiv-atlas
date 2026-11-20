[English](README.md) · [Deutsch](README.de.md)

# Watermarking AI-generated text and video with SynthID

Report Q004068 · Source deepmind.google · Date 2024-05-14 · [Open original](https://deepmind.google/blog/watermarking-ai-generated-text-and-video-with-synthid/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google beschreibt SynthID als unsichtbare Wasserzeichen für KI-generierte Texte und Videos: Bei Texten wird ein Muster über Token-Wahrscheinlichkeiten eingebettet, bei Videos in die Pixel jedes Einzelbilds. Laut Bericht ist die Erkennung unter anderem bei stark umgeschriebenen oder übersetzten Texten sowie bei kurzen sachlichen Antworten eingeschränkt; der bereitgestellte Text endet zudem mit einer abgebrochenen Bildbeschreibung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 73 / 82 % | 98 / 100 % | 99 / 100 % | 99 / 100 % | 89 / 93 % | 90 / 93 % | 90 / 93 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 26 / 48 % | 38 / 79 % | 9 / 13 % | 90 / 96 % | 36 / 55 % | 23 / 34 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 38 / 54 % | 85 / 99 % | 6 / 14 % | 70 / 89 % | 18 / 43 % | 13 / 28 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 21 / 38 % | 42 / 82 % | 2 / 8 % | 83 / 92 % | 11 / 30 % | 14 / 31 % | 4 / 15 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 15 / 44 % | 0 / 0 % | 72 / 81 % | 7 / 18 % | 13 / 27 % | 3 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 22 / 38 % | 6 / 71 % | 0 / 0 % | 72 / 81 % | 13 / 29 % | 8 / 16 % | 3 / 10 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 27 / 43 % | 0 / 0 % | 0 / 0 % | 66 / 82 % | 10 / 25 % | 6 / 12 % | 3 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 59 / 68 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 53 / 64 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 15 / 27 % | 33 / 66 % | 0 / 3 % | 43 / 75 % | 7 / 23 % | 8 / 24 % | 3 / 13 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 36 / 54 % | 0 / 0 % | 7 / 13 % | 24 / 36 % | 16 / 36 % | 0 / 0 % | 11 / 23 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 27 / 45 % | 0 / 0 % | 0 / 0 % | 35 / 53 % | 7 / 23 % | 7 / 20 % | 4 / 12 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 10 / 44 % | 0 / 0 % | 35 / 64 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 47 % | 11 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 10 / 44 % | 0 / 0 % | 21 / 41 % | 6 / 12 % | 5 / 10 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 17 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 29 % | 15 / 46 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 4 / 6 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 40 % | 5 / 13 % | 2 / 7 % | 1 / 6 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 12 / 81 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 1 / 6 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 10 / 25 % | 8 / 21 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 4 / 8 % | 2 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 6 / 38 % | 0 / 0 % | 3 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 5 / 9 % | 1 / 7 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 1 / 6 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 4 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 2 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 6 % | 0 / 0 % |
