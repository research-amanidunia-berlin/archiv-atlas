[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Manage/Configure Audio Device (Microphone) Inputs

Bericht Q009853 · Quelle medium.com · Datum 2026-03-14 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-macos-manage-configure-audio-device-microphone-inputs-0a8f3af39cb4)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag erklärt, wie macOS-Mikrofone mit `AVCaptureDevice` und Core Audio gefunden, über eine Geräte-ID ausgewählt und mit `AVAudioEngine` genutzt werden können. Als zentrale Einschränkung warnt der Autor vor einem möglicherweise veralteten Eingabeformat nach dem Gerätewechsel, das beim Einrichten eines Audio-Taps zum Absturz führen könne; er nennt drei mögliche Abhilfen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
