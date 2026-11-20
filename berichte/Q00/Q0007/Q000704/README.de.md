[English](README.md) · [Deutsch](README.de.md)

# Prioritizing Real-Time Failure Detection in AI Agents

Bericht Q000704 · Quelle partnershiponai.org · Datum 2025-09-11 · [Original öffnen](https://partnershiponai.org/resource/prioritizing-real-time-failure-detection-in-ai-agents/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Auszug argumentiert, dass autonom handelnde KI-Agenten Echtzeitüberwachung benötigen, weil Fehler durch direkte Aktionen erhebliche Folgen haben können. Wie stark die Kontrollen sein sollten, richte sich laut Text nach möglichen Schäden, Umkehrbarkeit und den Fähigkeiten des Agenten; mehrere Kontrollpunkte seien nötig. Eigene empirische Ergebnisse nennt dieser Überblick nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 41 / 56 % | 87 / 99 % | – | 94 / 97 % | 57 / 79 % | 34 / 59 % | 56 / 76 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 41 / 66 % | 88 / 97 % | – | 94 / 99 % | 75 / 88 % | 57 / 79 % | 81 / 89 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 35 / 59 % | 38 / 96 % | – | 77 / 93 % | 71 / 86 % | 69 / 86 % | 82 / 90 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 26 / 48 % | 57 / 97 % | – | 26 / 89 % | 44 / 70 % | 18 / 39 % | 29 / 53 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 16 / 33 % | 26 / 87 % | – | 57 / 88 % | 37 / 64 % | 10 / 27 % | 33 / 55 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 36 % | 0 / 0 % | – | 56 / 84 % | 24 / 53 % | 6 / 19 % | 13 / 44 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 17 / 33 % | 40 / 85 % | – | 50 / 77 % | 13 / 34 % | 5 / 16 % | 11 / 36 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 8 / 26 % | 43 / 91 % | – | 0 / 7 % | 8 / 24 % | 3 / 14 % | 8 / 23 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 24 / 49 % | 42 / 80 % | – | 9 / 40 % | 23 / 58 % | 13 / 32 % | 23 / 54 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 42 / 96 % | – | 17 / 38 % | 11 / 31 % | 6 / 16 % | 6 / 17 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 10 / 27 % | 39 / 86 % | – | 9 / 58 % | 10 / 29 % | 7 / 13 % | 6 / 15 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 32 / 88 % | – | 12 / 56 % | 17 / 49 % | 5 / 16 % | 13 / 33 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 9 / 31 % | 31 / 86 % | – | 13 / 52 % | 14 / 37 % | 7 / 19 % | 15 / 38 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 27 / 85 % | – | 0 / 0 % | 8 / 22 % | 4 / 13 % | 7 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 15 / 47 % | – | 21 / 41 % | 6 / 13 % | 2 / 4 % | 5 / 8 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 19 / 77 % | – | 0 / 0 % | 6 / 14 % | 2 / 5 % | 5 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 13 / 92 % | – | 18 / 55 % | 11 / 38 % | 2 / 10 % | 5 / 15 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 31 % | 10 / 92 % | – | 4 / 28 % | 15 / 44 % | 9 / 28 % | 18 / 45 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 17 / 31 % | 11 / 80 % | – | 5 / 24 % | 16 / 42 % | 6 / 17 % | 10 / 24 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 7 / 29 % | 0 / 0 % | – | 16 / 49 % | 7 / 17 % | 1 / 7 % | 5 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 15 / 58 % | – | 0 / 0 % | 6 / 16 % | 1 / 4 % | 5 / 10 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 33 % | 3 / 70 % | – | 0 / 0 % | 7 / 25 % | 1 / 6 % | 6 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 10 / 89 % | – | 1 / 20 % | 11 / 36 % | 2 / 10 % | 13 / 33 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 12 / 29 % | 7 / 82 % | – | 0 / 0 % | 10 / 28 % | 2 / 6 % | 7 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 10 / 43 % | 10 / 49 % | – | 0 / 0 % | 11 / 33 % | 2 / 9 % | 2 / 7 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 11 / 33 % | 1 / 70 % | – | 0 / 0 % | 8 / 20 % | 2 / 6 % | 6 / 14 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 32 % | 2 / 6 % | 8 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 30 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 10 / 69 % | – | 0 / 0 % | 7 / 23 % | 3 / 11 % | 6 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 9 / 88 % | – | 2 / 15 % | 8 / 25 % | 2 / 8 % | 5 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 9 / 83 % | – | 3 / 23 % | 6 / 14 % | 2 / 4 % | 4 / 7 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 87 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 4 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 4 / 12 % | 8 / 20 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 86 % | – | 3 / 40 % | 8 / 27 % | 3 / 11 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 4 / 94 % | – | 1 / 17 % | 7 / 18 % | 2 / 7 % | 5 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 3 % | 2 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 3 % | 5 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 3 / 39 % | – | 0 / 0 % | 0 / 0 % | 1 / 3 % | 5 / 9 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 4 % | 5 / 11 % |
