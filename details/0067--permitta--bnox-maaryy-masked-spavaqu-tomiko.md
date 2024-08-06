### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  969.5<br />
<br />
Final Rank Value (969.5) = Starting Rank Value (960.6) + Head To Head Adjustments (8.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.438[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 960.6
- 400 + ( ( 0.273 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 960.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           99 |        2 | 2024-08-05 | B8                | W   | 1.000      | 0.435        | 0.164 (0.071)    | 0.934 (0.406)    | 0 (0.000) |    24.04 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |       68 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.315 (0.137)    | 0.721 (0.313)    | 0 (0.000) |    23.97 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      149 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.04 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      201 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.63 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      205 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.533 (0.232)    | 0 (0.000) |    17.52 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      249 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.84 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      272 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      293 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.75 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      344 | 2024-07-26 | Space             | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |    15.50 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      350 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.46 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      388 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.67 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      436 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.38 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      487 | 2024-07-22 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.37 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      560 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.562 (0.244)    | 0 (0.000) |    15.87 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      649 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.90 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      699 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.550 (0.239)    | 0 (0.000) |    12.60 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      778 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.89 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      809 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.44 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      837 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.79 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      902 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.173 (0.064)    | 1.000 (0.371)    | -         |    18.69 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1030 | 2024-06-16 | 3DMAX             | L   | 0.863      | -            | -                | -                | -         |    -1.57 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1074 | 2024-06-15 | BIG               | W   | 0.855      | 0.435        | 0.154 (0.057)    | -                | -         |    23.74 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1111 | 2024-06-14 | PARIVISION        | W   | 0.849      | 0.435        | -                | 0.565 (0.208)    | -         |    18.84 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1125 | 2024-06-13 | 9INE              | L   | 0.845      | -            | -                | -                | -         |   -23.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1159 | 2024-06-12 | Nexus             | W   | 0.838      | -            | -                | -                | -         |     6.50 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1175 | 2024-06-11 | Nemiga            | L   | 0.831      | -            | -                | -                | -         |    -5.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           73 |     1200 | 2024-06-10 | Rebels            | L   | 0.825      | -            | -                | -                | -         |   -10.32 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1315 | 2024-06-08 | Space             | W   | 0.811      | -            | -                | -                | -         |    10.66 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           71 |     1446 | 2024-06-06 | Zero Tenacity     | W   | 0.797      | 0.435        | 0.143 (0.050)    | 1.000 (0.346)    | -         |    19.01 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           70 |     1581 | 2024-06-03 | GUN5              | W   | 0.776      | 0.435        | 0.072 (0.024)    | -                | -         |    14.87 | bnox, Markoś, mASKED, morelz, tomiko  |
|           69 |     1639 | 2024-06-01 | Enterprise        | L   | 0.762      | -            | -                | -                | -         |   -11.94 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           68 |     1650 | 2024-05-31 | AMKAL             | L   | 0.758      | -            | -                | -                | -         |    -4.25 | bnox, mASKED, morelz, Sidney, tomiko  |
|           67 |     1683 | 2024-05-30 | NAVI Junior       | W   | 0.751      | -            | -                | -                | -         |     2.74 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1691 | 2024-05-30 | Serbia            | L   | 0.749      | -            | -                | -                | -         |   -16.33 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1736 | 2024-05-28 | Preasy            | W   | 0.736      | -            | -                | -                | -         |     7.22 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1738 | 2024-05-28 | GUN5              | W   | 0.736      | 0.435        | 0.072 (0.023)    | -                | -         |    12.00 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1756 | 2024-05-27 | VP.Prodigy        | L   | 0.731      | -            | -                | -                | -         |   -12.00 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1780 | 2024-05-26 | ECLOT             | W   | 0.722      | -            | -                | -                | -         |    17.94 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1795 | 2024-05-25 | Nexus             | W   | 0.716      | -            | -                | -                | -         |     7.75 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1865 | 2024-05-22 | Endpoint          | W   | 0.697      | -            | -                | -                | -         |    11.60 | bnox, maaryy, mASKED, morelz, tomiko  |
|           59 |     1879 | 2024-05-22 | Johnny Speeds     | L   | 0.695      | -            | -                | -                | -         |    -2.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1900 | 2024-05-21 | INFINITE          | W   | 0.691      | -            | -                | -                | -         |     2.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1953 | 2024-05-20 | Passion UA        | L   | 0.682      | -            | -                | -                | -         |    -6.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2045 | 2024-05-17 | Sangal            | L   | 0.662      | -            | -                | -                | -         |    -5.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2112 | 2024-05-15 | EYEBALLERS        | L   | 0.651      | -            | -                | -                | -         |   -11.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2197 | 2024-05-13 | 1WIN              | L   | 0.638      | -            | -                | -                | -         |    -8.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|           53 |     2344 | 2024-05-07 | Enterprise        | L   | 0.596      | -            | -                | -                | -         |   -10.45 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2360 | 2024-05-06 | ENCE Academy      | W   | 0.589      | -            | -                | -                | -         |     4.53 | bnox, maaryy, mASKED, morelz, Sobol   |
|           51 |     2404 | 2024-05-03 | Insilio           | L   | 0.571      | -            | -                | -                | -         |    -8.78 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2431 | 2024-05-02 | Sampi             | L   | 0.564      | -            | -                | -                | -         |    -9.46 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           49 |     2443 | 2024-05-02 | B8                | L   | 0.562      | -            | -                | -                | -         |    -6.74 | bnox, maaryy, mASKED, morelz, Sobol   |
|           48 |     2491 | 2024-04-30 | BLEED             | L   | 0.549      | -            | -                | -                | -         |    -5.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2499 | 2024-04-29 | AMKAL             | L   | 0.544      | -            | -                | -                | -         |    -4.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           46 |     2508 | 2024-04-29 | RUBY              | W   | 0.542      | -            | -                | -                | -         |     7.98 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           45 |     2547 | 2024-04-27 | Insilio           | L   | 0.530      | -            | -                | -                | -         |    -9.26 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2553 | 2024-04-27 | Enterprise        | W   | 0.529      | -            | -                | -                | -         |     6.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2576 | 2024-04-26 | ARCRED            | L   | 0.522      | -            | -                | -                | -         |    -9.55 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2597 | 2024-04-25 | 1WIN              | L   | 0.517      | -            | -                | -                | -         |    -8.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2614 | 2024-04-24 | BLEED             | L   | 0.511      | -            | -                | -                | -         |    -6.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2619 | 2024-04-24 | Passion UA        | W   | 0.510      | 0.384        | 0.173 (0.034)    | 1.000 (0.196)    | -         |     9.26 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2625 | 2024-04-24 | Sampi             | L   | 0.509      | -            | -                | -                | -         |    -9.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2647 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.502      | -            | -                | -                | -         |     7.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2661 | 2024-04-22 | Grannys Knockers  | W   | 0.496      | -            | -                | -                | -         |     3.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2681 | 2024-04-21 | Insilio           | W   | 0.489      | -            | -                | -                | -         |     6.44 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2706 | 2024-04-20 | Nexus             | L   | 0.483      | -            | -                | -                | -         |   -10.18 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2711 | 2024-04-20 | Passion UA        | W   | 0.482      | 0.371        | 0.173 (0.031)    | -                | -         |     9.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2802 | 2024-04-18 | Passion UA        | L   | 0.470      | -            | -                | -                | -         |    -5.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2813 | 2024-04-18 | Sampi             | L   | 0.469      | -            | -                | -                | -         |    -8.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2831 | 2024-04-17 | PARIVISION        | W   | 0.464      | -            | -                | -                | -         |     9.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2871 | 2024-04-16 | Gaimin Gladiators | L   | 0.456      | -            | -                | -                | -         |    -6.81 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2933 | 2024-04-12 | MOUZ NXT          | W   | 0.429      | -            | -                | -                | -         |     8.32 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3014 | 2024-04-10 | EYEBALLERS        | W   | 0.416      | -            | -                | -                | -         |     5.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3090 | 2024-04-08 | HAVU              | W   | 0.403      | -            | -                | -                | -         |     2.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3101 | 2024-04-08 | JANO              | W   | 0.402      | -            | -                | -                | -         |     2.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3228 | 2024-04-03 | Enterprise        | L   | 0.371      | -            | -                | -                | -         |    -6.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3240 | 2024-04-03 | ECLOT             | L   | 0.369      | -            | -                | -                | -         |    -2.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3273 | 2024-04-02 | 3DMAX             | L   | 0.363      | -            | -                | -                | -         |    -0.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3282 | 2024-04-02 | Sashi             | L   | 0.362      | -            | -                | -                | -         |    -3.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3546 | 2024-03-16 | RUBY              | L   | 0.251      | -            | -                | -                | -         |    -4.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3566 | 2024-03-15 | The Chosen Few    | W   | 0.244      | -            | -                | -                | -         |     1.27 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3571 | 2024-03-15 | Sampi             | L   | 0.242      | -            | -                | -                | -         |    -4.72 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3619 | 2024-03-13 | MOUZ NXT          | W   | 0.232      | -            | -                | -                | -         |     4.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3636 | 2024-03-13 | ECLOT             | W   | 0.230      | -            | -                | -                | -         |     5.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3651 | 2024-03-13 | ECLOT             | W   | 0.229      | -            | -                | -                | -         |     5.72 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3692 | 2024-03-11 | ex-Preasy         | L   | 0.216      | -            | -                | -                | -         |    -4.97 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3737 | 2024-03-09 | Sashi             | L   | 0.203      | -            | -                | -                | -         |    -1.81 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3774 | 2024-03-07 | VP.Prodigy        | W   | 0.191      | -            | -                | -                | -         |     2.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3784 | 2024-03-07 | kONO              | W   | 0.189      | -            | -                | -                | -         |     1.71 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3811 | 2024-03-06 | Passion UA        | W   | 0.184      | -            | -                | -                | -         |     3.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3813 | 2024-03-06 | Enterprise        | W   | 0.183      | -            | -                | -                | -         |     2.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3853 | 2024-03-05 | Young Ninjas      | W   | 0.177      | -            | -                | -                | -         |     1.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3920 | 2024-03-02 | AURA              | W   | 0.156      | -            | -                | -                | -         |     0.33 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3964 | 2024-02-28 | Secret            | L   | 0.137      | -            | -                | -                | -         |    -3.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3968 | 2024-02-28 | ECLOT             | L   | 0.136      | -            | -                | -                | -         |    -0.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     3987 | 2024-02-27 | Sprout            | W   | 0.129      | -            | -                | -                | -         |     0.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4060 | 2024-02-24 | ECLOT             | W   | 0.110      | -            | -                | -                | -         |     2.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|            3 |     4093 | 2024-02-22 | PGE Turow         | W   | 0.096      | -            | -                | -                | -         |     0.45 | bnox, maaryy, mASKED, morelz, reiko   |
|            2 |     4127 | 2024-02-21 | ECLOT             | L   | 0.089      | -            | -                | -                | -         |    -0.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4172 | 2024-02-19 | ECLOT             | W   | 0.076      | -            | -                | -                | -         |     1.95 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,537.77)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $5,000.00      | $4,320.83       |
| 2024-06-13 |      0.845 | $545.00        | $460.47         |
| 2024-05-02 |      0.564 | $500.00        | $282.08         |
| 2024-04-25 |      0.515 | $3,000.00      | $1,545.83       |
| 2024-03-25 |      0.311 | $1,250.00      | $388.54         |
| 2024-02-28 |      0.136 | $3,000.00      | $406.67         |
| 2024-02-21 |      0.089 | $1,500.00      | $133.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
