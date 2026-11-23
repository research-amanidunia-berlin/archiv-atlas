[English](README.md) · [Deutsch](README.de.md)

# Progress on provable inference for large language models

Report Q000472 · Source anthropic.com · Date 2026-11-02 · [Open original](https://www.anthropic.com/research/provable-inference)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic beschreibt FlashProve, einen Forschungsprototyp, der mit kryptografischen Beweisen die Verwendung festgelegter Modellgewichte bei Sprachmodellantworten nachweisen soll, ohne die Gewichte offenzulegen. Die Autoren berichten für Llama 4 Maverick rund 110 Tokens pro Sekunde und Beweise von etwa 19 MB, nennen aber Einschränkungen: getestet wird eine Ganzzahlversion mit Greedy-Decoding, derzeit für Kontexte bis 1.024 Tokens; Architekturverbergung und Schutz vor Seitenkanälen sind nicht enthalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 48 / 66 % | 62 / 88 % | 97 / 98 % | 58 / 78 % | 43 / 60 % | 43 / 61 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 47 % | 83 / 96 % | 91 / 97 % | 29 / 55 % | 9 / 23 % | 21 / 40 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 40 / 57 % | 76 / 94 % | 25 / 39 % | 46 / 69 % | 27 / 44 % | 71 / 80 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 36 / 60 % | 69 / 87 % | 38 / 57 % | 65 / 83 % | 50 / 65 % | 76 / 86 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 44 / 66 % | 42 / 83 % | 76 / 90 % | 51 / 74 % | 49 / 69 % | 65 / 79 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 23 / 46 % | 45 / 69 % | 76 / 85 % | 21 / 40 % | 7 / 15 % | 17 / 27 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 39 / 61 % | 74 / 88 % | 74 / 83 % | 27 / 52 % | 34 / 52 % | 30 / 44 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 60 / 93 % | 70 / 83 % | 8 / 24 % | 2 / 9 % | 5 / 14 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 65 / 93 % | 58 / 81 % | 14 / 40 % | 4 / 12 % | 17 / 36 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 62 / 78 % | 12 / 32 % | 4 / 11 % | 6 / 14 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 36 / 77 % | 60 / 75 % | 47 / 66 % | 54 / 70 % | 56 / 70 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 60 / 85 % | 59 / 82 % | 9 / 26 % | 2 / 8 % | 6 / 18 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 59 / 88 % | 18 / 47 % | 24 / 52 % | 10 / 19 % | 14 / 34 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 35 / 58 % | 45 / 77 % | 57 / 77 % | 55 / 75 % | 40 / 59 % | 54 / 72 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 56 / 84 % | 12 / 33 % | 3 / 11 % | 9 / 30 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 52 / 72 % | 0 / 0 % | 11 / 29 % | 3 / 9 % | 12 / 26 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 51 / 80 % | 52 / 70 % | 13 / 32 % | 5 / 12 % | 16 / 37 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 46 / 65 % | 50 / 63 % | 24 / 49 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 41 % | 49 / 78 % | 20 / 35 % | 24 / 49 % | 8 / 23 % | 22 / 47 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 37 / 56 % | 30 / 60 % | 30 / 60 % | 24 / 49 % | 16 / 28 % | 22 / 41 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 35 / 78 % | 36 / 55 % | 34 / 59 % | 8 / 19 % | 23 / 46 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 35 / 78 % | 1 / 15 % | 8 / 21 % | 4 / 12 % | 8 / 24 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 31 / 70 % | 26 / 57 % | 7 / 21 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 28 / 60 % | 15 / 42 % | 23 / 49 % | 8 / 17 % | 14 / 30 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 25 / 53 % | 26 / 42 % | 15 / 36 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 17 / 41 % | 25 / 46 % | 7 / 24 % | 9 / 24 % | 5 / 13 % | 9 / 18 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 25 / 55 % | 0 / 0 % | 12 / 30 % | 8 / 17 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 41 % | 0 / 0 % | 7 / 16 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 21 / 53 % | 0 / 0 % | 9 / 16 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 17 / 52 % | 0 / 0 % | 10 / 23 % | 0 / 0 % | 9 / 15 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 16 / 48 % | 12 / 32 % | 6 / 12 % | 7 / 20 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 32 % | 3 / 7 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 13 / 28 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 11 / 20 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 0 / 0 % | 6 / 15 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 7 / 19 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 3 / 8 % | 0 / 0 % | – | – |
