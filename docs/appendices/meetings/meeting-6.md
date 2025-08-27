# Meeting 24/07/25 | 2h

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

## :material-note-text: **Note**  

**PIANO OPERATIVO**

0. Concentrarsi solo sul sotto albero RPG (iterazione 1)
1. Dividersi in sotto gruppi
2. Suddividersi in modo uguale l'albero
3. analizzare ogni foglia dell'albero assegnato
4. derivare 1 o più task operativi da svolgere

**CRITERI PER DEFINIRE UNA TASK**

- definizione chiara di quando una task INIZIA e FINISCE
- producono uno (o più) deliverables
- tempi e costi stimati
- durata intorno a 1 giorno (i.e. 8 ore)
- non richiede interruzioni per la sua completa esecuzione
- persona referente di quella task

Una task deve contenere:

- assegnatario
- descrizione
- durata
- deliverable

**SVOLGIMENTO DEL PIANO**

**rpg requirements**

1. vita del giocatore (a cuori)
    1. art dei vari oggetti che riguardano la vita
        1. sfondo
        2. cuore pieno
        3. cuore vuoto
        4. quarti di cuore
    2. implementazione logica a cuori
        1. reazione al danno
        1. perdita di tutti i quarti che non riempiono un cuore
        2. perdita di 1 cuore
        3. impossibilità di movimento
        2. reazione alle cure
        1. recupero di 1 o più quarti di cuore
        3. damage cooldown
        1. dopo aver subito danno ci sarà un lasso di tempo di invincibilità per il player
    3. animazioni
        1. ricezione danno
2. status effect
    1. stato applicato al giocatore
    2. ha una durata di tempo
    3. categorie
        1. effetto risolto all'inizio del lasso di tempo
            1. alla fine riapplica l'effetto al contrario
        2. effetto risolto lungo tutto il lasso di tempo
    4. art
    5. logica
        1. sia assoluti che percentuali
        2. guadagno/perdita di vita
        3. guadagno/perdita di vita massima
        4. guadagno/perdita danno dell'arma impugnata
        5. guadagno/perdita della velocità di movimento
        6. guadagno/perdita della velocità di recupero mana
3. mana del giocatore
    1. art
        1. background
        2. icona mana vuota
        3. icona mana piena
        4. icona mana in caricamento
    2. logica
        1. contatore con un valore massimo
        2. parte al valore massimo
        3. si ricarica ad una velocità costante
        4. si consuma quando la risoluzione di un effetto di un item richiede mana
4. schermate di pausa/home/HUD
    1. schermata home
        1. bottone di start
        1. logica
        2. art
        2. bottone impostazioni
        1. logica
        2. art
        3. bottone uscita
        1. logica
        2. art
        4. bottoni link social
        1. Discord
        2. Linktree
        5. sfondo
        1. animazione dello sfondo
    2. schermata pausa
        1. menù mappa
        1. visualizzazione mappa zone esplorate (se nel chasm)
        2. assente se nell'overworld
        3. art
        2. menù items
        1. descrizione degli item in inventario
        2. caratteristiche item in inventario
        3. art
        3. menù equipaggiamenti
        1. visualizzazione slot vestito
            1. informazioni relative al vestito
        2. visualizzazione slot reliquia
            1. informazioni relative alla reliquia
        4. menù impostazioni
        1. modifica impostazioni di suono
        2. modifica impostazioni dei comandi
        3. modifica impostazioni dello schermo
        4. art
        5. bottone esci
        1. esci dal chasm (se nel chasm)
            1. perdita dei progressi
        2. esci dal gioco (se nell'overworld)
            1. salvataggio dei progressi
        3. art
        6. art
        1. background
        2. bottoni
        3. icone
        7. animazioni
        1. animazione di cambio menù
    3. HUD
        1. vita
        1. visualizzare la vita del player
        2. inventario
        1. visualizzazione di tutto l'inventario
        2. visualizzazione dell'item correntemente impugnato
        3. mana
        1. visualizzazione del mana corrente
        4. ingresso al livello
        1. all'inizio del gioco e dopo ogni cambio livello
        2. descrizione dell'ambiente
            1. nome dell'ambiente
            2. numero del livello (parte da 1 e va su per ogni livello passato)
            3. flavour text
        5. status effect
        6. effetti di danno subito
        7. effetti di transizione
        1. tra una scena e l'altra
        2. tra una stanza e l'altra
        8. boss bar
        1. presente solo se in vicinanza di un boss
        2. visualizza la vita corrente del boss
        9. denaro corrente
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

**gruppi**

G1: Design - Luca, Filippo P

G2: Sviluppo - Filippo G, Silvia, Anny

**suddivisione albero**

La suddivisione è fatta in modo tale che il team di design si concentri sugli aspetti visivi e di interfaccia del gioco, mentre il team di sviluppo si occupi della logica di gioco.

Ad esempio, per quanto riguarda il macro requirement 1 *vita del giocatore a cuori*:

G1: sottoalbero 1.1 e 1.3
G2: sottoalbero 1.2

E così via per tutti gli altri

**analisi**

1.1

- assegnatario: Luca
- descrizione: produrre asset grafici 2D relativi alla vita del protagonista
- durata: 1 gg
- deliverable: asset grafici 2D: sfondo, cuore e quarti di cuore

1.2

- assegnatario: Filippo G

task 1:

- descrizione: implementare la logica di gestione della vita a cuori
- durata: 2 gg
- deliverable: creazione di uno o più script per la gestione della vita a cuori 

task 2:

- descrizione: implementazione di uno script che gestisca la sua visualizzazione
- durata: 1 gg
- deliverable: script che gestisca la visualizzazione della vita a cuori

task 3:

- descrizione: implementazione test
- durata: 1 gg
- deliverable: codice di test

1.3

- assegnatario: Filippo P
- descrizione: creare l'animazione del *flinching* tramite Blender
- deliverable: asset .anim (estensione speciale di unity)

2.1, 2.2, 2.3, 2.5

!!! DIVIDERE IN PIÙ TASKS, POSSIBILE ANCHE DIRE CHE NON SI POSSA MEGLIO DEFINIRE !!!

2.4

!!! ARRIVARE FINO A 4.*, POI ANDARE AL MEETING SUCCESSIVO !!!

## :material-check: **Decisioni prese**

- struttura del WBS

## :material-rocket-launch: **Azioni da fare**  

- Gestione delle risorse materiali e umane
- Gestione del cashflow

## :material-calendar: **Prossimo meeting**

31/07/2025 | 2h

## :material-account-group: **Partecipanti prossimo meeting**  

- Luca
- Filippo G