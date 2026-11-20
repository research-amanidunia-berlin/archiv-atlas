[English](README.md) · [Deutsch](README.de.md)

# Trustworthy AI for the enterprise: How to train an LLM to follow a code of conduct

Report Q004742 · Source oecd.ai · Date 2024-12-18 · [Open original](https://oecd.ai/en/wonk/how-to-train-an-llm-to-follow-a-code-of-conduct)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AI21 beschreibt, wie das Unternehmen OECD-KI-Prinzipien in 60 konkrete Verhaltensregeln überführt und seine Jamba-1.5-Modelle mit Angriffsprompts sowie menschlichem Feedback daran ausrichtet. Der Artikel stellt den Kodex als anpassbar dar, nennt aber keine zusammengefassten Testergebnisse oder unabhängigen Belege für seine Wirksamkeit; vorliegend ist der vollständige Artikel, kein Auszug oder eine Fehlerseite.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 63 / 75 % | 100 / 100 % | 84 / 94 % | 100 / 100 % | 88 / 93 % | 73 / 86 % | 80 / 88 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 59 % | 90 / 96 % | 56 / 80 % | 99 / 100 % | 66 / 83 % | 58 / 76 % | 67 / 80 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 47 / 64 % | 98 / 99 % | 77 / 89 % | 99 / 100 % | 81 / 90 % | 65 / 81 % | 77 / 86 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 33 / 51 % | 67 / 91 % | 8 / 27 % | 95 / 98 % | 57 / 77 % | 12 / 30 % | 19 / 34 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 41 / 61 % | 95 / 99 % | 52 / 76 % | 94 / 98 % | 64 / 81 % | 58 / 76 % | 57 / 74 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 87 / 98 % | 1 / 6 % | 78 / 90 % | 25 / 51 % | 8 / 28 % | 15 / 30 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 33 / 57 % | 53 / 85 % | 25 / 49 % | 87 / 94 % | 16 / 38 % | 15 / 36 % | 20 / 42 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 73 / 89 % | 1 / 8 % | 83 / 91 % | 15 / 38 % | 5 / 17 % | 11 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 41 / 76 % | 0 / 0 % | 75 / 86 % | 9 / 24 % | 3 / 10 % | 10 / 19 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 22 / 46 % | 53 / 89 % | 3 / 15 % | 68 / 88 % | 40 / 66 % | 9 / 29 % | 14 / 39 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 30 / 50 % | 66 / 88 % | 10 / 24 % | 32 / 51 % | 36 / 61 % | 21 / 37 % | 24 / 40 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 30 % | 65 / 94 % | 1 / 5 % | 35 / 63 % | 11 / 31 % | 4 / 18 % | 7 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 58 / 84 % | 0 / 0 % | 13 / 25 % | 7 / 15 % | 1 / 8 % | 7 / 12 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 18 / 37 % | 55 / 77 % | 1 / 6 % | 45 / 64 % | 14 / 35 % | 6 / 15 % | 13 / 30 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 13 / 40 % | 54 / 89 % | 0 / 4 % | 39 / 72 % | 19 / 41 % | 3 / 9 % | 9 / 17 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 38 % | 49 / 84 % | 4 / 19 % | 33 / 66 % | 22 / 46 % | 7 / 24 % | 11 / 25 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 48 / 81 % | 0 / 4 % | 2 / 9 % | 9 / 21 % | 4 / 15 % | 7 / 17 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 10 / 27 % | 41 / 76 % | 0 / 0 % | 11 / 27 % | 9 / 24 % | 3 / 13 % | 6 / 15 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 37 / 73 % | 0 / 0 % | 4 / 23 % | 11 / 28 % | 2 / 12 % | 6 / 14 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 32 / 82 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 7 % | 6 / 14 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 43 % | 16 / 53 % | 2 / 8 % | 31 / 49 % | 20 / 45 % | 7 / 19 % | 7 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 28 % | 29 / 73 % | 0 / 4 % | 1 / 5 % | 10 / 26 % | 5 / 18 % | 8 / 21 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 25 / 58 % | 1 / 4 % | 20 / 39 % | 11 / 35 % | 2 / 9 % | 8 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 17 / 67 % | 1 / 4 % | 17 / 30 % | 19 / 41 % | 5 / 13 % | 6 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 18 / 80 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 2 / 9 % | 5 / 11 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 38 % | 4 / 12 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 14 / 67 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 4 % | 4 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 1 / 5 % | 10 / 21 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 10 / 47 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 2 / 6 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 7 / 17 % | 9 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 9 / 30 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 4 / 11 % | 6 / 11 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 3 / 14 % | 8 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 2 / 12 % | 6 / 12 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 7 / 61 % | 0 / 0 % | 2 / 9 % | 7 / 14 % | 2 / 7 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 3 / 11 % | 5 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 2 / 6 % | 4 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 28 % | 0 / 0 % | 0 / 3 % | 6 / 13 % | 1 / 8 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 4 / 10 % |
