### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1097.5<br />
<br />
Final Rank Value (1097.5) = Starting Rank Value (1041.8) + Head To Head Adjustments (55.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1041.8
- 400 + ( ( 0.314 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1041.8


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
|           90 |       12 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.36 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      215 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      219 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      274 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      350 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.459 (0.200)    | 0 (0.000) |     8.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      469 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      509 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.517 (0.259)    | 0 (0.000) |    24.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      523 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    11.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      576 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      716 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    12.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1097 | 2024-06-13 | B8                | L   | 0.852      | -            | -                | -                | -         |   -11.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1158 | 2024-06-10 | Endpoint          | L   | 0.833      | -            | -                | -                | -         |   -20.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1194 | 2024-06-09 | GhoulsW           | W   | 0.828      | -            | -                | -                | 0 (0.000) |     0.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1213 | 2024-06-09 | BLEED             | L   | 0.827      | -            | -                | -                | -         |    -4.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1270 | 2024-06-08 | Sampi             | W   | 0.821      | 0.435        | -                | 1.000 (0.357)    | 0 (0.000) |     6.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1282 | 2024-06-08 | ECLOT             | L   | 0.820      | -            | -                | -                | -         |   -11.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1310 | 2024-06-07 | GamerLegion       | L   | 0.815      | -            | -                | -                | -         |   -10.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1375 | 2024-06-06 | Rhyno             | W   | 0.808      | 0.500        | 0.071 (0.029)    | -                | 0 (0.000) |     8.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1404 | 2024-06-06 | Entropiq          | W   | 0.807      | -            | -                | -                | 0 (0.000) |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1502 | 2024-06-04 | NAVI Junior       | W   | 0.793      | -            | -                | -                | -         |     1.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1509 | 2024-06-04 | Aurora Young Blud | W   | 0.792      | -            | -                | -                | -         |     4.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1547 | 2024-06-02 | FURIA             | L   | 0.780      | -            | -                | -                | -         |    -1.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1581 | 2024-06-01 | AMKAL             | W   | 0.773      | 0.435        | 0.130 (0.044)    | -                | -         |    15.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1640 | 2024-05-30 | Sangal            | W   | 0.759      | 0.435        | 0.219 (0.072)    | 0.861 (0.284)    | -         |    13.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1681 | 2024-05-28 | RUBY              | W   | 0.747      | 0.435        | 0.095 (0.031)    | -                | -         |     7.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1708 | 2024-05-27 | Nexus             | W   | 0.739      | -            | -                | -                | -         |     4.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1716 | 2024-05-26 | 9 Pandas          | L   | 0.734      | -            | -                | -                | -         |   -11.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1724 | 2024-05-26 | B8                | W   | 0.733      | 0.435        | 0.165 (0.053)    | 0.912 (0.290)    | -         |    15.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1749 | 2024-05-25 | 3DMAX             | W   | 0.725      | 0.435        | 0.506 (0.159)    | 1.000 (0.315)    | -         |    21.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1762 | 2024-05-24 | Illuminar         | W   | 0.719      | -            | -                | -                | -         |     6.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1775 | 2024-05-23 | Rare Atom         | W   | 0.713      | -            | -                | -                | -         |     3.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1815 | 2024-05-22 | Rhyno             | L   | 0.707      | -            | -                | -                | -         |   -12.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1857 | 2024-05-21 | DMS               | L   | 0.700      | -            | -                | -                | -         |   -14.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1926 | 2024-05-19 | BLEED             | L   | 0.686      | -            | -                | -                | -         |    -3.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     1992 | 2024-05-17 | DMS               | W   | 0.672      | -            | -                | -                | -         |     6.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2017 | 2024-05-16 | Sampi             | W   | 0.667      | 0.435        | -                | 1.000 (0.290)    | -         |     7.00 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2080 | 2024-05-15 | BLEED             | L   | 0.659      | -            | -                | -                | -         |    -2.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2133 | 2024-05-14 | B8                | L   | 0.653      | -            | -                | -                | -         |    -8.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2157 | 2024-05-13 | Space             | W   | 0.645      | -            | -                | -                | -         |     4.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2179 | 2024-05-12 | B8                | L   | 0.639      | -            | -                | -                | -         |    -9.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2193 | 2024-05-11 | Endpoint          | W   | 0.635      | -            | -                | -                | -         |     7.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2219 | 2024-05-10 | Aurora            | W   | 0.628      | 0.435        | 0.423 (0.116)    | 0.793 (0.216)    | -         |    18.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2289 | 2024-05-07 | RUSH B            | W   | 0.607      | -            | -                | -                | -         |     5.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2332 | 2024-05-05 | GL Academy        | W   | 0.593      | -            | -                | -                | -         |     3.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2334 | 2024-05-04 | Enterprise        | L   | 0.588      | -            | -                | -                | -         |   -12.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2353 | 2024-05-03 | Nemiga            | L   | 0.581      | -            | -                | -                | -         |    -6.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2373 | 2024-05-02 | Endpoint          | L   | 0.575      | -            | -                | -                | -         |   -12.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2386 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.573      | -            | -                | -                | -         |     7.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2392 | 2024-05-02 | 9 Pandas          | L   | 0.572      | -            | -                | -                | -         |   -11.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2407 | 2024-05-01 | BLEED             | W   | 0.567      | -            | -                | -                | -         |     9.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2419 | 2024-04-30 | ECLOT             | W   | 0.562      | -            | -                | -                | -         |    12.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2430 | 2024-04-30 | V1dar             | W   | 0.560      | -            | -                | -                | -         |     1.01 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2442 | 2024-04-29 | Nemiga            | L   | 0.555      | -            | -                | -                | -         |    -6.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2455 | 2024-04-29 | Grannys Knockers  | W   | 0.553      | -            | -                | -                | -         |     3.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2483 | 2024-04-27 | ECLOT             | W   | 0.542      | -            | -                | -                | -         |    12.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2555 | 2024-04-25 | Insilio           | L   | 0.525      | -            | -                | -                | -         |   -10.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2566 | 2024-04-24 | PARIVISION        | L   | 0.520      | -            | -                | -                | -         |    -7.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2600 | 2024-04-22 | EYEBALLERS        | W   | 0.507      | -            | -                | -                | -         |     4.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2608 | 2024-04-22 | Nemiga            | L   | 0.506      | -            | -                | -                | -         |    -5.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2617 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.501      | -            | -                | -                | -         |     5.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2624 | 2024-04-21 | ECLOT             | L   | 0.499      | -            | -                | -                | -         |    -4.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2645 | 2024-04-20 | BLEED             | L   | 0.494      | -            | -                | -                | -         |    -8.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2743 | 2024-04-18 | Enterprise        | W   | 0.481      | -            | -                | -                | -         |     4.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2753 | 2024-04-18 | ENCE Academy      | W   | 0.479      | -            | -                | -                | -         |     2.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2802 | 2024-04-17 | JANO              | W   | 0.472      | -            | -                | -                | -         |     1.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2816 | 2024-04-16 | GamerLegion       | L   | 0.467      | -            | -                | -                | -         |    -5.90 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2841 | 2024-04-15 | Alliance          | W   | 0.459      | -            | -                | -                | -         |     3.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2881 | 2024-04-12 | Permitta          | L   | 0.439      | -            | -                | -                | -         |    -8.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3008 | 2024-04-09 | Zero Tenacity     | W   | 0.420      | -            | -                | -                | -         |     7.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3043 | 2024-04-08 | B8                | W   | 0.413      | -            | -                | -                | -         |     7.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3167 | 2024-04-03 | PARIVISION        | W   | 0.382      | -            | -                | -                | -         |     7.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3498 | 2024-03-16 | Sampi             | L   | 0.259      | -            | -                | -                | -         |    -5.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3516 | 2024-03-15 | Entropiq          | W   | 0.253      | -            | -                | -                | -         |     0.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3567 | 2024-03-13 | Permitta          | L   | 0.242      | -            | -                | -                | -         |    -4.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3585 | 2024-03-13 | Alliance          | W   | 0.240      | -            | -                | -                | -         |     2.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3612 | 2024-03-12 | AURA              | W   | 0.234      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3619 | 2024-03-12 | Sampi             | L   | 0.232      | -            | -                | -                | -         |    -5.13 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3639 | 2024-03-11 | Passion UA        | W   | 0.227      | -            | -                | -                | -         |     3.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3641 | 2024-03-11 | NOM               | W   | 0.226      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3647 | 2024-03-10 | V1dar             | W   | 0.222      | -            | -                | -                | -         |     0.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3659 | 2024-03-10 | Passion UA        | L   | 0.220      | -            | -                | -                | -         |    -3.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3663 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.219      | -            | -                | -                | -         |     2.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3700 | 2024-03-08 | Fraud5            | W   | 0.208      | -            | -                | -                | -         |     0.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3717 | 2024-03-07 | INGLORIOUS        | L   | 0.202      | -            | -                | -                | -         |    -6.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3851 | 2024-03-03 | ex-Preasy         | W   | 0.172      | -            | -                | -                | -         |     1.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3864 | 2024-03-02 | kONO              | W   | 0.167      | -            | -                | -                | -         |     1.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3934 | 2024-02-27 | ECLOT             | L   | 0.140      | -            | -                | -                | -         |    -1.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3949 | 2024-02-26 | BLEED             | W   | 0.133      | -            | -                | -                | -         |     1.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4012 | 2024-02-24 | Sashi             | W   | 0.119      | -            | -                | -                | -         |     2.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4074 | 2024-02-21 | Entropiq          | W   | 0.099      | -            | -                | -                | -         |     0.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,092.97)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.781 | $5,000.00      | $3,903.36       |
| 2024-05-26 |      0.734 | $10,000.00     | $7,342.82       |
| 2024-05-18 |      0.681 | $500.00        | $340.61         |
| 2024-05-12 |      0.641 | $5,000.00      | $3,205.79       |
| 2024-05-03 |      0.581 | $25,000.00     | $14,516.78      |
| 2024-03-18 |      0.272 | $1,000.00      | $272.34         |
| 2024-03-11 |      0.227 | $3,500.00      | $792.77         |
| 2024-02-28 |      0.146 | $1,500.00      | $218.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
