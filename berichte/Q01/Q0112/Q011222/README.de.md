[English](README.md) · [Deutsch](README.de.md)

# OpenCode: The Open-Source AI Coding Agent You Can Run in Your Terminal

Bericht Q011222 · Quelle medium.com · Datum 2026-08-13 · [Original öffnen](https://medium.com/coding-nexus/opencode-the-open-source-ai-coding-agent-you-can-run-in-your-terminal-660cd1855ce1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt OpenCode als quelloffenen Coding-Agenten vor, der Projekte analysieren, Änderungen planen und Code bearbeiten kann und sich mit verschiedenen, auch lokalen, Modellen verbinden lässt. Er erklärt Installationswege sowie den Unterschied zwischen Plan- und Build-Modus, liefert aber eine Einführung statt eines unabhängigen Praxistests.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 21 / 42 % | 64 / 97 % | 6 / 33 % | 97 / 99 % | 32 / 57 % | 11 / 33 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 40 / 94 % | 0 / 0 % | 96 / 99 % | 10 / 27 % | 4 / 13 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 13 / 44 % | 0 / 0 % | 83 / 90 % | 6 / 18 % | 2 / 7 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 46 / 69 % | 5 / 14 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 18 / 36 % | 23 / 75 % | 0 / 0 % | 42 / 71 % | 17 / 40 % | 8 / 22 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 36 % | 37 / 71 % | 0 / 0 % | 2 / 15 % | 7 / 21 % | 6 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 37 % | 4 / 31 % | 0 / 0 % | 0 / 0 % | 13 / 32 % | 8 / 22 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 12 / 33 % | 0 / 0 % | 0 / 0 % | 6 / 21 % | 8 / 22 % | 5 / 9 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 5 / 10 % | 2 / 5 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 9 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 2 / 6 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 5 % |
