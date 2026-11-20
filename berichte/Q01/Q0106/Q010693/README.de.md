[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Photos Picker (Image, Movie, Single, Multiple, and Upside Down Pitfall!)

Bericht Q010693 · Quelle medium.com · Datum 2024-05-25 · [Original öffnen](https://medium.com/towardsdev/swiftui-photos-picker-image-movie-single-multiple-and-upside-down-pitfall-c6a000667940)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel zeigt SwiftUI-Code für die Auswahl einzelner oder mehrerer Bilder und Videos mit `PhotosPicker`. Gegen ein laut Autor bei HDR-Bildern beobachtetes Orientierungsproblem empfiehlt er ein eigenes `Transferable` über `UIImage`; für Videos werden Dateien kopiert und mit `AVPlayer` abgespielt. Die Ursachen für die Bildorientierung und mögliche Probleme mit der ursprünglichen Video-URL bleiben teilweise Vermutungen des Autors.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
