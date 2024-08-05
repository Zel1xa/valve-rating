### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1184.5<br />
<br />
Final Rank Value (1184.5) = Starting Rank Value (1171.5) + Head To Head Adjustments (13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.577[<sup>1</sup>](#table2)
- Bounty Collected: 0.467[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.210[<sup>2</sup>](#table1)

The average of these factors is 0.374<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1171.5
- 400 + ( ( 0.374 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1171.5


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
|           99 |       19 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.554 (0.277)    | 0 (0.000) |     6.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           98 |       50 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.513 (0.257)    | 0 (0.000) |     3.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           97 |       62 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |      243 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.613 (0.306)    | 0 (0.000) |    10.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |      464 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      474 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.030 (0.030)    | -                | 1 (1.000) |     1.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      544 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      671 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      680 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      697 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.523 (0.187)    | 0 (0.000) |     4.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      721 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -14.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      724 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.487 (0.174)    | 0 (0.000) |     5.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      928 | 2024-06-14 | 3DMAX             | L   | 0.885      | -            | -                | -                | -         |    -6.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      963 | 2024-06-13 | Sampi             | W   | 0.878      | -            | -                | -                | 0 (0.000) |     3.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      980 | 2024-06-12 | CPH Wolves        | W   | 0.872      | -            | -                | -                | 0 (0.000) |     2.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      989 | 2024-06-12 | Astralis Talent   | W   | 0.872      | -            | -                | -                | -         |     1.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |     1245 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.833      | -            | -                | -                | -         |    -3.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1281 | 2024-06-06 | HEROIC            | L   | 0.831      | -            | -                | -                | -         |    -3.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1310 | 2024-06-05 | ENCE              | L   | 0.826      | -            | -                | -                | -         |    -8.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1330 | 2024-06-05 | Astralis          | W   | 0.825      | 0.715        | 0.394 (0.233)    | 0.386 (0.228)    | 1 (0.825) |    24.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1340 | 2024-06-05 | The MongolZ       | L   | 0.824      | -            | -                | -                | -         |    -0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1775 | 2024-05-20 | Monte             | L   | 0.717      | -            | -                | -                | -         |   -16.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1788 | 2024-05-19 | Passion UA        | W   | 0.712      | 0.500        | 0.171 (0.061)    | 1.000 (0.356)    | -         |     5.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1815 | 2024-05-18 | B8                | L   | 0.706      | -            | -                | -                | -         |   -13.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1824 | 2024-05-18 | Monte             | W   | 0.705      | -            | -                | -                | -         |     5.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1832 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.704      | 0.500        | -                | 0.564 (0.199)    | -         |     3.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1863 | 2024-05-17 | ex-Guild Eagles   | W   | 0.697      | -            | -                | -                | -         |     2.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1903 | 2024-05-16 | Passion UA        | L   | 0.690      | -            | -                | -                | -         |   -16.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1950 | 2024-05-15 | Endpoint          | W   | 0.684      | -            | -                | -                | -         |     3.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     2122 | 2024-05-09 | 1WIN              | W   | 0.644      | -            | -                | -                | -         |     3.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2145 | 2024-05-08 | Grannys Knockers  | W   | 0.638      | -            | -                | -                | -         |     1.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2163 | 2024-05-07 | 9 Pandas          | W   | 0.631      | -            | -                | -                | -         |     4.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2177 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.625      | -            | -                | -                | -         |     4.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2191 | 2024-05-05 | Gaimin Gladiators | L   | 0.619      | -            | -                | -                | -         |   -14.76 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           65 |     2199 | 2024-05-05 | Come on now dawg  | W   | 0.618      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2251 | 2024-05-02 | fnatic            | W   | 0.599      | 0.384        | 0.371 (0.085)    | -                | -         |    16.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2286 | 2024-05-01 | 3DMAX             | W   | 0.591      | 0.384        | 0.499 (0.113)    | 1.000 (0.227)    | -         |    17.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2303 | 2024-04-30 | OG                | W   | 0.585      | 0.384        | 0.143 (0.032)    | -                | -         |     6.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2328 | 2024-04-29 | 500               | W   | 0.577      | -            | -                | -                | -         |     1.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           60 |     2356 | 2024-04-27 | 777               | W   | 0.566      | -            | -                | -                | -         |     1.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2360 | 2024-04-27 | JANO              | W   | 0.566      | -            | -                | -                | -         |     1.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2427 | 2024-04-25 | Passion UA        | W   | 0.551      | 0.384        | 0.171 (0.036)    | 1.000 (0.212)    | -         |     4.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2461 | 2024-04-23 | Gaimin Gladiators | W   | 0.538      | -            | -                | -                | -         |     5.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2466 | 2024-04-23 | BLEED             | W   | 0.537      | -            | -                | -                | -         |     6.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2517 | 2024-04-20 | Eternal Fire      | W   | 0.519      | 0.143        | 0.752 (0.056)    | -                | -         |    15.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2524 | 2024-04-20 | Cloud9            | W   | 0.518      | -            | -                | -                | -         |     7.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2563 | 2024-04-19 | Eternal Fire      | L   | 0.512      | -            | -                | -                | -         |    -0.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2572 | 2024-04-19 | Cloud9            | W   | 0.511      | -            | -                | -                | -         |     7.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2598 | 2024-04-18 | ex-Guild Eagles   | W   | 0.506      | -            | -                | -                | -         |     2.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2602 | 2024-04-18 | RUBY              | W   | 0.506      | -            | -                | -                | -         |     4.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2611 | 2024-04-18 | GamerLegion       | W   | 0.505      | -            | -                | -                | -         |     8.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2655 | 2024-04-17 | Passion UA        | L   | 0.498      | -            | -                | -                | -         |    -9.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2692 | 2024-04-16 | ex-Guild Eagles   | L   | 0.491      | -            | -                | -                | -         |   -13.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2713 | 2024-04-15 | ex-Preasy         | W   | 0.484      | -            | -                | -                | -         |     2.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2730 | 2024-04-14 | UNiTY             | W   | 0.477      | -            | -                | -                | -         |     4.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2788 | 2024-04-11 | Enterprise        | W   | 0.457      | -            | -                | -                | -         |     3.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2831 | 2024-04-10 | Passion UA        | L   | 0.451      | -            | -                | -                | -         |    -9.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2964 | 2024-04-06 | UNiTY             | W   | 0.423      | -            | -                | -                | -         |     3.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     3021 | 2024-04-04 | UNiTY             | W   | 0.411      | -            | -                | -                | -         |     3.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     3105 | 2024-04-02 | Permitta          | W   | 0.397      | -            | -                | -                | -         |     3.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     3114 | 2024-04-01 | Nexus             | L   | 0.390      | -            | -                | -                | -         |   -10.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3188 | 2024-03-27 | Rebels            | L   | 0.359      | -            | -                | -                | -         |    -7.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3223 | 2024-03-25 | Nexus             | W   | 0.345      | -            | -                | -                | -         |     1.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3247 | 2024-03-22 | Nemiga            | W   | 0.326      | 0.372        | 0.322 (0.039)    | -                | -         |     5.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3312 | 2024-03-19 | RUBY              | W   | 0.306      | -            | -                | -                | -         |     2.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3324 | 2024-03-18 | Insilio           | W   | 0.298      | -            | -                | -                | -         |     2.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3392 | 2024-03-15 | ECLOT             | W   | 0.277      | -            | -                | -                | -         |     3.88 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           32 |     3466 | 2024-03-13 | BLEED             | L   | 0.264      | -            | -                | -                | -         |    -5.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3513 | 2024-03-11 | Nemiga            | L   | 0.252      | -            | -                | -                | -         |    -3.65 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           30 |     3536 | 2024-03-10 | Sampi             | L   | 0.244      | -            | -                | -                | -         |    -6.19 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           29 |     3560 | 2024-03-09 | Permitta          | W   | 0.238      | -            | -                | -                | -         |     1.84 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           28 |     3581 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.230      | -            | -                | -                | -         |    -5.13 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3591 | 2024-03-07 | Insilio           | W   | 0.226      | -            | -                | -                | -         |     1.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3605 | 2024-03-07 | ex-sYnck          | W   | 0.225      | -            | -                | -                | -         |     0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3637 | 2024-03-06 | Alliance          | W   | 0.217      | -            | -                | -                | -         |     1.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3671 | 2024-03-05 | Johnny Speeds     | L   | 0.212      | -            | -                | -                | -         |    -1.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3680 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.210      | -            | -                | -                | -         |    -4.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3696 | 2024-03-04 | Entropiq          | L   | 0.204      | -            | -                | -                | -         |    -6.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3741 | 2024-03-02 | brazylijski luz   | W   | 0.191      | -            | -                | -                | -         |     0.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3775 | 2024-02-29 | JANO              | W   | 0.177      | -            | -                | -                | -         |     0.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3785 | 2024-02-28 | Sampi             | W   | 0.172      | -            | -                | -                | -         |     0.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3800 | 2024-02-27 | V1dar             | L   | 0.166      | -            | -                | -                | -         |    -5.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3841 | 2024-02-25 | Sangal            | L   | 0.153      | -            | -                | -                | -         |    -2.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3847 | 2024-02-25 | PGE Turow         | L   | 0.151      | -            | -                | -                | -         |    -4.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3887 | 2024-02-24 | MOUZ NXT          | L   | 0.144      | -            | -                | -                | -         |    -3.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3938 | 2024-02-21 | Sampi             | W   | 0.124      | -            | -                | -                | -         |     0.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4036 | 2024-02-17 | Zero Tenacity     | W   | 0.098      | -            | -                | -                | -         |     1.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4184 | 2024-02-11 | ARCRED            | W   | 0.058      | -            | -                | -                | -         |     0.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4186 | 2024-02-10 | Nemiga            | L   | 0.053      | -            | -                | -                | -         |    -0.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4194 | 2024-02-10 | AMKAL             | W   | 0.052      | -            | -                | -                | -         |     0.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4203 | 2024-02-09 | FORZE             | W   | 0.046      | -            | -                | -                | -         |     0.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4209 | 2024-02-09 | Insilio           | W   | 0.045      | -            | -                | -                | -         |     0.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4217 | 2024-02-08 | Nemiga            | L   | 0.039      | -            | -                | -                | -         |    -0.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4221 | 2024-02-08 | FORZE             | W   | 0.038      | -            | -                | -                | -         |     0.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4252 | 2024-02-05 | Entropiq          | W   | 0.017      | -            | -                | -                | -         |     0.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4269 | 2024-02-04 | TMVG              | L   | 0.011      | -            | -                | -                | -         |    -0.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4284 | 2024-02-03 | showmakerz        | W   | 0.006      | -            | -                | -                | -         |     0.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4288 | 2024-02-03 | Gaimin Gladiators | W   | 0.006      | -            | -                | -                | -         |     0.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4303 | 2024-02-03 | Sampi             | L   | 0.004      | -            | -                | -                | -         |    -0.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,379.79)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.872 | $9,365.00      | $8,170.62       |
| 2024-06-09 |      0.852 | $8,000.00      | $6,814.70       |
| 2024-05-18 |      0.706 | $5,000.00      | $3,528.63       |
| 2024-05-09 |      0.644 | $14,000.00     | $9,020.73       |
| 2024-05-02 |      0.599 | $12,500.00     | $7,484.78       |
| 2024-04-27 |      0.566 | $6,375.00      | $3,610.05       |
| 2024-04-06 |      0.423 | $5,000.00      | $2,116.13       |
| 2024-03-25 |      0.345 | $7,000.00      | $2,418.14       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
