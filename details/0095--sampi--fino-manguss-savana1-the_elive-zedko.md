### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  878.4<br />
<br />
Final Rank Value (878.4) = Starting Rank Value (885.6) + Head To Head Adjustments (-7.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.6
- 400 + ( ( 0.237 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 885.6


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
|           94 |       18 | 2024-08-05 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |      145 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      155 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      185 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      204 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      241 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      252 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      279 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      300 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.361 (0.157)    | 0 (0.000) |    13.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      348 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.514 (0.223)    | 0 (0.000) |    12.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      360 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      430 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      461 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.361 (0.157)    | 0 (0.000) |    13.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      501 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      512 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      588 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -18.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      636 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      762 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.491 (0.214)    | 0 (0.000) |    15.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      777 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      827 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.88 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      831 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | -         |     6.57 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      892 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.18 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      931 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.88 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1133 | 2024-06-13 | Rebels            | W   | 0.844      | 0.379        | 0.038 (0.012)    | 0.591 (0.189)    | -         |    17.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1140 | 2024-06-13 | Sashi             | L   | 0.843      | -            | -                | -                | -         |    -3.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1164 | 2024-06-12 | Enterprise        | L   | 0.837      | -            | -                | -                | -         |   -11.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1183 | 2024-06-11 | Astralis Talent   | W   | 0.831      | -            | -                | -                | -         |     8.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1193 | 2024-06-11 | Illuminar         | L   | 0.829      | -            | -                | -                | -         |   -12.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1253 | 2024-06-09 | Aurora Young Blud | L   | 0.817      | -            | -                | -                | -         |   -13.85 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1322 | 2024-06-08 | MOUZ NXT          | L   | 0.810      | -            | -                | -                | -         |    -6.53 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1341 | 2024-06-08 | CYBERSHOKE        | L   | 0.809      | -            | -                | -                | -         |   -14.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1443 | 2024-06-06 | Nemiga            | L   | 0.797      | -            | -                | -                | -         |    -6.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1459 | 2024-06-06 | HAVU              | W   | 0.796      | -            | -                | -                | -         |     6.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1502 | 2024-06-05 | NAVI Junior       | W   | 0.791      | -            | -                | -                | -         |     2.89 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1539 | 2024-06-04 | INFINITE          | W   | 0.785      | -            | -                | -                | -         |     2.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1559 | 2024-06-04 | DMS               | W   | 0.782      | 0.500        | -                | 0.438 (0.171)    | -         |    14.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1583 | 2024-06-03 | Rare Atom         | W   | 0.775      | 0.435        | -                | 0.474 (0.160)    | -         |     9.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1634 | 2024-06-01 | SINNERS           | L   | 0.763      | -            | -                | -                | -         |    -6.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1655 | 2024-05-31 | ECLOT             | L   | 0.758      | -            | -                | -                | -         |    -4.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1679 | 2024-05-30 | 3DMAX             | L   | 0.751      | -            | -                | -                | -         |    -0.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1732 | 2024-05-28 | Enterprise        | L   | 0.737      | -            | -                | -                | -         |   -11.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1735 | 2024-05-28 | Rhyno             | W   | 0.736      | 0.435        | 0.071 (0.023)    | -                | -         |    14.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1770 | 2024-05-26 | SINNERS           | L   | 0.724      | -            | -                | -                | -         |    -6.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1788 | 2024-05-25 | Passion UA        | L   | 0.717      | -            | -                | -                | -         |    -7.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1819 | 2024-05-23 | GUN5              | W   | 0.705      | 0.435        | 0.072 (0.022)    | 0.562 (0.172)    | -         |    12.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1854 | 2024-05-22 | VENI VIDI VICI    | W   | 0.698      | -            | -                | -                | -         |     1.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1943 | 2024-05-20 | Illuminar         | W   | 0.684      | -            | -                | -                | -         |    10.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1951 | 2024-05-20 | Verdant           | L   | 0.682      | -            | -                | -                | -         |   -10.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     2006 | 2024-05-18 | DMS               | L   | 0.669      | -            | -                | -                | -         |   -10.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2069 | 2024-05-16 | MOUZ NXT          | L   | 0.657      | -            | -                | -                | -         |    -6.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2077 | 2024-05-16 | B8                | L   | 0.656      | -            | -                | -                | -         |    -5.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2205 | 2024-05-13 | Nexus             | W   | 0.636      | -            | -                | -                | -         |     6.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2293 | 2024-05-09 | BLEED             | L   | 0.612      | -            | -                | -                | -         |    -6.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2370 | 2024-05-05 | RUSH B            | W   | 0.584      | -            | -                | -                | -         |     7.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2399 | 2024-05-04 | Endpoint          | L   | 0.576      | -            | -                | -                | -         |    -8.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2431 | 2024-05-02 | Permitta          | W   | 0.564      | 0.435        | -                | 0.901 (0.221)    | -         |     9.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2458 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.556      | -            | -                | -                | -         |    -7.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2465 | 2024-05-01 | ENCE Academy      | W   | 0.556      | -            | -                | -                | -         |     4.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2470 | 2024-04-30 | GL Academy        | W   | 0.552      | -            | -                | -                | -         |     4.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2488 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.549      | -            | -                | -                | -         |    -7.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2606 | 2024-04-25 | ECLOT             | L   | 0.515      | -            | -                | -                | -         |    -2.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2625 | 2024-04-24 | Permitta          | W   | 0.509      | 0.371        | -                | 0.901 (0.170)    | -         |     9.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2644 | 2024-04-23 | ECLOT             | L   | 0.502      | -            | -                | -                | -         |    -2.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2680 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.489      | -            | -                | -                | -         |     8.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2754 | 2024-04-19 | BLEED             | L   | 0.476      | -            | -                | -                | -         |    -5.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2813 | 2024-04-18 | Permitta          | W   | 0.469      | -            | -                | -                | -         |     8.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2835 | 2024-04-17 | NOM               | L   | 0.463      | -            | -                | -                | -         |   -12.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2873 | 2024-04-16 | SAW               | W   | 0.456      | 0.384        | 0.104 (0.018)    | -                | -         |    11.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2877 | 2024-04-16 | Secret            | W   | 0.455      | -            | -                | -                | -         |     1.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2887 | 2024-04-15 | ENCE Academy      | L   | 0.450      | -            | -                | -                | -         |   -10.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2922 | 2024-04-13 | BetBoom           | L   | 0.436      | -            | -                | -                | -         |    -0.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2966 | 2024-04-11 | PGE Turow         | W   | 0.422      | -            | -                | -                | -         |     2.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3139 | 2024-04-06 | Enterprise        | W   | 0.389      | -            | -                | -                | -         |     6.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3245 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.369      | 0.384        | 0.254 (0.036)    | -                | -         |    11.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3367 | 2024-03-27 | B8                | L   | 0.325      | -            | -                | -                | -         |    -2.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3508 | 2024-03-18 | ex-Preasy         | L   | 0.262      | -            | -                | -                | -         |    -5.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3539 | 2024-03-17 | Passion UA        | W   | 0.256      | 0.371        | 0.173 (0.016)    | -                | -         |     5.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3547 | 2024-03-16 | SINNERS           | L   | 0.250      | -            | -                | -                | -         |    -1.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3550 | 2024-03-16 | MOUZ NXT          | W   | 0.249      | 0.371        | 0.139 (0.013)    | -                | -         |     5.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3565 | 2024-03-15 | ECLOT             | L   | 0.244      | -            | -                | -                | -         |    -1.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3571 | 2024-03-15 | Permitta          | W   | 0.242      | -            | -                | -                | -         |     4.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3601 | 2024-03-14 | Passion UA        | L   | 0.236      | -            | -                | -                | -         |    -1.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3671 | 2024-03-12 | MOUZ NXT          | W   | 0.222      | -            | -                | -                | -         |     4.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3713 | 2024-03-10 | Sashi             | W   | 0.209      | 0.358        | 0.184 (0.014)    | -                | -         |     5.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3739 | 2024-03-09 | Enterprise        | W   | 0.203      | -            | -                | -                | -         |     3.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3824 | 2024-03-06 | AURA              | W   | 0.182      | -            | -                | -                | -         |     0.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3870 | 2024-03-04 | Sangal            | L   | 0.169      | -            | -                | -                | -         |    -0.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3924 | 2024-03-02 | Enterprise        | L   | 0.156      | -            | -                | -                | -         |    -2.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3962 | 2024-02-28 | Sashi             | L   | 0.137      | -            | -                | -                | -         |    -0.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4027 | 2024-02-25 | ECLOT             | L   | 0.116      | -            | -                | -                | -         |    -0.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4073 | 2024-02-23 | Entropiq          | W   | 0.102      | -            | -                | -                | -         |     0.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4115 | 2024-02-21 | Sashi             | L   | 0.090      | -            | -                | -                | -         |    -0.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4219 | 2024-02-17 | Secret            | W   | 0.063      | -            | -                | -                | -         |     0.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4366 | 2024-02-10 | Zero Tenacity     | W   | 0.018      | -            | -                | -                | -         |     0.43 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,697.23)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.845 | $3,268.00      | $2,761.16       |
| 2024-06-02 |      0.771 | $653.00        | $503.32         |
| 2024-05-18 |      0.671 | $1,000.00      | $671.11         |
| 2024-04-25 |      0.515 | $5,000.00      | $2,576.39       |
| 2024-04-14 |      0.443 | $1,600.00      | $709.33         |
| 2024-03-18 |      0.262 | $5,000.00      | $1,311.11       |
| 2024-03-17 |      0.258 | $639.00        | $164.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
