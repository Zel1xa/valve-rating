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
Final Rank Value (1098.8) = Starting Rank Value (1041.7) + Head To Head Adjustments (57.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1041.7
- 400 + ( ( 0.314 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1041.7


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
|           90 |       33 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.28 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      238 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      241 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      297 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      372 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.459 (0.200)    | 0 (0.000) |     8.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      492 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      532 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.517 (0.259)    | 0 (0.000) |    24.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      546 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    11.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      596 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      738 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.404 (0.202)    | 0 (0.000) |    12.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1120 | 2024-06-13 | B8                | L   | 0.851      | -            | -                | -                | -         |   -11.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1181 | 2024-06-10 | Endpoint          | L   | 0.833      | -            | -                | -                | -         |   -20.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1217 | 2024-06-09 | GhoulsW           | W   | 0.827      | -            | -                | -                | 0 (0.000) |     0.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1236 | 2024-06-09 | BLEED             | L   | 0.826      | -            | -                | -                | -         |    -4.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1293 | 2024-06-08 | Sampi             | W   | 0.820      | 0.435        | -                | 1.000 (0.356)    | 0 (0.000) |     6.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1305 | 2024-06-08 | ECLOT             | L   | 0.819      | -            | -                | -                | -         |   -11.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1333 | 2024-06-07 | GamerLegion       | L   | 0.814      | -            | -                | -                | -         |   -10.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1398 | 2024-06-06 | Rhyno             | W   | 0.807      | 0.500        | 0.071 (0.029)    | -                | 0 (0.000) |     8.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1427 | 2024-06-06 | Entropiq          | W   | 0.806      | -            | -                | -                | 0 (0.000) |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1525 | 2024-06-04 | NAVI Junior       | W   | 0.792      | -            | -                | -                | -         |     1.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1532 | 2024-06-04 | Aurora Young Blud | W   | 0.791      | -            | -                | -                | -         |     4.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1570 | 2024-06-02 | FURIA             | L   | 0.779      | -            | -                | -                | -         |    -1.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1604 | 2024-06-01 | AMKAL             | W   | 0.772      | 0.435        | 0.130 (0.044)    | -                | -         |    15.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1663 | 2024-05-30 | Sangal            | W   | 0.758      | 0.435        | 0.219 (0.072)    | 0.861 (0.284)    | -         |    13.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1704 | 2024-05-28 | RUBY              | W   | 0.747      | 0.435        | 0.095 (0.031)    | -                | -         |     7.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1731 | 2024-05-27 | Nexus             | W   | 0.738      | -            | -                | -                | -         |     4.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1739 | 2024-05-26 | 9 Pandas          | L   | 0.734      | -            | -                | -                | -         |   -11.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1747 | 2024-05-26 | B8                | W   | 0.732      | 0.435        | 0.165 (0.053)    | 0.912 (0.290)    | -         |    15.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1772 | 2024-05-25 | 3DMAX             | W   | 0.725      | 0.435        | 0.506 (0.159)    | 1.000 (0.315)    | -         |    21.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1785 | 2024-05-24 | Illuminar         | W   | 0.718      | -            | -                | -                | -         |     6.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1798 | 2024-05-23 | Rare Atom         | W   | 0.712      | -            | -                | -                | -         |     3.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1838 | 2024-05-22 | Rhyno             | L   | 0.706      | -            | -                | -                | -         |   -12.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1880 | 2024-05-21 | DMS               | L   | 0.699      | -            | -                | -                | -         |   -14.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1949 | 2024-05-19 | BLEED             | L   | 0.685      | -            | -                | -                | -         |    -3.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2015 | 2024-05-17 | DMS               | W   | 0.672      | -            | -                | -                | -         |     6.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2040 | 2024-05-16 | Sampi             | W   | 0.667      | 0.435        | -                | 1.000 (0.290)    | -         |     6.97 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2103 | 2024-05-15 | BLEED             | L   | 0.658      | -            | -                | -                | -         |    -2.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2156 | 2024-05-14 | B8                | L   | 0.652      | -            | -                | -                | -         |    -8.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2180 | 2024-05-13 | Space             | W   | 0.645      | -            | -                | -                | -         |     4.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2202 | 2024-05-12 | B8                | L   | 0.639      | -            | -                | -                | -         |    -9.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2216 | 2024-05-11 | Endpoint          | W   | 0.634      | -            | -                | -                | -         |     7.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2242 | 2024-05-10 | Aurora            | W   | 0.627      | 0.435        | 0.423 (0.115)    | 0.793 (0.216)    | -         |    18.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2312 | 2024-05-07 | RUSH B            | W   | 0.606      | -            | -                | -                | -         |     5.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2355 | 2024-05-05 | GL Academy        | W   | 0.592      | -            | -                | -                | -         |     3.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2357 | 2024-05-04 | Enterprise        | L   | 0.587      | -            | -                | -                | -         |   -12.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2376 | 2024-05-03 | Nemiga            | L   | 0.580      | -            | -                | -                | -         |    -5.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2396 | 2024-05-02 | Endpoint          | L   | 0.574      | -            | -                | -                | -         |   -12.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2409 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.572      | -            | -                | -                | -         |     7.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2415 | 2024-05-02 | 9 Pandas          | L   | 0.571      | -            | -                | -                | -         |   -11.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2430 | 2024-05-01 | BLEED             | W   | 0.566      | -            | -                | -                | -         |     9.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2442 | 2024-04-30 | ECLOT             | W   | 0.561      | -            | -                | -                | -         |    12.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2453 | 2024-04-30 | V1dar             | W   | 0.559      | -            | -                | -                | -         |     1.00 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2465 | 2024-04-29 | Nemiga            | L   | 0.554      | -            | -                | -                | -         |    -5.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2478 | 2024-04-29 | Grannys Knockers  | W   | 0.552      | -            | -                | -                | -         |     3.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2506 | 2024-04-27 | ECLOT             | W   | 0.541      | -            | -                | -                | -         |    12.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2578 | 2024-04-25 | Insilio           | L   | 0.525      | -            | -                | -                | -         |   -10.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2589 | 2024-04-24 | PARIVISION        | L   | 0.520      | -            | -                | -                | -         |    -7.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2623 | 2024-04-22 | EYEBALLERS        | W   | 0.506      | -            | -                | -                | -         |     4.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2631 | 2024-04-22 | Nemiga            | L   | 0.505      | -            | -                | -                | -         |    -5.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2640 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.500      | -            | -                | -                | -         |     5.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2647 | 2024-04-21 | ECLOT             | L   | 0.499      | -            | -                | -                | -         |    -4.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2668 | 2024-04-20 | BLEED             | L   | 0.493      | -            | -                | -                | -         |    -8.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2766 | 2024-04-18 | Enterprise        | W   | 0.480      | -            | -                | -                | -         |     5.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2776 | 2024-04-18 | ENCE Academy      | W   | 0.479      | -            | -                | -                | -         |     2.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2825 | 2024-04-17 | JANO              | W   | 0.471      | -            | -                | -                | -         |     1.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2839 | 2024-04-16 | GamerLegion       | L   | 0.466      | -            | -                | -                | -         |    -5.89 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2864 | 2024-04-15 | Alliance          | W   | 0.458      | -            | -                | -                | -         |     3.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2904 | 2024-04-12 | Permitta          | L   | 0.439      | -            | -                | -                | -         |    -8.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3031 | 2024-04-09 | Zero Tenacity     | W   | 0.420      | -            | -                | -                | -         |     7.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3066 | 2024-04-08 | B8                | W   | 0.412      | -            | -                | -                | -         |     7.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3190 | 2024-04-03 | PARIVISION        | W   | 0.381      | -            | -                | -                | -         |     7.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3521 | 2024-03-16 | Sampi             | L   | 0.258      | -            | -                | -                | -         |    -5.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3539 | 2024-03-15 | Entropiq          | W   | 0.253      | -            | -                | -                | -         |     0.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3590 | 2024-03-13 | Permitta          | L   | 0.241      | -            | -                | -                | -         |    -4.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3608 | 2024-03-13 | Alliance          | W   | 0.239      | -            | -                | -                | -         |     2.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3635 | 2024-03-12 | AURA              | W   | 0.233      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3642 | 2024-03-12 | Sampi             | L   | 0.232      | -            | -                | -                | -         |    -5.12 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3662 | 2024-03-11 | Passion UA        | W   | 0.226      | -            | -                | -                | -         |     3.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3664 | 2024-03-11 | NOM               | W   | 0.225      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3670 | 2024-03-10 | V1dar             | W   | 0.221      | -            | -                | -                | -         |     0.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3682 | 2024-03-10 | Passion UA        | L   | 0.219      | -            | -                | -                | -         |    -3.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3686 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.219      | -            | -                | -                | -         |     2.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3723 | 2024-03-08 | Fraud5            | W   | 0.207      | -            | -                | -                | -         |     0.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3740 | 2024-03-07 | INGLORIOUS        | L   | 0.201      | -            | -                | -                | -         |    -5.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3874 | 2024-03-03 | ex-Preasy         | W   | 0.172      | -            | -                | -                | -         |     1.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3887 | 2024-03-02 | kONO              | W   | 0.166      | -            | -                | -                | -         |     1.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3957 | 2024-02-27 | ECLOT             | L   | 0.139      | -            | -                | -                | -         |    -1.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3972 | 2024-02-26 | BLEED             | W   | 0.133      | -            | -                | -                | -         |     1.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4035 | 2024-02-24 | Sashi             | W   | 0.118      | -            | -                | -                | -         |     2.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4097 | 2024-02-21 | Entropiq          | W   | 0.098      | -            | -                | -                | -         |     0.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,053.63)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.780 | $5,000.00      | $3,899.54       |
| 2024-05-26 |      0.734 | $10,000.00     | $7,335.19       |
| 2024-05-18 |      0.680 | $500.00        | $340.23         |
| 2024-05-12 |      0.640 | $5,000.00      | $3,201.97       |
| 2024-05-03 |      0.580 | $25,000.00     | $14,497.69      |
| 2024-03-18 |      0.272 | $1,000.00      | $271.57         |
| 2024-03-11 |      0.226 | $3,500.00      | $790.09         |
| 2024-02-28 |      0.145 | $1,500.00      | $217.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
