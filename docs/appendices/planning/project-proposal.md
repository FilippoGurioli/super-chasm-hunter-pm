# Iteration Proposal – Super Chasm Hunter

## Sintesi

Il progetto **Super Chasm Hunter** mira allo sviluppo di un videogioco indie con caratteristiche **rogue-like, RPG e building**.  
L’obiettivo principale è duplice:  

- permettere al team di acquisire esperienza concreta nell’industria videoludica,  
- pubblicare il primo titolo sul mercato (Steam) entro l’inizio del 2027, generando un flusso di entrate sostenibile.  

Il progetto sarà sviluppato con approccio **iterativo**, che consente di apprendere e adattare i requisiti lungo il percorso.  
Il valore del progetto non è solo economico, ma anche formativo e reputazionale: validare le competenze del team, costruire un network e posizionarsi sul mercato.

## Background

Il team è composto da giovani sviluppatori appassionati, con esperienza accademica e personale in Unity e Blender.  
Al momento non dispone di un prodotto pubblicato, pertanto **Super Chasm Hunter** rappresenta la prima occasione di ingresso sul mercato.  

Motivazioni principali:  

- Creare un videogioco che sia **producibile in tempi relativamente brevi**.  
- Avviare un modello di business sostenibile, coprendo almeno i costi fissi di apertura di una partita IVA (circa 6300€/anno).  
- Acquisire competenze operative nel ciclo di vita completo di un videogioco: sviluppo, test, marketing e pubblicazione.

## Obiettivi

1. **Pubblicazione entro inizio 2027**  
   - **Tangibile**: entrate tramite Steam.  
   - **Intangibile**: credibilità del team.  
   - **Success Criteria**: lancio sul mercato.

2. **Caratteristiche di gameplay (rogue-like, RPG, building)**  
   - **Tangibile**: maggiore attrattiva per nicchie specifiche.  
   - **Success Criteria**: almeno 4 classi giocabili, mappe generate proceduralmente, oggetti piazzabili nel mondo di gioco.

3. **Accumulare esperienza professionale**  
   - **Intangibile**: crescita nelle competenze Unity/Blender, networking, marketing.  
   - **Success Criteria**: stabilire rapporti con almeno 3 altre aziende, realizzare 3 campagne marketing diverse.

4. **Sostenibilità economica minima**  
   - **Tangibile**: copertura dei costi annui (≥ 6300€).  
   - **Intangibile**: prova di interesse del mercato.  

## Approccio al progetto

- **Metodologia**: Project Management Life Cycle di tipo **Iterativo**.  
- **Motivazione**: obiettivi chiari, requisiti instabili → è necessario apprendere durante lo sviluppo.  
- **Strumenti**: Unity (game engine), Blender (grafica 3D/2D), asset di terze parti (per AI, ecc.).  
- **Rischi e mitigazioni**:
  - Rischi tecnici (es. aggiornamenti Unity, AI complesse) → mitigati tramite uso di versioni LTS e asset collaudati.
  - Rischi organizzativi (presenza disomogenea del team) → gestiti con pianificazione flessibile e comunicazioni strutturate.  
  - Rischi esterni (policy Steam) → accettati come inevitabili.

## Piano di lavoro

Il lavoro sarà suddiviso in 5 iterazioni principali:  

1. **Core Mechanics**  
   - Implementazione vita, mana, movimento e status effect del protagonista.  
   - Creazione di un primo HUD e menù di gioco.  
   - Test funzionali di base.  

2. **Rogue-like Features**  
   - Generazione procedurale delle mappe.  
   - Implementazione di NPC e nemici con AI.  
   - Gestione dell’inventario e interazioni con oggetti.  

3. **Building e Progressione**  
   - Possibilità di piazzare oggetti nel mondo.  
   - Gestione salvataggi (vita, mana, inventario, oggetti piazzati).  
   - Dialoghi, negozi, monete e sistema di progressione.  

4. **Rifinitura**  
   - Ottimizzazione grafica e animazioni.
   - Bilanciamento del gameplay e correzione bug.
   - Test approfonditi e feedback loop.

5. **Marketing**
   - Creazione di trailer, pagine social e campagne promozionali.  
   - Preparazione per la pubblicazione su Steam.

Tutte le attività sono dettagliate nel **Project Network Diagram (PND)** con stime di durata, percorso critico e slack.

## Stime di costo e durata

- **Durata stimata**:
  - Prima iterazione ≈ **81 giorni di calendario** (con scope bank inclusa).  
  - Iterazioni successive ≈ 170 giorni complessivi.
  - Tempo totale stimato: entro **01/05/2026** per la prima fase.

- **Scope Bank**: 15% dei giorni/uomo totali (≈ 22 giorni) per imprevisti, cambi di requisiti o aggiunte.

- **Costi principali**:  
  - Partita IVA annuale: 3600€  
  - Asset da acquistare (AI, animazioni, grafica): ≈ 500€
  - Totale stimato: **4100€** netto, **6300€** lordo.

Obiettivo minimo: copertura dei costi annui (≥ 6300€) tramite vendite su Steam.  

## Appendici

- [**POS (Project Overview Statement)**](../scoping/POS.md)
- [**Gestione del rischio**](risk-management.md) con elenco dettagliato dei rischi e strategie
- [**PND (Project Network Diagram)**](PND.md) con attività, percorso critico, scope bank e Gantt
- [**WBS (Work Breakdown Structure)**](WBS.md)
- [**Gantt Chart**](gantt.md)
- [**Analisi finanziaria**](../scoping/financial-analysis.md)
