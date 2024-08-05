### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1126.5<br />
<br />
Final Rank Value (1126.5) = Starting Rank Value (1160.2) + Head To Head Adjustments (-33.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.2
- 400 + ( ( 0.371 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1160.2


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
|           97 |        3 | 2024-08-05 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -30.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |        7 | 2024-08-05 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |       13 | 2024-08-05 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      193 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.553 (0.276)    | 0 (0.000) |     6.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      224 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     3.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      236 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      417 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.305)    | 0 (0.000) |    10.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      638 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      648 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      718 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      845 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      854 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      871 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.514 (0.184)    | 0 (0.000) |     4.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      895 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      898 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.533 (0.191)    | 0 (0.000) |     5.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1102 | 2024-06-14 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -5.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1137 | 2024-06-13 | Sampi             | W   | 0.845      | -            | -                | -                | 0 (0.000) |     3.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1154 | 2024-06-12 | CPH Wolves        | W   | 0.840      | -            | -                | -                | -         |     2.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1163 | 2024-06-12 | Astralis Talent   | W   | 0.839      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1419 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.800      | -            | -                | -                | -         |    -2.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1455 | 2024-06-06 | HEROIC            | L   | 0.798      | -            | -                | -                | -         |    -3.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1484 | 2024-06-05 | ENCE              | L   | 0.794      | -            | -                | -                | -         |    -7.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1504 | 2024-06-05 | Astralis          | W   | 0.792      | 0.715        | 0.389 (0.221)    | 0.413 (0.234)    | 1 (0.792) |    23.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1514 | 2024-06-05 | The MongolZ       | L   | 0.791      | -            | -                | -                | -         |    -0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1949 | 2024-05-20 | Monte             | L   | 0.684      | -            | -                | -                | -         |   -15.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1962 | 2024-05-19 | Passion UA        | W   | 0.680      | 0.500        | 0.173 (0.059)    | 1.000 (0.340)    | -         |     5.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1989 | 2024-05-18 | B8                | L   | 0.673      | -            | -                | -                | -         |   -12.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1998 | 2024-05-18 | Monte             | W   | 0.672      | -            | -                | -                | -         |     5.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2006 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.671      | 0.500        | -                | 0.550 (0.185)    | -         |     3.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2037 | 2024-05-17 | ex-Guild Eagles   | W   | 0.665      | -            | -                | -                | -         |     2.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2077 | 2024-05-16 | Passion UA        | L   | 0.658      | -            | -                | -                | -         |   -15.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2124 | 2024-05-15 | Endpoint          | W   | 0.651      | -            | -                | -                | -         |     3.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2296 | 2024-05-09 | 1WIN              | W   | 0.612      | -            | -                | -                | -         |     4.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2319 | 2024-05-08 | Grannys Knockers  | W   | 0.605      | -            | -                | -                | -         |     1.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2337 | 2024-05-07 | 9 Pandas          | W   | 0.599      | -            | -                | -                | -         |     4.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2351 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.593      | -            | -                | -                | -         |     4.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2365 | 2024-05-05 | Gaimin Gladiators | L   | 0.587      | -            | -                | -                | -         |   -14.14 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2373 | 2024-05-05 | Come on now dawg  | W   | 0.586      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2425 | 2024-05-02 | fnatic            | W   | 0.566      | 0.384        | 0.371 (0.081)    | -                | -         |    15.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2460 | 2024-05-01 | 3DMAX             | W   | 0.558      | 0.384        | 0.508 (0.109)    | 1.000 (0.215)    | -         |    16.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2477 | 2024-04-30 | OG                | W   | 0.552      | 0.384        | 0.138 (0.029)    | -                | -         |     6.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2502 | 2024-04-29 | 500               | W   | 0.545      | -            | -                | -                | -         |     1.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2530 | 2024-04-27 | 777               | W   | 0.534      | -            | -                | -                | -         |     1.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2534 | 2024-04-27 | JANO              | W   | 0.533      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2601 | 2024-04-25 | Passion UA        | W   | 0.518      | 0.384        | 0.173 (0.034)    | 1.000 (0.199)    | -         |     4.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2635 | 2024-04-23 | Gaimin Gladiators | W   | 0.506      | -            | -                | -                | -         |     5.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2640 | 2024-04-23 | BLEED             | W   | 0.505      | -            | -                | -                | -         |     5.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2691 | 2024-04-20 | Eternal Fire      | W   | 0.487      | 0.143        | 0.740 (0.051)    | -                | -         |    14.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2698 | 2024-04-20 | Cloud9            | W   | 0.486      | -            | -                | -                | -         |     6.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2737 | 2024-04-19 | Eternal Fire      | L   | 0.480      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2746 | 2024-04-19 | Cloud9            | W   | 0.479      | -            | -                | -                | -         |     6.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2772 | 2024-04-18 | ex-Guild Eagles   | W   | 0.474      | -            | -                | -                | -         |     2.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2776 | 2024-04-18 | RUBY              | W   | 0.473      | -            | -                | -                | -         |     3.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2785 | 2024-04-18 | GamerLegion       | W   | 0.473      | -            | -                | -                | -         |     7.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2829 | 2024-04-17 | Passion UA        | L   | 0.466      | -            | -                | -                | -         |    -8.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2866 | 2024-04-16 | ex-Guild Eagles   | L   | 0.459      | -            | -                | -                | -         |   -12.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2887 | 2024-04-15 | ex-Preasy         | W   | 0.452      | -            | -                | -                | -         |     2.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2904 | 2024-04-14 | UNiTY             | W   | 0.444      | -            | -                | -                | -         |     3.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2962 | 2024-04-11 | Enterprise        | W   | 0.424      | -            | -                | -                | -         |     3.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3005 | 2024-04-10 | Passion UA        | L   | 0.418      | -            | -                | -                | -         |    -8.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3138 | 2024-04-06 | UNiTY             | W   | 0.391      | -            | -                | -                | -         |     3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3195 | 2024-04-04 | UNiTY             | W   | 0.378      | -            | -                | -                | -         |     3.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3279 | 2024-04-02 | Permitta          | W   | 0.364      | -            | -                | -                | -         |     3.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3288 | 2024-04-01 | Nexus             | L   | 0.358      | -            | -                | -                | -         |    -9.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3362 | 2024-03-27 | Rebels            | L   | 0.327      | -            | -                | -                | -         |    -7.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3397 | 2024-03-25 | Nexus             | W   | 0.313      | -            | -                | -                | -         |     1.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3421 | 2024-03-22 | Nemiga            | W   | 0.294      | 0.372        | 0.316 (0.034)    | -                | -         |     5.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3486 | 2024-03-19 | RUBY              | W   | 0.274      | -            | -                | -                | -         |     2.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3498 | 2024-03-18 | Insilio           | W   | 0.266      | -            | -                | -                | -         |     1.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3566 | 2024-03-15 | ECLOT             | W   | 0.245      | -            | -                | -                | -         |     4.58 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3640 | 2024-03-13 | BLEED             | L   | 0.231      | -            | -                | -                | -         |    -5.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3687 | 2024-03-11 | Nemiga            | L   | 0.219      | -            | -                | -                | -         |    -3.10 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3710 | 2024-03-10 | Sampi             | L   | 0.212      | -            | -                | -                | -         |    -5.37 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3734 | 2024-03-09 | Permitta          | W   | 0.205      | -            | -                | -                | -         |     1.73 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3755 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.198      | -            | -                | -                | -         |    -4.44 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3765 | 2024-03-07 | Insilio           | W   | 0.194      | -            | -                | -                | -         |     1.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3779 | 2024-03-07 | ex-sYnck          | W   | 0.192      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3811 | 2024-03-06 | Alliance          | W   | 0.185      | -            | -                | -                | -         |     0.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3845 | 2024-03-05 | Johnny Speeds     | L   | 0.180      | -            | -                | -                | -         |    -1.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3854 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.178      | -            | -                | -                | -         |    -4.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3870 | 2024-03-04 | Entropiq          | L   | 0.171      | -            | -                | -                | -         |    -5.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3915 | 2024-03-02 | brazylijski luz   | W   | 0.159      | -            | -                | -                | -         |     0.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3949 | 2024-02-29 | JANO              | W   | 0.145      | -            | -                | -                | -         |     0.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3959 | 2024-02-28 | Sampi             | W   | 0.139      | -            | -                | -                | -         |     0.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3974 | 2024-02-27 | V1dar             | L   | 0.133      | -            | -                | -                | -         |    -4.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4015 | 2024-02-25 | Sangal            | L   | 0.120      | -            | -                | -                | -         |    -1.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4021 | 2024-02-25 | PGE Turow         | L   | 0.119      | -            | -                | -                | -         |    -3.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4061 | 2024-02-24 | MOUZ NXT          | L   | 0.111      | -            | -                | -                | -         |    -2.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4112 | 2024-02-21 | Sampi             | W   | 0.092      | -            | -                | -                | -         |     0.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4210 | 2024-02-17 | Zero Tenacity     | W   | 0.066      | -            | -                | -                | -         |     0.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4358 | 2024-02-11 | ARCRED            | W   | 0.025      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4360 | 2024-02-10 | Nemiga            | L   | 0.021      | -            | -                | -                | -         |    -0.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4368 | 2024-02-10 | AMKAL             | W   | 0.019      | -            | -                | -                | -         |     0.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4377 | 2024-02-09 | FORZE             | W   | 0.014      | -            | -                | -                | -         |     0.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4383 | 2024-02-09 | Insilio           | W   | 0.013      | -            | -                | -                | -         |     0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4391 | 2024-02-08 | Nemiga            | L   | 0.007      | -            | -                | -                | -         |    -0.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4395 | 2024-02-08 | FORZE             | W   | 0.006      | -            | -                | -                | -         |     0.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,201.65)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.840 | $9,365.00      | $7,867.25       |
| 2024-06-09 |      0.819 | $8,000.00      | $6,555.56       |
| 2024-05-18 |      0.673 | $5,000.00      | $3,366.67       |
| 2024-05-09 |      0.612 | $14,000.00     | $8,567.22       |
| 2024-05-02 |      0.566 | $12,500.00     | $7,079.86       |
| 2024-04-27 |      0.534 | $6,375.00      | $3,403.54       |
| 2024-04-06 |      0.391 | $5,000.00      | $1,954.17       |
| 2024-03-25 |      0.313 | $7,000.00      | $2,191.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
