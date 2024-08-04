### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1099.0<br />
<br />
Final Rank Value (1099.0) = Starting Rank Value (1042.3) + Head To Head Adjustments (56.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.263[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1042.3
- 400 + ( ( 0.314 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1042.3


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
|           90 |       34 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.29 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      239 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      242 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      298 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      373 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.460 (0.200)    | 0 (0.000) |     8.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      493 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      533 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.517 (0.259)    | 0 (0.000) |    24.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      547 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    11.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      597 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      739 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    12.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1121 | 2024-06-13 | B8                | L   | 0.851      | -            | -                | -                | -         |   -11.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1182 | 2024-06-10 | Endpoint          | L   | 0.832      | -            | -                | -                | -         |   -20.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1218 | 2024-06-09 | GhoulsW           | W   | 0.827      | -            | -                | -                | 0 (0.000) |     0.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1237 | 2024-06-09 | BLEED             | L   | 0.825      | -            | -                | -                | -         |    -4.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1294 | 2024-06-08 | Sampi             | W   | 0.820      | 0.435        | -                | 1.000 (0.356)    | 0 (0.000) |     6.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1306 | 2024-06-08 | ECLOT             | L   | 0.819      | -            | -                | -                | -         |   -11.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1334 | 2024-06-07 | GamerLegion       | L   | 0.814      | -            | -                | -                | -         |   -10.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1399 | 2024-06-06 | Rhyno             | W   | 0.807      | 0.500        | 0.071 (0.029)    | -                | 0 (0.000) |     8.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1428 | 2024-06-06 | Entropiq          | W   | 0.805      | -            | -                | -                | 0 (0.000) |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1526 | 2024-06-04 | NAVI Junior       | W   | 0.792      | -            | -                | -                | -         |     1.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1533 | 2024-06-04 | Aurora Young Blud | W   | 0.791      | -            | -                | -                | -         |     4.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1571 | 2024-06-02 | FURIA             | L   | 0.779      | -            | -                | -                | -         |    -1.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1605 | 2024-06-01 | AMKAL             | W   | 0.772      | 0.435        | 0.130 (0.044)    | -                | -         |    15.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1664 | 2024-05-30 | Sangal            | W   | 0.758      | 0.435        | 0.219 (0.072)    | 0.861 (0.284)    | -         |    13.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1705 | 2024-05-28 | RUBY              | W   | 0.746      | 0.435        | 0.095 (0.031)    | -                | -         |     7.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1732 | 2024-05-27 | Nexus             | W   | 0.738      | -            | -                | -                | -         |     4.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1740 | 2024-05-26 | 9 Pandas          | L   | 0.733      | -            | -                | -                | -         |   -11.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1748 | 2024-05-26 | B8                | W   | 0.732      | 0.435        | 0.165 (0.052)    | 0.951 (0.302)    | -         |    15.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1773 | 2024-05-25 | 3DMAX             | W   | 0.724      | 0.435        | 0.506 (0.159)    | 1.000 (0.315)    | -         |    21.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1786 | 2024-05-24 | Illuminar         | W   | 0.718      | -            | -                | -                | -         |     6.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1799 | 2024-05-23 | Rare Atom         | W   | 0.712      | -            | -                | -                | -         |     3.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1839 | 2024-05-22 | Rhyno             | L   | 0.705      | -            | -                | -                | -         |   -12.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1881 | 2024-05-21 | DMS               | L   | 0.699      | -            | -                | -                | -         |   -14.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1950 | 2024-05-19 | BLEED             | L   | 0.685      | -            | -                | -                | -         |    -3.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2016 | 2024-05-17 | DMS               | W   | 0.671      | -            | -                | -                | -         |     6.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2041 | 2024-05-16 | Sampi             | W   | 0.666      | 0.435        | -                | 1.000 (0.290)    | -         |     6.96 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2104 | 2024-05-15 | BLEED             | L   | 0.658      | -            | -                | -                | -         |    -2.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2157 | 2024-05-14 | B8                | L   | 0.652      | -            | -                | -                | -         |    -8.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2181 | 2024-05-13 | Space             | W   | 0.644      | -            | -                | -                | -         |     4.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2203 | 2024-05-12 | B8                | L   | 0.638      | -            | -                | -                | -         |    -9.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2217 | 2024-05-11 | Endpoint          | W   | 0.634      | -            | -                | -                | -         |     7.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2243 | 2024-05-10 | Aurora            | W   | 0.627      | 0.435        | 0.423 (0.115)    | 0.793 (0.216)    | -         |    18.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2313 | 2024-05-07 | RUSH B            | W   | 0.606      | -            | -                | -                | -         |     5.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2356 | 2024-05-05 | GL Academy        | W   | 0.592      | -            | -                | -                | -         |     3.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2358 | 2024-05-04 | Enterprise        | L   | 0.587      | -            | -                | -                | -         |   -12.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2377 | 2024-05-03 | Nemiga            | L   | 0.580      | -            | -                | -                | -         |    -5.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2397 | 2024-05-02 | Endpoint          | L   | 0.574      | -            | -                | -                | -         |   -12.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2410 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.572      | -            | -                | -                | -         |     7.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2416 | 2024-05-02 | 9 Pandas          | L   | 0.571      | -            | -                | -                | -         |   -11.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2431 | 2024-05-01 | BLEED             | W   | 0.565      | -            | -                | -                | -         |     9.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2443 | 2024-04-30 | ECLOT             | W   | 0.560      | -            | -                | -                | -         |    12.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2454 | 2024-04-30 | V1dar             | W   | 0.559      | -            | -                | -                | -         |     1.00 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2466 | 2024-04-29 | Nemiga            | L   | 0.554      | -            | -                | -                | -         |    -5.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2479 | 2024-04-29 | Grannys Knockers  | W   | 0.552      | -            | -                | -                | -         |     3.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2507 | 2024-04-27 | ECLOT             | W   | 0.540      | -            | -                | -                | -         |    12.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2579 | 2024-04-25 | Insilio           | L   | 0.524      | -            | -                | -                | -         |   -10.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2590 | 2024-04-24 | PARIVISION        | L   | 0.519      | -            | -                | -                | -         |    -7.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2624 | 2024-04-22 | EYEBALLERS        | W   | 0.506      | -            | -                | -                | -         |     4.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2632 | 2024-04-22 | Nemiga            | L   | 0.505      | -            | -                | -                | -         |    -5.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2641 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.500      | -            | -                | -                | -         |     5.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2648 | 2024-04-21 | ECLOT             | L   | 0.498      | -            | -                | -                | -         |    -4.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2669 | 2024-04-20 | BLEED             | L   | 0.493      | -            | -                | -                | -         |    -8.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2767 | 2024-04-18 | Enterprise        | W   | 0.480      | -            | -                | -                | -         |     4.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2777 | 2024-04-18 | ENCE Academy      | W   | 0.478      | -            | -                | -                | -         |     2.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2826 | 2024-04-17 | JANO              | W   | 0.471      | -            | -                | -                | -         |     1.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2840 | 2024-04-16 | GamerLegion       | L   | 0.466      | -            | -                | -                | -         |    -5.90 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2865 | 2024-04-15 | Alliance          | W   | 0.458      | -            | -                | -                | -         |     3.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2905 | 2024-04-12 | Permitta          | L   | 0.438      | -            | -                | -                | -         |    -8.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3032 | 2024-04-09 | Zero Tenacity     | W   | 0.419      | -            | -                | -                | -         |     7.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3067 | 2024-04-08 | B8                | W   | 0.412      | -            | -                | -                | -         |     7.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3191 | 2024-04-03 | PARIVISION        | W   | 0.381      | -            | -                | -                | -         |     7.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3522 | 2024-03-16 | Sampi             | L   | 0.258      | -            | -                | -                | -         |    -5.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3540 | 2024-03-15 | Entropiq          | W   | 0.252      | -            | -                | -                | -         |     0.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3591 | 2024-03-13 | Permitta          | L   | 0.241      | -            | -                | -                | -         |    -4.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3609 | 2024-03-13 | Alliance          | W   | 0.239      | -            | -                | -                | -         |     2.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3636 | 2024-03-12 | AURA              | W   | 0.233      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3643 | 2024-03-12 | Sampi             | L   | 0.231      | -            | -                | -                | -         |    -5.12 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3663 | 2024-03-11 | Passion UA        | W   | 0.225      | -            | -                | -                | -         |     3.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3665 | 2024-03-11 | NOM               | W   | 0.225      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3671 | 2024-03-10 | V1dar             | W   | 0.221      | -            | -                | -                | -         |     0.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3683 | 2024-03-10 | Passion UA        | L   | 0.219      | -            | -                | -                | -         |    -3.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3687 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.218      | -            | -                | -                | -         |     2.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3724 | 2024-03-08 | Fraud5            | W   | 0.206      | -            | -                | -                | -         |     0.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3741 | 2024-03-07 | INGLORIOUS        | L   | 0.201      | -            | -                | -                | -         |    -5.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3875 | 2024-03-03 | ex-Preasy         | W   | 0.171      | -            | -                | -                | -         |     1.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3888 | 2024-03-02 | kONO              | W   | 0.166      | -            | -                | -                | -         |     1.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3958 | 2024-02-27 | ECLOT             | L   | 0.139      | -            | -                | -                | -         |    -1.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3973 | 2024-02-26 | BLEED             | W   | 0.132      | -            | -                | -                | -         |     1.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4036 | 2024-02-24 | Sashi             | W   | 0.118      | -            | -                | -                | -         |     2.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4098 | 2024-02-21 | Entropiq          | W   | 0.098      | -            | -                | -                | -         |     0.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,038.14)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.780 | $5,000.00      | $3,898.03       |
| 2024-05-26 |      0.733 | $10,000.00     | $7,332.18       |
| 2024-05-18 |      0.680 | $500.00        | $340.08         |
| 2024-05-12 |      0.640 | $5,000.00      | $3,200.46       |
| 2024-05-03 |      0.580 | $25,000.00     | $14,490.16      |
| 2024-03-18 |      0.271 | $1,000.00      | $271.27         |
| 2024-03-11 |      0.225 | $3,500.00      | $789.04         |
| 2024-02-28 |      0.145 | $1,500.00      | $216.91         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
