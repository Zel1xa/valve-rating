### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1291.1<br />
<br />
Final Rank Value (1291.1) = Starting Rank Value (1166.5) + Head To Head Adjustments (124.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.602[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.386[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.373<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1166.5
- 400 + ( ( 0.373 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1166.5


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
|           68 |        2 | 2024-08-06 | Permitta          | W   | 1.000      | 0.435        | -                | 0.919 (0.399)    | 0 (0.000) |     4.79 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       36 | 2024-08-05 | 1WIN              | W   | 1.000      | 0.435        | -                | 0.718 (0.312)    | 0 (0.000) |     5.73 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           66 |       92 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      262 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.800 (0.400)    | 0 (0.000) |     5.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      315 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | -                | 0 (0.000) |    23.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      331 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      353 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.170 (0.074)    | 0.912 (0.396)    | 0 (0.000) |    12.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      367 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.919 (0.399)    | 0 (0.000) |     4.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      482 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      582 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      711 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      725 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    13.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      819 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | -         |     5.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |      836 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.80 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           54 |     1264 | 2024-06-09 | KOI               | W   | 0.814      | -            | -                | -                | -         |     8.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1330 | 2024-06-08 | SINNERS           | W   | 0.807      | 0.500        | -                | 0.800 (0.323)    | -         |     7.02 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1383 | 2024-06-07 | Aurora            | W   | 0.801      | 0.500        | 0.420 (0.168)    | -                | -         |    21.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1450 | 2024-06-06 | 3DMAX             | W   | 0.794      | 0.500        | 0.510 (0.202)    | 1.000 (0.397)    | -         |    21.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1510 | 2024-06-05 | SAW               | W   | 0.787      | 0.500        | 0.104 (0.041)    | -                | -         |    13.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1561 | 2024-06-04 | 9 Pandas          | W   | 0.781      | -            | -                | -                | -         |     9.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1674 | 2024-05-31 | SAW               | L   | 0.754      | -            | -                | -                | -         |    -9.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1677 | 2024-05-31 | FAVBET            | W   | 0.753      | -            | -                | -                | -         |     2.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1681 | 2024-05-31 | fnatic            | L   | 0.753      | -            | -                | -                | -         |    -3.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1709 | 2024-05-30 | MOUZ NXT          | L   | 0.745      | -            | -                | -                | -         |   -13.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1881 | 2024-05-22 | Zero Tenacity     | W   | 0.693      | 0.500        | 0.143 (0.050)    | 1.000 (0.347)    | -         |     9.94 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1928 | 2024-05-21 | Monte             | W   | 0.686      | -            | -                | -                | -         |     7.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1963 | 2024-05-20 | PARIVISION        | W   | 0.679      | -            | -                | -                | -         |     9.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1978 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.674      | 0.500        | 0.253 (0.085)    | -                | -         |    19.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     1985 | 2024-05-19 | Endpoint          | W   | 0.673      | -            | -                | -                | -         |     6.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2020 | 2024-05-18 | Rare Atom         | W   | 0.666      | -            | -                | -                | -         |     4.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2062 | 2024-05-17 | Permitta          | W   | 0.658      | -            | -                | -                | -         |     5.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2075 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.654      | -            | -                | -                | -         |    -1.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2142 | 2024-05-15 | Verdant           | L   | 0.646      | -            | -                | -                | -         |   -15.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2205 | 2024-05-14 | DMS               | L   | 0.638      | -            | -                | -                | -         |   -15.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2451 | 2024-05-02 | Metizport         | L   | 0.560      | -            | -                | -                | -         |   -13.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2484 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.552      | -            | -                | -                | -         |   -12.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2494 | 2024-04-30 | Zero Tenacity     | W   | 0.547      | -            | -                | -                | -         |     6.88 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2526 | 2024-04-29 | SINNERS           | W   | 0.538      | -            | -                | -                | -         |     7.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2533 | 2024-04-28 | 1WIN              | W   | 0.534      | -            | -                | -                | -         |     4.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2557 | 2024-04-27 | PARIVISION        | L   | 0.527      | -            | -                | -                | -         |    -9.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2591 | 2024-04-26 | Nemiga            | W   | 0.519      | 0.435        | 0.314 (0.071)    | -                | -         |     9.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2663 | 2024-04-23 | Grannys Knockers  | W   | 0.498      | -            | -                | -                | -         |     1.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2668 | 2024-04-22 | BLEED             | L   | 0.493      | -            | -                | -                | -         |    -9.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2679 | 2024-04-22 | ex-Guild Eagles   | L   | 0.491      | -            | -                | -                | -         |   -13.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2694 | 2024-04-21 | Alliance          | W   | 0.485      | -            | -                | -                | -         |     2.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2713 | 2024-04-20 | brazylijski luz   | W   | 0.480      | -            | -                | -                | -         |     2.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2729 | 2024-04-20 | JANO              | W   | 0.478      | -            | -                | -                | -         |     1.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2748 | 2024-04-19 | TSM               | W   | 0.474      | -            | -                | -                | -         |     1.03 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2760 | 2024-04-19 | Nemiga            | L   | 0.473      | -            | -                | -                | -         |    -7.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2868 | 2024-04-17 | 9 Pandas          | W   | 0.458      | -            | -                | -                | -         |     4.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2880 | 2024-04-16 | Zero Tenacity     | W   | 0.454      | -            | -                | -                | -         |     5.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2901 | 2024-04-15 | B8                | W   | 0.448      | -            | -                | -                | -         |     5.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2905 | 2024-04-15 | Aurora Young Blud | W   | 0.446      | -            | -                | -                | -         |     3.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     2946 | 2024-04-12 | Monte             | L   | 0.427      | -            | -                | -                | -         |    -9.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3199 | 2024-04-04 | EYEBALLERS        | W   | 0.374      | -            | -                | -                | -         |     2.44 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3282 | 2024-04-02 | 9 Pandas          | L   | 0.361      | -            | -                | -                | -         |    -7.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           12 |     3639 | 2024-03-13 | KOI               | L   | 0.228      | -            | -                | -                | -         |    -4.31 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3748 | 2024-03-09 | Zero Tenacity     | L   | 0.200      | -            | -                | -                | -         |    -3.63 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3797 | 2024-03-07 | 500               | L   | 0.187      | -            | -                | -                | -         |    -5.43 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3817 | 2024-03-06 | TSM               | W   | 0.181      | -            | -                | -                | -         |     0.35 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3887 | 2024-03-04 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     0.92 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3913 | 2024-03-03 | Rebels            | L   | 0.160      | -            | -                | -                | -         |    -3.63 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3940 | 2024-03-02 | HAVU              | W   | 0.152      | -            | -                | -                | -         |     0.34 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3961 | 2024-02-29 | Rebels            | L   | 0.140      | -            | -                | -                | -         |    -3.21 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3982 | 2024-02-28 | Alliance          | L   | 0.132      | -            | -                | -                | -         |    -3.55 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     3989 | 2024-02-27 | 9INE              | W   | 0.128      | -            | -                | -                | -         |     0.11 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4035 | 2024-02-25 | Sashi             | W   | 0.114      | -            | -                | -                | -         |     1.75 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4211 | 2024-02-18 | 500               | W   | 0.065      | -            | -                | -                | -         |     0.14 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,090.10)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.814 | $16,500.00     | $13,423.44      |
| 2024-05-22 |      0.693 | $50,000.00     | $34,666.67      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
