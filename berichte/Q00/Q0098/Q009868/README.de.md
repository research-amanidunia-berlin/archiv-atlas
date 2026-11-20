[English](README.md) · [Deutsch](README.de.md)

# Swift: Control & Monitor Cellular Network Traffic Routing

Bericht Q009868 · Quelle medium.com · Datum 2026-03-03 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-control-monitor-cellular-network-traffic-routing-a64e1f6129ea)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht erklärt, wie Apps laut Autor mit `CTSlicingManager` ab iOS 26.3 verfügbare Mobilfunk-Slices prüfen, eine passende Slice für neue Verbindungen anfordern und aktive Slices einsehen können. Dafür sind Berechtigungen, Unterstützung durch den Anbieter und geeignete Netzbedingungen nötig; vor dem Verbindungsaufbau muss die Slice aktiviert und der passende Netzwerkdiensttyp gesetzt werden. Tests müssen laut Bericht auf einem echten Gerät erfolgen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 5 / 38 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
