# Project Network Diagram

Partendo dall'elenco di tutte le task identificate tramite _giudizio dell'esperto_ è possibile costruire una prima versione del **Project Network Diagram (PND)**.

## Elenco delle attività

| ID  | Nome                                            | Assegnatario |
| --- | ----------------------------------------------- | ------------ |
| 1   | Asset vita protagonista                         | Luca         |
| 2   | Logica vita protagonista                        | Filippo G    |
| 3   | viz vita protagonista                           | Filippo G    |
| 4   | test vita prot                                  | Filippo G    |
| 5   | animazione flinching                            | Filippo P    |
| 6   | art status effect                               | Filippo P    |
| 7   | logica status effect - vita + mov               | Silvia       |
| 8   | logica status effect - arma                     | Silvia       |
| 9   | viz status effect                               | Silvia       |
| 10  | test status effect                              | Silvia       |
| 11  | asset 2D x mana prot                            | Luca         |
| 12  | logica mana                                     | Anny         |
| 13  | viz mana                                        | Anny         |
| 14  | test mana                                       | Anny         |
| 15  | logica gestione home menu - start, exit, social | Filippo G    |
| 16  | logica gestione impostazioni                    | Filippo G    |
| 17  | test home menu                                  | Filippo G    |
| 18  | asset per menu home                             | Luca         |
| 19  | pagine social vuote x link                      | Luca         |
| 21  | logica gestione mappa                           | Silvia       |
| 22  | viz inventario                                  | Silvia       |
| 23  | viz equipaggiamenti                             | Silvia       |
| 24  | gestione impostazioni                           | Silvia       |
| 25  | logica bottone exit                             | Silvia       |
| 26  | viz pause menu                                  | Silvia       |
| 27  | test pause menu                                 | Silvia       |
| 28  | art 2D pause menu                               | Luca         |
| 29  | animazioni cambio menu                          | Filippo P    |
| 30  | HUD ingresso livello                            | Anny         |
| 31  | effetti di danno + effetti tranisizione         | Anny         |
| 32  | viz boss bar                                    | Anny         |
| 33  | test HUD                                        | Anny         |
| 34  | logica movimento prot                           | Filippo G    |
| 35  | test movimento prot                             | Filippo G    |
| 36  | logica orientamento prot                        | Silvia       |
| 37  | test orientamento prot                          | Silvia       |
| 38  | logica risoluzione effetto base                 | Anny         |
| 39  | test risoluzione effetto base                   | Anny         |
| 40  | viz risoluzioene effetto base                   | Anny         |
| 41  | logica risoluzione effetto speciale             | Anny         |
| 42  | test risoluzione effetto speciale               | Anny         |
| 43  | viz risoluzione effetto speciale                | Anny         |
| 44  | logica salvataggio - quando                     | Filippo G    |
| 45  | test salvataggio - quando                       | Filippo G    |
| 46  | logica salvataggio - inventario, item in mano   | Filippo G    |
| 47  | test salvataggio - inventario, item in mano     | Filippo G    |
| 48  | logica salvataggio - vita, mana, data           | Filippo G    |
| 49  | test salvataggio - vita, mana, data             | Filippo G    |
| 50  | logica salvataggio - item piazzati              | Filippo G    |
| 51  | test salvataggio - item piazzati                | Filippo G    |

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
