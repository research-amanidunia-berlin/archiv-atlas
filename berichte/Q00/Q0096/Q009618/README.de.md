[English](README.md) · [Deutsch](README.de.md)

# Swift FoundationModels: Intercept and Modify Tool Calls

Bericht Q009618 · Quelle medium.com · Datum 2026-10-12 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-foundationmodels-intercept-and-modify-tool-calls-51e0205c2564)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht beschreibt, wie Swift FoundationModels-Tool-Aufrufe abgefangen, geändert und programmatisch ausgeführt werden können. Dafür wird das Ergebnis in den Sitzungsverlauf geschrieben und die Modellantwort intern neu angestoßen; die gezeigten Beispiele belegen den Ablauf, aber keine systematische Prüfung weiterer Fälle.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 19 / 39 % | 74 / 95 % | 0 / 0 % | 73 / 85 % | 17 / 35 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 13 / 32 % | 0 / 0 % | 56 / 74 % | 11 / 27 % | 5 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 6 / 12 % |
