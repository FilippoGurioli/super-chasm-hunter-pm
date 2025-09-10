# Chiusura

La fase di chiusura è l'ultima fase del ciclo di vita del progetto. In questo momento, il progetto viene formalmente accettato dal cliente, viene completata la documentazione finale e viene anche fatto il collaudo sul campo. In ultima istanza si valutano le performance del progetto e si raccolgono le lezioni apprese per futuri progetti.

## Procedura di accettazione

La procedura di accettazione è un processo formale che assicura che il progetto sia stato completato secondo i requisiti e le aspettative del cliente. Nella fattispecie si verifica che:

- tutti i deliverable siano stati consegnati;
- tutti i requisiti siano stati soddisfatti;
- tutti i problemi aperti siano stati risolti;
- i business values siano stati raggiunti;
- tutti i documenti siano stati completati e archiviati.

## Collaudo

È stato fatto anche un collaudo sul campo per verificare che il sistema funzioni correttamente nell'ambiente operativo del cliente. Questo include:

- test di integrazione
- test di performance
- test di accettazione utente (UAT)

## Installazione

Sin dallo scoping si era prestabilito che l'installazione sarebbe avvenuta tramite la piattaforma [Steam](https://store.steampowered.com/). In generale questa utilizza la strategia di cut-over per l'installazione ma, tramite apposite configurazioni, si può modificare parte di questo comportamento. Nella fattispecie, al fine di avere la storicità dell'applicazione, si è deciso di utilizzare una combinazione di cut-over e parallel.

### Cut-Over

Per quanto riguarda la prima pubblicazione di fatto è un cut-over, ovvero un "rimpiazzo" totale del sistema precedente. Ovviamente, essendo la prima pubblicazione, non c'è un vero e proprio sistema precedente ma si intende che l'applicazione viene resa disponibile a tutti gli utenti e per intero.

Se si lasciassero le configurazioni di default, Steam utilizzerebbe il cut-over anche per quanto riguarda gli aggiornamenti successivi. La piattaforma infatti forza l'aggiornamento dell'applicazione non appena questa viene aperta, rendendo impossibile l'utilizzo della versione precedente. Per ovviare a questo problema, si è deciso di modificare questa configurazione in modo che l'utente possa scegliere se aggiornare o meno l'applicazione e, nel caso, anche di poter fare roll-back a versioni precedenti.

### Parallel

Come detto, per gli aggiornamenti successivi si utilizza una procedura di installazione in parallelo, in cui il nuovo sistema viene installato accanto a quello esistente. Questa scelta è stata presa per permettere agli utenti maggiore flessibilità e per permettere agli sviluppatori di testare il nuovo sistema senza interrompere l'uso del sistema attuale. In questo modo, gli utenti possono continuare a utilizzare la versione precedente dell'applicazione mentre testano la nuova versione, riducendo il rischio di interruzioni del servizio.

## Documentazione

Per poter decretare concluso il progetto è necessario revisionare, aggiornare e/o completare tutta la documentazione dello stesso. In particolare, la documentazione da completare è:

- Project Overview Statement (POS)
- Analisi dei requisiti
- Analisi finanziaria
- Analisi dei rischi
- Documentazione tecnica
  - Game Design Document
  - Technical Design Document
  - Art Bible
- Gantt Chart
- Work Breakdown Structure (WBS)
- Project Network Diagram (PND)
- Issue Log
- Work Packages
- Andamento degli indici di performance
- Guida utente

## Audit

A fine progetto viene fatto un audit per valutare le performance del progetto e per identificare le lezioni apprese. Il team ritiene di fondamentale importanza stendere un documento di questo tipo per poter migliorare i processi e le pratiche di gestione dei progetti futuri. Le domande durante questo meeting spaziavano da quelle più tecniche, come "I requisiti sono stati rispettati?" o "Gli obiettivi del progetto sono stati raggiunti?", a quelle più generali come "Cosa ha generato i maggiori problemi?", "Quali problemi sono stati risolti in modo efficace?" o "Cosa si potrebbe migliorare in futuro?".

Oltre agli obiettivi più tecnici, che riguardavano semplicemente le caratteristiche del prodotto, si sono ampiamente rispettati anche gli altri obiettivi. Nella fattispecie:

- la pubblicazione del prodotto è avvenuta il 13/10/2026, in corrispondenza dello *Steam Next Fest*, rispettando la scadenza prefissata di inizio 2027;
- tutta la documentazione prodotta ha gettato le fondamenta per standardizzare i processi e i tool utilizzati, garantendo al team una solida base di conoscenze per affrontare progetti futuri con maggiore efficienza e autonomia;
- il ritorno attuale sugli investimenti (ROI) è del 120%, con ricavi che superano i 12.000€, coprendo ampiamente le spese annue della partita IVA, che ammontano a circa 6.300€.

In conclusione, il progetto ha rappresentato un'importante occasione di crescita e apprendimento, permettendo al team di acquisire nuove competenze e raggiungere gli obiettivi prefissati con successo.
