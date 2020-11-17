# SP-LS
Swimming Pixel - Launchpad Lightshow
Link zum Projekt http://hit-karlsruhe.de/hit-info/info-ws20/SP-LS/index.html


Allgemein:
Die Stadt Karlsruhe wurde 2019 von der UNESCO mit dem Titel City of Media Arts ausgezeichnet. Repräsentativ für diese Auszeichnung stehen Events, wie die Schlosslichtspiele, aber auch dauerhafte Einrichtungen, wie zum Beispiel das ZKM.
Die Hochschule Karlsruhe möchte sich ebenfalls daran beteiligen, die Stadt durch mediale Kunst einzigartig zu machen.

So soll im Rahmen der Lehrveranstaltung Informationstechnik - Labor das Projekt Swimming Pixels verwirklicht werden. Hierzu sollen die Studierenden schwimmende LED-Pixel konstruieren, die unteranderem mit Hilfe eines MIDI-Launchpads angesteuert werden können und somit den Schlossteich mit verschiedenen Lichtsequenzen erstrahlen lassen.

Die Aufgabe für dieses Projekt besteht darin, die LEDs der Swimming Pixel mithilfe eines Launchpads anzusteuern.

Es soll verschiedene Modi beinhalten:
- einen Einzelansteuerungsmodus, mit dem man die einzelnen Pixelfarben individuell ändern kann
- einen / mehrere Lightshowmodi, die Lichtabfolgen auf der gesamten Pixelmatrix realisieren

Somit soll es ermöglicht werden auf der Pixelmatrix komplexere Lichtabfolgen oder -muster zu realisieren.

Die Kommunikation zwischen dem Launchpad und den einzelnen Pixeln soll hierbei über MQTT erfolgen.


Vorgehen:
- Launchpad Lightshow herunterladen
- File in Node-Red importieren
- mit MQTT-Broker verbinden
- Pixel über Launchpad Web-Page ansteuern
