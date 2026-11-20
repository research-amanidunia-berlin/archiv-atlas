[English](README.md) · [Deutsch](README.de.md)

# When AI builds itself

Report Q005401 · Source anthropic.com · Date – · [Open original](https://www.anthropic.com/institute/recursive-self-improvement)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, dass Claude bereits viel Code schreibe, Experimente beschleunige und bei manchen Forschungsentscheidungen besser werde; dadurch werde die menschliche Arbeit an der KI-Entwicklung schneller und verlagere sich stärker auf Zielwahl und Bewertung. Der Bericht sieht vollständige Selbstverbesserung als mögliche, aber nicht sichere Zukunft und nennt sowohl erhebliche Chancen als auch Kontrollrisiken. Die Zahlen stammen teilweise aus internen Daten, und mehrere Messungen sowie Vergleiche haben ausdrücklich benannte Grenzen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 74 / 84 % | 98 / 99 % | – | 100 / 100 % | 93 / 95 % | 94 / 97 % | 94 / 96 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 58 % | 98 / 100 % | – | 81 / 87 % | 46 / 74 % | 20 / 43 % | 69 / 83 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 40 % | 87 / 97 % | – | 97 / 99 % | 32 / 62 % | 23 / 47 % | 31 / 54 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 71 / 95 % | – | 96 / 98 % | 17 / 45 % | 3 / 14 % | 22 / 45 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 13 / 44 % | 86 / 98 % | – | 29 / 68 % | 59 / 82 % | 27 / 53 % | 65 / 80 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 18 / 45 % | 12 / 53 % | – | 83 / 94 % | 34 / 64 % | 15 / 38 % | 20 / 59 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 18 / 51 % | 56 / 95 % | – | 82 / 93 % | 41 / 67 % | 19 / 41 % | 27 / 45 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 11 / 41 % | 81 / 98 % | – | 29 / 56 % | 33 / 59 % | 7 / 28 % | 17 / 41 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 30 / 56 % | 79 / 97 % | – | 79 / 93 % | 77 / 89 % | 62 / 78 % | 74 / 86 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 58 % | 63 / 97 % | – | 76 / 90 % | 44 / 70 % | 15 / 46 % | 40 / 69 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 25 / 54 % | 75 / 98 % | – | 37 / 54 % | 52 / 76 % | 33 / 53 % | 40 / 67 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 25 / 58 % | 74 / 91 % | – | 57 / 85 % | 49 / 72 % | 37 / 61 % | 49 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 52 % | 55 / 99 % | – | 72 / 91 % | 43 / 67 % | 11 / 38 % | 29 / 57 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 31 / 60 % | 54 / 97 % | – | 72 / 92 % | 59 / 79 % | 45 / 68 % | 69 / 82 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 35 / 94 % | – | 69 / 83 % | 9 / 25 % | 0 / 0 % | 5 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 13 / 38 % | 66 / 99 % | – | 52 / 75 % | 12 / 35 % | 8 / 26 % | 12 / 27 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 43 % | 64 / 97 % | – | 14 / 38 % | 25 / 54 % | 5 / 15 % | 38 / 61 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 24 / 90 % | – | 50 / 72 % | 31 / 59 % | 9 / 25 % | 17 / 36 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 17 / 50 % | 28 / 96 % | – | 44 / 67 % | 29 / 51 % | 12 / 28 % | 47 / 63 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 43 / 87 % | – | 16 / 59 % | 21 / 48 % | 14 / 24 % | 26 / 44 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 24 / 56 % | 23 / 92 % | – | 19 / 40 % | 41 / 68 % | 13 / 36 % | 41 / 66 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 16 / 33 % | 38 / 98 % | – | 20 / 57 % | 21 / 46 % | 4 / 19 % | 10 / 25 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 12 / 45 % | 15 / 78 % | – | 0 / 0 % | 36 / 64 % | 10 / 30 % | 32 / 62 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 50 % | 33 / 97 % | – | 0 / 0 % | 11 / 30 % | 4 / 12 % | 11 / 24 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 17 / 45 % | – | 25 / 48 % | 7 / 18 % | 0 / 0 % | 7 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 7 / 24 % | 25 / 84 % | – | 1 / 16 % | 8 / 22 % | 5 / 18 % | 9 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 23 / 80 % | – | 3 / 23 % | 0 / 0 % | 2 / 7 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 23 / 56 % | – | 0 / 0 % | 8 / 22 % | 1 / 5 % | 10 / 22 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 16 / 93 % | – | 12 / 48 % | 22 / 54 % | 4 / 22 % | 16 / 47 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 22 / 74 % | – | 1 / 23 % | 0 / 0 % | 0 / 0 % | 5 / 16 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 5 / 48 % | – | 0 / 0 % | 20 / 45 % | 0 / 0 % | 18 / 33 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 11 / 94 % | – | 2 / 16 % | 16 / 47 % | 1 / 6 % | 18 / 31 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 29 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 49 % | – | 0 / 0 % | 9 / 27 % | 0 / 0 % | 10 / 16 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 10 / 85 % | – | 0 / 0 % | 7 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 10 / 18 % | 3 / 46 % | – | 0 / 0 % | 9 / 22 % | 1 / 5 % | 9 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 94 % | – | 0 / 0 % | 0 / 0 % | 0 / 3 % | 7 / 12 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 2 % | 9 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 9 / 28 % | 5 / 66 % | – | 1 / 14 % | 8 / 25 % | 4 / 13 % | 8 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 5 / 43 % | – | 9 / 38 % | 6 / 14 % | 1 / 5 % | 5 / 9 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 27 % | 4 / 10 % | 7 / 21 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 46 % | – | 0 / 0 % | 8 / 19 % | 1 / 3 % | 6 / 19 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 7 / 47 % | – | 0 / 0 % | 6 / 21 % | 0 / 0 % | 7 / 16 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 5 / 53 % | – | 0 / 0 % | 6 / 13 % | 1 / 3 % | 0 / 0 % |
