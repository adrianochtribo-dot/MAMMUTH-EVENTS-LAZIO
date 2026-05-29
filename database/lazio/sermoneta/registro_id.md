# REGISTRO ID - KWF / ATLAS•EVENTA

Contatore sequenziale progressivo per l'univocità delle entità (eventi, istanze, luoghi).

## Regole Fondamentali
* EVENT_INDEX: ID numerico sequenziale (Partenza: 1).
* VINCOLO: È vietato creare ID saltati, duplicati o riordinati.
* AUTORITÀ: In caso di dubbi sull'ultimo ID, fermare il processo e verificare.
* STATO ATTUALE: Ultimo ID utilizzato = 0.
