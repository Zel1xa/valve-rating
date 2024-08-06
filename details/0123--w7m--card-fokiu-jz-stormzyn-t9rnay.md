### Roster Details<br />
Team Name: W7M<br />
Roster: card, fokiu, jz, stormzyn, t9rnay<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [32]( ../standings_americas.md)<br />
<br />
Final Rank Value:  803.4<br />
<br />
Final Rank Value (803.4) = Starting Rank Value (841.0) + Head To Head Adjustments (-37.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.195[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.0
- 400 + ( ( 0.214 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 841.0


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
|           81 |      136 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -15.72 | card, fokiu, jz, stormzyn, t9rnay      |
|           80 |      336 | 2024-07-27 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.11 | card, fokiu, jz, stormzyn, t9rnay      |
|           79 |      351 | 2024-07-26 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -4.79 | card, fokiu, jz, stormzyn, t9rnay      |
|           78 |      380 | 2024-07-25 | ODDIK             | W   | 1.000      | 0.143        | 0.099 (0.014)    | -                | 0 (0.000) |    22.89 | card, fokiu, jz, stormzyn, t9rnay      |
|           77 |      387 | 2024-07-25 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    22.13 | card, fokiu, jz, stormzyn, t9rnay      |
|           76 |      427 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.89 | card, fokiu, jz, stormzyn, t9rnay      |
|           75 |      432 | 2024-07-24 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.17 | card, fokiu, jz, stormzyn, t9rnay      |
|           74 |      456 | 2024-07-23 | Sharks            | L   | 1.000      | -            | -                | -                | -         |    -9.18 | card, fokiu, jz, stormzyn, t9rnay      |
|           73 |      517 | 2024-07-21 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -13.78 | card, fokiu, jz, stormzyn, t9rnay      |
|           72 |      552 | 2024-07-20 | KRÜ               | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.478 (0.159)    | 0 (0.000) |    15.90 | card, fokiu, jz, stormzyn, t9rnay      |
|           71 |      587 | 2024-07-19 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.775 (0.258)    | 0 (0.000) |    21.84 | card, fokiu, jz, stormzyn, t9rnay      |
|           70 |      698 | 2024-07-17 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.92 | card, fokiu, jz, stormzyn, t9rnay      |
|           69 |      715 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.50 | card, fokiu, jz, stormzyn, t9rnay      |
|           68 |      759 | 2024-07-16 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.79 | card, fokiu, jz, stormzyn, t9rnay      |
|           67 |      863 | 2024-07-12 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -12.95 | card, fokiu, jz, stormzyn, t9rnay      |
|           66 |      873 | 2024-07-11 | Case              | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.778 (0.288)    | 0 (0.000) |    18.12 | card, fokiu, jz, stormzyn, t9rnay      |
|           65 |      880 | 2024-07-11 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.475 (0.176)    | 0 (0.000) |    20.02 | card, fokiu, jz, stormzyn, t9rnay      |
|           64 |      892 | 2024-07-10 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.490 (0.182)    | 0 (0.000) |    18.23 | card, fokiu, jz, stormzyn, t9rnay      |
|           63 |      899 | 2024-07-10 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.70 | card, fokiu, jz, stormzyn, t9rnay      |
|           62 |      922 | 2024-07-09 | Case              | L   | 1.000      | -            | -                | -                | -         |   -11.69 | card, fokiu, jz, stormzyn, t9rnay      |
|           61 |      957 | 2024-07-06 | ODDIK             | L   | 0.995      | -            | -                | -                | -         |    -8.21 | card, fokiu, jz, stormzyn, t9rnay      |
|           60 |      989 | 2024-06-27 | Bounty Hunters    | L   | 0.936      | -            | -                | -                | -         |    -9.49 | card, fokiu, jz, stormzyn, t9rnay      |
|           59 |     1209 | 2024-06-10 | ODDIK             | L   | 0.822      | -            | -                | -                | -         |    -7.84 | card, fokiu, jz, stormzyn, t9rnay      |
|           58 |     1251 | 2024-06-09 | Solid             | W   | 0.815      | 0.450        | 0.024 (0.009)    | 0.807 (0.296)    | -         |    15.81 | card, fokiu, jz, stormzyn, t9rnay      |
|           57 |     1299 | 2024-06-08 | ODDIK             | L   | 0.810      | -            | -                | -                | -         |    -7.96 | card, fokiu, jz, stormzyn, t9rnay      |
|           56 |     1308 | 2024-06-08 | Bounty Hunters    | L   | 0.809      | -            | -                | -                | -         |    -8.54 | card, fokiu, jz, stormzyn, t9rnay      |
|           55 |     1391 | 2024-06-07 | Galorys           | W   | 0.801      | 0.450        | 0.030 (0.011)    | 0.530 (0.191)    | -         |    15.44 | card, fokiu, jz, stormzyn, t9rnay      |
|           54 |     1445 | 2024-06-06 | Fluxo             | L   | 0.795      | -            | -                | -                | -         |    -4.22 | card, fokiu, jz, stormzyn, t9rnay      |
|           53 |     1571 | 2024-06-03 | Vikings KR        | W   | 0.777      | 0.371        | -                | 0.490 (0.141)    | -         |    13.14 | card, fokiu, jz, stormzyn, t9rnay      |
|           52 |     1636 | 2024-06-01 | ex-Corinthians    | W   | 0.761      | -            | -                | -                | -         |     5.27 | card, fokiu, jz, stormzyn, t9rnay      |
|           51 |     1679 | 2024-05-30 | Hype              | L   | 0.750      | -            | -                | -                | -         |    -8.47 | card, fokiu, jz, stormzyn, t9rnay      |
|           50 |     1731 | 2024-05-28 | Yawara            | W   | 0.736      | -            | -                | -                | -         |     4.22 | card, fokiu, jz, stormzyn, t9rnay      |
|           49 |     1856 | 2024-05-22 | Solid             | L   | 0.697      | -            | -                | -                | -         |    -7.77 | card, fokiu, jz, stormzyn, t9rnay      |
|           48 |     1859 | 2024-05-22 | Solid             | L   | 0.696      | -            | -                | -                | -         |    -8.23 | card, fokiu, stormzyn, t9rnay, zede    |
|           47 |     1936 | 2024-05-20 | 9z                | L   | 0.683      | -            | -                | -                | -         |    -0.53 | card, fokiu, stormzyn, t9rnay, zede    |
|           46 |     1939 | 2024-05-20 | 9z                | L   | 0.683      | -            | -                | -                | -         |    -0.53 | card, fokiu, stormzyn, t9rnay, zede    |
|           45 |     2059 | 2024-05-16 | Sharks            | L   | 0.657      | -            | -                | -                | -         |    -4.83 | card, fokiu, stormzyn, t9rnay, zede    |
|           44 |     2062 | 2024-05-16 | Sharks            | L   | 0.656      | -            | -                | -                | -         |    -5.04 | card, fokiu, stormzyn, t9rnay, zede    |
|           43 |     2158 | 2024-05-14 | Imperial          | L   | 0.644      | -            | -                | -                | -         |    -1.37 | card, fokiu, stormzyn, t9rnay, zede    |
|           42 |     2161 | 2024-05-14 | Imperial          | L   | 0.644      | -            | -                | -                | -         |    -1.39 | card, fokiu, stormzyn, t9rnay, zede    |
|           41 |     2174 | 2024-05-14 | Hype              | L   | 0.642      | -            | -                | -                | -         |    -8.06 | card, fokiu, stormzyn, t9rnay, zede    |
|           40 |     2207 | 2024-05-13 | Sharks            | L   | 0.635      | -            | -                | -                | -         |    -5.75 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           39 |     2255 | 2024-05-11 | Sharks            | L   | 0.622      | -            | -                | -                | -         |    -5.90 | card, fokiu, stormzyn, t9rnay, zede    |
|           38 |     2306 | 2024-05-09 | KRÜ               | L   | 0.608      | -            | -                | -                | -         |    -7.43 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           37 |     2339 | 2024-05-07 | paiN              | L   | 0.596      | -            | -                | -                | -         |    -0.77 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           36 |     2359 | 2024-05-06 | paiN              | L   | 0.589      | -            | -                | -                | -         |    -0.77 | fokiu, jz, saadzin, stormzyn, zede     |
|           35 |     2360 | 2024-05-06 | paiN              | L   | 0.589      | -            | -                | -                | -         |    -0.77 | fokiu, jz, saadzin, stormzyn, zede     |
|           34 |     2382 | 2024-05-05 | Galorys           | W   | 0.581      | 0.435        | 0.030 (0.008)    | 0.530 (0.134)    | -         |    11.11 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           33 |     2567 | 2024-04-26 | ODDIK             | L   | 0.523      | -            | -                | -                | -         |    -5.06 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           32 |     2568 | 2024-04-26 | ODDIK             | L   | 0.522      | -            | -                | -                | -         |    -5.26 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           31 |     2832 | 2024-04-17 | ODDIK             | L   | 0.463      | -            | -                | -                | -         |    -5.00 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           30 |     2868 | 2024-04-16 | Sharks            | W   | 0.457      | -            | -                | -                | -         |     5.98 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           29 |     2935 | 2024-04-12 | RED Canids        | L   | 0.428      | -            | -                | -                | -         |    -2.61 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           28 |     3044 | 2024-04-09 | RED Canids        | L   | 0.410      | -            | -                | -                | -         |    -2.56 | fokiu, jz, saadzin, stormzyn, zede     |
|           27 |     3049 | 2024-04-09 | RED Canids        | L   | 0.410      | -            | -                | -                | -         |    -2.62 | fokiu, jz, saadzin, stormzyn, zede     |
|           26 |     3082 | 2024-04-08 | MIBR              | L   | 0.403      | -            | -                | -                | -         |    -0.51 | fokiu, jz, saadzin, stormzyn, zede     |
|           25 |     3138 | 2024-04-06 | RED Canids        | W   | 0.388      | 0.435        | 0.076 (0.013)    | 0.732 (0.123)    | -         |     9.87 | fokiu, jz, saadzin, stormzyn, zede     |
|           24 |     3355 | 2024-03-27 | BESTIA            | W   | 0.324      | 0.450        | 0.096 (0.014)    | -                | -         |     7.52 | fokiu, jz, saadzin, stormzyn, zede     |
|           23 |     3359 | 2024-03-27 | BESTIA            | L   | 0.323      | -            | -                | -                | -         |    -2.69 | fokiu, jz, saadzin, stormzyn, zede     |
|           22 |     3592 | 2024-03-14 | Galorys           | L   | 0.237      | -            | -                | -                | -         |    -3.10 | fokiu, jz, saadzin, stormzyn, zede     |
|           21 |     3594 | 2024-03-14 | Galorys           | L   | 0.237      | -            | -                | -                | -         |    -3.16 | fokiu, jz, saadzin, stormzyn, zede     |
|           20 |     3689 | 2024-03-11 | Solid             | L   | 0.215      | -            | -                | -                | -         |    -2.87 | fokiu, jz, saadzin, stormzyn, zede     |
|           19 |     3724 | 2024-03-09 | RED Canids        | L   | 0.203      | -            | -                | -                | -         |    -1.36 | fokiu, jz, saadzin, stormzyn, zede     |
|           18 |     3784 | 2024-03-07 | Solid             | W   | 0.188      | -            | -                | -                | -         |     3.48 | fokiu, jz, saadzin, stormzyn, zede     |
|           17 |     3838 | 2024-03-05 | 2GAME             | L   | 0.177      | -            | -                | -                | -         |    -3.94 | fokiu, jz, saadzin, stormzyn, zede     |
|           16 |     3840 | 2024-03-05 | 2GAME             | L   | 0.177      | -            | -                | -                | -         |    -3.98 | fokiu, jz, saadzin, stormzyn, zede     |
|           15 |     4045 | 2024-02-24 | Corinthians       | W   | 0.110      | -            | -                | -                | -         |     0.47 | fokiu, jz, saadzin, stormzyn, zede     |
|           14 |     4052 | 2024-02-24 | Corinthians       | W   | 0.110      | -            | -                | -                | -         |     0.47 | fokiu, jz, saadzin, stormzyn, zede     |
|           13 |     4105 | 2024-02-21 | Fluxo             | W   | 0.090      | -            | -                | -                | -         |     2.17 | fokiu, jz, saadzin, stormzyn, zede     |
|           12 |     4110 | 2024-02-21 | Fluxo             | L   | 0.090      | -            | -                | -                | -         |    -0.68 | fokiu, jz, saadzin, stormzyn, zede     |
|           11 |     4115 | 2024-02-21 | BESTIA            | L   | 0.088      | -            | -                | -                | -         |    -0.75 | fokiu, jz, saadzin, stormzyn, zede     |
|           10 |     4144 | 2024-02-20 | Case              | L   | 0.083      | -            | -                | -                | -         |    -0.95 | fokiu, jz, saadzin, stormzyn, zede     |
|            9 |     4209 | 2024-02-17 | Sharks            | W   | 0.063      | -            | -                | -                | -         |     1.34 | fokiu, jz, saadzin, stormzyn, zede     |
|            8 |     4240 | 2024-02-16 | Solid             | L   | 0.056      | -            | -                | -                | -         |    -0.74 | fokiu, jz, saadzin, stormzyn, zede     |
|            7 |     4249 | 2024-02-16 | Sharks            | L   | 0.055      | -            | -                | -                | -         |    -0.57 | fokiu, jz, saadzin, stormzyn, zede     |
|            6 |     4268 | 2024-02-15 | Fluxo             | L   | 0.049      | -            | -                | -                | -         |    -0.38 | fokiu, jz, saadzin, stormzyn, zede     |
|            5 |     4298 | 2024-02-14 | Hawks             | W   | 0.044      | -            | -                | -                | -         |     0.21 | fokiu, jz, saadzin, stormzyn, zede     |
|            4 |     4338 | 2024-02-13 | Case              | L   | 0.037      | -            | -                | -                | -         |    -0.43 | fokiu, jz, saadzin, stormzyn, zede     |
|            3 |     4343 | 2024-02-13 | Case              | W   | 0.037      | -            | -                | -                | -         |     0.73 | fokiu, jz, saadzin, stormzyn, zede     |
|            2 |     4349 | 2024-02-13 | Corinthians       | W   | 0.035      | -            | -                | -                | -         |     0.15 | fokiu, jz, saadzin, stormzyn, zede     |
|            1 |     4360 | 2024-02-12 | Corinthians       | W   | 0.029      | -            | -                | -                | -         |     0.12 | fokiu, jz, saadzin, stormzyn, zede     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,244.81)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.816 | $300.00        | $244.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
