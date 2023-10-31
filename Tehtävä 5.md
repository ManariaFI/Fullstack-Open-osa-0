```mermaid
sequenceDiagram
	participant browser
	participant server
	
	server->>browser: Antaa serverille muistiinpanot palvelimelta JSON-muotoisena raakadatana
	browser->>server: Selain lisää sivulle muistiinpanoja edustavat HTML-elementit hyödyntäen DOM-apia
```