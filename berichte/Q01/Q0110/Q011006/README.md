[English](README.md) · [Deutsch](README.de.md)

# GPT-6 Astra Has a 1.05 Million Token Context Window. Past 272,000 Tokens It Bills You Double.

Report Q011006 · Source medium.com · Date 2026-09-05 · [Open original](https://medium.com/codetodeploy/gpt-6-astra-has-a-1-05-million-token-context-window-past-272-000-tokens-it-bills-you-double-e46fb60d2ec1)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht behauptet, Astra sei vor allem bei langen, werkzeugintensiven Aufgaben stärker, doch ab 272.000 Eingabe-Tokens gelte für den gesamten Auftrag ein deutlich höherer Preis. Er hebt ein experimentelles Notizsystem hervor und beschreibt Benchmarks als gemischt; einige Werte seien nur eingeschränkt vergleichbar, und OpenAI habe keine GDPval-Punktzahl veröffentlicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 54 % | 94 / 97 % | 49 / 67 % | 100 / 100 % | 66 / 84 % | 74 / 86 % | 43 / 62 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 47 % | 77 / 97 % | 17 / 45 % | 100 / 100 % | 61 / 81 % | 54 / 74 % | 16 / 39 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 35 / 54 % | 97 / 100 % | 35 / 55 % | 100 / 100 % | 64 / 82 % | 40 / 58 % | 14 / 34 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 41 % | 64 / 87 % | 12 / 26 % | 97 / 98 % | 44 / 70 % | 46 / 62 % | 19 / 35 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 31 / 49 % | 83 / 94 % | 17 / 30 % | 96 / 98 % | 68 / 83 % | 73 / 84 % | 39 / 59 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 43 / 61 % | 76 / 90 % | 61 / 75 % | 92 / 97 % | 71 / 85 % | 73 / 84 % | 32 / 51 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 25 / 41 % | 76 / 92 % | 12 / 24 % | 89 / 94 % | 44 / 69 % | 25 / 50 % | 14 / 29 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 34 / 49 % | 83 / 92 % | 59 / 65 % | 89 / 92 % | 64 / 81 % | 58 / 70 % | 34 / 49 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 36 / 55 % | 35 / 78 % | 11 / 24 % | 87 / 91 % | 67 / 85 % | 35 / 52 % | 15 / 30 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 16 / 31 % | 39 / 83 % | 3 / 11 % | 83 / 88 % | 14 / 38 % | 8 / 20 % | 5 / 16 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 37 / 65 % | 2 / 9 % | 76 / 85 % | 9 / 27 % | 7 / 17 % | 2 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 29 / 49 % | 71 / 94 % | 17 / 29 % | 66 / 77 % | 58 / 79 % | 40 / 61 % | 17 / 37 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 17 / 47 % | 0 / 0 % | 68 / 77 % | 10 / 28 % | 11 / 27 % | 1 / 7 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 62 / 91 % | 5 / 14 % | 57 / 68 % | 26 / 53 % | 21 / 40 % | 5 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 54 / 84 % | 0 / 2 % | 50 / 68 % | 7 / 21 % | 10 / 18 % | 1 / 6 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 25 / 41 % | 26 / 56 % | 6 / 21 % | 37 / 55 % | 42 / 67 % | 26 / 44 % | 8 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 42 % | 41 / 75 % | 1 / 5 % | 16 / 28 % | 11 / 32 % | 11 / 22 % | 2 / 12 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 28 / 41 % | 10 / 33 % | 5 / 14 % | 3 / 11 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 54 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 15 / 36 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 16 / 41 % | 23 / 48 % | 4 / 11 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 4 / 12 % | 0 / 0 % | 23 / 49 % | 15 / 29 % | 4 / 10 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 18 / 41 % | 0 / 2 % | 0 / 0 % | 6 / 15 % | 5 / 11 % | 2 / 8 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 31 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 15 % | 9 / 16 % | 1 / 4 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 9 / 21 % | 12 / 21 % | 2 / 9 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 15 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 11 / 29 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 9 / 28 % | 9 / 18 % | 2 / 5 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 6 / 11 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 5 / 9 % | 0 / 2 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 8 / 37 % | 1 / 4 % | 2 / 11 % | 9 / 22 % | 6 / 12 % | 2 / 7 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 9 / 21 % | 5 / 9 % | 2 / 6 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 8 / 13 % | 0 / 1 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 5 / 9 % | 0 / 2 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 6 / 11 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 7 / 41 % | 0 / 3 % | 0 / 0 % | 6 / 17 % | 5 / 10 % | 3 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 1 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 8 % | 7 / 14 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 7 / 12 % | 1 / 4 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 7 / 21 % | 5 / 11 % | 2 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 4 / 6 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 6 / 12 % | 3 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 2 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 6 / 10 % | 1 / 4 % |
