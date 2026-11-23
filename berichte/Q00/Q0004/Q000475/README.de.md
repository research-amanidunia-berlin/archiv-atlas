[English](README.md) · [Deutsch](README.de.md)

# SpecCompact: Accelerating LLM Agent Context Compaction with Slot-Parallel Semantic Speculative Verification

Bericht Q000475 · Quelle arxiv.org · Datum – · [Original öffnen](https://arxiv.org/abs/2611.06876)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug stellt SpecCompact vor: Ein kleines Modell erzeugt Zusammenfassungsfelder parallel, die ein Zielmodell semantisch prüft und bei Bedarf korrigiert, um die Kontextverdichtung von LLM-Agenten zu beschleunigen. Die Autoren berichten von Beschleunigungen in Benchmarks und einer Hermes-Nutzerstudie, doch der Auszug enthält weder die konkreten Werte noch den vollständigen Artikel und nennt modell- sowie aufgabenabhängige Leistungsabwägungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 10 / 29 % | – | 6 / 15 % | 0 / 0 % | 2 / 7 % | 0 / 0 % | 12 / 25 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
