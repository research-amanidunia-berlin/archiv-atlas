[English](README.md) · [Deutsch](README.de.md)

# The Observability Gap in AI Agents

Bericht Q000002 · Quelle partnershiponai.org · Datum 2026-10-07 · [Original öffnen](https://partnershiponai.org/resource/the-observability-gap-in-ai-agents/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Berichtsauszug stellt sechs Lücken in den Überwachungsdaten verbreiteter KI-Agenten-Frameworks fest. Fehlende oder unvollständige Protokolle zu Identität, Berechtigungen, Gedächtnis, menschlichen Eingriffen, Modellbegründungen und Log-Wahrscheinlichkeiten erschwerten laut den Autorinnen und Autoren die Nachvollziehbarkeit und laufende Kontrolle. Der Auszug fordert koordinierte Maßnahmen mehrerer Akteure; Einzelheiten des Gesamtberichts liegen hier nicht vor.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 54 % | 69 / 95 % | – | 99 / 100 % | 57 / 79 % | 55 / 77 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 52 / 72 % | 88 / 95 % | – | 88 / 98 % | 76 / 88 % | 64 / 78 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 27 / 47 % | 44 / 88 % | – | 84 / 96 % | 35 / 65 % | 27 / 64 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 25 / 50 % | 63 / 91 % | – | 76 / 94 % | 30 / 61 % | 26 / 54 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 55 % | 69 / 96 % | – | 50 / 75 % | 41 / 68 % | 48 / 72 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 27 / 49 % | 53 / 98 % | – | 52 / 77 % | 45 / 69 % | 63 / 77 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 17 / 32 % | 58 / 90 % | – | 60 / 82 % | 12 / 27 % | 7 / 20 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 13 / 37 % | 39 / 72 % | – | 58 / 75 % | 39 / 64 % | 16 / 38 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 33 % | 0 / 0 % | – | 53 / 81 % | 9 / 28 % | 7 / 19 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 27 / 48 % | 45 / 89 % | – | 26 / 69 % | 40 / 68 % | 36 / 60 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 12 / 37 % | 43 / 94 % | – | 20 / 80 % | 23 / 53 % | 17 / 40 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 29 % | 41 / 85 % | – | 1 / 11 % | 9 / 24 % | 10 / 24 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 24 / 46 % | 37 / 71 % | – | 40 / 70 % | 38 / 65 % | 29 / 58 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 40 / 79 % | – | 1 / 9 % | 10 / 25 % | 6 / 15 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 39 / 77 % | – | 0 / 0 % | 8 / 20 % | 6 / 13 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 10 / 27 % | 32 / 76 % | – | 4 / 27 % | 13 / 32 % | 11 / 26 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 11 / 27 % | 32 / 79 % | – | 9 / 46 % | 14 / 35 % | 7 / 21 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 31 / 81 % | – | 0 / 0 % | 7 / 17 % | 7 / 16 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 17 / 32 % | 30 / 68 % | – | 2 / 21 % | 22 / 48 % | 21 / 42 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 11 / 36 % | 18 / 74 % | – | 11 / 54 % | 22 / 48 % | 28 / 53 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 12 / 28 % | 28 / 86 % | – | 1 / 12 % | 13 / 40 % | 11 / 26 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 18 / 38 % | 26 / 63 % | – | 0 / 0 % | 12 / 30 % | 26 / 50 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 25 / 80 % | – | 0 / 0 % | 6 / 16 % | 5 / 13 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 24 / 64 % | – | 7 / 51 % | 0 / 0 % | 6 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 20 / 53 % | – | 5 / 25 % | 6 / 11 % | 6 / 11 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 20 / 53 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 16 / 55 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 11 / 40 % | 0 / 0 % | – | 0 / 0 % | 15 / 37 % | 7 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 33 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 29 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 9 / 18 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 13 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | – | 6 / 24 % | 13 / 34 % | 6 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 13 / 33 % | 5 / 12 % | 8 / 12 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 5 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 20 % | 3 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 7 / 19 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 7 / 24 % | 7 / 16 % | 5 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 6 / 57 % | – | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 3 / 9 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 12 % |
