### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1283.8<br />
<br />
Final Rank Value (1283.8) = Starting Rank Value (1160.3) + Head To Head Adjustments (123.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.502[<sup>2</sup>](#table1)
- Opponent Network: 0.375[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.3
- 400 + ( ( 0.370 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1160.3


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
|           68 |       27 | 2024-08-05 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.76 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       83 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      252 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.790 (0.395)    | 0 (0.000) |     5.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      306 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.680 (0.296)    | 0 (0.000) |    23.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      322 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      344 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.170 (0.074)    | 0.912 (0.396)    | 0 (0.000) |    12.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      358 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.919 (0.399)    | 0 (0.000) |     4.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      473 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      573 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      702 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      716 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    13.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      810 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.30 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      827 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.88 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1255 | 2024-06-09 | KOI               | W   | 0.815      | -            | -                | -                | -         |     8.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1321 | 2024-06-08 | SINNERS           | W   | 0.808      | 0.500        | -                | 0.790 (0.319)    | -         |     7.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1374 | 2024-06-07 | Aurora            | W   | 0.802      | 0.500        | 0.421 (0.169)    | 0.759 (0.304)    | -         |    21.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1441 | 2024-06-06 | 3DMAX             | W   | 0.795      | 0.500        | 0.510 (0.203)    | 1.000 (0.398)    | -         |    22.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1501 | 2024-06-05 | SAW               | W   | 0.788      | 0.500        | 0.104 (0.041)    | -                | -         |    13.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1552 | 2024-06-04 | 9 Pandas          | W   | 0.782      | -            | -                | -                | -         |    10.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1665 | 2024-05-31 | SAW               | L   | 0.755      | -            | -                | -                | -         |    -9.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1668 | 2024-05-31 | FAVBET            | W   | 0.755      | -            | -                | -                | -         |     3.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1672 | 2024-05-31 | fnatic            | L   | 0.754      | -            | -                | -                | -         |    -3.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1700 | 2024-05-30 | MOUZ NXT          | L   | 0.746      | -            | -                | -                | -         |   -13.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1872 | 2024-05-22 | Zero Tenacity     | W   | 0.694      | 0.500        | 0.143 (0.050)    | 1.000 (0.347)    | -         |    10.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1919 | 2024-05-21 | Monte             | W   | 0.687      | -            | -                | -                | -         |     7.90 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1954 | 2024-05-20 | PARIVISION        | W   | 0.680      | -            | -                | -                | -         |     9.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1969 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.675      | 0.500        | 0.254 (0.086)    | -                | -         |    19.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1976 | 2024-05-19 | Endpoint          | W   | 0.674      | -            | -                | -                | -         |     6.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2011 | 2024-05-18 | Rare Atom         | W   | 0.667      | -            | -                | -                | -         |     4.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2053 | 2024-05-17 | Permitta          | W   | 0.659      | -            | -                | -                | -         |     5.44 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2066 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.655      | -            | -                | -                | -         |    -1.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2133 | 2024-05-15 | Verdant           | L   | 0.647      | -            | -                | -                | -         |   -14.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2196 | 2024-05-14 | DMS               | L   | 0.639      | -            | -                | -                | -         |   -15.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2442 | 2024-05-02 | Metizport         | L   | 0.561      | -            | -                | -                | -         |   -13.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2475 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.553      | -            | -                | -                | -         |   -12.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2485 | 2024-04-30 | Zero Tenacity     | W   | 0.548      | -            | -                | -                | -         |     7.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2517 | 2024-04-29 | SINNERS           | W   | 0.539      | -            | -                | -                | -         |     7.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2524 | 2024-04-28 | 1WIN              | W   | 0.535      | -            | -                | -                | -         |     4.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2548 | 2024-04-27 | PARIVISION        | L   | 0.528      | -            | -                | -                | -         |    -9.38 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2582 | 2024-04-26 | Nemiga            | W   | 0.520      | 0.435        | 0.315 (0.071)    | -                | -         |     9.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2654 | 2024-04-23 | Grannys Knockers  | W   | 0.499      | -            | -                | -                | -         |     1.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2659 | 2024-04-22 | BLEED             | L   | 0.494      | -            | -                | -                | -         |    -9.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2670 | 2024-04-22 | ex-Guild Eagles   | L   | 0.492      | -            | -                | -                | -         |   -13.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2685 | 2024-04-21 | Alliance          | W   | 0.486      | -            | -                | -                | -         |     2.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2704 | 2024-04-20 | brazylijski luz   | W   | 0.481      | -            | -                | -                | -         |     2.25 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2720 | 2024-04-20 | JANO              | W   | 0.479      | -            | -                | -                | -         |     1.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2739 | 2024-04-19 | TSM               | W   | 0.475      | -            | -                | -                | -         |     1.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2751 | 2024-04-19 | Nemiga            | L   | 0.474      | -            | -                | -                | -         |    -7.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2859 | 2024-04-17 | 9 Pandas          | W   | 0.459      | -            | -                | -                | -         |     4.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2871 | 2024-04-16 | Zero Tenacity     | W   | 0.455      | -            | -                | -                | -         |     5.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2892 | 2024-04-15 | B8                | W   | 0.449      | -            | -                | -                | -         |     5.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2896 | 2024-04-15 | Aurora Young Blud | W   | 0.448      | -            | -                | -                | -         |     2.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2937 | 2024-04-12 | Monte             | L   | 0.428      | -            | -                | -                | -         |    -9.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3190 | 2024-04-04 | EYEBALLERS        | W   | 0.375      | -            | -                | -                | -         |     2.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3273 | 2024-04-02 | 9 Pandas          | L   | 0.362      | -            | -                | -                | -         |    -7.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3630 | 2024-03-13 | KOI               | L   | 0.229      | -            | -                | -                | -         |    -4.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3739 | 2024-03-09 | Zero Tenacity     | L   | 0.201      | -            | -                | -                | -         |    -3.59 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3788 | 2024-03-07 | 500               | L   | 0.188      | -            | -                | -                | -         |    -5.45 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3808 | 2024-03-06 | TSM               | W   | 0.182      | -            | -                | -                | -         |     0.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3878 | 2024-03-04 | Sampi             | W   | 0.167      | -            | -                | -                | -         |     0.95 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3904 | 2024-03-03 | Rebels            | L   | 0.161      | -            | -                | -                | -         |    -3.62 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3931 | 2024-03-02 | HAVU              | W   | 0.153      | -            | -                | -                | -         |     0.35 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3952 | 2024-02-29 | Rebels            | L   | 0.141      | -            | -                | -                | -         |    -3.20 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3973 | 2024-02-28 | Alliance          | L   | 0.133      | -            | -                | -                | -         |    -3.57 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3980 | 2024-02-27 | 9INE              | W   | 0.129      | -            | -                | -                | -         |     0.11 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4026 | 2024-02-25 | Sashi             | W   | 0.115      | -            | -                | -                | -         |     1.79 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4202 | 2024-02-18 | 500               | W   | 0.066      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4405 | 2024-02-08 | AURA              | L   | 0.001      | -            | -                | -                | -         |    -0.03 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,163.99)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.815 | $16,500.00     | $13,441.77      |
| 2024-05-22 |      0.694 | $50,000.00     | $34,722.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
