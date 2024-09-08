### Roster Details<br />
Team Name: W7M<br />
Roster: card, fokiu, jz, stormzyn, t9rnay<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  806.0<br />
<br />
Final Rank Value (806.0) = Starting Rank Value (783.4) + Head To Head Adjustments (22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.198<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 783.4
- 400 + ( ( 0.198 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 783.4


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
|           65 |      315 | 2024-08-28 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -6.58 | card, fokiu, jz, stormzyn, t9rnay      |
|           64 |      381 | 2024-08-27 | Case              | L   | 1.000      | -            | -                | -                | -         |   -12.59 | card, fokiu, jz, stormzyn, t9rnay      |
|           63 |      432 | 2024-08-26 | Sharks            | W   | 1.000      | 0.143        | 0.056 (0.008)    | 0.537 (0.077)    | 0 (0.000) |    23.48 | card, fokiu, jz, stormzyn, t9rnay      |
|           62 |      446 | 2024-08-26 | Bounty Hunters    | W   | 1.000      | 0.143        | 0.026 (0.004)    | -                | 0 (0.000) |    17.60 | card, fokiu, jz, stormzyn, t9rnay      |
|           61 |     1264 | 2024-08-01 | Dusty Roots       | L   | 0.949      | -            | -                | -                | -         |   -15.70 | card, fokiu, jz, stormzyn, t9rnay      |
|           60 |     1464 | 2024-07-27 | Bad News Chickens | L   | 0.914      | -            | -                | -                | -         |   -19.57 | card, fokiu, jz, stormzyn, t9rnay      |
|           59 |     1479 | 2024-07-26 | Fluxo             | L   | 0.909      | -            | -                | -                | -         |    -4.76 | card, fokiu, jz, stormzyn, t9rnay      |
|           58 |     1508 | 2024-07-25 | ODDIK             | W   | 0.903      | 0.143        | 0.190 (0.024)    | 0.839 (0.108)    | 0 (0.000) |    21.98 | card, fokiu, jz, stormzyn, t9rnay      |
|           57 |     1515 | 2024-07-25 | Bounty Hunters    | W   | 0.903      | -            | -                | -                | 0 (0.000) |    18.82 | card, fokiu, jz, stormzyn, t9rnay      |
|           56 |     1555 | 2024-07-24 | Yawara            | W   | 0.895      | -            | -                | -                | 0 (0.000) |     4.50 | card, fokiu, jz, stormzyn, t9rnay      |
|           55 |     1560 | 2024-07-24 | Bad News Chickens | L   | 0.894      | -            | -                | -                | -         |   -18.78 | card, fokiu, jz, stormzyn, t9rnay      |
|           54 |     1584 | 2024-07-23 | Sharks            | L   | 0.889      | -            | -                | -                | -         |    -7.46 | card, fokiu, jz, stormzyn, t9rnay      |
|           53 |     1645 | 2024-07-21 | Hype              | L   | 0.875      | -            | -                | -                | -         |   -12.06 | card, fokiu, jz, stormzyn, t9rnay      |
|           52 |     1680 | 2024-07-20 | KRÜ               | W   | 0.868      | 0.333        | 0.017 (0.005)    | 0.629 (0.182)    | 0 (0.000) |    14.04 | card, fokiu, jz, stormzyn, t9rnay      |
|           51 |     1715 | 2024-07-19 | BESTIA            | W   | 0.861      | 0.333        | 0.107 (0.031)    | 0.807 (0.232)    | 0 (0.000) |    18.59 | card, fokiu, jz, stormzyn, t9rnay      |
|           50 |     1826 | 2024-07-17 | SPORT             | W   | 0.849      | -            | -                | -                | 0 (0.000) |    10.15 | card, fokiu, jz, stormzyn, t9rnay      |
|           49 |     1843 | 2024-07-17 | paiN              | L   | 0.847      | -            | -                | -                | -         |    -0.40 | card, fokiu, jz, stormzyn, t9rnay      |
|           48 |     1889 | 2024-07-16 | Hype              | L   | 0.842      | -            | -                | -                | -         |   -10.21 | card, fokiu, jz, stormzyn, t9rnay      |
|           47 |     1994 | 2024-07-12 | KRÜ               | L   | 0.814      | -            | -                | -                | -         |   -10.64 | card, fokiu, jz, stormzyn, t9rnay      |
|           46 |     2004 | 2024-07-11 | Case              | W   | 0.809      | 0.371        | 0.039 (0.012)    | 0.727 (0.218)    | 0 (0.000) |    16.01 | card, fokiu, jz, stormzyn, t9rnay      |
|           45 |     2011 | 2024-07-11 | Hype              | W   | 0.807      | 0.371        | 0.023 (0.007)    | 0.435 (0.130)    | 0 (0.000) |    15.99 | card, fokiu, jz, stormzyn, t9rnay      |
|           44 |     2023 | 2024-07-10 | Vikings KR        | W   | 0.802      | 0.371        | -                | 0.439 (0.130)    | -         |    13.60 | card, fokiu, jz, stormzyn, t9rnay      |
|           43 |     2030 | 2024-07-10 | 9z Academy        | W   | 0.801      | -            | -                | -                | -         |     4.95 | card, fokiu, jz, stormzyn, t9rnay      |
|           42 |     2053 | 2024-07-09 | Case              | L   | 0.794      | -            | -                | -                | -         |    -8.32 | card, fokiu, jz, stormzyn, t9rnay      |
|           41 |     2088 | 2024-07-06 | ODDIK             | L   | 0.774      | -            | -                | -                | -         |    -4.24 | card, fokiu, jz, stormzyn, t9rnay      |
|           40 |     2120 | 2024-06-27 | Bounty Hunters    | L   | 0.715      | -            | -                | -                | -         |    -8.23 | card, fokiu, jz, stormzyn, t9rnay      |
|           39 |     2340 | 2024-06-10 | ODDIK             | L   | 0.601      | -            | -                | -                | -         |    -3.63 | card, fokiu, jz, stormzyn, t9rnay      |
|           38 |     2382 | 2024-06-09 | Solid             | W   | 0.594      | 0.450        | -                | 0.692 (0.185)    | -         |    11.38 | card, fokiu, jz, stormzyn, t9rnay      |
|           37 |     2430 | 2024-06-08 | ODDIK             | L   | 0.590      | -            | -                | -                | -         |    -3.46 | card, fokiu, jz, stormzyn, t9rnay      |
|           36 |     2439 | 2024-06-08 | Bounty Hunters    | L   | 0.589      | -            | -                | -                | -         |    -6.94 | card, fokiu, jz, stormzyn, t9rnay      |
|           35 |     2522 | 2024-06-07 | Galorys           | W   | 0.580      | 0.450        | 0.019 (0.005)    | 0.372 (0.097)    | -         |    10.60 | card, fokiu, jz, stormzyn, t9rnay      |
|           34 |     2576 | 2024-06-06 | Fluxo             | L   | 0.574      | -            | -                | -                | -         |    -3.54 | card, fokiu, jz, stormzyn, t9rnay      |
|           33 |     2702 | 2024-06-03 | Vikings KR        | W   | 0.557      | 0.371        | -                | 0.439 (0.090)    | -         |     8.84 | card, fokiu, jz, stormzyn, t9rnay      |
|           32 |     2767 | 2024-06-01 | ex-Corinthians    | W   | 0.540      | -            | -                | -                | -         |     3.96 | card, fokiu, jz, stormzyn, t9rnay      |
|           31 |     2810 | 2024-05-30 | Hype              | L   | 0.530      | -            | -                | -                | -         |    -6.38 | card, fokiu, jz, stormzyn, t9rnay      |
|           30 |     2862 | 2024-05-28 | Yawara            | W   | 0.515      | -            | -                | -                | -         |     3.04 | card, fokiu, jz, stormzyn, t9rnay      |
|           29 |     2987 | 2024-05-22 | Solid             | L   | 0.476      | -            | -                | -                | -         |    -5.66 | card, fokiu, jz, stormzyn, t9rnay      |
|           28 |     2990 | 2024-05-22 | Solid             | L   | 0.476      | -            | -                | -                | -         |    -5.89 | card, fokiu, stormzyn, t9rnay, zede    |
|           27 |     3067 | 2024-05-20 | 9z                | L   | 0.463      | -            | -                | -                | -         |    -0.35 | card, fokiu, stormzyn, t9rnay, zede    |
|           26 |     3070 | 2024-05-20 | 9z                | L   | 0.463      | -            | -                | -                | -         |    -0.35 | card, fokiu, stormzyn, t9rnay, zede    |
|           25 |     3190 | 2024-05-16 | Sharks            | L   | 0.436      | -            | -                | -                | -         |    -2.29 | card, fokiu, stormzyn, t9rnay, zede    |
|           24 |     3193 | 2024-05-16 | Sharks            | L   | 0.436      | -            | -                | -                | -         |    -2.34 | card, fokiu, stormzyn, t9rnay, zede    |
|           23 |     3289 | 2024-05-14 | Imperial          | L   | 0.423      | -            | -                | -                | -         |    -1.85 | card, fokiu, stormzyn, t9rnay, zede    |
|           22 |     3292 | 2024-05-14 | Imperial          | L   | 0.423      | -            | -                | -                | -         |    -1.88 | card, fokiu, stormzyn, t9rnay, zede    |
|           21 |     3305 | 2024-05-14 | Hype              | L   | 0.422      | -            | -                | -                | -         |    -5.49 | card, fokiu, stormzyn, t9rnay, zede    |
|           20 |     3338 | 2024-05-13 | Sharks            | L   | 0.414      | -            | -                | -                | -         |    -2.41 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           19 |     3386 | 2024-05-11 | Sharks            | L   | 0.401      | -            | -                | -                | -         |    -2.38 | card, fokiu, stormzyn, t9rnay, zede    |
|           18 |     3437 | 2024-05-09 | KRÜ               | L   | 0.387      | -            | -                | -                | -         |    -4.61 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           17 |     3470 | 2024-05-07 | paiN              | L   | 0.375      | -            | -                | -                | -         |    -0.10 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           16 |     3490 | 2024-05-06 | paiN              | L   | 0.368      | -            | -                | -                | -         |    -0.10 | fokiu, jz, saadzin, stormzyn, zede     |
|           15 |     3491 | 2024-05-06 | paiN              | L   | 0.368      | -            | -                | -                | -         |    -0.10 | fokiu, jz, saadzin, stormzyn, zede     |
|           14 |     3513 | 2024-05-05 | Galorys           | W   | 0.360      | -            | -                | -                | -         |     5.06 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           13 |     3698 | 2024-04-26 | ODDIK             | L   | 0.302      | -            | -                | -                | -         |    -1.33 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           12 |     3699 | 2024-04-26 | ODDIK             | L   | 0.302      | -            | -                | -                | -         |    -1.35 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           11 |     3963 | 2024-04-17 | ODDIK             | L   | 0.242      | -            | -                | -                | -         |    -1.10 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           10 |     3999 | 2024-04-16 | Sharks            | W   | 0.236      | -            | -                | -                | -         |     3.11 | fokiu, saadzin, stormzyn, t9rnay, zede |
|            9 |     4066 | 2024-04-12 | RED Canids        | L   | 0.208      | -            | -                | -                | -         |    -1.65 | fokiu, saadzin, stormzyn, t9rnay, zede |
|            8 |     4175 | 2024-04-09 | RED Canids        | L   | 0.189      | -            | -                | -                | -         |    -1.53 | fokiu, jz, saadzin, stormzyn, zede     |
|            7 |     4180 | 2024-04-09 | RED Canids        | L   | 0.189      | -            | -                | -                | -         |    -1.55 | fokiu, jz, saadzin, stormzyn, zede     |
|            6 |     4213 | 2024-04-08 | MIBR              | L   | 0.183      | -            | -                | -                | -         |    -0.20 | fokiu, jz, saadzin, stormzyn, zede     |
|            5 |     4269 | 2024-04-06 | RED Canids        | W   | 0.168      | 0.435        | 0.049 (0.004)    | -                | -         |     3.94 | fokiu, jz, saadzin, stormzyn, zede     |
|            4 |     4486 | 2024-03-27 | BESTIA            | W   | 0.103      | 0.450        | 0.107 (0.005)    | -                | -         |     2.38 | fokiu, jz, saadzin, stormzyn, zede     |
|            3 |     4490 | 2024-03-27 | BESTIA            | L   | 0.103      | -            | -                | -                | -         |    -0.87 | fokiu, jz, saadzin, stormzyn, zede     |
|            2 |     4723 | 2024-03-14 | Galorys           | L   | 0.016      | -            | -                | -                | -         |    -0.29 | fokiu, jz, saadzin, stormzyn, zede     |
|            1 |     4725 | 2024-03-14 | Galorys           | L   | 0.016      | -            | -                | -                | -         |    -0.29 | fokiu, jz, saadzin, stormzyn, zede     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,887.32)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      0.881 | $1,000.00      | $881.39         |
| 2024-07-14 |      0.827 | $1,000.00      | $827.29         |
| 2024-06-09 |      0.595 | $300.00        | $178.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
