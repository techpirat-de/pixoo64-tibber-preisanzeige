# pixoo64-tibber-preisanzeige
Diese Information richtet sich an alle Nutzer von Tibber oder an die, die es werden wollen, dem Stromanbieter.

Hey, hier ist dein individueller Einladungscode für Tibber, dem Stromanbieter, der dir hilft, deinen Stromverbrauch zu verstehen und zu reduzieren: https://invite.tibber.com/Techpirat. Du erhältst 100% Ökostrom und kannst jederzeit mit einer Frist von 2 Wochen kündigen. Probiere es aus, und wir erhalten beide 50 € Bonus für den Tibber-Store.

Die Idee ist, den aktuellen Strompreis vom Stromanbieter Tibber auf dem Pixoo64 anzuzeigen. Hast du noch keinen Pixoo64? Dann kannst du ihn hier kaufen: https://amzn.to/3X4DTJ8. Mein Code ist erstellt und getestet mit Python 3.9.7.

Großer Dank an https://github.com/SomethingWithComputers/pixoo. Er hat eine Library für das Pixoo64 Display geschrieben, mit dessen Hilfe die Anzeige ganz leicht möglich ist. Ihr müsst die Library von "SomethingWithComputers" im gleichen Verzeichnis importieren.

Bitte folgende Module installieren und importieren:

from pixoo import Pixoo # Das ist die Library für das Pixoo64
import time
import requests

Um die Echtzeit-Preisanzeige zu bekommen, braucht ihr einen API-Key von Tibber. Euren Tibber API-Key bekommt ihr hier: https://developer.tibber.com/settings/access-token. Einfach dort mit euren normalen Zugangsdaten anmelden. Diesen müsst ihr an der entsprechenden Stelle in der Datei pixoo_display.py eintragen.

Ihr müsst auch die lokale IP-Adresse des Pixoo eintragen. Diese findet ihr über euren Router oder über die Pixoo Divoom App. In der App auf "Entdecken" unten links. Dann unter "Verfügbare Geräte" euren Pixoo64 auswählen und die "IP-Adresse" abschreiben. In meinem Fall ist es 192.168.2.200. Diese durch eure eigene in der Datei local_ip.py ersetzen.

Ziel ist es, dass je nach aktuellem Preis die Ampel rot, gelb oder grün zeigt. Angegeben werden auch das Datum, Uhrzeit und der Preis.

Starte nun die pixoo_display.py in einer passenden Umgebebung. 
Wie ihr diese Umgebung einrichtet zeige ich euch in einem Video. 
So bald dieses Video verfügbar ist schreibe ich den Link hier rein.

Nach dem Starten wird das Display alle 60 Sekunden aktualisiert. Bei ersten Start, startet das Display einmal neu um in den Epfangmodus zu wechseln. 

Besucht mich auf YouTube: https://www.youtube.com/techpirat


##############################  

English version:
This information is intended for all users of Tibber or those who want to become one, the electricity provider.

Hey, here's your unique invite code for Tibber, the electricity provider to help you understand and reduce your electricity consumption: https://invite.tibber.com/Techpirat. You receive 100% green electricity and can cancel at any time with a notice period of 2 weeks. Try it and we'll both get €50 bonus for the Tibber store.

The idea is to display the current electricity price from electricity provider Tibber on the Pixoo64. Don't have a Pixoo64 yet? Then you can buy it here: https://amzn.to/3X4DTJ8. My code is built and tested with Python 3.9.7.

Big thanks to https://github.com/SomethingWithComputers/pixoo. He has written a library for the Pixoo64 display that makes displaying it very easy. You have to import the library from "SomethingWithComputers" in the same directory.

Please install and import the following modules:

from pixoo import Pixoo # This is the library for the Pixoo64
import time
import requests

To get the real-time price display, you need a Tibber API key. You can get your Tibber API key here: https://developer.tibber.com/settings/access-token. Simply register there with your normal access data. You have to enter this at the appropriate place in the pixoo_display.py file.

You must also enter the local IP address of the Pixoo. You can find this via your router or via the Pixoo Divoom app. In the app on "Discover" on the bottom left. Then select your Pixoo64 under "Available devices" and write down the "IP address". In my case it is 192.168.2.200. Replace this with your own in the local_ip.py file.

The aim is for the traffic light to show red, yellow or green depending on the current price. The date, time and price are also given.

Now start the pixoo_display.py in a suitable environment.
I'll show you how to set up this environment in a video.
As soon as this video is available I will post the link here.

After starting, the display is updated every 60 seconds. At the first start, the display restarts once to switch to the reception mode.

Visit me on YouTube: https://www.youtube.com/techpirat