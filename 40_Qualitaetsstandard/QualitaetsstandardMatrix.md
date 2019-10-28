
# Qualitätsstandard Matrix
Die Matrix wird falsch angezeigt, jedoch besteht das Problem nur bei GitHub!

| Qualitätsstandard Matrix | **Functional Stability** | **Performance** | **Compatibility** | **Usability** | **Reliability** | **Security** | **Maintainability** | **Portability** |
|--|--|--|--|--|--|--|--|--|--|
| **Functional Stability** | / |  |  |  |  |  |  |  |
| **Performance** | < | / |  |  |  |  |  |  |
| **Compatibility** | ^ | ^ | / |  |  |  |  |  |
| **Usability** | / | ^ | < | / |  |  |  |  |
| **Reliability** | < | < | < | ^ | / |  |  |  |
| **Security** | < | < | < | ^ | < | / |  |  |
| **Maintainability** | ^ | < | < | ^ | ^ | ^ | / |  |
| **Portability** | ^ | / | / | ^ | ^ | ^ | ^ | / |

## Kurze Erklärung
- Uns ist besonders die Usability wichtig, da die App einen relativ kleinen Bereich umfasst und wenige Funktionen liefert
- Portabilität hat den geringsten Stellenwert, da die Applikation auf nur Wenigen Plattformen angeboten werden soll und eine Portierung/Migration zwischen den Plattformen nicht vorgesehen ist, bzw. durch eine zentrale Datenbank/API bereitgestellt wird
- Performance hat ebenfalls einen geringen Stanpunkt, da nur wenige Daten verarbeitet werden (Einmal pro Minute, oder 30 Sekundentakt)
- Sicherheit ist ausgeglicken
    + Personenbezogene Daten und das WLAN in dem das Gerät hängt müssen sicher sein
    + Das Gerät selbst kann aber durch die Bewässerung einen relativ geringen Schaden anrichten