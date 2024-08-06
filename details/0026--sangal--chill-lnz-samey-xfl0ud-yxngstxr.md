### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1282.9<br />
<br />
Final Rank Value (1282.9) = Starting Rank Value (1161.1) + Head To Head Adjustments (121.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.376[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1161.1
- 400 + ( ( 0.370 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1161.1


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
|           68 |       30 | 2024-08-05 | 1WIN              | W   | 1.000      | 0.435        | -                | 0.718 (0.312)    | 0 (0.000) |     5.79 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       83 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      250 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.790 (0.395)    | 0 (0.000) |     5.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      304 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | -                | 0 (0.000) |    23.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      320 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      342 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.170 (0.074)    | 0.912 (0.396)    | 0 (0.000) |    12.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      356 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.919 (0.399)    | 0 (0.000) |     4.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      471 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      571 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      700 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      714 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    13.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      808 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      825 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.92 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1253 | 2024-06-09 | KOI               | W   | 0.814      | -            | -                | -                | -         |     8.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1319 | 2024-06-08 | SINNERS           | W   | 0.808      | 0.500        | -                | 0.790 (0.319)    | -         |     7.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1372 | 2024-06-07 | Aurora            | W   | 0.801      | 0.500        | 0.420 (0.168)    | 0.759 (0.304)    | -         |    21.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1439 | 2024-06-06 | 3DMAX             | W   | 0.794      | 0.500        | 0.510 (0.202)    | 1.000 (0.397)    | -         |    22.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1499 | 2024-06-05 | SAW               | W   | 0.788      | 0.500        | 0.104 (0.041)    | -                | -         |    13.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1550 | 2024-06-04 | 9 Pandas          | W   | 0.781      | -            | -                | -                | -         |    10.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1663 | 2024-05-31 | SAW               | L   | 0.754      | -            | -                | -                | -         |    -9.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1666 | 2024-05-31 | FAVBET            | W   | 0.754      | -            | -                | -                | -         |     3.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1670 | 2024-05-31 | fnatic            | L   | 0.753      | -            | -                | -                | -         |    -3.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1698 | 2024-05-30 | MOUZ NXT          | L   | 0.745      | -            | -                | -                | -         |   -13.82 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1870 | 2024-05-22 | Zero Tenacity     | W   | 0.694      | 0.500        | 0.143 (0.050)    | 1.000 (0.347)    | -         |    10.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1917 | 2024-05-21 | Monte             | W   | 0.686      | -            | -                | -                | -         |     7.93 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1952 | 2024-05-20 | PARIVISION        | W   | 0.680      | -            | -                | -                | -         |     9.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1967 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.675      | 0.500        | 0.253 (0.086)    | -                | -         |    19.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1974 | 2024-05-19 | Endpoint          | W   | 0.673      | -            | -                | -                | -         |     6.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2009 | 2024-05-18 | Rare Atom         | W   | 0.666      | -            | -                | -                | -         |     1.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2051 | 2024-05-17 | Permitta          | W   | 0.659      | -            | -                | -                | -         |     5.42 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2064 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.655      | -            | -                | -                | -         |    -1.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2131 | 2024-05-15 | Verdant           | L   | 0.646      | -            | -                | -                | -         |   -14.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2194 | 2024-05-14 | DMS               | L   | 0.639      | -            | -                | -                | -         |   -15.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2440 | 2024-05-02 | Metizport         | L   | 0.560      | -            | -                | -                | -         |   -13.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2473 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.552      | -            | -                | -                | -         |   -12.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2483 | 2024-04-30 | Zero Tenacity     | W   | 0.547      | -            | -                | -                | -         |     6.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2515 | 2024-04-29 | SINNERS           | W   | 0.539      | -            | -                | -                | -         |     7.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2522 | 2024-04-28 | 1WIN              | W   | 0.534      | -            | -                | -                | -         |     4.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2546 | 2024-04-27 | PARIVISION        | L   | 0.527      | -            | -                | -                | -         |    -9.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2580 | 2024-04-26 | Nemiga            | W   | 0.519      | 0.435        | 0.314 (0.071)    | -                | -         |     9.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2652 | 2024-04-23 | Grannys Knockers  | W   | 0.499      | -            | -                | -                | -         |     1.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2657 | 2024-04-22 | BLEED             | L   | 0.494      | -            | -                | -                | -         |    -9.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2668 | 2024-04-22 | ex-Guild Eagles   | L   | 0.492      | -            | -                | -                | -         |   -13.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2683 | 2024-04-21 | Alliance          | W   | 0.485      | -            | -                | -                | -         |     2.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2702 | 2024-04-20 | brazylijski luz   | W   | 0.481      | -            | -                | -                | -         |     2.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2718 | 2024-04-20 | JANO              | W   | 0.479      | -            | -                | -                | -         |     1.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2737 | 2024-04-19 | TSM               | W   | 0.475      | -            | -                | -                | -         |     1.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2749 | 2024-04-19 | Nemiga            | L   | 0.474      | -            | -                | -                | -         |    -7.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2857 | 2024-04-17 | 9 Pandas          | W   | 0.459      | -            | -                | -                | -         |     4.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2869 | 2024-04-16 | Zero Tenacity     | W   | 0.454      | -            | -                | -                | -         |     5.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2890 | 2024-04-15 | B8                | W   | 0.448      | -            | -                | -                | -         |     5.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2894 | 2024-04-15 | Aurora Young Blud | W   | 0.447      | -            | -                | -                | -         |     3.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2935 | 2024-04-12 | Monte             | L   | 0.427      | -            | -                | -                | -         |    -9.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3188 | 2024-04-04 | EYEBALLERS        | W   | 0.375      | -            | -                | -                | -         |     2.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3271 | 2024-04-02 | 9 Pandas          | L   | 0.361      | -            | -                | -                | -         |    -7.85 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3628 | 2024-03-13 | KOI               | L   | 0.228      | -            | -                | -                | -         |    -4.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3737 | 2024-03-09 | Zero Tenacity     | L   | 0.200      | -            | -                | -                | -         |    -3.59 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3786 | 2024-03-07 | 500               | L   | 0.187      | -            | -                | -                | -         |    -5.43 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3806 | 2024-03-06 | TSM               | W   | 0.182      | -            | -                | -                | -         |     0.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3876 | 2024-03-04 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     0.94 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3902 | 2024-03-03 | Rebels            | L   | 0.161      | -            | -                | -                | -         |    -3.61 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3929 | 2024-03-02 | HAVU              | W   | 0.152      | -            | -                | -                | -         |     0.35 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3950 | 2024-02-29 | Rebels            | L   | 0.141      | -            | -                | -                | -         |    -3.19 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3971 | 2024-02-28 | Alliance          | L   | 0.133      | -            | -                | -                | -         |    -3.55 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3978 | 2024-02-27 | 9INE              | W   | 0.128      | -            | -                | -                | -         |     0.11 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4024 | 2024-02-25 | Sashi             | W   | 0.115      | -            | -                | -                | -         |     1.78 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4200 | 2024-02-18 | 500               | W   | 0.066      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4403 | 2024-02-08 | AURA              | L   | 0.000      | -            | -                | -                | -         |    -0.01 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,120.89)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.814 | $16,500.00     | $13,431.08      |
| 2024-05-22 |      0.694 | $50,000.00     | $34,689.81      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
