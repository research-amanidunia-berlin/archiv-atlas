[English](README.md) · [Deutsch](README.de.md)

# Harness engineering: leveraging Codex in an agent-first world

Report Q006874 · Source openai.com · Date 2026-02-11 · [Open original](https://openai.com/index/harness-engineering/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt, wie ein OpenAI-Team laut eigener Darstellung ein internes Produkt ohne manuell geschriebenen Code mit Codex entwickelte. Dafür investierte es in Repository-Dokumentation, feste Architekturregeln und Werkzeuge, mit denen Agenten die Anwendung selbst testen und beobachten können. Die berichtete Autonomie hängt stark von dieser speziellen Umgebung ab; langfristige Wartbarkeit bleibt offen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 51 / 70 % | 99 / 100 % | 100 / 100 % | 77 / 87 % | 48 / 74 % | 74 / 83 % | 55 / 81 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 36 / 56 % | 99 / 100 % | 85 / 92 % | 54 / 74 % | 44 / 65 % | 68 / 78 % | 36 / 61 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 27 / 46 % | 71 / 93 % | 99 / 100 % | 46 / 69 % | 18 / 41 % | 51 / 69 % | 8 / 25 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 33 / 69 % | 98 / 99 % | 8 / 26 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 75 / 95 % | 95 / 97 % | 9 / 25 % | 0 / 0 % | 9 / 22 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 51 / 88 % | 77 / 90 % | 9 / 22 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 24 / 44 % | 75 / 96 % | 0 / 0 % | 17 / 45 % | 0 / 0 % | 25 / 46 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 67 / 98 % | 0 / 0 % | 13 / 41 % | 2 / 8 % | 10 / 24 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 43 / 95 % | 67 / 81 % | 26 / 53 % | 11 / 32 % | 14 / 37 % | 3 / 11 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 23 / 47 % | 60 / 89 % | 28 / 53 % | 48 / 70 % | 26 / 55 % | 62 / 78 % | 6 / 17 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 60 / 75 % | 5 / 13 % | 1 / 5 % | 4 / 8 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 51 / 93 % | 55 / 77 % | 12 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 33 / 77 % | 43 / 59 % | 13 / 37 % | 3 / 8 % | 15 / 27 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 36 / 84 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 18 / 92 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 1 % | 11 / 22 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 10 / 18 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 24 % | 1 / 3 % | 7 / 13 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 2 % | 7 / 14 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 8 / 22 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 2 / 57 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 5 / 7 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 2 / 7 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 5 / 12 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
