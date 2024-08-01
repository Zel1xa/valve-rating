### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1176.5<br />
<br />
Final Rank Value (1176.5) = Starting Rank Value (1168.2) + Head To Head Adjustments (8.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.578[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
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
|           97 |       54 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.554 (0.277)    | 0 (0.000) |     6.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |       85 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.512 (0.256)    | 0 (0.000) |     3.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |       98 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -18.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      278 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.614 (0.307)    | 0 (0.000) |     9.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      508 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      518 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      588 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      723 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      732 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      749 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.555 (0.199)    | 0 (0.000) |     5.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      773 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      776 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | 0 (0.000) |     6.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      969 | 2024-06-14 | 3DMAX             | L   | 0.879      | -            | -                | -                | -         |    -6.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |     1004 | 2024-06-13 | Sampi             | W   | 0.872      | -            | -                | -                | 0 (0.000) |     3.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |     1021 | 2024-06-12 | CPH Wolves        | W   | 0.866      | -            | -                | -                | 0 (0.000) |     2.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1030 | 2024-06-12 | Astralis Talent   | W   | 0.866      | -            | -                | -                | -         |     1.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1299 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.827      | -            | -                | -                | -         |    -4.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1336 | 2024-06-06 | HEROIC            | L   | 0.825      | -            | -                | -                | -         |    -3.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1366 | 2024-06-05 | ENCE              | L   | 0.820      | -            | -                | -                | -         |    -8.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1387 | 2024-06-05 | Astralis          | W   | 0.819      | 0.715        | 0.359 (0.210)    | 0.385 (0.225)    | 1 (0.819) |    24.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1397 | 2024-06-05 | The MongolZ       | L   | 0.818      | -            | -                | -                | -         |    -0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1855 | 2024-05-20 | Monte             | L   | 0.711      | -            | -                | -                | -         |   -16.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1873 | 2024-05-19 | Passion UA        | W   | 0.706      | 0.500        | 0.173 (0.061)    | 1.000 (0.353)    | -         |     5.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1900 | 2024-05-18 | B8                | L   | 0.700      | -            | -                | -                | -         |   -13.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1909 | 2024-05-18 | Monte             | W   | 0.699      | -            | -                | -                | -         |     5.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1918 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.698      | 0.500        | -                | 0.563 (0.196)    | -         |     3.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1949 | 2024-05-17 | ex-Guild Eagles   | W   | 0.691      | -            | -                | -                | -         |     2.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1989 | 2024-05-16 | Passion UA        | L   | 0.684      | -            | -                | -                | -         |   -16.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2040 | 2024-05-15 | Endpoint          | W   | 0.678      | -            | -                | -                | -         |     3.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2217 | 2024-05-09 | 1WIN              | W   | 0.638      | -            | -                | -                | -         |     3.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2242 | 2024-05-08 | Grannys Knockers  | W   | 0.632      | -            | -                | -                | -         |     1.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2260 | 2024-05-07 | 9 Pandas          | W   | 0.625      | -            | -                | -                | -         |     4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2274 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.619      | -            | -                | -                | -         |     4.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2288 | 2024-05-05 | Gaimin Gladiators | L   | 0.613      | -            | -                | -                | -         |   -14.56 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           63 |     2296 | 2024-05-05 | Come on now dawg  | W   | 0.612      | -            | -                | -                | -         |     0.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2349 | 2024-05-02 | fnatic            | W   | 0.593      | 0.384        | 0.292 (0.067)    | -                | -         |    12.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2385 | 2024-05-01 | 3DMAX             | W   | 0.585      | 0.384        | 0.505 (0.114)    | 1.000 (0.225)    | -         |    16.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           60 |     2403 | 2024-04-30 | OG                | W   | 0.579      | 0.384        | 0.143 (0.032)    | -                | -         |     6.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2428 | 2024-04-29 | 500               | W   | 0.571      | -            | -                | -                | -         |     1.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2456 | 2024-04-27 | 777               | W   | 0.560      | -            | -                | -                | -         |     1.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2460 | 2024-04-27 | JANO              | W   | 0.560      | -            | -                | -                | -         |     1.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2527 | 2024-04-25 | Passion UA        | W   | 0.545      | 0.384        | 0.173 (0.036)    | 1.000 (0.209)    | -         |     5.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2563 | 2024-04-23 | Gaimin Gladiators | W   | 0.532      | -            | -                | -                | -         |     5.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2568 | 2024-04-23 | BLEED             | W   | 0.531      | -            | -                | -                | -         |     6.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2623 | 2024-04-20 | Eternal Fire      | W   | 0.513      | 0.143        | 0.757 (0.055)    | -                | -         |    15.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2630 | 2024-04-20 | Cloud9            | W   | 0.512      | -            | -                | -                | -         |     7.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2670 | 2024-04-19 | Eternal Fire      | L   | 0.506      | -            | -                | -                | -         |    -0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2679 | 2024-04-19 | Cloud9            | W   | 0.505      | -            | -                | -                | -         |     6.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2706 | 2024-04-18 | ex-Guild Eagles   | W   | 0.500      | -            | -                | -                | -         |     2.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2710 | 2024-04-18 | RUBY              | W   | 0.500      | -            | -                | -                | -         |     4.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2719 | 2024-04-18 | GamerLegion       | W   | 0.499      | -            | -                | -                | -         |     8.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2764 | 2024-04-17 | Passion UA        | L   | 0.492      | -            | -                | -                | -         |    -9.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2802 | 2024-04-16 | ex-Guild Eagles   | L   | 0.485      | -            | -                | -                | -         |   -12.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2823 | 2024-04-15 | ex-Preasy         | W   | 0.478      | -            | -                | -                | -         |     2.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2840 | 2024-04-14 | UNiTY             | W   | 0.471      | -            | -                | -                | -         |     3.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2899 | 2024-04-11 | Enterprise        | W   | 0.451      | -            | -                | -                | -         |     3.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2942 | 2024-04-10 | Passion UA        | L   | 0.445      | -            | -                | -                | -         |    -8.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     3075 | 2024-04-06 | UNiTY             | W   | 0.417      | -            | -                | -                | -         |     3.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     3133 | 2024-04-04 | UNiTY             | W   | 0.405      | -            | -                | -                | -         |     3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3224 | 2024-04-02 | Permitta          | W   | 0.391      | -            | -                | -                | -         |     3.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3233 | 2024-04-01 | Nexus             | L   | 0.384      | -            | -                | -                | -         |   -10.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3308 | 2024-03-27 | Rebels            | L   | 0.353      | -            | -                | -                | -         |    -7.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3347 | 2024-03-25 | Nexus             | W   | 0.339      | -            | -                | -                | -         |     1.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3371 | 2024-03-22 | Nemiga            | W   | 0.320      | 0.372        | 0.324 (0.039)    | -                | -         |     5.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3436 | 2024-03-19 | RUBY              | W   | 0.300      | -            | -                | -                | -         |     2.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3448 | 2024-03-18 | Insilio           | W   | 0.292      | -            | -                | -                | -         |     1.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3516 | 2024-03-15 | ECLOT             | W   | 0.271      | -            | -                | -                | -         |     3.79 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           30 |     3594 | 2024-03-13 | BLEED             | L   | 0.258      | -            | -                | -                | -         |    -5.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3642 | 2024-03-11 | Nemiga            | L   | 0.246      | -            | -                | -                | -         |    -3.58 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           28 |     3665 | 2024-03-10 | Sampi             | L   | 0.238      | -            | -                | -                | -         |    -6.02 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           27 |     3690 | 2024-03-09 | Permitta          | W   | 0.232      | -            | -                | -                | -         |     1.84 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           26 |     3711 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.224      | -            | -                | -                | -         |    -5.03 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3721 | 2024-03-07 | Insilio           | W   | 0.220      | -            | -                | -                | -         |     1.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3735 | 2024-03-07 | ex-sYnck          | W   | 0.219      | -            | -                | -                | -         |     0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3768 | 2024-03-06 | Alliance          | W   | 0.211      | -            | -                | -                | -         |     1.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3806 | 2024-03-05 | Johnny Speeds     | L   | 0.206      | -            | -                | -                | -         |    -1.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3815 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.204      | -            | -                | -                | -         |    -4.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3831 | 2024-03-04 | Entropiq          | L   | 0.198      | -            | -                | -                | -         |    -6.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3876 | 2024-03-02 | brazylijski luz   | W   | 0.185      | -            | -                | -                | -         |     0.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3911 | 2024-02-29 | JANO              | W   | 0.171      | -            | -                | -                | -         |     0.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3922 | 2024-02-28 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     0.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3937 | 2024-02-27 | V1dar             | L   | 0.160      | -            | -                | -                | -         |    -4.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3980 | 2024-02-25 | Sangal            | L   | 0.147      | -            | -                | -                | -         |    -2.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3986 | 2024-02-25 | PGE Turow         | L   | 0.145      | -            | -                | -                | -         |    -4.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4028 | 2024-02-24 | MOUZ NXT          | L   | 0.138      | -            | -                | -                | -         |    -2.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4083 | 2024-02-21 | Sampi             | W   | 0.118      | -            | -                | -                | -         |     0.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4180 | 2024-02-17 | Zero Tenacity     | W   | 0.092      | -            | -                | -                | -         |     1.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4338 | 2024-02-11 | ARCRED            | W   | 0.052      | -            | -                | -                | -         |     0.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4340 | 2024-02-10 | Nemiga            | L   | 0.047      | -            | -                | -                | -         |    -0.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4348 | 2024-02-10 | AMKAL             | W   | 0.046      | -            | -                | -                | -         |     0.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4357 | 2024-02-09 | FORZE             | W   | 0.040      | -            | -                | -                | -         |     0.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4364 | 2024-02-09 | Insilio           | W   | 0.039      | -            | -                | -                | -         |     0.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4372 | 2024-02-08 | Nemiga            | L   | 0.033      | -            | -                | -                | -         |    -0.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4376 | 2024-02-08 | FORZE             | W   | 0.032      | -            | -                | -                | -         |     0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4407 | 2024-02-05 | Entropiq          | W   | 0.011      | -            | -                | -                | -         |     0.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4424 | 2024-02-04 | TMVG              | L   | 0.005      | -            | -                | -                | -         |    -0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4439 | 2024-02-03 | showmakerz        | W   | 0.000      | -            | -                | -                | -         |     0.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,976.04)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.866 | $9,365.00      | $8,114.38       |
| 2024-06-09 |      0.846 | $8,000.00      | $6,766.67       |
| 2024-05-18 |      0.700 | $5,000.00      | $3,498.61       |
| 2024-05-09 |      0.638 | $14,000.00     | $8,936.67       |
| 2024-05-02 |      0.593 | $12,500.00     | $7,409.72       |
| 2024-04-27 |      0.560 | $6,375.00      | $3,571.77       |
| 2024-04-06 |      0.417 | $5,000.00      | $2,086.11       |
| 2024-03-25 |      0.339 | $7,000.00      | $2,376.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
