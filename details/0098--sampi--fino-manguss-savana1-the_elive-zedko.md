### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  854.5<br />
<br />
Final Rank Value (854.5) = Starting Rank Value (885.8) + Head To Head Adjustments (-31.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.8
- 400 + ( ( 0.238 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 885.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |       86 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |       95 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      125 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      142 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      181 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      192 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      220 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      240 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.364 (0.158)    | 0 (0.000) |    12.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      287 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    12.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      300 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      370 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      401 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.364 (0.158)    | 0 (0.000) |    13.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      440 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      452 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      528 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      576 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -16.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      702 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.502 (0.218)    | 0 (0.000) |    15.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      713 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      767 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.90 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      771 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.77 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      832 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.45 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      871 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.95 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1073 | 2024-06-13 | Rebels            | W   | 0.855      | 0.379        | 0.038 (0.012)    | 0.599 (0.194)    | -         |    18.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1080 | 2024-06-13 | Sashi             | L   | 0.854      | -            | -                | -                | -         |    -3.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1104 | 2024-06-12 | Enterprise        | L   | 0.848      | -            | -                | -                | -         |   -11.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1123 | 2024-06-11 | Astralis Talent   | W   | 0.841      | -            | -                | -                | -         |     8.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1133 | 2024-06-11 | Illuminar         | L   | 0.840      | -            | -                | -                | -         |   -12.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1193 | 2024-06-09 | Aurora Young Blud | L   | 0.828      | -            | -                | -                | -         |   -15.18 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1262 | 2024-06-08 | MOUZ NXT          | L   | 0.821      | -            | -                | -                | -         |    -6.57 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1281 | 2024-06-08 | CYBERSHOKE        | L   | 0.820      | -            | -                | -                | -         |   -14.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1383 | 2024-06-06 | Nemiga            | L   | 0.808      | -            | -                | -                | -         |    -6.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1399 | 2024-06-06 | HAVU              | W   | 0.807      | -            | -                | -                | -         |     6.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1442 | 2024-06-05 | NAVI Junior       | W   | 0.801      | -            | -                | -                | -         |     3.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1479 | 2024-06-04 | INFINITE          | W   | 0.796      | -            | -                | -                | -         |     3.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1499 | 2024-06-04 | DMS               | W   | 0.793      | 0.500        | -                | 0.446 (0.177)    | -         |    14.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1523 | 2024-06-03 | Rare Atom         | W   | 0.786      | 0.435        | -                | 0.480 (0.164)    | -         |     6.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1574 | 2024-06-01 | SINNERS           | L   | 0.774      | -            | -                | -                | -         |    -7.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1595 | 2024-05-31 | ECLOT             | L   | 0.769      | -            | -                | -                | -         |    -5.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1619 | 2024-05-30 | 3DMAX             | L   | 0.762      | -            | -                | -                | -         |    -0.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1672 | 2024-05-28 | Enterprise        | L   | 0.748      | -            | -                | -                | -         |   -11.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1675 | 2024-05-28 | Rhyno             | W   | 0.747      | 0.435        | 0.071 (0.023)    | -                | -         |    14.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1710 | 2024-05-26 | SINNERS           | L   | 0.735      | -            | -                | -                | -         |    -7.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1728 | 2024-05-25 | Passion UA        | L   | 0.728      | -            | -                | -                | -         |    -7.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1759 | 2024-05-23 | GUN5              | W   | 0.716      | 0.435        | 0.073 (0.023)    | 0.570 (0.177)    | -         |    12.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1794 | 2024-05-22 | VENI VIDI VICI    | W   | 0.709      | -            | -                | -                | -         |     1.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1883 | 2024-05-20 | Illuminar         | W   | 0.695      | -            | -                | -                | -         |    11.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1891 | 2024-05-20 | Verdant           | L   | 0.693      | -            | -                | -                | -         |   -10.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1946 | 2024-05-18 | DMS               | L   | 0.680      | -            | -                | -                | -         |   -10.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2009 | 2024-05-16 | MOUZ NXT          | L   | 0.668      | -            | -                | -                | -         |    -7.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2017 | 2024-05-16 | B8                | L   | 0.667      | -            | -                | -                | -         |    -5.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2145 | 2024-05-13 | Nexus             | W   | 0.647      | -            | -                | -                | -         |     7.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2233 | 2024-05-09 | BLEED             | L   | 0.622      | -            | -                | -                | -         |    -6.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2310 | 2024-05-05 | RUSH B            | W   | 0.595      | -            | -                | -                | -         |     7.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2339 | 2024-05-04 | Endpoint          | L   | 0.586      | -            | -                | -                | -         |    -8.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2371 | 2024-05-02 | Permitta          | W   | 0.575      | 0.435        | -                | 0.876 (0.219)    | -         |     9.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2398 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.567      | -            | -                | -                | -         |    -7.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2405 | 2024-05-01 | ENCE Academy      | W   | 0.567      | -            | -                | -                | -         |     4.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2410 | 2024-04-30 | GL Academy        | W   | 0.563      | -            | -                | -                | -         |     5.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2428 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.560      | -            | -                | -                | -         |    -7.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2546 | 2024-04-25 | ECLOT             | L   | 0.526      | -            | -                | -                | -         |    -2.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2565 | 2024-04-24 | Permitta          | W   | 0.519      | 0.371        | -                | 0.876 (0.169)    | -         |     9.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2584 | 2024-04-23 | ECLOT             | L   | 0.513      | -            | -                | -                | -         |    -2.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2620 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.499      | -            | -                | -                | -         |     8.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2694 | 2024-04-19 | BLEED             | L   | 0.487      | -            | -                | -                | -         |    -5.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2753 | 2024-04-18 | Permitta          | W   | 0.479      | -            | -                | -                | -         |     8.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2775 | 2024-04-17 | NOM               | L   | 0.474      | -            | -                | -                | -         |   -13.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2813 | 2024-04-16 | SAW               | W   | 0.467      | 0.384        | 0.105 (0.019)    | -                | -         |    11.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2817 | 2024-04-16 | Secret            | W   | 0.466      | -            | -                | -                | -         |     1.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2827 | 2024-04-15 | ENCE Academy      | L   | 0.461      | -            | -                | -                | -         |   -10.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2862 | 2024-04-13 | BetBoom           | L   | 0.447      | -            | -                | -                | -         |    -0.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2906 | 2024-04-11 | PGE Turow         | W   | 0.433      | -            | -                | -                | -         |     2.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3079 | 2024-04-06 | Enterprise        | W   | 0.400      | -            | -                | -                | -         |     6.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3185 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.380      | 0.384        | 0.222 (0.032)    | -                | -         |    11.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3307 | 2024-03-27 | B8                | L   | 0.336      | -            | -                | -                | -         |    -2.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3448 | 2024-03-18 | ex-Preasy         | L   | 0.273      | -            | -                | -                | -         |    -5.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3479 | 2024-03-17 | Passion UA        | W   | 0.266      | 0.371        | 0.172 (0.017)    | -                | -         |     6.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3487 | 2024-03-16 | SINNERS           | L   | 0.261      | -            | -                | -                | -         |    -2.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3490 | 2024-03-16 | MOUZ NXT          | W   | 0.260      | 0.371        | 0.139 (0.013)    | -                | -         |     5.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3505 | 2024-03-15 | ECLOT             | L   | 0.254      | -            | -                | -                | -         |    -1.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3511 | 2024-03-15 | Permitta          | W   | 0.253      | -            | -                | -                | -         |     4.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3541 | 2024-03-14 | Passion UA        | L   | 0.247      | -            | -                | -                | -         |    -2.11 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3611 | 2024-03-12 | MOUZ NXT          | W   | 0.233      | -            | -                | -                | -         |     5.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3653 | 2024-03-10 | Sashi             | W   | 0.220      | 0.358        | 0.184 (0.015)    | -                | -         |     5.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3679 | 2024-03-09 | Enterprise        | W   | 0.214      | -            | -                | -                | -         |     3.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3764 | 2024-03-06 | AURA              | W   | 0.193      | -            | -                | -                | -         |     0.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3810 | 2024-03-04 | Sangal            | L   | 0.180      | -            | -                | -                | -         |    -1.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3864 | 2024-03-02 | Enterprise        | L   | 0.166      | -            | -                | -                | -         |    -2.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3902 | 2024-02-28 | Sashi             | L   | 0.148      | -            | -                | -                | -         |    -0.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     3967 | 2024-02-25 | ECLOT             | L   | 0.126      | -            | -                | -                | -         |    -0.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4013 | 2024-02-23 | Entropiq          | W   | 0.113      | -            | -                | -                | -         |     0.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4055 | 2024-02-21 | Sashi             | L   | 0.101      | -            | -                | -                | -         |    -0.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4159 | 2024-02-17 | Secret            | W   | 0.074      | -            | -                | -                | -         |     0.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4306 | 2024-02-10 | Zero Tenacity     | W   | 0.029      | -            | -                | -                | -         |     0.69 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,883.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.856 | $3,268.00      | $2,796.56       |
| 2024-06-02 |      0.782 | $653.00        | $510.40         |
| 2024-05-18 |      0.682 | $1,000.00      | $681.94         |
| 2024-04-25 |      0.526 | $5,000.00      | $2,630.56       |
| 2024-04-14 |      0.454 | $1,600.00      | $726.67         |
| 2024-03-18 |      0.273 | $5,000.00      | $1,365.28       |
| 2024-03-17 |      0.269 | $639.00        | $171.73         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
