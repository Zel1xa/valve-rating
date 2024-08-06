### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1096.0<br />
<br />
Final Rank Value (1096.0) = Starting Rank Value (1097.0) + Head To Head Adjustments (-1.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.326[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.339<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1097.0
- 400 + ( ( 0.339 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1097.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |       83 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      161 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      242 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      277 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      289 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      331 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      353 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      372 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      393 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      411 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      476 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      498 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      504 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      524 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    17.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      559 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.531 (0.266)    | 0 (0.000) |    29.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      572 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      601 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.315 (0.157)    | 0.704 (0.352)    | -         |    20.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      658 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      669 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      725 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.521 (0.261)    | -         |    10.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      786 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.919 (0.340)    | -         |    11.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      808 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      828 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      846 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.13 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      910 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      928 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      930 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      950 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1124 | 2024-06-14 | 3DMAX             | L   | 0.846      | -            | -                | -                | -         |    -3.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1216 | 2024-06-10 | Space             | W   | 0.821      | -            | -                | -                | -         |     6.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1328 | 2024-06-08 | Zero Tenacity     | L   | 0.808      | -            | -                | -                | -         |   -11.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1390 | 2024-06-07 | Rare Atom         | W   | 0.801      | -            | -                | -                | -         |     5.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1403 | 2024-06-07 | Aurora Young Blud | W   | 0.799      | -            | -                | -                | -         |     6.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1474 | 2024-06-06 | Serbia            | W   | 0.792      | -            | -                | -                | -         |     5.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1526 | 2024-06-05 | EYEBALLERS        | L   | 0.786      | -            | -                | -                | -         |   -18.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1556 | 2024-06-04 | Illuminar         | W   | 0.781      | -            | -                | -                | -         |     4.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1565 | 2024-06-04 | Serbia            | W   | 0.780      | -            | -                | -                | -         |     4.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1614 | 2024-06-02 | UNiTY             | W   | 0.766      | -            | -                | -                | -         |     8.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1675 | 2024-05-31 | Zero Tenacity     | L   | 0.754      | -            | -                | -                | -         |   -10.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1696 | 2024-05-30 | Zero Tenacity     | W   | 0.747      | 0.371        | 0.143 (0.040)    | 1.000 (0.277)    | -         |    13.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1725 | 2024-05-29 | Illuminar         | W   | 0.739      | -            | -                | -                | -         |     5.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1796 | 2024-05-25 | Sampi             | W   | 0.714      | 0.435        | -                | 1.000 (0.310)    | -         |     7.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1817 | 2024-05-24 | FURIA             | L   | 0.708      | -            | -                | -                | -         |    -0.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1823 | 2024-05-24 | ECSTATIC          | W   | 0.706      | -            | -                | -                | -         |     1.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1837 | 2024-05-23 | SINNERS           | W   | 0.699      | -            | -                | -                | -         |    12.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1961 | 2024-05-20 | Permitta          | W   | 0.679      | 0.435        | -                | 0.919 (0.271)    | -         |     6.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1973 | 2024-05-19 | Sashi             | L   | 0.675      | -            | -                | -                | -         |    -5.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1984 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.673      | -            | -                | -                | -         |     7.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     2004 | 2024-05-18 | 9 Pandas          | L   | 0.668      | -            | -                | -                | -         |   -10.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2047 | 2024-05-17 | Nexus             | W   | 0.660      | -            | -                | -                | -         |     4.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2088 | 2024-05-16 | Sashi             | W   | 0.653      | 0.500        | 0.184 (0.060)    | 0.958 (0.313)    | -         |    15.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2127 | 2024-05-15 | Endpoint          | L   | 0.648      | -            | -                | -                | -         |   -12.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2181 | 2024-05-14 | SINNERS           | L   | 0.642      | -            | -                | -                | -         |    -8.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2274 | 2024-05-11 | Preasy            | W   | 0.619      | -            | -                | -                | -         |     3.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2438 | 2024-05-02 | Nemiga            | L   | 0.561      | -            | -                | -                | -         |    -5.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2461 | 2024-05-01 | PARIVISION        | W   | 0.554      | -            | -                | -                | -         |    10.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2498 | 2024-04-30 | 9 Pandas          | W   | 0.546      | -            | -                | -                | -         |     7.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2525 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.535      | -            | -                | -                | -         |   -10.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2575 | 2024-04-26 | 9 Pandas          | W   | 0.521      | -            | -                | -                | -         |     7.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2576 | 2024-04-26 | 9 Pandas          | W   | 0.521      | -            | -                | -                | -         |     6.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2612 | 2024-04-25 | Sashi             | L   | 0.513      | -            | -                | -                | -         |    -4.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2627 | 2024-04-24 | Permitta          | L   | 0.507      | -            | -                | -                | -         |    -9.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2656 | 2024-04-22 | B8                | L   | 0.495      | -            | -                | -                | -         |    -7.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2697 | 2024-04-20 | Young Ninjas      | W   | 0.482      | -            | -                | -                | -         |     2.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2719 | 2024-04-20 | Permitta          | L   | 0.479      | -            | -                | -                | -         |    -9.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2753 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.474      | -            | -                | -                | -         |    -9.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2810 | 2024-04-18 | Permitta          | W   | 0.467      | -            | -                | -                | -         |     5.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2840 | 2024-04-17 | Sashi             | W   | 0.461      | 0.371        | 0.184 (0.031)    | -                | -         |     8.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2874 | 2024-04-16 | 500               | L   | 0.455      | -            | -                | -                | -         |   -12.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2913 | 2024-04-14 | SINNERS           | L   | 0.440      | -            | -                | -                | -         |    -4.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2968 | 2024-04-11 | 3DMAX             | W   | 0.421      | 0.384        | 0.510 (0.082)    | -                | -         |    12.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     3016 | 2024-04-10 | Sashi             | W   | 0.413      | 0.371        | 0.184 (0.028)    | -                | -         |     8.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3203 | 2024-04-04 | HAVU              | W   | 0.374      | -            | -                | -                | -         |     1.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3274 | 2024-04-02 | BLEED             | L   | 0.361      | -            | -                | -                | -         |    -6.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3303 | 2024-03-31 | FAVBET            | L   | 0.347      | -            | -                | -                | -         |    -9.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3310 | 2024-03-30 | Lazer Cats        | W   | 0.340      | -            | -                | -                | -         |     0.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3318 | 2024-03-29 | NAVI Junior       | L   | 0.334      | -            | -                | -                | -         |    -9.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3337 | 2024-03-28 | GL Academy        | L   | 0.327      | -            | -                | -                | -         |    -8.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3547 | 2024-03-17 | Sampi             | L   | 0.253      | -            | -                | -                | -         |    -5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3556 | 2024-03-16 | ex-Preasy         | L   | 0.247      | -            | -                | -                | -         |    -6.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3609 | 2024-03-14 | Sampi             | W   | 0.234      | -            | -                | -                | -         |     1.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3677 | 2024-03-12 | Alliance          | W   | 0.220      | -            | -                | -                | -         |     1.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3699 | 2024-03-11 | MOUZ NXT          | L   | 0.214      | -            | -                | -                | -         |    -3.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3719 | 2024-03-10 | MOUZ NXT          | W   | 0.207      | -            | -                | -                | -         |     2.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3734 | 2024-03-09 | The Chosen Few    | L   | 0.201      | -            | -                | -                | -         |    -5.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3759 | 2024-03-08 | Spirit Academy    | L   | 0.195      | -            | -                | -                | -         |    -5.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3764 | 2024-03-08 | Entropiq          | W   | 0.193      | -            | -                | -                | -         |     0.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3783 | 2024-03-07 | AURA              | W   | 0.188      | -            | -                | -                | -         |     0.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3819 | 2024-03-06 | Permitta          | L   | 0.181      | -            | -                | -                | -         |    -3.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3823 | 2024-03-06 | Fraud5            | W   | 0.180      | -            | -                | -                | -         |     0.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3848 | 2024-03-05 | B8                | L   | 0.175      | -            | -                | -                | -         |    -2.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3877 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.167      | -            | -                | -                | -         |     1.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4410 | 2024-02-08 | BLEED             | L   | 0.000      | -            | -                | -                | -         |     0.00 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,481.97)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.792 | $11,000.00     | $8,717.50       |
| 2024-05-03 |      0.568 | $12,500.00     | $7,097.22       |
| 2024-03-31 |      0.347 | $657.00        | $228.22         |
| 2024-03-30 |      0.340 | $1,000.00      | $340.28         |
| 2024-03-18 |      0.259 | $3,000.00      | $778.33         |
| 2024-03-11 |      0.214 | $1,500.00      | $320.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
