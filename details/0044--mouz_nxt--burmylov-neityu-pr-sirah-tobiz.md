### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1098.8<br />
<br />
Final Rank Value (1098.8) = Starting Rank Value (1042.1) + Head To Head Adjustments (56.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.262[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1042.1
- 400 + ( ( 0.314 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1042.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           90 |       38 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.29 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      243 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      246 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      302 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      377 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.460 (0.200)    | 0 (0.000) |     8.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      497 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      537 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.518 (0.259)    | 0 (0.000) |    24.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      551 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    11.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      601 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      743 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    12.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1125 | 2024-06-13 | B8                | L   | 0.849      | -            | -                | -                | -         |   -11.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1186 | 2024-06-10 | Endpoint          | L   | 0.830      | -            | -                | -                | -         |   -20.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1222 | 2024-06-09 | GhoulsW           | W   | 0.824      | -            | -                | -                | 0 (0.000) |     0.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1241 | 2024-06-09 | BLEED             | L   | 0.823      | -            | -                | -                | -         |    -4.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1298 | 2024-06-08 | Sampi             | W   | 0.817      | 0.435        | -                | 1.000 (0.355)    | 0 (0.000) |     6.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1310 | 2024-06-08 | ECLOT             | L   | 0.816      | -            | -                | -                | -         |   -11.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1338 | 2024-06-07 | GamerLegion       | L   | 0.811      | -            | -                | -                | -         |   -10.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1403 | 2024-06-06 | Rhyno             | W   | 0.805      | 0.500        | 0.071 (0.029)    | -                | 0 (0.000) |     8.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1432 | 2024-06-06 | Entropiq          | W   | 0.803      | -            | -                | -                | 0 (0.000) |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1530 | 2024-06-04 | NAVI Junior       | W   | 0.790      | -            | -                | -                | -         |     1.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1537 | 2024-06-04 | Aurora Young Blud | W   | 0.789      | -            | -                | -                | -         |     4.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1575 | 2024-06-02 | FURIA             | L   | 0.776      | -            | -                | -                | -         |    -1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1609 | 2024-06-01 | AMKAL             | W   | 0.770      | 0.435        | 0.130 (0.043)    | -                | -         |    15.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1668 | 2024-05-30 | Sangal            | W   | 0.756      | 0.435        | 0.219 (0.072)    | 0.861 (0.283)    | -         |    13.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1709 | 2024-05-28 | RUBY              | W   | 0.744      | 0.435        | 0.095 (0.031)    | -                | -         |     7.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1736 | 2024-05-27 | Nexus             | W   | 0.736      | -            | -                | -                | -         |     4.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1744 | 2024-05-26 | 9 Pandas          | L   | 0.731      | -            | -                | -                | -         |   -11.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1752 | 2024-05-26 | B8                | W   | 0.729      | 0.435        | 0.165 (0.052)    | 0.951 (0.301)    | -         |    14.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1777 | 2024-05-25 | 3DMAX             | W   | 0.722      | 0.435        | 0.507 (0.159)    | 1.000 (0.314)    | -         |    21.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1790 | 2024-05-24 | Illuminar         | W   | 0.716      | -            | -                | -                | -         |     6.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1803 | 2024-05-23 | Rare Atom         | W   | 0.710      | -            | -                | -                | -         |     3.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1843 | 2024-05-22 | Rhyno             | L   | 0.703      | -            | -                | -                | -         |   -12.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1885 | 2024-05-21 | DMS               | L   | 0.697      | -            | -                | -                | -         |   -14.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1954 | 2024-05-19 | BLEED             | L   | 0.682      | -            | -                | -                | -         |    -3.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2020 | 2024-05-17 | DMS               | W   | 0.669      | -            | -                | -                | -         |     6.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2045 | 2024-05-16 | Sampi             | W   | 0.664      | 0.435        | -                | 1.000 (0.288)    | -         |     6.93 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2108 | 2024-05-15 | BLEED             | L   | 0.656      | -            | -                | -                | -         |    -2.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2161 | 2024-05-14 | B8                | L   | 0.649      | -            | -                | -                | -         |    -8.82 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2185 | 2024-05-13 | Space             | W   | 0.642      | -            | -                | -                | -         |     4.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2207 | 2024-05-12 | B8                | L   | 0.636      | -            | -                | -                | -         |    -9.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2221 | 2024-05-11 | Endpoint          | W   | 0.631      | -            | -                | -                | -         |     7.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2247 | 2024-05-10 | Aurora            | W   | 0.625      | 0.435        | 0.423 (0.115)    | 0.792 (0.215)    | -         |    18.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2317 | 2024-05-07 | RUSH B            | W   | 0.603      | -            | -                | -                | -         |     5.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2360 | 2024-05-05 | GL Academy        | W   | 0.589      | -            | -                | -                | -         |     3.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2362 | 2024-05-04 | Enterprise        | L   | 0.585      | -            | -                | -                | -         |   -12.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2381 | 2024-05-03 | Nemiga            | L   | 0.577      | -            | -                | -                | -         |    -5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2401 | 2024-05-02 | Endpoint          | L   | 0.571      | -            | -                | -                | -         |   -12.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2414 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.570      | -            | -                | -                | -         |     7.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2420 | 2024-05-02 | 9 Pandas          | L   | 0.569      | -            | -                | -                | -         |   -11.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2435 | 2024-05-01 | BLEED             | W   | 0.563      | -            | -                | -                | -         |     9.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2447 | 2024-04-30 | ECLOT             | W   | 0.558      | -            | -                | -                | -         |    12.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2458 | 2024-04-30 | V1dar             | W   | 0.556      | -            | -                | -                | -         |     1.00 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2470 | 2024-04-29 | Nemiga            | L   | 0.551      | -            | -                | -                | -         |    -5.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2483 | 2024-04-29 | Grannys Knockers  | W   | 0.549      | -            | -                | -                | -         |     3.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2511 | 2024-04-27 | ECLOT             | W   | 0.538      | -            | -                | -                | -         |    12.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2583 | 2024-04-25 | Insilio           | L   | 0.522      | -            | -                | -                | -         |   -10.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2594 | 2024-04-24 | PARIVISION        | L   | 0.517      | -            | -                | -                | -         |    -7.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2628 | 2024-04-22 | EYEBALLERS        | W   | 0.504      | -            | -                | -                | -         |     4.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2636 | 2024-04-22 | Nemiga            | L   | 0.502      | -            | -                | -                | -         |    -5.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2645 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.497      | -            | -                | -                | -         |     5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2652 | 2024-04-21 | ECLOT             | L   | 0.496      | -            | -                | -                | -         |    -4.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2673 | 2024-04-20 | BLEED             | L   | 0.491      | -            | -                | -                | -         |    -8.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2771 | 2024-04-18 | Enterprise        | W   | 0.477      | -            | -                | -                | -         |     4.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2781 | 2024-04-18 | ENCE Academy      | W   | 0.476      | -            | -                | -                | -         |     2.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2830 | 2024-04-17 | JANO              | W   | 0.468      | -            | -                | -                | -         |     1.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2844 | 2024-04-16 | GamerLegion       | L   | 0.464      | -            | -                | -                | -         |    -5.84 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2869 | 2024-04-15 | Alliance          | W   | 0.456      | -            | -                | -                | -         |     3.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2909 | 2024-04-12 | Permitta          | L   | 0.436      | -            | -                | -                | -         |    -8.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3036 | 2024-04-09 | Zero Tenacity     | W   | 0.417      | -            | -                | -                | -         |     7.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3071 | 2024-04-08 | B8                | W   | 0.410      | -            | -                | -                | -         |     6.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3195 | 2024-04-03 | PARIVISION        | W   | 0.378      | -            | -                | -                | -         |     7.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3526 | 2024-03-16 | Sampi             | L   | 0.256      | -            | -                | -                | -         |    -5.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3544 | 2024-03-15 | Entropiq          | W   | 0.250      | -            | -                | -                | -         |     0.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3595 | 2024-03-13 | Permitta          | L   | 0.238      | -            | -                | -                | -         |    -4.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3613 | 2024-03-13 | Alliance          | W   | 0.236      | -            | -                | -                | -         |     2.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3640 | 2024-03-12 | AURA              | W   | 0.231      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3647 | 2024-03-12 | Sampi             | L   | 0.229      | -            | -                | -                | -         |    -5.06 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3667 | 2024-03-11 | Passion UA        | W   | 0.223      | -            | -                | -                | -         |     3.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3669 | 2024-03-11 | NOM               | W   | 0.222      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3675 | 2024-03-10 | V1dar             | W   | 0.218      | -            | -                | -                | -         |     0.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3687 | 2024-03-10 | Passion UA        | L   | 0.217      | -            | -                | -                | -         |    -3.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3691 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.216      | -            | -                | -                | -         |     2.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3728 | 2024-03-08 | Fraud5            | W   | 0.204      | -            | -                | -                | -         |     0.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3745 | 2024-03-07 | INGLORIOUS        | L   | 0.198      | -            | -                | -                | -         |    -5.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3879 | 2024-03-03 | ex-Preasy         | W   | 0.169      | -            | -                | -                | -         |     0.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3892 | 2024-03-02 | kONO              | W   | 0.163      | -            | -                | -                | -         |     1.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3962 | 2024-02-27 | ECLOT             | L   | 0.137      | -            | -                | -                | -         |    -1.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3977 | 2024-02-26 | BLEED             | W   | 0.130      | -            | -                | -                | -         |     1.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4040 | 2024-02-24 | Sashi             | W   | 0.116      | -            | -                | -                | -         |     2.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4102 | 2024-02-21 | Entropiq          | W   | 0.096      | -            | -                | -                | -         |     0.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,915.35)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.777 | $5,000.00      | $3,886.11       |
| 2024-05-26 |      0.731 | $10,000.00     | $7,308.33       |
| 2024-05-18 |      0.678 | $500.00        | $338.89         |
| 2024-05-12 |      0.638 | $5,000.00      | $3,188.54       |
| 2024-05-03 |      0.577 | $25,000.00     | $14,430.56      |
| 2024-03-18 |      0.269 | $1,000.00      | $268.89         |
| 2024-03-11 |      0.223 | $3,500.00      | $780.69         |
| 2024-02-28 |      0.142 | $1,500.00      | $213.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
