# pixoo64-tibber-preisanzeige
Diese Information richtet sich an alle Nutzer von tibber dem Stromanbieter

ey, hier ist dein individueller Einladungscode für Tibber, der Stromanbieter, der dir hilft, deinen Stromverbrauch zu verstehen und zu reduzieren: https://invite.tibber.com/Techpirat. Du erhältst 100% Ökostrom und kannst jederzeit mit einer Frist von 2 Wochen kündigen. Probiere es aus und wir erhalten beide 50 € Bonus für den Tibber-Store.

Die Idee ist: Zeige den aktuellen Strompreis vom Stromanbieter tipper auf dem Pixoo64 an.
Habt Ihr noch keinen Pixoo64? Dann kanst du ihn hier kaufen: https://amzn.to/3X4DTJ8
Mein Code ist erstellt und getestet mit python 3.9.7
Bitte folgende Module installieren und Importieren:
from pixoo import  Pixoo #<-- Das ist die Library für das Pixoo64
import time
import requests

Großen Dank an https://github.com/SomethingWithComputers/pixoo er hat eine Library für das Pixoo64 Display geschrieben.
Mit dessen Hilfe ist die Anzeige ganz leicht möglich.
Ihr müsst die Library von "SomethingWithComputers" im gleichen Verzeichniss importieren

Ziel ist es das je nach aktuellen Preis die Ampel rot, gelb oder grün zeigt.
Angegeben werden auch das Datum, Uhrzeit und der Preis.

Euern tibber API Key bekommt ihr hier: https://developer.tibber.com/settings/access-token
Diesen müsst Ihr in der pixoo_display.py an entsprechender Stelle eintagen


##############################  

English version:
This information is intended for all users of tibber the electricity provider

ey, here's your unique invite code for Tibber, the electricity provider that helps you understand and reduce your electricity consumption: https://invite.tibber.com/Techpirat. You receive 100% green electricity and can cancel at any time with a notice period of 2 weeks. Try it and we both get €50 bonus for the Tibber store.

The idea is: Show the current electricity price from the electricity provider tipper on the Pixoo64.
Don't have a Pixoo64 yet? Then you can buy it here: https://amzn.to/3X4DTJ8
My code is built and tested with python 3.9.7
Please install and import the following modules:
from pixoo import Pixoo #<-- This is the library for the Pixoo64
import time
import requests

Big thanks to https://github.com/SomethingWithComputers/pixoo he wrote a library for the Pixoo64 display.
With its help, the display is very easy.
You have to import the library from "SomethingWithComputers" in the same directory

The aim is for the traffic light to show red, yellow or green depending on the current price.
The date, time and price are also given.

You can get your tibber API key here: https://developer.tibber.com/settings/access-token
You have to enter this in the pixoo_display.py at the appropriate place