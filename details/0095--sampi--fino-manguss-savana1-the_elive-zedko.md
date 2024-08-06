### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  886.9<br />
<br />
Final Rank Value (886.9) = Starting Rank Value (886.1) + Head To Head Adjustments (0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.236<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.1
- 400 + ( ( 0.236 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 886.1


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
|           94 |       36 | 2024-08-05 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |      163 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      173 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      203 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -13.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      222 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      259 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    16.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      270 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      297 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      318 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.353 (0.154)    | 0 (0.000) |    12.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      366 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |    12.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      378 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      448 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      479 | 2024-07-23 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      519 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      530 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      606 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      654 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      780 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.479 (0.208)    | 0 (0.000) |    15.28 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      795 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      845 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.96 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      849 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | -         |     6.44 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      910 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.01 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      949 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.83 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1151 | 2024-06-13 | Rebels            | W   | 0.840      | 0.379        | 0.038 (0.012)    | 0.578 (0.184)    | -         |    17.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1158 | 2024-06-13 | Sashi             | L   | 0.839      | -            | -                | -                | -         |    -3.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1182 | 2024-06-12 | Enterprise        | L   | 0.833      | -            | -                | -                | -         |   -11.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1201 | 2024-06-11 | Astralis Talent   | W   | 0.827      | -            | -                | -                | -         |     8.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1211 | 2024-06-11 | Illuminar         | L   | 0.825      | -            | -                | -                | -         |   -12.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1271 | 2024-06-09 | Aurora Young Blud | L   | 0.813      | -            | -                | -                | -         |   -12.86 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1340 | 2024-06-08 | MOUZ NXT          | L   | 0.807      | -            | -                | -                | -         |    -6.52 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1359 | 2024-06-08 | CYBERSHOKE        | L   | 0.805      | -            | -                | -                | -         |   -14.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1461 | 2024-06-06 | Nemiga            | L   | 0.793      | -            | -                | -                | -         |    -6.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1477 | 2024-06-06 | HAVU              | W   | 0.792      | -            | -                | -                | -         |     6.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1520 | 2024-06-05 | NAVI Junior       | W   | 0.787      | -            | -                | -                | -         |     6.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1557 | 2024-06-04 | INFINITE          | W   | 0.781      | -            | -                | -                | -         |     2.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1577 | 2024-06-04 | DMS               | W   | 0.778      | 0.500        | -                | 0.428 (0.166)    | -         |    14.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1601 | 2024-06-03 | Rare Atom         | W   | 0.771      | 0.435        | -                | 0.465 (0.156)    | -         |     9.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1652 | 2024-06-01 | SINNERS           | L   | 0.759      | -            | -                | -                | -         |    -6.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1673 | 2024-05-31 | ECLOT             | L   | 0.754      | -            | -                | -                | -         |    -4.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1697 | 2024-05-30 | 3DMAX             | L   | 0.748      | -            | -                | -                | -         |    -0.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1750 | 2024-05-28 | Enterprise        | L   | 0.733      | -            | -                | -                | -         |   -11.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1753 | 2024-05-28 | Rhyno             | W   | 0.733      | 0.435        | 0.071 (0.022)    | -                | -         |    13.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1788 | 2024-05-26 | SINNERS           | L   | 0.720      | -            | -                | -                | -         |    -6.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1806 | 2024-05-25 | Passion UA        | L   | 0.713      | -            | -                | -                | -         |    -7.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1837 | 2024-05-23 | GUN5              | W   | 0.701      | 0.435        | 0.072 (0.022)    | 0.550 (0.168)    | -         |    12.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1872 | 2024-05-22 | VENI VIDI VICI    | W   | 0.695      | -            | -                | -                | -         |     1.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1961 | 2024-05-20 | Illuminar         | W   | 0.680      | -            | -                | -                | -         |    10.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1969 | 2024-05-20 | Verdant           | L   | 0.679      | -            | -                | -                | -         |   -10.28 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     2024 | 2024-05-18 | DMS               | L   | 0.666      | -            | -                | -                | -         |   -10.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2087 | 2024-05-16 | MOUZ NXT          | L   | 0.653      | -            | -                | -                | -         |    -6.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2095 | 2024-05-16 | B8                | L   | 0.652      | -            | -                | -                | -         |    -5.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2223 | 2024-05-13 | Nexus             | W   | 0.632      | -            | -                | -                | -         |     6.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2311 | 2024-05-09 | BLEED             | L   | 0.608      | -            | -                | -                | -         |    -6.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2388 | 2024-05-05 | RUSH B            | W   | 0.580      | -            | -                | -                | -         |     7.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2417 | 2024-05-04 | Endpoint          | L   | 0.572      | -            | -                | -                | -         |    -8.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2449 | 2024-05-02 | Permitta          | W   | 0.560      | 0.435        | -                | 0.919 (0.224)    | -         |     9.65 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2476 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.553      | -            | -                | -                | -         |    -7.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2483 | 2024-05-01 | ENCE Academy      | W   | 0.552      | -            | -                | -                | -         |     4.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2488 | 2024-04-30 | GL Academy        | W   | 0.548      | -            | -                | -                | -         |     4.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2506 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.545      | -            | -                | -                | -         |    -7.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2624 | 2024-04-25 | ECLOT             | L   | 0.511      | -            | -                | -                | -         |    -2.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2643 | 2024-04-24 | Permitta          | W   | 0.505      | 0.371        | -                | 0.919 (0.172)    | -         |     9.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2662 | 2024-04-23 | ECLOT             | L   | 0.498      | -            | -                | -                | -         |    -2.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2698 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.485      | -            | -                | -                | -         |     8.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2772 | 2024-04-19 | BLEED             | L   | 0.472      | -            | -                | -                | -         |    -5.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2831 | 2024-04-18 | Permitta          | W   | 0.465      | 0.371        | -                | 0.919 (0.158)    | -         |     9.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2853 | 2024-04-17 | NOM               | L   | 0.459      | -            | -                | -                | -         |   -12.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2891 | 2024-04-16 | SAW               | W   | 0.452      | 0.384        | 0.104 (0.018)    | -                | -         |    11.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2895 | 2024-04-16 | Secret            | W   | 0.451      | -            | -                | -                | -         |     1.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2905 | 2024-04-15 | ENCE Academy      | L   | 0.446      | -            | -                | -                | -         |   -10.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2940 | 2024-04-13 | BetBoom           | L   | 0.432      | -            | -                | -                | -         |    -0.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2984 | 2024-04-11 | PGE Turow         | W   | 0.418      | -            | -                | -                | -         |     2.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3157 | 2024-04-06 | Enterprise        | W   | 0.385      | -            | -                | -                | -         |     6.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3263 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.365      | 0.384        | 0.253 (0.036)    | -                | -         |    11.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3385 | 2024-03-27 | B8                | L   | 0.321      | -            | -                | -                | -         |    -2.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3526 | 2024-03-18 | ex-Preasy         | L   | 0.258      | -            | -                | -                | -         |    -5.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3557 | 2024-03-17 | Passion UA        | W   | 0.252      | 0.371        | 0.173 (0.016)    | -                | -         |     5.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3565 | 2024-03-16 | SINNERS           | L   | 0.246      | -            | -                | -                | -         |    -1.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3568 | 2024-03-16 | MOUZ NXT          | W   | 0.245      | 0.371        | 0.139 (0.013)    | -                | -         |     5.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3583 | 2024-03-15 | ECLOT             | L   | 0.240      | -            | -                | -                | -         |    -1.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3589 | 2024-03-15 | Permitta          | W   | 0.238      | -            | -                | -                | -         |     4.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3619 | 2024-03-14 | Passion UA        | L   | 0.233      | -            | -                | -                | -         |    -1.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3689 | 2024-03-12 | MOUZ NXT          | W   | 0.218      | -            | -                | -                | -         |     4.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3731 | 2024-03-10 | Sashi             | W   | 0.206      | 0.358        | 0.184 (0.014)    | -                | -         |     5.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3757 | 2024-03-09 | Enterprise        | W   | 0.199      | -            | -                | -                | -         |     3.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3842 | 2024-03-06 | AURA              | W   | 0.178      | -            | -                | -                | -         |     0.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3888 | 2024-03-04 | Sangal            | L   | 0.166      | -            | -                | -                | -         |    -0.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3942 | 2024-03-02 | Enterprise        | L   | 0.152      | -            | -                | -                | -         |    -2.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3980 | 2024-02-28 | Sashi             | L   | 0.133      | -            | -                | -                | -         |    -0.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4045 | 2024-02-25 | ECLOT             | L   | 0.112      | -            | -                | -                | -         |    -0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4091 | 2024-02-23 | Entropiq          | W   | 0.098      | -            | -                | -                | -         |     0.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4133 | 2024-02-21 | Sashi             | L   | 0.086      | -            | -                | -                | -         |    -0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4237 | 2024-02-17 | Secret            | W   | 0.059      | -            | -                | -                | -         |     0.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4384 | 2024-02-10 | Zero Tenacity     | W   | 0.014      | -            | -                | -                | -         |     0.34 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,630.50)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.841 | $3,268.00      | $2,748.45       |
| 2024-06-02 |      0.767 | $653.00        | $500.78         |
| 2024-05-18 |      0.667 | $1,000.00      | $667.22         |
| 2024-04-25 |      0.511 | $5,000.00      | $2,556.94       |
| 2024-04-14 |      0.439 | $1,600.00      | $703.11         |
| 2024-03-18 |      0.258 | $5,000.00      | $1,291.67       |
| 2024-03-17 |      0.254 | $639.00        | $162.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
