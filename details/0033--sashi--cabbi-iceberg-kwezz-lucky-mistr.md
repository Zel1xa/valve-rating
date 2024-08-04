### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1178.1<br />
<br />
Final Rank Value (1178.1) = Starting Rank Value (1160.6) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.372<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.6
- 400 + ( ( 0.372 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1160.6


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
|           94 |      167 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     6.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      198 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |     3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      210 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      391 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.309)    | 0 (0.000) |    10.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      612 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      622 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      692 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      819 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      828 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      845 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | 0 (0.000) |     4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      869 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      872 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.537 (0.192)    | 0 (0.000) |     5.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1076 | 2024-06-14 | 3DMAX             | L   | 0.859      | -            | -                | -                | -         |    -5.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1111 | 2024-06-13 | Sampi             | W   | 0.853      | -            | -                | -                | 0 (0.000) |     3.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1128 | 2024-06-12 | CPH Wolves        | W   | 0.847      | -            | -                | -                | 0 (0.000) |     2.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1137 | 2024-06-12 | Astralis Talent   | W   | 0.847      | -            | -                | -                | -         |     1.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1393 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.808      | -            | -                | -                | -         |    -2.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1429 | 2024-06-06 | HEROIC            | L   | 0.806      | -            | -                | -                | -         |    -3.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1458 | 2024-06-05 | ENCE              | L   | 0.801      | -            | -                | -                | -         |    -8.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1478 | 2024-06-05 | Astralis          | W   | 0.800      | 0.715        | 0.391 (0.223)    | 0.421 (0.241)    | 1 (0.800) |    24.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1488 | 2024-06-05 | The MongolZ       | L   | 0.798      | -            | -                | -                | -         |    -0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1923 | 2024-05-20 | Monte             | L   | 0.692      | -            | -                | -                | -         |   -15.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1936 | 2024-05-19 | Passion UA        | W   | 0.687      | 0.500        | 0.172 (0.059)    | 1.000 (0.343)    | -         |     5.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1963 | 2024-05-18 | B8                | L   | 0.680      | -            | -                | -                | -         |   -12.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1972 | 2024-05-18 | Monte             | W   | 0.679      | -            | -                | -                | -         |     5.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1980 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.678      | 0.500        | -                | 0.560 (0.190)    | -         |     3.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2011 | 2024-05-17 | ex-Guild Eagles   | W   | 0.672      | -            | -                | -                | -         |     2.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2051 | 2024-05-16 | Passion UA        | L   | 0.665      | -            | -                | -                | -         |   -15.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2098 | 2024-05-15 | Endpoint          | W   | 0.659      | -            | -                | -                | -         |     3.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2270 | 2024-05-09 | 1WIN              | W   | 0.619      | -            | -                | -                | -         |     4.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2293 | 2024-05-08 | Grannys Knockers  | W   | 0.612      | -            | -                | -                | -         |     1.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2311 | 2024-05-07 | 9 Pandas          | W   | 0.606      | -            | -                | -                | -         |     4.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2325 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.600      | -            | -                | -                | -         |     4.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2339 | 2024-05-05 | Gaimin Gladiators | L   | 0.594      | -            | -                | -                | -         |   -14.26 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2347 | 2024-05-05 | Come on now dawg  | W   | 0.593      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2399 | 2024-05-02 | fnatic            | W   | 0.574      | 0.384        | 0.371 (0.082)    | -                | -         |    15.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2434 | 2024-05-01 | 3DMAX             | W   | 0.565      | 0.384        | 0.506 (0.110)    | 1.000 (0.217)    | -         |    16.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2451 | 2024-04-30 | OG                | W   | 0.560      | 0.384        | 0.139 (0.030)    | -                | -         |     6.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2476 | 2024-04-29 | 500               | W   | 0.552      | -            | -                | -                | -         |     1.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2504 | 2024-04-27 | 777               | W   | 0.541      | -            | -                | -                | -         |     1.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2508 | 2024-04-27 | JANO              | W   | 0.540      | -            | -                | -                | -         |     1.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2575 | 2024-04-25 | Passion UA        | W   | 0.525      | 0.384        | 0.172 (0.035)    | 1.000 (0.202)    | -         |     4.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2609 | 2024-04-23 | Gaimin Gladiators | W   | 0.513      | -            | -                | -                | -         |     5.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2614 | 2024-04-23 | BLEED             | W   | 0.512      | -            | -                | -                | -         |     5.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2665 | 2024-04-20 | Eternal Fire      | W   | 0.494      | 0.143        | 0.742 (0.052)    | -                | -         |    14.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2672 | 2024-04-20 | Cloud9            | W   | 0.493      | -            | -                | -                | -         |     6.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2711 | 2024-04-19 | Eternal Fire      | L   | 0.487      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2720 | 2024-04-19 | Cloud9            | W   | 0.486      | -            | -                | -                | -         |     6.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2746 | 2024-04-18 | ex-Guild Eagles   | W   | 0.481      | -            | -                | -                | -         |     2.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2750 | 2024-04-18 | RUBY              | W   | 0.481      | -            | -                | -                | -         |     4.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2759 | 2024-04-18 | GamerLegion       | W   | 0.480      | -            | -                | -                | -         |     7.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2803 | 2024-04-17 | Passion UA        | L   | 0.473      | -            | -                | -                | -         |    -9.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2840 | 2024-04-16 | ex-Guild Eagles   | L   | 0.466      | -            | -                | -                | -         |   -12.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2861 | 2024-04-15 | ex-Preasy         | W   | 0.459      | -            | -                | -                | -         |     2.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2878 | 2024-04-14 | UNiTY             | W   | 0.451      | -            | -                | -                | -         |     3.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2936 | 2024-04-11 | Enterprise        | W   | 0.432      | -            | -                | -                | -         |     3.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2979 | 2024-04-10 | Passion UA        | L   | 0.425      | -            | -                | -                | -         |    -8.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3112 | 2024-04-06 | UNiTY             | W   | 0.398      | -            | -                | -                | -         |     3.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3169 | 2024-04-04 | UNiTY             | W   | 0.385      | -            | -                | -                | -         |     3.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3253 | 2024-04-02 | Permitta          | W   | 0.371      | -            | -                | -                | -         |     3.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3262 | 2024-04-01 | Nexus             | L   | 0.365      | -            | -                | -                | -         |    -9.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3336 | 2024-03-27 | Rebels            | L   | 0.334      | -            | -                | -                | -         |    -7.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3371 | 2024-03-25 | Nexus             | W   | 0.320      | -            | -                | -                | -         |     1.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3395 | 2024-03-22 | Nemiga            | W   | 0.301      | 0.372        | 0.317 (0.036)    | -                | -         |     5.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3460 | 2024-03-19 | RUBY              | W   | 0.281      | -            | -                | -                | -         |     2.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3472 | 2024-03-18 | Insilio           | W   | 0.273      | -            | -                | -                | -         |     1.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3540 | 2024-03-15 | ECLOT             | W   | 0.252      | -            | -                | -                | -         |     4.73 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3614 | 2024-03-13 | BLEED             | L   | 0.239      | -            | -                | -                | -         |    -5.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3661 | 2024-03-11 | Nemiga            | L   | 0.226      | -            | -                | -                | -         |    -3.18 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3684 | 2024-03-10 | Sampi             | L   | 0.219      | -            | -                | -                | -         |    -5.54 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3708 | 2024-03-09 | Permitta          | W   | 0.212      | -            | -                | -                | -         |     1.79 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3729 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.205      | -            | -                | -                | -         |    -4.59 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3739 | 2024-03-07 | Insilio           | W   | 0.201      | -            | -                | -                | -         |     1.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3753 | 2024-03-07 | ex-sYnck          | W   | 0.199      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3785 | 2024-03-06 | Alliance          | W   | 0.192      | -            | -                | -                | -         |     1.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3819 | 2024-03-05 | Johnny Speeds     | L   | 0.187      | -            | -                | -                | -         |    -1.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3828 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.185      | -            | -                | -                | -         |    -4.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3844 | 2024-03-04 | Entropiq          | L   | 0.178      | -            | -                | -                | -         |    -5.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3889 | 2024-03-02 | brazylijski luz   | W   | 0.166      | -            | -                | -                | -         |     0.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3923 | 2024-02-29 | JANO              | W   | 0.152      | -            | -                | -                | -         |     0.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3933 | 2024-02-28 | Sampi             | W   | 0.146      | -            | -                | -                | -         |     0.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3948 | 2024-02-27 | V1dar             | L   | 0.140      | -            | -                | -                | -         |    -4.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     3989 | 2024-02-25 | Sangal            | L   | 0.128      | -            | -                | -                | -         |    -2.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     3995 | 2024-02-25 | PGE Turow         | L   | 0.126      | -            | -                | -                | -         |    -3.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4035 | 2024-02-24 | MOUZ NXT          | L   | 0.118      | -            | -                | -                | -         |    -2.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4086 | 2024-02-21 | Sampi             | W   | 0.099      | -            | -                | -                | -         |     0.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4184 | 2024-02-17 | Zero Tenacity     | W   | 0.073      | -            | -                | -                | -         |     0.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4332 | 2024-02-11 | ARCRED            | W   | 0.032      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4334 | 2024-02-10 | Nemiga            | L   | 0.028      | -            | -                | -                | -         |    -0.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4342 | 2024-02-10 | AMKAL             | W   | 0.026      | -            | -                | -                | -         |     0.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4351 | 2024-02-09 | FORZE             | W   | 0.021      | -            | -                | -                | -         |     0.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4357 | 2024-02-09 | Insilio           | W   | 0.020      | -            | -                | -                | -         |     0.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4365 | 2024-02-08 | Nemiga            | L   | 0.014      | -            | -                | -                | -         |    -0.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4369 | 2024-02-08 | FORZE             | W   | 0.013      | -            | -                | -                | -         |     0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,681.05)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.847 | $9,365.00      | $7,934.02       |
| 2024-06-09 |      0.827 | $8,000.00      | $6,612.59       |
| 2024-05-18 |      0.680 | $5,000.00      | $3,402.31       |
| 2024-05-09 |      0.619 | $14,000.00     | $8,667.04       |
| 2024-05-02 |      0.574 | $12,500.00     | $7,168.98       |
| 2024-04-27 |      0.541 | $6,375.00      | $3,448.99       |
| 2024-04-06 |      0.398 | $5,000.00      | $1,989.81       |
| 2024-03-25 |      0.320 | $7,000.00      | $2,241.30       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
