### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
<br />
Final Rank Value:  970.1<br />
<br />
Final Rank Value (970.1) = Starting Rank Value (1015.2) + Head To Head Adjustments (-45.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.490[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.279[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.301<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1015.2
- 400 + ( ( 0.301 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1015.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           95 |       31 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.78 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |       55 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.85 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      131 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.40 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      137 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.571 (0.257)    | 0 (0.000) |     7.60 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      145 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.87 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      172 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.34 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      202 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.16 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      283 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.08 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      291 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.20 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      360 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.24 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      365 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.58 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      399 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.125 (0.048)    | 0.746 (0.287)    | 0 (0.000) |    23.69 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      425 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | -                | 0.733 (0.282)    | 0 (0.000) |    22.42 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      482 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.64 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      493 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.54 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      533 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.19 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      535 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.24 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      547 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -15.08 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      594 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.46 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      599 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.21 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      609 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     9.22 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      660 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.857 (0.386)    | -         |    17.60 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      669 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -13.74 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      718 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.79 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      748 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     7.15 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      759 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.65 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      789 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.87 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |      817 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.83 | luchov, naz, Noktse, tomaszin, zock    |
|           67 |      832 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.33 | luchov, naz, Noktse, tomaszin, zock    |
|           66 |      840 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -18.69 | luchov, naz, Noktse, tomaszin, zock    |
|           65 |     1078 | 2024-06-10 | paiN              | L   | 0.842      | -            | -                | -                | -         |    -4.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1084 | 2024-06-10 | Bounty Hunters    | W   | 0.840      | -            | -                | -                | -         |     9.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1112 | 2024-06-09 | RED Canids        | W   | 0.835      | -            | -                | -                | -         |    16.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1139 | 2024-06-09 | Sharks            | L   | 0.833      | -            | -                | -                | -         |   -12.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1191 | 2024-06-08 | Vikings KR        | L   | 0.827      | -            | -                | -                | -         |   -20.36 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1234 | 2024-06-07 | ODDIK             | W   | 0.821      | 0.450        | 0.098 (0.036)    | 0.857 (0.317)    | -         |     9.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1294 | 2024-06-06 | inSanitY          | L   | 0.814      | -            | -                | -                | -         |   -15.43 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1354 | 2024-06-05 | MIBR              | L   | 0.808      | -            | -                | -                | -         |    -2.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1406 | 2024-06-04 | Sharks            | L   | 0.802      | -            | -                | -                | -         |   -13.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1716 | 2024-05-22 | Case              | W   | 0.715      | 0.450        | -                | 0.750 (0.241)    | -         |     7.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1722 | 2024-05-22 | Case              | W   | 0.715      | 0.450        | -                | 0.750 (0.241)    | -         |     7.74 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1724 | 2024-05-22 | Fluxo             | W   | 0.714      | 0.450        | 0.125 (0.040)    | -                | -         |    12.50 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1727 | 2024-05-22 | Fluxo             | W   | 0.714      | 0.450        | 0.125 (0.040)    | -                | -         |    13.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1763 | 2024-05-21 | Smoke             | W   | 0.708      | -            | -                | -                | -         |     3.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1766 | 2024-05-21 | Smoke             | W   | 0.708      | -            | -                | -                | -         |     3.52 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1769 | 2024-05-21 | Imperial          | W   | 0.708      | 0.450        | 0.234 (0.075)    | -                | -         |    17.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1770 | 2024-05-21 | Imperial          | W   | 0.707      | 0.450        | 0.234 (0.074)    | -                | -         |    18.50 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1802 | 2024-05-20 | Corinthians       | W   | 0.701      | -            | -                | -                | -         |     1.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1804 | 2024-05-20 | 9z                | W   | 0.701      | 0.450        | 0.136 (0.043)    | -                | -         |    17.77 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1807 | 2024-05-20 | 9z                | L   | 0.701      | -            | -                | -                | -         |    -4.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1888 | 2024-05-17 | Solid             | L   | 0.682      | -            | -                | -                | -         |   -13.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1889 | 2024-05-17 | Solid             | W   | 0.682      | 0.450        | -                | 0.863 (0.265)    | -         |     8.44 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     1973 | 2024-05-15 | ODDIK             | W   | 0.668      | 0.450        | 0.098 (0.030)    | 0.857 (0.258)    | -         |    10.48 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     1974 | 2024-05-15 | ODDIK             | W   | 0.668      | 0.450        | -                | 0.857 (0.258)    | -         |    11.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     1984 | 2024-05-15 | Hype              | L   | 0.667      | -            | -                | -                | -         |   -12.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2035 | 2024-05-14 | Imperial          | L   | 0.661      | -            | -                | -                | -         |    -3.39 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2045 | 2024-05-14 | RED Canids        | L   | 0.660      | -            | -                | -                | -         |    -8.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2085 | 2024-05-12 | Solid             | W   | 0.648      | -            | -                | -                | -         |     8.37 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2092 | 2024-05-12 | O PLANO           | W   | 0.647      | -            | -                | -                | -         |     1.76 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2119 | 2024-05-11 | paiN              | L   | 0.640      | -            | -                | -                | -         |    -2.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2143 | 2024-05-10 | Imperial          | W   | 0.634      | 0.435        | 0.234 (0.064)    | -                | -         |    16.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2162 | 2024-05-09 | Sharks            | W   | 0.628      | -            | -                | -                | -         |    11.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2188 | 2024-05-08 | Vikings KR        | W   | 0.620      | -            | -                | -                | -         |     7.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2219 | 2024-05-06 | Sharks            | L   | 0.608      | -            | -                | -                | -         |    -8.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2457 | 2024-04-25 | RED Canids        | L   | 0.535      | -            | -                | -                | -         |    -6.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2459 | 2024-04-25 | RED Canids        | L   | 0.535      | -            | -                | -                | -         |    -6.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2724 | 2024-04-16 | O PLANO           | L   | 0.475      | -            | -                | -                | -         |   -13.72 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2821 | 2024-04-11 | Galorys           | L   | 0.440      | -            | -                | -                | -         |    -8.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     2903 | 2024-04-09 | Galorys           | L   | 0.428      | -            | -                | -                | -         |    -8.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     2908 | 2024-04-09 | Galorys           | W   | 0.428      | -            | -                | -                | -         |     5.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     2944 | 2024-04-08 | RED Canids        | L   | 0.421      | -            | -                | -                | -         |    -5.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     2987 | 2024-04-07 | Sharks            | L   | 0.413      | -            | -                | -                | -         |   -10.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     2995 | 2024-04-06 | Fluxo             | W   | 0.408      | -            | -                | -                | -         |     7.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3032 | 2024-04-04 | adalYamigos       | L   | 0.395      | -            | -                | -                | -         |   -11.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3041 | 2024-04-04 | adalYamigos       | W   | 0.395      | -            | -                | -                | -         |     1.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3049 | 2024-04-04 | Imperial          | L   | 0.394      | -            | -                | -                | -         |    -2.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3086 | 2024-04-03 | Fluxo             | L   | 0.387      | -            | -                | -                | -         |    -5.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3122 | 2024-04-02 | Sharks            | W   | 0.382      | -            | -                | -                | -         |     2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3127 | 2024-04-02 | Fluxo             | L   | 0.381      | -            | -                | -                | -         |    -5.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3216 | 2024-03-27 | W7M               | L   | 0.342      | -            | -                | -                | -         |    -7.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3219 | 2024-03-27 | W7M               | W   | 0.342      | -            | -                | -                | -         |     2.91 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3523 | 2024-03-12 | RED Canids        | L   | 0.240      | -            | -                | -                | -         |    -3.91 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3533 | 2024-03-11 | FURIA Academy     | W   | 0.235      | -            | -                | -                | -         |     0.40 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3556 | 2024-03-10 | adalYamigos       | L   | 0.229      | -            | -                | -                | -         |    -6.53 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3604 | 2024-03-08 | FURIA Academy     | W   | 0.215      | -            | -                | -                | -         |     0.35 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3769 | 2024-03-02 | Wildcard          | L   | 0.174      | -            | -                | -                | -         |    -3.51 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3786 | 2024-03-01 | Liquid            | L   | 0.168      | -            | -                | -                | -         |    -0.32 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     3910 | 2024-02-24 | Imperial          | L   | 0.127      | -            | -                | -                | -         |    -0.89 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     3929 | 2024-02-23 | 9z                | L   | 0.121      | -            | -                | -                | -         |    -0.94 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     3939 | 2024-02-22 | Imperial          | W   | 0.115      | -            | -                | -                | -         |     2.83 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     3946 | 2024-02-22 | 9z                | L   | 0.114      | -            | -                | -                | -         |    -0.89 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     3968 | 2024-02-21 | W7M               | W   | 0.107      | -            | -                | -                | -         |     0.92 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4045 | 2024-02-18 | FURIA Academy     | W   | 0.087      | -            | -                | -                | -         |     0.14 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4089 | 2024-02-16 | Case              | L   | 0.075      | -            | -                | -                | -         |    -1.40 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4208 | 2024-02-12 | FURIA Academy     | W   | 0.048      | -            | -                | -                | -         |     0.08 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,693.98)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-10 |      0.842 | $4,000.00      | $3,366.39       |
| 2024-06-09 |      0.834 | $2,000.00      | $1,668.80       |
| 2024-05-12 |      0.648 | $5,000.00      | $3,237.73       |
| 2024-02-25 |      0.134 | $5,000.00      | $671.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
