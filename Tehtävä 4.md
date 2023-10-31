```mermaid
sequenceDiagram
	participant browser
	participant server
	
	browser->>server: Ota input vastaan kun paina tallenna
	Note right of server: server poistaa vanhimman vastaanotetun inputin ja työntää uusimman vastauksen sovellukseen
	server->>browser: Palauttaa käyttäjän luoman inputin muiden arrayssa tällä hetkellä olevien inputien kanssa
```