### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1005.2<br />
<br />
Final Rank Value (1005.2) = Starting Rank Value (1017.4) + Head To Head Adjustments (-12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.488[<sup>1</sup>](#table2)
- Bounty Collected: 0.435[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.300<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1017.4
- 400 + ( ( 0.300 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1017.4


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
|          100 |       68 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.43 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |       74 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | 0 (0.000) |     7.57 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |       82 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.67 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      110 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.60 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      139 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.67 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      221 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -15.88 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      229 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.12 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      298 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.30 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      303 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.63 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      339 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.122 (0.047)    | 0.701 (0.270)    | 0 (0.000) |    23.66 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      365 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | -                | 0.753 (0.290)    | 0 (0.000) |    23.04 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      423 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.55 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      435 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -19.62 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      480 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -6.43 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      482 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.20 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      494 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.82 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      542 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.13 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      546 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.84 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      556 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     9.59 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      608 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.66 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      612 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |    19.12 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      622 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.09 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      674 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.89 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      708 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     4.13 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      721 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.89 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      752 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.06 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      780 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.61 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      795 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     3.45 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      803 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.13 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |     1056 | 2024-06-10 | paiN              | L   | 0.856      | -            | -                | -                | -         |    -5.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           70 |     1062 | 2024-06-10 | Bounty Hunters    | W   | 0.855      | -            | -                | -                | -         |     9.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           69 |     1090 | 2024-06-09 | RED Canids        | W   | 0.850      | 0.371        | -                | 0.753 (0.237)    | -         |    15.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           68 |     1118 | 2024-06-09 | Sharks            | L   | 0.847      | -            | -                | -                | -         |   -13.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1159 | 2024-06-08 | Solid             | W   | 0.842      | 0.371        | -                | 0.843 (0.263)    | -         |     8.31 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1174 | 2024-06-08 | Vikings KR        | L   | 0.841      | -            | -                | -                | -         |   -20.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1227 | 2024-06-07 | ODDIK             | W   | 0.836      | 0.450        | 0.096 (0.036)    | 0.822 (0.309)    | -         |     9.45 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1289 | 2024-06-06 | inSanitY          | L   | 0.829      | -            | -                | -                | -         |   -16.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1351 | 2024-06-05 | MIBR              | L   | 0.823      | -            | -                | -                | -         |    -3.37 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1404 | 2024-06-04 | Sharks            | L   | 0.816      | -            | -                | -                | -         |   -14.39 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1721 | 2024-05-22 | Case              | W   | 0.730      | -            | -                | -                | -         |     7.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1727 | 2024-05-22 | Case              | W   | 0.729      | -            | -                | -                | -         |     7.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1729 | 2024-05-22 | Fluxo             | W   | 0.729      | 0.450        | 0.122 (0.040)    | -                | -         |    12.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1732 | 2024-05-22 | Fluxo             | W   | 0.729      | 0.450        | 0.122 (0.040)    | -                | -         |    13.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1780 | 2024-05-21 | Smoke             | W   | 0.723      | -            | -                | -                | -         |     4.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1783 | 2024-05-21 | Smoke             | W   | 0.723      | -            | -                | -                | -         |     4.75 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1788 | 2024-05-21 | Imperial          | W   | 0.722      | 0.450        | 0.240 (0.078)    | -                | -         |    18.86 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1789 | 2024-05-21 | Imperial          | W   | 0.722      | 0.450        | 0.240 (0.078)    | -                | -         |    19.50 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1820 | 2024-05-20 | Corinthians       | W   | 0.716      | -            | -                | -                | -         |     1.49 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1824 | 2024-05-20 | Corinthians       | W   | 0.716      | -            | -                | -                | -         |     1.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1826 | 2024-05-20 | 9z                | W   | 0.716      | 0.450        | 0.138 (0.044)    | -                | -         |    17.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1829 | 2024-05-20 | 9z                | L   | 0.715      | -            | -                | -                | -         |    -5.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1920 | 2024-05-17 | Solid             | L   | 0.697      | -            | -                | -                | -         |   -13.57 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1921 | 2024-05-17 | Solid             | W   | 0.696      | 0.450        | -                | 0.843 (0.264)    | -         |     8.42 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     2005 | 2024-05-15 | ODDIK             | W   | 0.683      | 0.450        | 0.096 (0.030)    | 0.822 (0.252)    | -         |    10.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     2006 | 2024-05-15 | ODDIK             | W   | 0.682      | 0.450        | -                | 0.822 (0.252)    | -         |    11.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2016 | 2024-05-15 | Hype              | L   | 0.681      | -            | -                | -                | -         |   -12.43 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2073 | 2024-05-14 | Imperial          | L   | 0.676      | -            | -                | -                | -         |    -3.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2083 | 2024-05-14 | RED Canids        | L   | 0.675      | -            | -                | -                | -         |    -8.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2126 | 2024-05-12 | Solid             | W   | 0.662      | -            | -                | -                | -         |     8.31 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2133 | 2024-05-12 | O PLANO           | W   | 0.661      | -            | -                | -                | -         |     1.71 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2160 | 2024-05-11 | paiN              | L   | 0.655      | -            | -                | -                | -         |    -2.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2184 | 2024-05-10 | Imperial          | W   | 0.648      | 0.435        | 0.240 (0.067)    | -                | -         |    17.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2203 | 2024-05-09 | Sharks            | W   | 0.643      | -            | -                | -                | -         |    11.31 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2232 | 2024-05-08 | Vikings KR        | W   | 0.635      | -            | -                | -                | -         |     7.23 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2263 | 2024-05-06 | Sharks            | L   | 0.623      | -            | -                | -                | -         |    -8.44 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2505 | 2024-04-25 | RED Canids        | L   | 0.550      | -            | -                | -                | -         |    -5.87 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2507 | 2024-04-25 | RED Canids        | L   | 0.549      | -            | -                | -                | -         |    -6.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2781 | 2024-04-16 | O PLANO           | L   | 0.490      | -            | -                | -                | -         |   -14.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2880 | 2024-04-11 | Galorys           | L   | 0.455      | -            | -                | -                | -         |    -8.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2962 | 2024-04-09 | Galorys           | L   | 0.443      | -            | -                | -                | -         |    -8.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2967 | 2024-04-09 | Galorys           | W   | 0.443      | -            | -                | -                | -         |     5.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     3003 | 2024-04-08 | RED Canids        | L   | 0.436      | -            | -                | -                | -         |    -5.65 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     3046 | 2024-04-07 | Sharks            | L   | 0.427      | -            | -                | -                | -         |   -10.43 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3054 | 2024-04-06 | Fluxo             | W   | 0.423      | -            | -                | -                | -         |     8.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3091 | 2024-04-04 | adalYamigos       | L   | 0.410      | -            | -                | -                | -         |   -11.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3100 | 2024-04-04 | adalYamigos       | W   | 0.409      | -            | -                | -                | -         |     1.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3108 | 2024-04-04 | Imperial          | L   | 0.409      | -            | -                | -                | -         |    -2.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3147 | 2024-04-03 | Fluxo             | L   | 0.402      | -            | -                | -                | -         |    -5.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3189 | 2024-04-02 | Sharks            | W   | 0.397      | -            | -                | -                | -         |     2.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3194 | 2024-04-02 | Fluxo             | L   | 0.395      | -            | -                | -                | -         |    -5.29 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3283 | 2024-03-27 | W7M               | L   | 0.357      | -            | -                | -                | -         |    -8.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3288 | 2024-03-27 | W7M               | W   | 0.356      | -            | -                | -                | -         |     3.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3608 | 2024-03-12 | RED Canids        | L   | 0.255      | -            | -                | -                | -         |    -3.85 | deco, luchov, meyern, Noktse, tomaszin |
|           17 |     3618 | 2024-03-11 | FURIA Academy     | W   | 0.250      | -            | -                | -                | -         |     0.46 | deco, luchov, meyern, Noktse, tomaszin |
|           16 |     3641 | 2024-03-10 | adalYamigos       | L   | 0.243      | -            | -                | -                | -         |    -6.87 | deco, luchov, meyern, Noktse, tomaszin |
|           15 |     3690 | 2024-03-08 | FURIA Academy     | W   | 0.230      | -            | -                | -                | -         |     0.41 | deco, luchov, meyern, Noktse, tomaszin |
|           14 |     3860 | 2024-03-02 | Wildcard          | L   | 0.188      | -            | -                | -                | -         |    -3.83 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3878 | 2024-03-01 | Liquid            | L   | 0.183      | -            | -                | -                | -         |    -0.49 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     4005 | 2024-02-24 | Imperial          | L   | 0.141      | -            | -                | -                | -         |    -0.87 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     4026 | 2024-02-23 | 9z                | L   | 0.135      | -            | -                | -                | -         |    -1.03 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     4038 | 2024-02-22 | Imperial          | W   | 0.130      | -            | -                | -                | -         |     3.29 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     4046 | 2024-02-22 | 9z                | L   | 0.129      | -            | -                | -                | -         |    -0.97 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4069 | 2024-02-21 | W7M               | W   | 0.121      | -            | -                | -                | -         |     1.13 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4146 | 2024-02-18 | FURIA Academy     | W   | 0.101      | -            | -                | -                | -         |     0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4191 | 2024-02-16 | Case              | L   | 0.090      | -            | -                | -                | -         |    -1.70 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4298 | 2024-02-13 | MIBR              | W   | 0.070      | -            | -                | -                | -         |     1.99 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4299 | 2024-02-13 | MIBR              | W   | 0.070      | -            | -                | -                | -         |     1.99 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4304 | 2024-02-13 | paiN              | W   | 0.070      | -            | -                | -                | -         |     1.92 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4305 | 2024-02-13 | paiN              | W   | 0.070      | -            | -                | -                | -         |     1.92 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4318 | 2024-02-12 | FURIA Academy     | W   | 0.063      | -            | -                | -                | -         |     0.11 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,178.80)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-10 |      0.856 | $4,000.00      | $3,425.09       |
| 2024-06-09 |      0.849 | $2,000.00      | $1,698.15       |
| 2024-05-12 |      0.662 | $5,000.00      | $3,311.11       |
| 2024-02-25 |      0.149 | $5,000.00      | $744.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
