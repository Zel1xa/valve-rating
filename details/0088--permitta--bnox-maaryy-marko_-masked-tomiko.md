### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, Markoś, mASKED, tomiko<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  887.3<br />
<br />
Final Rank Value (887.3) = Starting Rank Value (948.3) + Head To Head Adjustments (-61.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.283<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 948.3
- 400 + ( ( 0.283 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 948.3


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
|          118 |       55 | 2024-09-06 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.99 | bnox, maaryy, Markoś, mASKED, tomiko  |
|          117 |       65 | 2024-09-05 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -5.32 | bnox, fr3nd, maaryy, mASKED, tomiko   |
|          116 |      156 | 2024-09-03 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.70 | bnox, fr3nd, maaryy, mASKED, tomiko   |
|          115 |      181 | 2024-09-02 | Alliance          | L   | 1.000      | -            | -                | -                | -         |   -16.48 | bnox, fr3nd, maaryy, mASKED, tomiko   |
|          114 |      212 | 2024-08-31 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.00 | bnox, fr3nd, maaryy, mASKED, tomiko   |
|          113 |      220 | 2024-08-31 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.56 | bnox, maaryy, mASKED, mwlky, tomiko   |
|          112 |      279 | 2024-08-29 | Revenant          | W   | 1.000      | 0.435        | -                | 0.666 (0.289)    | 0 (0.000) |    17.86 | bnox, fr3nd, maaryy, mASKED, tomiko   |
|          111 |      437 | 2024-08-26 | EYEBALLERS        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.93 | bnox, fr3nd, maaryy, mASKED, tomiko   |
|          110 |      465 | 2024-08-26 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |    -9.91 | bnox, maaryy, Markoś, mASKED, tomiko  |
|          109 |      513 | 2024-08-25 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -11.32 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          108 |      538 | 2024-08-24 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -12.03 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          107 |      550 | 2024-08-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          106 |      555 | 2024-08-23 | BIG               | L   | 1.000      | -            | -                | -                | -         |    -5.28 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          105 |      587 | 2024-08-22 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -1.16 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          104 |      621 | 2024-08-21 | RUBY              | W   | 1.000      | 0.435        | 0.073 (0.032)    | -                | 0 (0.000) |    12.94 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          103 |      638 | 2024-08-21 | Nemiga            | W   | 1.000      | 0.143        | 0.303 (0.043)    | -                | 0 (0.000) |    27.17 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          102 |      651 | 2024-08-21 | AMKAL             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    22.46 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          101 |      695 | 2024-08-20 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -19.17 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          100 |      739 | 2024-08-18 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -11.42 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           99 |      746 | 2024-08-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -13.02 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |      792 | 2024-08-16 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.84 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      835 | 2024-08-15 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.93 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      848 | 2024-08-14 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.08 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      868 | 2024-08-13 | Illuminar         | W   | 1.000      | -            | -                | -                | -         |    12.49 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      887 | 2024-08-13 | Space             | W   | 1.000      | -            | -                | -                | -         |    11.29 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      932 | 2024-08-12 | Alliance          | L   | 1.000      | -            | -                | -                | -         |   -19.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      938 | 2024-08-12 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -12.27 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |     1015 | 2024-08-09 | TSM               | L   | 0.999      | -            | -                | -                | -         |   -11.87 | bnox, maaryy, mASKED, mwlky, tomiko   |
|           90 |     1028 | 2024-08-08 | Qiang             | L   | 0.994      | -            | -                | -                | -         |   -16.31 | bnox, maaryy, mASKED, mwlky, tomiko   |
|           89 |     1040 | 2024-08-08 | Young Ninjas      | L   | 0.992      | -            | -                | -                | -         |   -20.12 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |     1080 | 2024-08-07 | Verdant           | W   | 0.986      | -            | -                | -                | -         |     9.68 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |     1096 | 2024-08-07 | 9INE              | L   | 0.985      | -            | -                | -                | -         |   -16.64 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |     1121 | 2024-08-06 | Sangal            | L   | 0.980      | -            | -                | -                | -         |    -3.38 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |     1133 | 2024-08-06 | FLuffy Gangsters  | W   | 0.979      | -            | -                | -                | -         |     4.57 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |     1138 | 2024-08-05 | B8                | W   | 0.975      | 0.435        | 0.176 (0.074)    | 1.000 (0.424)    | -         |    22.36 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |     1204 | 2024-08-03 | Nemiga            | W   | 0.961      | 0.435        | 0.303 (0.127)    | 0.774 (0.323)    | -         |    22.57 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |     1285 | 2024-08-01 | K27               | W   | 0.947      | -            | -                | -                | -         |     4.38 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |     1337 | 2024-07-31 | Endpoint          | L   | 0.940      | -            | -                | -                | -         |   -16.36 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |     1339 | 2024-07-31 | 9INE              | W   | 0.939      | 0.435        | -                | 0.707 (0.289)    | -         |    15.94 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1385 | 2024-07-30 | PARIVISION        | L   | 0.932      | -            | -                | -                | -         |    -8.52 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1408 | 2024-07-29 | HAVU              | W   | 0.927      | -            | -                | -                | -         |     3.82 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1429 | 2024-07-28 | BC.Game           | W   | 0.922      | -            | -                | -                | -         |    13.88 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1480 | 2024-07-26 | Space             | W   | 0.908      | -            | -                | -                | -         |    12.85 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           75 |     1486 | 2024-07-26 | Sangal            | L   | 0.907      | -            | -                | -                | -         |    -2.72 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           74 |     1524 | 2024-07-25 | Into the Breach   | L   | 0.901      | -            | -                | -                | -         |   -15.22 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           73 |     1572 | 2024-07-24 | Meteor            | L   | 0.892      | -            | -                | -                | -         |   -21.64 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1623 | 2024-07-22 | Metizport         | W   | 0.881      | -            | -                | -                | -         |    13.45 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           71 |     1696 | 2024-07-20 | GUN5              | W   | 0.866      | 0.435        | 0.091 (0.034)    | 0.959 (0.361)    | -         |    15.18 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           70 |     1785 | 2024-07-18 | INFINITE          | L   | 0.853      | -            | -                | -                | -         |   -23.86 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           69 |     1835 | 2024-07-17 | ALTERNATE aTTaX   | W   | 0.848      | 0.435        | 0.102 (0.037)    | 0.837 (0.308)    | -         |    12.81 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           68 |     1916 | 2024-07-16 | Passion UA        | L   | 0.839      | -            | -                | -                | -         |    -9.70 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           67 |     1948 | 2024-07-15 | Space             | L   | 0.834      | -            | -                | -                | -         |   -15.80 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           66 |     1976 | 2024-07-14 | Insilio           | L   | 0.826      | -            | -                | -                | -         |   -13.52 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           65 |     2041 | 2024-07-10 | Passion UA        | W   | 0.799      | 0.371        | 0.164 (0.048)    | 1.000 (0.296)    | -         |    15.32 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           64 |     2169 | 2024-06-16 | 3DMAX             | L   | 0.640      | -            | -                | -                | -         |    -0.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           63 |     2213 | 2024-06-15 | BIG               | W   | 0.632      | 0.435        | 0.146 (0.040)    | -                | -         |    16.47 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           62 |     2250 | 2024-06-14 | PARIVISION        | W   | 0.626      | -            | -                | -                | -         |    14.11 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           61 |     2264 | 2024-06-13 | 9INE              | L   | 0.621      | -            | -                | -                | -         |   -17.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           60 |     2298 | 2024-06-12 | Nexus             | W   | 0.614      | -            | -                | -                | -         |     4.97 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     2314 | 2024-06-11 | Nemiga            | L   | 0.608      | -            | -                | -                | -         |    -3.98 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     2339 | 2024-06-10 | Rebels            | L   | 0.601      | -            | -                | -                | -         |    -8.99 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           57 |     2454 | 2024-06-08 | Space             | W   | 0.588      | -            | -                | -                | -         |     7.42 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           56 |     2585 | 2024-06-06 | Zero Tenacity     | W   | 0.574      | 0.435        | 0.163 (0.041)    | 1.000 (0.249)    | -         |    13.31 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           55 |     2720 | 2024-06-03 | GUN5              | W   | 0.553      | 0.435        | 0.091 (0.022)    | 0.959 (0.230)    | -         |    11.18 | bnox, Markoś, mASKED, morelz, tomiko  |
|           54 |     2778 | 2024-06-01 | Enterprise        | L   | 0.539      | -            | -                | -                | -         |    -9.06 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           53 |     2789 | 2024-05-31 | AMKAL             | L   | 0.535      | -            | -                | -                | -         |    -3.80 | bnox, mASKED, morelz, Sidney, tomiko  |
|           52 |     2822 | 2024-05-30 | NAVI Junior       | W   | 0.527      | -            | -                | -                | -         |     3.77 | bnox, maaryy, mASKED, morelz, tomiko  |
|           51 |     2830 | 2024-05-30 | Partizan          | L   | 0.526      | -            | -                | -                | -         |   -11.67 | bnox, maaryy, mASKED, morelz, tomiko  |
|           50 |     2875 | 2024-05-28 | Preasy            | W   | 0.513      | -            | -                | -                | -         |     4.20 | bnox, maaryy, mASKED, morelz, tomiko  |
|           49 |     2877 | 2024-05-28 | GUN5              | W   | 0.512      | 0.435        | -                | 0.959 (0.214)    | -         |     9.48 | bnox, maaryy, mASKED, morelz, tomiko  |
|           48 |     2895 | 2024-05-27 | VP.Prodigy        | L   | 0.507      | -            | -                | -                | -         |    -9.33 | bnox, maaryy, mASKED, morelz, tomiko  |
|           47 |     2919 | 2024-05-26 | ECLOT             | W   | 0.499      | -            | -                | -                | -         |    10.93 | bnox, maaryy, mASKED, morelz, tomiko  |
|           46 |     2934 | 2024-05-25 | Nexus             | W   | 0.493      | -            | -                | -                | -         |     5.05 | bnox, maaryy, mASKED, morelz, tomiko  |
|           45 |     3004 | 2024-05-22 | Endpoint          | W   | 0.474      | -            | -                | -                | -         |     9.61 | bnox, maaryy, mASKED, morelz, tomiko  |
|           44 |     3018 | 2024-05-22 | Johnny Speeds     | L   | 0.472      | -            | -                | -                | -         |    -3.13 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     3039 | 2024-05-21 | INFINITE          | W   | 0.468      | -            | -                | -                | -         |     1.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     3092 | 2024-05-20 | Passion UA        | L   | 0.459      | -            | -                | -                | -         |    -4.93 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     3184 | 2024-05-17 | Sangal            | L   | 0.439      | -            | -                | -                | -         |    -1.71 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     3251 | 2024-05-15 | EYEBALLERS        | L   | 0.428      | -            | -                | -                | -         |    -8.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     3336 | 2024-05-13 | 1WIN              | L   | 0.414      | -            | -                | -                | -         |    -6.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     3483 | 2024-05-07 | Enterprise        | L   | 0.372      | -            | -                | -                | -         |    -6.80 | bnox, maaryy, mASKED, morelz, Sobol   |
|           37 |     3499 | 2024-05-06 | ENCE Academy      | W   | 0.366      | -            | -                | -                | -         |     2.48 | bnox, maaryy, mASKED, morelz, Sobol   |
|           36 |     3543 | 2024-05-03 | Insilio           | L   | 0.347      | -            | -                | -                | -         |    -5.58 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           35 |     3570 | 2024-05-02 | Sampi             | L   | 0.341      | -            | -                | -                | -         |    -5.66 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           34 |     3582 | 2024-05-02 | B8                | L   | 0.339      | -            | -                | -                | -         |    -3.82 | bnox, maaryy, mASKED, morelz, Sobol   |
|           33 |     3630 | 2024-04-30 | BLEED             | L   | 0.326      | -            | -                | -                | -         |    -5.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     3638 | 2024-04-29 | AMKAL             | L   | 0.320      | -            | -                | -                | -         |    -2.98 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     3647 | 2024-04-29 | RUBY              | W   | 0.319      | -            | -                | -                | -         |     4.29 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           30 |     3686 | 2024-04-27 | Insilio           | L   | 0.307      | -            | -                | -                | -         |    -5.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     3692 | 2024-04-27 | Enterprise        | W   | 0.306      | -            | -                | -                | -         |     3.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3715 | 2024-04-26 | ARCRED            | L   | 0.299      | -            | -                | -                | -         |    -5.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3736 | 2024-04-25 | 1WIN              | L   | 0.294      | -            | -                | -                | -         |    -5.38 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3753 | 2024-04-24 | BLEED             | L   | 0.288      | -            | -                | -                | -         |    -5.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3758 | 2024-04-24 | Passion UA        | W   | 0.287      | -            | -                | -                | -         |     5.28 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3764 | 2024-04-24 | Sampi             | L   | 0.285      | -            | -                | -                | -         |    -5.06 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3786 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.278      | -            | -                | -                | -         |     5.20 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3800 | 2024-04-22 | Grannys Knockers  | W   | 0.272      | -            | -                | -                | -         |     1.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3820 | 2024-04-21 | Insilio           | W   | 0.265      | -            | -                | -                | -         |     3.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3845 | 2024-04-20 | Nexus             | L   | 0.260      | -            | -                | -                | -         |    -5.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3850 | 2024-04-20 | Passion UA        | W   | 0.259      | -            | -                | -                | -         |     4.89 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3941 | 2024-04-18 | Passion UA        | L   | 0.246      | -            | -                | -                | -         |    -3.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3952 | 2024-04-18 | Sampi             | L   | 0.245      | -            | -                | -                | -         |    -4.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3970 | 2024-04-17 | PARIVISION        | W   | 0.240      | -            | -                | -                | -         |     5.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     4010 | 2024-04-16 | Gaimin Gladiators | L   | 0.233      | -            | -                | -                | -         |    -4.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     4072 | 2024-04-12 | MOUZ NXT          | W   | 0.206      | -            | -                | -                | -         |     3.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     4153 | 2024-04-10 | EYEBALLERS        | W   | 0.192      | -            | -                | -                | -         |     1.92 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     4229 | 2024-04-08 | HAVU              | W   | 0.180      | -            | -                | -                | -         |     0.60 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     4240 | 2024-04-08 | JANO              | W   | 0.179      | -            | -                | -                | -         |     0.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     4367 | 2024-04-03 | Enterprise        | L   | 0.147      | -            | -                | -                | -         |    -2.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     4379 | 2024-04-03 | ECLOT             | L   | 0.146      | -            | -                | -                | -         |    -1.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     4412 | 2024-04-02 | 3DMAX             | L   | 0.140      | -            | -                | -                | -         |    -0.06 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     4421 | 2024-04-02 | Sashi             | L   | 0.139      | -            | -                | -                | -         |    -1.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     4685 | 2024-03-16 | RUBY              | L   | 0.027      | -            | -                | -                | -         |    -0.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     4705 | 2024-03-15 | The Chosen Few    | W   | 0.020      | -            | -                | -                | -         |     0.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4710 | 2024-03-15 | Sampi             | L   | 0.019      | -            | -                | -                | -         |    -0.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|            3 |     4758 | 2024-03-13 | MOUZ NXT          | W   | 0.008      | -            | -                | -                | -         |     0.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     4775 | 2024-03-13 | ECLOT             | W   | 0.007      | -            | -                | -                | -         |     0.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4790 | 2024-03-13 | ECLOT             | W   | 0.006      | -            | -                | -                | -         |     0.12 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,603.41)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      0.981 | $5,000.00      | $4,904.86       |
| 2024-06-16 |      0.641 | $5,000.00      | $3,204.17       |
| 2024-06-13 |      0.622 | $545.00        | $338.76         |
| 2024-05-02 |      0.341 | $500.00        | $170.42         |
| 2024-04-25 |      0.292 | $3,000.00      | $875.83         |
| 2024-03-25 |      0.087 | $1,250.00      | $109.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
