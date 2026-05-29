# SCHEMA EVENTI - KWF / ATLAS•EVENTA

Ogni entità evento deve rispettare rigorosamente la seguente struttura.
Dati non conformi comportano il blocco dell'inserimento.

## Campi Obbligatori (Set Chiuso)
* EVENT_ID: Concetto evento (ID univoco immutabile).
* INSTANCE_ID: Occorrenza temporale dell'evento.
* PLACE_ID: Codice ISTAT del luogo (Sermoneta).
* EVENT_NAME_NORMALIZED: Nome normalizzato (Chiave logica).
* CATEGORY: Categoria di appartenenza (Vedi categorie.md).
* DATE_START: Data inizio (ISO YYYY-MM-DD).
* DATE_END: Data fine (ISO YYYY-MM-DD).

## Regole di Validazione
1. Nessun altro campo è ammesso.
2. Se un dato non rientra in questi campi, deve essere scartato.
3. Evento incompleto = Non creare, parcheggia.
