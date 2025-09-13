# Launching

Una volta definito il piano operativo derivante dagli obiettivi del progetto, è il momento di lanciare l'iterazione. In questa fase si definiscono le regole operative del team, si attua l'implementazione delle task, monitorando il progresso e risolvendo i problemi che si presentano.

## Kick-off Meeting

In data 01/10/2025 si è tenuto il kick-off meeting dell'iterazione, con la partecipazione di tutto il team. Questo momento è stato utilizzato per ufficializzare la partenza del progetto oltre che scandire una volta ancora a tutto il team gli obiettivi, e come questi siano stati concretizzati all'interno delle task. Si è dettagliata la milestone a cui si vuole arrivare con questa iterazione, dando anche un contesto generale su tutto il piano del progetto.

Sono state inoltre definite le strategie da adottare in fase di implementazione tra cui stile di lavoro, strumenti da utilizzare, testing, gestione dei problemi e delle decisioni.

## Regole operative

Sono state stabilite alcune regole operative per il team, al fine di affrontare al meglio le sfide del progetto. Queste includono:

- **problem solving**: stabilire un approccio metodico alla risoluzione di problemi per garantire velocità ed efficienza.
- **decision making**: definire un processo decisionale chiaro per evitare ambiguità e ritardi.
- **conflict resolution**: adottare tecniche per gestire e risolvere i conflitti all'interno del team in modo costruttivo.
- **brainstorming**: definire momenti e modalità per il brainstorming creativo.
- **team meetings**: stabilire la frequenza e l'agenda delle riunioni di team per mantenere tutti allineati.

### Problem solving

Per risolvere i problemi il team ha scelto di adottare la strategia a 5 passi:

1. definire il problema e il suo proprietario
2. analizzare il problema attraverso i dati e capirne le cause
3. generare delle idee a partire da questi dati
4. valutare le idee prioritizzando le migliori
5. implementare l'idea migliore attraverso un piano d'azione

Se il problema non si risolve si ricomincia l'algoritmo da capo.

I vari problemi si affronteranno in meeting appositi in cui solo il Project Manager, il problem owner e possibili supporti parteciperanno, al fine di evitare di bloccare tutto il processo produttivo.

Ogni problema andrà tracciato tramite l'issue log.

### Decision making

Se non specificato diversamente, tutte le decisioni verranno prese in modo _collaborativo_. Ci sono importanti eccezioni che vengono esposte di seguito:

- **scope decisions**: le decisioni riguardanti i requirement fondati sul progetto sono stati presi in modo _consultativo_ dal CEO.
- **quality decisions**: le decisioni relative alla qualità del prodotto sono state decise in modo _diretto_ dal CTO.

Queste due eccezioni sono state scelte dal team di sua volontà, ritenendo queste figure le più autorevoli per quanto riguarda le tematiche associate, inoltre, ancora una volta, ci si vuole esporre in prima persona a tutte le strategie principali, così da poterne dedurre vantaggi e svantaggi ed adottare la migliore in seguito.

Ogni altra decisione è stata presa e verrà presa tramite appositi meeting in cui tutto il team verrà ascoltato. Le scelte quindi deriveranno dal consenso e dalle discussioni.

### Conflict resolution

Anche la risoluzione di conflitti ha più facce a seconda della situazione in cui ci si trova. Per conflitti riguardanti temi fondanti (e.g. game design, distribuzione del carico di lavoro etc.) si adotta la strategia _collaborativa_. Per quanto riguarda invece problemi minori e urgenti (e.g. aspetti estetici, non legati al core del progetto) si decide di utilizzare la strategia del _compromesso_.

#### Risoluzione collaborativa

