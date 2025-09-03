# Project Network Diagram

Partendo dall'elenco di tutte le task identificate tramite _giudizio dell'esperto_ è possibile costruire il **Project Network Diagram (PND)**.

## Elenco delle attività

| ID  | Nome                                            | Assegnatario | Durata | Early Start | Early Finish | Late Start | Late Finish |
| --- | ----------------------------------------------- | ------------ | ------ | ----------- | ------------ | ---------- | ----------- |
| 1   | Asset vita protagonista                         | Luca         | 2 gg   | 0 | 2 |
| 2   | Logica vita protagonista                        | Filippo G    | 4 gg   |
| 3   | Viz vita protagonista                           | Filippo G    | 1 gg   |
| 4   | Test vita prot                                  | Filippo G    | 1 gg   |
| 5   | Animazione flinching                            | Filippo P    | 3 gg   | 0 | 3 |
| 6   | Art status effect                               | Filippo P    | 2 gg   | 4 | 6 |
| 7   | Logica status effect - vita + mov               | Silvia       | 10 gg  |
| 8   | Logica status effect - arma                     | Silvia       | 5 gg   |
| 9   | Viz status effect                               | Silvia       | 1 gg   |
| 10  | Test status effect                              | Silvia       | 2 gg   |
| 11  | Asset 2D x mana prot                            | Luca         | 2 gg   | 3 | 5 |
| 12  | Logica mana                                     | Anny         | 2 gg   |
| 13  | Viz mana                                        | Anny         | 1 gg   |
| 14  | Test mana                                       | Anny         | 1 gg   |
| 15  | Logica gestione home menu - start, exit, social | Filippo G    | 3 gg   |
| 16  | Logica gestione impostazioni in home menu       | Filippo G    | 3 gg   |
| 17  | Test home menu                                  | Filippo G    | 1 gg   |
| 18  | Asset per menu home                             | Luca         | 2 gg   | 6 | 8 |
| 19  | Pagine social vuote x link                      | Luca         | 4 h    | 9 | 9.5 |
| 20  | Logica gestione mappa                           | Silvia       | 5 gg   |
| 21  | Viz inventario                                  | Silvia       | 3 gg   |
| 22  | Viz equipaggiamenti                             | Silvia       | 2 gg   |
| 23  | Gestione impostazioni in pause menu             | Silvia       | 1 gg   |
| 24  | Logica bottone exit                             | Silvia       | 1 gg   |
| 25  | Viz pause menu                                  | Silvia       | 1 gg   |
| 26  | Test pause menu                                 | Silvia       | 2 gg   |
| 27  | Art 2D pause menu                               | Luca         | 2 gg   | 9.6 | 11.5 |
| 28  | Animazioni cambio menu                          | Filippo P    | 3 gg   | 7 | 10 |
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
| 54  | Asset mercante                                  | Filippo P    | 2 gg   | 11 | 13 |
| 55  | Asset dialoghi                                  | Filippo P    | 3 gg   | 14 | 17 |
| 56  | Acquisto oggetti                                | Anny         | 5 gg   |
| 57  | Negozio aperto/chiuso                           | Anny         | 3 gg   |
| 58  | Test acquisto e apertura                        | Anny         | 2 gg   |
| 59  | Denaro                                          | Filippo G    | 2 gg   |
| 60  | Test denaro                                     | Filippo G    | 1 gg   |
| 61  | Munizioni                                       | Silvia       | 4 gg   |
| 62  | Test munizioni                                  | Silvia       | 1 gg   |

Early Finish:
Luca: 11.5 gg
Filippo P: 17 gg
Filippo G:
Silvia:
Anny:

Giorni uomo totali: **146** giorni

| Assegnatario | Giorni totali |
| ------------ | ------------- |
| Luca         | 8,5           |
| Filippo G    | 33            |
| Filippo P    | 13            |
| Silvia       | 48            |
| Anny         | 43            |

Si noti che il lavoro è fortemente sblianciato verso la parte di sviluppo software per il fatto che questa iterazione non prevede grandi asset da sviluppare. Si stima che nelle iterazioni successive questo sbilanciamento tenderà dall'altra parte.

## Diagramma

