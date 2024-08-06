### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1097.2<br />
<br />
Final Rank Value (1097.2) = Starting Rank Value (1097.0) + Head To Head Adjustments (0.1)<br />

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


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           92 |       85 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           91 |      163 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           90 |      244 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           89 |      279 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           88 |      291 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           87 |      333 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           86 |      355 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           85 |      374 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           84 |      395 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           83 |      413 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           82 |      478 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           81 |      500 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           80 |      506 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           79 |      526 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    17.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           78 |      561 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.531 (0.266)    | 0 (0.000) |    29.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           77 |      574 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           76 |      603 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.314 (0.157)    | 0.704 (0.352)    | -         |    20.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           75 |      660 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           74 |      671 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           73 |      727 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.521 (0.261)    | -         |    11.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           72 |      788 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.919 (0.340)    | -         |    11.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           71 |      810 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           70 |      830 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           69 |      848 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.13 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           68 |      912 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           67 |      930 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           66 |      932 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           65 |      952 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           64 |     1126 | 2024-06-14 | 3DMAX             | L   | 0.845      | -            | -                | -                | -         |    -3.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           63 |     1218 | 2024-06-10 | Space             | W   | 0.821      | -            | -                | -                | -         |     6.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           62 |     1330 | 2024-06-08 | Zero Tenacity     | L   | 0.807      | -            | -                | -                | -         |   -11.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           61 |     1392 | 2024-06-07 | Rare Atom         | W   | 0.800      | -            | -                | -                | -         |     5.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           60 |     1405 | 2024-06-07 | Aurora Young Blud | W   | 0.799      | -            | -                | -                | -         |     7.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           59 |     1476 | 2024-06-06 | Serbia            | W   | 0.792      | -            | -                | -                | -         |     5.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           58 |     1528 | 2024-06-05 | EYEBALLERS        | L   | 0.786      | -            | -                | -                | -         |   -18.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           57 |     1558 | 2024-06-04 | Illuminar         | W   | 0.781      | -            | -                | -                | -         |     4.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           56 |     1567 | 2024-06-04 | Serbia            | W   | 0.780      | -            | -                | -                | -         |     4.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           55 |     1616 | 2024-06-02 | UNiTY             | W   | 0.765      | -            | -                | -                | -         |     8.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           54 |     1677 | 2024-05-31 | Zero Tenacity     | L   | 0.753      | -            | -                | -                | -         |   -10.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           53 |     1698 | 2024-05-30 | Zero Tenacity     | W   | 0.747      | 0.371        | 0.143 (0.040)    | 1.000 (0.277)    | -         |    13.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           52 |     1727 | 2024-05-29 | Illuminar         | W   | 0.739      | -            | -                | -                | -         |     5.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           51 |     1798 | 2024-05-25 | Sampi             | W   | 0.714      | 0.435        | -                | 1.000 (0.310)    | -         |     7.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           50 |     1819 | 2024-05-24 | FURIA             | L   | 0.707      | -            | -                | -                | -         |    -0.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           49 |     1825 | 2024-05-24 | ECSTATIC          | W   | 0.705      | -            | -                | -                | -         |     1.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           48 |     1839 | 2024-05-23 | SINNERS           | W   | 0.699      | -            | -                | -                | -         |    12.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           47 |     1963 | 2024-05-20 | Permitta          | W   | 0.679      | 0.435        | -                | 0.919 (0.271)    | -         |     6.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           46 |     1975 | 2024-05-19 | Sashi             | L   | 0.674      | -            | -                | -                | -         |    -5.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           45 |     1986 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.673      | -            | -                | -                | -         |     7.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           44 |     2006 | 2024-05-18 | 9 Pandas          | L   | 0.667      | -            | -                | -                | -         |   -10.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           43 |     2049 | 2024-05-17 | Nexus             | W   | 0.660      | -            | -                | -                | -         |     4.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           42 |     2090 | 2024-05-16 | Sashi             | W   | 0.652      | 0.500        | 0.184 (0.060)    | 0.958 (0.313)    | -         |    15.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           41 |     2129 | 2024-05-15 | Endpoint          | L   | 0.647      | -            | -                | -                | -         |   -12.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           40 |     2183 | 2024-05-14 | SINNERS           | L   | 0.641      | -            | -                | -                | -         |    -8.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           39 |     2276 | 2024-05-11 | Preasy            | W   | 0.619      | -            | -                | -                | -         |     3.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           38 |     2440 | 2024-05-02 | Nemiga            | L   | 0.561      | -            | -                | -                | -         |    -5.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           37 |     2463 | 2024-05-01 | PARIVISION        | W   | 0.554      | -            | -                | -                | -         |    10.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           36 |     2500 | 2024-04-30 | 9 Pandas          | W   | 0.546      | -            | -                | -                | -         |     7.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           35 |     2527 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.534      | -            | -                | -                | -         |   -10.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           34 |     2577 | 2024-04-26 | 9 Pandas          | W   | 0.521      | -            | -                | -                | -         |     7.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           33 |     2578 | 2024-04-26 | 9 Pandas          | W   | 0.521      | -            | -                | -                | -         |     6.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           32 |     2614 | 2024-04-25 | Sashi             | L   | 0.513      | -            | -                | -                | -         |    -4.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           31 |     2629 | 2024-04-24 | Permitta          | L   | 0.507      | -            | -                | -                | -         |    -9.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           30 |     2658 | 2024-04-22 | B8                | L   | 0.495      | -            | -                | -                | -         |    -7.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           29 |     2699 | 2024-04-20 | Young Ninjas      | W   | 0.482      | -            | -                | -                | -         |     2.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           28 |     2721 | 2024-04-20 | Permitta          | L   | 0.479      | -            | -                | -                | -         |    -9.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           27 |     2755 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.474      | -            | -                | -                | -         |    -9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           26 |     2812 | 2024-04-18 | Permitta          | W   | 0.467      | -            | -                | -                | -         |     5.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           25 |     2842 | 2024-04-17 | Sashi             | W   | 0.460      | 0.371        | 0.184 (0.031)    | -                | -         |     8.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           24 |     2876 | 2024-04-16 | 500               | L   | 0.454      | -            | -                | -                | -         |   -12.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           23 |     2915 | 2024-04-14 | SINNERS           | L   | 0.440      | -            | -                | -                | -         |    -4.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           22 |     2970 | 2024-04-11 | 3DMAX             | W   | 0.420      | 0.384        | 0.510 (0.082)    | -                | -         |    12.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           21 |     3018 | 2024-04-10 | Sashi             | W   | 0.413      | 0.371        | 0.184 (0.028)    | -                | -         |     8.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           20 |     3205 | 2024-04-04 | HAVU              | W   | 0.374      | -            | -                | -                | -         |     1.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           19 |     3276 | 2024-04-02 | BLEED             | L   | 0.361      | -            | -                | -                | -         |    -6.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           18 |     3305 | 2024-03-31 | FAVBET            | L   | 0.347      | -            | -                | -                | -         |    -9.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           17 |     3312 | 2024-03-30 | Lazer Cats        | W   | 0.340      | -            | -                | -                | -         |     0.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           16 |     3320 | 2024-03-29 | NAVI Junior       | L   | 0.333      | -            | -                | -                | -         |    -9.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           15 |     3339 | 2024-03-28 | GL Academy        | L   | 0.327      | -            | -                | -                | -         |    -8.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           14 |     3549 | 2024-03-17 | Sampi             | L   | 0.252      | -            | -                | -                | -         |    -5.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           13 |     3558 | 2024-03-16 | ex-Preasy         | L   | 0.247      | -            | -                | -                | -         |    -6.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           12 |     3611 | 2024-03-14 | Sampi             | W   | 0.233      | -            | -                | -                | -         |     1.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           11 |     3679 | 2024-03-12 | Alliance          | W   | 0.220      | -            | -                | -                | -         |     1.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           10 |     3701 | 2024-03-11 | MOUZ NXT          | L   | 0.213      | -            | -                | -                | -         |    -3.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            9 |     3721 | 2024-03-10 | MOUZ NXT          | W   | 0.207      | -            | -                | -                | -         |     2.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            8 |     3736 | 2024-03-09 | The Chosen Few    | L   | 0.201      | -            | -                | -                | -         |    -5.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            7 |     3761 | 2024-03-08 | Spirit Academy    | L   | 0.194      | -            | -                | -                | -         |    -5.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            6 |     3766 | 2024-03-08 | Entropiq          | W   | 0.193      | -            | -                | -                | -         |     0.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            5 |     3785 | 2024-03-07 | AURA              | W   | 0.188      | -            | -                | -                | -         |     0.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            4 |     3821 | 2024-03-06 | Permitta          | L   | 0.180      | -            | -                | -                | -         |    -3.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            3 |     3825 | 2024-03-06 | Fraud5            | W   | 0.180      | -            | -                | -                | -         |     0.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            2 |     3850 | 2024-03-05 | B8                | L   | 0.175      | -            | -                | -                | -         |    -2.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            1 |     3879 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.167      | -            | -                | -                | -         |     1.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,470.98)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.792 | $11,000.00     | $8,713.43       |
| 2024-05-03 |      0.567 | $12,500.00     | $7,092.59       |
| 2024-03-31 |      0.347 | $657.00        | $227.97         |
| 2024-03-30 |      0.340 | $1,000.00      | $339.91         |
| 2024-03-18 |      0.259 | $3,000.00      | $777.22         |
| 2024-03-11 |      0.213 | $1,500.00      | $319.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