1. Si prenota del tempo e dello spazio per ascoltare le figure in conflitto.
2. Si identifica il problema scindendolo dalle persone.
3. Si utilizza la [_root cause analysis_](https://www.tableau.com/it-it/learn/articles/root-cause-analysis) rispondendo in cascata (circa) 5 volte al "perchè".
4. Si attua una ricerca attiva e condivisa di una soluzione
5. Si formalizza la decisione presa e la si attua

#### Risoluzione col compromesso

Una volta aver identificato il problema le due parti cedono entrambe parte della ragione al fine di evitare la perdita di troppo tempo. Si adotta una soluzione temporanea al problema fin tanto che non se ne trova una definitiva.

### Brainstorming

Le sessioni di brainstorming verranno innescate principalmente per due motivi:

- ricerca di soluzioni efficaci ai problemi
- creazione di idee nuove per l'implementazione

Queste riunioni verranno fatte su richiesta e avranno come scopo principale ascoltare ogni voce. Solo in un secondo momento queste idee verranno analizzate e si estrapolerà la migliore. Si incentiverà l'apertura mentale e si sopprimerà ogni pregiudizio al fine di lasciare quanto più spazio possibile alla creatività.

### Team meetings

I team meetings saranno necessariamente molto frequenti al fine di poter avere un monitoraggio pervasivo dal quale poter fare audit e soddisfare l'obiettivo 3 del progetto. Di conseguenza, ogni meeting avrà una durata corta per evitare overhead insostenibili durante l'esecuzione del progetto.

Sono stati definiti 4 tipologie diverse di meeting:

| Nome               | Frequenza                                 | Durata    | Obiettivo                                                           |
| ------------------ | ----------------------------------------- | --------- | ------------------------------------------------------------------- |
| Daily status       | 1 al giorno                               | 10 min    | Aggiornare il team su quanto prodotto il giorno prima               |
| Problem resolution | almeno 1 per ogni problema nell'issue log | variabile | Risolvere i problemi in modo collaborativo                          |
| Status review      | 1 ogni 2 settimane                        | 1 ora     | Rivedere i progressi dell'iterazione e pianificare il futuro        |
| Milestone          | al completamento della milestone          | 2 ore     | Rivedere i risultati raggiunti e pianificare la prossima iterazione |

Si noti che sotto i problem resolution meetings ci sono anche tutti i meeting volti al brainstorming, al conflict resolution e al decision making.

Ogni meeting verrà sempre trascritto utilizzando il [meeting template](./appendices/meeting-template.md). In caso di problemi o di loro risoluzioni si aggiornerà l'issue log, mentre ad ogni project review si aggiorneranno gli strumenti di monitoraggio oltre che documentazione gestionale (e.g. WBS, PND, Gantt etc.).

## Tools

Di seguito si elencano gli strumenti che il team adotterà lungo tutta l'esecuzione del progetto.

- **Unity**: game engine, volto allo sviluppo del gioco;
- **Visual Studio Code e Rider**: i due IDE più affermati per lo sviluppo, entrambi integrabili con Unity;
- **Git**: sistema di versionamento standard de facto, permette di sfruttare strategie di branching (e.g. GitFlow) e mantenere pulizia nella codebase;
- **GitHub Stack**: insieme di feature che GitHub fornisce ai suoi clienti
  - **GitHub Repositories**: cloud affidabile in cui storicizzare il codice, utile per la condivisione;
  - **GitHub Projects**: strumento a sostegno di ogni repository, permette di tenere traccia dello stato di avanzamento delle task;
  - **GitHub Issues**: strumento a sostegno di ogni repository, permette di tenere traccia di tutti i problemi emersi nel progetto;
  - **GitHub Actions**: strumento a sostegno di ogni repository, permette di lanciare test e fare deploy in modo da avere garanzia di qualità in modo automatico;
  - **GitHub Pages**: strumento a sostegno di ogni repository, permette di pubblicare una pagina su cui scrivere tutta la documentazione relativa al progetto;
- **Discord**: software performante su cui effettuare chiamate da remoto, fornito di strumenti aggiuntivi per la condivisione di idee, schemi e prototipi.

## Work Package

Al fine di tenere monitorato il critical path, si è deciso di redigere un work package con le attività che lo compongono. Questo dovrebbe permettere maggior controllo su ogni sua parte, avendo la garanzia di prendere il prima possibile problemi e ritardi. Ogni item nel work package deve avere un titolo, una descrizione, l'assegnatario, la data di inizio, di fine prevista e di fine effettiva e note.

## Esecuzione

Il diretto successore del lancio è l'esecuzione. Qui si metteranno in atto tutte le strategie prese in precedenza. Si sfrutterà tutta la documentazione prodotta per stare in schedula, rimanere nel focus e raggiungere la milestone nei tempi previsti. Durante tutta questa fase si presterà molta attenzione nel continuare a redigere i documenti di monitoraggio al fine di poter fare audit a fine progetto e ottenere preziose informazioni su come migliorare.
