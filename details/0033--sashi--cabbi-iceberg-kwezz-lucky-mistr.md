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
Final Rank Value (1178.1) = Starting Rank Value (1160.5) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.241[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.372<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.5
- 400 + ( ( 0.372 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1160.5


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
|           94 |      172 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     6.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      203 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.509 (0.254)    | 0 (0.000) |     3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      215 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      396 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.310)    | 0 (0.000) |    10.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      617 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      627 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      697 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      824 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      833 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      850 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | 0 (0.000) |     4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      874 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      877 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.539 (0.193)    | 0 (0.000) |     5.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1081 | 2024-06-14 | 3DMAX             | L   | 0.857      | -            | -                | -                | -         |    -5.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1116 | 2024-06-13 | Sampi             | W   | 0.850      | -            | -                | -                | 0 (0.000) |     3.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1133 | 2024-06-12 | CPH Wolves        | W   | 0.845      | -            | -                | -                | 0 (0.000) |     2.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1142 | 2024-06-12 | Astralis Talent   | W   | 0.844      | -            | -                | -                | -         |     1.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1398 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.805      | -            | -                | -                | -         |    -2.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1434 | 2024-06-06 | HEROIC            | L   | 0.803      | -            | -                | -                | -         |    -3.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1463 | 2024-06-05 | ENCE              | L   | 0.798      | -            | -                | -                | -         |    -8.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1483 | 2024-06-05 | Astralis          | W   | 0.797      | 0.715        | 0.390 (0.222)    | 0.421 (0.240)    | 1 (0.797) |    23.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1493 | 2024-06-05 | The MongolZ       | L   | 0.796      | -            | -                | -                | -         |    -0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1928 | 2024-05-20 | Monte             | L   | 0.689      | -            | -                | -                | -         |   -15.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1941 | 2024-05-19 | Passion UA        | W   | 0.684      | 0.500        | 0.172 (0.059)    | 1.000 (0.342)    | -         |     5.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1968 | 2024-05-18 | B8                | L   | 0.678      | -            | -                | -                | -         |   -12.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1977 | 2024-05-18 | Monte             | W   | 0.677      | -            | -                | -                | -         |     5.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1985 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.676      | 0.500        | -                | 0.560 (0.189)    | -         |     3.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2016 | 2024-05-17 | ex-Guild Eagles   | W   | 0.669      | -            | -                | -                | -         |     2.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2056 | 2024-05-16 | Passion UA        | L   | 0.662      | -            | -                | -                | -         |   -15.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2103 | 2024-05-15 | Endpoint          | W   | 0.656      | -            | -                | -                | -         |     3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2275 | 2024-05-09 | 1WIN              | W   | 0.616      | -            | -                | -                | -         |     4.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2298 | 2024-05-08 | Grannys Knockers  | W   | 0.610      | -            | -                | -                | -         |     1.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2316 | 2024-05-07 | 9 Pandas          | W   | 0.603      | -            | -                | -                | -         |     4.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2330 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.598      | -            | -                | -                | -         |     4.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2344 | 2024-05-05 | Gaimin Gladiators | L   | 0.591      | -            | -                | -                | -         |   -14.22 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2352 | 2024-05-05 | Come on now dawg  | W   | 0.590      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2404 | 2024-05-02 | fnatic            | W   | 0.571      | 0.384        | 0.371 (0.081)    | -                | -         |    15.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2439 | 2024-05-01 | 3DMAX             | W   | 0.563      | 0.384        | 0.507 (0.110)    | 1.000 (0.216)    | -         |    16.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2456 | 2024-04-30 | OG                | W   | 0.557      | 0.384        | 0.138 (0.030)    | -                | -         |     6.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2481 | 2024-04-29 | 500               | W   | 0.549      | -            | -                | -                | -         |     1.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2509 | 2024-04-27 | 777               | W   | 0.538      | -            | -                | -                | -         |     1.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2513 | 2024-04-27 | JANO              | W   | 0.538      | -            | -                | -                | -         |     1.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2580 | 2024-04-25 | Passion UA        | W   | 0.523      | 0.384        | 0.172 (0.035)    | 1.000 (0.201)    | -         |     4.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2614 | 2024-04-23 | Gaimin Gladiators | W   | 0.510      | -            | -                | -                | -         |     5.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2619 | 2024-04-23 | BLEED             | W   | 0.509      | -            | -                | -                | -         |     5.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2670 | 2024-04-20 | Eternal Fire      | W   | 0.491      | 0.143        | 0.741 (0.052)    | -                | -         |    14.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2677 | 2024-04-20 | Cloud9            | W   | 0.490      | -            | -                | -                | -         |     6.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2716 | 2024-04-19 | Eternal Fire      | L   | 0.485      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2725 | 2024-04-19 | Cloud9            | W   | 0.483      | -            | -                | -                | -         |     6.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2751 | 2024-04-18 | ex-Guild Eagles   | W   | 0.478      | -            | -                | -                | -         |     2.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2755 | 2024-04-18 | RUBY              | W   | 0.478      | -            | -                | -                | -         |     4.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2764 | 2024-04-18 | GamerLegion       | W   | 0.477      | -            | -                | -                | -         |     7.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2808 | 2024-04-17 | Passion UA        | L   | 0.470      | -            | -                | -                | -         |    -9.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2845 | 2024-04-16 | ex-Guild Eagles   | L   | 0.463      | -            | -                | -                | -         |   -12.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2866 | 2024-04-15 | ex-Preasy         | W   | 0.456      | -            | -                | -                | -         |     2.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2883 | 2024-04-14 | UNiTY             | W   | 0.449      | -            | -                | -                | -         |     3.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2941 | 2024-04-11 | Enterprise        | W   | 0.429      | -            | -                | -                | -         |     3.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2984 | 2024-04-10 | Passion UA        | L   | 0.423      | -            | -                | -                | -         |    -8.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3117 | 2024-04-06 | UNiTY             | W   | 0.395      | -            | -                | -                | -         |     3.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3174 | 2024-04-04 | UNiTY             | W   | 0.383      | -            | -                | -                | -         |     3.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3258 | 2024-04-02 | Permitta          | W   | 0.369      | -            | -                | -                | -         |     3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3267 | 2024-04-01 | Nexus             | L   | 0.362      | -            | -                | -                | -         |    -9.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3341 | 2024-03-27 | Rebels            | L   | 0.331      | -            | -                | -                | -         |    -7.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3376 | 2024-03-25 | Nexus             | W   | 0.318      | -            | -                | -                | -         |     1.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3400 | 2024-03-22 | Nemiga            | W   | 0.298      | 0.372        | 0.317 (0.035)    | -                | -         |     5.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3465 | 2024-03-19 | RUBY              | W   | 0.278      | -            | -                | -                | -         |     2.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3477 | 2024-03-18 | Insilio           | W   | 0.270      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3545 | 2024-03-15 | ECLOT             | W   | 0.249      | -            | -                | -                | -         |     4.67 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3619 | 2024-03-13 | BLEED             | L   | 0.236      | -            | -                | -                | -         |    -5.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3666 | 2024-03-11 | Nemiga            | L   | 0.224      | -            | -                | -                | -         |    -3.15 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3689 | 2024-03-10 | Sampi             | L   | 0.216      | -            | -                | -                | -         |    -5.48 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3713 | 2024-03-09 | Permitta          | W   | 0.210      | -            | -                | -                | -         |     1.76 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3734 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.202      | -            | -                | -                | -         |    -4.54 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3744 | 2024-03-07 | Insilio           | W   | 0.198      | -            | -                | -                | -         |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3758 | 2024-03-07 | ex-sYnck          | W   | 0.197      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3790 | 2024-03-06 | Alliance          | W   | 0.189      | -            | -                | -                | -         |     0.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3824 | 2024-03-05 | Johnny Speeds     | L   | 0.184      | -            | -                | -                | -         |    -1.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3833 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.182      | -            | -                | -                | -         |    -4.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3849 | 2024-03-04 | Entropiq          | L   | 0.176      | -            | -                | -                | -         |    -5.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3894 | 2024-03-02 | brazylijski luz   | W   | 0.163      | -            | -                | -                | -         |     0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3928 | 2024-02-29 | JANO              | W   | 0.149      | -            | -                | -                | -         |     0.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3938 | 2024-02-28 | Sampi             | W   | 0.144      | -            | -                | -                | -         |     0.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3953 | 2024-02-27 | V1dar             | L   | 0.138      | -            | -                | -                | -         |    -4.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     3994 | 2024-02-25 | Sangal            | L   | 0.125      | -            | -                | -                | -         |    -1.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4000 | 2024-02-25 | PGE Turow         | L   | 0.123      | -            | -                | -                | -         |    -3.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4040 | 2024-02-24 | MOUZ NXT          | L   | 0.116      | -            | -                | -                | -         |    -2.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4091 | 2024-02-21 | Sampi             | W   | 0.096      | -            | -                | -                | -         |     0.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4189 | 2024-02-17 | Zero Tenacity     | W   | 0.070      | -            | -                | -                | -         |     0.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4337 | 2024-02-11 | ARCRED            | W   | 0.030      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4339 | 2024-02-10 | Nemiga            | L   | 0.025      | -            | -                | -                | -         |    -0.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4347 | 2024-02-10 | AMKAL             | W   | 0.024      | -            | -                | -                | -         |     0.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4356 | 2024-02-09 | FORZE             | W   | 0.018      | -            | -                | -                | -         |     0.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4362 | 2024-02-09 | Insilio           | W   | 0.017      | -            | -                | -                | -         |     0.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4370 | 2024-02-08 | Nemiga            | L   | 0.012      | -            | -                | -                | -         |    -0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4374 | 2024-02-08 | FORZE             | W   | 0.010      | -            | -                | -                | -         |     0.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,500.50)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.845 | $9,365.00      | $7,908.87       |
| 2024-06-09 |      0.824 | $8,000.00      | $6,591.11       |
| 2024-05-18 |      0.678 | $5,000.00      | $3,388.89       |
| 2024-05-09 |      0.616 | $14,000.00     | $8,629.44       |
| 2024-05-02 |      0.571 | $12,500.00     | $7,135.42       |
| 2024-04-27 |      0.538 | $6,375.00      | $3,431.88       |
| 2024-04-06 |      0.395 | $5,000.00      | $1,976.39       |
| 2024-03-25 |      0.318 | $7,000.00      | $2,222.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
