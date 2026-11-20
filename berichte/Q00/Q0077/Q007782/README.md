[English](README.md) · [Deutsch](README.de.md)

# Hierarchical text-conditional image generation with CLIP latents

Report Q007782 · Source openai.com · Date 2022-04-13 · [Open original](https://openai.com/index/hierarchical-text-conditional-image-generation-with-clip-latents/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Text ist nur ein Auszug mit Abstract und Bildunterschriften. Die Autoren schlagen ein zweistufiges Verfahren vor, das Text zunächst in eine CLIP-Bildrepräsentation und diese dann per Diffusionsdecoder in ein Bild umwandelt; laut Abstract erhöht dies die Vielfalt und ermöglicht Stil und Bedeutung bewahrende Varianten sowie sprachgesteuerte Änderungen. Diffusionsmodelle für den Prior seien den Autoren zufolge effizienter und lieferten bessere Ergebnisse als autoregressive Modelle; konkrete Messwerte fehlen im Auszug.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 40 / 69 % | – | 59 / 76 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 29 / 59 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 10 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 11 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 3 / 9 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 15 % | 5 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 10 % |
