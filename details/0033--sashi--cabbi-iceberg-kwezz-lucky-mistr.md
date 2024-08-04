### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1175.6<br />
<br />
Final Rank Value (1175.6) = Starting Rank Value (1158.2) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.577[<sup>1</sup>](#table2)
- Bounty Collected: 0.461[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1158.2
- 400 + ( ( 0.371 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1158.2


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
|           94 |      131 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     6.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      164 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     3.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      177 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      357 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.618 (0.309)    | 0 (0.000) |    10.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      578 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      588 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      658 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      784 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      793 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      810 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | 0 (0.000) |     4.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      834 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      837 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.535 (0.192)    | 0 (0.000) |     5.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1041 | 2024-06-14 | 3DMAX             | L   | 0.864      | -            | -                | -                | -         |    -5.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1076 | 2024-06-13 | Sampi             | W   | 0.857      | -            | -                | -                | 0 (0.000) |     3.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1093 | 2024-06-12 | CPH Wolves        | W   | 0.852      | -            | -                | -                | 0 (0.000) |     2.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1102 | 2024-06-12 | Astralis Talent   | W   | 0.851      | -            | -                | -                | -         |     1.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1358 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.812      | -            | -                | -                | -         |    -2.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1394 | 2024-06-06 | HEROIC            | L   | 0.810      | -            | -                | -                | -         |    -3.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1423 | 2024-06-05 | ENCE              | L   | 0.805      | -            | -                | -                | -         |    -8.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1443 | 2024-06-05 | Astralis          | W   | 0.804      | 0.715        | 0.353 (0.203)    | 0.382 (0.220)    | 1 (0.804) |    23.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1453 | 2024-06-05 | The MongolZ       | L   | 0.803      | -            | -                | -                | -         |    -0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1888 | 2024-05-20 | Monte             | L   | 0.696      | -            | -                | -                | -         |   -15.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1901 | 2024-05-19 | Passion UA        | W   | 0.691      | 0.500        | 0.172 (0.059)    | 1.000 (0.346)    | -         |     5.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1928 | 2024-05-18 | B8                | L   | 0.685      | -            | -                | -                | -         |   -12.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1937 | 2024-05-18 | Monte             | W   | 0.684      | -            | -                | -                | -         |     5.70 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1945 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.683      | 0.500        | -                | 0.561 (0.191)    | -         |     3.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     1976 | 2024-05-17 | ex-Guild Eagles   | W   | 0.676      | -            | -                | -                | -         |     2.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2016 | 2024-05-16 | Passion UA        | L   | 0.669      | -            | -                | -                | -         |   -15.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2063 | 2024-05-15 | Endpoint          | W   | 0.663      | -            | -                | -                | -         |     3.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2235 | 2024-05-09 | 1WIN              | W   | 0.624      | -            | -                | -                | -         |     3.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2258 | 2024-05-08 | Grannys Knockers  | W   | 0.617      | -            | -                | -                | -         |     1.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2276 | 2024-05-07 | 9 Pandas          | W   | 0.611      | -            | -                | -                | -         |     4.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2290 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.605      | -            | -                | -                | -         |     4.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2304 | 2024-05-05 | Gaimin Gladiators | L   | 0.598      | -            | -                | -                | -         |   -14.35 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2312 | 2024-05-05 | Come on now dawg  | W   | 0.597      | -            | -                | -                | -         |     0.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2364 | 2024-05-02 | fnatic            | W   | 0.578      | 0.384        | 0.371 (0.082)    | -                | -         |    15.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2399 | 2024-05-01 | 3DMAX             | W   | 0.570      | 0.384        | 0.505 (0.111)    | 1.000 (0.219)    | -         |    16.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2416 | 2024-04-30 | OG                | W   | 0.564      | 0.384        | 0.140 (0.030)    | -                | -         |     6.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2441 | 2024-04-29 | 500               | W   | 0.557      | -            | -                | -                | -         |     1.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2469 | 2024-04-27 | 777               | W   | 0.546      | -            | -                | -                | -         |     1.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2473 | 2024-04-27 | JANO              | W   | 0.545      | -            | -                | -                | -         |     1.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2539 | 2024-04-25 | Passion UA        | W   | 0.530      | 0.384        | 0.172 (0.035)    | 1.000 (0.204)    | -         |     4.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2573 | 2024-04-23 | Gaimin Gladiators | W   | 0.517      | -            | -                | -                | -         |     5.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2578 | 2024-04-23 | BLEED             | W   | 0.516      | -            | -                | -                | -         |     5.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2629 | 2024-04-20 | Eternal Fire      | W   | 0.498      | 0.143        | 0.743 (0.053)    | -                | -         |    15.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2636 | 2024-04-20 | Cloud9            | W   | 0.497      | -            | -                | -                | -         |     6.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2675 | 2024-04-19 | Eternal Fire      | L   | 0.492      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2684 | 2024-04-19 | Cloud9            | W   | 0.491      | -            | -                | -                | -         |     6.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2710 | 2024-04-18 | ex-Guild Eagles   | W   | 0.485      | -            | -                | -                | -         |     2.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2714 | 2024-04-18 | RUBY              | W   | 0.485      | -            | -                | -                | -         |     4.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2723 | 2024-04-18 | GamerLegion       | W   | 0.485      | -            | -                | -                | -         |     7.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2767 | 2024-04-17 | Passion UA        | L   | 0.477      | -            | -                | -                | -         |    -9.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2804 | 2024-04-16 | ex-Guild Eagles   | L   | 0.471      | -            | -                | -                | -         |   -12.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2825 | 2024-04-15 | ex-Preasy         | W   | 0.464      | -            | -                | -                | -         |     2.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2842 | 2024-04-14 | UNiTY             | W   | 0.456      | -            | -                | -                | -         |     4.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2900 | 2024-04-11 | Enterprise        | W   | 0.436      | -            | -                | -                | -         |     3.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2943 | 2024-04-10 | Passion UA        | L   | 0.430      | -            | -                | -                | -         |    -8.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3076 | 2024-04-06 | UNiTY             | W   | 0.403      | -            | -                | -                | -         |     3.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3133 | 2024-04-04 | UNiTY             | W   | 0.390      | -            | -                | -                | -         |     3.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3217 | 2024-04-02 | Permitta          | W   | 0.376      | -            | -                | -                | -         |     3.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3226 | 2024-04-01 | Nexus             | L   | 0.370      | -            | -                | -                | -         |    -9.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3300 | 2024-03-27 | Rebels            | L   | 0.339      | -            | -                | -                | -         |    -7.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3335 | 2024-03-25 | Nexus             | W   | 0.325      | -            | -                | -                | -         |     1.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3359 | 2024-03-22 | Nemiga            | W   | 0.305      | 0.372        | 0.318 (0.036)    | -                | -         |     5.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3424 | 2024-03-19 | RUBY              | W   | 0.285      | -            | -                | -                | -         |     2.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3436 | 2024-03-18 | Insilio           | W   | 0.278      | -            | -                | -                | -         |     1.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3504 | 2024-03-15 | ECLOT             | W   | 0.256      | -            | -                | -                | -         |     4.83 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3577 | 2024-03-13 | BLEED             | L   | 0.243      | -            | -                | -                | -         |    -5.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3624 | 2024-03-11 | Nemiga            | L   | 0.231      | -            | -                | -                | -         |    -3.42 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3647 | 2024-03-10 | Sampi             | L   | 0.223      | -            | -                | -                | -         |    -5.64 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3671 | 2024-03-09 | Permitta          | W   | 0.217      | -            | -                | -                | -         |     1.85 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3692 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.209      | -            | -                | -                | -         |    -4.67 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3702 | 2024-03-07 | Insilio           | W   | 0.206      | -            | -                | -                | -         |     1.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3716 | 2024-03-07 | ex-sYnck          | W   | 0.204      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3748 | 2024-03-06 | Alliance          | W   | 0.197      | -            | -                | -                | -         |     1.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3782 | 2024-03-05 | Johnny Speeds     | L   | 0.192      | -            | -                | -                | -         |    -1.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3791 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.190      | -            | -                | -                | -         |    -4.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3807 | 2024-03-04 | Entropiq          | L   | 0.183      | -            | -                | -                | -         |    -5.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3852 | 2024-03-02 | brazylijski luz   | W   | 0.170      | -            | -                | -                | -         |     0.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3886 | 2024-02-29 | JANO              | W   | 0.156      | -            | -                | -                | -         |     0.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3896 | 2024-02-28 | Sampi             | W   | 0.151      | -            | -                | -                | -         |     0.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3911 | 2024-02-27 | V1dar             | L   | 0.145      | -            | -                | -                | -         |    -4.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     3952 | 2024-02-25 | Sangal            | L   | 0.132      | -            | -                | -                | -         |    -2.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     3958 | 2024-02-25 | PGE Turow         | L   | 0.130      | -            | -                | -                | -         |    -3.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     3998 | 2024-02-24 | MOUZ NXT          | L   | 0.123      | -            | -                | -                | -         |    -2.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4049 | 2024-02-21 | Sampi             | W   | 0.104      | -            | -                | -                | -         |     0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4146 | 2024-02-17 | Zero Tenacity     | W   | 0.078      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4294 | 2024-02-11 | ARCRED            | W   | 0.037      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4296 | 2024-02-10 | Nemiga            | L   | 0.033      | -            | -                | -                | -         |    -0.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4304 | 2024-02-10 | AMKAL             | W   | 0.031      | -            | -                | -                | -         |     0.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4313 | 2024-02-09 | FORZE             | W   | 0.025      | -            | -                | -                | -         |     0.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4319 | 2024-02-09 | Insilio           | W   | 0.024      | -            | -                | -                | -         |     0.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4327 | 2024-02-08 | Nemiga            | L   | 0.019      | -            | -                | -                | -         |    -0.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4331 | 2024-02-08 | FORZE             | W   | 0.018      | -            | -                | -                | -         |     0.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,986.12)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.852 | $9,365.00      | $7,976.51       |
| 2024-06-09 |      0.831 | $8,000.00      | $6,648.89       |
| 2024-05-18 |      0.685 | $5,000.00      | $3,425.00       |
| 2024-05-09 |      0.624 | $14,000.00     | $8,730.56       |
| 2024-05-02 |      0.578 | $12,500.00     | $7,225.69       |
| 2024-04-27 |      0.546 | $6,375.00      | $3,477.92       |
| 2024-04-06 |      0.403 | $5,000.00      | $2,012.50       |
| 2024-03-25 |      0.325 | $7,000.00      | $2,273.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
