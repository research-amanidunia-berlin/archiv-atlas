[English](README.md) · [Deutsch](README.de.md)

# Security incident disclosure

Report Q005089 · Source huggingface.co · Date 2026-07-16 · [Open original](https://huggingface.co/blog/security-incident-july-2026)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Hugging Face zufolge drang ein autonomes KI-Agentensystem über zwei Schwachstellen in der Dataset-Verarbeitung in Teile der Produktionsinfrastruktur ein und erlangte Zugriff auf interne Datensätze und Dienstzugangsdaten. Das Unternehmen schloss die Schwachstellen, erneuerte Zugangsdaten und untersuchte mögliche Auswirkungen auf Partner- und Kundendaten, die noch nicht abschließend geklärt waren. Für die Analyse des Angriffsprotokolls nutzte es ein offenes Modell auf eigener Infrastruktur.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 47 % | 86 / 96 % | 16 / 54 % | 100 / 100 % | 44 / 69 % | 43 / 69 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 48 / 70 % | 93 / 97 % | 76 / 94 % | 100 / 100 % | 79 / 88 % | 78 / 88 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 48 / 70 % | 77 / 95 % | 65 / 85 % | 99 / 100 % | 76 / 88 % | 75 / 87 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 49 / 66 % | 57 / 85 % | 61 / 88 % | 98 / 99 % | 71 / 86 % | 77 / 88 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 24 / 53 % | 62 / 88 % | 17 / 61 % | 89 / 96 % | 60 / 78 % | 33 / 59 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 20 / 47 % | 3 / 14 % | 85 / 92 % | 32 / 56 % | 11 / 30 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 15 / 38 % | 41 / 91 % | 1 / 7 % | 85 / 92 % | 12 / 30 % | 9 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 1 / 8 % | 81 / 93 % | 16 / 41 % | 6 / 12 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 34 / 54 % | 54 / 77 % | 10 / 31 % | 73 / 85 % | 42 / 66 % | 47 / 72 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 58 / 70 % | 12 / 33 % | 8 / 17 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 9 % | 52 / 81 % | 6 / 21 % | 5 / 13 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 52 / 81 % | 11 / 31 % | 7 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 24 / 48 % | 44 / 77 % | 6 / 20 % | 11 / 37 % | 36 / 61 % | 51 / 72 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 50 / 76 % | 7 / 18 % | 4 / 7 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 53 % | 17 / 72 % | 2 / 11 % | 0 / 0 % | 18 / 44 % | 48 / 71 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 17 / 48 % | 37 / 80 % | 14 / 37 % | 46 / 80 % | 28 / 53 % | 23 / 41 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 36 % | 45 / 77 % | 1 / 7 % | 42 / 75 % | 12 / 32 % | 11 / 26 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 27 / 46 % | 0 / 0 % | 39 / 51 % | 9 / 21 % | 10 / 20 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 26 / 74 % | 1 / 7 % | 37 / 68 % | 12 / 36 % | 8 / 26 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 23 / 53 % | 4 / 13 % | 0 / 0 % | 18 / 41 % | 30 / 54 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 22 / 49 % | 25 / 95 % | 12 / 68 % | 12 / 68 % | 28 / 56 % | 14 / 37 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 11 / 40 % | 24 / 64 % | 3 / 23 % | 16 / 59 % | 6 / 17 % | 9 / 21 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 23 / 64 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 4 / 10 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 2 / 9 % | 0 / 0 % | 16 / 38 % | 17 / 30 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 14 / 61 % | 5 / 39 % | 16 / 55 % | 17 / 44 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 13 / 40 % | 12 / 30 % | 8 / 17 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 11 / 41 % | 0 / 0 % | 1 / 7 % | 0 / 0 % | 12 / 33 % | 6 / 17 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 9 / 24 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 6 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 8 / 15 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 8 / 15 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 8 / 24 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 5 / 13 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 6 / 14 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % |
