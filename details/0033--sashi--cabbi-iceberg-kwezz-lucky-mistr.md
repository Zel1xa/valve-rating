### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1177.2<br />
<br />
Final Rank Value (1177.2) = Starting Rank Value (1160.7) + Head To Head Adjustments (16.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.372<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.7
- 400 + ( ( 0.372 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1160.7


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
|           94 |      142 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     6.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      175 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     3.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      188 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      368 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.309)    | 0 (0.000) |    10.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      589 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      599 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      669 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      796 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      805 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      822 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | 0 (0.000) |     4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      846 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      849 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.537 (0.192)    | 0 (0.000) |     5.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1053 | 2024-06-14 | 3DMAX             | L   | 0.860      | -            | -                | -                | -         |    -5.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1088 | 2024-06-13 | Sampi             | W   | 0.853      | -            | -                | -                | 0 (0.000) |     3.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1105 | 2024-06-12 | CPH Wolves        | W   | 0.848      | -            | -                | -                | 0 (0.000) |     2.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1114 | 2024-06-12 | Astralis Talent   | W   | 0.847      | -            | -                | -                | -         |     1.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1370 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.808      | -            | -                | -                | -         |    -2.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1406 | 2024-06-06 | HEROIC            | L   | 0.806      | -            | -                | -                | -         |    -3.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1435 | 2024-06-05 | ENCE              | L   | 0.802      | -            | -                | -                | -         |    -8.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1455 | 2024-06-05 | Astralis          | W   | 0.800      | 0.715        | 0.391 (0.224)    | 0.421 (0.241)    | 1 (0.800) |    24.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1465 | 2024-06-05 | The MongolZ       | L   | 0.799      | -            | -                | -                | -         |    -0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1900 | 2024-05-20 | Monte             | L   | 0.692      | -            | -                | -                | -         |   -15.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1913 | 2024-05-19 | Passion UA        | W   | 0.687      | 0.500        | 0.172 (0.059)    | 1.000 (0.344)    | -         |     5.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1940 | 2024-05-18 | B8                | L   | 0.681      | -            | -                | -                | -         |   -12.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1949 | 2024-05-18 | Monte             | W   | 0.680      | -            | -                | -                | -         |     5.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1957 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.679      | 0.500        | -                | 0.560 (0.190)    | -         |     3.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     1988 | 2024-05-17 | ex-Guild Eagles   | W   | 0.673      | -            | -                | -                | -         |     2.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2028 | 2024-05-16 | Passion UA        | L   | 0.666      | -            | -                | -                | -         |   -15.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2075 | 2024-05-15 | Endpoint          | W   | 0.659      | -            | -                | -                | -         |     3.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2247 | 2024-05-09 | 1WIN              | W   | 0.620      | -            | -                | -                | -         |     4.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2270 | 2024-05-08 | Grannys Knockers  | W   | 0.613      | -            | -                | -                | -         |     1.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2288 | 2024-05-07 | 9 Pandas          | W   | 0.607      | -            | -                | -                | -         |     4.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2302 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.601      | -            | -                | -                | -         |     4.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2316 | 2024-05-05 | Gaimin Gladiators | L   | 0.594      | -            | -                | -                | -         |   -14.32 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2324 | 2024-05-05 | Come on now dawg  | W   | 0.594      | -            | -                | -                | -         |     0.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2376 | 2024-05-02 | fnatic            | W   | 0.574      | 0.384        | 0.371 (0.082)    | -                | -         |    15.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2411 | 2024-05-01 | 3DMAX             | W   | 0.566      | 0.384        | 0.506 (0.110)    | 1.000 (0.218)    | -         |    16.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2428 | 2024-04-30 | OG                | W   | 0.560      | 0.384        | 0.139 (0.030)    | -                | -         |     6.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2453 | 2024-04-29 | 500               | W   | 0.553      | -            | -                | -                | -         |     1.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2481 | 2024-04-27 | 777               | W   | 0.542      | -            | -                | -                | -         |     1.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2485 | 2024-04-27 | JANO              | W   | 0.541      | -            | -                | -                | -         |     1.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2552 | 2024-04-25 | Passion UA        | W   | 0.526      | 0.384        | 0.172 (0.035)    | 1.000 (0.202)    | -         |     4.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2586 | 2024-04-23 | Gaimin Gladiators | W   | 0.514      | -            | -                | -                | -         |     5.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2591 | 2024-04-23 | BLEED             | W   | 0.513      | -            | -                | -                | -         |     5.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2642 | 2024-04-20 | Eternal Fire      | W   | 0.495      | 0.143        | 0.742 (0.052)    | -                | -         |    14.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2649 | 2024-04-20 | Cloud9            | W   | 0.494      | -            | -                | -                | -         |     6.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2688 | 2024-04-19 | Eternal Fire      | L   | 0.488      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2697 | 2024-04-19 | Cloud9            | W   | 0.487      | -            | -                | -                | -         |     6.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2723 | 2024-04-18 | ex-Guild Eagles   | W   | 0.482      | -            | -                | -                | -         |     2.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2727 | 2024-04-18 | RUBY              | W   | 0.481      | -            | -                | -                | -         |     4.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2736 | 2024-04-18 | GamerLegion       | W   | 0.481      | -            | -                | -                | -         |     7.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2780 | 2024-04-17 | Passion UA        | L   | 0.473      | -            | -                | -                | -         |    -9.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2817 | 2024-04-16 | ex-Guild Eagles   | L   | 0.467      | -            | -                | -                | -         |   -12.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2838 | 2024-04-15 | ex-Preasy         | W   | 0.460      | -            | -                | -                | -         |     2.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2855 | 2024-04-14 | UNiTY             | W   | 0.452      | -            | -                | -                | -         |     3.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2913 | 2024-04-11 | Enterprise        | W   | 0.432      | -            | -                | -                | -         |     3.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2956 | 2024-04-10 | Passion UA        | L   | 0.426      | -            | -                | -                | -         |    -8.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3089 | 2024-04-06 | UNiTY             | W   | 0.399      | -            | -                | -                | -         |     3.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3146 | 2024-04-04 | UNiTY             | W   | 0.386      | -            | -                | -                | -         |     3.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3230 | 2024-04-02 | Permitta          | W   | 0.372      | -            | -                | -                | -         |     3.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3239 | 2024-04-01 | Nexus             | L   | 0.366      | -            | -                | -                | -         |    -9.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3313 | 2024-03-27 | Rebels            | L   | 0.335      | -            | -                | -                | -         |    -7.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3348 | 2024-03-25 | Nexus             | W   | 0.321      | -            | -                | -                | -         |     1.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3372 | 2024-03-22 | Nemiga            | W   | 0.302      | 0.372        | 0.317 (0.036)    | -                | -         |     4.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3437 | 2024-03-19 | RUBY              | W   | 0.282      | -            | -                | -                | -         |     2.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3449 | 2024-03-18 | Insilio           | W   | 0.274      | -            | -                | -                | -         |     1.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3517 | 2024-03-15 | ECLOT             | W   | 0.253      | -            | -                | -                | -         |     4.74 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3591 | 2024-03-13 | BLEED             | L   | 0.239      | -            | -                | -                | -         |    -5.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3638 | 2024-03-11 | Nemiga            | L   | 0.227      | -            | -                | -                | -         |    -3.40 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3661 | 2024-03-10 | Sampi             | L   | 0.220      | -            | -                | -                | -         |    -5.56 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3685 | 2024-03-09 | Permitta          | W   | 0.213      | -            | -                | -                | -         |     1.79 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3706 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.206      | -            | -                | -                | -         |    -4.61 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3716 | 2024-03-07 | Insilio           | W   | 0.202      | -            | -                | -                | -         |     1.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3730 | 2024-03-07 | ex-sYnck          | W   | 0.200      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3762 | 2024-03-06 | Alliance          | W   | 0.193      | -            | -                | -                | -         |     1.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3796 | 2024-03-05 | Johnny Speeds     | L   | 0.188      | -            | -                | -                | -         |    -1.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3805 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.186      | -            | -                | -                | -         |    -4.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3821 | 2024-03-04 | Entropiq          | L   | 0.179      | -            | -                | -                | -         |    -5.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3866 | 2024-03-02 | brazylijski luz   | W   | 0.167      | -            | -                | -                | -         |     0.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3900 | 2024-02-29 | JANO              | W   | 0.153      | -            | -                | -                | -         |     0.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3910 | 2024-02-28 | Sampi             | W   | 0.147      | -            | -                | -                | -         |     0.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3925 | 2024-02-27 | V1dar             | L   | 0.141      | -            | -                | -                | -         |    -4.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     3966 | 2024-02-25 | Sangal            | L   | 0.128      | -            | -                | -                | -         |    -2.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     3972 | 2024-02-25 | PGE Turow         | L   | 0.127      | -            | -                | -                | -         |    -3.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4012 | 2024-02-24 | MOUZ NXT          | L   | 0.119      | -            | -                | -                | -         |    -2.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4063 | 2024-02-21 | Sampi             | W   | 0.100      | -            | -                | -                | -         |     0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4161 | 2024-02-17 | Zero Tenacity     | W   | 0.074      | -            | -                | -                | -         |     0.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4309 | 2024-02-11 | ARCRED            | W   | 0.033      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4311 | 2024-02-10 | Nemiga            | L   | 0.029      | -            | -                | -                | -         |    -0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4319 | 2024-02-10 | AMKAL             | W   | 0.027      | -            | -                | -                | -         |     0.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4328 | 2024-02-09 | FORZE             | W   | 0.022      | -            | -                | -                | -         |     0.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4334 | 2024-02-09 | Insilio           | W   | 0.021      | -            | -                | -                | -         |     0.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4342 | 2024-02-08 | Nemiga            | L   | 0.015      | -            | -                | -                | -         |    -0.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4346 | 2024-02-08 | FORZE             | W   | 0.014      | -            | -                | -                | -         |     0.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,732.41)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.848 | $9,365.00      | $7,941.17       |
| 2024-06-09 |      0.827 | $8,000.00      | $6,618.70       |
| 2024-05-18 |      0.681 | $5,000.00      | $3,406.13       |
| 2024-05-09 |      0.620 | $14,000.00     | $8,677.73       |
| 2024-05-02 |      0.574 | $12,500.00     | $7,178.53       |
| 2024-04-27 |      0.542 | $6,375.00      | $3,453.86       |
| 2024-04-06 |      0.399 | $5,000.00      | $1,993.63       |
| 2024-03-25 |      0.321 | $7,000.00      | $2,246.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
