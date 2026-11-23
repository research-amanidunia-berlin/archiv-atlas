[English](README.md) · [Deutsch](README.de.md)

# The C2PA standard: what it specifies, who runs it, and what a check really tells you

Report Q000592 · Source aiinforemover.com · Date 2026-11-05 · [Open original](https://aiinforemover.com/blog/c2pa-standard)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht erklärt C2PA als Standard für signierte Herkunftsdatensätze und unterscheidet die Prüfstufen „well-formed“, „valid“ und „trusted“, deren Ergebnis auch von der Vertrauensliste des Validators abhängt. Eine gültige Signatur belegt laut Bericht weder die Wahrheit eines Inhalts noch, dass eine Datei ohne Manifest nie eines hatte; der erwähnte Checker erkennt nur C2PA-Marker.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 90 / 96 % | – | 20 / 37 % | 53 / 68 % | 57 / 67 % | 0 / 0 % | 74 / 85 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 50 / 64 % | 59 / 97 % | – | 60 / 78 % | 59 / 76 % | 65 / 77 % | 82 / 93 % | 58 / 80 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 71 / 90 % | – | 12 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 55 / 83 % | – | 20 / 43 % | 0 / 0 % | 0 / 0 % | 15 / 31 % | 32 / 54 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 55 / 82 % | – | 14 / 30 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 18 / 41 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 45 % | 0 / 0 % | – | 6 / 19 % | 0 / 0 % | 11 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 26 / 66 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 4 / 10 % | 15 / 27 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | 14 / 36 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 4 / 9 % | 10 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 10 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 10 / 24 % | 0 / 0 % | 10 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 4 / 8 % | 0 / 0 % | 9 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | – | 9 / 22 % | 5 / 13 % | 9 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 9 / 20 % | 2 / 8 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 5 / 9 % | 0 / 0 % | 8 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 8 / 19 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 3 / 8 % | 6 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 1 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 6 / 16 % | 1 / 6 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 4 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
