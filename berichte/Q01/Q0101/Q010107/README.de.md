[English](README.md) · [Deutsch](README.de.md)

# Auto-GPT: A Powerful AI Tool That Makes GPT-4 Autonomous

Bericht Q010107 · Quelle frank-andrade.medium.com · Datum 2023-04-18 · [Original öffnen](https://frank-andrade.medium.com/auto-gpt-a-powerful-ai-tool-that-makes-gpt-4-autonomous-4157b54f94c7)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag stellt Auto-GPT als experimentellen GPT-4-Agenten vor, der nach Vorgabe einer Rolle und von Zielen selbstständig Schritte planen, im Web recherchieren und Dateien bearbeiten soll. Beispiele aus sozialen Medien zeigen mögliche Anwendungen, sind aber keine systematische Prüfung. Als Nachteile nennt der Autor hohe, durch viele Modellaufrufe entstehende Kosten und Halluzinationen; die Einordnung als Schritt Richtung AGI bleibt spekulativ.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 20 / 44 % | 82 / 95 % | 7 / 41 % | 92 / 97 % | 36 / 63 % | 20 / 47 % | 4 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 37 % | 49 / 80 % | 1 / 6 % | 34 / 64 % | 11 / 36 % | 10 / 28 % | 1 / 11 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 7 / 30 % | 0 / 4 % | 44 / 65 % | 8 / 26 % | 8 / 21 % | 1 / 5 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 15 / 35 % | 2 / 39 % | 0 / 7 % | 42 / 68 % | 11 / 35 % | 9 / 30 % | 1 / 7 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 9 / 20 % | 19 / 48 % | 0 / 2 % | 23 / 51 % | 5 / 13 % | 4 / 11 % | 0 / 2 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 26 % | 6 / 63 % | 0 / 2 % | 21 / 41 % | 5 / 15 % | 5 / 14 % | 1 / 5 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 15 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 7 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 32 % | 5 / 10 % | 0 / 0 % | 0 / 1 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 12 / 30 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 4 / 8 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 12 / 34 % | 11 / 59 % | 0 / 3 % | 0 / 0 % | 8 / 29 % | 7 / 22 % | 1 / 4 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 29 % | 12 / 65 % | 1 / 8 % | 7 / 19 % | 9 / 30 % | 6 / 18 % | 1 / 9 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 7 % | 5 / 8 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 11 / 31 % | 0 / 0 % | 0 / 5 % | 8 / 27 % | 10 / 30 % | 7 / 16 % | 1 / 3 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 8 / 28 % | 9 / 34 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 7 / 21 % | 0 / 2 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 34 % | 5 / 52 % | 0 / 3 % | 1 / 13 % | 8 / 23 % | 8 / 22 % | 1 / 10 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 9 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 7 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 9 / 37 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 8 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 7 % | 0 / 2 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 5 / 27 % | 2 / 28 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 4 / 8 % | 0 / 2 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 6 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 4 / 8 % | 1 / 3 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 6 / 20 % | 1 / 62 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 13 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 3 / 6 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 6 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 7 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 2 / 21 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 10 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 5 % | 0 / 1 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 10 % | 0 / 0 % |
