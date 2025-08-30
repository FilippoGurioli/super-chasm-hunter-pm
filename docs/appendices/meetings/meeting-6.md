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

**rpg requirements** - fino a 4.* compreso

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
        2. bottone impostazioni
        3. bottone uscita
        4. bottoni link social
            1. Discord
            2. Linktree
        5. art
            1. bottoni
                1. start
                2. impostazioni
                3. uscita
                4. link social
            2. sfondo
                1. animazione dello sfondo
    2. schermata pausa
        1. menù mappa
            1. visualizzazione mappa zone esplorate (se nel chasm)
            2. assente se nell'overworld
        2. menù items
            1. descrizione degli item in inventario
            2. caratteristiche item in inventario
        3. menù equipaggiamenti
            1. visualizzazione slot vestito
                1. informazioni relative al vestito
            2. visualizzazione slot reliquia
                1. informazioni relative alla reliquia
        4. menù impostazioni
            1. modifica impostazioni di suono
            2. modifica impostazioni dei comandi
            3. modifica impostazioni dello schermo
        5. bottone esci
            1. esci dal chasm (se nel chasm)
                1. perdita dei progressi
            2. esci dal gioco (se nell'overworld)
                1. salvataggio dei progressi
        6. art
            1. background
            2. bottoni
            3. icona
            4. menu
                1. mappa
                2. items
                3. equipaggiamento
                4. impostazioni
        7. animazioni
            1. animazione di cambio menù
    3. HUD
        1. ingresso al livello
            1. all'inizio del gioco e dopo ogni cambio livello
            2. descrizione dell'ambiente
                1. nome dell'ambiente
                2. numero del livello (parte da 1 e aumenta per ogni livello passato)
                3. flavour text
        2. effetti di danno subito
        3. effetti di transizione
            1. tra una scena e l'altra
            2. tra una stanza e l'altra
        4. boss bar
            1. presente solo se in vicinanza di un boss
            2. visualizza la vita corrente del boss

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
- durata: 1 gg
- deliverable: asset .anim (estensione speciale di unity)

2.1, 2.2, 2.3, 2.5

- assegnatario: Silvia

task 1:

- descrizione: implementare logica di gestione degli status effect (solo per vita e movimento)
- durata: 2 gg
- deliverable: codice sorgente per la gestione degli status effect

task 2:

- descrizione: implementare logica di gestione degli status effect (per arma impugnata)
- durata: 2 gg
- deliverable: codice sorgente per la gestione degli status effect

task 3:

- descrizione: implementare gestione della visualizzazione degli status effect
- durata: 1 gg
- deliverable: codice sorgente per la gestione della visualizzazione degli status effect

task 4:

- descrizione: implementare test per status effect
- durata: 1gg
- deliverable: codice di test

2.4

- assegnatario: Filippo P
- descrizione: fare art (particles + grafiche 2D) per gli status effect
- durata: 2 gg
- deliverable: asset grafici 2D per gli status effect e asset particellari

3.1

- assegnatario: Luca
- descrizione: produrre asset grafici 2D relativi al mana del protagonista
- durata: 1gg
- deliverable: asset grafici 2D: sfondo e mana

3.2

- assegnatario: Anny

task 1:

- descrizione: implementare logica di gestione del mana
- durata: 2 gg
- deliverable: codice sorgente per la gestione del mana

task 2:

- descrizione: implementare test per gestione mana
- durata: 1 gg
- deliverable: codice di test

4.1.1, 4.1.2, 4.1.3, 4.1.4

- assegnatario: Filippo G

task 1:

- descrizione: implementare logica di gestione home menu (start, uscita e link social)
- durata: 1 gg
- deliverable: codice sorgente per la gestione del home menu

task 2:

- descrizione: implementare logica di gestione impostazioni (audio, video, controlli)
- durata: 2 gg
- deliverable: codice sorgente per la gestione delle impostazioni

task 3:

- descrizione: test home menu
- durata: 1 gg
- deliverable: codice di test

4.1.5

- assegnatario: Luca

task 1:

- descrizione: creare asset 2D per il menu home
- durata: 2 gg
- deliverable: asset 2D per il menu home

task 2:

- descrizione: creare pagine social (vuote) e fornire il link per il menu home
- durata: 2h
- deliverable: link alle pagine social

4.2.1, 4.2.2, 4.2.3, 4.2.4, 4.2.5

- assegnatario: Silvia

task 1:

- descrizione: implementare logica di gestione mappa
- durata: 1 gg
- deliverable: codice sorgente per la gestione della mappa

task 2:

- descrizione: implementare logica di visualizzazione inventario
- durata: 2 gg
- deliverable: codice sorgente per la visualizzazione dell'inventario

task 3:

- descrizione: implementare visualizzazione degli equipaggiamenti
- durata: 1 gg
- deliverable: codice sorgente per la visualizzazione degli equipaggiamenti

task 4:

- descrizione: implementare logica di gestione delle impostazioni (audio, video, controlli)
- durata: 4h (a fronte di una precedente implementazione nel home menu)
- deliverable: codice sorgente per la gestione delle impostazioni

task 5:

- descrizione: implementare logica del bottone esci (pause menu)
- durata: 4h
- deliverable: codice sorgente per la logica del bottone esci

task 6:

- descrizione: implementare logica per la visualizzazione dei componenti di tutti i task precedenti
- durata: 2 gg
- deliverable: codice sorgente per la visualizzazione dei componenti di tutti i task precedenti

task 7:

- descrizione: test per tutti i task precedenti
- durata: 2 gg
- deliverable: codice di test

4.2.6

- assegnatario: Luca
- descrizione: fare art (grafiche 2D) per schermata di pausa
- durata: 2 gg
- deliverable: asset 2D per la schermata di pausa

4.2.7

- assegnatario: Filippo P
- descrizione: produzione animazioni di cambio menu
- durata: 1 gg
- deliverable: asset .anim per il cambio menu

4.3

- assegnatario: Anny

task 1:

- descrizione: HUD ingresso al livello
- durata: 1 gg
- deliverable: codice sorgente per la visualizzazione dell'HUD di ingresso al livello

task 2:

- descrizione: effetti di danno subito + effetti di transizione
- durata: 1 gg
- deliverable: codice sorgente per la visualizzazione nell'HUD di effetti di danno e effetti di transizione

task 3:

- descrizione: visualizzazione boss bar
- durata: 1 gg
- deliverable: codice per la visualizzazione della boss bar

task 4:

- descrizione: test delle task precedenti
- durata: 2 gg
- deliverable: codice di test

## :material-check: **Decisioni prese**

- struttura del WBS

## :material-rocket-launch: **Azioni da fare**  

- finire WBS
- Gestione delle risorse materiali e umane
- Gestione del cashflow

## :material-calendar: **Prossimo meeting**

31/07/2025 | 2h

## :material-account-group: **Partecipanti prossimo meeting**  

Tutto il team
