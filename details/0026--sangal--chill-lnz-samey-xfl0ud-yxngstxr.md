### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1291.0<br />
<br />
Final Rank Value (1291.0) = Starting Rank Value (1166.0) + Head To Head Adjustments (125.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.602[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.386[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.372<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1166.0
- 400 + ( ( 0.372 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1166.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           69 |        1 | 2024-08-06 | Permitta          | W   | 1.000      | 0.435        | -                | 0.919 (0.399)    | 0 (0.000) |     4.79 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           68 |       35 | 2024-08-05 | 1WIN              | W   | 1.000      | 0.435        | -                | 0.718 (0.312)    | 0 (0.000) |     5.73 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       91 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      260 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.790 (0.395)    | 0 (0.000) |     5.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      314 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | -                | 0 (0.000) |    23.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      330 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      352 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.170 (0.074)    | 0.912 (0.396)    | 0 (0.000) |    12.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      366 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.919 (0.399)    | 0 (0.000) |     4.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      481 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      581 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      710 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      724 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    13.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      818 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | -         |     5.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      835 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.81 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1263 | 2024-06-09 | KOI               | W   | 0.814      | -            | -                | -                | -         |     8.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1329 | 2024-06-08 | SINNERS           | W   | 0.807      | 0.500        | -                | 0.790 (0.319)    | -         |     7.03 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1382 | 2024-06-07 | Aurora            | W   | 0.801      | 0.500        | 0.420 (0.168)    | -                | -         |    21.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1449 | 2024-06-06 | 3DMAX             | W   | 0.794      | 0.500        | 0.510 (0.202)    | 1.000 (0.397)    | -         |    21.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1509 | 2024-06-05 | SAW               | W   | 0.787      | 0.500        | 0.104 (0.041)    | -                | -         |    13.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1560 | 2024-06-04 | 9 Pandas          | W   | 0.781      | -            | -                | -                | -         |     9.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1673 | 2024-05-31 | SAW               | L   | 0.754      | -            | -                | -                | -         |    -9.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1676 | 2024-05-31 | FAVBET            | W   | 0.754      | -            | -                | -                | -         |     2.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1680 | 2024-05-31 | fnatic            | L   | 0.753      | -            | -                | -                | -         |    -3.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1708 | 2024-05-30 | MOUZ NXT          | L   | 0.745      | -            | -                | -                | -         |   -13.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1880 | 2024-05-22 | Zero Tenacity     | W   | 0.694      | 0.500        | 0.143 (0.050)    | 1.000 (0.347)    | -         |     9.95 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1927 | 2024-05-21 | Monte             | W   | 0.686      | -            | -                | -                | -         |     7.80 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1962 | 2024-05-20 | PARIVISION        | W   | 0.679      | -            | -                | -                | -         |     9.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1977 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.674      | 0.500        | 0.253 (0.085)    | -                | -         |    19.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1984 | 2024-05-19 | Endpoint          | W   | 0.673      | -            | -                | -                | -         |     6.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2019 | 2024-05-18 | Rare Atom         | W   | 0.666      | -            | -                | -                | -         |     4.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2061 | 2024-05-17 | Permitta          | W   | 0.658      | -            | -                | -                | -         |     5.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2074 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.654      | -            | -                | -                | -         |    -1.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2141 | 2024-05-15 | Verdant           | L   | 0.646      | -            | -                | -                | -         |   -15.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2204 | 2024-05-14 | DMS               | L   | 0.638      | -            | -                | -                | -         |   -15.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2450 | 2024-05-02 | Metizport         | L   | 0.560      | -            | -                | -                | -         |   -13.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2483 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.552      | -            | -                | -                | -         |   -12.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2493 | 2024-04-30 | Zero Tenacity     | W   | 0.547      | -            | -                | -                | -         |     6.89 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2525 | 2024-04-29 | SINNERS           | W   | 0.539      | -            | -                | -                | -         |     7.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2532 | 2024-04-28 | 1WIN              | W   | 0.534      | -            | -                | -                | -         |     4.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2556 | 2024-04-27 | PARIVISION        | L   | 0.527      | -            | -                | -                | -         |    -9.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2590 | 2024-04-26 | Nemiga            | W   | 0.519      | 0.435        | 0.314 (0.071)    | -                | -         |     9.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2662 | 2024-04-23 | Grannys Knockers  | W   | 0.498      | -            | -                | -                | -         |     1.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2667 | 2024-04-22 | BLEED             | L   | 0.494      | -            | -                | -                | -         |    -9.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2678 | 2024-04-22 | ex-Guild Eagles   | L   | 0.492      | -            | -                | -                | -         |   -13.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2693 | 2024-04-21 | Alliance          | W   | 0.485      | -            | -                | -                | -         |     2.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2712 | 2024-04-20 | brazylijski luz   | W   | 0.480      | -            | -                | -                | -         |     2.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2728 | 2024-04-20 | JANO              | W   | 0.478      | -            | -                | -                | -         |     1.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2747 | 2024-04-19 | TSM               | W   | 0.474      | -            | -                | -                | -         |     1.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2759 | 2024-04-19 | Nemiga            | L   | 0.474      | -            | -                | -                | -         |    -7.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2867 | 2024-04-17 | 9 Pandas          | W   | 0.459      | -            | -                | -                | -         |     4.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2879 | 2024-04-16 | Zero Tenacity     | W   | 0.454      | -            | -                | -                | -         |     5.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2900 | 2024-04-15 | B8                | W   | 0.448      | -            | -                | -                | -         |     5.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2904 | 2024-04-15 | Aurora Young Blud | W   | 0.447      | -            | -                | -                | -         |     3.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2945 | 2024-04-12 | Monte             | L   | 0.427      | -            | -                | -                | -         |    -9.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3198 | 2024-04-04 | EYEBALLERS        | W   | 0.374      | -            | -                | -                | -         |     2.44 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3281 | 2024-04-02 | 9 Pandas          | L   | 0.361      | -            | -                | -                | -         |    -7.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3638 | 2024-03-13 | KOI               | L   | 0.228      | -            | -                | -                | -         |    -4.31 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3747 | 2024-03-09 | Zero Tenacity     | L   | 0.200      | -            | -                | -                | -         |    -3.63 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3796 | 2024-03-07 | 500               | L   | 0.187      | -            | -                | -                | -         |    -5.43 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3816 | 2024-03-06 | TSM               | W   | 0.181      | -            | -                | -                | -         |     0.35 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3886 | 2024-03-04 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     0.92 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3912 | 2024-03-03 | Rebels            | L   | 0.160      | -            | -                | -                | -         |    -3.63 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3939 | 2024-03-02 | HAVU              | W   | 0.152      | -            | -                | -                | -         |     0.34 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3960 | 2024-02-29 | Rebels            | L   | 0.140      | -            | -                | -                | -         |    -3.21 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3981 | 2024-02-28 | Alliance          | L   | 0.132      | -            | -                | -                | -         |    -3.56 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3988 | 2024-02-27 | 9INE              | W   | 0.128      | -            | -                | -                | -         |     0.11 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4034 | 2024-02-25 | Sashi             | W   | 0.114      | -            | -                | -                | -         |     1.75 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4210 | 2024-02-18 | 500               | W   | 0.065      | -            | -                | -                | -         |     0.14 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4413 | 2024-02-08 | AURA              | L   | 0.000      | -            | -                | -                | -         |    -0.00 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,102.42)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.814 | $16,500.00     | $13,426.49      |
| 2024-05-22 |      0.694 | $50,000.00     | $34,675.93      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
