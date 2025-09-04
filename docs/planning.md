# Pianificazione

Dopo l'accettazione del progetto, la fase di pianificazione ha l'obiettivo di tradurre i requisiti iniziali in un piano operativo dettagliato, con l'intento di ridurre i rischi e massimizzare le probabilità di successo.

I principali _deliverable_ di questa fase includono:

- **Project Definition Statement (PDS)**: composto da Game Design Document (GDD), Art Bible e Technical Design Document (TDD);
- **Work Breakdown Structure (WBS)**: traduce i requisiti (RBS) in task operativi;
- **Resource Management Plan**: definisce le risorse previste e le modalità di allocazione;
- **Project Network Diagram**: rappresenta graficamente le attività e le loro dipendenze;
- **Gantt Chart**: cronoprogramma delle attività, milestone e tempistiche;
- **Risk Management Plan**: identifica, analizza e pianifica le risposte ai rischi;
- **Project Proposal**: documento di sintesi che definisce obiettivi, risorse e tempi di realizzazione.

La documentazione è elaborata attraverso _Joint Project Planning Sessions_ tra i membri del team.

- [Meeting 5](./appendices/meetings/meeting-5.md)
- [Meeting 6](./appendices/meetings/meeting-6.md)
- [Meeting 7](./appendices/meetings/meeting-7.md)
- [Meeting 8](./appendices/meetings/meeting-8.md)
- [Meeting 9](./appendices/meetings/meeting-9.md)
- [Meeting 10](./appendices/meetings/meeting-10.md)
- [Meeting 11](./appendices/meetings/meeting-11.md)

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

## Gestione Appalti

Dalle analisi fatte durante la gestione del rischio è emersa la necessità di esternalizzare alcune componenti del progetto. In particolare, si è deciso di affidare a terzi la realizzazione delle AI dei nemici, in quanto rallenterebbe significativamente lo sviluppo.

- [Gestione Appalti](./appendices/planning/procurement-analysis.md)

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

Il **PDS** raccoglie le specifiche di dettaglio necessarie per l'esecuzione del progetto. Durante la fase di _Execution_, il team ha fatto riferimento a questo documento per definire _come_ realizzare ciascun requisito.

Il PDS è articolato in tre sotto-documenti principali:

- **Game Design Document (GDD)**  
  Contiene tutte le scelte di game design: genere, gameplay, meccaniche di gioco e motivazioni creative. Redatto dal Game Designer. Non include analisi tecniche o implementative.

- **Art Bible**  
  Definisce lo stile visivo: concept art, palette colori, design dei personaggi, ambientazioni e linee guida estetiche. Garantisce coerenza visiva e viene redatto dall'Art Director.

- **Technical Design Document (TDD)**  
  Sviluppato dal CTO sulla base di POS, RBS, GDD e Art Bible. Definisce architettura tecnica, tecnologie, testing, pipeline di sviluppo e scelte implementative.

## Resource Management Plan

Durante la fase di pianificazione è stata effettuata l'analisi delle risorse necessarie per l'iterazione. Nella fattispecie si sono analizzate e stimate le risorse materiali, le risorse umane e le competenze necessarie per ciascuna attività.

- [Resource Management](./appendices/planning/resource-management.md)

## Strumenti di pianificazione

Data la già alta precisione con cui certi requisiti sono stati definiti, il team ha deciso di redigere la WBS in modo particolare. La Work Breakdown Structure (WBS) non scompone maggiormente i requisiti (in quanto già dettagliati), al contrario, funge da "ponte" tra la RBS e il Project Network Diagram (PND).

Per redigere la WBS il team ha seguito un approccio strutturato come segue:

1. si formano diversi gruppi all'interno del team, ciascuno responsabile di un sottoinsieme di requisiti (i.e. _subteam approach_).
2. Ogni team deve analizzare tutti i nodi foglia del sottoalbero del RBS assegnatogli.
3. Dall'analisi dei nodi i gruppi devono estrarre una serie di task operativi.

Successivamente, si è sfruttato il _metodo Delphi_ per decidere le stime di tempo di ogni task. Unendo tutte le informazioni ottenute, si è quindi potuto redigere il PND e Gantt Chart.

**Nota**: per calcolare le stime sopra citate sono stati adottati due approcci diversi: per la stima del lavoro si è adottato il _giudizio dell'esperto_, mentre per la stima del tempo si è utilizzato il _metodo Delphi_. Questa decisione è stata presa per tre ragioni:

1. Il team crede che il modo migliore per stabilire la complessità di un'attività sia basarsi sull'esperienza di chi l'ha già svolta in passato.
2. Una volta che tutto il team ne ha compreso la complessità, una stima della task tramite _metodo Delphi_ risulta più accurata.
3. Per perseguire al meglio l'obiettivo di accumulare esperienza, il team si sottopone di sua volontà a quante più strategie possibili, al fine di poterne valutare pregi e difetti in prima persona.

I documenti risultanti sono i seguenti:

- [WBS](./appendices/planning/WBS.md)
- [Project Network Diagram](./appendices/planning/PND.md)
- [Gantt Chart](./appendices/planning/gantt.md)

Durante le analisi e le stime si è anche accumulata una _scope bank_ pari ad una maggiorazione del 15%. Questa servirà in fase di esecuzione dell'iterazione per gestire eventuali imprevisti o cambiamenti di requisiti.

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
