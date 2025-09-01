# Project Network Diagram

Partendo dall'elenco di tutte le task identificate tramite *giudizio dell'esperto* è possibile costruire una prima versione del **Project Network Diagram (PND)**.

## Elenco delle attività

| ID | Nome | Durata | Assegnatario |
|----|------|--------|--------------|
| 1  | Asset vita protagonista | 1 gg | Luca |
| 2  | Logica vita protagonista | 2 gg | Filippo G |
| 3  | viz vita protagonista | 1 gg | Filippo G |
| 4  | test vita prot | 1 gg | Filippo G |
| 5  | animazione flinching | 1 gg | Filippo P |
| 6  | art status effect | 2 gg | Filippo P |
| 7  | logica status effect - vita + mov | 2 gg | Silvia |
| 8  | logica status effect - arma | 2 gg | Silvia |
| 9  | viz status effect | 1 gg | Silvia |
| 10 | test status effect | 1 gg | Silvia |
| 11 | asset 2D x mana prot | 1 gg | Luca |
| 12 | logica mana | 2 gg | Anny |
| 13 | viz mana | 1 gg | Anny |
| 14 | test mana | 1 gg | Anny |
| 15 | logica gestione home menu - start, exit, social | 1 gg | Filippo G |
| 16 | logica gestione impostazioni | 2 gg | Filippo G |
| 17 | test home menu | 1 gg | Filippo G |
| 18 | asset per menu home | 2 gg | Luca |
| 19 | pagine social vuote x link | 2h | Luca |
| 21 | logica gestione mappa | 1 gg | Silvia |
| 22 | viz inventario | 2 gg | Silvia |
| 23 | viz equipaggiamenti | 2 gg | Silvia |
| 24 | gestione impostazioni | 4h | Silvia |
| 25 | logica bottone exit | 4h | Silvia |
| 26 | viz pause menu | 2 gg | Silvia |
| 27 | test pause menu | 2 gg | Silvia |
| 28 | art 2D pause menu | 2 gg | Luca |
| 29 | animazioni cambio menu | 1 gg | Filippo P |
| 30 | HUD ingresso livello | 1 gg | Anny |
| 31 | effetti di danno + effetti tranisizione | 1 gg | Anny |
| 32 | viz boss bar | 1 gg | Anny |
| 33 | test HUD | 2 gg | Anny |
| 34 | logica movimento prot | 1 gg | Filippo G |
| 35 | test movimento prot | 1 gg | Filippo G |
| 36 | logica orientamento prot | 1 gg | Silvia |
| 37 | test orientamento prot | 1 gg | Silvia |
| 38 | logica risoluzione effetto base | 3 gg | Anny |
| 39 | test risoluzione effetto base | 1 gg | Anny |
| 40 | viz risoluzioene effetto base | 1 gg | Anny |
| 41 | logica risoluzione effetto speciale | 1 gg | Anny |
| 42 | test risoluzione effetto speciale | 1 gg | Anny |
| 43 | viz risoluzione effetto speciale | 1 gg | Anny |

8.1 --> 8.1.1 --> F8[Filippo G]
8.1 --> 8.1.2 --> F8
8.1 --> 8.1.3 --> F8
8 --> 8.2
8.2 --> 8.2.1
8.2.1 --> 8.2.1.1
8.2.1.1 --> 8.2.1.1.1 --> F81[Filippo G]
8.2.1.1 --> 8.2.1.1.2 --> F81
8.2.1.1 --> 8.2.1.1.3 --> F81
8.2.1 --> 8.2.1.2 --> F81
8.2 --> 8.2.2
8.2.2 --> 8.2.2.1 --> F82[Filippo G]
8.2.2 --> 8.2.2.2 --> F82
8.2 --> 8.2.3
8.2.3 --> 8.2.3.1 --> F82
8.2.3 --> 8.2.3.2 --> F82
8.2 --> 8.2.4
8.2.4 --> 8.2.4.1 --> F82
8.2.4 --> 8.2.4.2 --> F82
8.2 --> 8.2.5 --> F82

F8 --> F8.1[logica salvataggio - quando, 1 gg]
F8.1 --> F8.2[test logica salvataggio - quando, 1 gg]
F81 --> F81.1[logica salvataggio - inventario + item in mano, 1 gg]
F81.1 --> F81.2[test logica salvataggio - inventario + item in mano, 1 gg]
F82 --> F82.1[logica salvataggio - vita + mana + data, 1 gg]
F82.1 --> F82.2[test logica salvataggio - vita + mana + data, 1 gg]
F82.2 --> F82.3[logica salvataggio - item piazzati, 1 gg]
F82.3 --> F82.4[test logica salvataggio - item piazzati, 1 gg]

0 --> 9
9 --> 9.1 --> S9[Silvia]
9 --> 9.2
9.2 --> 9.2.1
9.2.1 --> 9.2.1.1 --> S9
9.2.1 --> 9.2.1.2 --> S9
9.2 --> 9.2.2 --> S9
9.2 --> 9.2.3 --> S9
9.2 --> 9.2.4
9.2.4 --> 9.2.4.1 --> F9[Filippo P]
9.2.4 --> 9.2.4.2 --> F9
9 --> 9.3
9.3 --> 9.3.1 --> A9[Anny]
9.3 --> 9.3.2 --> 9.3.2.1 --> A9
9.3 --> 9.3.3
9.3.3 --> 9.3.3.1 --> A9
9.3.3 --> 9.3.3.2 --> A9
9 --> 9.4 --> 9.4.1 --> A9

S9 --> S9.1[logica vendita item, 1 gg]
S9.1 --> S9.2[logica gestione dialoghi, 3 gg]
S9.2 --> S9.3[test logica vendita item + dialoghi, 2 gg]

F9 --> F9.1[creare asset del mercante, 2 gg]
F9.1 --> F9.2[creare asset per dialoghi, 2 gg]

A9 --> A9.1[logica acquisto oggetti, 2 gg]
A9.1 --> A9.2[logica negozio aperto/chiuso, 1 gg]
A9.2 --> A9.3[test logica acquisto e apertura, 2 gg]

10 --> 10.1 --> F10[Filippo G]
10 --> 10.2 --> F10
10 --> 10.3 --> 10.3.1 --> F10
10 --> 10.4 --> F10
10 --> 10.5 --> F10

F10 --> F10.1[logica denaro, 1 gg]
F10.1 --> F10.2[test logica denaro, 1 gg]

0 --> 11
11 --> 11.1 --> S11[Silvia]
11 --> 11.2 --> S11
11 --> 11.3
11.3 --> 11.3.1 --> S11
11.3 --> 11.3.2 --> S11
11.3 --> 11.3.3 --> S11
11 --> 11.4 --> S11

S11 --> S11.1[logica munizioni, 1 gg]
S11.1 --> S11.2[test logica munizioni, 1 gg]

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