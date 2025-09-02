# Project Network Diagram

Partendo dall'elenco di tutte le task identificate tramite _giudizio dell'esperto_ è possibile costruire il **Project Network Diagram (PND)**.

## Elenco delle attività

| ID  | Nome                                            | Assegnatario | Durata |
| --- | ----------------------------------------------- | ------------ | ------ |
| 1   | Asset vita protagonista                         | Luca         | 2 gg   |
| 2   | Logica vita protagonista                        | Filippo G    | 4 gg   |
| 3   | Viz vita protagonista                           | Filippo G    | 1 gg   |
| 4   | Test vita prot                                  | Filippo G    | 1 gg   |
| 5   | Animazione flinching                            | Filippo P    | 3 gg   |
| 6   | Art status effect                               | Filippo P    | 2 gg   |
| 7   | Logica status effect - vita + mov               | Silvia       | 10 gg  |
| 8   | Logica status effect - arma                     | Silvia       | 5 gg   |
| 9   | Viz status effect                               | Silvia       | 1 gg   |
| 10  | Test status effect                              | Silvia       | 2 gg   |
| 11  | Asset 2D x mana prot                            | Luca         | 2 gg   |
| 12  | Logica mana                                     | Anny         | 2 gg   |
| 13  | Viz mana                                        | Anny         | 1 gg   |
| 14  | Test mana                                       | Anny         | 1 gg   |
| 15  | Logica gestione home menu - start, exit, social | Filippo G    | 3 gg   |
| 16  | Logica gestione impostazioni in home menu       | Filippo G    | 3 gg   |
| 17  | Test home menu                                  | Filippo G    | 1 gg   |
| 18  | Asset per menu home                             | Luca         | 2 gg   |
| 19  | Pagine social vuote x link                      | Luca         | 4 h    |
| 20  | Logica gestione mappa                           | Silvia       | 5 gg   |
| 21  | Viz inventario                                  | Silvia       | 3 gg   |
| 22  | Viz equipaggiamenti                             | Silvia       | 2 gg   |
| 23  | Gestione impostazioni in pause menu             | Silvia       | 1 gg   |
| 24  | Logica bottone exit                             | Silvia       | 1 gg   |
| 25  | Viz pause menu                                  | Silvia       | 1 gg   |
| 26  | Test pause menu                                 | Silvia       | 2 gg   |
| 27  | Art 2D pause menu                               | Luca         | 2 gg   |
| 28  | Animazioni cambio menu                          | Filippo P    | 3 gg   |
| 29  | HUD ingresso livello                            | Anny         | 3 gg   |
| 30  | Effetti di danno + effetti tranisizione         | Anny         | 3 gg   |
| 31  | Viz boss bar                                    | Anny         | 2 gg   |
| 32  | Test HUD                                        | Anny         | 1 gg   |
| 33  | Logica movimento prot                           | Filippo G    | 1 gg   |
| 34  | Test movimento prot                             | Filippo G    | 1 gg   |
| 35  | Logica orientamento prot                        | Silvia       | 1 gg   |
| 36  | Test orientamento prot                          | Silvia       | 1 gg   |
| 37  | Logica risoluzione effetto base                 | Anny         | 10 gg  |
| 38  | Test risoluzione effetto base                   | Anny         | 3 gg   |
| 39  | Viz risoluzione effetto base                    | Anny         | 1 gg   |
| 40  | Logica risoluzione effetto speciale             | Anny         | 3 gg   |
| 41  | Test risoluzione effetto speciale               | Anny         | 2 gg   |
| 42  | Viz risoluzione effetto speciale                | Anny         | 1 gg   |
| 43  | Logica salvataggio - quando                     | Filippo G    | 5 gg   |
| 44  | Test salvataggio - quando                       | Filippo G    | 1 gg   |
| 45  | Logica salvataggio - inventario, item in mano   | Filippo G    | 3 gg   |
| 46  | Test salvataggio - inventario, item in mano     | Filippo G    | 1 gg   |
| 47  | Logica salvataggio - vita, mana, data           | Filippo G    | 1 gg   |
| 48  | Test salvataggio - vita, mana, data             | Filippo G    | 1 gg   |
| 49  | Logica salvataggio - item piazzati              | Filippo G    | 2 gg   |
| 50  | Test salvataggio - item piazzati                | Filippo G    | 1 gg   |
| 51  | Vendita item                                    | Silvia       | 3 gg   |
| 52  | Gestione dialoghi                               | Silvia       | 3 gg   |
| 53  | Test vendita item + dialoghi                    | Silvia       | 2 gg   |
| 54  | Asset mercante                                  | Filippo P    | 2 gg   |
| 55  | Asset dialoghi                                  | Filippo P    | 3 gg   |
| 56  | Acquisto oggetti                                | Anny         | 5 gg   |
| 57  | Negozio aperto/chiuso                           | Anny         | 3 gg   |
| 58  | Test acquisto e apertura                        | Anny         | 2 gg   |
| 59  | Denaro                                          | Filippo G    | 2 gg   |
| 60  | Test denaro                                     | Filippo G    | 1 gg   |
| 61  | Munizioni                                       | Silvia       | 4 gg   |
| 62  | Test munizioni                                  | Silvia       | 1 gg   |

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
