[English](README.md) · [Deutsch](README.de.md)

# Ornith-1.5: A 9B Open-Source Model Built to Improve Itself

Bericht Q011213 · Quelle medium.com · Datum 2026-08-22 · [Original öffnen](https://medium.com/coding-nexus/ornith-1-5-a-9b-open-source-model-built-to-improve-itself-ab3055ef6e88)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt Ornith-1.5 als offene Modellfamilie vor, deren Modelle laut Projekt eigene Lernaufgaben erzeugen und zur Verbesserung nutzen sollen. Der Autor berichtet starke Benchmarkwerte und hebt besonders die lokal betreibbare 9B-Version mit Werkzeugaufrufen und bis zu 262.144 Tokens Kontext hervor; die Leistungsangaben werden im Text nicht unabhängig überprüft, und die Erweiterung auf rund eine Million Tokens erfordert laut Bericht eine bedarfsgerechte YaRN-Konfiguration.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 35 / 63 % | 91 / 99 % | 51 / 80 % | 98 / 100 % | 57 / 79 % | 26 / 55 % | 50 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 14 / 40 % | 52 / 88 % | 1 / 10 % | 96 / 98 % | 12 / 36 % | 2 / 14 % | 8 / 23 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 16 / 46 % | 15 / 77 % | 1 / 6 % | 87 / 95 % | 8 / 23 % | 2 / 9 % | 5 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 9 / 38 % | 0 / 0 % | 56 / 80 % | 7 / 22 % | 0 / 0 % | 5 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 39 / 74 % | 0 / 3 % | 42 / 70 % | 9 / 31 % | 0 / 0 % | 8 / 19 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 10 / 41 % | 42 / 70 % | 2 / 12 % | 38 / 73 % | 18 / 41 % | 1 / 8 % | 9 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 13 / 41 % | 29 / 72 % | 1 / 6 % | 0 / 0 % | 7 / 21 % | 2 / 10 % | 8 / 24 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 52 % | 6 / 14 % | 1 / 5 % | 2 / 7 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 20 / 44 % | 1 / 32 % | 0 / 0 % | 0 / 0 % | 6 / 22 % | 0 / 0 % | 11 / 23 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 13 / 48 % | 15 / 71 % | 1 / 5 % | 12 / 33 % | 12 / 33 % | 2 / 10 % | 7 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 44 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 7 / 14 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 11 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 3 / 11 % | 9 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 3 / 44 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 0 % | 7 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 2 % | 8 / 15 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 1 / 4 % | 5 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 5 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 1 / 4 % | 6 / 12 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 2 / 27 % | 0 / 3 % | 0 / 0 % | 6 / 20 % | 1 / 8 % | 5 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 6 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 6 % | 4 / 10 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 1 / 28 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 4 % | 2 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 2 / 4 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 0 / 0 % |
