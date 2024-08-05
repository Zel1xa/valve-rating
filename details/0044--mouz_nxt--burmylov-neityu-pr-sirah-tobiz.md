### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1101.1<br />
<br />
Final Rank Value (1101.1) = Starting Rank Value (1044.9) + Head To Head Adjustments (56.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.267[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.315<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1044.9
- 400 + ( ( 0.315 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1044.9


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
|           90 |       51 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.24 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      256 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      259 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      315 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      390 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.499 (0.217)    | 0 (0.000) |     8.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      510 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      550 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.517 (0.258)    | 0 (0.000) |    24.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      564 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.442 (0.221)    | 0 (0.000) |    11.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      614 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      756 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.442 (0.221)    | 0 (0.000) |    12.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1138 | 2024-06-13 | B8                | L   | 0.845      | -            | -                | -                | -         |   -11.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1199 | 2024-06-10 | Endpoint          | L   | 0.827      | -            | -                | -                | -         |   -20.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1235 | 2024-06-09 | GhoulsW           | W   | 0.821      | -            | -                | -                | 0 (0.000) |     0.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1254 | 2024-06-09 | BLEED             | L   | 0.820      | -            | -                | -                | -         |    -4.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1311 | 2024-06-08 | Sampi             | W   | 0.814      | 0.435        | -                | 1.000 (0.354)    | 0 (0.000) |     6.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1323 | 2024-06-08 | ECLOT             | L   | 0.813      | -            | -                | -                | -         |   -11.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1351 | 2024-06-07 | GamerLegion       | L   | 0.808      | -            | -                | -                | -         |   -10.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1416 | 2024-06-06 | Rhyno             | W   | 0.801      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1445 | 2024-06-06 | Entropiq          | W   | 0.800      | -            | -                | -                | 0 (0.000) |     0.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1543 | 2024-06-04 | NAVI Junior       | W   | 0.786      | -            | -                | -                | -         |     1.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1550 | 2024-06-04 | Aurora Young Blud | W   | 0.785      | -            | -                | -                | -         |     4.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1588 | 2024-06-02 | FURIA             | L   | 0.773      | -            | -                | -                | -         |    -1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1622 | 2024-06-01 | AMKAL             | W   | 0.766      | 0.435        | 0.130 (0.043)    | -                | -         |    15.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1681 | 2024-05-30 | Sangal            | W   | 0.752      | 0.435        | 0.219 (0.072)    | 0.877 (0.287)    | -         |    13.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1722 | 2024-05-28 | RUBY              | W   | 0.741      | 0.435        | 0.095 (0.031)    | -                | -         |     7.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1749 | 2024-05-27 | Nexus             | W   | 0.732      | -            | -                | -                | -         |     3.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1757 | 2024-05-26 | 9 Pandas          | L   | 0.728      | -            | -                | -                | -         |   -11.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1765 | 2024-05-26 | B8                | W   | 0.726      | 0.435        | 0.165 (0.052)    | 0.947 (0.299)    | -         |    14.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1790 | 2024-05-25 | 3DMAX             | W   | 0.719      | 0.435        | 0.508 (0.159)    | 1.000 (0.312)    | -         |    21.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1803 | 2024-05-24 | Illuminar         | W   | 0.712      | -            | -                | -                | -         |     6.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1816 | 2024-05-23 | Rare Atom         | W   | 0.706      | -            | -                | -                | -         |     5.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1856 | 2024-05-22 | Rhyno             | L   | 0.700      | -            | -                | -                | -         |   -12.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1898 | 2024-05-21 | DMS               | L   | 0.693      | -            | -                | -                | -         |   -14.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1967 | 2024-05-19 | BLEED             | L   | 0.679      | -            | -                | -                | -         |    -3.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2033 | 2024-05-17 | DMS               | W   | 0.666      | -            | -                | -                | -         |     6.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2058 | 2024-05-16 | Sampi             | W   | 0.660      | 0.435        | -                | 1.000 (0.287)    | -         |     6.85 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2121 | 2024-05-15 | BLEED             | L   | 0.652      | -            | -                | -                | -         |    -2.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2174 | 2024-05-14 | B8                | L   | 0.646      | -            | -                | -                | -         |    -8.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2198 | 2024-05-13 | Space             | W   | 0.639      | -            | -                | -                | -         |     4.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2220 | 2024-05-12 | B8                | L   | 0.632      | -            | -                | -                | -         |    -9.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2234 | 2024-05-11 | Endpoint          | W   | 0.628      | -            | -                | -                | -         |     6.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2260 | 2024-05-10 | Aurora            | W   | 0.621      | 0.435        | 0.422 (0.114)    | 0.788 (0.213)    | -         |    18.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2330 | 2024-05-07 | RUSH B            | W   | 0.600      | -            | -                | -                | -         |     5.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2373 | 2024-05-05 | GL Academy        | W   | 0.586      | -            | -                | -                | -         |     3.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2375 | 2024-05-04 | Enterprise        | L   | 0.581      | -            | -                | -                | -         |   -12.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2394 | 2024-05-03 | Nemiga            | L   | 0.574      | -            | -                | -                | -         |    -5.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2414 | 2024-05-02 | Endpoint          | L   | 0.568      | -            | -                | -                | -         |   -12.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2427 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.566      | -            | -                | -                | -         |     7.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2433 | 2024-05-02 | 9 Pandas          | L   | 0.565      | -            | -                | -                | -         |   -11.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2448 | 2024-05-01 | BLEED             | W   | 0.560      | -            | -                | -                | -         |     9.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2460 | 2024-04-30 | ECLOT             | W   | 0.555      | -            | -                | -                | -         |    12.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2471 | 2024-04-30 | V1dar             | W   | 0.553      | -            | -                | -                | -         |     0.98 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2483 | 2024-04-29 | Nemiga            | L   | 0.548      | -            | -                | -                | -         |    -5.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2496 | 2024-04-29 | Grannys Knockers  | W   | 0.546      | -            | -                | -                | -         |     3.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2524 | 2024-04-27 | ECLOT             | W   | 0.535      | -            | -                | -                | -         |    12.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2596 | 2024-04-25 | Insilio           | L   | 0.519      | -            | -                | -                | -         |   -10.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2607 | 2024-04-24 | PARIVISION        | L   | 0.514      | -            | -                | -                | -         |    -7.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2641 | 2024-04-22 | EYEBALLERS        | W   | 0.500      | -            | -                | -                | -         |     4.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2649 | 2024-04-22 | Nemiga            | L   | 0.499      | -            | -                | -                | -         |    -5.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2658 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.494      | -            | -                | -                | -         |     5.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2665 | 2024-04-21 | ECLOT             | L   | 0.493      | -            | -                | -                | -         |    -4.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2686 | 2024-04-20 | BLEED             | L   | 0.487      | -            | -                | -                | -         |    -8.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2784 | 2024-04-18 | Enterprise        | W   | 0.474      | -            | -                | -                | -         |     4.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2794 | 2024-04-18 | ENCE Academy      | W   | 0.473      | -            | -                | -                | -         |     2.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2843 | 2024-04-17 | JANO              | W   | 0.465      | -            | -                | -                | -         |     1.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2857 | 2024-04-16 | GamerLegion       | L   | 0.460      | -            | -                | -                | -         |    -5.86 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2882 | 2024-04-15 | Alliance          | W   | 0.452      | -            | -                | -                | -         |     3.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2922 | 2024-04-12 | Permitta          | L   | 0.433      | -            | -                | -                | -         |    -8.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3049 | 2024-04-09 | Zero Tenacity     | W   | 0.414      | -            | -                | -                | -         |     7.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3084 | 2024-04-08 | B8                | W   | 0.406      | -            | -                | -                | -         |     6.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3208 | 2024-04-03 | PARIVISION        | W   | 0.375      | -            | -                | -                | -         |     6.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3539 | 2024-03-16 | Sampi             | L   | 0.252      | -            | -                | -                | -         |    -5.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3557 | 2024-03-15 | Entropiq          | W   | 0.247      | -            | -                | -                | -         |     0.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3608 | 2024-03-13 | Permitta          | L   | 0.235      | -            | -                | -                | -         |    -4.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3626 | 2024-03-13 | Alliance          | W   | 0.233      | -            | -                | -                | -         |     1.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3653 | 2024-03-12 | AURA              | W   | 0.227      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3660 | 2024-03-12 | Sampi             | L   | 0.226      | -            | -                | -                | -         |    -5.02 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3680 | 2024-03-11 | Passion UA        | W   | 0.220      | -            | -                | -                | -         |     3.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3682 | 2024-03-11 | NOM               | W   | 0.219      | -            | -                | -                | -         |     0.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3688 | 2024-03-10 | V1dar             | W   | 0.215      | -            | -                | -                | -         |     0.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3700 | 2024-03-10 | Passion UA        | L   | 0.213      | -            | -                | -                | -         |    -3.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3704 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.212      | -            | -                | -                | -         |     2.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3741 | 2024-03-08 | Fraud5            | W   | 0.201      | -            | -                | -                | -         |     0.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3758 | 2024-03-07 | INGLORIOUS        | L   | 0.195      | -            | -                | -                | -         |    -5.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3892 | 2024-03-03 | ex-Preasy         | W   | 0.166      | -            | -                | -                | -         |     0.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3905 | 2024-03-02 | kONO              | W   | 0.160      | -            | -                | -                | -         |     1.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3975 | 2024-02-27 | ECLOT             | L   | 0.133      | -            | -                | -                | -         |    -1.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3990 | 2024-02-26 | BLEED             | W   | 0.127      | -            | -                | -                | -         |     1.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4053 | 2024-02-24 | Sashi             | W   | 0.112      | -            | -                | -                | -         |     2.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4115 | 2024-02-21 | Entropiq          | W   | 0.092      | -            | -                | -                | -         |     0.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,743.68)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.774 | $5,000.00      | $3,869.44       |
| 2024-05-26 |      0.728 | $10,000.00     | $7,275.00       |
| 2024-05-18 |      0.674 | $500.00        | $337.22         |
| 2024-05-12 |      0.634 | $5,000.00      | $3,171.88       |
| 2024-05-03 |      0.574 | $25,000.00     | $14,347.22      |
| 2024-03-18 |      0.266 | $1,000.00      | $265.56         |
| 2024-03-11 |      0.220 | $3,500.00      | $769.03         |
| 2024-02-28 |      0.139 | $1,500.00      | $208.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
