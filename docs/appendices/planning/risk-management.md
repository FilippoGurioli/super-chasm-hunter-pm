# Gestione del Rischio

Questo documento elenca i rischi previsti durante la [fase di scoping](../scoping/risk-analysis.md) e cerca di trovare una soluzione concreta che aderisca alla strategia scelta durante lo scoping.

| ID  | Descrizione rischio                                           | Tipologia     | Impatto | Mitigazione          |
|-----|---------------------------------------------------------------|---------------|---------|----------------------|
| R1  | Unity ha rilasci frequenti portando a veloce obsolescenza     | Tecnico       | Medio   | Mitigare             |
| R2  | Stima dell'effort può essere sbagliata data l'inesperienza    | Manageriale   | Alto    | Piano di contingenza |
| R3  | Budget limitato può portare all'inattuabilità del progetto    | Organizzativo | Alto    | Piano di contingenza |
| R4  | La presenza non costante del team può portare a ritardi       | Organizzativo | Basso   | Accettare            |
| R5  | L'utilizzo massiccio di asset può rallentare il progetto      | Tecnico       | Basso   | Accettare            |
| R6  | Sbagliare tecnica di marketing può portare ad un flop         | Tecnico       | Alto    | Mitigare             |
| R7  | Perdita di dati a causa di utilizzo improprio degli strumenti | Tecnico       | Alto    | Evitare              |
| R8  | Steam cambia le policy e/o la percentuale trattenuta          | Esterno       | Medio   | Accettare            |
| R9  | Asset acquistati possono diventare deprecati                  | Esterno       | Basso   | Accettare            |
| R10 | Lavorare in tempi diversi può compromettere la comunicazione  | Manageriale   | Medio   | Evitare              |
| R11 | Sviluppo di AI NPC può rallentare significativamente          | Tecnico       | Medio   | Trasferire           |

## R1: Unity ha rilasci frequenti portando a veloce obsolescenza

- **Tipologia**: Tecnico
- **Impatto**: Medio
- **Mitigazione**: Mitigare

Oltre alla scelta di una versione LTS, prevedere una revisione trimestrale delle release Unity per identificare tempestivamente eventuali modifiche critiche, e pianificare aggiornamenti incrementali se necessar

## R2: Stima dell'effort può essere sbagliata data l'inesperienza

- **Tipologia**: Manageriale
- **Impatto**: Alto
- **Mitigazione**: Piano di contingenza

Prevedere dei buffer di tempo e costi nel piano di progetto per assorbire eventuali errori di stima e attuare una revisione delle stime ogni 2 mesi, adattandole in base all'avanzamento reale.

## R3: Budget limitato può portare all'inattuabilità del progetto

- **Tipologia**: Organizzativo
- **Impatto**: Alto
- **Mitigazione**: Piano di contingenza

Definire un MVP (Minimum Viable Product) che garantisca margine sufficiente e che, in caso di carenza di budget, permetta comunque un primo ingresso nel mercato.

Identificare forme alternative di finanziamento come crowdfunding e early access.

Revisionare mensilmente il budget per aderire quanto più possibile al piano.

## R4: La presenza non costante del team può portare a ritardi

- **Tipologia**: Organizzativo
- **Impatto**: Basso
- **Mitigazione**: Accettare

Avendo una buona pianificazione (specialmente riguardante WBS e Gantt) che tenga conto di queste variabili si accetta il rischio.

## R5: L'utilizzo massiccio di asset può rallentare il progetto

- **Tipologia**: Tecnico
- **Impatto**: Basso
- **Mitigazione**: Accettare

L'utilizzo di asset è ben voluto dal team essendo in grado di velocizzare di molto i tempi di sviluppo. Questo rischio riguarda principalmente la possibilità che l'integrazione di essi sia particolarmente problematica. Avendo il team 3 software engineer con esperienza si ha buona certezza che problemi di integrazione siano sempre affrontabili direttamente dal team, senza fare affidamento a terzi.

## R6: Sbagliare tecnica di marketing può portare ad un flop

- **Tipologia**: Tecnico
- **Impatto**: Alto
- **Mitigazione**: Mitigare

Si è pensato di effettuare una ricerca di mercato preliminare prima di lanciare la campagna marketing. Inoltre si prevedono campagne di test (alfa/beta testing) su piccola scala per validare il messaggio promozionale. Infine si stabiliranno indicatori KPI da monitorare entro i primi mesi di marketing per correggere la rotta rapidamente.

## R7: Perdita di dati a causa di utilizzo improprio degli strumenti

- **Tipologia**: Tecnico
- **Impatto**: Alto
- **Mitigazione**: Evitare

Soluzioni proposte:

- Formare i membri del team sull'uso corretto dei sistemi di versioning e cloud storage.
- Abilitare backup automatici giornalieri per i file di progetto.
- Imporre l'uso di repository con permessi granulari e controlli di accesso.

## R8: Steam cambia le policy e/o la percentuale trattenuta

- **Tipologia**: Esterno
- **Impatto**: Medio
- **Mitigazione**: Accettare

Steam è la più grande piattaforma di distribuzione di videogiochi al mondo. È inverosimile che, anche a fronte di un improbabile aggiornamento delle policy, esse siano stringenti al punto da far fallire il progetto. Date queste considerazioni, si accetta questo rischio.

## R9: Asset acquistati possono diventare deprecati

- **Tipologia**: Esterno
- **Impatto**: Basso
- **Mitigazione**: Accettare

A differenza del rischio R5, questo fa riferimento alla velocità con la quale nuovi asset possano soppiantare quelli più comunemente usati attualmente. Questo porterebbe ad una perdita effettiva in quanto il prodotto, per restare competitivo, dovrà acquistare il nuovo asset perdendo il budget investito nell'asset deprecato.

Ad ogni modo, prima di ogni acquisto si fa un'attenta valutazione dell'asset da acquistare, analizzando a fondo il mercato, quindi stilando una lista di possibili asset in grado di soddisfare i requisiti e infine acquistando quello che meglio risolve il problema. A fronte di tutto questo, si assume che il rischio sia basso e che quindi sia accettabile.

## R10: Lavorare in tempi diversi può compromettere la comunicazione

- **Tipologia**: Manageriale
- **Impatto**: Medio
- **Mitigazione**: Evitare

L'aspetto organizzativo è centrale in questo progetto. È fondamentale evitare qualsiasi perdita di informazione a causa di comunicazioni informali/verbali mai trascritte. Al fine di avere informazioni su cui fare audit e anche per ricordare chiaramente quanto detto, è fondamentale che ogni comunicazione verbale e/o informale venga trascritta se di importanza significativa.

- Si attueranno meeting settimanali in cui far emergere le possibili riflessioni che ogni membro può aver fatto. 
- Si incentiverà l'utilizzo di canali testuali anche per le informazioni più semplici.
- Si redigerà ad ogni meeting la trascrizione di quanto detto (come già si sta facendo)

## R11: Sviluppo di AI NPC può rallentare significativamente

- **Tipologia**: Tecnico
- **Impatto**: Medio
- **Mitigazione**: Trasferire

Lo sviluppo di intelligenze artificiali può portare via molto tempo allo sviluppo del progetto. Avendo già fatto esperienza della complessità di questo requisito, il team ha deciso preventivamente di affidarsi ad un asset di terze parti per il suo compimento. È stata fatta [un'analisi di mercato](./procurement-analysis) che ha portato all'acquisto di un asset che evitasse questo rischio. 
