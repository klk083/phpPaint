Dette er en liten informasjon om hvordan man kjører server og client.

**PHP** ble brukt sammen med **Ratchet** for å skape en websocket server, for å lage en enkel paint applikasjon.

</br>
For at dette skal funke må man ha PHP installert.

For å starte server kjører man komandoen under i komandolinjen når du står i mappen **MyApp**
```
php bin/chat-server.php
```
For å koble til en klient kjøres 
```
var conn = new WebSocket('ws://localhost:8080');
```
Som jeg har lagt inn i canvas.html

Når serveren er oppe å går kan man åpne html filen i en nettleser og begynne å tegne.
