[English](README.md) · [Deutsch](README.de.md)

# Uncovering Latent Human Wellbeing in LLM Embeddings

Report Q001748 · Source far.ai · Date 2026-07-16 · [Open original](https://www.far.ai/blog/uncovering-latent-human-wellbeing-in-llm-embeddings)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht findet, dass sich Bewertungen der Angenehmheit von Szenarien aus vortrainierten Sprachmodell-Einbettungen ableiten lassen: `text-embedding-ada-002` erreicht mit einer PCA-Komponente im paarweisen Vergleich 73,7 Prozent Testgenauigkeit, nahe an den berichteten 74,6 Prozent eines feinabgestimmten BERT-large. Das Ergebnis betrifft eine begrenzte ETHICS-Aufgabe mit US-bezogenen Urteilen und belegt kein umfassendes Verständnis menschlicher Werte.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 51 / 67 % | 98 / 100 % | 100 / 100 % | 77 / 87 % | 53 / 67 % | 71 / 81 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 68 / 94 % | 92 / 96 % | 8 / 27 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 37 / 91 % | 89 / 94 % | 15 / 39 % | 6 / 17 % | 8 / 21 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 65 / 76 % | 8 / 25 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 52 % | 32 / 76 % | 52 / 80 % | 14 / 41 % | 5 / 16 % | 10 / 27 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 51 % | 0 / 0 % | 48 / 58 % | 11 / 34 % | 0 / 0 % | 10 / 22 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 57 % | 23 / 73 % | 47 / 78 % | 43 / 71 % | 28 / 43 % | 27 / 45 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 15 / 38 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 11 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 15 / 48 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 9 / 47 % | 2 / 28 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 8 / 47 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 28 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 2 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
