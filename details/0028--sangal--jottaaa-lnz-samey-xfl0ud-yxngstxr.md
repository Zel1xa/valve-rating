### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1273.0<br />
<br />
Final Rank Value (1273.0) = Starting Rank Value (1156.1) + Head To Head Adjustments (116.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.502[<sup>2</sup>](#table1)
- Opponent Network: 0.375[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1156.1
- 400 + ( ( 0.370 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1156.1


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
|           67 |       25 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      193 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.757 (0.379)    | 0 (0.000) |     5.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      246 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.708 (0.308)    | 0 (0.000) |    23.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      262 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.82 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      284 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.165 (0.072)    | 0.912 (0.396)    | 0 (0.000) |    12.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      299 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.876 (0.381)    | 0 (0.000) |     4.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      410 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.82 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      513 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.89 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      642 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      656 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | 0 (0.000) |    13.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      748 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      768 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.02 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1195 | 2024-06-09 | KOI               | W   | 0.828      | -            | -                | -                | -         |     8.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1261 | 2024-06-08 | SINNERS           | W   | 0.821      | 0.500        | -                | 0.757 (0.311)    | -         |     6.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1314 | 2024-06-07 | Aurora            | W   | 0.815      | 0.500        | 0.423 (0.173)    | 0.793 (0.323)    | -         |    22.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1381 | 2024-06-06 | 3DMAX             | W   | 0.808      | 0.500        | 0.506 (0.204)    | 1.000 (0.404)    | -         |    22.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1441 | 2024-06-05 | SAW               | W   | 0.801      | 0.500        | 0.105 (0.042)    | -                | -         |    13.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1492 | 2024-06-04 | 9 Pandas          | W   | 0.795      | -            | -                | -                | -         |    10.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1605 | 2024-05-31 | SAW               | L   | 0.768      | -            | -                | -                | -         |    -9.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1608 | 2024-05-31 | FAVBET            | W   | 0.767      | -            | -                | -                | -         |     3.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1612 | 2024-05-31 | fnatic            | L   | 0.767      | -            | -                | -                | -         |    -3.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1640 | 2024-05-30 | MOUZ NXT          | L   | 0.759      | -            | -                | -                | -         |   -13.93 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1812 | 2024-05-22 | Zero Tenacity     | W   | 0.707      | 0.500        | 0.137 (0.048)    | 1.000 (0.354)    | -         |    10.42 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1859 | 2024-05-21 | Monte             | W   | 0.700      | -            | -                | -                | -         |     8.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1894 | 2024-05-20 | PARIVISION        | W   | 0.693      | -            | -                | -                | -         |     9.82 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1909 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.688      | 0.500        | 0.255 (0.088)    | -                | -         |    20.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1916 | 2024-05-19 | Endpoint          | W   | 0.687      | -            | -                | -                | -         |     6.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     1951 | 2024-05-18 | Rare Atom         | W   | 0.680      | -            | -                | -                | -         |     2.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     1993 | 2024-05-17 | Permitta          | W   | 0.672      | -            | -                | -                | -         |     5.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2006 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.668      | -            | -                | -                | -         |    -1.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2073 | 2024-05-15 | Verdant           | L   | 0.660      | -            | -                | -                | -         |   -15.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2136 | 2024-05-14 | DMS               | L   | 0.652      | -            | -                | -                | -         |   -15.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2382 | 2024-05-02 | Metizport         | L   | 0.574      | -            | -                | -                | -         |   -13.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2415 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.566      | -            | -                | -                | -         |   -12.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2425 | 2024-04-30 | Zero Tenacity     | W   | 0.561      | -            | -                | -                | -         |     7.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2457 | 2024-04-29 | SINNERS           | W   | 0.552      | -            | -                | -                | -         |     6.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2464 | 2024-04-28 | 1WIN              | W   | 0.548      | -            | -                | -                | -         |     4.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2488 | 2024-04-27 | PARIVISION        | L   | 0.541      | -            | -                | -                | -         |    -9.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2522 | 2024-04-26 | Nemiga            | W   | 0.533      | 0.435        | 0.317 (0.073)    | -                | -         |     9.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2594 | 2024-04-23 | Grannys Knockers  | W   | 0.512      | -            | -                | -                | -         |     1.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2599 | 2024-04-22 | BLEED             | L   | 0.507      | -            | -                | -                | -         |    -9.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2610 | 2024-04-22 | ex-Guild Eagles   | L   | 0.505      | -            | -                | -                | -         |   -13.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2625 | 2024-04-21 | Alliance          | W   | 0.499      | -            | -                | -                | -         |     2.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2644 | 2024-04-20 | brazylijski luz   | W   | 0.494      | -            | -                | -                | -         |     2.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2660 | 2024-04-20 | JANO              | W   | 0.492      | -            | -                | -                | -         |     1.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2679 | 2024-04-19 | TSM               | W   | 0.488      | -            | -                | -                | -         |     1.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2691 | 2024-04-19 | Nemiga            | L   | 0.487      | -            | -                | -                | -         |    -7.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2799 | 2024-04-17 | 9 Pandas          | W   | 0.472      | -            | -                | -                | -         |     4.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2811 | 2024-04-16 | Zero Tenacity     | W   | 0.468      | -            | -                | -                | -         |     5.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2832 | 2024-04-15 | B8                | W   | 0.462      | -            | -                | -                | -         |     5.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2836 | 2024-04-15 | Aurora Young Blud | W   | 0.460      | -            | -                | -                | -         |     2.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2877 | 2024-04-12 | Monte             | L   | 0.441      | -            | -                | -                | -         |    -9.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3130 | 2024-04-04 | EYEBALLERS        | W   | 0.388      | -            | -                | -                | -         |     2.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3213 | 2024-04-02 | 9 Pandas          | L   | 0.375      | -            | -                | -                | -         |    -7.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3570 | 2024-03-13 | KOI               | L   | 0.242      | -            | -                | -                | -         |    -4.41 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3679 | 2024-03-09 | Zero Tenacity     | L   | 0.214      | -            | -                | -                | -         |    -3.81 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3728 | 2024-03-07 | 500               | L   | 0.201      | -            | -                | -                | -         |    -5.81 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3748 | 2024-03-06 | TSM               | W   | 0.195      | -            | -                | -                | -         |     0.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3818 | 2024-03-04 | Sampi             | W   | 0.180      | -            | -                | -                | -         |     1.05 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3844 | 2024-03-03 | Rebels            | L   | 0.174      | -            | -                | -                | -         |    -3.87 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3871 | 2024-03-02 | HAVU              | W   | 0.166      | -            | -                | -                | -         |     0.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3892 | 2024-02-29 | Rebels            | L   | 0.154      | -            | -                | -                | -         |    -3.47 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3913 | 2024-02-28 | Alliance          | L   | 0.146      | -            | -                | -                | -         |    -3.90 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3920 | 2024-02-27 | 9INE              | W   | 0.142      | -            | -                | -                | -         |     0.13 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     3966 | 2024-02-25 | Sashi             | W   | 0.128      | -            | -                | -                | -         |     2.02 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4142 | 2024-02-18 | 500               | W   | 0.079      | -            | -                | -                | -         |     0.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4345 | 2024-02-08 | AURA              | L   | 0.014      | -            | -                | -                | -         |    -0.43 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,021.41)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.828 | $16,500.00     | $13,654.51      |
| 2024-05-22 |      0.707 | $50,000.00     | $35,366.90      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
