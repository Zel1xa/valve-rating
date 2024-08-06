### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1104.1<br />
<br />
Final Rank Value (1104.1) = Starting Rank Value (1045.6) + Head To Head Adjustments (58.5)<br />

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
|           90 |       72 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.24 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      277 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      280 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      336 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      411 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.521 (0.227)    | 0 (0.000) |     9.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      531 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      571 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.538 (0.269)    | 0 (0.000) |    24.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      585 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    11.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      635 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      777 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    12.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1159 | 2024-06-13 | B8                | L   | 0.839      | -            | -                | -                | -         |   -11.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1220 | 2024-06-10 | Endpoint          | L   | 0.820      | -            | -                | -                | -         |   -20.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1256 | 2024-06-09 | GhoulsW           | W   | 0.814      | -            | -                | -                | 0 (0.000) |     0.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1275 | 2024-06-09 | BLEED             | L   | 0.813      | -            | -                | -                | -         |    -4.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1332 | 2024-06-08 | Sampi             | W   | 0.807      | 0.435        | -                | 1.000 (0.351)    | 0 (0.000) |     6.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1344 | 2024-06-08 | ECLOT             | L   | 0.807      | -            | -                | -                | -         |   -10.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1372 | 2024-06-07 | GamerLegion       | L   | 0.802      | -            | -                | -                | -         |   -10.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1437 | 2024-06-06 | Rhyno             | W   | 0.795      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1466 | 2024-06-06 | Entropiq          | W   | 0.793      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1564 | 2024-06-04 | NAVI Junior       | W   | 0.780      | -            | -                | -                | -         |     1.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1571 | 2024-06-04 | Aurora Young Blud | W   | 0.779      | -            | -                | -                | -         |     5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1609 | 2024-06-02 | FURIA             | L   | 0.767      | -            | -                | -                | -         |    -1.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1643 | 2024-06-01 | AMKAL             | W   | 0.760      | 0.435        | 0.130 (0.043)    | -                | -         |    15.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1702 | 2024-05-30 | Sangal            | W   | 0.746      | 0.435        | 0.219 (0.071)    | 0.846 (0.274)    | -         |    13.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1743 | 2024-05-28 | RUBY              | W   | 0.734      | 0.435        | 0.095 (0.030)    | -                | -         |     7.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1770 | 2024-05-27 | Nexus             | W   | 0.726      | -            | -                | -                | -         |     3.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1778 | 2024-05-26 | 9 Pandas          | L   | 0.721      | -            | -                | -                | -         |   -11.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1786 | 2024-05-26 | B8                | W   | 0.719      | 0.435        | 0.170 (0.053)    | 0.912 (0.285)    | -         |    14.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1811 | 2024-05-25 | 3DMAX             | W   | 0.712      | 0.435        | 0.510 (0.158)    | 1.000 (0.309)    | -         |    21.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1824 | 2024-05-24 | Illuminar         | W   | 0.706      | -            | -                | -                | -         |     6.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1837 | 2024-05-23 | Rare Atom         | W   | 0.700      | -            | -                | -                | -         |     5.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1877 | 2024-05-22 | Rhyno             | L   | 0.693      | -            | -                | -                | -         |   -12.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1919 | 2024-05-21 | DMS               | L   | 0.687      | -            | -                | -                | -         |   -14.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1988 | 2024-05-19 | BLEED             | L   | 0.672      | -            | -                | -                | -         |    -2.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2054 | 2024-05-17 | DMS               | W   | 0.659      | -            | -                | -                | -         |     6.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2079 | 2024-05-16 | Sampi             | W   | 0.654      | 0.435        | -                | 1.000 (0.284)    | -         |     6.77 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2142 | 2024-05-15 | BLEED             | L   | 0.646      | -            | -                | -                | -         |    -2.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2195 | 2024-05-14 | B8                | L   | 0.639      | -            | -                | -                | -         |    -8.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2219 | 2024-05-13 | Space             | W   | 0.632      | -            | -                | -                | -         |     4.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2241 | 2024-05-12 | B8                | L   | 0.626      | -            | -                | -                | -         |    -9.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2255 | 2024-05-11 | Endpoint          | W   | 0.622      | -            | -                | -                | -         |     6.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2281 | 2024-05-10 | Aurora            | W   | 0.615      | 0.435        | 0.420 (0.112)    | 0.759 (0.203)    | -         |    18.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2351 | 2024-05-07 | RUSH B            | W   | 0.594      | -            | -                | -                | -         |     5.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2394 | 2024-05-05 | GL Academy        | W   | 0.579      | -            | -                | -                | -         |     3.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2396 | 2024-05-04 | Enterprise        | L   | 0.575      | -            | -                | -                | -         |   -12.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2415 | 2024-05-03 | Nemiga            | L   | 0.567      | -            | -                | -                | -         |    -5.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2435 | 2024-05-02 | Endpoint          | L   | 0.562      | -            | -                | -                | -         |   -11.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2448 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.560      | -            | -                | -                | -         |     7.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2454 | 2024-05-02 | 9 Pandas          | L   | 0.559      | -            | -                | -                | -         |   -11.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2469 | 2024-05-01 | BLEED             | W   | 0.553      | -            | -                | -                | -         |     9.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2481 | 2024-04-30 | ECLOT             | W   | 0.548      | -            | -                | -                | -         |    12.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2492 | 2024-04-30 | V1dar             | W   | 0.547      | -            | -                | -                | -         |     0.96 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2504 | 2024-04-29 | Nemiga            | L   | 0.542      | -            | -                | -                | -         |    -5.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2517 | 2024-04-29 | Grannys Knockers  | W   | 0.539      | -            | -                | -                | -         |     3.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2545 | 2024-04-27 | ECLOT             | W   | 0.528      | -            | -                | -                | -         |    11.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2617 | 2024-04-25 | Insilio           | L   | 0.512      | -            | -                | -                | -         |   -10.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2628 | 2024-04-24 | PARIVISION        | L   | 0.507      | -            | -                | -                | -         |    -7.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2662 | 2024-04-22 | EYEBALLERS        | W   | 0.494      | -            | -                | -                | -         |     4.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2670 | 2024-04-22 | Nemiga            | L   | 0.492      | -            | -                | -                | -         |    -5.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2679 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.487      | -            | -                | -                | -         |     5.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2686 | 2024-04-21 | ECLOT             | L   | 0.486      | -            | -                | -                | -         |    -4.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2707 | 2024-04-20 | BLEED             | L   | 0.481      | -            | -                | -                | -         |    -8.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2805 | 2024-04-18 | Enterprise        | W   | 0.467      | -            | -                | -                | -         |     4.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2815 | 2024-04-18 | ENCE Academy      | W   | 0.466      | -            | -                | -                | -         |     2.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2864 | 2024-04-17 | JANO              | W   | 0.459      | -            | -                | -                | -         |     1.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2878 | 2024-04-16 | GamerLegion       | L   | 0.454      | -            | -                | -                | -         |    -5.85 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2903 | 2024-04-15 | Alliance          | W   | 0.446      | -            | -                | -                | -         |     3.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2943 | 2024-04-12 | Permitta          | L   | 0.426      | -            | -                | -                | -         |    -8.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3070 | 2024-04-09 | Zero Tenacity     | W   | 0.407      | -            | -                | -                | -         |     6.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3105 | 2024-04-08 | B8                | W   | 0.400      | -            | -                | -                | -         |     6.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3229 | 2024-04-03 | PARIVISION        | W   | 0.368      | -            | -                | -                | -         |     6.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3560 | 2024-03-16 | Sampi             | L   | 0.246      | -            | -                | -                | -         |    -5.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3578 | 2024-03-15 | Entropiq          | W   | 0.240      | -            | -                | -                | -         |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3629 | 2024-03-13 | Permitta          | L   | 0.229      | -            | -                | -                | -         |    -4.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3647 | 2024-03-13 | Alliance          | W   | 0.226      | -            | -                | -                | -         |     1.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3674 | 2024-03-12 | AURA              | W   | 0.221      | -            | -                | -                | -         |     0.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3681 | 2024-03-12 | Sampi             | L   | 0.219      | -            | -                | -                | -         |    -4.88 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3701 | 2024-03-11 | Passion UA        | W   | 0.213      | -            | -                | -                | -         |     3.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3703 | 2024-03-11 | NOM               | W   | 0.212      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3709 | 2024-03-10 | V1dar             | W   | 0.208      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3721 | 2024-03-10 | Passion UA        | L   | 0.207      | -            | -                | -                | -         |    -2.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3725 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.206      | -            | -                | -                | -         |     2.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3762 | 2024-03-08 | Fraud5            | W   | 0.194      | -            | -                | -                | -         |     0.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3779 | 2024-03-07 | INGLORIOUS        | L   | 0.188      | -            | -                | -                | -         |    -5.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3913 | 2024-03-03 | ex-Preasy         | W   | 0.159      | -            | -                | -                | -         |     0.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3926 | 2024-03-02 | kONO              | W   | 0.154      | -            | -                | -                | -         |     1.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3996 | 2024-02-27 | ECLOT             | L   | 0.127      | -            | -                | -                | -         |    -1.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     4011 | 2024-02-26 | BLEED             | W   | 0.120      | -            | -                | -                | -         |     1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4074 | 2024-02-24 | Sashi             | W   | 0.106      | -            | -                | -                | -         |     2.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4136 | 2024-02-21 | Entropiq          | W   | 0.086      | -            | -                | -                | -         |     0.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,409.88)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.767 | $5,000.00      | $3,837.04       |
| 2024-05-26 |      0.721 | $10,000.00     | $7,210.19       |
| 2024-05-18 |      0.668 | $500.00        | $333.98         |
| 2024-05-12 |      0.628 | $5,000.00      | $3,139.47       |
| 2024-05-03 |      0.567 | $25,000.00     | $14,185.19      |
| 2024-03-18 |      0.259 | $1,000.00      | $259.07         |
| 2024-03-11 |      0.213 | $3,500.00      | $746.34         |
| 2024-02-28 |      0.132 | $1,500.00      | $198.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