```mermaid
graph TD
0[Start Node]
1[1 - Slack - 2 gg]
2[2 - Slack - 4 gg]
3[3 - Slack - 1 gg]
4[4 - Slack - 1 gg]
5[5 - Slack - 3 gg]
6[6 - Slack - 2 gg]
7[7 - Slack - 10 gg]
8[8 - Slack - 5 gg]
9[9 - Slack - 1 gg]
10[10 - Slack - 2 gg]
11[11 - Slack - 2 gg]
12[12 - Slack - 2 gg]
13[13 - Slack - 1 gg]
14[14 - Slack - 1 gg]
15[15 - Slack - 3 gg]
16[16 - Slack - 3 gg]
17[17 - Slack - 1 gg]
18[18 - Slack - 2 gg]
19[19 - Slack - 4 h]
20[20 - Slack - 5 gg]
21[21 - Slack - 3 gg]
22[22 - Slack - 2 gg]
23[23 - Slack - 1 gg]
24[24 - Slack - 1 gg]
25[25 - Slack - 1 gg]
26[26 - Slack - 2 gg]
27[27 - Slack - 2 gg]
28[28 - Slack - 3 gg]
29[29 - Slack - 3 gg]
30[30 - Slack - 3 gg]
31[31 - Slack - 2 gg]
32[32 - Slack - 1 gg]
33[33 - Slack - 1 gg]
34[34 - Slack - 1 gg]
35[35 - Slack - 1 gg]
36[36 - Slack - 1 gg]
37[37 - Slack - 10 gg]
38[38 - Slack - 3 gg]
39[39 - Slack - 1 gg]
40[40 - Slack - 3 gg]
41[41 - Slack - 2 gg]
42[42 - Slack - 1 gg]
43[43 - Slack - 5 gg]
44[44 - Slack - 1 gg]
45[45 - Slack - 3 gg]
46[46 - Slack - 1 gg]
47[47 - Slack - 1 gg]
48[48 - Slack - 1 gg]
49[49 - Slack - 2 gg]
50[50 - Slack - 1 gg]
51[51 - Slack - 3 gg]
52[52 - Slack - 3 gg]
53[53 - Slack - 2 gg]
54[54 - Slack - 2 gg]
55[55 - Slack - 3 gg]
56[56 - Slack - 5 gg]
57[57 - Slack - 3 gg]
58[58 - Slack - 2 gg]
59[59 - Slack - 2 gg]
60[60 - Slack - 1 gg]
61[61 - Slack - 4 gg]
62[62 - Slack - 1 gg]
End[End Node]

Item(Item)
Inventario(Inventario)
Nemici(Nemici)
Building(Building)

%% Resource Dependencies
%% Luca
0 --> 1 --> 11 --> 18 --> 19 --> 27 --> End
%% Silvia
0 --> 7 --> 8 --> 9 --> 10 --> 20 --> 21 --> 22 --> 23 --> 24 --> 25 --> 26 --> 35 --> 36 --> 51 --> 52 --> 53 --> 61 --> 62 --> End
%% Filippo P
0 --> 5 --> 6 --> 28 --> 54 --> 55 --> End
%% Anny
0 --> 12 --> 13 --> 14 --> 29 --> 30 --> 31 --> 32 --> 37 --> 38 --> 39 --> 40 --> 41 --> 42 --> 56 --> 57 --> 58 --> End
%% Filippo G
0 --> 2 --> 3 --> 4 --> 15 --> 16 --> 17 --> 33 --> 34 --> 43 --> 44 --> 45 --> 46 --> 47 --> 48 --> 49 --> 50 --> 59 --> 60 --> End

%% Technical dependencies
1 --> 3
2 --> 30
2 --> 47
6 --> 9
11 --> 13
12 --> 47
16 --> 23
19 --> 15
27 --> 25
28 --> 25
55 --> 52
59 --> 51
59 --> 56
Nemici --> 31
Inventario --> 45
Building --> 49
Item --> 30
Item --> 37
Item --> 51
Item --> 56

    classDef dashed stroke-dasharray: 5 5;
    class Item,Nemici,Building,Inventario dashed;
```

Si sono dovute aggiungere alcune task fittizie che rappresentano dipendenze con le iterazioni successive. Per ogni dipedenza da esse si sfrutterà il _mocking_ per poter comunque procedere con l'implementazione.

### Dipendenze

Dalla tabella delle attività si può dedurre facilmente le dipendenze di personale, ossia l'impossibilità per la stessa persona di eseguire due task contemporaneamente.

Successivamente sono state analizzate le dipendenze tecniche, ovvero la necessità tecnica di finire una certa task prima di poterne incominciare un'altra.

### Diagramma delle dipendenze di personale

```mermaid
graph TD
0[Start Node]
End[End Node]

%% Resource Dependencies
%% Luca
0 --> 1 --> 11 --> 18 --> 19 --> 27 --> End
%% Silvia
0 --> 7 --> 8 --> 9 --> 10 --> 20 --> 21 --> 22 --> 23 --> 24 --> 25 --> 26 --> 35 --> 36 --> 51 --> 52 --> 53 --> 61 --> 62 --> End
%% Filippo P
0 --> 5 --> 6 --> 28 --> 54 --> 55 --> End
%% Anny
0 --> 12 --> 13 --> 14 --> 29 --> 30 --> 31 --> 32 --> 37 --> 38 --> 39 --> 40 --> 41 --> 42 --> 56 --> 57 --> 58 --> End
%% Filippo G
0 --> 2 --> 3 --> 4 --> 15 --> 16 --> 17 --> 33 --> 34 --> 43 --> 44 --> 45 --> 46 --> 47 --> 48 --> 49 --> 50 --> 59 --> 60 --> End
```

### Diagramma delle dipendenze tecniche

```mermaid
graph LR
Item(Item)
Inventario(Inventario)
Nemici(Nemici)
Building(Building)

%% Technical dependencies
1 --> 3
2 --> 30
2 --> 47
6 --> 9
11 --> 13
12 --> 47
16 --> 23
19 --> 15
27 --> 25
28 --> 25
55 --> 52
59 --> 51
59 --> 56
Nemici --> 31
Inventario --> 45
Building --> 49
Item --> 30
Item --> 37
Item --> 51
Item --> 56

    classDef dashed stroke-dasharray: 5 5;
    class Item,Nemici,Building,Inventario dashed;
```
