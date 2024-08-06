### Roster Details<br />
Team Name: Dusty Roots<br />
Roster: 1962, alexer, maxxkor, OwensinhoM, tom1jed<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
<br />
Final Rank Value:  824.5<br />
<br />
Final Rank Value (824.5) = Starting Rank Value (850.6) + Head To Head Adjustments (-26.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.125[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.6
- 400 + ( ( 0.219 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 850.6


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
|           36 |      102 | 2024-08-02 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -15.29 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           35 |      138 | 2024-08-01 | Bounty Hunters    | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.540 (0.077)    | 0 (0.000) |    19.91 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           34 |      145 | 2024-08-01 | W7M               | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.519 (0.074)    | 0 (0.000) |    15.72 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           33 |      205 | 2024-07-31 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.64 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           32 |      211 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           31 |      233 | 2024-07-30 | MIBR              | W   | 1.000      | 0.450        | 0.208 (0.093)    | 0.633 (0.285)    | 0 (0.000) |    30.03 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           30 |      236 | 2024-07-30 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.27 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           29 |      249 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -6.07 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           28 |      470 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.46 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           27 |      481 | 2024-07-23 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.476 (0.176)    | 0 (0.000) |    20.06 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           26 |      527 | 2024-07-21 | 9z Academy        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.067 (0.025)    | 0 (0.000) |     5.85 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           25 |      587 | 2024-07-19 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.67 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           24 |      630 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.31 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           23 |      632 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.32 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           22 |      692 | 2024-07-17 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.530 (0.239)    | 0 (0.000) |    17.94 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           21 |      695 | 2024-07-17 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -13.37 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           20 |      721 | 2024-07-17 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -5.80 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           19 |      757 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.12 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           18 |      762 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.48 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           17 |      767 | 2024-07-16 | KRÜ               | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.479 (0.177)    | 0 (0.000) |    19.50 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           16 |      805 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.77 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           15 |      810 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.92 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           14 |      860 | 2024-07-13 | Case              | L   | 1.000      | -            | -                | -                | -         |   -12.46 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           13 |      884 | 2024-07-11 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.95 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           12 |      994 | 2024-06-28 | Vikings KR        | L   | 0.941      | -            | -                | -                | -         |   -15.53 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           11 |     1005 | 2024-06-26 | Patins da Ferrari | L   | 0.927      | -            | -                | -                | -         |   -14.52 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           10 |     1025 | 2024-06-17 | inSanitY          | L   | 0.869      | -            | -                | -                | -         |    -8.88 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            9 |     1340 | 2024-06-08 | paiN              | L   | 0.807      | -            | -                | -                | -         |    -1.58 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            8 |     1441 | 2024-06-06 | Vikings KR        | W   | 0.794      | 0.371        | 0.008 (0.002)    | 0.490 (0.144)    | 0 (0.000) |    10.53 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            7 |     1500 | 2024-06-05 | LA RUGONETA       | W   | 0.788      | 0.284        | 0.002 (0.001)    | -                | 1 (0.788) |     3.95 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            6 |     1602 | 2024-06-02 | 9z Academy        | W   | 0.768      | 0.371        | 0.000 (0.000)    | 0.067 (0.019)    | 0 (0.000) |     3.32 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            5 |     1671 | 2024-05-31 | FURIA Academy     | W   | 0.754      | 0.371        | -                | 0.102 (0.029)    | -         |     3.67 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            4 |     1716 | 2024-05-29 | Case              | L   | 0.742      | -            | -                | -                | -         |    -9.35 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            3 |     1775 | 2024-05-27 | Galorys           | L   | 0.727      | -            | -                | -                | -         |    -9.72 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            2 |     4253 | 2024-02-16 | FURIA Academy     | L   | 0.054      | -            | -                | -                | -         |    -1.48 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |
|            1 |     4370 | 2024-02-12 | Case              | L   | 0.027      | -            | -                | -                | -         |    -0.33 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,056.61)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-19 |      0.881 | $545.00        | $480.36         |
| 2024-06-05 |      0.788 | $2,000.00      | $1,576.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
