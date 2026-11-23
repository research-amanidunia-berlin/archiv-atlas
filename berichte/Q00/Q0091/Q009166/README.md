[English](README.md) · [Deutsch](README.de.md)

# March 20 ChatGPT outage: Here’s what happened

Report Q009166 · Source openai.com · Date 2023-03-24 · [Open original](https://openai.com/index/march-20-chatgpt-outage/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI führt den ChatGPT-Ausfall und mögliche Einblicke in fremde Chat- und Zahlungsdaten auf einen Fehler im Redis-Python-Client zurück. Laut Unternehmen könnten im neunstündigen Zeitraum am 20. März Daten von 1,2 Prozent der damals aktiven Plus-Abonnenten sichtbar gewesen sein; vollständige Kartennummern seien nicht betroffen gewesen, und die tatsächliche Zahl eingesehener Datensätze sei vermutlich sehr gering. OpenAI erklärt, den Fehler behoben, Betroffene benachrichtigt und zusätzliche Schutzmaßnahmen eingeführt zu haben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 82 / 97 % | 100 / 100 % | 41 / 65 % | 0 / 0 % | 21 / 39 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 45 / 64 % | 70 / 94 % | 97 / 99 % | 55 / 76 % | 33 / 50 % | 39 / 57 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 79 / 88 % | 16 / 39 % | 0 / 0 % | 17 / 30 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 68 / 75 % | 20 / 38 % | 14 / 29 % | 25 / 41 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 37 / 59 % | 47 / 84 % | 63 / 73 % | 40 / 61 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 61 / 67 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 51 / 70 % | 61 / 77 % | 20 / 42 % | 0 / 0 % | 13 / 24 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 57 / 67 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 51 % | 49 / 77 % | 54 / 60 % | 18 / 43 % | 0 / 0 % | 24 / 40 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 41 / 67 % | 49 / 64 % | 38 / 57 % | 12 / 24 % | 22 / 34 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 41 / 70 % | 10 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 34 / 79 % | 30 / 62 % | 11 / 27 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 35 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | 13 / 22 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 12 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 11 / 57 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 19 % | 0 / 0 % | 7 / 12 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 5 / 11 % | – | – |
