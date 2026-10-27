# EEPROM

Libreria EEPROM di compatibilità per Arduino/ESP32, conservata come riferimento per applicazioni precedenti.

> **Archivio di consultazione.** La documentazione del progetto dichiara la libreria deprecata.

## Mappa del repository

| Percorso | Contenuto | File |
|---|---|---:|
| [examples/](./examples) | Esempi di utilizzo. | 3 |
| [src/](./src) | Codice sorgente principale. | 2 |

---

## Documentazione di riferimento conservata

## EEPROM

EEPROM is deprecated.  For new applications on ESP32, use Preferences.  EEPROM is provided for backwards compatibility with existing Arduino applications.
EEPROM is implemented using a single blob within NVS, so it is a container within a container. As such, it is not going to be a high performance storage method.  Preferences will directly use nvs, and store each entry as a single object therein.
# EEPROM
# EEPROM
