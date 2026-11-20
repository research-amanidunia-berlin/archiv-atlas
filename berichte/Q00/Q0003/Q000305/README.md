[English](README.md) · [Deutsch](README.de.md)

# Introducing Claude Fable 5.2 and Claude Mythos 5.2

Report Q000305 · Source anthropic.com · Date 2026-11-09 · [Open original](https://www.anthropic.com/claude-fable-and-mythos-5-2)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge verbessert Claude Fable 5.2 und Mythos 5.2 Ergebnisse bei Programmierung, wissenschaftlichen Aufgaben und Robotik; der Bericht nennt dazu Beispiele und Benchmarks, die überwiegend vom Unternehmen selbst stammen. Anthropic beschreibt mehrere Schutzmaßnahmen, räumt aber ein, dass Sicherheitsprüfungen nicht alle Fehler erfassen und manche Vergleichswerte nur unter besonderen Testbedingungen gelten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 45 / 64 % | 100 / 100 % | – | 99 / 100 % | 82 / 90 % | 79 / 89 % | 80 / 89 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 48 / 65 % | 76 / 91 % | – | 100 / 100 % | 81 / 90 % | 54 / 77 % | 83 / 93 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 54 / 70 % | 99 / 100 % | – | 99 / 100 % | 63 / 77 % | 43 / 61 % | 81 / 89 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 30 / 46 % | 99 / 100 % | – | 95 / 96 % | 71 / 85 % | 19 / 35 % | 50 / 67 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 60 % | 99 / 100 % | – | 98 / 99 % | 75 / 87 % | 71 / 85 % | 84 / 92 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 33 / 55 % | 81 / 98 % | – | 97 / 99 % | 70 / 84 % | 13 / 32 % | 63 / 77 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 47 / 66 % | 84 / 98 % | – | 96 / 97 % | 86 / 92 % | 83 / 92 % | 92 / 96 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 45 / 83 % | – | 89 / 94 % | 18 / 44 % | 9 / 21 % | 21 / 33 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 57 / 72 % | 85 / 94 % | – | 44 / 75 % | 82 / 89 % | 62 / 73 % | 89 / 92 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 26 / 46 % | 88 / 99 % | – | 87 / 92 % | 38 / 64 % | 14 / 25 % | 44 / 61 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 35 / 55 % | 86 / 98 % | – | 74 / 84 % | 77 / 88 % | 34 / 55 % | 77 / 86 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 41 % | 11 / 42 % | – | 83 / 86 % | 49 / 73 % | 10 / 24 % | 59 / 74 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 29 / 61 % | – | 81 / 89 % | 49 / 72 % | 11 / 24 % | 14 / 30 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 35 / 82 % | – | 81 / 88 % | 15 / 38 % | 3 / 11 % | 9 / 15 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 54 / 85 % | – | 79 / 88 % | 37 / 58 % | 18 / 33 % | 24 / 36 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 27 / 70 % | – | 70 / 78 % | 9 / 26 % | 2 / 8 % | 6 / 14 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 50 / 82 % | – | 70 / 81 % | 10 / 28 % | 2 / 8 % | 9 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 26 / 49 % | 32 / 89 % | – | 12 / 27 % | 43 / 66 % | 21 / 42 % | 69 / 81 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 38 / 57 % | 36 / 78 % | – | 68 / 83 % | 60 / 80 % | 12 / 29 % | 37 / 53 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 58 / 90 % | – | 66 / 77 % | 30 / 55 % | 5 / 15 % | 14 / 30 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 65 / 97 % | – | 39 / 67 % | 43 / 72 % | 11 / 31 % | 27 / 61 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 30 / 51 % | 63 / 93 % | – | 49 / 61 % | 39 / 64 % | 13 / 25 % | 41 / 55 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 59 / 76 % | 7 / 22 % | 2 / 8 % | 7 / 15 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 16 / 28 % | 35 / 70 % | – | 41 / 56 % | 12 / 34 % | 3 / 10 % | 6 / 14 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 22 / 48 % | 0 / 0 % | – | 0 / 0 % | 41 / 66 % | 13 / 28 % | 15 / 30 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 18 / 35 % | 39 / 77 % | – | 32 / 37 % | 38 / 58 % | 9 / 21 % | 37 / 49 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 31 % | 0 / 0 % | – | 0 / 0 % | 14 / 36 % | 4 / 14 % | 15 / 28 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 0 / 0 % | 14 / 24 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 14 / 43 % | – | 3 / 18 % | 12 / 30 % | 3 / 9 % | 6 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 34 % | 1 / 5 % | 12 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 32 % | 1 / 6 % | 7 / 15 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 5 / 33 % | – | 0 / 0 % | 11 / 30 % | 5 / 11 % | 7 / 14 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 21 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 22 % | 1 / 3 % | 9 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 5 / 30 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 9 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 18 % | 0 / 0 % | 8 / 23 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 6 / 20 % | 7 / 18 % | 0 / 0 % | 6 / 12 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 1 / 3 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 1 / 7 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 3 / 6 % | 6 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 1 / 2 % | 5 / 8 % |
