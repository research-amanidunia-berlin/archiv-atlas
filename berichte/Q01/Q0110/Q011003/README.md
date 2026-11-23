[English](README.md) · [Deutsch](README.de.md)

# Does Codex Train on Your Code? OpenAI Answered That Four Different Ways in Three Days.

Report Q011003 · Source medium.com · Date 2026-09-15 · [Open original](https://medium.com/ai-advances/does-codex-train-on-your-code-openai-answered-that-four-different-ways-in-three-days-3e32e3e6a002)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Artikel kritisiert, dass OpenAI auf die Frage, ob Codex-Sitzungen ins Training einfließen, zunächst mit Aussagen über Datenzugriff und Suche geantwortet habe; später habe das Unternehmen einen Beitrag anonymisierter Nutzungsdaten nicht ausschließen können. Die Erklärung, Buckmasters spätere Prompts seien nach Trainingsbeginn eingegangen, kläre laut Autor weder frühere Sitzungen noch die fehlende unabhängige Prüfbarkeit. Er warnt außerdem, dass Codex-Vollumgebungen eine eigene Trainingseinstellung haben, die von der allgemeinen ChatGPT-Abwahl unberührt bleibe.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 42 / 60 % | 64 / 91 % | 100 / 100 % | 33 / 60 % | 15 / 31 % | 23 / 43 % | 11 / 28 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 39 / 63 % | 99 / 100 % | 98 / 100 % | 85 / 91 % | 81 / 90 % | 88 / 93 % | 98 / 99 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 70 / 93 % | 99 / 100 % | 26 / 50 % | 11 / 21 % | 17 / 31 % | 2 / 6 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 44 % | 99 / 100 % | 99 / 100 % | 32 / 60 % | 10 / 30 % | 39 / 57 % | 14 / 41 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 94 / 97 % | 24 / 49 % | 7 / 15 % | 14 / 28 % | 6 / 19 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 10 / 49 % | 89 / 93 % | 10 / 20 % | 1 / 6 % | 9 / 20 % | 0 / 2 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 86 / 92 % | 25 / 50 % | 0 / 0 % | 17 / 32 % | 5 / 14 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 21 / 41 % | 86 / 98 % | 74 / 83 % | 13 / 33 % | 5 / 15 % | 10 / 20 % | 1 / 7 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 17 / 56 % | 85 / 90 % | 12 / 26 % | 10 / 20 % | 15 / 28 % | 1 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 24 / 52 % | 44 / 84 % | 84 / 90 % | 26 / 50 % | 6 / 17 % | 24 / 46 % | 2 / 9 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 27 / 84 % | 82 / 90 % | 12 / 31 % | 0 / 0 % | 20 / 34 % | 1 / 4 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 33 / 57 % | 71 / 95 % | 74 / 86 % | 73 / 85 % | 68 / 81 % | 78 / 86 % | 72 / 83 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 55 % | 52 / 90 % | 75 / 84 % | 34 / 65 % | 61 / 77 % | 53 / 71 % | 23 / 49 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 31 / 53 % | 67 / 95 % | 74 / 81 % | 44 / 69 % | 38 / 54 % | 40 / 58 % | 22 / 43 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 34 / 59 % | 16 / 55 % | 73 / 85 % | 64 / 80 % | 40 / 56 % | 74 / 84 % | 56 / 78 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 66 / 82 % | 7 / 18 % | 3 / 11 % | 5 / 12 % | 1 / 5 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 27 / 52 % | 59 / 94 % | 63 / 75 % | 24 / 49 % | 8 / 20 % | 32 / 54 % | 1 / 7 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 32 % | 59 / 78 % | 0 / 0 % | 0 / 0 % | 18 / 33 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 21 / 50 % | 45 / 72 % | 48 / 61 % | 36 / 61 % | 30 / 50 % | 22 / 36 % | 19 / 41 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 21 / 46 % | 46 / 79 % | 36 / 55 % | 26 / 49 % | 7 / 17 % | 20 / 37 % | 5 / 17 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 41 / 62 % | 10 / 23 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 37 / 61 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 18 / 72 % | 30 / 52 % | 9 / 23 % | 4 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 25 / 58 % | 27 / 46 % | 14 / 33 % | 6 / 17 % | 8 / 17 % | 1 / 4 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 13 / 35 % | 0 / 0 % | 0 / 0 % | 14 / 35 % | 17 / 27 % | 22 / 37 % | 1 / 4 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 45 % | 10 / 19 % | 14 / 26 % | 2 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 16 / 31 % | 12 / 27 % | 0 / 0 % | 17 / 32 % | 1 / 4 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 28 % | 0 / 0 % | 15 / 25 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 27 % | 5 / 11 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 25 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 4 / 38 % | 0 / 0 % | 11 / 29 % | 8 / 19 % | 10 / 20 % | 2 / 8 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 18 % | 5 / 11 % | 10 / 23 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 27 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 4 / 10 % | 10 / 21 % | 1 / 4 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 8 / 15 % | 1 / 4 % | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 16 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
