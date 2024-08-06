### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  810.4<br />
<br />
Final Rank Value (810.4) = Starting Rank Value (778.5) + Head To Head Adjustments (31.9)<br />

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
|           37 |      486 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.34 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      490 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.66 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      670 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |     8.72 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      675 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.30 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      788 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.218 (0.073)    | 0 (0.000) |     9.73 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      790 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.218 (0.073)    | 0 (0.000) |    10.51 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1303 | 2024-06-08 | FlyQuest           | L   | 0.811      | -            | -                | -                | -         |    -3.66 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1413 | 2024-06-07 | FlyQuest           | W   | 0.798      | 0.333        | 0.104 (0.028)    | 0.277 (0.074)    | 0 (0.000) |    21.91 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1484 | 2024-06-06 | Bad News Kangaroos | W   | 0.792      | 0.333        | 0.016 (0.004)    | 0.217 (0.057)    | 0 (0.000) |    11.95 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1888 | 2024-05-22 | Vantage            | W   | 0.692      | 0.333        | -                | 0.064 (0.015)    | 0 (0.000) |     6.01 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1893 | 2024-05-22 | Vantage            | W   | 0.692      | -            | -                | -                | 0 (0.000) |     6.31 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2146 | 2024-05-15 | Canon Event        | W   | 0.645      | -            | -                | -                | 0 (0.000) |     2.77 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2151 | 2024-05-15 | Canon Event        | W   | 0.645      | -            | -                | -                | 0 (0.000) |     2.85 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2339 | 2024-05-08 | KZG                | W   | 0.599      | 0.333        | 0.005 (0.001)    | 0.106 (0.021)    | -         |     5.89 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2342 | 2024-05-08 | KZG                | W   | 0.599      | 0.333        | 0.005 (0.001)    | 0.106 (0.021)    | -         |     6.17 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2573 | 2024-04-26 | MIBR               | L   | 0.524      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2595 | 2024-04-26 | KZG                | W   | 0.519      | 0.500        | 0.005 (0.001)    | 0.106 (0.028)    | 1 (0.519) |     5.58 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2598 | 2024-04-25 | Rebels             | L   | 0.517      | -            | -                | -                | -         |    -4.15 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2729 | 2024-04-19 | Bad News Kangaroos | L   | 0.478      | -            | -                | -                | -         |    -7.72 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2771 | 2024-04-19 | FlyQuest           | L   | 0.472      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2777 | 2024-04-18 | Bad News Kangaroos | W   | 0.471      | 0.143        | 0.016 (0.001)    | -                | -         |     7.23 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2853 | 2024-04-17 | Arcade             | W   | 0.459      | -            | -                | -                | -         |     4.71 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2857 | 2024-04-17 | Canon Event        | W   | 0.459      | -            | -                | -                | -         |     2.24 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3026 | 2024-04-10 | Bad News Kangaroos | L   | 0.412      | -            | -                | -                | -         |    -6.67 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3033 | 2024-04-10 | Bad News Kangaroos | W   | 0.412      | 0.333        | 0.016 (0.002)    | 0.217 (0.030)    | -         |     6.45 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3386 | 2024-03-27 | Arcade             | W   | 0.319      | -            | -                | -                | -         |     3.48 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3391 | 2024-03-27 | Arcade             | W   | 0.319      | -            | -                | -                | -         |     3.57 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3658 | 2024-03-13 | FlyQuest           | L   | 0.226      | -            | -                | -                | -         |    -0.81 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3666 | 2024-03-13 | FlyQuest           | L   | 0.225      | -            | -                | -                | -         |    -0.81 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3833 | 2024-03-06 | Mindfreak          | W   | 0.179      | -            | -                | -                | -         |     1.93 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3839 | 2024-03-06 | Mindfreak          | W   | 0.179      | -            | -                | -                | -         |     1.95 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4088 | 2024-02-23 | FlyQuest           | L   | 0.099      | -            | -                | -                | -         |    -0.35 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4090 | 2024-02-22 | Bad News Kangaroos | W   | 0.098      | -            | -                | -                | -         |     0.90 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4107 | 2024-02-22 | FlyQuest           | L   | 0.092      | -            | -                | -                | -         |    -0.33 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4110 | 2024-02-21 | Vantage            | W   | 0.091      | -            | -                | -                | -         |     0.95 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4137 | 2024-02-21 | DXA                | W   | 0.086      | -            | -                | -                | -         |     1.03 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4141 | 2024-02-21 | DXA                | W   | 0.085      | -            | -                | -                | -         |     1.04 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,217.73)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.811 | $2,000.00      | $1,622.04       |
| 2024-04-28 |      0.532 | $3,000.00      | $1,595.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
