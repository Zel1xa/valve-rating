### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.8<br />
<br />
Final Rank Value (1155.8) = Starting Rank Value (1160.3) + Head To Head Adjustments (-4.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.3
- 400 + ( ( 0.371 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1160.3


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
|           96 |        0 | 2024-08-05 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |        5 | 2024-08-05 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      185 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.559 (0.280)    | 0 (0.000) |     6.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      216 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.507 (0.253)    | 0 (0.000) |     3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      228 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      409 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.618 (0.309)    | 0 (0.000) |    10.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      630 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      640 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      710 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      837 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      846 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      863 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.520 (0.186)    | 0 (0.000) |     4.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      887 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      890 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.539 (0.193)    | 0 (0.000) |     5.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1094 | 2024-06-14 | 3DMAX             | L   | 0.853      | -            | -                | -                | -         |    -5.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1129 | 2024-06-13 | Sampi             | W   | 0.847      | -            | -                | -                | 0 (0.000) |     3.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1146 | 2024-06-12 | CPH Wolves        | W   | 0.841      | -            | -                | -                | -         |     2.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1155 | 2024-06-12 | Astralis Talent   | W   | 0.841      | -            | -                | -                | -         |     1.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1411 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.802      | -            | -                | -                | -         |    -2.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1447 | 2024-06-06 | HEROIC            | L   | 0.799      | -            | -                | -                | -         |    -3.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1476 | 2024-06-05 | ENCE              | L   | 0.795      | -            | -                | -                | -         |    -7.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1496 | 2024-06-05 | Astralis          | W   | 0.794      | 0.715        | 0.390 (0.221)    | 0.419 (0.238)    | 1 (0.794) |    23.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1506 | 2024-06-05 | The MongolZ       | L   | 0.792      | -            | -                | -                | -         |    -0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1941 | 2024-05-20 | Monte             | L   | 0.686      | -            | -                | -                | -         |   -15.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1954 | 2024-05-19 | Passion UA        | W   | 0.681      | 0.500        | 0.173 (0.059)    | 1.000 (0.340)    | -         |     5.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1981 | 2024-05-18 | B8                | L   | 0.674      | -            | -                | -                | -         |   -12.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1990 | 2024-05-18 | Monte             | W   | 0.673      | -            | -                | -                | -         |     5.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1998 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.672      | 0.500        | -                | 0.557 (0.187)    | -         |     3.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2029 | 2024-05-17 | ex-Guild Eagles   | W   | 0.666      | -            | -                | -                | -         |     2.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2069 | 2024-05-16 | Passion UA        | L   | 0.659      | -            | -                | -                | -         |   -15.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2116 | 2024-05-15 | Endpoint          | W   | 0.652      | -            | -                | -                | -         |     3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2288 | 2024-05-09 | 1WIN              | W   | 0.613      | -            | -                | -                | -         |     4.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2311 | 2024-05-08 | Grannys Knockers  | W   | 0.606      | -            | -                | -                | -         |     1.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2329 | 2024-05-07 | 9 Pandas          | W   | 0.600      | -            | -                | -                | -         |     4.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2343 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.594      | -            | -                | -                | -         |     4.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2357 | 2024-05-05 | Gaimin Gladiators | L   | 0.588      | -            | -                | -                | -         |   -14.16 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2365 | 2024-05-05 | Come on now dawg  | W   | 0.587      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2417 | 2024-05-02 | fnatic            | W   | 0.568      | 0.384        | 0.371 (0.081)    | -                | -         |    15.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2452 | 2024-05-01 | 3DMAX             | W   | 0.559      | 0.384        | 0.508 (0.109)    | 1.000 (0.215)    | -         |    16.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2469 | 2024-04-30 | OG                | W   | 0.554      | 0.384        | 0.138 (0.029)    | -                | -         |     6.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2494 | 2024-04-29 | 500               | W   | 0.546      | -            | -                | -                | -         |     1.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2522 | 2024-04-27 | 777               | W   | 0.535      | -            | -                | -                | -         |     1.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2526 | 2024-04-27 | JANO              | W   | 0.534      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2593 | 2024-04-25 | Passion UA        | W   | 0.519      | 0.384        | 0.173 (0.034)    | 1.000 (0.200)    | -         |     4.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2627 | 2024-04-23 | Gaimin Gladiators | W   | 0.507      | -            | -                | -                | -         |     5.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2632 | 2024-04-23 | BLEED             | W   | 0.506      | -            | -                | -                | -         |     5.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2683 | 2024-04-20 | Eternal Fire      | W   | 0.488      | 0.143        | 0.740 (0.052)    | -                | -         |    14.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2690 | 2024-04-20 | Cloud9            | W   | 0.487      | -            | -                | -                | -         |     6.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2729 | 2024-04-19 | Eternal Fire      | L   | 0.481      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2738 | 2024-04-19 | Cloud9            | W   | 0.480      | -            | -                | -                | -         |     6.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2764 | 2024-04-18 | ex-Guild Eagles   | W   | 0.475      | -            | -                | -                | -         |     2.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2768 | 2024-04-18 | RUBY              | W   | 0.475      | -            | -                | -                | -         |     3.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2777 | 2024-04-18 | GamerLegion       | W   | 0.474      | -            | -                | -                | -         |     7.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2821 | 2024-04-17 | Passion UA        | L   | 0.467      | -            | -                | -                | -         |    -8.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2858 | 2024-04-16 | ex-Guild Eagles   | L   | 0.460      | -            | -                | -                | -         |   -12.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2879 | 2024-04-15 | ex-Preasy         | W   | 0.453      | -            | -                | -                | -         |     2.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2896 | 2024-04-14 | UNiTY             | W   | 0.445      | -            | -                | -                | -         |     3.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2954 | 2024-04-11 | Enterprise        | W   | 0.426      | -            | -                | -                | -         |     3.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2997 | 2024-04-10 | Passion UA        | L   | 0.419      | -            | -                | -                | -         |    -8.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3130 | 2024-04-06 | UNiTY             | W   | 0.392      | -            | -                | -                | -         |     3.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3187 | 2024-04-04 | UNiTY             | W   | 0.379      | -            | -                | -                | -         |     3.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3271 | 2024-04-02 | Permitta          | W   | 0.365      | -            | -                | -                | -         |     3.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3280 | 2024-04-01 | Nexus             | L   | 0.359      | -            | -                | -                | -         |    -9.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3354 | 2024-03-27 | Rebels            | L   | 0.328      | -            | -                | -                | -         |    -7.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3389 | 2024-03-25 | Nexus             | W   | 0.314      | -            | -                | -                | -         |     1.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3413 | 2024-03-22 | Nemiga            | W   | 0.295      | 0.372        | 0.316 (0.035)    | -                | -         |     5.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3478 | 2024-03-19 | RUBY              | W   | 0.275      | -            | -                | -                | -         |     2.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3490 | 2024-03-18 | Insilio           | W   | 0.267      | -            | -                | -                | -         |     1.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3558 | 2024-03-15 | ECLOT             | W   | 0.246      | -            | -                | -                | -         |     4.60 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3632 | 2024-03-13 | BLEED             | L   | 0.233      | -            | -                | -                | -         |    -5.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3679 | 2024-03-11 | Nemiga            | L   | 0.220      | -            | -                | -                | -         |    -3.11 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3702 | 2024-03-10 | Sampi             | L   | 0.213      | -            | -                | -                | -         |    -5.40 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3726 | 2024-03-09 | Permitta          | W   | 0.206      | -            | -                | -                | -         |     1.73 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3747 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.199      | -            | -                | -                | -         |    -4.46 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3757 | 2024-03-07 | Insilio           | W   | 0.195      | -            | -                | -                | -         |     1.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3771 | 2024-03-07 | ex-sYnck          | W   | 0.193      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3803 | 2024-03-06 | Alliance          | W   | 0.186      | -            | -                | -                | -         |     0.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3837 | 2024-03-05 | Johnny Speeds     | L   | 0.181      | -            | -                | -                | -         |    -1.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3846 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.179      | -            | -                | -                | -         |    -4.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3862 | 2024-03-04 | Entropiq          | L   | 0.172      | -            | -                | -                | -         |    -5.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3907 | 2024-03-02 | brazylijski luz   | W   | 0.160      | -            | -                | -                | -         |     0.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3941 | 2024-02-29 | JANO              | W   | 0.146      | -            | -                | -                | -         |     0.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3951 | 2024-02-28 | Sampi             | W   | 0.140      | -            | -                | -                | -         |     0.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3966 | 2024-02-27 | V1dar             | L   | 0.134      | -            | -                | -                | -         |    -4.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4007 | 2024-02-25 | Sangal            | L   | 0.122      | -            | -                | -                | -         |    -1.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4013 | 2024-02-25 | PGE Turow         | L   | 0.120      | -            | -                | -                | -         |    -3.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4053 | 2024-02-24 | MOUZ NXT          | L   | 0.112      | -            | -                | -                | -         |    -2.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4104 | 2024-02-21 | Sampi             | W   | 0.093      | -            | -                | -                | -         |     0.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4202 | 2024-02-17 | Zero Tenacity     | W   | 0.067      | -            | -                | -                | -         |     0.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4350 | 2024-02-11 | ARCRED            | W   | 0.026      | -            | -                | -                | -         |     0.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4352 | 2024-02-10 | Nemiga            | L   | 0.022      | -            | -                | -                | -         |    -0.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4360 | 2024-02-10 | AMKAL             | W   | 0.020      | -            | -                | -                | -         |     0.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4369 | 2024-02-09 | FORZE             | W   | 0.015      | -            | -                | -                | -         |     0.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4375 | 2024-02-09 | Insilio           | W   | 0.014      | -            | -                | -                | -         |     0.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4383 | 2024-02-08 | Nemiga            | L   | 0.008      | -            | -                | -                | -         |    -0.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4387 | 2024-02-08 | FORZE             | W   | 0.007      | -            | -                | -                | -         |     0.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,276.36)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.841 | $9,365.00      | $7,877.66       |
| 2024-06-09 |      0.821 | $8,000.00      | $6,564.44       |
| 2024-05-18 |      0.674 | $5,000.00      | $3,372.22       |
| 2024-05-09 |      0.613 | $14,000.00     | $8,582.78       |
| 2024-05-02 |      0.568 | $12,500.00     | $7,093.75       |
| 2024-04-27 |      0.535 | $6,375.00      | $3,410.63       |
| 2024-04-06 |      0.392 | $5,000.00      | $1,959.72       |
| 2024-03-25 |      0.314 | $7,000.00      | $2,199.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
