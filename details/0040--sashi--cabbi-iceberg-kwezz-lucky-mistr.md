### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1127.3<br />
<br />
Final Rank Value (1127.3) = Starting Rank Value (1159.8) + Head To Head Adjustments (-32.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.369<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1159.8
- 400 + ( ( 0.369 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1159.8


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
|           97 |       17 | 2024-08-05 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -30.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |       21 | 2024-08-05 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |       27 | 2024-08-05 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      207 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.539 (0.270)    | 0 (0.000) |     7.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      238 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     3.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      250 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -16.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      431 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.598 (0.299)    | 0 (0.000) |    10.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      652 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      662 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      732 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      859 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      868 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      885 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.502 (0.180)    | 0 (0.000) |     4.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      909 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      912 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.523 (0.187)    | 0 (0.000) |     5.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1116 | 2024-06-14 | 3DMAX             | L   | 0.847      | -            | -                | -                | -         |    -5.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1151 | 2024-06-13 | Sampi             | W   | 0.840      | -            | -                | -                | 0 (0.000) |     3.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1168 | 2024-06-12 | CPH Wolves        | W   | 0.835      | -            | -                | -                | -         |     2.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1177 | 2024-06-12 | Astralis Talent   | W   | 0.834      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1433 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.795      | -            | -                | -                | -         |    -2.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1469 | 2024-06-06 | HEROIC            | L   | 0.793      | -            | -                | -                | -         |    -3.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1498 | 2024-06-05 | ENCE              | L   | 0.788      | -            | -                | -                | -         |    -7.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1518 | 2024-06-05 | Astralis          | W   | 0.787      | 0.715        | 0.389 (0.219)    | 0.403 (0.227)    | 1 (0.787) |    23.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1528 | 2024-06-05 | The MongolZ       | L   | 0.786      | -            | -                | -                | -         |    -0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1963 | 2024-05-20 | Monte             | L   | 0.679      | -            | -                | -                | -         |   -15.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1976 | 2024-05-19 | Passion UA        | W   | 0.674      | 0.500        | 0.173 (0.058)    | 1.000 (0.337)    | -         |     5.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     2003 | 2024-05-18 | B8                | L   | 0.668      | -            | -                | -                | -         |   -12.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     2012 | 2024-05-18 | Monte             | W   | 0.667      | -            | -                | -                | -         |     5.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2020 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.666      | 0.500        | -                | 0.537 (0.179)    | -         |     3.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2051 | 2024-05-17 | ex-Guild Eagles   | W   | 0.659      | -            | -                | -                | -         |     2.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2091 | 2024-05-16 | Passion UA        | L   | 0.652      | -            | -                | -                | -         |   -15.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2138 | 2024-05-15 | Endpoint          | W   | 0.646      | -            | -                | -                | -         |     3.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2310 | 2024-05-09 | 1WIN              | W   | 0.607      | -            | -                | -                | -         |     4.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2333 | 2024-05-08 | Grannys Knockers  | W   | 0.600      | -            | -                | -                | -         |     1.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2351 | 2024-05-07 | 9 Pandas          | W   | 0.594      | -            | -                | -                | -         |     4.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2365 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.588      | -            | -                | -                | -         |     4.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2379 | 2024-05-05 | Gaimin Gladiators | L   | 0.581      | -            | -                | -                | -         |   -14.04 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2387 | 2024-05-05 | Come on now dawg  | W   | 0.580      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2439 | 2024-05-02 | fnatic            | W   | 0.561      | 0.384        | 0.371 (0.080)    | -                | -         |    15.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2474 | 2024-05-01 | 3DMAX             | W   | 0.553      | 0.384        | 0.510 (0.108)    | 1.000 (0.213)    | -         |    16.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2491 | 2024-04-30 | OG                | W   | 0.547      | 0.384        | 0.137 (0.029)    | -                | -         |     5.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2516 | 2024-04-29 | 500               | W   | 0.540      | -            | -                | -                | -         |     1.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2544 | 2024-04-27 | 777               | W   | 0.529      | -            | -                | -                | -         |     1.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2548 | 2024-04-27 | JANO              | W   | 0.528      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2615 | 2024-04-25 | Passion UA        | W   | 0.513      | 0.384        | 0.173 (0.034)    | 1.000 (0.197)    | -         |     5.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2649 | 2024-04-23 | Gaimin Gladiators | W   | 0.500      | -            | -                | -                | -         |     4.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2654 | 2024-04-23 | BLEED             | W   | 0.499      | -            | -                | -                | -         |     5.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2705 | 2024-04-20 | Eternal Fire      | W   | 0.481      | 0.143        | 0.739 (0.051)    | -                | -         |    14.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2712 | 2024-04-20 | Cloud9            | W   | 0.480      | -            | -                | -                | -         |     6.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2751 | 2024-04-19 | Eternal Fire      | L   | 0.475      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2760 | 2024-04-19 | Cloud9            | W   | 0.474      | -            | -                | -                | -         |     6.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2786 | 2024-04-18 | ex-Guild Eagles   | W   | 0.468      | -            | -                | -                | -         |     2.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2790 | 2024-04-18 | RUBY              | W   | 0.468      | -            | -                | -                | -         |     4.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2799 | 2024-04-18 | GamerLegion       | W   | 0.468      | -            | -                | -                | -         |     7.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2843 | 2024-04-17 | Passion UA        | L   | 0.460      | -            | -                | -                | -         |    -8.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2880 | 2024-04-16 | ex-Guild Eagles   | L   | 0.454      | -            | -                | -                | -         |   -12.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2901 | 2024-04-15 | ex-Preasy         | W   | 0.447      | -            | -                | -                | -         |     2.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2918 | 2024-04-14 | UNiTY             | W   | 0.439      | -            | -                | -                | -         |     3.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2976 | 2024-04-11 | Enterprise        | W   | 0.419      | -            | -                | -                | -         |     3.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3019 | 2024-04-10 | Passion UA        | L   | 0.413      | -            | -                | -                | -         |    -8.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3152 | 2024-04-06 | UNiTY             | W   | 0.385      | -            | -                | -                | -         |     3.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3209 | 2024-04-04 | UNiTY             | W   | 0.373      | -            | -                | -                | -         |     3.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3293 | 2024-04-02 | Permitta          | W   | 0.359      | -            | -                | -                | -         |     3.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3302 | 2024-04-01 | Nexus             | L   | 0.353      | -            | -                | -                | -         |    -9.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3376 | 2024-03-27 | Rebels            | L   | 0.322      | -            | -                | -                | -         |    -7.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3411 | 2024-03-25 | Nexus             | W   | 0.308      | -            | -                | -                | -         |     1.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3435 | 2024-03-22 | Nemiga            | W   | 0.288      | 0.372        | 0.314 (0.034)    | -                | -         |     4.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3500 | 2024-03-19 | RUBY              | W   | 0.268      | -            | -                | -                | -         |     2.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3512 | 2024-03-18 | Insilio           | W   | 0.260      | -            | -                | -                | -         |     1.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3580 | 2024-03-15 | ECLOT             | W   | 0.239      | -            | -                | -                | -         |     4.49 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3654 | 2024-03-13 | BLEED             | L   | 0.226      | -            | -                | -                | -         |    -5.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3701 | 2024-03-11 | Nemiga            | L   | 0.214      | -            | -                | -                | -         |    -3.04 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3724 | 2024-03-10 | Sampi             | L   | 0.206      | -            | -                | -                | -         |    -5.24 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3748 | 2024-03-09 | Permitta          | W   | 0.200      | -            | -                | -                | -         |     1.78 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3769 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.192      | -            | -                | -                | -         |    -4.31 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3779 | 2024-03-07 | Insilio           | W   | 0.189      | -            | -                | -                | -         |     1.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3793 | 2024-03-07 | ex-sYnck          | W   | 0.187      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3825 | 2024-03-06 | Alliance          | W   | 0.180      | -            | -                | -                | -         |     0.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3859 | 2024-03-05 | Johnny Speeds     | L   | 0.175      | -            | -                | -                | -         |    -1.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3868 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.173      | -            | -                | -                | -         |    -3.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3884 | 2024-03-04 | Entropiq          | L   | 0.166      | -            | -                | -                | -         |    -5.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3929 | 2024-03-02 | brazylijski luz   | W   | 0.153      | -            | -                | -                | -         |     0.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3963 | 2024-02-29 | JANO              | W   | 0.139      | -            | -                | -                | -         |     0.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3973 | 2024-02-28 | Sampi             | W   | 0.134      | -            | -                | -                | -         |     0.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3988 | 2024-02-27 | V1dar             | L   | 0.128      | -            | -                | -                | -         |    -3.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4029 | 2024-02-25 | Sangal            | L   | 0.115      | -            | -                | -                | -         |    -1.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4035 | 2024-02-25 | PGE Turow         | L   | 0.113      | -            | -                | -                | -         |    -3.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4075 | 2024-02-24 | MOUZ NXT          | L   | 0.106      | -            | -                | -                | -         |    -2.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4126 | 2024-02-21 | Sampi             | W   | 0.087      | -            | -                | -                | -         |     0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4224 | 2024-02-17 | Zero Tenacity     | W   | 0.061      | -            | -                | -                | -         |     0.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4372 | 2024-02-11 | ARCRED            | W   | 0.020      | -            | -                | -                | -         |     0.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4374 | 2024-02-10 | Nemiga            | L   | 0.015      | -            | -                | -                | -         |    -0.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4382 | 2024-02-10 | AMKAL             | W   | 0.014      | -            | -                | -                | -         |     0.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4391 | 2024-02-09 | FORZE             | W   | 0.008      | -            | -                | -                | -         |     0.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4397 | 2024-02-09 | Insilio           | W   | 0.007      | -            | -                | -                | -         |     0.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4405 | 2024-02-08 | Nemiga            | L   | 0.002      | -            | -                | -                | -         |    -0.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4409 | 2024-02-08 | FORZE             | W   | 0.001      | -            | -                | -                | -         |     0.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58,840.55)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.835 | $9,365.00      | $7,816.96       |
| 2024-06-09 |      0.814 | $8,000.00      | $6,512.59       |
| 2024-05-18 |      0.668 | $5,000.00      | $3,339.81       |
| 2024-05-09 |      0.607 | $14,000.00     | $8,492.04       |
| 2024-05-02 |      0.561 | $12,500.00     | $7,012.73       |
| 2024-04-27 |      0.529 | $6,375.00      | $3,369.31       |
| 2024-04-06 |      0.385 | $5,000.00      | $1,927.31       |
| 2024-03-25 |      0.308 | $7,000.00      | $2,153.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
