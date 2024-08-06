### Roster Details<br />
Team Name: Dusty Roots<br />
Roster: 1962, alexer, maxxkor, OwensinhoM, tom1jed<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
<br />
Final Rank Value:  825.2<br />
<br />
Final Rank Value (825.2) = Starting Rank Value (850.9) + Head To Head Adjustments (-25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.127[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.9
- 400 + ( ( 0.220 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 850.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       85 | 2024-08-02 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -15.27 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           35 |      121 | 2024-08-01 | Bounty Hunters    | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.552 (0.079)    | 0 (0.000) |    19.94 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           34 |      128 | 2024-08-01 | W7M               | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.531 (0.076)    | 0 (0.000) |    15.73 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           33 |      188 | 2024-07-31 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.63 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           32 |      194 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           31 |      216 | 2024-07-30 | MIBR              | W   | 1.000      | 0.450        | 0.208 (0.094)    | 0.648 (0.292)    | 0 (0.000) |    30.04 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           30 |      219 | 2024-07-30 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.27 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           29 |      232 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -6.05 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           28 |      453 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.44 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           27 |      464 | 2024-07-23 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.485 (0.180)    | 0 (0.000) |    20.08 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           26 |      510 | 2024-07-21 | 9z Academy        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.069 (0.025)    | 0 (0.000) |     5.83 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           25 |      570 | 2024-07-19 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.65 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           24 |      613 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.30 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           23 |      615 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.31 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           22 |      675 | 2024-07-17 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.543 (0.244)    | 0 (0.000) |    17.96 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           21 |      678 | 2024-07-17 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -13.35 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           20 |      704 | 2024-07-17 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -5.76 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           19 |      740 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.08 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           18 |      745 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.44 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           17 |      750 | 2024-07-16 | KRÜ               | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.488 (0.181)    | 0 (0.000) |    19.55 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           16 |      788 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.74 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           15 |      793 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.88 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           14 |      843 | 2024-07-13 | Case              | L   | 1.000      | -            | -                | -                | -         |   -12.43 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           13 |      867 | 2024-07-11 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.91 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           12 |      977 | 2024-06-28 | Vikings KR        | L   | 0.944      | -            | -                | -                | -         |   -15.56 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           11 |      988 | 2024-06-26 | Patins da Ferrari | L   | 0.931      | -            | -                | -                | -         |   -14.57 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           10 |     1008 | 2024-06-17 | inSanitY          | L   | 0.873      | -            | -                | -                | -         |    -8.86 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            9 |     1323 | 2024-06-08 | paiN              | L   | 0.810      | -            | -                | -                | -         |    -1.57 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            8 |     1424 | 2024-06-06 | Vikings KR        | W   | 0.798      | 0.371        | 0.008 (0.002)    | 0.500 (0.148)    | 0 (0.000) |    10.60 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            7 |     1483 | 2024-06-05 | LA RUGONETA       | W   | 0.792      | 0.284        | 0.002 (0.001)    | -                | 1 (0.792) |     3.96 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            6 |     1585 | 2024-06-02 | 9z Academy        | W   | 0.772      | 0.371        | 0.000 (0.000)    | 0.069 (0.020)    | 0 (0.000) |     3.33 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            5 |     1654 | 2024-05-31 | FURIA Academy     | W   | 0.758      | 0.371        | -                | 0.104 (0.029)    | -         |     3.68 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            4 |     1699 | 2024-05-29 | Case              | L   | 0.745      | -            | -                | -                | -         |    -9.36 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            3 |     1758 | 2024-05-27 | Galorys           | L   | 0.730      | -            | -                | -                | -         |    -9.74 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            2 |     4236 | 2024-02-16 | FURIA Academy     | L   | 0.058      | -            | -                | -                | -         |    -1.58 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |
|            1 |     4353 | 2024-02-12 | Case              | L   | 0.031      | -            | -                | -                | -         |    -0.37 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,066.50)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-19 |      0.885 | $545.00        | $482.48         |
| 2024-06-05 |      0.792 | $2,000.00      | $1,584.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
