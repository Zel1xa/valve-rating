### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.3<br />
<br />
Final Rank Value (1102.3) = Starting Rank Value (1045.4) + Head To Head Adjustments (56.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.315<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1045.4
- 400 + ( ( 0.315 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1045.4


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
|           90 |       59 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.24 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      264 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      267 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      323 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      398 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.532 (0.231)    | 0 (0.000) |     8.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      518 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      558 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.511 (0.255)    | 0 (0.000) |    24.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      572 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.437 (0.219)    | 0 (0.000) |    11.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      622 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      764 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.437 (0.219)    | 0 (0.000) |    12.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1146 | 2024-06-13 | B8                | L   | 0.844      | -            | -                | -                | -         |   -11.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1207 | 2024-06-10 | Endpoint          | L   | 0.826      | -            | -                | -                | -         |   -20.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1243 | 2024-06-09 | GhoulsW           | W   | 0.820      | -            | -                | -                | 0 (0.000) |     0.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1262 | 2024-06-09 | BLEED             | L   | 0.819      | -            | -                | -                | -         |    -4.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1319 | 2024-06-08 | Sampi             | W   | 0.813      | 0.435        | -                | 1.000 (0.353)    | 0 (0.000) |     6.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1331 | 2024-06-08 | ECLOT             | L   | 0.812      | -            | -                | -                | -         |   -11.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1359 | 2024-06-07 | GamerLegion       | L   | 0.807      | -            | -                | -                | -         |   -10.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1424 | 2024-06-06 | Rhyno             | W   | 0.800      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1453 | 2024-06-06 | Entropiq          | W   | 0.799      | -            | -                | -                | 0 (0.000) |     0.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1551 | 2024-06-04 | NAVI Junior       | W   | 0.785      | -            | -                | -                | -         |     1.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1558 | 2024-06-04 | Aurora Young Blud | W   | 0.784      | -            | -                | -                | -         |     4.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1596 | 2024-06-02 | FURIA             | L   | 0.772      | -            | -                | -                | -         |    -1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1630 | 2024-06-01 | AMKAL             | W   | 0.765      | 0.435        | 0.130 (0.043)    | -                | -         |    15.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1689 | 2024-05-30 | Sangal            | W   | 0.751      | 0.435        | 0.219 (0.071)    | 0.866 (0.283)    | -         |    13.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1730 | 2024-05-28 | RUBY              | W   | 0.739      | 0.435        | 0.095 (0.031)    | -                | -         |     7.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1757 | 2024-05-27 | Nexus             | W   | 0.731      | -            | -                | -                | -         |     3.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1765 | 2024-05-26 | 9 Pandas          | L   | 0.726      | -            | -                | -                | -         |   -11.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1773 | 2024-05-26 | B8                | W   | 0.725      | 0.435        | 0.165 (0.052)    | 0.935 (0.295)    | -         |    14.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1798 | 2024-05-25 | 3DMAX             | W   | 0.718      | 0.435        | 0.508 (0.158)    | 1.000 (0.312)    | -         |    21.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1811 | 2024-05-24 | Illuminar         | W   | 0.711      | -            | -                | -                | -         |     6.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1824 | 2024-05-23 | Rare Atom         | W   | 0.705      | -            | -                | -                | -         |     5.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1864 | 2024-05-22 | Rhyno             | L   | 0.699      | -            | -                | -                | -         |   -12.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1906 | 2024-05-21 | DMS               | L   | 0.692      | -            | -                | -                | -         |   -14.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1975 | 2024-05-19 | BLEED             | L   | 0.678      | -            | -                | -                | -         |    -2.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2041 | 2024-05-17 | DMS               | W   | 0.664      | -            | -                | -                | -         |     6.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2066 | 2024-05-16 | Sampi             | W   | 0.659      | 0.435        | -                | 1.000 (0.287)    | -         |     6.82 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2129 | 2024-05-15 | BLEED             | L   | 0.651      | -            | -                | -                | -         |    -2.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2182 | 2024-05-14 | B8                | L   | 0.645      | -            | -                | -                | -         |    -8.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2206 | 2024-05-13 | Space             | W   | 0.637      | -            | -                | -                | -         |     4.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2228 | 2024-05-12 | B8                | L   | 0.631      | -            | -                | -                | -         |    -9.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2242 | 2024-05-11 | Endpoint          | W   | 0.627      | -            | -                | -                | -         |     6.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2268 | 2024-05-10 | Aurora            | W   | 0.620      | 0.435        | 0.422 (0.114)    | 0.779 (0.210)    | -         |    18.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2338 | 2024-05-07 | RUSH B            | W   | 0.599      | -            | -                | -                | -         |     5.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2381 | 2024-05-05 | GL Academy        | W   | 0.585      | -            | -                | -                | -         |     3.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2383 | 2024-05-04 | Enterprise        | L   | 0.580      | -            | -                | -                | -         |   -12.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2402 | 2024-05-03 | Nemiga            | L   | 0.573      | -            | -                | -                | -         |    -5.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2422 | 2024-05-02 | Endpoint          | L   | 0.567      | -            | -                | -                | -         |   -12.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2435 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.565      | -            | -                | -                | -         |     7.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2441 | 2024-05-02 | 9 Pandas          | L   | 0.564      | -            | -                | -                | -         |   -11.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2456 | 2024-05-01 | BLEED             | W   | 0.559      | -            | -                | -                | -         |     9.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2468 | 2024-04-30 | ECLOT             | W   | 0.554      | -            | -                | -                | -         |    12.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2479 | 2024-04-30 | V1dar             | W   | 0.552      | -            | -                | -                | -         |     0.97 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2491 | 2024-04-29 | Nemiga            | L   | 0.547      | -            | -                | -                | -         |    -5.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2504 | 2024-04-29 | Grannys Knockers  | W   | 0.545      | -            | -                | -                | -         |     3.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2532 | 2024-04-27 | ECLOT             | W   | 0.534      | -            | -                | -                | -         |    12.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2604 | 2024-04-25 | Insilio           | L   | 0.517      | -            | -                | -                | -         |   -10.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2615 | 2024-04-24 | PARIVISION        | L   | 0.512      | -            | -                | -                | -         |    -7.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2649 | 2024-04-22 | EYEBALLERS        | W   | 0.499      | -            | -                | -                | -         |     4.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2657 | 2024-04-22 | Nemiga            | L   | 0.498      | -            | -                | -                | -         |    -5.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2666 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.493      | -            | -                | -                | -         |     5.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2673 | 2024-04-21 | ECLOT             | L   | 0.492      | -            | -                | -                | -         |    -4.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2694 | 2024-04-20 | BLEED             | L   | 0.486      | -            | -                | -                | -         |    -8.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2792 | 2024-04-18 | Enterprise        | W   | 0.473      | -            | -                | -                | -         |     4.87 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2802 | 2024-04-18 | ENCE Academy      | W   | 0.472      | -            | -                | -                | -         |     2.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2851 | 2024-04-17 | JANO              | W   | 0.464      | -            | -                | -                | -         |     1.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2865 | 2024-04-16 | GamerLegion       | L   | 0.459      | -            | -                | -                | -         |    -5.87 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2890 | 2024-04-15 | Alliance          | W   | 0.451      | -            | -                | -                | -         |     3.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2930 | 2024-04-12 | Permitta          | L   | 0.432      | -            | -                | -                | -         |    -8.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3057 | 2024-04-09 | Zero Tenacity     | W   | 0.412      | -            | -                | -                | -         |     7.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3092 | 2024-04-08 | B8                | W   | 0.405      | -            | -                | -                | -         |     6.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3216 | 2024-04-03 | PARIVISION        | W   | 0.374      | -            | -                | -                | -         |     6.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3547 | 2024-03-16 | Sampi             | L   | 0.251      | -            | -                | -                | -         |    -5.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3565 | 2024-03-15 | Entropiq          | W   | 0.245      | -            | -                | -                | -         |     0.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3616 | 2024-03-13 | Permitta          | L   | 0.234      | -            | -                | -                | -         |    -4.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3634 | 2024-03-13 | Alliance          | W   | 0.232      | -            | -                | -                | -         |     1.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3661 | 2024-03-12 | AURA              | W   | 0.226      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3668 | 2024-03-12 | Sampi             | L   | 0.224      | -            | -                | -                | -         |    -5.00 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3688 | 2024-03-11 | Passion UA        | W   | 0.219      | -            | -                | -                | -         |     3.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3690 | 2024-03-11 | NOM               | W   | 0.218      | -            | -                | -                | -         |     0.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3696 | 2024-03-10 | V1dar             | W   | 0.214      | -            | -                | -                | -         |     0.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3708 | 2024-03-10 | Passion UA        | L   | 0.212      | -            | -                | -                | -         |    -3.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3712 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.211      | -            | -                | -                | -         |     2.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3749 | 2024-03-08 | Fraud5            | W   | 0.200      | -            | -                | -                | -         |     0.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3766 | 2024-03-07 | INGLORIOUS        | L   | 0.194      | -            | -                | -                | -         |    -5.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3900 | 2024-03-03 | ex-Preasy         | W   | 0.164      | -            | -                | -                | -         |     0.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3913 | 2024-03-02 | kONO              | W   | 0.159      | -            | -                | -                | -         |     1.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3983 | 2024-02-27 | ECLOT             | L   | 0.132      | -            | -                | -                | -         |    -1.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3998 | 2024-02-26 | BLEED             | W   | 0.126      | -            | -                | -                | -         |     1.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4061 | 2024-02-24 | Sashi             | W   | 0.111      | -            | -                | -                | -         |     2.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4123 | 2024-02-21 | Entropiq          | W   | 0.091      | -            | -                | -                | -         |     0.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,686.46)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.773 | $5,000.00      | $3,863.89       |
| 2024-05-26 |      0.726 | $10,000.00     | $7,263.89       |
| 2024-05-18 |      0.673 | $500.00        | $336.67         |
| 2024-05-12 |      0.633 | $5,000.00      | $3,166.32       |
| 2024-05-03 |      0.573 | $25,000.00     | $14,319.44      |
| 2024-03-18 |      0.264 | $1,000.00      | $264.44         |
| 2024-03-11 |      0.219 | $3,500.00      | $765.14         |
| 2024-02-28 |      0.138 | $1,500.00      | $206.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
