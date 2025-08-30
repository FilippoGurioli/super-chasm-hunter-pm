# Meeting 31/07/2025 | 2h

## :material-target: **Scopo**

Joint Project Planning Session

## :material-format-list-numbered: **Scaletta**  

- WBS

## :material-account-group: **Partecipanti**  

Tutto il team:

- Luca
- Filippo G
- Filippo P
- Anny
- Silvia

## :material-paperclip: **Documentazione allegata**  

- [RBS](../scoping/RBSs/building-requirements.md)
- [Analisi dei requisiti](../scoping/requirement-analysis.md)
- [POS](../scoping/POS.md)
- [Meeting 6](./meeting-6.md)

## :material-note-text: **Note**  

**rpg requirements** - da 5.* a 9.* compreso

5. sistema di movimento
    1. movimento a 4 direzioni
    2. muove il player nella direzione corrispondente (N, S, W, E)
6. sistema di orientamento
    1. basato sulla posizione del mouse
    2. il player deve sempre guardare in direzione del mouse
7. sistema di combattimento
    1. al click sinistro del mouse si risolve l'effetto base dell'item impugnato
        1. applicazione di tutti gli status effect relativi all'effetto base
        2. rimozione delle risorse necessarie alla risoluzione dell'effetto base
        3. applicazione dell'effetto base
    2. al click destro del mouse si risolve l'effetto speciale dell'item impugnato
        1. applicazione di tutti gli status effect relativi all'effetto speciale
        2. rimozione delle risorse necessarie alla risoluzione dell'effetto speciale
        3. applicazione dell'effetto speciale
8. salvataggio di gioco
    1. logica di *quando* si può salvare
        1. perdita dei progressi se si muore/perde nel Chasm
        2. mantenimento dei dati se si esce dal Chasm vivi
        3. salvataggio tramite menu fuori dal Chasm
    2. logica di *cosa* si deve salvare
        1. inventario
            1. tutti gli item
                1. nome
                2. effetto
                3. quantità
            2. l'item correntemente impugnato
        2. vita corrente
            1. vita attuale
            2. vita massima
            3. mana corrente
                1. mana attuale
                2. mana massimo
            4. oggetti piazzati nell'overworld
                1. nome
                2. orientamento
            5. data in gioco (*in-game date*)
9. negozi
    1. sono sia nell'overworld che nel chasm
    2. mercante
        1. ci interagisci per vendere item
            1. aggiunge il valore al denaro in possesso dal player
            2. rimuove l'item all'inventario del player
        2. mercanti diversi possono fare offerte diverse
        3. mostrano un dialogo interattivo per accettare/rifiutare l'offerta
        4. art
            1. art del mercante
            2. art del dialogo
    3. mercanzia
        1. espone gli articoli in vendita
        2. ci interagisci
            1. compri uno degli oggetti in vendita
        3. gli item in vendita possono
            1. essere infinitamente acquistabili
            2. essere acquistabili una sola volta
    4. può essere aperto o chiuso
        1. dipende dal giorno
10. denaro
    1. ha un valore massimo
    2. non può scendere sotto zero
    3. aumenta quando il player tocca item monete nel gioco
        1. monete aumentano il valore del denaro in modo variabile
    4. aumenta quando il player vende item a mercanti
    5. diminuisce quando il player compra item dai mercanti
11. munizioni
    1. ha un valore massimo
    2. non può scendere sotto zero
    3. aumenta quando il player *trova* altre munizioni
        1. raccoglie
        2. compra
        3. crea
    4. diminuisce quando un'arma le utilizza

**analisi**

5.1, 5.2

- assegnatario: Filippo G

task 1:

- descrizione: implementare logica per il movimento del protagonista
- durata: 1 gg
- deliverable: codice sorgente per il movimento del protagonista

task 2:

- descrizione: test per movimento protagonista
- durata: 1 gg
- deliverable: codice di test

6.1, 6.2

- assegnatario: Silvia

task 1:

- descrizione: implementare logica per l'orientamento del protagonista
- durata: 1 gg
- deliverable: codice sorgente per l'orientamento del protagonista

task 2:

- descrizione: test per l'orientamento del protagonista
- durata: 1 gg
- deliverable: codice di test

7.1.1, 7.1.2, 7.1.3

- assegnatario: Anny

task 1:

- descrizione: implementare logica per la risoluzione dell'effetto base
- durata: 3 gg
- deliverable: codice sorgente

task 2:

