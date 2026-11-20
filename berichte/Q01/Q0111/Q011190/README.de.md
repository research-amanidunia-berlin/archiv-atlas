[English](README.md) · [Deutsch](README.de.md)

# OpenMuse: Build Your Own Open-Source AI Personal Assistant That Can Use Your Computer

Bericht Q011190 · Quelle medium.com · Datum 2026-09-27 · [Original öffnen](https://medium.com/coding-nexus/openmuse-build-your-own-open-source-ai-personal-assistant-that-can-use-your-computer-7fe32a8f3193)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel stellt OpenMuse als selbst hostbaren KI-Assistenten vor, der laut Autor Browser, Terminal, Dateien und verbundene Apps für mehrstufige Aufgaben nutzen kann. Er nennt Voraussetzungen und Schritte für den lokalen Start und zeigt einen Formularablauf als Beispiel, der laut Text nur ins lokale Postfach schreibt. Eine unabhängige Prüfung der Fähigkeiten oder eine ausführliche Sicherheitsanalyse enthält der Beitrag nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 26 / 49 % | 65 / 99 % | 16 / 58 % | 95 / 99 % | 43 / 67 % | 25 / 52 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 16 / 36 % | 11 / 86 % | 1 / 7 % | 92 / 98 % | 12 / 31 % | 8 / 23 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 30 % | 19 / 52 % | 0 / 0 % | 70 / 87 % | 7 / 21 % | 5 / 14 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 18 / 37 % | 17 / 74 % | 1 / 9 % | 46 / 77 % | 11 / 32 % | 10 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 56 % | 5 / 13 % | 5 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 15 / 38 % | 2 / 27 % | 1 / 5 % | 10 / 36 % | 12 / 30 % | 7 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 7 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 31 % | 13 / 64 % | 0 / 0 % | 5 / 24 % | 5 / 14 % | 3 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 30 % | 7 / 38 % | 0 / 3 % | 0 / 0 % | 10 / 27 % | 9 / 23 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 8 / 48 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 5 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 3 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 5 / 25 % | 0 / 0 % | 0 / 0 % | 1 / 8 % | 6 / 18 % | 2 / 9 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 6 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 4 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 4 / 9 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 3 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
