[English](README.md) · [Deutsch](README.de.md)

# AWS Lambda as MCP Tools: AWS Lambda MCP Server vs AgentCore Gateway

Bericht Q010120 · Quelle medium.com · Datum 2025-10-02 · [Original öffnen](https://medium.com/aws-tip/aws-lambda-as-mcp-tools-aws-lambda-mcp-server-vs-agentcore-gateway-495999063932)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor vergleicht einen per STDIO genutzten Lambda MCP Server mit dem umfangreicher einzurichtenden AgentCore Gateway. Er berichtet von fehlenden Werkzeugbeschreibungen und einem unpassenden Parameter im Agentenversuch; entscheidend sei, ob Lambda-Werkzeuge nur dem Host-Agenten dienen oder über HTTP auch anderen MCP-Clients mit passender OAuth-Berechtigung zugänglich sein sollen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 19 / 40 % | 93 / 99 % | 0 / 0 % | 98 / 99 % | 25 / 46 % | 11 / 26 % | 3 / 11 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 8 / 56 % | 0 / 0 % | 52 / 69 % | 10 / 24 % | 7 / 15 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 4 / 38 % | 0 / 0 % | 49 / 64 % | 7 / 18 % | 0 / 0 % | 1 / 4 % |
