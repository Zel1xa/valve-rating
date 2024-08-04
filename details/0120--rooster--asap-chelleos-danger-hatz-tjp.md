### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  805.0<br />
<br />
Final Rank Value (805.0) = Starting Rank Value (775.1) + Head To Head Adjustments (29.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.1
- 400 + ( ( 0.183 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 775.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      410 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.19 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      415 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.53 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      594 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     8.37 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      600 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.67 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      712 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.57 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      715 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.32 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1227 | 2024-06-08 | FlyQuest           | L   | 0.826      | -            | -                | -                | -         |    -3.58 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1337 | 2024-06-07 | FlyQuest           | W   | 0.813      | 0.333        | 0.104 (0.028)    | 0.290 (0.079)    | 0 (0.000) |    22.44 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1408 | 2024-06-06 | Bad News Kangaroos | W   | 0.806      | 0.333        | 0.003 (0.001)    | 0.146 (0.039)    | 0 (0.000) |     8.60 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1812 | 2024-05-22 | Vantage            | W   | 0.707      | 0.333        | -                | 0.070 (0.017)    | 0 (0.000) |     6.14 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1817 | 2024-05-22 | Vantage            | W   | 0.706      | 0.333        | -                | 0.070 (0.017)    | 0 (0.000) |     6.46 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2070 | 2024-05-15 | Canon Event        | W   | 0.660      | -            | -                | -                | 0 (0.000) |     2.83 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2075 | 2024-05-15 | Canon Event        | W   | 0.660      | -            | -                | -                | 0 (0.000) |     2.91 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2263 | 2024-05-08 | KZG                | W   | 0.613      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     6.03 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2266 | 2024-05-08 | KZG                | W   | 0.613      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     6.32 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2497 | 2024-04-26 | MIBR               | L   | 0.539      | -            | -                | -                | -         |    -0.45 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2519 | 2024-04-26 | KZG                | W   | 0.533      | 0.500        | 0.005 (0.001)    | 0.112 (0.030)    | 1 (0.533) |     5.75 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2522 | 2024-04-25 | Rebels             | L   | 0.532      | -            | -                | -                | -         |    -4.24 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2653 | 2024-04-19 | Bad News Kangaroos | L   | 0.492      | -            | -                | -                | -         |    -8.19 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2695 | 2024-04-19 | FlyQuest           | L   | 0.487      | -            | -                | -                | -         |    -1.72 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2701 | 2024-04-18 | Bad News Kangaroos | W   | 0.486      | 0.143        | 0.017 (0.001)    | -                | -         |     7.21 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2777 | 2024-04-17 | Arcade             | W   | 0.474      | -            | -                | -                | -         |     4.72 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2781 | 2024-04-17 | Canon Event        | W   | 0.473      | -            | -                | -                | -         |     2.31 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2950 | 2024-04-10 | Bad News Kangaroos | L   | 0.427      | -            | -                | -                | -         |    -7.12 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     2957 | 2024-04-10 | Bad News Kangaroos | W   | 0.426      | 0.333        | 0.017 (0.002)    | -                | -         |     6.45 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3310 | 2024-03-27 | Arcade             | W   | 0.334      | -            | -                | -                | -         |     3.53 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3315 | 2024-03-27 | Arcade             | W   | 0.333      | -            | -                | -                | -         |     3.62 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3582 | 2024-03-13 | FlyQuest           | L   | 0.240      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3590 | 2024-03-13 | FlyQuest           | L   | 0.240      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3757 | 2024-03-06 | Mindfreak          | W   | 0.194      | -            | -                | -                | -         |     2.09 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3763 | 2024-03-06 | Mindfreak          | W   | 0.193      | -            | -                | -                | -         |     2.12 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4012 | 2024-02-23 | FlyQuest           | L   | 0.113      | -            | -                | -                | -         |    -0.38 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4014 | 2024-02-22 | Bad News Kangaroos | W   | 0.112      | -            | -                | -                | -         |     1.68 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4031 | 2024-02-22 | FlyQuest           | L   | 0.107      | -            | -                | -                | -         |    -0.36 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4034 | 2024-02-21 | Vantage            | W   | 0.105      | -            | -                | -                | -         |     1.11 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4061 | 2024-02-21 | DXA                | W   | 0.100      | -            | -                | -                | -         |     1.19 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4065 | 2024-02-21 | DXA                | W   | 0.100      | -            | -                | -                | -         |     1.19 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,290.42)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.826 | $2,000.00      | $1,651.11       |
| 2024-04-28 |      0.546 | $3,000.00      | $1,639.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
