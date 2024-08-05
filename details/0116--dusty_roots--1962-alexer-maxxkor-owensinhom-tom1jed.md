### Roster Details<br />
Team Name: Dusty Roots<br />
Roster: 1962, alexer, maxxkor, OwensinhoM, tom1jed<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
<br />
Final Rank Value:  825.6<br />
<br />
Final Rank Value (825.6) = Starting Rank Value (851.0) + Head To Head Adjustments (-25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.129[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 851.0
- 400 + ( ( 0.220 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 851.0


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
|           36 |       74 | 2024-08-02 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -15.26 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           35 |      110 | 2024-08-01 | Bounty Hunters    | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.558 (0.080)    | 0 (0.000) |    19.96 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           34 |      117 | 2024-08-01 | W7M               | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.537 (0.077)    | 0 (0.000) |    15.74 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           33 |      177 | 2024-07-31 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.62 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           32 |      183 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.24 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           31 |      205 | 2024-07-30 | MIBR              | W   | 1.000      | 0.450        | 0.208 (0.094)    | 0.657 (0.296)    | 0 (0.000) |    30.05 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           30 |      208 | 2024-07-30 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.26 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           29 |      221 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -6.04 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           28 |      442 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.42 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           27 |      453 | 2024-07-23 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.490 (0.182)    | 0 (0.000) |    20.10 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           26 |      499 | 2024-07-21 | 9z Academy        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.070 (0.026)    | 0 (0.000) |     5.82 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           25 |      559 | 2024-07-19 | Case              | L   | 1.000      | -            | -                | -                | -         |   -10.64 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           24 |      602 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.29 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           23 |      604 | 2024-07-18 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.31 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           22 |      664 | 2024-07-17 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.550 (0.247)    | 0 (0.000) |    17.97 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           21 |      667 | 2024-07-17 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -13.33 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           20 |      693 | 2024-07-17 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -5.74 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           19 |      729 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.06 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           18 |      734 | 2024-07-16 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -6.41 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           17 |      739 | 2024-07-16 | KRÜ               | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.493 (0.183)    | 0 (0.000) |    19.57 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           16 |      777 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.72 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           15 |      782 | 2024-07-15 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.86 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           14 |      832 | 2024-07-13 | Case              | L   | 1.000      | -            | -                | -                | -         |   -12.41 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           13 |      856 | 2024-07-11 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.88 | 1962, alexer, maxxkor, OwensinhoM, tom1jed |
|           12 |      966 | 2024-06-28 | Vikings KR        | L   | 0.948      | -            | -                | -                | -         |   -15.59 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           11 |      977 | 2024-06-26 | Patins da Ferrari | L   | 0.934      | -            | -                | -                | -         |   -14.60 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|           10 |      997 | 2024-06-17 | inSanitY          | L   | 0.876      | -            | -                | -                | -         |    -8.86 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            9 |     1312 | 2024-06-08 | paiN              | L   | 0.814      | -            | -                | -                | -         |    -1.56 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            8 |     1413 | 2024-06-06 | Vikings KR        | W   | 0.802      | 0.371        | 0.008 (0.002)    | 0.506 (0.150)    | 0 (0.000) |    10.66 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            7 |     1472 | 2024-06-05 | LA RUGONETA       | W   | 0.795      | 0.284        | 0.002 (0.001)    | -                | 1 (0.795) |     3.97 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            6 |     1574 | 2024-06-02 | 9z Academy        | W   | 0.775      | 0.371        | 0.000 (0.000)    | 0.070 (0.020)    | 0 (0.000) |     3.34 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            5 |     1643 | 2024-05-31 | FURIA Academy     | W   | 0.761      | 0.371        | -                | 0.105 (0.030)    | -         |     3.70 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            4 |     1688 | 2024-05-29 | Case              | L   | 0.749      | -            | -                | -                | -         |    -9.38 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            3 |     1747 | 2024-05-27 | Galorys           | L   | 0.734      | -            | -                | -                | -         |    -9.76 | alexer, maxxkor, OwensinhoM, tom1jed, zock |
|            2 |     4225 | 2024-02-16 | FURIA Academy     | L   | 0.061      | -            | -                | -                | -         |    -1.68 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |
|            1 |     4342 | 2024-02-12 | Case              | L   | 0.034      | -            | -                | -                | -         |    -0.41 | alexer, guishu, KvNs, maxxkor, OwensinhoM  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,074.99)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-19 |      0.889 | $545.00        | $484.29         |
| 2024-06-05 |      0.795 | $2,000.00      | $1,590.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
