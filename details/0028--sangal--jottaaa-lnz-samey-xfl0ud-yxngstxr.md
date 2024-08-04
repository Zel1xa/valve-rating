### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1271.6<br />
<br />
Final Rank Value (1271.6) = Starting Rank Value (1155.5) + Head To Head Adjustments (116.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.375[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1155.5
- 400 + ( ( 0.370 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1155.5


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
|           68 |       17 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           67 |      185 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.758 (0.379)    | 0 (0.000) |     4.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      238 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.708 (0.308)    | 0 (0.000) |    23.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      254 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.83 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      276 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.165 (0.072)    | 0.912 (0.396)    | 0 (0.000) |    12.93 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      291 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.876 (0.381)    | 0 (0.000) |     4.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      402 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      505 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.90 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      634 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      648 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | 0 (0.000) |    13.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      740 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      760 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.04 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           56 |     1187 | 2024-06-09 | KOI               | W   | 0.828      | -            | -                | -                | -         |     8.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |     1253 | 2024-06-08 | SINNERS           | W   | 0.822      | 0.500        | -                | 0.758 (0.311)    | -         |     6.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1306 | 2024-06-07 | Aurora            | W   | 0.815      | 0.500        | 0.424 (0.173)    | 0.793 (0.323)    | -         |    22.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1373 | 2024-06-06 | 3DMAX             | W   | 0.809      | 0.500        | 0.506 (0.204)    | 1.000 (0.404)    | -         |    22.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1433 | 2024-06-05 | SAW               | W   | 0.802      | 0.500        | 0.105 (0.042)    | -                | -         |    13.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1484 | 2024-06-04 | 9 Pandas          | W   | 0.795      | -            | -                | -                | -         |    10.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1597 | 2024-05-31 | SAW               | L   | 0.769      | -            | -                | -                | -         |    -9.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1600 | 2024-05-31 | FAVBET            | W   | 0.768      | -            | -                | -                | -         |     3.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1604 | 2024-05-31 | fnatic            | L   | 0.768      | -            | -                | -                | -         |    -3.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1632 | 2024-05-30 | MOUZ NXT          | L   | 0.760      | -            | -                | -                | -         |   -13.93 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1804 | 2024-05-22 | Zero Tenacity     | W   | 0.708      | 0.500        | 0.137 (0.048)    | 1.000 (0.354)    | -         |    10.44 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1851 | 2024-05-21 | Monte             | W   | 0.701      | -            | -                | -                | -         |     8.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1886 | 2024-05-20 | PARIVISION        | W   | 0.694      | -            | -                | -                | -         |     9.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1901 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.689      | 0.500        | 0.222 (0.077)    | -                | -         |    20.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1908 | 2024-05-19 | Endpoint          | W   | 0.688      | -            | -                | -                | -         |     6.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1943 | 2024-05-18 | Rare Atom         | W   | 0.681      | -            | -                | -                | -         |     2.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     1985 | 2024-05-17 | Permitta          | W   | 0.673      | -            | -                | -                | -         |     5.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     1998 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.669      | -            | -                | -                | -         |    -1.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2065 | 2024-05-15 | Verdant           | L   | 0.660      | -            | -                | -                | -         |   -15.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2128 | 2024-05-14 | DMS               | L   | 0.653      | -            | -                | -                | -         |   -15.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2374 | 2024-05-02 | Metizport         | L   | 0.574      | -            | -                | -                | -         |   -13.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2407 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.566      | -            | -                | -                | -         |   -12.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2417 | 2024-04-30 | Zero Tenacity     | W   | 0.561      | -            | -                | -                | -         |     7.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2449 | 2024-04-29 | SINNERS           | W   | 0.553      | -            | -                | -                | -         |     6.89 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2456 | 2024-04-28 | 1WIN              | W   | 0.549      | -            | -                | -                | -         |     4.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2480 | 2024-04-27 | PARIVISION        | L   | 0.541      | -            | -                | -                | -         |    -9.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2514 | 2024-04-26 | Nemiga            | W   | 0.534      | 0.435        | 0.317 (0.074)    | -                | -         |     9.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2586 | 2024-04-23 | Grannys Knockers  | W   | 0.513      | -            | -                | -                | -         |     1.82 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2591 | 2024-04-22 | BLEED             | L   | 0.508      | -            | -                | -                | -         |    -9.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2602 | 2024-04-22 | ex-Guild Eagles   | L   | 0.506      | -            | -                | -                | -         |   -13.34 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2617 | 2024-04-21 | Alliance          | W   | 0.500      | -            | -                | -                | -         |     2.78 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2636 | 2024-04-20 | brazylijski luz   | W   | 0.495      | -            | -                | -                | -         |     2.38 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2652 | 2024-04-20 | JANO              | W   | 0.493      | -            | -                | -                | -         |     1.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2671 | 2024-04-19 | TSM               | W   | 0.489      | -            | -                | -                | -         |     1.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2683 | 2024-04-19 | Nemiga            | L   | 0.488      | -            | -                | -                | -         |    -7.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2791 | 2024-04-17 | 9 Pandas          | W   | 0.473      | -            | -                | -                | -         |     4.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2803 | 2024-04-16 | Zero Tenacity     | W   | 0.469      | -            | -                | -                | -         |     5.89 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2824 | 2024-04-15 | B8                | W   | 0.462      | -            | -                | -                | -         |     5.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2828 | 2024-04-15 | Aurora Young Blud | W   | 0.461      | -            | -                | -                | -         |     2.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2869 | 2024-04-12 | Monte             | L   | 0.441      | -            | -                | -                | -         |    -9.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     3122 | 2024-04-04 | EYEBALLERS        | W   | 0.389      | -            | -                | -                | -         |     2.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3205 | 2024-04-02 | 9 Pandas          | L   | 0.375      | -            | -                | -                | -         |    -8.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3562 | 2024-03-13 | KOI               | L   | 0.242      | -            | -                | -                | -         |    -4.42 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     3671 | 2024-03-09 | Zero Tenacity     | L   | 0.214      | -            | -                | -                | -         |    -3.82 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3720 | 2024-03-07 | 500               | L   | 0.201      | -            | -                | -                | -         |    -5.83 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3740 | 2024-03-06 | TSM               | W   | 0.196      | -            | -                | -                | -         |     0.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3810 | 2024-03-04 | Sampi             | W   | 0.180      | -            | -                | -                | -         |     1.05 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3836 | 2024-03-03 | Rebels            | L   | 0.175      | -            | -                | -                | -         |    -3.88 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3863 | 2024-03-02 | HAVU              | W   | 0.167      | -            | -                | -                | -         |     0.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3884 | 2024-02-29 | Rebels            | L   | 0.155      | -            | -                | -                | -         |    -3.48 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3905 | 2024-02-28 | Alliance          | L   | 0.147      | -            | -                | -                | -         |    -3.91 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3912 | 2024-02-27 | 9INE              | W   | 0.142      | -            | -                | -                | -         |     0.13 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3958 | 2024-02-25 | Sashi             | W   | 0.129      | -            | -                | -                | -         |     2.02 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4134 | 2024-02-18 | 500               | W   | 0.080      | -            | -                | -                | -         |     0.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4337 | 2024-02-08 | AURA              | L   | 0.015      | -            | -                | -                | -         |    -0.45 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4359 | 2024-02-06 | ex-Preasy         | L   | 0.000      | -            | -                | -                | -         |    -0.01 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,069.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.828 | $16,500.00     | $13,666.35      |
| 2024-05-22 |      0.708 | $50,000.00     | $35,402.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
