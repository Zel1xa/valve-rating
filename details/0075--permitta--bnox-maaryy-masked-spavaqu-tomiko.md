### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  939.3<br />
<br />
Final Rank Value (939.3) = Starting Rank Value (944.1) + Head To Head Adjustments (-4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.431[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.1
- 400 + ( ( 0.266 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 944.1


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
|           99 |       10 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.317 (0.138)    | 0.695 (0.302)    | 0 (0.000) |    23.80 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |       90 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.15 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      141 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.35 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      144 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.537 (0.233)    | 0 (0.000) |    17.62 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      188 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.87 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      212 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.33 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      233 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.94 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      284 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.55 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      291 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.57 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      328 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.71 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      376 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.50 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      427 | 2024-07-22 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.63 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      500 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    16.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      587 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.80 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      642 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.560 (0.244)    | 0 (0.000) |    12.59 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      718 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.88 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      749 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.11 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      777 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.73 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      842 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.172 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.54 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      970 | 2024-06-16 | 3DMAX             | L   | 0.874      | -            | -                | -                | -         |    -1.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1014 | 2024-06-15 | BIG               | W   | 0.866      | 0.435        | 0.155 (0.058)    | -                | -         |    24.15 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1051 | 2024-06-14 | PARIVISION        | W   | 0.860      | 0.435        | -                | 0.534 (0.200)    | -         |    19.07 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1065 | 2024-06-13 | 9INE              | L   | 0.856      | -            | -                | -                | -         |   -24.07 | bnox, maaryy, mASKED, morelz, Vegi    |
|           76 |     1099 | 2024-06-12 | Nexus             | W   | 0.849      | -            | -                | -                | -         |     6.71 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1115 | 2024-06-11 | Nemiga            | L   | 0.842      | -            | -                | -                | -         |    -5.77 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1140 | 2024-06-10 | Rebels            | L   | 0.836      | -            | -                | -                | -         |   -10.21 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           73 |     1255 | 2024-06-08 | Space             | W   | 0.822      | -            | -                | -                | -         |    11.29 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1386 | 2024-06-06 | Zero Tenacity     | W   | 0.808      | 0.435        | 0.137 (0.048)    | 1.000 (0.351)    | -         |    19.45 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           71 |     1521 | 2024-06-03 | GUN5              | W   | 0.787      | 0.435        | 0.073 (0.025)    | 0.570 (0.195)    | -         |    15.28 | bnox, Markoś, mASKED, morelz, tomiko  |
|           70 |     1579 | 2024-06-01 | Enterprise        | L   | 0.773      | -            | -                | -                | -         |   -11.93 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           69 |     1590 | 2024-05-31 | AMKAL             | L   | 0.769      | -            | -                | -                | -         |    -4.12 | bnox, mASKED, morelz, Sidney, tomiko  |
|           68 |     1623 | 2024-05-30 | NAVI Junior       | W   | 0.761      | -            | -                | -                | -         |     2.91 | bnox, maaryy, mASKED, morelz, tomiko  |
|           67 |     1631 | 2024-05-30 | Serbia            | L   | 0.760      | -            | -                | -                | -         |   -16.32 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1676 | 2024-05-28 | Preasy            | W   | 0.747      | -            | -                | -                | -         |     7.66 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1678 | 2024-05-28 | GUN5              | W   | 0.746      | 0.435        | 0.073 (0.024)    | 0.570 (0.185)    | -         |    12.43 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1696 | 2024-05-27 | VP.Prodigy        | L   | 0.741      | -            | -                | -                | -         |   -11.92 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1720 | 2024-05-26 | ECLOT             | W   | 0.733      | -            | -                | -                | -         |    18.32 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1735 | 2024-05-25 | Nexus             | W   | 0.727      | -            | -                | -                | -         |     8.12 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1805 | 2024-05-22 | Endpoint          | W   | 0.708      | -            | -                | -                | -         |    12.04 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1819 | 2024-05-22 | Johnny Speeds     | L   | 0.706      | -            | -                | -                | -         |    -2.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     1840 | 2024-05-21 | INFINITE          | W   | 0.702      | -            | -                | -                | -         |     2.93 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1893 | 2024-05-20 | Passion UA        | L   | 0.693      | -            | -                | -                | -         |    -6.92 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1985 | 2024-05-17 | Sangal            | L   | 0.673      | -            | -                | -                | -         |    -5.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2052 | 2024-05-15 | EYEBALLERS        | L   | 0.662      | -            | -                | -                | -         |   -10.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2137 | 2024-05-13 | 1WIN              | L   | 0.649      | -            | -                | -                | -         |    -9.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2284 | 2024-05-07 | Enterprise        | L   | 0.607      | -            | -                | -                | -         |   -10.42 | bnox, maaryy, mASKED, morelz, Sobol   |
|           53 |     2300 | 2024-05-06 | ENCE Academy      | W   | 0.600      | -            | -                | -                | -         |     4.81 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2344 | 2024-05-03 | Insilio           | L   | 0.581      | -            | -                | -                | -         |    -8.74 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           51 |     2371 | 2024-05-02 | Sampi             | L   | 0.575      | -            | -                | -                | -         |    -9.37 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2383 | 2024-05-02 | B8                | L   | 0.573      | -            | -                | -                | -         |    -6.66 | bnox, maaryy, mASKED, morelz, Sobol   |
|           49 |     2431 | 2024-04-30 | BLEED             | L   | 0.560      | -            | -                | -                | -         |    -5.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     2439 | 2024-04-29 | AMKAL             | L   | 0.554      | -            | -                | -                | -         |    -4.55 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2448 | 2024-04-29 | RUBY              | W   | 0.553      | 0.435        | 0.095 (0.023)    | -                | -         |     8.52 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           46 |     2487 | 2024-04-27 | Insilio           | L   | 0.541      | -            | -                | -                | -         |    -9.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     2493 | 2024-04-27 | Enterprise        | W   | 0.540      | -            | -                | -                | -         |     7.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2516 | 2024-04-26 | ARCRED            | L   | 0.533      | -            | -                | -                | -         |   -10.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2537 | 2024-04-25 | 1WIN              | L   | 0.528      | -            | -                | -                | -         |    -9.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2554 | 2024-04-24 | BLEED             | L   | 0.522      | -            | -                | -                | -         |    -6.30 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2559 | 2024-04-24 | Passion UA        | W   | 0.521      | 0.384        | 0.172 (0.034)    | 1.000 (0.200)    | -         |     9.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2565 | 2024-04-24 | Sampi             | L   | 0.519      | -            | -                | -                | -         |    -9.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2587 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.512      | -            | -                | -                | -         |     7.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2601 | 2024-04-22 | Grannys Knockers  | W   | 0.506      | -            | -                | -                | -         |     3.77 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2621 | 2024-04-21 | Insilio           | W   | 0.499      | -            | -                | -                | -         |     6.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2646 | 2024-04-20 | Nexus             | L   | 0.494      | -            | -                | -                | -         |   -10.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2651 | 2024-04-20 | Passion UA        | W   | 0.493      | 0.371        | 0.172 (0.031)    | -                | -         |     9.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2742 | 2024-04-18 | Passion UA        | L   | 0.481      | -            | -                | -                | -         |    -5.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2753 | 2024-04-18 | Sampi             | L   | 0.479      | -            | -                | -                | -         |    -8.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2771 | 2024-04-17 | PARIVISION        | W   | 0.475      | -            | -                | -                | -         |     9.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2811 | 2024-04-16 | Gaimin Gladiators | L   | 0.467      | -            | -                | -                | -         |    -6.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2873 | 2024-04-12 | MOUZ NXT          | W   | 0.440      | -            | -                | -                | -         |     8.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2954 | 2024-04-10 | EYEBALLERS        | W   | 0.426      | -            | -                | -                | -         |     5.64 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3030 | 2024-04-08 | HAVU              | W   | 0.414      | -            | -                | -                | -         |     2.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3041 | 2024-04-08 | JANO              | W   | 0.413      | -            | -                | -                | -         |     2.30 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3168 | 2024-04-03 | Enterprise        | L   | 0.382      | -            | -                | -                | -         |    -6.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3180 | 2024-04-03 | ECLOT             | L   | 0.380      | -            | -                | -                | -         |    -2.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3213 | 2024-04-02 | 3DMAX             | L   | 0.374      | -            | -                | -                | -         |    -0.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3222 | 2024-04-02 | Sashi             | L   | 0.373      | -            | -                | -                | -         |    -3.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3486 | 2024-03-16 | RUBY              | L   | 0.262      | -            | -                | -                | -         |    -4.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3506 | 2024-03-15 | The Chosen Few    | W   | 0.254      | -            | -                | -                | -         |     1.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3511 | 2024-03-15 | Sampi             | L   | 0.253      | -            | -                | -                | -         |    -4.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3559 | 2024-03-13 | MOUZ NXT          | W   | 0.243      | -            | -                | -                | -         |     4.64 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3576 | 2024-03-13 | ECLOT             | W   | 0.241      | -            | -                | -                | -         |     6.03 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3591 | 2024-03-13 | ECLOT             | W   | 0.240      | -            | -                | -                | -         |     6.09 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3632 | 2024-03-11 | ex-Preasy         | L   | 0.227      | -            | -                | -                | -         |    -5.06 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3677 | 2024-03-09 | Sashi             | L   | 0.214      | -            | -                | -                | -         |    -1.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3714 | 2024-03-07 | VP.Prodigy        | W   | 0.202      | -            | -                | -                | -         |     2.44 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3724 | 2024-03-07 | kONO              | W   | 0.200      | -            | -                | -                | -         |     1.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3751 | 2024-03-06 | Passion UA        | W   | 0.194      | -            | -                | -                | -         |     4.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3753 | 2024-03-06 | Enterprise        | W   | 0.194      | -            | -                | -                | -         |     2.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3793 | 2024-03-05 | Young Ninjas      | W   | 0.188      | -            | -                | -                | -         |     1.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3860 | 2024-03-02 | AURA              | W   | 0.167      | -            | -                | -                | -         |     0.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3904 | 2024-02-28 | Secret            | L   | 0.147      | -            | -                | -                | -         |    -4.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3908 | 2024-02-28 | ECLOT             | L   | 0.146      | -            | -                | -                | -         |    -0.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3927 | 2024-02-27 | Sprout            | W   | 0.140      | -            | -                | -                | -         |     0.20 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     4000 | 2024-02-24 | ECLOT             | W   | 0.120      | -            | -                | -                | -         |     3.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4033 | 2024-02-22 | PGE Turow         | W   | 0.106      | -            | -                | -                | -         |     0.54 | bnox, maaryy, mASKED, morelz, reiko   |
|            3 |     4067 | 2024-02-21 | ECLOT             | L   | 0.100      | -            | -                | -                | -         |    -0.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     4112 | 2024-02-19 | ECLOT             | W   | 0.087      | -            | -                | -                | -         |     2.26 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4349 | 2024-02-07 | Endpoint          | L   | 0.007      | -            | -                | -                | -         |    -0.13 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,698.05)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.875 | $5,000.00      | $4,375.00       |
| 2024-06-13 |      0.856 | $545.00        | $466.38         |
| 2024-05-02 |      0.575 | $500.00        | $287.50         |
| 2024-04-25 |      0.526 | $3,000.00      | $1,578.33       |
| 2024-03-25 |      0.322 | $1,250.00      | $402.08         |
| 2024-02-28 |      0.146 | $3,000.00      | $439.17         |
| 2024-02-21 |      0.100 | $1,500.00      | $149.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
