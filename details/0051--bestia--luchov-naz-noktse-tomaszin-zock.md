### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1026.0<br />
<br />
Final Rank Value (1026.0) = Starting Rank Value (962.4) + Head To Head Adjustments (63.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.507[<sup>1</sup>](#table2)
- Bounty Collected: 0.430[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 962.4
- 400 + ( ( 0.290 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 962.4


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
|          103 |      112 | 2024-09-04 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -14.85 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |      137 | 2024-09-03 | Bounty Hunters    | W   | 1.000      | 0.371        | -                | 0.440 (0.163)    | 0 (0.000) |     7.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |      173 | 2024-09-02 | paiN Academy      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.82 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |      380 | 2024-08-27 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.22 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      434 | 2024-08-26 | Galorys           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.32 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      450 | 2024-08-26 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.96 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      858 | 2024-08-13 | MIBR              | W   | 1.000      | 0.450        | 0.156 (0.070)    | 0.644 (0.290)    | 0 (0.000) |    26.36 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      862 | 2024-08-13 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.66 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      867 | 2024-08-13 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.97 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      948 | 2024-08-11 | Case              | W   | 1.000      | 0.333        | -                | 0.727 (0.242)    | 0 (0.000) |    11.67 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      993 | 2024-08-09 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.02 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |     1055 | 2024-08-07 | 9z Academy        | W   | 0.988      | -            | -                | -                | 0 (0.000) |     2.12 | luchov, Luken, Noktse, tomaszin, zock  |
|           91 |     1188 | 2024-08-03 | Vikings KR        | W   | 0.963      | -            | -                | -                | -         |     8.74 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |     1195 | 2024-08-03 | ODDIK             | L   | 0.962      | -            | -                | -                | -         |   -10.19 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |     1224 | 2024-08-02 | Case              | W   | 0.956      | -            | -                | -                | -         |    11.96 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |     1233 | 2024-08-02 | Solid             | L   | 0.954      | -            | -                | -                | -         |   -16.94 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |     1254 | 2024-08-01 | Players           | W   | 0.950      | -            | -                | -                | -         |     5.05 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |     1258 | 2024-08-01 | LaChampionsLiga   | W   | 0.950      | -            | -                | -                | -         |     2.28 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |     1271 | 2024-08-01 | Fluxo             | L   | 0.948      | -            | -                | -                | -         |    -9.54 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |     1353 | 2024-07-30 | Galorys           | L   | 0.936      | -            | -                | -                | -         |   -21.87 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |     1359 | 2024-07-30 | Galorys           | W   | 0.936      | -            | -                | -                | -         |     7.24 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |     1367 | 2024-07-30 | KRÜ               | W   | 0.934      | 0.371        | -                | 0.629 (0.218)    | -         |     9.00 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |     1394 | 2024-07-29 | Intense           | W   | 0.929      | -            | -                | -                | -         |     7.17 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |     1423 | 2024-07-28 | Vikings KR        | W   | 0.923      | -            | -                | -                | -         |     7.08 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |     1505 | 2024-07-25 | Sharks            | L   | 0.903      | -            | -                | -                | -         |   -13.29 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |     1513 | 2024-07-25 | Bad News Chickens | W   | 0.903      | -            | -                | -                | -         |     4.40 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |     1582 | 2024-07-23 | Fluxo             | L   | 0.890      | -            | -                | -                | -         |    -8.33 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |     1587 | 2024-07-23 | Hype              | W   | 0.889      | -            | -                | -                | -         |     9.16 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |     1622 | 2024-07-22 | Fluxo             | W   | 0.881      | 0.384        | 0.122 (0.041)    | 0.649 (0.220)    | -         |    20.72 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |     1647 | 2024-07-21 | RED Canids        | W   | 0.874      | 0.384        | -                | 0.612 (0.206)    | -         |    19.08 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |     1704 | 2024-07-19 | KRÜ               | W   | 0.862      | 0.384        | -                | 0.629 (0.209)    | -         |     9.70 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |     1715 | 2024-07-19 | W7M               | L   | 0.861      | -            | -                | -                | -         |   -18.59 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |     1755 | 2024-07-18 | Imperial          | L   | 0.855      | -            | -                | -                | -         |    -8.36 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |     1757 | 2024-07-18 | Amigos de T2M4SS  | W   | 0.855      | -            | -                | -                | -         |     1.20 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |     1769 | 2024-07-18 | ODDIK             | L   | 0.854      | -            | -                | -                | -         |    -9.50 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1817 | 2024-07-17 | Fluxo             | L   | 0.849      | -            | -                | -                | -         |    -8.98 | luchov, naz, Noktse, tomaszin, zock    |
|           67 |     1821 | 2024-07-17 | Fluxo             | L   | 0.849      | -            | -                | -                | -         |    -9.61 | luchov, naz, Noktse, tomaszin, zock    |
|           66 |     1831 | 2024-07-17 | Vikings KR        | W   | 0.848      | -            | -                | -                | -         |     7.26 | luchov, naz, Noktse, tomaszin, zock    |
|           65 |     1883 | 2024-07-16 | ODDIK             | L   | 0.843      | -            | -                | -                | -         |    -9.26 | luchov, naz, Noktse, tomaszin, zock    |
|           64 |     1887 | 2024-07-16 | ODDIK             | W   | 0.843      | 0.450        | 0.190 (0.072)    | 0.839 (0.318)    | -         |    17.71 | luchov, naz, Noktse, tomaszin, zock    |
|           63 |     1896 | 2024-07-16 | ODDIK             | L   | 0.841      | -            | -                | -                | -         |    -8.65 | luchov, naz, Noktse, tomaszin, zock    |
|           62 |     1945 | 2024-07-15 | Vikings KR        | W   | 0.834      | -            | -                | -                | -         |     6.70 | luchov, naz, Noktse, tomaszin, zock    |
|           61 |     1978 | 2024-07-13 | Intense           | W   | 0.822      | -            | -                | -                | -         |     5.42 | luchov, naz, Noktse, tomaszin, zock    |
|           60 |     1991 | 2024-07-12 | SPORT             | L   | 0.815      | -            | -                | -                | -         |   -21.02 | luchov, naz, Noktse, tomaszin, zock    |
|           59 |     2022 | 2024-07-10 | Sharks            | L   | 0.802      | -            | -                | -                | -         |   -11.96 | luchov, naz, Noktse, tomaszin, zock    |
|           58 |     2050 | 2024-07-09 | SPORT             | W   | 0.795      | -            | -                | -                | -         |     3.99 | luchov, naz, Noktse, tomaszin, zock    |
|           57 |     2065 | 2024-07-08 | Intense           | W   | 0.788      | -            | -                | -                | -         |     4.70 | luchov, naz, Noktse, tomaszin, zock    |
|           56 |     2073 | 2024-07-08 | Bounty Hunters    | L   | 0.787      | -            | -                | -                | -         |   -15.88 | luchov, naz, Noktse, tomaszin, zock    |
|           55 |     2205 | 2024-06-15 | 9z                | L   | 0.633      | -            | -                | -                | -         |    -1.76 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     2236 | 2024-06-14 | paiN              | L   | 0.628      | -            | -                | -                | -         |    -0.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     2335 | 2024-06-10 | paiN              | L   | 0.603      | -            | -                | -                | -         |    -0.77 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     2341 | 2024-06-10 | Bounty Hunters    | W   | 0.601      | -            | -                | -                | -         |     6.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     2369 | 2024-06-09 | RED Canids        | W   | 0.596      | -            | -                | -                | -         |    11.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     2397 | 2024-06-09 | Sharks            | L   | 0.594      | -            | -                | -                | -         |    -7.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     2436 | 2024-06-08 | Solid             | W   | 0.589      | -            | -                | -                | -         |     5.87 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     2451 | 2024-06-08 | Vikings KR        | L   | 0.588      | -            | -                | -                | -         |   -14.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     2497 | 2024-06-07 | ODDIK             | W   | 0.582      | 0.450        | 0.190 (0.050)    | 0.839 (0.220)    | -         |    10.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     2557 | 2024-06-06 | inSanitY          | L   | 0.575      | -            | -                | -                | -         |   -11.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2617 | 2024-06-05 | MIBR              | L   | 0.569      | -            | -                | -                | -         |    -1.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2669 | 2024-06-04 | Sharks            | L   | 0.563      | -            | -                | -                | -         |    -7.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2983 | 2024-05-22 | Case              | W   | 0.476      | -            | -                | -                | -         |     6.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2989 | 2024-05-22 | Case              | W   | 0.476      | -            | -                | -                | -         |     6.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2991 | 2024-05-22 | Fluxo             | W   | 0.475      | 0.450        | 0.122 (0.026)    | -                | -         |     8.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2994 | 2024-05-22 | Fluxo             | W   | 0.475      | -            | -                | -                | -         |     8.47 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     3030 | 2024-05-21 | Players           | W   | 0.469      | -            | -                | -                | -         |     2.48 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     3033 | 2024-05-21 | Players           | W   | 0.469      | -            | -                | -                | -         |     2.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     3036 | 2024-05-21 | Imperial          | W   | 0.469      | 0.450        | 0.150 (0.032)    | -                | -         |    10.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     3037 | 2024-05-21 | Imperial          | W   | 0.468      | 0.450        | 0.150 (0.032)    | -                | -         |    10.43 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     3069 | 2024-05-20 | Corinthians       | W   | 0.463      | -            | -                | -                | -         |     0.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     3071 | 2024-05-20 | 9z                | W   | 0.462      | 0.450        | 0.362 (0.075)    | -                | -         |    13.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     3074 | 2024-05-20 | 9z                | L   | 0.462      | -            | -                | -                | -         |    -0.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     3156 | 2024-05-17 | Solid             | L   | 0.443      | -            | -                | -                | -         |    -8.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     3157 | 2024-05-17 | Solid             | W   | 0.443      | -            | -                | -                | -         |     5.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     3241 | 2024-05-15 | ODDIK             | W   | 0.429      | 0.450        | 0.190 (0.037)    | 0.839 (0.162)    | -         |     9.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     3242 | 2024-05-15 | ODDIK             | W   | 0.429      | 0.450        | 0.190 (0.037)    | -                | -         |     9.50 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     3252 | 2024-05-15 | Hype              | L   | 0.428      | -            | -                | -                | -         |    -8.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3303 | 2024-05-14 | Imperial          | L   | 0.422      | -            | -                | -                | -         |    -3.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3313 | 2024-05-14 | RED Canids        | L   | 0.421      | -            | -                | -                | -         |    -5.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3353 | 2024-05-12 | Solid             | W   | 0.409      | -            | -                | -                | -         |     4.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3360 | 2024-05-12 | O PLANO           | W   | 0.408      | -            | -                | -                | -         |     1.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3387 | 2024-05-11 | paiN              | L   | 0.401      | -            | -                | -                | -         |    -0.27 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3411 | 2024-05-10 | Imperial          | W   | 0.395      | -            | -                | -                | -         |     8.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3430 | 2024-05-09 | Sharks            | W   | 0.389      | -            | -                | -                | -         |     8.23 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3457 | 2024-05-08 | Vikings KR        | W   | 0.381      | -            | -                | -                | -         |     3.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3488 | 2024-05-06 | Sharks            | L   | 0.369      | -            | -                | -                | -         |    -3.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3727 | 2024-04-25 | RED Canids        | L   | 0.296      | -            | -                | -                | -         |    -3.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3729 | 2024-04-25 | RED Canids        | L   | 0.296      | -            | -                | -                | -         |    -3.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3994 | 2024-04-16 | O PLANO           | L   | 0.236      | -            | -                | -                | -         |    -6.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     4091 | 2024-04-11 | Galorys           | L   | 0.201      | -            | -                | -                | -         |    -4.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     4173 | 2024-04-09 | Galorys           | L   | 0.189      | -            | -                | -                | -         |    -4.56 | luchov, meyern, naz, Noktse, tomaszin  |
|           13 |     4178 | 2024-04-09 | Galorys           | W   | 0.189      | -            | -                | -                | -         |     1.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           12 |     4214 | 2024-04-08 | RED Canids        | L   | 0.182      | -            | -                | -                | -         |    -2.65 | luchov, meyern, naz, Noktse, tomaszin  |
|           11 |     4257 | 2024-04-07 | Sharks            | L   | 0.174      | -            | -                | -                | -         |    -4.29 | luchov, meyern, naz, Noktse, tomaszin  |
|           10 |     4265 | 2024-04-06 | Fluxo             | W   | 0.169      | -            | -                | -                | -         |     1.26 | luchov, meyern, naz, Noktse, tomaszin  |
|            9 |     4302 | 2024-04-04 | adalYamigos       | L   | 0.156      | -            | -                | -                | -         |    -4.51 | luchov, meyern, naz, Noktse, tomaszin  |
|            8 |     4311 | 2024-04-04 | adalYamigos       | W   | 0.156      | -            | -                | -                | -         |     0.41 | luchov, meyern, naz, Noktse, tomaszin  |
|            7 |     4319 | 2024-04-04 | Imperial          | L   | 0.155      | -            | -                | -                | -         |    -1.79 | luchov, meyern, naz, Noktse, tomaszin  |
|            6 |     4356 | 2024-04-03 | Fluxo             | L   | 0.148      | -            | -                | -                | -         |    -3.67 | luchov, meyern, naz, Noktse, tomaszin  |
|            5 |     4392 | 2024-04-02 | Sharks            | W   | 0.143      | -            | -                | -                | -         |     0.92 | luchov, meyern, naz, Noktse, tomaszin  |
|            4 |     4397 | 2024-04-02 | Fluxo             | L   | 0.142      | -            | -                | -                | -         |    -3.53 | luchov, meyern, naz, Noktse, tomaszin  |
|            3 |     4486 | 2024-03-27 | W7M               | L   | 0.103      | -            | -                | -                | -         |    -2.38 | luchov, meyern, naz, Noktse, tomaszin  |
|            2 |     4490 | 2024-03-27 | W7M               | W   | 0.103      | -            | -                | -                | -         |     0.87 | luchov, meyern, naz, Noktse, tomaszin  |
|            1 |     4801 | 2024-03-12 | RED Canids        | L   | 0.001      | -            | -                | -                | -         |    -0.02 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($32,453.80)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-04 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-08-13 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-08-02 |      0.956 | $750.00        | $716.94         |
| 2024-07-22 |      0.881 | $20,000.00     | $17,627.78      |
| 2024-06-16 |      0.643 | $1,500.00      | $964.44         |
| 2024-06-10 |      0.603 | $4,000.00      | $2,410.65       |
| 2024-06-09 |      0.595 | $2,000.00      | $1,190.93       |
| 2024-05-12 |      0.409 | $5,000.00      | $2,043.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
