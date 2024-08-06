### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.8<br />
<br />
Final Rank Value (1102.8) = Starting Rank Value (1045.6) + Head To Head Adjustments (57.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.454[<sup>2</sup>](#table1)
- Opponent Network: 0.263[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1045.6
- 400 + ( ( 0.314 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1045.6


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
|           90 |       70 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.20 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      275 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      278 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      334 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      409 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.521 (0.226)    | 0 (0.000) |     8.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      529 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      569 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.538 (0.269)    | 0 (0.000) |    24.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      583 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    11.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      633 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      775 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    12.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1157 | 2024-06-13 | B8                | L   | 0.839      | -            | -                | -                | -         |   -11.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1218 | 2024-06-10 | Endpoint          | L   | 0.821      | -            | -                | -                | -         |   -20.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1254 | 2024-06-09 | GhoulsW           | W   | 0.815      | -            | -                | -                | 0 (0.000) |     0.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1273 | 2024-06-09 | BLEED             | L   | 0.814      | -            | -                | -                | -         |    -4.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1330 | 2024-06-08 | Sampi             | W   | 0.808      | 0.435        | -                | 1.000 (0.351)    | 0 (0.000) |     6.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1342 | 2024-06-08 | ECLOT             | L   | 0.807      | -            | -                | -                | -         |   -10.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1370 | 2024-06-07 | GamerLegion       | L   | 0.802      | -            | -                | -                | -         |   -10.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1435 | 2024-06-06 | Rhyno             | W   | 0.795      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1464 | 2024-06-06 | Entropiq          | W   | 0.794      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1562 | 2024-06-04 | NAVI Junior       | W   | 0.780      | -            | -                | -                | -         |     1.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1569 | 2024-06-04 | Aurora Young Blud | W   | 0.779      | -            | -                | -                | -         |     4.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1607 | 2024-06-02 | FURIA             | L   | 0.767      | -            | -                | -                | -         |    -1.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1641 | 2024-06-01 | AMKAL             | W   | 0.760      | 0.435        | 0.130 (0.043)    | -                | -         |    15.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1700 | 2024-05-30 | Sangal            | W   | 0.746      | 0.435        | 0.219 (0.071)    | 0.846 (0.274)    | -         |    13.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1741 | 2024-05-28 | RUBY              | W   | 0.734      | 0.435        | 0.095 (0.030)    | -                | -         |     7.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1768 | 2024-05-27 | Nexus             | W   | 0.726      | -            | -                | -                | -         |     3.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1776 | 2024-05-26 | 9 Pandas          | L   | 0.721      | -            | -                | -                | -         |   -11.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1784 | 2024-05-26 | B8                | W   | 0.720      | 0.435        | 0.170 (0.053)    | 0.912 (0.285)    | -         |    14.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1809 | 2024-05-25 | 3DMAX             | W   | 0.713      | 0.435        | 0.510 (0.158)    | 1.000 (0.310)    | -         |    21.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1822 | 2024-05-24 | Illuminar         | W   | 0.706      | -            | -                | -                | -         |     6.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1835 | 2024-05-23 | Rare Atom         | W   | 0.700      | -            | -                | -                | -         |     5.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1875 | 2024-05-22 | Rhyno             | L   | 0.694      | -            | -                | -                | -         |   -12.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1917 | 2024-05-21 | DMS               | L   | 0.687      | -            | -                | -                | -         |   -14.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1986 | 2024-05-19 | BLEED             | L   | 0.673      | -            | -                | -                | -         |    -2.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2052 | 2024-05-17 | DMS               | W   | 0.659      | -            | -                | -                | -         |     6.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2077 | 2024-05-16 | Sampi             | W   | 0.654      | 0.435        | -                | 1.000 (0.284)    | -         |     6.77 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2140 | 2024-05-15 | BLEED             | L   | 0.646      | -            | -                | -                | -         |    -2.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2193 | 2024-05-14 | B8                | L   | 0.640      | -            | -                | -                | -         |    -8.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2217 | 2024-05-13 | Space             | W   | 0.632      | -            | -                | -                | -         |     4.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2239 | 2024-05-12 | B8                | L   | 0.626      | -            | -                | -                | -         |    -9.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2253 | 2024-05-11 | Endpoint          | W   | 0.622      | -            | -                | -                | -         |     6.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2279 | 2024-05-10 | Aurora            | W   | 0.615      | 0.435        | 0.421 (0.112)    | 0.759 (0.203)    | -         |    18.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2349 | 2024-05-07 | RUSH B            | W   | 0.594      | -            | -                | -                | -         |     5.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2392 | 2024-05-05 | GL Academy        | W   | 0.580      | -            | -                | -                | -         |     3.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2394 | 2024-05-04 | Enterprise        | L   | 0.575      | -            | -                | -                | -         |   -12.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2413 | 2024-05-03 | Nemiga            | L   | 0.568      | -            | -                | -                | -         |    -5.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2433 | 2024-05-02 | Endpoint          | L   | 0.562      | -            | -                | -                | -         |   -11.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2446 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.560      | -            | -                | -                | -         |     7.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2452 | 2024-05-02 | 9 Pandas          | L   | 0.559      | -            | -                | -                | -         |   -11.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2467 | 2024-05-01 | BLEED             | W   | 0.554      | -            | -                | -                | -         |     9.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2479 | 2024-04-30 | ECLOT             | W   | 0.549      | -            | -                | -                | -         |    12.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2490 | 2024-04-30 | V1dar             | W   | 0.547      | -            | -                | -                | -         |     0.96 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2502 | 2024-04-29 | Nemiga            | L   | 0.542      | -            | -                | -                | -         |    -5.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2515 | 2024-04-29 | Grannys Knockers  | W   | 0.540      | -            | -                | -                | -         |     3.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2543 | 2024-04-27 | ECLOT             | W   | 0.529      | -            | -                | -                | -         |    11.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2615 | 2024-04-25 | Insilio           | L   | 0.512      | -            | -                | -                | -         |   -10.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2626 | 2024-04-24 | PARIVISION        | L   | 0.507      | -            | -                | -                | -         |    -7.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2660 | 2024-04-22 | EYEBALLERS        | W   | 0.494      | -            | -                | -                | -         |     4.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2668 | 2024-04-22 | Nemiga            | L   | 0.493      | -            | -                | -                | -         |    -5.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2677 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.488      | -            | -                | -                | -         |     5.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2684 | 2024-04-21 | ECLOT             | L   | 0.487      | -            | -                | -                | -         |    -4.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2705 | 2024-04-20 | BLEED             | L   | 0.481      | -            | -                | -                | -         |    -8.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2803 | 2024-04-18 | Enterprise        | W   | 0.468      | -            | -                | -                | -         |     4.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2813 | 2024-04-18 | ENCE Academy      | W   | 0.467      | -            | -                | -                | -         |     2.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2862 | 2024-04-17 | JANO              | W   | 0.459      | -            | -                | -                | -         |     1.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2876 | 2024-04-16 | GamerLegion       | L   | 0.454      | -            | -                | -                | -         |    -5.86 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2901 | 2024-04-15 | Alliance          | W   | 0.446      | -            | -                | -                | -         |     3.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2941 | 2024-04-12 | Permitta          | L   | 0.427      | -            | -                | -                | -         |    -8.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3068 | 2024-04-09 | Zero Tenacity     | W   | 0.407      | -            | -                | -                | -         |     6.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3103 | 2024-04-08 | B8                | W   | 0.400      | -            | -                | -                | -         |     6.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3227 | 2024-04-03 | PARIVISION        | W   | 0.369      | -            | -                | -                | -         |     6.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3558 | 2024-03-16 | Sampi             | L   | 0.246      | -            | -                | -                | -         |    -5.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3576 | 2024-03-15 | Entropiq          | W   | 0.240      | -            | -                | -                | -         |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3627 | 2024-03-13 | Permitta          | L   | 0.229      | -            | -                | -                | -         |    -4.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3645 | 2024-03-13 | Alliance          | W   | 0.227      | -            | -                | -                | -         |     1.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3672 | 2024-03-12 | AURA              | W   | 0.221      | -            | -                | -                | -         |     0.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3679 | 2024-03-12 | Sampi             | L   | 0.219      | -            | -                | -                | -         |    -4.89 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3699 | 2024-03-11 | Passion UA        | W   | 0.214      | -            | -                | -                | -         |     3.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3701 | 2024-03-11 | NOM               | W   | 0.213      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3707 | 2024-03-10 | V1dar             | W   | 0.209      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3719 | 2024-03-10 | Passion UA        | L   | 0.207      | -            | -                | -                | -         |    -2.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3723 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.206      | -            | -                | -                | -         |     2.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3760 | 2024-03-08 | Fraud5            | W   | 0.195      | -            | -                | -                | -         |     0.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3777 | 2024-03-07 | INGLORIOUS        | L   | 0.189      | -            | -                | -                | -         |    -5.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3911 | 2024-03-03 | ex-Preasy         | W   | 0.159      | -            | -                | -                | -         |     0.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3924 | 2024-03-02 | kONO              | W   | 0.154      | -            | -                | -                | -         |     1.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3994 | 2024-02-27 | ECLOT             | L   | 0.127      | -            | -                | -                | -         |    -1.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     4009 | 2024-02-26 | BLEED             | W   | 0.121      | -            | -                | -                | -         |     1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4072 | 2024-02-24 | Sashi             | W   | 0.106      | -            | -                | -                | -         |     2.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4134 | 2024-02-21 | Entropiq          | W   | 0.086      | -            | -                | -                | -         |     0.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,428.96)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.768 | $5,000.00      | $3,838.89       |
| 2024-05-26 |      0.721 | $10,000.00     | $7,213.89       |
| 2024-05-18 |      0.668 | $500.00        | $334.17         |
| 2024-05-12 |      0.628 | $5,000.00      | $3,141.32       |
| 2024-05-03 |      0.568 | $25,000.00     | $14,194.44      |
| 2024-03-18 |      0.259 | $1,000.00      | $259.44         |
| 2024-03-11 |      0.214 | $3,500.00      | $747.64         |
| 2024-02-28 |      0.133 | $1,500.00      | $199.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
