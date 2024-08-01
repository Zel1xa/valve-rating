### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1176.4<br />
<br />
Final Rank Value (1176.4) = Starting Rank Value (1168.2) + Head To Head Adjustments (8.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.578[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.210[<sup>2</sup>](#table1)

The average of these factors is 0.373<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1168.2
- 400 + ( ( 0.373 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1168.2


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
|           98 |       49 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.554 (0.277)    | 0 (0.000) |     6.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           97 |       82 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.512 (0.256)    | 0 (0.000) |     3.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |       96 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -18.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |      276 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.614 (0.307)    | 0 (0.000) |     9.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      506 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      516 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      586 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      721 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      730 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      747 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.555 (0.199)    | 0 (0.000) |     5.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      771 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      774 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.521 (0.187)    | 0 (0.000) |     6.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      967 | 2024-06-14 | 3DMAX             | L   | 0.879      | -            | -                | -                | -         |    -6.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |     1002 | 2024-06-13 | Sampi             | W   | 0.872      | -            | -                | -                | 0 (0.000) |     3.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |     1019 | 2024-06-12 | CPH Wolves        | W   | 0.867      | -            | -                | -                | 0 (0.000) |     2.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |     1028 | 2024-06-12 | Astralis Talent   | W   | 0.866      | -            | -                | -                | -         |     1.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1297 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.827      | -            | -                | -                | -         |    -4.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1334 | 2024-06-06 | HEROIC            | L   | 0.825      | -            | -                | -                | -         |    -3.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1364 | 2024-06-05 | ENCE              | L   | 0.820      | -            | -                | -                | -         |    -8.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1385 | 2024-06-05 | Astralis          | W   | 0.819      | 0.715        | 0.359 (0.210)    | 0.385 (0.226)    | 1 (0.819) |    24.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1395 | 2024-06-05 | The MongolZ       | L   | 0.818      | -            | -                | -                | -         |    -0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1853 | 2024-05-20 | Monte             | L   | 0.711      | -            | -                | -                | -         |   -16.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1871 | 2024-05-19 | Passion UA        | W   | 0.706      | 0.500        | 0.173 (0.061)    | 1.000 (0.353)    | -         |     5.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1898 | 2024-05-18 | B8                | L   | 0.700      | -            | -                | -                | -         |   -13.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1907 | 2024-05-18 | Monte             | W   | 0.699      | -            | -                | -                | -         |     5.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1916 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.698      | 0.500        | -                | 0.563 (0.197)    | -         |     3.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1947 | 2024-05-17 | ex-Guild Eagles   | W   | 0.691      | -            | -                | -                | -         |     2.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1987 | 2024-05-16 | Passion UA        | L   | 0.684      | -            | -                | -                | -         |   -16.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     2038 | 2024-05-15 | Endpoint          | W   | 0.678      | -            | -                | -                | -         |     3.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2215 | 2024-05-09 | 1WIN              | W   | 0.639      | -            | -                | -                | -         |     3.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2240 | 2024-05-08 | Grannys Knockers  | W   | 0.632      | -            | -                | -                | -         |     1.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2258 | 2024-05-07 | 9 Pandas          | W   | 0.626      | -            | -                | -                | -         |     4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2272 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.620      | -            | -                | -                | -         |     4.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2286 | 2024-05-05 | Gaimin Gladiators | L   | 0.613      | -            | -                | -                | -         |   -14.56 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           64 |     2294 | 2024-05-05 | Come on now dawg  | W   | 0.612      | -            | -                | -                | -         |     0.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2347 | 2024-05-02 | fnatic            | W   | 0.593      | 0.384        | 0.292 (0.067)    | -                | -         |    12.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2383 | 2024-05-01 | 3DMAX             | W   | 0.585      | 0.384        | 0.505 (0.114)    | 1.000 (0.225)    | -         |    16.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2401 | 2024-04-30 | OG                | W   | 0.579      | 0.384        | 0.143 (0.032)    | -                | -         |     6.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           60 |     2426 | 2024-04-29 | 500               | W   | 0.572      | -            | -                | -                | -         |     1.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2454 | 2024-04-27 | 777               | W   | 0.561      | -            | -                | -                | -         |     1.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2458 | 2024-04-27 | JANO              | W   | 0.560      | -            | -                | -                | -         |     1.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2525 | 2024-04-25 | Passion UA        | W   | 0.545      | 0.384        | 0.173 (0.036)    | 1.000 (0.209)    | -         |     5.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2561 | 2024-04-23 | Gaimin Gladiators | W   | 0.532      | -            | -                | -                | -         |     5.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2566 | 2024-04-23 | BLEED             | W   | 0.531      | -            | -                | -                | -         |     6.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2621 | 2024-04-20 | Eternal Fire      | W   | 0.513      | 0.143        | 0.757 (0.056)    | -                | -         |    15.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2628 | 2024-04-20 | Cloud9            | W   | 0.512      | -            | -                | -                | -         |     7.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2668 | 2024-04-19 | Eternal Fire      | L   | 0.507      | -            | -                | -                | -         |    -0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2677 | 2024-04-19 | Cloud9            | W   | 0.506      | -            | -                | -                | -         |     7.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2704 | 2024-04-18 | ex-Guild Eagles   | W   | 0.500      | -            | -                | -                | -         |     2.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2708 | 2024-04-18 | RUBY              | W   | 0.500      | -            | -                | -                | -         |     4.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2717 | 2024-04-18 | GamerLegion       | W   | 0.500      | -            | -                | -                | -         |     8.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2762 | 2024-04-17 | Passion UA        | L   | 0.492      | -            | -                | -                | -         |    -9.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2800 | 2024-04-16 | ex-Guild Eagles   | L   | 0.486      | -            | -                | -                | -         |   -12.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2821 | 2024-04-15 | ex-Preasy         | W   | 0.479      | -            | -                | -                | -         |     2.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2838 | 2024-04-14 | UNiTY             | W   | 0.471      | -            | -                | -                | -         |     3.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2897 | 2024-04-11 | Enterprise        | W   | 0.451      | -            | -                | -                | -         |     3.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2940 | 2024-04-10 | Passion UA        | L   | 0.445      | -            | -                | -                | -         |    -8.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     3073 | 2024-04-06 | UNiTY             | W   | 0.417      | -            | -                | -                | -         |     3.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     3131 | 2024-04-04 | UNiTY             | W   | 0.405      | -            | -                | -                | -         |     3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     3222 | 2024-04-02 | Permitta          | W   | 0.391      | -            | -                | -                | -         |     3.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3231 | 2024-04-01 | Nexus             | L   | 0.385      | -            | -                | -                | -         |   -10.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3306 | 2024-03-27 | Rebels            | L   | 0.354      | -            | -                | -                | -         |    -7.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3345 | 2024-03-25 | Nexus             | W   | 0.340      | -            | -                | -                | -         |     1.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3369 | 2024-03-22 | Nemiga            | W   | 0.320      | 0.372        | 0.324 (0.039)    | -                | -         |     5.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3434 | 2024-03-19 | RUBY              | W   | 0.300      | -            | -                | -                | -         |     2.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3446 | 2024-03-18 | Insilio           | W   | 0.292      | -            | -                | -                | -         |     2.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3514 | 2024-03-15 | ECLOT             | W   | 0.271      | -            | -                | -                | -         |     3.79 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           31 |     3592 | 2024-03-13 | BLEED             | L   | 0.258      | -            | -                | -                | -         |    -5.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3640 | 2024-03-11 | Nemiga            | L   | 0.246      | -            | -                | -                | -         |    -3.59 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           29 |     3663 | 2024-03-10 | Sampi             | L   | 0.238      | -            | -                | -                | -         |    -6.03 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           28 |     3688 | 2024-03-09 | Permitta          | W   | 0.232      | -            | -                | -                | -         |     1.87 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3709 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.224      | -            | -                | -                | -         |    -5.04 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           26 |     3719 | 2024-03-07 | Insilio           | W   | 0.221      | -            | -                | -                | -         |     1.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3733 | 2024-03-07 | ex-sYnck          | W   | 0.219      | -            | -                | -                | -         |     0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3766 | 2024-03-06 | Alliance          | W   | 0.212      | -            | -                | -                | -         |     1.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3804 | 2024-03-05 | Johnny Speeds     | L   | 0.207      | -            | -                | -                | -         |    -1.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3813 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.205      | -            | -                | -                | -         |    -4.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3829 | 2024-03-04 | Entropiq          | L   | 0.198      | -            | -                | -                | -         |    -6.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3874 | 2024-03-02 | brazylijski luz   | W   | 0.185      | -            | -                | -                | -         |     0.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3909 | 2024-02-29 | JANO              | W   | 0.171      | -            | -                | -                | -         |     0.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3920 | 2024-02-28 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     0.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3935 | 2024-02-27 | V1dar             | L   | 0.160      | -            | -                | -                | -         |    -4.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3978 | 2024-02-25 | Sangal            | L   | 0.147      | -            | -                | -                | -         |    -2.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3984 | 2024-02-25 | PGE Turow         | L   | 0.145      | -            | -                | -                | -         |    -4.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     4026 | 2024-02-24 | MOUZ NXT          | L   | 0.138      | -            | -                | -                | -         |    -2.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4081 | 2024-02-21 | Sampi             | W   | 0.119      | -            | -                | -                | -         |     0.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4178 | 2024-02-17 | Zero Tenacity     | W   | 0.093      | -            | -                | -                | -         |     1.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4336 | 2024-02-11 | ARCRED            | W   | 0.052      | -            | -                | -                | -         |     0.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4338 | 2024-02-10 | Nemiga            | L   | 0.048      | -            | -                | -                | -         |    -0.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4346 | 2024-02-10 | AMKAL             | W   | 0.046      | -            | -                | -                | -         |     0.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4355 | 2024-02-09 | FORZE             | W   | 0.040      | -            | -                | -                | -         |     0.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4362 | 2024-02-09 | Insilio           | W   | 0.039      | -            | -                | -                | -         |     0.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4370 | 2024-02-08 | Nemiga            | L   | 0.034      | -            | -                | -                | -         |    -0.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4374 | 2024-02-08 | FORZE             | W   | 0.033      | -            | -                | -                | -         |     0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4405 | 2024-02-05 | Entropiq          | W   | 0.012      | -            | -                | -                | -         |     0.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4422 | 2024-02-04 | TMVG              | L   | 0.006      | -            | -                | -                | -         |    -0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4437 | 2024-02-03 | showmakerz        | W   | 0.001      | -            | -                | -                | -         |     0.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4441 | 2024-02-03 | Gaimin Gladiators | W   | 0.000      | -            | -                | -                | -         |     0.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,994.72)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.867 | $9,365.00      | $8,116.98       |
| 2024-06-09 |      0.846 | $8,000.00      | $6,768.89       |
| 2024-05-18 |      0.700 | $5,000.00      | $3,500.00       |
| 2024-05-09 |      0.639 | $14,000.00     | $8,940.56       |
| 2024-05-02 |      0.593 | $12,500.00     | $7,413.19       |
| 2024-04-27 |      0.561 | $6,375.00      | $3,573.54       |
| 2024-04-06 |      0.417 | $5,000.00      | $2,087.50       |
| 2024-03-25 |      0.340 | $7,000.00      | $2,378.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
