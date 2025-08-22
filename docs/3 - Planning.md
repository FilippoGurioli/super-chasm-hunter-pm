---
title: Planning
---

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

La documentazione verrà elaborata attraverso *Joint Project Planning Sessions* tra i membri del team.

- [Meeting 5](./Allegati/Meetings/Meeting%205%20-%2017-07-25.md)

---

## Project Definition Statement (PDS)

Il **PDS** raccoglie le specifiche di dettaglio necessarie per l'esecuzione del progetto. Durante la fase di *Execution*, il team farà riferimento a questo documento per definire *come* realizzare ciascun requisito.

Il PDS è articolato in tre sotto-documenti principali:

- **Game Design Document (GDD)**  
  Contiene tutte le scelte di game design: genere, gameplay, meccaniche di gioco e motivazioni creative. Redatto dal Game Designer. Non include analisi tecniche o implementative.

- **Art Bible**  
  Definisce lo stile visivo: concept art, palette colori, design dei personaggi, ambientazioni e linee guida estetiche. Garantisce coerenza visiva e viene redatto dall'Art Director.

- **Technical Design Document (TDD)**  
  Sviluppato dal CTO sulla base di POS, RBS, GDD e Art Bible. Definisce architettura tecnica, tecnologie, testing, pipeline di sviluppo e scelte implementative.

## WBS

- Prioritizzazione dei requirements (MoSCoW)
- Approccio subteam
- WBS incompleta per scelta PMLC

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

## Project Proposal

- Executive Summary
- Background
- Objectives
- Overview of the Approach to be Taken
- Detailed Statement of Work
- Time and Cost Summary
- Appendices
