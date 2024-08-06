### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  810.5<br />
<br />
Final Rank Value (810.5) = Starting Rank Value (778.5) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.5
- 400 + ( ( 0.184 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 778.5


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
|           37 |      480 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.34 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      484 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.66 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      664 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |     8.72 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      669 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.31 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      782 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.218 (0.073)    | 0 (0.000) |     9.73 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      784 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.218 (0.073)    | 0 (0.000) |    10.51 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1297 | 2024-06-08 | FlyQuest           | L   | 0.812      | -            | -                | -                | -         |    -3.66 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1407 | 2024-06-07 | FlyQuest           | W   | 0.799      | 0.333        | 0.104 (0.028)    | 0.278 (0.074)    | 0 (0.000) |    21.93 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1478 | 2024-06-06 | Bad News Kangaroos | W   | 0.792      | 0.333        | 0.016 (0.004)    | 0.217 (0.057)    | 0 (0.000) |    11.95 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1882 | 2024-05-22 | Vantage            | W   | 0.693      | 0.333        | -                | 0.064 (0.015)    | 0 (0.000) |     6.01 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1887 | 2024-05-22 | Vantage            | W   | 0.692      | -            | -                | -                | 0 (0.000) |     6.32 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2140 | 2024-05-15 | Canon Event        | W   | 0.646      | -            | -                | -                | 0 (0.000) |     2.77 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2145 | 2024-05-15 | Canon Event        | W   | 0.646      | -            | -                | -                | 0 (0.000) |     2.85 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2333 | 2024-05-08 | KZG                | W   | 0.599      | 0.333        | 0.005 (0.001)    | 0.106 (0.021)    | -         |     5.89 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2336 | 2024-05-08 | KZG                | W   | 0.599      | 0.333        | 0.005 (0.001)    | 0.106 (0.021)    | -         |     6.17 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2567 | 2024-04-26 | MIBR               | L   | 0.525      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2589 | 2024-04-26 | KZG                | W   | 0.519      | 0.500        | 0.005 (0.001)    | 0.106 (0.028)    | 1 (0.519) |     5.58 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2592 | 2024-04-25 | Rebels             | L   | 0.518      | -            | -                | -                | -         |    -4.16 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2723 | 2024-04-19 | Bad News Kangaroos | L   | 0.478      | -            | -                | -                | -         |    -7.73 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2765 | 2024-04-19 | FlyQuest           | L   | 0.473      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2771 | 2024-04-18 | Bad News Kangaroos | W   | 0.472      | 0.143        | 0.016 (0.001)    | -                | -         |     7.24 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2847 | 2024-04-17 | Arcade             | W   | 0.460      | -            | -                | -                | -         |     4.71 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2851 | 2024-04-17 | Canon Event        | W   | 0.459      | -            | -                | -                | -         |     2.24 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3020 | 2024-04-10 | Bad News Kangaroos | L   | 0.413      | -            | -                | -                | -         |    -6.67 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3027 | 2024-04-10 | Bad News Kangaroos | W   | 0.412      | 0.333        | 0.016 (0.002)    | 0.217 (0.030)    | -         |     6.46 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3380 | 2024-03-27 | Arcade             | W   | 0.320      | -            | -                | -                | -         |     3.48 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3385 | 2024-03-27 | Arcade             | W   | 0.319      | -            | -                | -                | -         |     3.57 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3652 | 2024-03-13 | FlyQuest           | L   | 0.226      | -            | -                | -                | -         |    -0.81 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3660 | 2024-03-13 | FlyQuest           | L   | 0.226      | -            | -                | -                | -         |    -0.81 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3827 | 2024-03-06 | Mindfreak          | W   | 0.180      | -            | -                | -                | -         |     1.93 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3833 | 2024-03-06 | Mindfreak          | W   | 0.179      | -            | -                | -                | -         |     1.96 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4082 | 2024-02-23 | FlyQuest           | L   | 0.099      | -            | -                | -                | -         |    -0.35 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4084 | 2024-02-22 | Bad News Kangaroos | W   | 0.098      | -            | -                | -                | -         |     0.90 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4101 | 2024-02-22 | FlyQuest           | L   | 0.093      | -            | -                | -                | -         |    -0.33 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4104 | 2024-02-21 | Vantage            | W   | 0.091      | -            | -                | -                | -         |     0.96 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4131 | 2024-02-21 | DXA                | W   | 0.086      | -            | -                | -                | -         |     1.04 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4135 | 2024-02-21 | DXA                | W   | 0.086      | -            | -                | -                | -         |     1.05 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,220.51)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.812 | $2,000.00      | $1,623.15       |
| 2024-04-28 |      0.532 | $3,000.00      | $1,597.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
