### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1178.2<br />
<br />
Final Rank Value (1178.2) = Starting Rank Value (1160.6) + Head To Head Adjustments (17.6)<br />

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
|           94 |      168 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     6.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      199 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |     3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      211 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      392 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.309)    | 0 (0.000) |    10.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      613 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      623 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      693 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      820 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      829 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      846 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | 0 (0.000) |     4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      870 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      873 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.537 (0.192)    | 0 (0.000) |     5.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1077 | 2024-06-14 | 3DMAX             | L   | 0.859      | -            | -                | -                | -         |    -5.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1112 | 2024-06-13 | Sampi             | W   | 0.852      | -            | -                | -                | 0 (0.000) |     3.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1129 | 2024-06-12 | CPH Wolves        | W   | 0.847      | -            | -                | -                | 0 (0.000) |     2.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1138 | 2024-06-12 | Astralis Talent   | W   | 0.846      | -            | -                | -                | -         |     1.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1394 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.807      | -            | -                | -                | -         |    -2.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1430 | 2024-06-06 | HEROIC            | L   | 0.805      | -            | -                | -                | -         |    -3.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1459 | 2024-06-05 | ENCE              | L   | 0.801      | -            | -                | -                | -         |    -8.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1479 | 2024-06-05 | Astralis          | W   | 0.799      | 0.715        | 0.390 (0.223)    | 0.421 (0.241)    | 1 (0.799) |    24.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1489 | 2024-06-05 | The MongolZ       | L   | 0.798      | -            | -                | -                | -         |    -0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1924 | 2024-05-20 | Monte             | L   | 0.691      | -            | -                | -                | -         |   -15.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1937 | 2024-05-19 | Passion UA        | W   | 0.686      | 0.500        | 0.172 (0.059)    | 1.000 (0.343)    | -         |     5.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1964 | 2024-05-18 | B8                | L   | 0.680      | -            | -                | -                | -         |   -12.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1973 | 2024-05-18 | Monte             | W   | 0.679      | -            | -                | -                | -         |     5.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1981 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.678      | 0.500        | -                | 0.560 (0.190)    | -         |     3.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2012 | 2024-05-17 | ex-Guild Eagles   | W   | 0.672      | -            | -                | -                | -         |     2.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2052 | 2024-05-16 | Passion UA        | L   | 0.665      | -            | -                | -                | -         |   -15.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2099 | 2024-05-15 | Endpoint          | W   | 0.658      | -            | -                | -                | -         |     3.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2271 | 2024-05-09 | 1WIN              | W   | 0.619      | -            | -                | -                | -         |     4.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2294 | 2024-05-08 | Grannys Knockers  | W   | 0.612      | -            | -                | -                | -         |     1.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2312 | 2024-05-07 | 9 Pandas          | W   | 0.606      | -            | -                | -                | -         |     4.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2326 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.600      | -            | -                | -                | -         |     4.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2340 | 2024-05-05 | Gaimin Gladiators | L   | 0.593      | -            | -                | -                | -         |   -14.26 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2348 | 2024-05-05 | Come on now dawg  | W   | 0.593      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2400 | 2024-05-02 | fnatic            | W   | 0.573      | 0.384        | 0.371 (0.082)    | -                | -         |    15.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2435 | 2024-05-01 | 3DMAX             | W   | 0.565      | 0.384        | 0.506 (0.110)    | 1.000 (0.217)    | -         |    16.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2452 | 2024-04-30 | OG                | W   | 0.559      | 0.384        | 0.139 (0.030)    | -                | -         |     6.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2477 | 2024-04-29 | 500               | W   | 0.552      | -            | -                | -                | -         |     1.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2505 | 2024-04-27 | 777               | W   | 0.541      | -            | -                | -                | -         |     1.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2509 | 2024-04-27 | JANO              | W   | 0.540      | -            | -                | -                | -         |     1.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2576 | 2024-04-25 | Passion UA        | W   | 0.525      | 0.384        | 0.172 (0.035)    | 1.000 (0.202)    | -         |     4.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2610 | 2024-04-23 | Gaimin Gladiators | W   | 0.513      | -            | -                | -                | -         |     5.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2615 | 2024-04-23 | BLEED             | W   | 0.512      | -            | -                | -                | -         |     5.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2666 | 2024-04-20 | Eternal Fire      | W   | 0.494      | 0.143        | 0.742 (0.052)    | -                | -         |    14.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2673 | 2024-04-20 | Cloud9            | W   | 0.493      | -            | -                | -                | -         |     6.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2712 | 2024-04-19 | Eternal Fire      | L   | 0.487      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2721 | 2024-04-19 | Cloud9            | W   | 0.486      | -            | -                | -                | -         |     6.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2747 | 2024-04-18 | ex-Guild Eagles   | W   | 0.481      | -            | -                | -                | -         |     2.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2751 | 2024-04-18 | RUBY              | W   | 0.480      | -            | -                | -                | -         |     4.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2760 | 2024-04-18 | GamerLegion       | W   | 0.480      | -            | -                | -                | -         |     7.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2804 | 2024-04-17 | Passion UA        | L   | 0.472      | -            | -                | -                | -         |    -9.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2841 | 2024-04-16 | ex-Guild Eagles   | L   | 0.466      | -            | -                | -                | -         |   -12.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2862 | 2024-04-15 | ex-Preasy         | W   | 0.459      | -            | -                | -                | -         |     2.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2879 | 2024-04-14 | UNiTY             | W   | 0.451      | -            | -                | -                | -         |     3.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2937 | 2024-04-11 | Enterprise        | W   | 0.431      | -            | -                | -                | -         |     3.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2980 | 2024-04-10 | Passion UA        | L   | 0.425      | -            | -                | -                | -         |    -8.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3113 | 2024-04-06 | UNiTY             | W   | 0.398      | -            | -                | -                | -         |     3.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3170 | 2024-04-04 | UNiTY             | W   | 0.385      | -            | -                | -                | -         |     3.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3254 | 2024-04-02 | Permitta          | W   | 0.371      | -            | -                | -                | -         |     3.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3263 | 2024-04-01 | Nexus             | L   | 0.365      | -            | -                | -                | -         |    -9.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3337 | 2024-03-27 | Rebels            | L   | 0.334      | -            | -                | -                | -         |    -7.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3372 | 2024-03-25 | Nexus             | W   | 0.320      | -            | -                | -                | -         |     1.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3396 | 2024-03-22 | Nemiga            | W   | 0.300      | 0.372        | 0.317 (0.035)    | -                | -         |     5.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3461 | 2024-03-19 | RUBY              | W   | 0.280      | -            | -                | -                | -         |     2.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3473 | 2024-03-18 | Insilio           | W   | 0.273      | -            | -                | -                | -         |     1.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3541 | 2024-03-15 | ECLOT             | W   | 0.252      | -            | -                | -                | -         |     4.72 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3615 | 2024-03-13 | BLEED             | L   | 0.238      | -            | -                | -                | -         |    -5.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3662 | 2024-03-11 | Nemiga            | L   | 0.226      | -            | -                | -                | -         |    -3.17 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3685 | 2024-03-10 | Sampi             | L   | 0.218      | -            | -                | -                | -         |    -5.53 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3709 | 2024-03-09 | Permitta          | W   | 0.212      | -            | -                | -                | -         |     1.79 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3730 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.205      | -            | -                | -                | -         |    -4.59 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3740 | 2024-03-07 | Insilio           | W   | 0.201      | -            | -                | -                | -         |     1.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3754 | 2024-03-07 | ex-sYnck          | W   | 0.199      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3786 | 2024-03-06 | Alliance          | W   | 0.192      | -            | -                | -                | -         |     1.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3820 | 2024-03-05 | Johnny Speeds     | L   | 0.187      | -            | -                | -                | -         |    -1.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3829 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.185      | -            | -                | -                | -         |    -4.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3845 | 2024-03-04 | Entropiq          | L   | 0.178      | -            | -                | -                | -         |    -5.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3890 | 2024-03-02 | brazylijski luz   | W   | 0.166      | -            | -                | -                | -         |     0.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3924 | 2024-02-29 | JANO              | W   | 0.152      | -            | -                | -                | -         |     0.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3934 | 2024-02-28 | Sampi             | W   | 0.146      | -            | -                | -                | -         |     0.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3949 | 2024-02-27 | V1dar             | L   | 0.140      | -            | -                | -                | -         |    -4.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     3990 | 2024-02-25 | Sangal            | L   | 0.127      | -            | -                | -                | -         |    -1.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     3996 | 2024-02-25 | PGE Turow         | L   | 0.125      | -            | -                | -                | -         |    -3.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4036 | 2024-02-24 | MOUZ NXT          | L   | 0.118      | -            | -                | -                | -         |    -2.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4087 | 2024-02-21 | Sampi             | W   | 0.099      | -            | -                | -                | -         |     0.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4185 | 2024-02-17 | Zero Tenacity     | W   | 0.073      | -            | -                | -                | -         |     0.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4333 | 2024-02-11 | ARCRED            | W   | 0.032      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4335 | 2024-02-10 | Nemiga            | L   | 0.028      | -            | -                | -                | -         |    -0.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4343 | 2024-02-10 | AMKAL             | W   | 0.026      | -            | -                | -                | -         |     0.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4352 | 2024-02-09 | FORZE             | W   | 0.021      | -            | -                | -                | -         |     0.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4358 | 2024-02-09 | Insilio           | W   | 0.019      | -            | -                | -                | -         |     0.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4366 | 2024-02-08 | Nemiga            | L   | 0.014      | -            | -                | -                | -         |    -0.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4370 | 2024-02-08 | FORZE             | W   | 0.013      | -            | -                | -                | -         |     0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,660.82)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.847 | $9,365.00      | $7,931.20       |
| 2024-06-09 |      0.826 | $8,000.00      | $6,610.19       |
| 2024-05-18 |      0.680 | $5,000.00      | $3,400.81       |
| 2024-05-09 |      0.619 | $14,000.00     | $8,662.82       |
| 2024-05-02 |      0.573 | $12,500.00     | $7,165.22       |
| 2024-04-27 |      0.541 | $6,375.00      | $3,447.07       |
| 2024-04-06 |      0.398 | $5,000.00      | $1,988.31       |
| 2024-03-25 |      0.320 | $7,000.00      | $2,239.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
