### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.2<br />
<br />
Final Rank Value (945.2) = Starting Rank Value (944.0) + Head To Head Adjustments (1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.431[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.0
- 400 + ( ( 0.266 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 944.0


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
|           99 |       18 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.317 (0.138)    | 0.695 (0.302)    | 0 (0.000) |    23.64 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |       98 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.04 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      149 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.56 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      151 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.537 (0.233)    | 0 (0.000) |    17.42 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      196 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -9.08 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      220 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      241 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.98 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      292 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.52 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      299 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.56 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      336 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.74 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      384 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.53 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      435 | 2024-07-22 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.91 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      508 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    16.12 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      595 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.81 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      650 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.560 (0.243)    | 0 (0.000) |    12.58 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      726 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.87 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      757 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      785 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.69 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      850 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.172 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.56 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      978 | 2024-06-16 | 3DMAX             | L   | 0.874      | -            | -                | -                | -         |    -1.60 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1022 | 2024-06-15 | BIG               | W   | 0.865      | 0.435        | 0.155 (0.058)    | -                | -         |    24.13 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1059 | 2024-06-14 | PARIVISION        | W   | 0.860      | 0.435        | -                | 0.534 (0.200)    | -         |    19.05 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1073 | 2024-06-13 | 9INE              | L   | 0.855      | -            | -                | -                | -         |   -24.06 | bnox, maaryy, mASKED, morelz, Vegi    |
|           76 |     1107 | 2024-06-12 | Nexus             | W   | 0.848      | -            | -                | -                | -         |     6.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1123 | 2024-06-11 | Nemiga            | L   | 0.842      | -            | -                | -                | -         |    -5.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1148 | 2024-06-10 | Rebels            | L   | 0.835      | -            | -                | -                | -         |   -10.22 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           73 |     1263 | 2024-06-08 | Space             | W   | 0.821      | -            | -                | -                | -         |    11.25 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1394 | 2024-06-06 | Zero Tenacity     | W   | 0.807      | 0.435        | 0.137 (0.048)    | 1.000 (0.351)    | -         |    19.43 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           71 |     1529 | 2024-06-03 | GUN5              | W   | 0.786      | 0.435        | 0.073 (0.025)    | 0.570 (0.195)    | -         |    15.24 | bnox, Markoś, mASKED, morelz, tomiko  |
|           70 |     1587 | 2024-06-01 | Enterprise        | L   | 0.772      | -            | -                | -                | -         |   -11.95 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           69 |     1598 | 2024-05-31 | AMKAL             | L   | 0.768      | -            | -                | -                | -         |    -4.12 | bnox, mASKED, morelz, Sidney, tomiko  |
|           68 |     1631 | 2024-05-30 | NAVI Junior       | W   | 0.761      | -            | -                | -                | -         |     2.89 | bnox, maaryy, mASKED, morelz, tomiko  |
|           67 |     1639 | 2024-05-30 | Serbia            | L   | 0.759      | -            | -                | -                | -         |   -16.33 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1684 | 2024-05-28 | Preasy            | W   | 0.746      | -            | -                | -                | -         |     7.63 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1686 | 2024-05-28 | GUN5              | W   | 0.746      | 0.435        | 0.073 (0.024)    | 0.570 (0.185)    | -         |    12.39 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1704 | 2024-05-27 | VP.Prodigy        | L   | 0.741      | -            | -                | -                | -         |   -11.93 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1728 | 2024-05-26 | ECLOT             | W   | 0.732      | -            | -                | -                | -         |    18.30 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1743 | 2024-05-25 | Nexus             | W   | 0.727      | -            | -                | -                | -         |     8.08 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1813 | 2024-05-22 | Endpoint          | W   | 0.707      | -            | -                | -                | -         |    11.99 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1827 | 2024-05-22 | Johnny Speeds     | L   | 0.705      | -            | -                | -                | -         |    -2.44 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     1848 | 2024-05-21 | INFINITE          | W   | 0.702      | -            | -                | -                | -         |     2.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1901 | 2024-05-20 | Passion UA        | L   | 0.692      | -            | -                | -                | -         |    -6.92 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1993 | 2024-05-17 | Sangal            | L   | 0.672      | -            | -                | -                | -         |    -5.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2060 | 2024-05-15 | EYEBALLERS        | L   | 0.661      | -            | -                | -                | -         |   -10.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2145 | 2024-05-13 | 1WIN              | L   | 0.648      | -            | -                | -                | -         |    -8.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2292 | 2024-05-07 | Enterprise        | L   | 0.606      | -            | -                | -                | -         |   -10.43 | bnox, maaryy, mASKED, morelz, Sobol   |
|           53 |     2308 | 2024-05-06 | ENCE Academy      | W   | 0.599      | -            | -                | -                | -         |     4.79 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2352 | 2024-05-03 | Insilio           | L   | 0.581      | -            | -                | -                | -         |    -8.71 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           51 |     2379 | 2024-05-02 | Sampi             | L   | 0.574      | -            | -                | -                | -         |    -9.36 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2391 | 2024-05-02 | B8                | L   | 0.572      | -            | -                | -                | -         |    -6.66 | bnox, maaryy, mASKED, morelz, Sobol   |
|           49 |     2439 | 2024-04-30 | BLEED             | L   | 0.559      | -            | -                | -                | -         |    -5.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     2447 | 2024-04-29 | AMKAL             | L   | 0.554      | -            | -                | -                | -         |    -4.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2456 | 2024-04-29 | RUBY              | W   | 0.552      | 0.435        | 0.095 (0.023)    | -                | -         |     8.49 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           46 |     2495 | 2024-04-27 | Insilio           | L   | 0.540      | -            | -                | -                | -         |    -9.21 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     2501 | 2024-04-27 | Enterprise        | W   | 0.539      | -            | -                | -                | -         |     7.21 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2524 | 2024-04-26 | ARCRED            | L   | 0.533      | -            | -                | -                | -         |   -10.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2545 | 2024-04-25 | 1WIN              | L   | 0.527      | -            | -                | -                | -         |    -8.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2562 | 2024-04-24 | BLEED             | L   | 0.521      | -            | -                | -                | -         |    -6.30 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2567 | 2024-04-24 | Passion UA        | W   | 0.520      | 0.384        | 0.172 (0.034)    | 1.000 (0.200)    | -         |     9.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2573 | 2024-04-24 | Sampi             | L   | 0.519      | -            | -                | -                | -         |    -9.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2595 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.512      | -            | -                | -                | -         |     7.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2609 | 2024-04-22 | Grannys Knockers  | W   | 0.506      | -            | -                | -                | -         |     3.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2629 | 2024-04-21 | Insilio           | W   | 0.499      | -            | -                | -                | -         |     6.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2654 | 2024-04-20 | Nexus             | L   | 0.493      | -            | -                | -                | -         |   -10.18 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2659 | 2024-04-20 | Passion UA        | W   | 0.492      | 0.371        | 0.172 (0.031)    | -                | -         |     9.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2750 | 2024-04-18 | Passion UA        | L   | 0.480      | -            | -                | -                | -         |    -5.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2761 | 2024-04-18 | Sampi             | L   | 0.479      | -            | -                | -                | -         |    -8.71 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2779 | 2024-04-17 | PARIVISION        | W   | 0.474      | -            | -                | -                | -         |     9.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2819 | 2024-04-16 | Gaimin Gladiators | L   | 0.467      | -            | -                | -                | -         |    -6.60 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2881 | 2024-04-12 | MOUZ NXT          | W   | 0.439      | -            | -                | -                | -         |     8.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2962 | 2024-04-10 | EYEBALLERS        | W   | 0.426      | -            | -                | -                | -         |     5.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3038 | 2024-04-08 | HAVU              | W   | 0.413      | -            | -                | -                | -         |     2.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3049 | 2024-04-08 | JANO              | W   | 0.412      | -            | -                | -                | -         |     2.30 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3176 | 2024-04-03 | Enterprise        | L   | 0.381      | -            | -                | -                | -         |    -6.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3188 | 2024-04-03 | ECLOT             | L   | 0.379      | -            | -                | -                | -         |    -2.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3221 | 2024-04-02 | 3DMAX             | L   | 0.373      | -            | -                | -                | -         |    -0.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3230 | 2024-04-02 | Sashi             | L   | 0.372      | -            | -                | -                | -         |    -3.33 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3494 | 2024-03-16 | RUBY              | L   | 0.261      | -            | -                | -                | -         |    -4.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3514 | 2024-03-15 | The Chosen Few    | W   | 0.254      | -            | -                | -                | -         |     1.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3519 | 2024-03-15 | Sampi             | L   | 0.252      | -            | -                | -                | -         |    -4.75 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3567 | 2024-03-13 | MOUZ NXT          | W   | 0.242      | -            | -                | -                | -         |     4.64 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3584 | 2024-03-13 | ECLOT             | W   | 0.240      | -            | -                | -                | -         |     6.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3599 | 2024-03-13 | ECLOT             | W   | 0.239      | -            | -                | -                | -         |     6.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3640 | 2024-03-11 | ex-Preasy         | L   | 0.226      | -            | -                | -                | -         |    -5.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3685 | 2024-03-09 | Sashi             | L   | 0.213      | -            | -                | -                | -         |    -1.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3722 | 2024-03-07 | VP.Prodigy        | W   | 0.202      | -            | -                | -                | -         |     2.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3732 | 2024-03-07 | kONO              | W   | 0.199      | -            | -                | -                | -         |     1.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3759 | 2024-03-06 | Passion UA        | W   | 0.194      | -            | -                | -                | -         |     4.18 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3761 | 2024-03-06 | Enterprise        | W   | 0.193      | -            | -                | -                | -         |     2.81 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3801 | 2024-03-05 | Young Ninjas      | W   | 0.187      | -            | -                | -                | -         |     1.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3868 | 2024-03-02 | AURA              | W   | 0.166      | -            | -                | -                | -         |     0.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3912 | 2024-02-28 | Secret            | L   | 0.147      | -            | -                | -                | -         |    -4.20 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3916 | 2024-02-28 | ECLOT             | L   | 0.146      | -            | -                | -                | -         |    -0.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3935 | 2024-02-27 | Sprout            | W   | 0.140      | -            | -                | -                | -         |     0.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     4008 | 2024-02-24 | ECLOT             | W   | 0.120      | -            | -                | -                | -         |     3.10 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4041 | 2024-02-22 | PGE Turow         | W   | 0.106      | -            | -                | -                | -         |     0.54 | bnox, maaryy, mASKED, morelz, reiko   |
|            3 |     4075 | 2024-02-21 | ECLOT             | L   | 0.099      | -            | -                | -                | -         |    -0.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     4120 | 2024-02-19 | ECLOT             | W   | 0.087      | -            | -                | -                | -         |     2.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4357 | 2024-02-07 | Endpoint          | L   | 0.006      | -            | -                | -                | -         |    -0.11 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,687.43)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $5,000.00      | $4,371.41       |
| 2024-06-13 |      0.855 | $545.00        | $465.99         |
| 2024-05-02 |      0.574 | $500.00        | $287.14         |
| 2024-04-25 |      0.525 | $3,000.00      | $1,576.18       |
| 2024-03-25 |      0.321 | $1,250.00      | $401.19         |
| 2024-02-28 |      0.146 | $3,000.00      | $437.01         |
| 2024-02-21 |      0.099 | $1,500.00      | $148.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
