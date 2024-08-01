### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1120.2<br />
<br />
Final Rank Value (1120.2) = Starting Rank Value (1065.0) + Head To Head Adjustments (55.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.540[<sup>1</sup>](#table2)
- Bounty Collected: 0.465[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.323<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1065.0
- 400 + ( ( 0.323 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1065.0


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
|           97 |      119 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           96 |      123 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           95 |      178 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           94 |      253 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           93 |      375 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           92 |      416 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.128 (0.064)    | 0.513 (0.256)    | 0 (0.000) |    24.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           91 |      431 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.072 (0.036)    | 0.403 (0.202)    | 0 (0.000) |    12.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           90 |      488 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -3.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           89 |      631 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.072 (0.036)    | -                | 0 (0.000) |    12.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |     1007 | 2024-06-13 | B8                | L   | 0.872      | -            | -                | -                | -         |   -12.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |     1070 | 2024-06-10 | Endpoint          | L   | 0.854      | -            | -                | -                | -         |   -20.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |     1106 | 2024-06-09 | GhoulsW           | W   | 0.848      | -            | -                | -                | 0 (0.000) |     1.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |     1125 | 2024-06-09 | BLEED             | L   | 0.847      | -            | -                | -                | -         |    -4.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |     1184 | 2024-06-08 | Sampi             | W   | 0.841      | 0.435        | -                | 1.000 (0.365)    | 0 (0.000) |     6.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |     1197 | 2024-06-08 | ECLOT             | L   | 0.840      | -            | -                | -                | -         |   -14.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |     1231 | 2024-06-07 | GamerLegion       | L   | 0.835      | -            | -                | -                | -         |   -10.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |     1298 | 2024-06-06 | Rhyno             | W   | 0.828      | -            | -                | -                | 0 (0.000) |     8.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1328 | 2024-06-06 | Entropiq          | W   | 0.827      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1366 | 2024-06-05 | Passion UA        | W   | 0.821      | 0.435        | 0.172 (0.062)    | 1.000 (0.357)    | -         |    10.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1428 | 2024-06-04 | NAVI Junior       | W   | 0.813      | -            | -                | -                | -         |     1.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1435 | 2024-06-04 | Aurora Young Blud | W   | 0.812      | -            | -                | -                | -         |     4.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1474 | 2024-06-02 | FURIA             | L   | 0.800      | -            | -                | -                | -         |    -1.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1508 | 2024-06-01 | AMKAL             | W   | 0.793      | 0.435        | 0.132 (0.045)    | -                | -         |    15.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1567 | 2024-05-30 | Sangal            | W   | 0.779      | 0.435        | 0.221 (0.075)    | 0.823 (0.279)    | -         |    13.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1608 | 2024-05-28 | RUBY              | W   | 0.767      | -            | -                | -                | -         |     8.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1636 | 2024-05-27 | Nexus             | W   | 0.759      | -            | -                | -                | -         |     4.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1645 | 2024-05-26 | 9 Pandas          | L   | 0.754      | -            | -                | -                | -         |   -11.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1653 | 2024-05-26 | B8                | W   | 0.753      | 0.435        | 0.168 (0.055)    | 0.878 (0.287)    | -         |    15.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1678 | 2024-05-25 | 3DMAX             | W   | 0.746      | 0.435        | 0.505 (0.164)    | 1.000 (0.324)    | -         |    22.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1691 | 2024-05-24 | Illuminar         | W   | 0.739      | -            | -                | -                | -         |     7.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1704 | 2024-05-23 | Rare Atom         | W   | 0.733      | -            | -                | -                | -         |     2.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1754 | 2024-05-22 | Rhyno             | L   | 0.727      | -            | -                | -                | -         |   -12.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1801 | 2024-05-21 | DMS               | L   | 0.720      | -            | -                | -                | -         |   -15.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1880 | 2024-05-19 | BLEED             | L   | 0.706      | -            | -                | -                | -         |    -2.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1905 | 2024-05-18 | B8                | W   | 0.700      | 0.435        | 0.168 (0.051)    | 0.878 (0.267)    | -         |    13.63 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           62 |     1947 | 2024-05-17 | DMS               | W   | 0.693      | -            | -                | -                | -         |     7.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1972 | 2024-05-16 | Sampi             | W   | 0.687      | 0.435        | -                | 1.000 (0.299)    | -         |     7.48 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           60 |     2039 | 2024-05-15 | BLEED             | L   | 0.679      | -            | -                | -                | -         |    -2.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     2095 | 2024-05-14 | B8                | L   | 0.673      | -            | -                | -                | -         |    -8.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     2121 | 2024-05-13 | Space             | W   | 0.666      | -            | -                | -                | -         |     5.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     2143 | 2024-05-12 | B8                | L   | 0.659      | -            | -                | -                | -         |    -9.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2157 | 2024-05-11 | Endpoint          | W   | 0.655      | -            | -                | -                | -         |     8.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2183 | 2024-05-10 | Aurora            | W   | 0.648      | 0.435        | 0.432 (0.122)    | 0.798 (0.225)    | -         |    19.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           54 |     2255 | 2024-05-07 | RUSH B            | W   | 0.627      | -            | -                | -                | -         |     5.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2298 | 2024-05-05 | GL Academy        | W   | 0.613      | -            | -                | -                | -         |     3.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2300 | 2024-05-04 | Enterprise        | L   | 0.608      | -            | -                | -                | -         |   -13.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2319 | 2024-05-03 | Nemiga            | L   | 0.601      | -            | -                | -                | -         |    -5.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2339 | 2024-05-02 | Endpoint          | L   | 0.595      | -            | -                | -                | -         |   -11.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2341 | 2024-05-02 | 500               | L   | 0.595      | -            | -                | -                | -         |   -15.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2353 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.593      | -            | -                | -                | -         |     7.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2359 | 2024-05-02 | 9 Pandas          | L   | 0.592      | -            | -                | -                | -         |   -11.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2360 | 2024-05-01 | Soda              | L   | 0.589      | -            | -                | -                | -         |   -17.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2375 | 2024-05-01 | BLEED             | W   | 0.587      | -            | -                | -                | -         |     9.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2388 | 2024-04-30 | ECLOT             | W   | 0.582      | -            | -                | -                | -         |    10.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2399 | 2024-04-30 | V1dar             | W   | 0.580      | -            | -                | -                | -         |     0.98 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           42 |     2411 | 2024-04-29 | Nemiga            | L   | 0.575      | -            | -                | -                | -         |    -6.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2424 | 2024-04-29 | Grannys Knockers  | W   | 0.573      | -            | -                | -                | -         |     3.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2452 | 2024-04-27 | ECLOT             | W   | 0.562      | -            | -                | -                | -         |    10.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2462 | 2024-04-27 | Permitta          | W   | 0.560      | -            | -                | -                | -         |     6.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           38 |     2524 | 2024-04-25 | Insilio           | L   | 0.546      | -            | -                | -                | -         |   -11.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2535 | 2024-04-24 | PARIVISION        | L   | 0.541      | -            | -                | -                | -         |    -8.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2547 | 2024-04-23 | BLEED             | W   | 0.536      | -            | -                | -                | -         |     8.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2572 | 2024-04-22 | EYEBALLERS        | W   | 0.527      | -            | -                | -                | -         |     4.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2580 | 2024-04-22 | Nemiga            | L   | 0.526      | -            | -                | -                | -         |    -5.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2582 | 2024-04-22 | Permitta          | L   | 0.526      | -            | -                | -                | -         |   -10.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2590 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.521      | -            | -                | -                | -         |     5.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2597 | 2024-04-21 | ECLOT             | L   | 0.520      | -            | -                | -                | -         |    -7.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2620 | 2024-04-20 | BLEED             | L   | 0.514      | -            | -                | -                | -         |    -8.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2720 | 2024-04-18 | Enterprise        | W   | 0.501      | -            | -                | -                | -         |     4.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2730 | 2024-04-18 | ENCE Academy      | W   | 0.500      | -            | -                | -                | -         |     2.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2780 | 2024-04-17 | JANO              | W   | 0.492      | -            | -                | -                | -         |     1.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2795 | 2024-04-16 | GamerLegion       | L   | 0.487      | -            | -                | -                | -         |    -6.33 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           25 |     2820 | 2024-04-15 | Alliance          | W   | 0.479      | -            | -                | -                | -         |     3.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           24 |     2861 | 2024-04-12 | Permitta          | L   | 0.460      | -            | -                | -                | -         |    -9.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2988 | 2024-04-09 | Zero Tenacity     | W   | 0.441      | -            | -                | -                | -         |     7.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3023 | 2024-04-08 | B8                | W   | 0.433      | -            | -                | -                | -         |     7.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3149 | 2024-04-03 | PARIVISION        | W   | 0.402      | -            | -                | -                | -         |     7.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3491 | 2024-03-16 | Sampi             | L   | 0.279      | -            | -                | -                | -         |    -6.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3509 | 2024-03-15 | Entropiq          | W   | 0.273      | -            | -                | -                | -         |     0.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3565 | 2024-03-13 | Permitta          | L   | 0.262      | -            | -                | -                | -         |    -5.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3582 | 2024-03-13 | Alliance          | W   | 0.260      | -            | -                | -                | -         |     2.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3610 | 2024-03-12 | AURA              | W   | 0.254      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3617 | 2024-03-12 | Sampi             | L   | 0.253      | -            | -                | -                | -         |    -5.69 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           14 |     3637 | 2024-03-11 | Passion UA        | W   | 0.247      | -            | -                | -                | -         |     4.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           13 |     3639 | 2024-03-11 | NOM               | W   | 0.246      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3645 | 2024-03-10 | V1dar             | W   | 0.242      | -            | -                | -                | -         |     0.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3657 | 2024-03-10 | Passion UA        | L   | 0.240      | -            | -                | -                | -         |    -3.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3661 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.239      | -            | -                | -                | -         |     3.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3699 | 2024-03-08 | Fraud5            | W   | 0.228      | -            | -                | -                | -         |     0.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3716 | 2024-03-07 | INGLORIOUS        | L   | 0.222      | -            | -                | -                | -         |    -6.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3855 | 2024-03-03 | ex-Preasy         | W   | 0.193      | -            | -                | -                | -         |     1.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3868 | 2024-03-02 | kONO              | W   | 0.187      | -            | -                | -                | -         |     1.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3940 | 2024-02-27 | ECLOT             | L   | 0.160      | -            | -                | -                | -         |    -2.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3955 | 2024-02-26 | BLEED             | W   | 0.154      | -            | -                | -                | -         |     1.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3957 | 2024-02-26 | Permitta          | L   | 0.153      | -            | -                | -                | -         |    -3.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4022 | 2024-02-24 | Sashi             | W   | 0.139      | -            | -                | -                | -         |     2.82 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4088 | 2024-02-21 | Entropiq          | W   | 0.119      | -            | -                | -                | -         |     0.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,131.32)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.801 | $5,000.00      | $4,004.17       |
| 2024-05-26 |      0.754 | $10,000.00     | $7,544.44       |
| 2024-05-18 |      0.701 | $500.00        | $350.69         |
| 2024-05-12 |      0.661 | $5,000.00      | $3,306.60       |
| 2024-05-03 |      0.601 | $25,000.00     | $15,020.83      |
| 2024-03-18 |      0.292 | $1,000.00      | $292.50         |
| 2024-03-11 |      0.247 | $3,500.00      | $863.33         |
| 2024-02-28 |      0.166 | $1,500.00      | $248.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
