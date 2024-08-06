### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1126.7<br />
<br />
Final Rank Value (1126.7) = Starting Rank Value (1159.9) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1159.9
- 400 + ( ( 0.370 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1159.9


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
|           97 |       10 | 2024-08-05 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -30.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |       14 | 2024-08-05 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |       20 | 2024-08-05 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      200 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.552 (0.276)    | 0 (0.000) |     6.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      231 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.499 (0.249)    | 0 (0.000) |     3.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      243 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      424 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.306)    | 0 (0.000) |    10.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      645 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      655 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      725 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      852 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      861 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      878 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.513 (0.184)    | 0 (0.000) |     4.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      902 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      905 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.534 (0.191)    | 0 (0.000) |     5.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1109 | 2024-06-14 | 3DMAX             | L   | 0.848      | -            | -                | -                | -         |    -5.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1144 | 2024-06-13 | Sampi             | W   | 0.841      | -            | -                | -                | 0 (0.000) |     3.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1161 | 2024-06-12 | CPH Wolves        | W   | 0.835      | -            | -                | -                | -         |     2.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1170 | 2024-06-12 | Astralis Talent   | W   | 0.835      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1426 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.796      | -            | -                | -                | -         |    -2.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1462 | 2024-06-06 | HEROIC            | L   | 0.794      | -            | -                | -                | -         |    -3.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1491 | 2024-06-05 | ENCE              | L   | 0.789      | -            | -                | -                | -         |    -7.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1511 | 2024-06-05 | Astralis          | W   | 0.788      | 0.715        | 0.389 (0.219)    | 0.412 (0.232)    | 1 (0.788) |    23.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1521 | 2024-06-05 | The MongolZ       | L   | 0.787      | -            | -                | -                | -         |    -0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1956 | 2024-05-20 | Monte             | L   | 0.680      | -            | -                | -                | -         |   -15.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1969 | 2024-05-19 | Passion UA        | W   | 0.675      | 0.500        | 0.173 (0.058)    | 1.000 (0.337)    | -         |     5.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1996 | 2024-05-18 | B8                | L   | 0.669      | -            | -                | -                | -         |   -12.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     2005 | 2024-05-18 | Monte             | W   | 0.667      | -            | -                | -                | -         |     5.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2013 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.666      | 0.500        | -                | 0.549 (0.183)    | -         |     3.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2044 | 2024-05-17 | ex-Guild Eagles   | W   | 0.660      | -            | -                | -                | -         |     2.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2084 | 2024-05-16 | Passion UA        | L   | 0.653      | -            | -                | -                | -         |   -15.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2131 | 2024-05-15 | Endpoint          | W   | 0.647      | -            | -                | -                | -         |     3.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2303 | 2024-05-09 | 1WIN              | W   | 0.607      | -            | -                | -                | -         |     4.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2326 | 2024-05-08 | Grannys Knockers  | W   | 0.601      | -            | -                | -                | -         |     1.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2344 | 2024-05-07 | 9 Pandas          | W   | 0.594      | -            | -                | -                | -         |     4.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2358 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.588      | -            | -                | -                | -         |     4.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2372 | 2024-05-05 | Gaimin Gladiators | L   | 0.582      | -            | -                | -                | -         |   -14.05 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2380 | 2024-05-05 | Come on now dawg  | W   | 0.581      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2432 | 2024-05-02 | fnatic            | W   | 0.562      | 0.384        | 0.371 (0.080)    | -                | -         |    15.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2467 | 2024-05-01 | 3DMAX             | W   | 0.554      | 0.384        | 0.509 (0.108)    | 1.000 (0.213)    | -         |    16.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2484 | 2024-04-30 | OG                | W   | 0.548      | 0.384        | 0.137 (0.029)    | -                | -         |     6.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2509 | 2024-04-29 | 500               | W   | 0.540      | -            | -                | -                | -         |     1.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2537 | 2024-04-27 | 777               | W   | 0.529      | -            | -                | -                | -         |     1.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2541 | 2024-04-27 | JANO              | W   | 0.529      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2608 | 2024-04-25 | Passion UA        | W   | 0.514      | 0.384        | 0.173 (0.034)    | 1.000 (0.197)    | -         |     5.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2642 | 2024-04-23 | Gaimin Gladiators | W   | 0.501      | -            | -                | -                | -         |     4.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2647 | 2024-04-23 | BLEED             | W   | 0.500      | -            | -                | -                | -         |     5.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2698 | 2024-04-20 | Eternal Fire      | W   | 0.482      | 0.143        | 0.739 (0.051)    | -                | -         |    14.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2705 | 2024-04-20 | Cloud9            | W   | 0.481      | -            | -                | -                | -         |     6.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2744 | 2024-04-19 | Eternal Fire      | L   | 0.475      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2753 | 2024-04-19 | Cloud9            | W   | 0.474      | -            | -                | -                | -         |     6.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2779 | 2024-04-18 | ex-Guild Eagles   | W   | 0.469      | -            | -                | -                | -         |     2.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2783 | 2024-04-18 | RUBY              | W   | 0.469      | -            | -                | -                | -         |     3.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2792 | 2024-04-18 | GamerLegion       | W   | 0.468      | -            | -                | -                | -         |     7.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2836 | 2024-04-17 | Passion UA        | L   | 0.461      | -            | -                | -                | -         |    -8.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2873 | 2024-04-16 | ex-Guild Eagles   | L   | 0.454      | -            | -                | -                | -         |   -12.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2894 | 2024-04-15 | ex-Preasy         | W   | 0.447      | -            | -                | -                | -         |     2.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2911 | 2024-04-14 | UNiTY             | W   | 0.439      | -            | -                | -                | -         |     3.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2969 | 2024-04-11 | Enterprise        | W   | 0.420      | -            | -                | -                | -         |     3.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3012 | 2024-04-10 | Passion UA        | L   | 0.414      | -            | -                | -                | -         |    -8.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3145 | 2024-04-06 | UNiTY             | W   | 0.386      | -            | -                | -                | -         |     3.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3202 | 2024-04-04 | UNiTY             | W   | 0.374      | -            | -                | -                | -         |     3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3286 | 2024-04-02 | Permitta          | W   | 0.359      | -            | -                | -                | -         |     3.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3295 | 2024-04-01 | Nexus             | L   | 0.353      | -            | -                | -                | -         |    -9.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3369 | 2024-03-27 | Rebels            | L   | 0.322      | -            | -                | -                | -         |    -7.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3404 | 2024-03-25 | Nexus             | W   | 0.308      | -            | -                | -                | -         |     1.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3428 | 2024-03-22 | Nemiga            | W   | 0.289      | 0.372        | 0.315 (0.034)    | -                | -         |     4.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3493 | 2024-03-19 | RUBY              | W   | 0.269      | -            | -                | -                | -         |     2.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3505 | 2024-03-18 | Insilio           | W   | 0.261      | -            | -                | -                | -         |     1.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3573 | 2024-03-15 | ECLOT             | W   | 0.240      | -            | -                | -                | -         |     4.49 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3647 | 2024-03-13 | BLEED             | L   | 0.227      | -            | -                | -                | -         |    -5.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3694 | 2024-03-11 | Nemiga            | L   | 0.214      | -            | -                | -                | -         |    -3.05 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3717 | 2024-03-10 | Sampi             | L   | 0.207      | -            | -                | -                | -         |    -5.25 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3741 | 2024-03-09 | Permitta          | W   | 0.201      | -            | -                | -                | -         |     1.78 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3762 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.193      | -            | -                | -                | -         |    -4.34 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3772 | 2024-03-07 | Insilio           | W   | 0.189      | -            | -                | -                | -         |     1.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3786 | 2024-03-07 | ex-sYnck          | W   | 0.188      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3818 | 2024-03-06 | Alliance          | W   | 0.180      | -            | -                | -                | -         |     0.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3852 | 2024-03-05 | Johnny Speeds     | L   | 0.175      | -            | -                | -                | -         |    -1.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3861 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.173      | -            | -                | -                | -         |    -3.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3877 | 2024-03-04 | Entropiq          | L   | 0.166      | -            | -                | -                | -         |    -5.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3922 | 2024-03-02 | brazylijski luz   | W   | 0.154      | -            | -                | -                | -         |     0.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3956 | 2024-02-29 | JANO              | W   | 0.140      | -            | -                | -                | -         |     0.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3966 | 2024-02-28 | Sampi             | W   | 0.134      | -            | -                | -                | -         |     0.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3981 | 2024-02-27 | V1dar             | L   | 0.129      | -            | -                | -                | -         |    -3.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4022 | 2024-02-25 | Sangal            | L   | 0.116      | -            | -                | -                | -         |    -1.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4028 | 2024-02-25 | PGE Turow         | L   | 0.114      | -            | -                | -                | -         |    -3.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4068 | 2024-02-24 | MOUZ NXT          | L   | 0.106      | -            | -                | -                | -         |    -2.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4119 | 2024-02-21 | Sampi             | W   | 0.087      | -            | -                | -                | -         |     0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4217 | 2024-02-17 | Zero Tenacity     | W   | 0.061      | -            | -                | -                | -         |     0.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4365 | 2024-02-11 | ARCRED            | W   | 0.021      | -            | -                | -                | -         |     0.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4367 | 2024-02-10 | Nemiga            | L   | 0.016      | -            | -                | -                | -         |    -0.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4375 | 2024-02-10 | AMKAL             | W   | 0.015      | -            | -                | -                | -         |     0.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4384 | 2024-02-09 | FORZE             | W   | 0.009      | -            | -                | -                | -         |     0.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4390 | 2024-02-09 | Insilio           | W   | 0.008      | -            | -                | -                | -         |     0.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4398 | 2024-02-08 | Nemiga            | L   | 0.002      | -            | -                | -                | -         |    -0.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4402 | 2024-02-08 | FORZE             | W   | 0.001      | -            | -                | -                | -         |     0.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58,884.13)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.835 | $9,365.00      | $7,823.03       |
| 2024-06-09 |      0.815 | $8,000.00      | $6,517.78       |
| 2024-05-18 |      0.669 | $5,000.00      | $3,343.06       |
| 2024-05-09 |      0.607 | $14,000.00     | $8,501.11       |
| 2024-05-02 |      0.562 | $12,500.00     | $7,020.83       |
| 2024-04-27 |      0.529 | $6,375.00      | $3,373.44       |
| 2024-04-06 |      0.386 | $5,000.00      | $1,930.56       |
| 2024-03-25 |      0.308 | $7,000.00      | $2,158.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