- descrizione: test logica risoluzione effetti base
- durata: 1 gg
- deliverable: codice di test

task 3:

- descrizione: visualizzazione risoluzione effetti
- durata: 1 gg
- deliverable: codice sorgente

7.2.1, 7.2.2, 7.2.3

- assegnatario: Anny

task 1:

- descrizione: implementare logica per la risoluzione dell'effetto speciale
- durata: 1 gg (a fronte dell'implementazione della risoluzione effetto base)
- deliverable: codice sorgente

task 2:

- descrizione: test risoluzione effetto speciale
- durata: 1 gg
- deliverable: codice di test

8.1.1, 8.1.2, 8.1.3

- asegnatario: Filippo G

task 1:

- descrizione: implementare logica per il salvataggio di gioco (quando salvare)
- durata: 1 gg
- deliverable: codice sorgente

task 2:

- descrizione: test logica per il salvataggio (quando)
- durata: 1 gg
- deliverable: codice di test

8.2.1.1.1, 8.2.1.1.2, 8.2.1.1.3, 8.2.1.2

- assegnatario: Filippo G

task 1:

- descrizione: implementare logica per il salvataggio di gioco (inventario + item in mano)
- durata: 1 gg
- deliverable: codice sorgente

task 2:

- descrizione: test logica per il salvataggio (inventario + item in mano)
- durata: 1 gg
- deliverable: codice di test

8.2.2.1, 8.2.2.2, 8.2.2.3.1, 8.2.2.3.2, 8.2.2.4.1, 8.2.2.4.2, 8.2.2.5

- assegnatario: Filippo G

task 1:

- descrizione: implementare logica per il salvataggio di gioco (vita + mana + data)
- durata: 1 gg
- deliverable: codice sorgente

task 2:

- descrizione: test logica per il salvataggio di gioco (vita + mana + durata)
- durata: 1 gg
- deliverable: codice di test

task 3:

- descrizione: implementare logica per il salvataggio di gioco (item piazzati)
- durata: 1 gg
- deliverable: codice sorgente

task 4:

- descrizione: test logica per il salvataggio di gioco (item piazzati)
- durata: 1 gg
- deliverable: codice di test

9.1, 9.2.1.1, 9.2.1.2, 9.2.2, 9.2.3

- assegnatario: Silvia

task 1:

- descrizione: implementazione logica per vendita item ai negozi
- durata: 1 gg
- deliverable: codice sorgente

task 2:

- descrizione: implementare logica per gestione dialoghi
- durata: 3 gg
- deliverable: codice sorgente

task 3:

- descrizione: test logica per vendita item ai negozi + dialoghi
- durata: 2 gg
- deliverable: codice di test

9.2.4.1, 9.2.4.2

- assegnatario: Filippo P

task 1:

- descrizione: creare asset del mercante
- durata: 2 gg
- deliverable: asset

task 2:

- descrizione: creare asset per i dialoghi (sfondi, font etc)
- durata: 2 gg
- deliverable: asset

9.3.1, 9.3.2.1, 9.3.3.1, 9.3.3.2, 9.4.1

- assegnatario: Anny

task 1:

- descrizione: implementazione acquisto oggetti dai mercati
- durata: 2 gg
- deliverable: codice sorgente

task 2:

- descrizione: implementazione logica di negozio aperto/chiuso
- durata: 1 gg 
- deliverable: codice sorgente

task 3:

- descrizione: test logica acquisto e apertura
- durata: 2 gg
- deliverable: codice di test

10.1, 10.2, 10.3.1, 10.4, 10.5

- assegnatario: Filippo G

task 1:

- descrizione: implementare logica denaro
- durata: 1 gg
- deliverable: codice sorgente

task 2:

- descrizione: testare logica denaro
- durata: 1 gg
- deliverable: codice di test

11.1, 11.2, 11.3.1, 11.3.2, 11.3.3, 11.4

- assegnatario: Silvia

task 1:

- descrizione: implementare logica munizioni
- durata: 1 gg
- deliverable: codice sorgente

task 2:

- descrizione: test logica munizioni
- durata: 1 gg
- deliverable: codice di test

## :material-check: **Decisioni prese**

- struttura del WBS

## :material-rocket-launch: **Azioni da fare**  

- Gestione delle risorse materiali e umane
- Gestione del cashflow

## :material-calendar: **Prossimo meeting**

31/07/2025 | 2h

## :material-account-group: **Partecipanti prossimo meeting**  

Filippo G
Luca