```mermaid
sequenceDiagram
	participant browser
	participant server
	
	browser->>server: pyytää lisäämään JSON-muistiinpanon, osoite "new note spa", tyyppi "POST"
	Note left of browser: Content-type kertoo että pyynnön mukana tuleva data on JSON-muotoista
	Server->>browser: vastaa kyselyyn statuskoodilla 201 created; selain pysyy samalla sivulla
```