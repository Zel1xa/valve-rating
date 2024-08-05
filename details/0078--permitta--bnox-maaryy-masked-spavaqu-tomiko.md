### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.5<br />
<br />
Final Rank Value (942.5) = Starting Rank Value (945.0) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.430[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 945.0
- 400 + ( ( 0.266 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 945.0


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
|           98 |       57 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.316 (0.137)    | 0.731 (0.318)    | 0 (0.000) |    24.04 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      138 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.10 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      190 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.54 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      194 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.539 (0.234)    | 0 (0.000) |    17.60 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      238 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.81 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      261 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.24 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      282 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.82 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      333 | 2024-07-26 | Space             | W   | 1.000      | 0.435        | -                | 0.445 (0.193)    | 0 (0.000) |    15.64 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      339 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.40 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      377 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.58 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      425 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.28 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      476 | 2024-07-22 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.53 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      549 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.569 (0.247)    | 0 (0.000) |    16.01 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      638 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.83 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      688 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.557 (0.242)    | 0 (0.000) |    12.73 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      767 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.67 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      798 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.25 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      826 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.74 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      891 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.173 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.76 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1019 | 2024-06-16 | 3DMAX             | L   | 0.867      | -            | -                | -                | -         |    -1.56 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1063 | 2024-06-15 | BIG               | W   | 0.859      | 0.435        | 0.155 (0.058)    | -                | -         |    23.92 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1100 | 2024-06-14 | PARIVISION        | W   | 0.853      | 0.435        | -                | 0.532 (0.197)    | -         |    19.00 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1114 | 2024-06-13 | 9INE              | L   | 0.848      | -            | -                | -                | -         |   -23.89 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1148 | 2024-06-12 | Nexus             | W   | 0.841      | -            | -                | -                | -         |     6.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1164 | 2024-06-11 | Nemiga            | L   | 0.835      | -            | -                | -                | -         |    -5.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|           73 |     1189 | 2024-06-10 | Rebels            | L   | 0.828      | -            | -                | -                | -         |   -10.16 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1304 | 2024-06-08 | Space             | W   | 0.814      | -            | -                | -                | -         |    10.90 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           71 |     1435 | 2024-06-06 | Zero Tenacity     | W   | 0.800      | 0.435        | 0.137 (0.048)    | 1.000 (0.348)    | -         |    19.23 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           70 |     1570 | 2024-06-03 | GUN5              | W   | 0.779      | 0.435        | 0.073 (0.025)    | 0.569 (0.193)    | -         |    15.11 | bnox, Markoś, mASKED, morelz, tomiko  |
|           69 |     1628 | 2024-06-01 | Enterprise        | L   | 0.765      | -            | -                | -                | -         |   -11.88 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           68 |     1639 | 2024-05-31 | AMKAL             | L   | 0.762      | -            | -                | -                | -         |    -4.14 | bnox, mASKED, morelz, Sidney, tomiko  |
|           67 |     1672 | 2024-05-30 | NAVI Junior       | W   | 0.754      | -            | -                | -                | -         |     2.85 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1680 | 2024-05-30 | Serbia            | L   | 0.753      | -            | -                | -                | -         |   -16.22 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1725 | 2024-05-28 | Preasy            | W   | 0.739      | -            | -                | -                | -         |     7.55 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1727 | 2024-05-28 | GUN5              | W   | 0.739      | 0.435        | 0.073 (0.023)    | -                | -         |    12.27 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1745 | 2024-05-27 | VP.Prodigy        | L   | 0.734      | -            | -                | -                | -         |   -11.84 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1769 | 2024-05-26 | ECLOT             | W   | 0.725      | -            | -                | -                | -         |    18.16 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1784 | 2024-05-25 | Nexus             | W   | 0.720      | -            | -                | -                | -         |     7.98 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1854 | 2024-05-22 | Endpoint          | W   | 0.701      | -            | -                | -                | -         |    11.88 | bnox, maaryy, mASKED, morelz, tomiko  |
|           59 |     1868 | 2024-05-22 | Johnny Speeds     | L   | 0.699      | -            | -                | -                | -         |    -2.33 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1889 | 2024-05-21 | INFINITE          | W   | 0.695      | -            | -                | -                | -         |     2.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1942 | 2024-05-20 | Passion UA        | L   | 0.686      | -            | -                | -                | -         |    -6.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2034 | 2024-05-17 | Sangal            | L   | 0.665      | -            | -                | -                | -         |    -5.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2101 | 2024-05-15 | EYEBALLERS        | L   | 0.655      | -            | -                | -                | -         |   -10.92 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2186 | 2024-05-13 | 1WIN              | L   | 0.641      | -            | -                | -                | -         |    -8.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           53 |     2333 | 2024-05-07 | Enterprise        | L   | 0.599      | -            | -                | -                | -         |   -10.32 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2349 | 2024-05-06 | ENCE Academy      | W   | 0.593      | -            | -                | -                | -         |     4.73 | bnox, maaryy, mASKED, morelz, Sobol   |
|           51 |     2393 | 2024-05-03 | Insilio           | L   | 0.574      | -            | -                | -                | -         |    -8.65 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2420 | 2024-05-02 | Sampi             | L   | 0.567      | -            | -                | -                | -         |    -9.29 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           49 |     2432 | 2024-05-02 | B8                | L   | 0.566      | -            | -                | -                | -         |    -6.56 | bnox, maaryy, mASKED, morelz, Sobol   |
|           48 |     2480 | 2024-04-30 | BLEED             | L   | 0.552      | -            | -                | -                | -         |    -5.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2488 | 2024-04-29 | AMKAL             | L   | 0.547      | -            | -                | -                | -         |    -4.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           46 |     2497 | 2024-04-29 | RUBY              | W   | 0.546      | 0.435        | 0.095 (0.023)    | -                | -         |     8.24 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           45 |     2536 | 2024-04-27 | Insilio           | L   | 0.533      | -            | -                | -                | -         |    -9.13 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2542 | 2024-04-27 | Enterprise        | W   | 0.532      | -            | -                | -                | -         |     7.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2565 | 2024-04-26 | ARCRED            | L   | 0.526      | -            | -                | -                | -         |   -10.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2586 | 2024-04-25 | 1WIN              | L   | 0.521      | -            | -                | -                | -         |    -8.46 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2603 | 2024-04-24 | BLEED             | L   | 0.514      | -            | -                | -                | -         |    -6.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2608 | 2024-04-24 | Passion UA        | W   | 0.514      | 0.384        | 0.173 (0.034)    | 1.000 (0.197)    | -         |     9.46 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2614 | 2024-04-24 | Sampi             | L   | 0.512      | -            | -                | -                | -         |    -9.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2636 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.505      | -            | -                | -                | -         |     7.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2650 | 2024-04-22 | Grannys Knockers  | W   | 0.499      | -            | -                | -                | -         |     3.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2670 | 2024-04-21 | Insilio           | W   | 0.492      | -            | -                | -                | -         |     6.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2695 | 2024-04-20 | Nexus             | L   | 0.486      | -            | -                | -                | -         |   -10.03 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2700 | 2024-04-20 | Passion UA        | W   | 0.485      | 0.371        | 0.173 (0.031)    | -                | -         |     9.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2791 | 2024-04-18 | Passion UA        | L   | 0.473      | -            | -                | -                | -         |    -5.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2802 | 2024-04-18 | Sampi             | L   | 0.472      | -            | -                | -                | -         |    -8.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2820 | 2024-04-17 | PARIVISION        | W   | 0.467      | -            | -                | -                | -         |     9.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2860 | 2024-04-16 | Gaimin Gladiators | L   | 0.460      | -            | -                | -                | -         |    -6.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2922 | 2024-04-12 | MOUZ NXT          | W   | 0.433      | -            | -                | -                | -         |     8.60 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3003 | 2024-04-10 | EYEBALLERS        | W   | 0.419      | -            | -                | -                | -         |     5.50 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3079 | 2024-04-08 | HAVU              | W   | 0.407      | -            | -                | -                | -         |     2.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3090 | 2024-04-08 | JANO              | W   | 0.405      | -            | -                | -                | -         |     2.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3217 | 2024-04-03 | Enterprise        | L   | 0.374      | -            | -                | -                | -         |    -6.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3229 | 2024-04-03 | ECLOT             | L   | 0.373      | -            | -                | -                | -         |    -2.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3262 | 2024-04-02 | 3DMAX             | L   | 0.367      | -            | -                | -                | -         |    -0.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3271 | 2024-04-02 | Sashi             | L   | 0.365      | -            | -                | -                | -         |    -3.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3535 | 2024-03-16 | RUBY              | L   | 0.254      | -            | -                | -                | -         |    -4.46 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3555 | 2024-03-15 | The Chosen Few    | W   | 0.247      | -            | -                | -                | -         |     1.37 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3560 | 2024-03-15 | Sampi             | L   | 0.246      | -            | -                | -                | -         |    -4.64 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3608 | 2024-03-13 | MOUZ NXT          | W   | 0.235      | -            | -                | -                | -         |     4.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3625 | 2024-03-13 | ECLOT             | W   | 0.233      | -            | -                | -                | -         |     5.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3640 | 2024-03-13 | ECLOT             | W   | 0.232      | -            | -                | -                | -         |     5.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3681 | 2024-03-11 | ex-Preasy         | L   | 0.220      | -            | -                | -                | -         |    -4.92 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3726 | 2024-03-09 | Sashi             | L   | 0.206      | -            | -                | -                | -         |    -1.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3763 | 2024-03-07 | VP.Prodigy        | W   | 0.195      | -            | -                | -                | -         |     2.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3773 | 2024-03-07 | kONO              | W   | 0.193      | -            | -                | -                | -         |     1.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3800 | 2024-03-06 | Passion UA        | W   | 0.187      | -            | -                | -                | -         |     4.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3802 | 2024-03-06 | Enterprise        | W   | 0.186      | -            | -                | -                | -         |     2.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3842 | 2024-03-05 | Young Ninjas      | W   | 0.180      | -            | -                | -                | -         |     1.50 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3909 | 2024-03-02 | AURA              | W   | 0.160      | -            | -                | -                | -         |     0.37 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3953 | 2024-02-28 | Secret            | L   | 0.140      | -            | -                | -                | -         |    -4.01 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3957 | 2024-02-28 | ECLOT             | L   | 0.139      | -            | -                | -                | -         |    -0.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     3976 | 2024-02-27 | Sprout            | W   | 0.133      | -            | -                | -                | -         |     0.18 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4049 | 2024-02-24 | ECLOT             | W   | 0.113      | -            | -                | -                | -         |     2.92 | bnox, maaryy, mASKED, morelz, Vegi    |
|            3 |     4082 | 2024-02-22 | PGE Turow         | W   | 0.099      | -            | -                | -                | -         |     0.50 | bnox, maaryy, mASKED, morelz, reiko   |
|            2 |     4116 | 2024-02-21 | ECLOT             | L   | 0.092      | -            | -                | -                | -         |    -0.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4161 | 2024-02-19 | ECLOT             | W   | 0.080      | -            | -                | -                | -         |     2.07 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,587.08)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.868 | $5,000.00      | $4,337.50       |
| 2024-06-13 |      0.848 | $545.00        | $462.29         |
| 2024-05-02 |      0.568 | $500.00        | $283.75         |
| 2024-04-25 |      0.519 | $3,000.00      | $1,555.83       |
| 2024-03-25 |      0.314 | $1,250.00      | $392.71         |
| 2024-02-28 |      0.139 | $3,000.00      | $416.67         |
| 2024-02-21 |      0.092 | $1,500.00      | $138.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
