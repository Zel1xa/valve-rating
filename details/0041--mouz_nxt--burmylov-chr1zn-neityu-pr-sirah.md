### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1120.1<br />
<br />
Final Rank Value (1120.1) = Starting Rank Value (1063.9) + Head To Head Adjustments (56.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.540[<sup>1</sup>](#table2)
- Bounty Collected: 0.465[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.323<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1063.9
- 400 + ( ( 0.323 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1063.9


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
|           97 |      125 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           96 |      128 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           95 |      184 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           94 |      259 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           93 |      381 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           92 |      422 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.128 (0.064)    | 0.513 (0.257)    | 0 (0.000) |    24.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           91 |      437 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.072 (0.036)    | 0.403 (0.202)    | 0 (0.000) |    12.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           90 |      492 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -2.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           89 |      637 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.072 (0.036)    | -                | 0 (0.000) |    12.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |     1013 | 2024-06-13 | B8                | L   | 0.871      | -            | -                | -                | -         |   -12.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |     1076 | 2024-06-10 | Endpoint          | L   | 0.852      | -            | -                | -                | -         |   -20.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |     1112 | 2024-06-09 | GhoulsW           | W   | 0.846      | -            | -                | -                | 0 (0.000) |     1.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |     1131 | 2024-06-09 | BLEED             | L   | 0.845      | -            | -                | -                | -         |    -4.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |     1190 | 2024-06-08 | Sampi             | W   | 0.839      | 0.435        | -                | 1.000 (0.365)    | 0 (0.000) |     6.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |     1203 | 2024-06-08 | ECLOT             | L   | 0.838      | -            | -                | -                | -         |   -14.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |     1237 | 2024-06-07 | GamerLegion       | L   | 0.833      | -            | -                | -                | -         |   -10.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |     1304 | 2024-06-06 | Rhyno             | W   | 0.827      | -            | -                | -                | 0 (0.000) |     8.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1334 | 2024-06-06 | Entropiq          | W   | 0.825      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1372 | 2024-06-05 | Passion UA        | W   | 0.820      | 0.435        | 0.173 (0.061)    | 1.000 (0.356)    | -         |    10.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1434 | 2024-06-04 | NAVI Junior       | W   | 0.812      | -            | -                | -                | -         |     1.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1441 | 2024-06-04 | Aurora Young Blud | W   | 0.811      | -            | -                | -                | -         |     4.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1480 | 2024-06-02 | FURIA             | L   | 0.798      | -            | -                | -                | -         |    -1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1514 | 2024-06-01 | AMKAL             | W   | 0.792      | 0.435        | 0.132 (0.045)    | -                | -         |    15.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1573 | 2024-05-30 | Sangal            | W   | 0.777      | 0.435        | 0.221 (0.075)    | 0.823 (0.278)    | -         |    13.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1614 | 2024-05-28 | RUBY              | W   | 0.766      | -            | -                | -                | -         |     8.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1642 | 2024-05-27 | Nexus             | W   | 0.757      | -            | -                | -                | -         |     4.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1651 | 2024-05-26 | 9 Pandas          | L   | 0.753      | -            | -                | -                | -         |   -11.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1659 | 2024-05-26 | B8                | W   | 0.751      | 0.435        | 0.168 (0.055)    | 0.878 (0.286)    | -         |    15.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1684 | 2024-05-25 | 3DMAX             | W   | 0.744      | 0.435        | 0.505 (0.163)    | 1.000 (0.323)    | -         |    22.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1697 | 2024-05-24 | Illuminar         | W   | 0.738      | -            | -                | -                | -         |     7.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1710 | 2024-05-23 | Rare Atom         | W   | 0.732      | -            | -                | -                | -         |     2.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1760 | 2024-05-22 | Rhyno             | L   | 0.725      | -            | -                | -                | -         |   -12.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1807 | 2024-05-21 | DMS               | L   | 0.718      | -            | -                | -                | -         |   -15.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1886 | 2024-05-19 | BLEED             | L   | 0.704      | -            | -                | -                | -         |    -2.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1911 | 2024-05-18 | B8                | W   | 0.698      | 0.435        | 0.168 (0.051)    | 0.878 (0.266)    | -         |    13.60 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           62 |     1953 | 2024-05-17 | DMS               | W   | 0.691      | -            | -                | -                | -         |     7.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1978 | 2024-05-16 | Sampi             | W   | 0.686      | 0.435        | -                | 1.000 (0.298)    | -         |     7.46 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           60 |     2045 | 2024-05-15 | BLEED             | L   | 0.677      | -            | -                | -                | -         |    -2.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     2101 | 2024-05-14 | B8                | L   | 0.671      | -            | -                | -                | -         |    -8.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     2127 | 2024-05-13 | Space             | W   | 0.664      | -            | -                | -                | -         |     5.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     2149 | 2024-05-12 | B8                | L   | 0.658      | -            | -                | -                | -         |    -9.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2163 | 2024-05-11 | Endpoint          | W   | 0.653      | -            | -                | -                | -         |     8.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2189 | 2024-05-10 | Aurora            | W   | 0.647      | 0.435        | 0.431 (0.121)    | 0.798 (0.224)    | -         |    19.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           54 |     2261 | 2024-05-07 | RUSH B            | W   | 0.625      | -            | -                | -                | -         |     5.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2304 | 2024-05-05 | GL Academy        | W   | 0.611      | -            | -                | -                | -         |     3.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2306 | 2024-05-04 | Enterprise        | L   | 0.607      | -            | -                | -                | -         |   -13.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2325 | 2024-05-03 | Nemiga            | L   | 0.599      | -            | -                | -                | -         |    -5.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2345 | 2024-05-02 | Endpoint          | L   | 0.593      | -            | -                | -                | -         |   -11.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2347 | 2024-05-02 | 500               | L   | 0.593      | -            | -                | -                | -         |   -15.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2359 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.592      | -            | -                | -                | -         |     7.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2365 | 2024-05-02 | 9 Pandas          | L   | 0.591      | -            | -                | -                | -         |   -11.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2366 | 2024-05-01 | Soda              | L   | 0.588      | -            | -                | -                | -         |   -17.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2381 | 2024-05-01 | BLEED             | W   | 0.585      | -            | -                | -                | -         |     9.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2394 | 2024-04-30 | ECLOT             | W   | 0.580      | -            | -                | -                | -         |    10.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2405 | 2024-04-30 | V1dar             | W   | 0.578      | -            | -                | -                | -         |     0.98 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           42 |     2417 | 2024-04-29 | Nemiga            | L   | 0.573      | -            | -                | -                | -         |    -6.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2430 | 2024-04-29 | Grannys Knockers  | W   | 0.571      | -            | -                | -                | -         |     3.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2458 | 2024-04-27 | ECLOT             | W   | 0.560      | -            | -                | -                | -         |    10.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2468 | 2024-04-27 | Permitta          | W   | 0.559      | -            | -                | -                | -         |     6.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           38 |     2530 | 2024-04-25 | Insilio           | L   | 0.544      | -            | -                | -                | -         |   -11.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2541 | 2024-04-24 | PARIVISION        | L   | 0.539      | -            | -                | -                | -         |    -8.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2553 | 2024-04-23 | BLEED             | W   | 0.534      | -            | -                | -                | -         |     8.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2578 | 2024-04-22 | EYEBALLERS        | W   | 0.526      | -            | -                | -                | -         |     4.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2586 | 2024-04-22 | Nemiga            | L   | 0.524      | -            | -                | -                | -         |    -5.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2588 | 2024-04-22 | Permitta          | L   | 0.524      | -            | -                | -                | -         |   -10.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2596 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.519      | -            | -                | -                | -         |     5.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2603 | 2024-04-21 | ECLOT             | L   | 0.518      | -            | -                | -                | -         |    -7.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2626 | 2024-04-20 | BLEED             | L   | 0.512      | -            | -                | -                | -         |    -8.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2726 | 2024-04-18 | Enterprise        | W   | 0.499      | -            | -                | -                | -         |     4.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2736 | 2024-04-18 | ENCE Academy      | W   | 0.498      | -            | -                | -                | -         |     2.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2786 | 2024-04-17 | JANO              | W   | 0.490      | -            | -                | -                | -         |     1.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2801 | 2024-04-16 | GamerLegion       | L   | 0.485      | -            | -                | -                | -         |    -6.29 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           25 |     2826 | 2024-04-15 | Alliance          | W   | 0.477      | -            | -                | -                | -         |     3.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           24 |     2867 | 2024-04-12 | Permitta          | L   | 0.458      | -            | -                | -                | -         |    -9.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2994 | 2024-04-09 | Zero Tenacity     | W   | 0.439      | -            | -                | -                | -         |     7.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3029 | 2024-04-08 | B8                | W   | 0.432      | -            | -                | -                | -         |     7.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3155 | 2024-04-03 | PARIVISION        | W   | 0.400      | -            | -                | -                | -         |     7.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3497 | 2024-03-16 | Sampi             | L   | 0.278      | -            | -                | -                | -         |    -6.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3515 | 2024-03-15 | Entropiq          | W   | 0.272      | -            | -                | -                | -         |     0.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3571 | 2024-03-13 | Permitta          | L   | 0.260      | -            | -                | -                | -         |    -5.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3588 | 2024-03-13 | Alliance          | W   | 0.258      | -            | -                | -                | -         |     2.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3616 | 2024-03-12 | AURA              | W   | 0.253      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3623 | 2024-03-12 | Sampi             | L   | 0.251      | -            | -                | -                | -         |    -5.65 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           14 |     3643 | 2024-03-11 | Passion UA        | W   | 0.245      | -            | -                | -                | -         |     4.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           13 |     3645 | 2024-03-11 | NOM               | W   | 0.244      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3651 | 2024-03-10 | V1dar             | W   | 0.240      | -            | -                | -                | -         |     0.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3663 | 2024-03-10 | Passion UA        | L   | 0.239      | -            | -                | -                | -         |    -3.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3667 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.238      | -            | -                | -                | -         |     3.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3705 | 2024-03-08 | Fraud5            | W   | 0.226      | -            | -                | -                | -         |     0.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3722 | 2024-03-07 | INGLORIOUS        | L   | 0.220      | -            | -                | -                | -         |    -6.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3861 | 2024-03-03 | ex-Preasy         | W   | 0.191      | -            | -                | -                | -         |     1.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3874 | 2024-03-02 | kONO              | W   | 0.185      | -            | -                | -                | -         |     1.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3946 | 2024-02-27 | ECLOT             | L   | 0.159      | -            | -                | -                | -         |    -2.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3961 | 2024-02-26 | BLEED             | W   | 0.152      | -            | -                | -                | -         |     1.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3963 | 2024-02-26 | Permitta          | L   | 0.152      | -            | -                | -                | -         |    -3.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4028 | 2024-02-24 | Sashi             | W   | 0.138      | -            | -                | -                | -         |     2.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4094 | 2024-02-21 | Entropiq          | W   | 0.117      | -            | -                | -                | -         |     0.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,045.49)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.799 | $5,000.00      | $3,995.83       |
| 2024-05-26 |      0.753 | $10,000.00     | $7,527.78       |
| 2024-05-18 |      0.700 | $500.00        | $349.86         |
| 2024-05-12 |      0.660 | $5,000.00      | $3,298.26       |
| 2024-05-03 |      0.599 | $25,000.00     | $14,979.17      |
| 2024-03-18 |      0.291 | $1,000.00      | $290.83         |
| 2024-03-11 |      0.245 | $3,500.00      | $857.50         |
| 2024-02-28 |      0.164 | $1,500.00      | $246.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
