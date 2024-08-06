### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1283.1<br />
<br />
Final Rank Value (1283.1) = Starting Rank Value (1160.6) + Head To Head Adjustments (122.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.379[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.6
- 400 + ( ( 0.371 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1160.6


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
|           68 |       19 | 2024-08-05 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.76 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       75 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      244 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.808 (0.404)    | 0 (0.000) |     5.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      298 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.696 (0.303)    | 0 (0.000) |    23.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      314 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      336 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.164 (0.071)    | 0.934 (0.406)    | 0 (0.000) |    12.82 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      350 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.901 (0.392)    | 0 (0.000) |     4.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      465 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      565 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      694 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      708 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.164 (0.082)    | 0.934 (0.467)    | 0 (0.000) |    13.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      802 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      819 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.87 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1247 | 2024-06-09 | KOI               | W   | 0.817      | -            | -                | -                | -         |     8.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1313 | 2024-06-08 | SINNERS           | W   | 0.811      | 0.500        | -                | 0.808 (0.328)    | -         |     7.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1366 | 2024-06-07 | Aurora            | W   | 0.805      | 0.500        | 0.421 (0.169)    | 0.777 (0.313)    | -         |    22.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1433 | 2024-06-06 | 3DMAX             | W   | 0.798      | 0.500        | 0.509 (0.203)    | 1.000 (0.399)    | -         |    22.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1493 | 2024-06-05 | SAW               | W   | 0.791      | 0.500        | 0.104 (0.041)    | -                | -         |    13.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1544 | 2024-06-04 | 9 Pandas          | W   | 0.784      | -            | -                | -                | -         |    10.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1657 | 2024-05-31 | SAW               | L   | 0.758      | -            | -                | -                | -         |    -9.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1660 | 2024-05-31 | FAVBET            | W   | 0.757      | -            | -                | -                | -         |     3.02 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1664 | 2024-05-31 | fnatic            | L   | 0.757      | -            | -                | -                | -         |    -3.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1692 | 2024-05-30 | MOUZ NXT          | L   | 0.749      | -            | -                | -                | -         |   -13.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1864 | 2024-05-22 | Zero Tenacity     | W   | 0.697      | 0.500        | 0.143 (0.050)    | 1.000 (0.349)    | -         |    10.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1911 | 2024-05-21 | Monte             | W   | 0.690      | -            | -                | -                | -         |     7.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1946 | 2024-05-20 | PARIVISION        | W   | 0.683      | -            | -                | -                | -         |     9.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1961 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.678      | 0.500        | 0.254 (0.086)    | -                | -         |    19.85 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1968 | 2024-05-19 | Endpoint          | W   | 0.677      | -            | -                | -                | -         |     6.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2003 | 2024-05-18 | Rare Atom         | W   | 0.670      | -            | -                | -                | -         |     4.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2045 | 2024-05-17 | Permitta          | W   | 0.662      | -            | -                | -                | -         |     5.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2058 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.658      | -            | -                | -                | -         |    -1.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2125 | 2024-05-15 | Verdant           | L   | 0.650      | -            | -                | -                | -         |   -15.03 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2188 | 2024-05-14 | DMS               | L   | 0.642      | -            | -                | -                | -         |   -15.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2434 | 2024-05-02 | Metizport         | L   | 0.564      | -            | -                | -                | -         |   -14.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2467 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.556      | -            | -                | -                | -         |   -12.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2477 | 2024-04-30 | Zero Tenacity     | W   | 0.551      | -            | -                | -                | -         |     7.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2509 | 2024-04-29 | SINNERS           | W   | 0.542      | -            | -                | -                | -         |     7.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2516 | 2024-04-28 | 1WIN              | W   | 0.538      | -            | -                | -                | -         |     4.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2540 | 2024-04-27 | PARIVISION        | L   | 0.531      | -            | -                | -                | -         |    -9.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2574 | 2024-04-26 | Nemiga            | W   | 0.523      | 0.435        | 0.315 (0.072)    | -                | -         |     9.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2646 | 2024-04-23 | Grannys Knockers  | W   | 0.502      | -            | -                | -                | -         |     1.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2651 | 2024-04-22 | BLEED             | L   | 0.497      | -            | -                | -                | -         |    -9.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2662 | 2024-04-22 | ex-Guild Eagles   | L   | 0.495      | -            | -                | -                | -         |   -13.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2677 | 2024-04-21 | Alliance          | W   | 0.489      | -            | -                | -                | -         |     2.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2696 | 2024-04-20 | brazylijski luz   | W   | 0.484      | -            | -                | -                | -         |     2.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2712 | 2024-04-20 | JANO              | W   | 0.482      | -            | -                | -                | -         |     1.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2731 | 2024-04-19 | TSM               | W   | 0.478      | -            | -                | -                | -         |     1.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2743 | 2024-04-19 | Nemiga            | L   | 0.477      | -            | -                | -                | -         |    -7.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2851 | 2024-04-17 | 9 Pandas          | W   | 0.462      | -            | -                | -                | -         |     4.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2863 | 2024-04-16 | Zero Tenacity     | W   | 0.458      | -            | -                | -                | -         |     5.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2884 | 2024-04-15 | B8                | W   | 0.451      | -            | -                | -                | -         |     5.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2888 | 2024-04-15 | Aurora Young Blud | W   | 0.450      | -            | -                | -                | -         |     2.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2929 | 2024-04-12 | Monte             | L   | 0.431      | -            | -                | -                | -         |    -9.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3182 | 2024-04-04 | EYEBALLERS        | W   | 0.378      | -            | -                | -                | -         |     2.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3265 | 2024-04-02 | 9 Pandas          | L   | 0.364      | -            | -                | -                | -         |    -7.89 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3622 | 2024-03-13 | KOI               | L   | 0.232      | -            | -                | -                | -         |    -4.31 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3731 | 2024-03-09 | Zero Tenacity     | L   | 0.204      | -            | -                | -                | -         |    -3.63 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3780 | 2024-03-07 | 500               | L   | 0.190      | -            | -                | -                | -         |    -5.53 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3800 | 2024-03-06 | TSM               | W   | 0.185      | -            | -                | -                | -         |     0.37 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3870 | 2024-03-04 | Sampi             | W   | 0.169      | -            | -                | -                | -         |     0.96 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3896 | 2024-03-03 | Rebels            | L   | 0.164      | -            | -                | -                | -         |    -3.69 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3923 | 2024-03-02 | HAVU              | W   | 0.156      | -            | -                | -                | -         |     0.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3944 | 2024-02-29 | Rebels            | L   | 0.144      | -            | -                | -                | -         |    -3.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3965 | 2024-02-28 | Alliance          | L   | 0.136      | -            | -                | -                | -         |    -3.64 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3972 | 2024-02-27 | 9INE              | W   | 0.132      | -            | -                | -                | -         |     0.11 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4018 | 2024-02-25 | Sashi             | W   | 0.118      | -            | -                | -                | -         |     1.84 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4194 | 2024-02-18 | 500               | W   | 0.069      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4397 | 2024-02-08 | AURA              | L   | 0.004      | -            | -                | -                | -         |    -0.12 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,348.72)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.817 | $16,500.00     | $13,487.60      |
| 2024-05-22 |      0.697 | $50,000.00     | $34,861.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
