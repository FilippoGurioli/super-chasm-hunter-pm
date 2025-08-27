# Pianificazione

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

## Gestione del cambiamento

La gestione del cambiamento è un aspetto cruciale del progetto, poiché consente di adattarsi alle nuove esigenze e alle sfide emergenti. Durante la fase di pianificazione, è stato sviluppato un piano di gestione del cambiamento che include:

1. **Identificazione dei cambiamenti**: Raccogliere e documentare tutte le richieste di cambiamento provenienti dai membri del team e dagli stakeholder.
2. **Valutazione dell'impatto**: Analizzare l'impatto di ciascun cambiamento proposto sui requisiti, sul piano di progetto e sulle risorse.
3. **Approvazione dei cambiamenti**: Stabilire un processo di approvazione formale per i cambiamenti, coinvolgendo le parti interessate chiave.
4. **Comunicazione**: Assicurarsi che tutte le parti interessate siano informate dei cambiamenti approvati e delle loro implicazioni.
5. **Monitoraggio e revisione**: Monitorare l'implementazione dei cambiamenti e rivedere il piano di progetto di conseguenza.

## Gestione del Rischio

In questa fase si è anche voluto indagare più a fondo sui [rischi](./appendices/scoping/risk-analysis.md) individuati durante lo scoping. Per ognuno di essi è stata effettuata un'analisi sulla strategia risolutiva, cercando di concretizzarla in attività specifiche.

- [Gestione del rischio](./appendices/planning/risk-management.md)

## Iterazioni

Si prevedono 5 iterazioni, una per ogni macro genere che il prodotto deve avere (RPG, rogue-like e building), una di rifinitura e una finale di marketing e pubblicazione. È obbligatorio specificare che le operazioni di marketing verranno eseguite durante tutta la fase di sviluppo al fine di costruire una community e mantenerla viva. Con l'ultima iterazione si intende il completamento delle attività di marketing e la preparazione per il lancio del prodotto.

La documentazione successiva è da ritenersi relativa alla prima iterazione, fatta eccezione per il PDS che sarà aggiornato piuttosto che riscritto ex novo ad ogni ciclo.

Ogni iterazione porta anche al raggiungimento di una milestone. Le milestone sono così definite:

- **Milestone 1**: Completamento delle feature RPG;
- **Milestone 2**: Completamento delle feature rogue-like;
- **Milestone 3**: Completamento delle feature di building;
- **Milestone 4**: Completamento azioni di rifinitura;
- **Milestone 5**: Completamento azioni di marketing, finalizzazione e pubblicazione.

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

Durante la fase di pianificazione è stata effettuata l'analisi delle risorse necessarie per l'iterazione. Nella fattispecie si sono analizzate e stimate le risorse materiali, le risorse umane e le competenze necessarie per ciascuna attività. Una volta completata la stima delle risorse materiali è anche stato redatto una cashflow management table.

- [Resource Management](./appendices/planning/resource-management.md)
- [Cashflow Management](./appendices/planning/cashflow-management.md)

## Project Network Diagram e Gantt Chart

Una volta saputi tutti i task relativi a questa iterazione, il team ha proceduto con la stima del lavoro e del tempo necessario.

Per stima del lavoro necessario si intende definire con dettaglio massimo in cosa consiste la task in analisi. Per stima del tempo invece si intende il tempo necessario per completare la task.

Per calcolare le stime sopra citate sono stati adottati due approcci diversi: per la stima del lavoro si è adottato il *giudizio dell'esperto*, mentre per la stima del tempo si è utilizzato il *metodo Delphi*. Questa decisione è stata presa per tre ragioni:

1. Il team crede che il modo migliore per stabilire la complessità di un'attività sia basarsi sull'esperienza di chi l'ha già svolta in passato.
2. Una volta che tutto il team ne ha compreso la complessità, una stima della task tramite *metodo Delphi* risulta più accurata.
3. Per perseguire al meglio l'obiettivo di accumulare esperienza, il team si sottopone di sua volontà a quante più strategie possibili, al fine di poterne valutare pregi e difetti in prima persona.

Una volta che ogni task ha un ID, una descrizione, una stima del lavoro e una stima del tempo, il team ha proceduto a costruire Project Network Diagram e, di conseguenza, anche il Gantt Chart.

- [Project Network Diagram](./appendices/planning/PND.md)
- [Gantt Chart](./appendices/planning/gantt.md)

Durante le analisi e le stime si è anche accumulata una *scope bank* pari ad una maggiorazione del 20%. Questa servirà in fase di esecuzione dell'iterazione per gestire eventuali imprevisti o cambiamenti di requisiti.

## Project Proposal

Alla fine della pianificazione è stato redatto il [Project Proposal](./appendices/planning/project-proposal.md), che include:

- Executive Summary
- Background
- Objectives
- Overview of the Approach to be Taken
- Detailed Statement of Work
- Time and Cost Summary
- Appendices

Questo è stato sottoposto nel [Joint Project Planning Session finale](./appendices/meetings/meeting-5.md) al PM e al CEO per la conferma o aggiornamento.

## Lancio

Dopo l'accettazione del Project Proposal, il team procederà con il lancio dell'iterazione. Verranno definiti i tool e i template necessari per l'esecuzione. Verranno anche definite le regole operative del team e le modalità di comunicazione. Infine, verranno assegnate le risorse e finalizzata la schedula dell'iterazione. 
