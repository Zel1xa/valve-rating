### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  943.2<br />
<br />
Final Rank Value (943.2) = Starting Rank Value (945.5) + Head To Head Adjustments (-2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.430[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 945.5
- 400 + ( ( 0.266 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 945.5


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
|           98 |       65 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.316 (0.137)    | 0.722 (0.314)    | 0 (0.000) |    24.04 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      146 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.09 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      198 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.55 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      202 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.533 (0.231)    | 0 (0.000) |    17.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      246 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.77 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      269 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.22 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      290 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.86 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      341 | 2024-07-26 | Space             | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |    15.60 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      347 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.40 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      385 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      433 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.29 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      484 | 2024-07-22 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.50 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      557 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.562 (0.244)    | 0 (0.000) |    16.01 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      646 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.84 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      696 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.550 (0.239)    | 0 (0.000) |    12.73 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      775 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.79 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      806 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.30 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      834 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.66 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      899 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.173 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.82 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1027 | 2024-06-16 | 3DMAX             | L   | 0.866      | -            | -                | -                | -         |    -1.56 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1071 | 2024-06-15 | BIG               | W   | 0.858      | 0.435        | 0.154 (0.058)    | -                | -         |    23.87 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1108 | 2024-06-14 | PARIVISION        | W   | 0.852      | 0.435        | -                | 0.565 (0.209)    | -         |    19.01 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1122 | 2024-06-13 | 9INE              | L   | 0.847      | -            | -                | -                | -         |   -23.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1156 | 2024-06-12 | Nexus             | W   | 0.840      | -            | -                | -                | -         |     6.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1172 | 2024-06-11 | Nemiga            | L   | 0.834      | -            | -                | -                | -         |    -5.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           73 |     1197 | 2024-06-10 | Rebels            | L   | 0.827      | -            | -                | -                | -         |   -10.19 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1312 | 2024-06-08 | Space             | W   | 0.813      | -            | -                | -                | -         |    10.84 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           71 |     1443 | 2024-06-06 | Zero Tenacity     | W   | 0.799      | 0.435        | 0.143 (0.050)    | 1.000 (0.347)    | -         |    19.19 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           70 |     1578 | 2024-06-03 | GUN5              | W   | 0.778      | 0.435        | 0.073 (0.025)    | 0.562 (0.190)    | -         |    15.08 | bnox, Markoś, mASKED, morelz, tomiko  |
|           69 |     1636 | 2024-06-01 | Enterprise        | L   | 0.764      | -            | -                | -                | -         |   -11.83 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           68 |     1647 | 2024-05-31 | AMKAL             | L   | 0.760      | -            | -                | -                | -         |    -4.16 | bnox, mASKED, morelz, Sidney, tomiko  |
|           67 |     1680 | 2024-05-30 | NAVI Junior       | W   | 0.753      | -            | -                | -                | -         |     2.83 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1688 | 2024-05-30 | Serbia            | L   | 0.752      | -            | -                | -                | -         |   -16.23 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1733 | 2024-05-28 | Preasy            | W   | 0.738      | -            | -                | -                | -         |     7.40 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1735 | 2024-05-28 | GUN5              | W   | 0.738      | 0.435        | 0.073 (0.023)    | -                | -         |    12.23 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1753 | 2024-05-27 | VP.Prodigy        | L   | 0.733      | -            | -                | -                | -         |   -11.85 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1777 | 2024-05-26 | ECLOT             | W   | 0.724      | -            | -                | -                | -         |    18.12 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1792 | 2024-05-25 | Nexus             | W   | 0.719      | -            | -                | -                | -         |     7.94 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1862 | 2024-05-22 | Endpoint          | W   | 0.699      | -            | -                | -                | -         |    11.83 | bnox, maaryy, mASKED, morelz, tomiko  |
|           59 |     1876 | 2024-05-22 | Johnny Speeds     | L   | 0.698      | -            | -                | -                | -         |    -2.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1897 | 2024-05-21 | INFINITE          | W   | 0.694      | -            | -                | -                | -         |     2.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1950 | 2024-05-20 | Passion UA        | L   | 0.684      | -            | -                | -                | -         |    -6.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2042 | 2024-05-17 | Sangal            | L   | 0.664      | -            | -                | -                | -         |    -5.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2109 | 2024-05-15 | EYEBALLERS        | L   | 0.653      | -            | -                | -                | -         |   -10.92 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2194 | 2024-05-13 | 1WIN              | L   | 0.640      | -            | -                | -                | -         |    -8.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           53 |     2341 | 2024-05-07 | Enterprise        | L   | 0.598      | -            | -                | -                | -         |   -10.32 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2357 | 2024-05-06 | ENCE Academy      | W   | 0.591      | -            | -                | -                | -         |     4.70 | bnox, maaryy, mASKED, morelz, Sobol   |
|           51 |     2401 | 2024-05-03 | Insilio           | L   | 0.573      | -            | -                | -                | -         |    -8.64 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2428 | 2024-05-02 | Sampi             | L   | 0.566      | -            | -                | -                | -         |    -9.31 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           49 |     2440 | 2024-05-02 | B8                | L   | 0.564      | -            | -                | -                | -         |    -6.57 | bnox, maaryy, mASKED, morelz, Sobol   |
|           48 |     2488 | 2024-04-30 | BLEED             | L   | 0.551      | -            | -                | -                | -         |    -5.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2496 | 2024-04-29 | AMKAL             | L   | 0.546      | -            | -                | -                | -         |    -4.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           46 |     2505 | 2024-04-29 | RUBY              | W   | 0.544      | 0.435        | 0.095 (0.022)    | -                | -         |     8.22 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           45 |     2544 | 2024-04-27 | Insilio           | L   | 0.532      | -            | -                | -                | -         |    -9.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2550 | 2024-04-27 | Enterprise        | W   | 0.531      | -            | -                | -                | -         |     7.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2573 | 2024-04-26 | ARCRED            | L   | 0.525      | -            | -                | -                | -         |    -9.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2594 | 2024-04-25 | 1WIN              | L   | 0.519      | -            | -                | -                | -         |    -8.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2611 | 2024-04-24 | BLEED             | L   | 0.513      | -            | -                | -                | -         |    -6.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2616 | 2024-04-24 | Passion UA        | W   | 0.512      | 0.384        | 0.173 (0.034)    | 1.000 (0.197)    | -         |     9.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2622 | 2024-04-24 | Sampi             | L   | 0.511      | -            | -                | -                | -         |    -9.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2644 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.504      | -            | -                | -                | -         |     7.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2658 | 2024-04-22 | Grannys Knockers  | W   | 0.498      | -            | -                | -                | -         |     3.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2678 | 2024-04-21 | Insilio           | W   | 0.491      | -            | -                | -                | -         |     6.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2703 | 2024-04-20 | Nexus             | L   | 0.485      | -            | -                | -                | -         |   -10.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2708 | 2024-04-20 | Passion UA        | W   | 0.484      | 0.371        | 0.173 (0.031)    | -                | -         |     9.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2799 | 2024-04-18 | Passion UA        | L   | 0.472      | -            | -                | -                | -         |    -5.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2810 | 2024-04-18 | Sampi             | L   | 0.471      | -            | -                | -                | -         |    -8.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2828 | 2024-04-17 | PARIVISION        | W   | 0.466      | -            | -                | -                | -         |     9.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2868 | 2024-04-16 | Gaimin Gladiators | L   | 0.459      | -            | -                | -                | -         |    -6.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2930 | 2024-04-12 | MOUZ NXT          | W   | 0.432      | -            | -                | -                | -         |     8.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3011 | 2024-04-10 | EYEBALLERS        | W   | 0.418      | -            | -                | -                | -         |     5.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3087 | 2024-04-08 | HAVU              | W   | 0.406      | -            | -                | -                | -         |     2.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3098 | 2024-04-08 | JANO              | W   | 0.404      | -            | -                | -                | -         |     2.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3225 | 2024-04-03 | Enterprise        | L   | 0.373      | -            | -                | -                | -         |    -6.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3237 | 2024-04-03 | ECLOT             | L   | 0.372      | -            | -                | -                | -         |    -2.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3270 | 2024-04-02 | 3DMAX             | L   | 0.366      | -            | -                | -                | -         |    -0.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3279 | 2024-04-02 | Sashi             | L   | 0.364      | -            | -                | -                | -         |    -3.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3543 | 2024-03-16 | RUBY              | L   | 0.253      | -            | -                | -                | -         |    -4.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3563 | 2024-03-15 | The Chosen Few    | W   | 0.246      | -            | -                | -                | -         |     1.37 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3568 | 2024-03-15 | Sampi             | L   | 0.244      | -            | -                | -                | -         |    -4.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3616 | 2024-03-13 | MOUZ NXT          | W   | 0.234      | -            | -                | -                | -         |     4.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3633 | 2024-03-13 | ECLOT             | W   | 0.232      | -            | -                | -                | -         |     5.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3648 | 2024-03-13 | ECLOT             | W   | 0.231      | -            | -                | -                | -         |     5.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3689 | 2024-03-11 | ex-Preasy         | L   | 0.218      | -            | -                | -                | -         |    -4.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3734 | 2024-03-09 | Sashi             | L   | 0.205      | -            | -                | -                | -         |    -1.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3771 | 2024-03-07 | VP.Prodigy        | W   | 0.194      | -            | -                | -                | -         |     2.33 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3781 | 2024-03-07 | kONO              | W   | 0.191      | -            | -                | -                | -         |     1.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3808 | 2024-03-06 | Passion UA        | W   | 0.186      | -            | -                | -                | -         |     4.04 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3810 | 2024-03-06 | Enterprise        | W   | 0.185      | -            | -                | -                | -         |     2.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3850 | 2024-03-05 | Young Ninjas      | W   | 0.179      | -            | -                | -                | -         |     1.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3917 | 2024-03-02 | AURA              | W   | 0.158      | -            | -                | -                | -         |     0.37 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3961 | 2024-02-28 | Secret            | L   | 0.139      | -            | -                | -                | -         |    -3.98 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3965 | 2024-02-28 | ECLOT             | L   | 0.138      | -            | -                | -                | -         |    -0.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     3984 | 2024-02-27 | Sprout            | W   | 0.132      | -            | -                | -                | -         |     0.18 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4057 | 2024-02-24 | ECLOT             | W   | 0.112      | -            | -                | -                | -         |     2.89 | bnox, maaryy, mASKED, morelz, Vegi    |
|            3 |     4090 | 2024-02-22 | PGE Turow         | W   | 0.098      | -            | -                | -                | -         |     0.49 | bnox, maaryy, mASKED, morelz, reiko   |
|            2 |     4124 | 2024-02-21 | ECLOT             | L   | 0.091      | -            | -                | -                | -         |    -0.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4169 | 2024-02-19 | ECLOT             | W   | 0.079      | -            | -                | -                | -         |     2.04 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,570.64)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $5,000.00      | $4,331.94       |
| 2024-06-13 |      0.847 | $545.00        | $461.69         |
| 2024-05-02 |      0.566 | $500.00        | $283.19         |
| 2024-04-25 |      0.517 | $3,000.00      | $1,552.50       |
| 2024-03-25 |      0.313 | $1,250.00      | $391.32         |
| 2024-02-28 |      0.138 | $3,000.00      | $413.33         |
| 2024-02-21 |      0.091 | $1,500.00      | $136.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
