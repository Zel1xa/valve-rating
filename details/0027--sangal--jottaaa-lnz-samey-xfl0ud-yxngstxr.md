### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1275.3<br />
<br />
Final Rank Value (1275.3) = Starting Rank Value (1159.6) + Head To Head Adjustments (115.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.502[<sup>2</sup>](#table1)
- Opponent Network: 0.381[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1159.6
- 400 + ( ( 0.371 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1159.6


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
|           67 |       51 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      221 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.797 (0.398)    | 0 (0.000) |     5.25 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      274 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.708 (0.308)    | 0 (0.000) |    23.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      290 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      312 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.165 (0.072)    | 0.951 (0.413)    | 0 (0.000) |    12.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      326 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.876 (0.381)    | 0 (0.000) |     4.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      441 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      541 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.93 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      670 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      684 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.951 (0.475)    | 0 (0.000) |    13.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      778 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      795 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.95 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1223 | 2024-06-09 | KOI               | W   | 0.824      | -            | -                | -                | -         |     8.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1289 | 2024-06-08 | SINNERS           | W   | 0.818      | 0.500        | -                | 0.797 (0.326)    | -         |     7.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1342 | 2024-06-07 | Aurora            | W   | 0.811      | 0.500        | 0.423 (0.171)    | 0.792 (0.321)    | -         |    22.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1409 | 2024-06-06 | 3DMAX             | W   | 0.804      | 0.500        | 0.507 (0.204)    | 1.000 (0.402)    | -         |    22.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1469 | 2024-06-05 | SAW               | W   | 0.798      | 0.500        | 0.105 (0.042)    | -                | -         |    13.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1520 | 2024-06-04 | 9 Pandas          | W   | 0.791      | -            | -                | -                | -         |    10.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1633 | 2024-05-31 | SAW               | L   | 0.764      | -            | -                | -                | -         |    -9.34 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1636 | 2024-05-31 | FAVBET            | W   | 0.764      | -            | -                | -                | -         |     3.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1640 | 2024-05-31 | fnatic            | L   | 0.763      | -            | -                | -                | -         |    -3.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1668 | 2024-05-30 | MOUZ NXT          | L   | 0.756      | -            | -                | -                | -         |   -13.94 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1840 | 2024-05-22 | Zero Tenacity     | W   | 0.704      | 0.500        | 0.137 (0.048)    | 1.000 (0.352)    | -         |    10.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1887 | 2024-05-21 | Monte             | W   | 0.696      | -            | -                | -                | -         |     8.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1922 | 2024-05-20 | PARIVISION        | W   | 0.690      | -            | -                | -                | -         |     9.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1937 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.685      | 0.500        | 0.254 (0.087)    | -                | -         |    20.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1944 | 2024-05-19 | Endpoint          | W   | 0.683      | -            | -                | -                | -         |     6.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     1979 | 2024-05-18 | Rare Atom         | W   | 0.676      | -            | -                | -                | -         |     2.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2021 | 2024-05-17 | Permitta          | W   | 0.669      | -            | -                | -                | -         |     5.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2034 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.665      | -            | -                | -                | -         |    -1.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2101 | 2024-05-15 | Verdant           | L   | 0.656      | -            | -                | -                | -         |   -15.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2164 | 2024-05-14 | DMS               | L   | 0.649      | -            | -                | -                | -         |   -15.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2410 | 2024-05-02 | Metizport         | L   | 0.570      | -            | -                | -                | -         |   -14.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2443 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.562      | -            | -                | -                | -         |   -12.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2453 | 2024-04-30 | Zero Tenacity     | W   | 0.557      | -            | -                | -                | -         |     7.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2485 | 2024-04-29 | SINNERS           | W   | 0.549      | -            | -                | -                | -         |     7.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2492 | 2024-04-28 | 1WIN              | W   | 0.544      | -            | -                | -                | -         |     4.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2516 | 2024-04-27 | PARIVISION        | L   | 0.537      | -            | -                | -                | -         |    -9.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2550 | 2024-04-26 | Nemiga            | W   | 0.530      | 0.435        | 0.317 (0.073)    | -                | -         |     9.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2622 | 2024-04-23 | Grannys Knockers  | W   | 0.509      | -            | -                | -                | -         |     1.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2627 | 2024-04-22 | BLEED             | L   | 0.504      | -            | -                | -                | -         |    -9.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2638 | 2024-04-22 | ex-Guild Eagles   | L   | 0.502      | -            | -                | -                | -         |   -13.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2653 | 2024-04-21 | Alliance          | W   | 0.496      | -            | -                | -                | -         |     2.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2672 | 2024-04-20 | brazylijski luz   | W   | 0.491      | -            | -                | -                | -         |     2.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2688 | 2024-04-20 | JANO              | W   | 0.489      | -            | -                | -                | -         |     1.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2707 | 2024-04-19 | TSM               | W   | 0.485      | -            | -                | -                | -         |     1.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2719 | 2024-04-19 | Nemiga            | L   | 0.484      | -            | -                | -                | -         |    -7.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2827 | 2024-04-17 | 9 Pandas          | W   | 0.469      | -            | -                | -                | -         |     4.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2839 | 2024-04-16 | Zero Tenacity     | W   | 0.464      | -            | -                | -                | -         |     5.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2860 | 2024-04-15 | B8                | W   | 0.458      | -            | -                | -                | -         |     5.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2864 | 2024-04-15 | Aurora Young Blud | W   | 0.457      | -            | -                | -                | -         |     2.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2905 | 2024-04-12 | Monte             | L   | 0.437      | -            | -                | -                | -         |    -9.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3158 | 2024-04-04 | EYEBALLERS        | W   | 0.385      | -            | -                | -                | -         |     2.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3241 | 2024-04-02 | 9 Pandas          | L   | 0.371      | -            | -                | -                | -         |    -7.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3598 | 2024-03-13 | KOI               | L   | 0.238      | -            | -                | -                | -         |    -4.39 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3707 | 2024-03-09 | Zero Tenacity     | L   | 0.210      | -            | -                | -                | -         |    -3.77 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3756 | 2024-03-07 | 500               | L   | 0.197      | -            | -                | -                | -         |    -5.72 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3776 | 2024-03-06 | TSM               | W   | 0.192      | -            | -                | -                | -         |     0.38 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3846 | 2024-03-04 | Sampi             | W   | 0.176      | -            | -                | -                | -         |     1.01 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3872 | 2024-03-03 | Rebels            | L   | 0.171      | -            | -                | -                | -         |    -3.82 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3899 | 2024-03-02 | HAVU              | W   | 0.163      | -            | -                | -                | -         |     0.38 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3920 | 2024-02-29 | Rebels            | L   | 0.151      | -            | -                | -                | -         |    -3.41 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3941 | 2024-02-28 | Alliance          | L   | 0.143      | -            | -                | -                | -         |    -3.82 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3948 | 2024-02-27 | 9INE              | W   | 0.138      | -            | -                | -                | -         |     0.12 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     3994 | 2024-02-25 | Sashi             | W   | 0.125      | -            | -                | -                | -         |     1.95 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4170 | 2024-02-18 | 500               | W   | 0.076      | -            | -                | -                | -         |     0.17 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4373 | 2024-02-08 | AURA              | L   | 0.010      | -            | -                | -                | -         |    -0.32 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,792.05)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.824 | $16,500.00     | $13,597.60      |
| 2024-05-22 |      0.704 | $50,000.00     | $35,194.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
