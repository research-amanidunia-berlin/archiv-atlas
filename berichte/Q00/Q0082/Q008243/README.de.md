[English](README.md) · [Deutsch](README.de.md)

# Scaling Kubernetes to 2,500 nodes

Bericht Q008243 · Quelle openai.com · Datum 2018-01-18 · [Original öffnen](https://openai.com/index/scaling-kubernetes-to-2500-nodes/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet, Kubernetes 2018 auf mehr als 2.500 Azure-Knoten skaliert und dabei Engpässe bei etcd, API-Abfragen, DNS, Docker-Abrufen, Netzwerk und ARP-Caches durch gezielte Konfigurationsänderungen behoben zu haben. Das Unternehmen meldete anschließend rund drei Monate ohne Zwischenfälle; die Wirksamkeit der Maßnahmen wird im Text als eigene Erfahrung beschrieben, nicht unabhängig belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 69 / 93 % | – | 88 / 94 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 88 / 99 % | – | 81 / 90 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 62 / 92 % | – | 44 / 59 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
