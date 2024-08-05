### Roster Details<br />
Team Name: Dusty Roots<br />
Roster: 1962, alexer, maxxkor, OwensinhoM, tom1jed<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
<br />
Final Rank Value:  825.5<br />
<br />
Final Rank Value (825.5) = Starting Rank Value (850.9) + Head To Head Adjustments (-25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.129[<sup>2</sup>](#table1)
- LAN Wins: 0.092[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.9
- 400 + ( ( 0.220 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 850.9


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
|           36 |       61 | 2024-08-02 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -15.25 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           35 |       97 | 2024-08-01 | Bounty Hunters    | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.558 (0.080)    | 0 (0.000) |    19.97 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           34 |      104 | 2024-08-01 | W7M               | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.538 (0.077)    | 0 (0.000) |    15.75 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           33 |      164 | 2024-07-31 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.61 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           32 |      170 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           31 |      192 | 2024-07-30 | MIBR              | W   | 1.000      | 0.450        | 0.209 (0.094)    | 0.659 (0.297)    | 0 (0.000) |    30.05 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           30 |      195 | 2024-07-30 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           29 |      208 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -6.03 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           28 |      429 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.41 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           27 |      440 | 2024-07-23 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.490 (0.182)    | 0 (0.000) |    20.11 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           26 |      486 | 2024-07-21 | 9z Academy        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.070 (0.026)    | 0 (0.000) |     5.82 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           25 |      546 | 2024-07-19 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.63 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           24 |      589 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.28 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           23 |      591 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.30 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           22 |      651 | 2024-07-17 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.552 (0.248)    | 0 (0.000) |    17.97 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           21 |      654 | 2024-07-17 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -13.33 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           20 |      680 | 2024-07-17 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -5.72 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           19 |      716 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.04 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           18 |      721 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.38 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           17 |      726 | 2024-07-16 | KRÜ               | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.494 (0.183)    | 0 (0.000) |    19.58 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           16 |      764 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.70 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           15 |      769 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.84 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           14 |      819 | 2024-07-13 | Case              | L   | 1.000      | -            | -                | -                | -         |   -12.40 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           13 |      843 | 2024-07-11 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.87 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           12 |      953 | 2024-06-28 | Vikings KR        | L   | 0.951      | -            | -                | -                | -         |   -15.64 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           11 |      964 | 2024-06-26 | Patins da Ferrari | L   | 0.938      | -            | -                | -                | -         |   -14.63 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           10 |      984 | 2024-06-17 | inSanitY          | L   | 0.880      | -            | -                | -                | -         |    -8.87 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            9 |     1299 | 2024-06-08 | paiN              | L   | 0.817      | -            | -                | -                | -         |    -1.56 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            8 |     1400 | 2024-06-06 | Vikings KR        | W   | 0.805      | 0.371        | 0.008 (0.002)    | 0.507 (0.151)    | 0 (0.000) |    10.71 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            7 |     1459 | 2024-06-05 | LA RUGONETA       | W   | 0.799      | 0.284        | 0.002 (0.001)    | -                | 1 (0.799) |     3.99 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            6 |     1561 | 2024-06-02 | 9z Academy        | W   | 0.779      | 0.371        | 0.000 (0.000)    | 0.070 (0.020)    | 0 (0.000) |     3.35 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            5 |     1630 | 2024-05-31 | FURIA Academy     | W   | 0.765      | 0.371        | -                | 0.105 (0.030)    | -         |     3.72 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            4 |     1675 | 2024-05-29 | Case              | L   | 0.752      | -            | -                | -                | -         |    -9.41 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            3 |     1734 | 2024-05-27 | Galorys           | L   | 0.737      | -            | -                | -                | -         |    -9.80 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            2 |     4212 | 2024-02-16 | FURIA Academy     | L   | 0.064      | -            | -                | -                | -         |    -1.77 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |
|            1 |     4329 | 2024-02-12 | Case              | L   | 0.038      | -            | -                | -                | -         |    -0.45 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,083.47)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-19 |      0.892 | $545.00        | $486.11         |
| 2024-06-05 |      0.799 | $2,000.00      | $1,597.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
