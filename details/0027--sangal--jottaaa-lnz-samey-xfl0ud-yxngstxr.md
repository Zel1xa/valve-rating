### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1275.6<br />
<br />
Final Rank Value (1275.6) = Starting Rank Value (1159.8) + Head To Head Adjustments (115.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.502[<sup>2</sup>](#table1)
- Opponent Network: 0.382[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.372<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1159.8
- 400 + ( ( 0.372 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1159.8


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
|           67 |       47 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      216 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.797 (0.398)    | 0 (0.000) |     5.25 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      270 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.708 (0.308)    | 0 (0.000) |    23.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      286 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      308 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.165 (0.072)    | 0.951 (0.413)    | 0 (0.000) |    12.88 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      322 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.876 (0.381)    | 0 (0.000) |     4.42 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      437 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      537 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.94 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      666 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      680 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.951 (0.476)    | 0 (0.000) |    13.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      774 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      791 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.96 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1219 | 2024-06-09 | KOI               | W   | 0.826      | -            | -                | -                | -         |     8.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1285 | 2024-06-08 | SINNERS           | W   | 0.820      | 0.500        | -                | 0.797 (0.327)    | -         |     7.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1338 | 2024-06-07 | Aurora            | W   | 0.814      | 0.500        | 0.423 (0.172)    | 0.793 (0.322)    | -         |    22.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1405 | 2024-06-06 | 3DMAX             | W   | 0.807      | 0.500        | 0.506 (0.204)    | 1.000 (0.403)    | -         |    22.30 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1465 | 2024-06-05 | SAW               | W   | 0.800      | 0.500        | 0.105 (0.042)    | -                | -         |    13.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1516 | 2024-06-04 | 9 Pandas          | W   | 0.793      | -            | -                | -                | -         |    10.42 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1629 | 2024-05-31 | SAW               | L   | 0.767      | -            | -                | -                | -         |    -9.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1632 | 2024-05-31 | FAVBET            | W   | 0.766      | -            | -                | -                | -         |     3.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1636 | 2024-05-31 | fnatic            | L   | 0.766      | -            | -                | -                | -         |    -3.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1664 | 2024-05-30 | MOUZ NXT          | L   | 0.758      | -            | -                | -                | -         |   -13.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1836 | 2024-05-22 | Zero Tenacity     | W   | 0.706      | 0.500        | 0.137 (0.048)    | 1.000 (0.353)    | -         |    10.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1883 | 2024-05-21 | Monte             | W   | 0.699      | -            | -                | -                | -         |     8.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1918 | 2024-05-20 | PARIVISION        | W   | 0.692      | -            | -                | -                | -         |     9.78 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1933 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.687      | 0.500        | 0.254 (0.087)    | -                | -         |    20.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1940 | 2024-05-19 | Endpoint          | W   | 0.686      | -            | -                | -                | -         |     6.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     1975 | 2024-05-18 | Rare Atom         | W   | 0.679      | -            | -                | -                | -         |     2.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2017 | 2024-05-17 | Permitta          | W   | 0.671      | -            | -                | -                | -         |     5.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2030 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.667      | -            | -                | -                | -         |    -1.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2097 | 2024-05-15 | Verdant           | L   | 0.659      | -            | -                | -                | -         |   -15.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2160 | 2024-05-14 | DMS               | L   | 0.651      | -            | -                | -                | -         |   -15.44 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2406 | 2024-05-02 | Metizport         | L   | 0.573      | -            | -                | -                | -         |   -14.26 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2439 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.565      | -            | -                | -                | -         |   -12.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2449 | 2024-04-30 | Zero Tenacity     | W   | 0.560      | -            | -                | -                | -         |     7.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2481 | 2024-04-29 | SINNERS           | W   | 0.551      | -            | -                | -                | -         |     7.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2488 | 2024-04-28 | 1WIN              | W   | 0.547      | -            | -                | -                | -         |     4.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2512 | 2024-04-27 | PARIVISION        | L   | 0.540      | -            | -                | -                | -         |    -9.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2546 | 2024-04-26 | Nemiga            | W   | 0.532      | 0.435        | 0.317 (0.073)    | -                | -         |     9.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2618 | 2024-04-23 | Grannys Knockers  | W   | 0.511      | -            | -                | -                | -         |     1.78 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2623 | 2024-04-22 | BLEED             | L   | 0.506      | -            | -                | -                | -         |    -9.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2634 | 2024-04-22 | ex-Guild Eagles   | L   | 0.504      | -            | -                | -                | -         |   -13.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2649 | 2024-04-21 | Alliance          | W   | 0.498      | -            | -                | -                | -         |     2.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2668 | 2024-04-20 | brazylijski luz   | W   | 0.493      | -            | -                | -                | -         |     2.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2684 | 2024-04-20 | JANO              | W   | 0.491      | -            | -                | -                | -         |     1.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2703 | 2024-04-19 | TSM               | W   | 0.487      | -            | -                | -                | -         |     1.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2715 | 2024-04-19 | Nemiga            | L   | 0.486      | -            | -                | -                | -         |    -7.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2823 | 2024-04-17 | 9 Pandas          | W   | 0.471      | -            | -                | -                | -         |     4.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2835 | 2024-04-16 | Zero Tenacity     | W   | 0.467      | -            | -                | -                | -         |     5.83 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2856 | 2024-04-15 | B8                | W   | 0.460      | -            | -                | -                | -         |     5.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2860 | 2024-04-15 | Aurora Young Blud | W   | 0.459      | -            | -                | -                | -         |     2.42 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2901 | 2024-04-12 | Monte             | L   | 0.440      | -            | -                | -                | -         |    -9.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3154 | 2024-04-04 | EYEBALLERS        | W   | 0.387      | -            | -                | -                | -         |     2.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3237 | 2024-04-02 | 9 Pandas          | L   | 0.373      | -            | -                | -                | -         |    -8.02 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3594 | 2024-03-13 | KOI               | L   | 0.241      | -            | -                | -                | -         |    -4.42 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3703 | 2024-03-09 | Zero Tenacity     | L   | 0.213      | -            | -                | -                | -         |    -3.81 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3752 | 2024-03-07 | 500               | L   | 0.199      | -            | -                | -                | -         |    -5.79 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3772 | 2024-03-06 | TSM               | W   | 0.194      | -            | -                | -                | -         |     0.39 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3842 | 2024-03-04 | Sampi             | W   | 0.178      | -            | -                | -                | -         |     1.03 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3868 | 2024-03-03 | Rebels            | L   | 0.173      | -            | -                | -                | -         |    -3.87 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3895 | 2024-03-02 | HAVU              | W   | 0.165      | -            | -                | -                | -         |     0.39 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3916 | 2024-02-29 | Rebels            | L   | 0.153      | -            | -                | -                | -         |    -3.46 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3937 | 2024-02-28 | Alliance          | L   | 0.145      | -            | -                | -                | -         |    -3.88 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3944 | 2024-02-27 | 9INE              | W   | 0.141      | -            | -                | -                | -         |     0.12 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     3990 | 2024-02-25 | Sashi             | W   | 0.127      | -            | -                | -                | -         |     1.98 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4166 | 2024-02-18 | 500               | W   | 0.078      | -            | -                | -                | -         |     0.17 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4369 | 2024-02-08 | AURA              | L   | 0.013      | -            | -                | -                | -         |    -0.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,950.60)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.826 | $16,500.00     | $13,636.94      |
| 2024-05-22 |      0.706 | $50,000.00     | $35,313.66      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
