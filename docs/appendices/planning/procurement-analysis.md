# Procurement analysis - AI NPC

## Obiettivo

Lo scopo di questa analisi è identificare la soluzione più adatta per implementare l’intelligenza artificiale (AI) dei personaggi non giocanti (NPC) in un videogioco indie.  
L’accento è posto sulla **gestione del comportamento dei nemici** (pathfinding, combattimento, interazioni ambientali) e sulla **facilità d’integrazione** in un team ridotto con risorse limitate.

## Criteri di valutazione

Sono stati individuati i seguenti criteri principali:

1. Facilità di integrazione con Unity e altre librerie.
2. Flessibilità e personalizzazione del comportamento degli NPC.
3. Documentazione e supporto della community.
4. Performance su progetti di scala ridotta (per evitare overhead inutili).
5. Costo in rapporto al budget del progetto.

## Soluzioni considerate

Sono stati presi in esame alcuni asset disponibili su Unity Asset Store:

- [**Emerald AI**](https://assetstore.unity.com/packages/tools/behavior-ai/emerald-ai-2025-268519)
  Sistema AI modulare per NPC e creature, supporta comportamento complesso (combattimento, pattugliamento, interazioni), altamente personalizzabile.

- [**NPC AI Engine**](https://assetstore.unity.com/packages/tools/behavior-ai/npc-ai-engine-dialog-actions-voice-and-lipsync-convai-235621)
  Asset che fornisce un motore AI specializzato per NPC, con comportamento modulare, personalizzabile e adatto a diversi generi (RPG, survival, adventure).

- [**NodeCanvas**](https://assetstore.unity.com/packages/tools/visual-scripting/nodecanvas-14914?srsltid=AfmBOopu2A9Ie08NRZUJsDbQ-5mY-vLphjocDKDY5vG3aHmenxEryEzf)
  Strumento di behaviour tree e FSM, più orientato alla creazione manuale di logiche custom piuttosto che a una soluzione “plug and play”.

- [**ICE Creature Control**](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbXIzS3V6U2lhTVAxTnNNQUNDWlJpaEJhd1RoUXxBQ3Jtc0trTUhzY1UtQUZSLURNNFVRU3NudHJSdWVwY05KeTZDV3JDNnFyal81TTN4bTRuMUs2QW5UaHlVVFpfeGV2VkllSkxqbkpCYW53eGMzb3ZnazdWZkw0dnhPblB3VUxfRHBwbE9wMHBDQVFvcm9LWU1Pbw&q=https%3A%2F%2Fwww.assetstore.unity3d.com%2F%23%21%2Fcontent%2F35364%3Faid%3D1101lSgi&v=nacyil1QwPQ) (storico, meno aggiornato ma ancora usato in alcuni contesti)  
  Buono per AI di creature, ma con supporto limitato e aggiornamenti rari.

## Analisi comparativa

### Tabella riepilogativa

| Asset             | Integrazione | Flessibilità | Documentazione/Supporto | Performance | Costo (€) | Note principali                             |
| ----------------- | ------------ | ------------ | ----------------------- | ----------- | --------- | ------------------------------------------- |
| **Emerald AI**    | Alta         | Alta         | Alta (forum attivo)     | Buona       | Medio     | Ottimo bilanciamento tra facilità e potenza |
| **NPC AI Engine** | Media        | Media        | Media                   | Ottima      | Nullo     | Specifico per NPC, poco diffuso             |
| **NodeCanvas**    | Alta         | Molto alta   | Buona                   | Buona       | Alto      | Richiede tempo per configurazioni manuali   |
| **ICE Creature**  | Media        | Bassa        | Bassa (poco supporto)   | Media       | Basso     | Meno aggiornato, rischio obsolescenza       |

### Paired Comparison

| Confronto     | Emerald AI | Rival AI | NodeCanvas | ICE Creature | Somma | Rank |
| ------------- | ---------- | -------- | ---------- | ------------ | ----- | ---- |
| Emerald AI    | X          | 1        | 1          | 1            | 3     | 1    |
| NPC AI Engine | 0          | X        | 0          | 1            | 1     | 3    |
| ICE Creature  | 0          | 1        | X          | 1            | 2     | 2    |
| NodeCanvas    | 0          | 0        | 0          | X            | 0     | 4    |

**Conteggio preferenze:**

- Emerald AI: 3
- NodeCanvas: 0
- NPC AI Engine: 1
- ICE Creature: 2

## Decisione finale

Alla luce dell’analisi:

- **Emerald AI** garantisce il miglior equilibrio tra facilità d’integrazione, potenza e supporto.  
- È ideale per un team indie con tempo e risorse limitate, poiché offre **soluzioni già pronte per NPC complessi**, riducendo il lavoro manuale.  
- Il costo è sostenibile e giustificato dal valore in termini di velocità di sviluppo.  

Decisione: **Emerald AI** come soluzione AI principale per il progetto
