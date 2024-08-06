### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  882.8<br />
<br />
Final Rank Value (882.8) = Starting Rank Value (886.4) + Head To Head Adjustments (-3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.4
- 400 + ( ( 0.237 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 886.4


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
|           94 |       22 | 2024-08-05 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |      149 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      159 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      189 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      208 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      245 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    16.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      256 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      283 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      304 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.361 (0.157)    | 0 (0.000) |    12.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      352 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.513 (0.223)    | 0 (0.000) |    12.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      364 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      434 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      465 | 2024-07-23 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      505 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      516 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      592 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      640 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      766 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.491 (0.213)    | 0 (0.000) |    15.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      781 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      831 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.87 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      835 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | -         |     6.55 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      896 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.15 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      935 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.87 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1137 | 2024-06-13 | Rebels            | W   | 0.842      | 0.379        | 0.038 (0.012)    | 0.591 (0.188)    | -         |    17.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1144 | 2024-06-13 | Sashi             | L   | 0.841      | -            | -                | -                | -         |    -3.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1168 | 2024-06-12 | Enterprise        | L   | 0.835      | -            | -                | -                | -         |   -10.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1187 | 2024-06-11 | Astralis Talent   | W   | 0.828      | -            | -                | -                | -         |     8.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1197 | 2024-06-11 | Illuminar         | L   | 0.826      | -            | -                | -                | -         |   -12.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1257 | 2024-06-09 | Aurora Young Blud | L   | 0.815      | -            | -                | -                | -         |   -13.81 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1326 | 2024-06-08 | MOUZ NXT          | L   | 0.808      | -            | -                | -                | -         |    -6.51 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1345 | 2024-06-08 | CYBERSHOKE        | L   | 0.806      | -            | -                | -                | -         |   -14.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1447 | 2024-06-06 | Nemiga            | L   | 0.795      | -            | -                | -                | -         |    -6.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1463 | 2024-06-06 | HAVU              | W   | 0.794      | -            | -                | -                | -         |     6.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1506 | 2024-06-05 | NAVI Junior       | W   | 0.788      | -            | -                | -                | -         |     2.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1543 | 2024-06-04 | INFINITE          | W   | 0.782      | -            | -                | -                | -         |     2.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1563 | 2024-06-04 | DMS               | W   | 0.780      | 0.500        | -                | 0.437 (0.171)    | -         |    14.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1587 | 2024-06-03 | Rare Atom         | W   | 0.773      | 0.435        | -                | 0.475 (0.159)    | -         |     9.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1638 | 2024-06-01 | SINNERS           | L   | 0.761      | -            | -                | -                | -         |    -6.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1659 | 2024-05-31 | ECLOT             | L   | 0.755      | -            | -                | -                | -         |    -4.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1683 | 2024-05-30 | 3DMAX             | L   | 0.749      | -            | -                | -                | -         |    -0.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1736 | 2024-05-28 | Enterprise        | L   | 0.735      | -            | -                | -                | -         |   -11.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1739 | 2024-05-28 | Rhyno             | W   | 0.734      | 0.435        | 0.071 (0.023)    | -                | -         |    13.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1774 | 2024-05-26 | SINNERS           | L   | 0.721      | -            | -                | -                | -         |    -6.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1792 | 2024-05-25 | Passion UA        | L   | 0.715      | -            | -                | -                | -         |    -7.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1823 | 2024-05-23 | GUN5              | W   | 0.702      | 0.435        | 0.072 (0.022)    | 0.562 (0.172)    | -         |    12.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1858 | 2024-05-22 | VENI VIDI VICI    | W   | 0.696      | -            | -                | -                | -         |     1.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1947 | 2024-05-20 | Illuminar         | W   | 0.681      | -            | -                | -                | -         |    10.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1955 | 2024-05-20 | Verdant           | L   | 0.680      | -            | -                | -                | -         |   -10.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     2010 | 2024-05-18 | DMS               | L   | 0.667      | -            | -                | -                | -         |   -10.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2073 | 2024-05-16 | MOUZ NXT          | L   | 0.655      | -            | -                | -                | -         |    -6.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2081 | 2024-05-16 | B8                | L   | 0.653      | -            | -                | -                | -         |    -5.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2209 | 2024-05-13 | Nexus             | W   | 0.634      | -            | -                | -                | -         |     6.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2297 | 2024-05-09 | BLEED             | L   | 0.609      | -            | -                | -                | -         |    -6.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2374 | 2024-05-05 | RUSH B            | W   | 0.582      | -            | -                | -                | -         |     7.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2403 | 2024-05-04 | Endpoint          | L   | 0.573      | -            | -                | -                | -         |    -8.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2435 | 2024-05-02 | Permitta          | W   | 0.561      | 0.435        | -                | 0.940 (0.229)    | -         |     9.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2462 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.554      | -            | -                | -                | -         |    -7.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2469 | 2024-05-01 | ENCE Academy      | W   | 0.553      | -            | -                | -                | -         |     4.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2474 | 2024-04-30 | GL Academy        | W   | 0.549      | -            | -                | -                | -         |     4.89 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2492 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.547      | -            | -                | -                | -         |    -7.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2610 | 2024-04-25 | ECLOT             | L   | 0.513      | -            | -                | -                | -         |    -2.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2629 | 2024-04-24 | Permitta          | W   | 0.506      | 0.371        | -                | 0.940 (0.176)    | -         |     9.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2648 | 2024-04-23 | ECLOT             | L   | 0.500      | -            | -                | -                | -         |    -2.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2684 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.486      | -            | -                | -                | -         |     8.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2758 | 2024-04-19 | BLEED             | L   | 0.473      | -            | -                | -                | -         |    -5.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2817 | 2024-04-18 | Permitta          | W   | 0.466      | 0.371        | -                | 0.940 (0.162)    | -         |     8.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2839 | 2024-04-17 | NOM               | L   | 0.461      | -            | -                | -                | -         |   -12.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2877 | 2024-04-16 | SAW               | W   | 0.454      | 0.384        | 0.104 (0.018)    | -                | -         |    11.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2881 | 2024-04-16 | Secret            | W   | 0.453      | -            | -                | -                | -         |     1.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2891 | 2024-04-15 | ENCE Academy      | L   | 0.448      | -            | -                | -                | -         |   -10.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2926 | 2024-04-13 | BetBoom           | L   | 0.433      | -            | -                | -                | -         |    -0.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2970 | 2024-04-11 | PGE Turow         | W   | 0.419      | -            | -                | -                | -         |     2.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3143 | 2024-04-06 | Enterprise        | W   | 0.387      | -            | -                | -                | -         |     6.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3249 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.367      | 0.384        | 0.254 (0.036)    | -                | -         |    11.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3371 | 2024-03-27 | B8                | L   | 0.322      | -            | -                | -                | -         |    -2.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3512 | 2024-03-18 | ex-Preasy         | L   | 0.260      | -            | -                | -                | -         |    -5.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3543 | 2024-03-17 | Passion UA        | W   | 0.253      | 0.371        | 0.173 (0.016)    | -                | -         |     5.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3551 | 2024-03-16 | SINNERS           | L   | 0.248      | -            | -                | -                | -         |    -1.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3554 | 2024-03-16 | MOUZ NXT          | W   | 0.246      | 0.371        | 0.139 (0.013)    | -                | -         |     5.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3569 | 2024-03-15 | ECLOT             | L   | 0.241      | -            | -                | -                | -         |    -1.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3575 | 2024-03-15 | Permitta          | W   | 0.240      | -            | -                | -                | -         |     4.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3605 | 2024-03-14 | Passion UA        | L   | 0.234      | -            | -                | -                | -         |    -1.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3675 | 2024-03-12 | MOUZ NXT          | W   | 0.220      | -            | -                | -                | -         |     4.89 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3717 | 2024-03-10 | Sashi             | W   | 0.207      | 0.358        | 0.184 (0.014)    | -                | -         |     5.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3743 | 2024-03-09 | Enterprise        | W   | 0.200      | -            | -                | -                | -         |     3.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3828 | 2024-03-06 | AURA              | W   | 0.180      | -            | -                | -                | -         |     0.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3874 | 2024-03-04 | Sangal            | L   | 0.167      | -            | -                | -                | -         |    -0.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3928 | 2024-03-02 | Enterprise        | L   | 0.153      | -            | -                | -                | -         |    -2.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3966 | 2024-02-28 | Sashi             | L   | 0.134      | -            | -                | -                | -         |    -0.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4031 | 2024-02-25 | ECLOT             | L   | 0.113      | -            | -                | -                | -         |    -0.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4077 | 2024-02-23 | Entropiq          | W   | 0.100      | -            | -                | -                | -         |     0.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4119 | 2024-02-21 | Sashi             | L   | 0.087      | -            | -                | -                | -         |    -0.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4223 | 2024-02-17 | Secret            | W   | 0.061      | -            | -                | -                | -         |     0.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4370 | 2024-02-10 | Zero Tenacity     | W   | 0.015      | -            | -                | -                | -         |     0.37 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,654.33)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.842 | $3,268.00      | $2,752.99       |
| 2024-06-02 |      0.768 | $653.00        | $501.69         |
| 2024-05-18 |      0.669 | $1,000.00      | $668.61         |
| 2024-04-25 |      0.513 | $5,000.00      | $2,563.89       |
| 2024-04-14 |      0.441 | $1,600.00      | $705.33         |
| 2024-03-18 |      0.260 | $5,000.00      | $1,298.61       |
| 2024-03-17 |      0.255 | $639.00        | $163.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
