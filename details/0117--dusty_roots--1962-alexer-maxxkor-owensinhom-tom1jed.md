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
Final Rank Value (825.5) = Starting Rank Value (850.8) + Head To Head Adjustments (-25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.129[<sup>2</sup>](#table1)
- LAN Wins: 0.092[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.8
- 400 + ( ( 0.220 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 850.8


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
|           36 |       57 | 2024-08-02 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -15.25 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           35 |       93 | 2024-08-01 | Bounty Hunters    | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.557 (0.080)    | 0 (0.000) |    19.98 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           34 |      100 | 2024-08-01 | W7M               | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.537 (0.077)    | 0 (0.000) |    15.75 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           33 |      160 | 2024-07-31 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.61 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           32 |      166 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           31 |      188 | 2024-07-30 | MIBR              | W   | 1.000      | 0.450        | 0.209 (0.094)    | 0.659 (0.297)    | 0 (0.000) |    30.06 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           30 |      191 | 2024-07-30 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           29 |      204 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -6.02 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           28 |      425 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.40 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           27 |      436 | 2024-07-23 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.489 (0.181)    | 0 (0.000) |    20.11 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           26 |      482 | 2024-07-21 | 9z Academy        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.070 (0.026)    | 0 (0.000) |     5.82 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           25 |      542 | 2024-07-19 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.63 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           24 |      585 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.28 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           23 |      587 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.29 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           22 |      647 | 2024-07-17 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.552 (0.248)    | 0 (0.000) |    17.98 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           21 |      650 | 2024-07-17 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -13.33 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           20 |      676 | 2024-07-17 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -5.71 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           19 |      712 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.03 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           18 |      717 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.37 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           17 |      722 | 2024-07-16 | KRÜ               | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.493 (0.183)    | 0 (0.000) |    19.59 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           16 |      760 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.69 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           15 |      765 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.83 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           14 |      815 | 2024-07-13 | Case              | L   | 1.000      | -            | -                | -                | -         |   -12.40 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           13 |      839 | 2024-07-11 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.87 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           12 |      949 | 2024-06-28 | Vikings KR        | L   | 0.953      | -            | -                | -                | -         |   -15.67 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           11 |      960 | 2024-06-26 | Patins da Ferrari | L   | 0.940      | -            | -                | -                | -         |   -14.66 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           10 |      980 | 2024-06-17 | inSanitY          | L   | 0.882      | -            | -                | -                | -         |    -8.88 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            9 |     1295 | 2024-06-08 | paiN              | L   | 0.819      | -            | -                | -                | -         |    -1.56 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            8 |     1396 | 2024-06-06 | Vikings KR        | W   | 0.807      | 0.371        | 0.008 (0.002)    | 0.506 (0.151)    | 0 (0.000) |    10.74 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            7 |     1455 | 2024-06-05 | LA RUGONETA       | W   | 0.801      | 0.284        | 0.002 (0.001)    | -                | 1 (0.801) |     4.00 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            6 |     1557 | 2024-06-02 | 9z Academy        | W   | 0.781      | 0.371        | 0.000 (0.000)    | 0.070 (0.020)    | 0 (0.000) |     3.37 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            5 |     1626 | 2024-05-31 | FURIA Academy     | W   | 0.767      | 0.371        | -                | 0.105 (0.030)    | -         |     3.74 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            4 |     1671 | 2024-05-29 | Case              | L   | 0.754      | -            | -                | -                | -         |    -9.43 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            3 |     1730 | 2024-05-27 | Galorys           | L   | 0.739      | -            | -                | -                | -         |    -9.83 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            2 |     4208 | 2024-02-16 | FURIA Academy     | L   | 0.067      | -            | -                | -                | -         |    -1.83 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |
|            1 |     4325 | 2024-02-12 | Case              | L   | 0.040      | -            | -                | -                | -         |    -0.48 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,089.54)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-19 |      0.894 | $545.00        | $487.41         |
| 2024-06-05 |      0.801 | $2,000.00      | $1,602.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
