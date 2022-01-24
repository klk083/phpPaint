Dette er en liten informasjon om hvordan man kjører server og client.


php ble brukt med ratchet for å skape en websocket server.


For å starte server kjører man komandoen under i komandolinjen når du står i mappen MyApp
php bin/chat-server.php

For å koble til en klient kjøres 
var conn = new WebSocket('ws://localhost:8080');

Som jeg har lagt inn i canvas.html

Når serveren er oppe å går kan man åpne html filen og begynne å tegne.

Jeg startet en apache server hvor jeg la HTML filen på.





