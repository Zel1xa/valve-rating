### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1272.0<br />
<br />
Final Rank Value (1272.0) = Starting Rank Value (1155.7) + Head To Head Adjustments (116.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.375[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1155.7
- 400 + ( ( 0.370 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1155.7


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
|           68 |       14 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           67 |      182 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.758 (0.379)    | 0 (0.000) |     4.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      235 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.709 (0.308)    | 0 (0.000) |    23.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      251 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.83 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      273 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.165 (0.072)    | 0.913 (0.397)    | 0 (0.000) |    12.93 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      288 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.876 (0.381)    | 0 (0.000) |     4.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      399 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      502 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      631 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      645 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.913 (0.456)    | 0 (0.000) |    13.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      737 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      757 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.04 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           56 |     1183 | 2024-06-09 | KOI               | W   | 0.831      | -            | -                | -                | -         |     8.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |     1249 | 2024-06-08 | SINNERS           | W   | 0.825      | 0.500        | -                | 0.758 (0.313)    | -         |     6.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1302 | 2024-06-07 | Aurora            | W   | 0.818      | 0.500        | 0.424 (0.174)    | 0.794 (0.325)    | -         |    22.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1369 | 2024-06-06 | 3DMAX             | W   | 0.812      | 0.500        | 0.505 (0.205)    | 1.000 (0.406)    | -         |    22.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1429 | 2024-06-05 | SAW               | W   | 0.805      | 0.500        | 0.106 (0.042)    | -                | -         |    14.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1480 | 2024-06-04 | 9 Pandas          | W   | 0.798      | -            | -                | -                | -         |    10.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1593 | 2024-05-31 | SAW               | L   | 0.772      | -            | -                | -                | -         |    -9.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1596 | 2024-05-31 | FAVBET            | W   | 0.771      | -            | -                | -                | -         |     3.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1600 | 2024-05-31 | fnatic            | L   | 0.771      | -            | -                | -                | -         |    -3.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1628 | 2024-05-30 | MOUZ NXT          | L   | 0.763      | -            | -                | -                | -         |   -13.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1800 | 2024-05-22 | Zero Tenacity     | W   | 0.711      | 0.500        | 0.137 (0.049)    | 1.000 (0.356)    | -         |    10.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1847 | 2024-05-21 | Monte             | W   | 0.704      | -            | -                | -                | -         |     8.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1882 | 2024-05-20 | PARIVISION        | W   | 0.697      | -            | -                | -                | -         |     9.90 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1897 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.692      | 0.500        | 0.223 (0.077)    | -                | -         |    20.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1904 | 2024-05-19 | Endpoint          | W   | 0.691      | -            | -                | -                | -         |     6.44 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1939 | 2024-05-18 | Rare Atom         | W   | 0.684      | -            | -                | -                | -         |     2.24 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     1981 | 2024-05-17 | Permitta          | W   | 0.676      | -            | -                | -                | -         |     5.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     1994 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.672      | -            | -                | -                | -         |    -1.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2061 | 2024-05-15 | Verdant           | L   | 0.663      | -            | -                | -                | -         |   -15.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2124 | 2024-05-14 | DMS               | L   | 0.656      | -            | -                | -                | -         |   -15.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2370 | 2024-05-02 | Metizport         | L   | 0.578      | -            | -                | -                | -         |   -13.34 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2403 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.569      | -            | -                | -                | -         |   -12.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2413 | 2024-04-30 | Zero Tenacity     | W   | 0.564      | -            | -                | -                | -         |     7.24 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2445 | 2024-04-29 | SINNERS           | W   | 0.556      | -            | -                | -                | -         |     6.94 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2452 | 2024-04-28 | 1WIN              | W   | 0.552      | -            | -                | -                | -         |     4.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2476 | 2024-04-27 | PARIVISION        | L   | 0.544      | -            | -                | -                | -         |    -9.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2509 | 2024-04-26 | Nemiga            | W   | 0.537      | 0.435        | 0.318 (0.074)    | -                | -         |     9.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2581 | 2024-04-23 | Grannys Knockers  | W   | 0.516      | -            | -                | -                | -         |     1.83 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2586 | 2024-04-22 | BLEED             | L   | 0.511      | -            | -                | -                | -         |    -9.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2597 | 2024-04-22 | ex-Guild Eagles   | L   | 0.509      | -            | -                | -                | -         |   -13.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2612 | 2024-04-21 | Alliance          | W   | 0.503      | -            | -                | -                | -         |     2.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2631 | 2024-04-20 | brazylijski luz   | W   | 0.498      | -            | -                | -                | -         |     2.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2647 | 2024-04-20 | JANO              | W   | 0.496      | -            | -                | -                | -         |     1.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2666 | 2024-04-19 | TSM               | W   | 0.492      | -            | -                | -                | -         |     1.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2678 | 2024-04-19 | Nemiga            | L   | 0.491      | -            | -                | -                | -         |    -7.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2786 | 2024-04-17 | 9 Pandas          | W   | 0.476      | -            | -                | -                | -         |     4.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2798 | 2024-04-16 | Zero Tenacity     | W   | 0.472      | -            | -                | -                | -         |     5.93 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2819 | 2024-04-15 | B8                | W   | 0.465      | -            | -                | -                | -         |     5.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2823 | 2024-04-15 | Aurora Young Blud | W   | 0.464      | -            | -                | -                | -         |     2.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2864 | 2024-04-12 | Monte             | L   | 0.444      | -            | -                | -                | -         |    -9.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     3117 | 2024-04-04 | EYEBALLERS        | W   | 0.392      | -            | -                | -                | -         |     2.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3200 | 2024-04-02 | 9 Pandas          | L   | 0.378      | -            | -                | -                | -         |    -8.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3557 | 2024-03-13 | KOI               | L   | 0.246      | -            | -                | -                | -         |    -4.46 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     3665 | 2024-03-09 | Zero Tenacity     | L   | 0.217      | -            | -                | -                | -         |    -3.87 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3714 | 2024-03-07 | 500               | L   | 0.204      | -            | -                | -                | -         |    -5.91 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3734 | 2024-03-06 | TSM               | W   | 0.199      | -            | -                | -                | -         |     0.41 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3804 | 2024-03-04 | Sampi             | W   | 0.183      | -            | -                | -                | -         |     1.07 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3830 | 2024-03-03 | Rebels            | L   | 0.178      | -            | -                | -                | -         |    -3.95 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3857 | 2024-03-02 | HAVU              | W   | 0.170      | -            | -                | -                | -         |     0.41 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3878 | 2024-02-29 | Rebels            | L   | 0.158      | -            | -                | -                | -         |    -3.54 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3899 | 2024-02-28 | Alliance          | L   | 0.150      | -            | -                | -                | -         |    -3.99 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3906 | 2024-02-27 | 9INE              | W   | 0.146      | -            | -                | -                | -         |     0.13 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3952 | 2024-02-25 | Sashi             | W   | 0.132      | -            | -                | -                | -         |     2.07 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4127 | 2024-02-18 | 500               | W   | 0.083      | -            | -                | -                | -         |     0.19 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4330 | 2024-02-08 | AURA              | L   | 0.018      | -            | -                | -                | -         |    -0.54 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4352 | 2024-02-06 | ex-Preasy         | L   | 0.003      | -            | -                | -                | -         |    -0.10 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,272.33)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.831 | $16,500.00     | $13,716.77      |
| 2024-05-22 |      0.711 | $50,000.00     | $35,555.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
