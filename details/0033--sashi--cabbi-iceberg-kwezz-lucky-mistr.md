### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1175.4<br />
<br />
Final Rank Value (1175.4) = Starting Rank Value (1158.0) + Head To Head Adjustments (17.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.461[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1158.0
- 400 + ( ( 0.371 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1158.0


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
|           94 |      134 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     6.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      167 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     3.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      180 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      360 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.618 (0.309)    | 0 (0.000) |    10.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      581 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      591 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      661 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      788 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      797 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      814 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | 0 (0.000) |     4.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      838 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      841 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.537 (0.192)    | 0 (0.000) |     5.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1045 | 2024-06-14 | 3DMAX             | L   | 0.861      | -            | -                | -                | -         |    -5.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1080 | 2024-06-13 | Sampi             | W   | 0.854      | -            | -                | -                | 0 (0.000) |     3.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1097 | 2024-06-12 | CPH Wolves        | W   | 0.849      | -            | -                | -                | 0 (0.000) |     2.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1106 | 2024-06-12 | Astralis Talent   | W   | 0.848      | -            | -                | -                | -         |     1.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1362 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.809      | -            | -                | -                | -         |    -2.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1398 | 2024-06-06 | HEROIC            | L   | 0.807      | -            | -                | -                | -         |    -3.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1427 | 2024-06-05 | ENCE              | L   | 0.802      | -            | -                | -                | -         |    -8.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1447 | 2024-06-05 | Astralis          | W   | 0.801      | 0.715        | 0.352 (0.202)    | 0.382 (0.219)    | 1 (0.801) |    23.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1457 | 2024-06-05 | The MongolZ       | L   | 0.800      | -            | -                | -                | -         |    -0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1892 | 2024-05-20 | Monte             | L   | 0.693      | -            | -                | -                | -         |   -15.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1905 | 2024-05-19 | Passion UA        | W   | 0.688      | 0.500        | 0.172 (0.059)    | 1.000 (0.344)    | -         |     5.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1932 | 2024-05-18 | B8                | L   | 0.682      | -            | -                | -                | -         |   -12.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1941 | 2024-05-18 | Monte             | W   | 0.681      | -            | -                | -                | -         |     5.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1949 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.680      | 0.500        | -                | 0.560 (0.190)    | -         |     3.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     1980 | 2024-05-17 | ex-Guild Eagles   | W   | 0.673      | -            | -                | -                | -         |     2.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2020 | 2024-05-16 | Passion UA        | L   | 0.666      | -            | -                | -                | -         |   -15.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2067 | 2024-05-15 | Endpoint          | W   | 0.660      | -            | -                | -                | -         |     3.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2239 | 2024-05-09 | 1WIN              | W   | 0.621      | -            | -                | -                | -         |     3.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2262 | 2024-05-08 | Grannys Knockers  | W   | 0.614      | -            | -                | -                | -         |     1.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2280 | 2024-05-07 | 9 Pandas          | W   | 0.608      | -            | -                | -                | -         |     4.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2294 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.602      | -            | -                | -                | -         |     4.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2308 | 2024-05-05 | Gaimin Gladiators | L   | 0.595      | -            | -                | -                | -         |   -14.31 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2316 | 2024-05-05 | Come on now dawg  | W   | 0.594      | -            | -                | -                | -         |     0.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2368 | 2024-05-02 | fnatic            | W   | 0.575      | 0.384        | 0.371 (0.082)    | -                | -         |    15.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2403 | 2024-05-01 | 3DMAX             | W   | 0.567      | 0.384        | 0.506 (0.110)    | 1.000 (0.218)    | -         |    16.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2420 | 2024-04-30 | OG                | W   | 0.561      | 0.384        | 0.139 (0.030)    | -                | -         |     6.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2445 | 2024-04-29 | 500               | W   | 0.554      | -            | -                | -                | -         |     1.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2473 | 2024-04-27 | 777               | W   | 0.542      | -            | -                | -                | -         |     1.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2477 | 2024-04-27 | JANO              | W   | 0.542      | -            | -                | -                | -         |     1.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2544 | 2024-04-25 | Passion UA        | W   | 0.527      | 0.384        | 0.172 (0.035)    | 1.000 (0.203)    | -         |     4.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2578 | 2024-04-23 | Gaimin Gladiators | W   | 0.514      | -            | -                | -                | -         |     5.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2583 | 2024-04-23 | BLEED             | W   | 0.513      | -            | -                | -                | -         |     5.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2634 | 2024-04-20 | Eternal Fire      | W   | 0.495      | 0.143        | 0.743 (0.053)    | -                | -         |    14.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2641 | 2024-04-20 | Cloud9            | W   | 0.494      | -            | -                | -                | -         |     6.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2680 | 2024-04-19 | Eternal Fire      | L   | 0.489      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2689 | 2024-04-19 | Cloud9            | W   | 0.488      | -            | -                | -                | -         |     6.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2715 | 2024-04-18 | ex-Guild Eagles   | W   | 0.482      | -            | -                | -                | -         |     2.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2719 | 2024-04-18 | RUBY              | W   | 0.482      | -            | -                | -                | -         |     4.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2728 | 2024-04-18 | GamerLegion       | W   | 0.482      | -            | -                | -                | -         |     7.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2772 | 2024-04-17 | Passion UA        | L   | 0.474      | -            | -                | -                | -         |    -9.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2809 | 2024-04-16 | ex-Guild Eagles   | L   | 0.468      | -            | -                | -                | -         |   -12.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2830 | 2024-04-15 | ex-Preasy         | W   | 0.461      | -            | -                | -                | -         |     2.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2847 | 2024-04-14 | UNiTY             | W   | 0.453      | -            | -                | -                | -         |     3.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2905 | 2024-04-11 | Enterprise        | W   | 0.433      | -            | -                | -                | -         |     3.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2948 | 2024-04-10 | Passion UA        | L   | 0.427      | -            | -                | -                | -         |    -8.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3081 | 2024-04-06 | UNiTY             | W   | 0.399      | -            | -                | -                | -         |     3.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3138 | 2024-04-04 | UNiTY             | W   | 0.387      | -            | -                | -                | -         |     3.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3222 | 2024-04-02 | Permitta          | W   | 0.373      | -            | -                | -                | -         |     3.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3231 | 2024-04-01 | Nexus             | L   | 0.367      | -            | -                | -                | -         |    -9.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3305 | 2024-03-27 | Rebels            | L   | 0.336      | -            | -                | -                | -         |    -7.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3340 | 2024-03-25 | Nexus             | W   | 0.322      | -            | -                | -                | -         |     1.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3364 | 2024-03-22 | Nemiga            | W   | 0.302      | 0.372        | 0.317 (0.036)    | -                | -         |     4.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3429 | 2024-03-19 | RUBY              | W   | 0.282      | -            | -                | -                | -         |     2.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3441 | 2024-03-18 | Insilio           | W   | 0.274      | -            | -                | -                | -         |     1.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3509 | 2024-03-15 | ECLOT             | W   | 0.253      | -            | -                | -                | -         |     4.77 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3583 | 2024-03-13 | BLEED             | L   | 0.240      | -            | -                | -                | -         |    -5.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3630 | 2024-03-11 | Nemiga            | L   | 0.228      | -            | -                | -                | -         |    -3.38 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3653 | 2024-03-10 | Sampi             | L   | 0.220      | -            | -                | -                | -         |    -5.57 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3677 | 2024-03-09 | Permitta          | W   | 0.214      | -            | -                | -                | -         |     1.82 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3698 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.206      | -            | -                | -                | -         |    -4.60 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3708 | 2024-03-07 | Insilio           | W   | 0.203      | -            | -                | -                | -         |     1.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3722 | 2024-03-07 | ex-sYnck          | W   | 0.201      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3754 | 2024-03-06 | Alliance          | W   | 0.194      | -            | -                | -                | -         |     1.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3788 | 2024-03-05 | Johnny Speeds     | L   | 0.189      | -            | -                | -                | -         |    -1.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3797 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.187      | -            | -                | -                | -         |    -4.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3813 | 2024-03-04 | Entropiq          | L   | 0.180      | -            | -                | -                | -         |    -5.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3858 | 2024-03-02 | brazylijski luz   | W   | 0.167      | -            | -                | -                | -         |     0.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3892 | 2024-02-29 | JANO              | W   | 0.153      | -            | -                | -                | -         |     0.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3902 | 2024-02-28 | Sampi             | W   | 0.148      | -            | -                | -                | -         |     0.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3917 | 2024-02-27 | V1dar             | L   | 0.142      | -            | -                | -                | -         |    -4.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     3958 | 2024-02-25 | Sangal            | L   | 0.129      | -            | -                | -                | -         |    -2.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     3964 | 2024-02-25 | PGE Turow         | L   | 0.127      | -            | -                | -                | -         |    -3.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4004 | 2024-02-24 | MOUZ NXT          | L   | 0.120      | -            | -                | -                | -         |    -2.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4055 | 2024-02-21 | Sampi             | W   | 0.101      | -            | -                | -                | -         |     0.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4153 | 2024-02-17 | Zero Tenacity     | W   | 0.075      | -            | -                | -                | -         |     0.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4301 | 2024-02-11 | ARCRED            | W   | 0.034      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4303 | 2024-02-10 | Nemiga            | L   | 0.029      | -            | -                | -                | -         |    -0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4311 | 2024-02-10 | AMKAL             | W   | 0.028      | -            | -                | -                | -         |     0.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4320 | 2024-02-09 | FORZE             | W   | 0.022      | -            | -                | -                | -         |     0.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4326 | 2024-02-09 | Insilio           | W   | 0.021      | -            | -                | -                | -         |     0.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4334 | 2024-02-08 | Nemiga            | L   | 0.016      | -            | -                | -                | -         |    -0.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4338 | 2024-02-08 | FORZE             | W   | 0.015      | -            | -                | -                | -         |     0.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,780.66)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.849 | $9,365.00      | $7,947.89       |
| 2024-06-09 |      0.828 | $8,000.00      | $6,624.44       |
| 2024-05-18 |      0.682 | $5,000.00      | $3,409.72       |
| 2024-05-09 |      0.621 | $14,000.00     | $8,687.78       |
| 2024-05-02 |      0.575 | $12,500.00     | $7,187.50       |
| 2024-04-27 |      0.542 | $6,375.00      | $3,458.44       |
| 2024-04-06 |      0.399 | $5,000.00      | $1,997.22       |
| 2024-03-25 |      0.322 | $7,000.00      | $2,251.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
