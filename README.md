# Countdown für DLRG Typo3 7.6.x

Der Coundown baut auf das jQuery Countdown Plugin von [Hilios](http://hilios.github.io/jQuery.countdown/) auf.

Ladet das Countdown Plugin auf der [Hilios](http://hilios.github.io/jQuery.countdown/) Seite herunter.

Anschließend müsst ihr euch per FTP mit dem DLRG Server verbinden. Dazu findet ihr die Informationen im [DLRG Wiki](https://wiki.dlrg.de/index.php/Ftp).
Wenn ihr euch verbunden habt konnt ihr die `jquery.countdown.js` oder `jquery.countdown.min.js` unter ` /public_html/` hochladen.

Um den Countdown nutzen zu können muss auf der gewünschten Seite **zwei** neue Seiteninhalte "reines HTML" angelegt werden.

In den ersten Seiteninhalt wird der Code aus der `Output.html eingefügt.

**Bitte den Pfad zu `jquery.countdown.js` oder `jquery.countdown.min.js` anpassen.
Der Ordner `public_html` wird über https://gliederung.dlrg.de/php/ aufgerufen.**

Jetzt wird im zweiten Seiteninhalt der Code aus der `Settings.html` eingefügt

Nun sollte auf der gewünschten Seite ein Countdown erscheinen.

