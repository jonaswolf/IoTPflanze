#Risikomanagement

##Risikoarten
- F Fachliches Risiko
    + FV Vertrieb
        * FV1 Plattform, eigener OnlineShop ist zu unbekannt, Marketing KnowHow fehlt
            - Marketing auslagern, Über gängige Plattformen vertreiben
    + FF Finanzen
        * FF1 Das Bundle/die Produkte können nicht entwickelt werden (keine Investoren/Startkapital)
            - In Echt: eigene Entwicklung da 'Hobbyprojekt'
            - Crowdfunding Kampagne starten, Crowdfunding an Partner wie Companisto auslagern
        * FF2 Produkte können zu keinem günstigen Preis angeboten werden, da Mengenrabatte zu Anfang nicht möglich sind
            - Entwicklungspartner finden
            - Versuchen Sonderkonditionen bei Herstellern einzuholen
            - Vorverkauf starten und erst bei bestimmter Menge kaufen
- I Inhärentes Risiko
    + I1 Steuerung der Anwendung/der Hardware von Unbefugten
        * Implementierung einer entsprechenden Sicherheitsstruktur
        * Arduino muss über genug Speicher verfügen um Sicherheitspatches einspielen zu lassen
        * Software kann mittels Fernwartung geupdated werden
    + I2 Angriff auf die Analyseplattform (bspw. DDOS)
        * Nutzen von Cloudanbietern sobald das Produkt erfolgreicher wird (AWS, Google, Azure)
        * Lagern der Daten in verschiedenen Rechenzentren/Cloudflare
    + I3 Mitlesen der Daten/Hacking des Servers
        * Verschlüsselung
        * Nutzer zu sicheren Passwörtern zwingen
- C Compliance Risiko
    + C1 Datenschutzrichtlinien/DSGVO
        * Beratung durch Datenschützer
    + C2 Patentrechtliche Folgen
        * Prüfen der Patentgesetze
    + C3 Softwarelizenzen
        * Beachtung der Lizenzen, Absprache mit Entwicklern im Vorhinein

- B Erkennungsrisiko und Bewertungsrisiko
    + B1 Risiken werden wegen mangelndem Wissen nicht erkannt
        * Andere Erfahrende Entwickler das Projekt betrachten und den Blickwinkel wechseln
    + B2 Finanzielle Fehlkalulation
        * Externer Berater
    + B3 Falsch/Falsch interpretierte Analysen
        * Analysen outsourcen, gegenprüfen lassen

- K Kontrollrisiko
    + K1 zu I2 DDOS Protection springt nicht an
    + K2 zu I3 Daten werden mitgelesen, Leck fällt erst spät auf