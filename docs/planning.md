# Planning

Dopo l'accettazione del progetto, la fase di pianificazione ha l'obiettivo di tradurre i requisiti iniziali in un piano operativo dettagliato, con l'intento di ridurre i rischi e massimizzare le probabilità di successo.  

I principali *deliverable* di questa fase includono:

- **Project Definition Statement (PDS)**: composto da Game Design Document (GDD), Art Bible e Technical Design Document (TDD);
- **Work Breakdown Structure (WBS)**: traduce i requisiti (RBS) in task operativi;
- **Resource Management Plan**: definisce le risorse previste e le modalità di allocazione;
- **Project Network Diagram**: rappresenta graficamente le attività e le loro dipendenze;
- **Gantt Chart**: cronoprogramma delle attività, milestone e tempistiche;
- **Risk Management Plan**: identifica, analizza e pianifica le risposte ai rischi;
- **Project Proposal**: documento di sintesi che definisce obiettivi, risorse e tempi di realizzazione.

La documentazione è elaborata attraverso *Joint Project Planning Sessions* tra i membri del team.

- [Meeting 5](./appendices/meetings/meeting-5.md)

## Iterazioni

Si prevedono 5 iterazioni, 1 per ogni macro genere che il prodotto deve avere (RPG, rogue-like e building), una di rifinitura e una finale di marketing e pubblicazione. È obbligatorio specificare che le operazioni di marketing verranno eseguite durante tutta la fase di sviluppo al fine di costruire una community e mantenerla viva. Con l'ultima iterazione si intende il completamento delle attività di marketing e la preparazione per il lancio del prodotto.

La documentazione successiva è da ritenersi relativa alla prima iterazione, fatta eccezione per il PDS che sarà aggiornato piuttosto che riscritto ex novo ad ogni ciclo.

Ogni iterazione porta anche al raggiungimento di una milestone. Le milestone sono così definite:

- **Milestone 1**: Completamento delle feature RPG
- **Milestone 2**: Completamento delle feature rogue-like
- **Milestone 3**: Completamento delle feature di building
- **Milestone 4**: Completamento azioni di rifinitura
- **Milestone 5**: Completamento azioni di marketing, finalizzazione e pubblicazione

---

## Project Definition Statement (PDS)

Il **PDS** raccoglie le specifiche di dettaglio necessarie per l'esecuzione del progetto. Durante la fase di *Execution*, il team ha fatto riferimento a questo documento per definire *come* realizzare ciascun requisito.

Il PDS è articolato in tre sotto-documenti principali:

- **Game Design Document (GDD)**  
  Contiene tutte le scelte di game design: genere, gameplay, meccaniche di gioco e motivazioni creative. Redatto dal Game Designer. Non include analisi tecniche o implementative.

- **Art Bible**  
  Definisce lo stile visivo: concept art, palette colori, design dei personaggi, ambientazioni e linee guida estetiche. Garantisce coerenza visiva e viene redatto dall'Art Director.

- **Technical Design Document (TDD)**  
  Sviluppato dal CTO sulla base di POS, RBS, GDD e Art Bible. Definisce architettura tecnica, tecnologie, testing, pipeline di sviluppo e scelte implementative.

## Work Breakdown Structure (WBS)

Per redigere la WBS il team ha seguito un approccio strutturato come segue:

1. si formano diversi gruppi all'interno del team, ciascuno responsabile di un sottoinsieme di requisiti (i.e. *subteam approach*).
2. Ogni team deve analizzare tutti i nodi foglia del sottoalbero del RBS assegnatogli.
3. Ogni nodo analizzato deve portare a 1 o più task operativi da svolgere.

Una volta fatto ciò, il team si raduna per stabilire un ordine di priorità di ogni task seguendo la filosofia *MoSCoW*.

Il documento risultante è il seguente:

- [WBS](./appendices/planning/WBS.md)

## Resource Management Plan

- Stima delle risorse materiali
- Stima delle risorse umane
- Stima competenze -> skill x attività | skill x personale = attività x personale
- Cashflow management

## Project Network Diagram + Gantt Chart

1. Stima del lavoro -> giudizio dell'"esperto"
2. Stima del tempo -> delphi

- Creare il PND

---

Come costruire un Initial Dependency Diagram
1. Per ogni task, scrivere sul Post-It il suo ID, il nome e la durata.
2. Posizionare il Post-It sulla parte destra della lavagna (whiteboard).
3. Posizionare lo start node sulla parte sinistra della lavagna.
4. Muovere tutti i task senza un predecessore sulla parte sinistra della
lavagna e collegarli allo start node.
5. Muovere a sinistra tutti i task che si trovano sulla parte destra, ma che
hanno tutti i predecessori già sulla sinistra e collegali con una singola
linea ai predecessori.
6. Ripetere il passo 5 finché tutti i task sono stati spostati a sinistra.

---

- Comprimere se necessario
- Derivare il Gantt
- Creare una scope bank

## Risk Management

Analizzare ogni rischio espresso nella Analisi dei Rischi, analizzare la strategia risolutiva e commentare come la si intende attuare

## Gestione del cambiamento

???

## Project Proposal

- Executive Summary
- Background
- Objectives
- Overview of the Approach to be Taken
- Detailed Statement of Work
- Time and Cost Summary
- Appendices

## Lancio