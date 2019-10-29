# Releaseplanung und Aufwand
Unten werden die verschiedenen Releases dargestellt, die Module sollen daei einzeln nach Aufwand bewertet werden:

## Version 0
- Hardwareanforderungen
    + Arduino mit Sensoren (S)
    + Messen der Bodenfeuchtigkeit
    + Messen der Temperatur
    + ggfs. Messen der Luftfeuchtigkeit
    + Bluetooth (S)
- Softwareanforderungen
    + App: Oben beschriebene Daten in der App einsehen
        * Bluetoothverbindung (M)
        * App kann auf Daten des Arduino zugreifen und lesen (S)
    + Arduino
        * Anhand der gemessenen Daten die Wasserzufur steuern (M)
        * Freigeben/Senden der aktuellen Daten (S)
- Zusammenspiel HW und SW
    + Bluetooth Verbindung

## Version 1
- Hardwareanforderungen
    + Arduino mit Sensoren
    + Messen der Bodenfeuchtigkeit
    + Messen der Temperatur
    + ggfs. Messen der Luftfeuchtigkeit
    + Bluetooth
    + WLAN
- Softwareanforderungen
    + App: Oben beschriebene Daten in der App einsehen
        * Bluetoothverbindung ()
        * Anbindung an Datenbank (M)
        * Anzeigen von Vergangenheitswerten (S)
        * App kann auf Daten des Arduino zugreifen und lesen ()
    + Arduino
        * Anhand der gemessenen Daten die Wasserzufur steuern ()
        * Freigeben/Senden der aktuellen Daten ()
        * Schreiben der aktuellen Daten in eine Datenbank (S)
    + Server
        * Datenbankstruktur (S)
        * Nutzer können auf Arduino zugreifen (nur Lesen, kein Account benötigt) (M)
- Zusammenspiel HW und SW
    + WLAN/Internet Verbindung

## Version 2
- Hardwareanforderungen
    + Arduino mit Sensoren
    + Messen der Bodenfeuchtigkeit
    + Messen der Temperatur
    + ggfs. Messen der Luftfeuchtigkeit
    + Bluetooth
    + WLAN
- Softwareanforderungen
    + App: Oben beschriebene Daten in der App einsehen
        * Bluetoothverbindung ()
        * Anbindung an Datenbank ()
        * Anzeigen von Vergangenheitswerten ()
        * App kann auf Daten des Arduino zugreifen und lesen ()
        * Ändern der Wassermenge des Arduinos (L)
            - Muss Zwangsläufig Nutzerrechte beinhalten (M)
    + Arduino
        * Anhand der gemessenen Daten die Wasserzufur steuern ()
            - Wasserzufur durch App anpassbar (M)
        * Freigeben/Senden der aktuellen Daten ()
        * Schreiben der aktuellen Daten in eine Datenbank ()
    + Server
        * Datenbankstruktur ()
            - Erweitern um Nutzer (M)
        * Nutzer können auf Arduino zugreifen()
            - Nutzersystem (M)
- Zusammenspiel HW und SW
    + WLAN/Internet Verbindung

## Version 2
- Hardwareanforderungen
    + Arduino mit Sensoren
    + Messen der Bodenfeuchtigkeit
    + Messen der Temperatur
    + ggfs. Messen der Luftfeuchtigkeit
    + Bluetooth
    + WLAN
- Softwareanforderungen
    + App: Oben beschriebene Daten in der App einsehen
        * Bluetoothverbindung ()
        * Anbindung an Datenbank ()
        * Anzeigen von Vergangenheitswerten ()
        * App kann auf Daten des Arduino zugreifen und lesen ()
        * Ändern der Wassermenge des Arduinos ()
            - Muss Zwangsläufig Nutzerrechte beinhalten ()
    + Arduino
        * Anhand der gemessenen Daten die Wasserzufur steuern ()
            - Wasserzufur durch App anpassbar ()
        * Freigeben/Senden der aktuellen Daten ()
        * Schreiben der aktuellen Daten in eine Datenbank ()
    + Server
        * Datenbankstruktur ()
            - Erweitern um Nutzer ()
        * Nutzer können auf Arduino zugreifen()
            - Nutzersystem ()
        * Analysefunktion
            - Nutzer können Daten Analysieren und so Wasserzufur optimieren (M)
- Zusammenspiel HW und SW
    + WLAN/Internet Verbindung
