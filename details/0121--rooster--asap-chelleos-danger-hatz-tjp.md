### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  811.7<br />
<br />
Final Rank Value (811.7) = Starting Rank Value (778.6) + Head To Head Adjustments (33.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.6
- 400 + ( ( 0.185 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 778.6


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
|           37 |      446 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.38 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      450 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.70 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      630 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |     8.63 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      635 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.40 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      748 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.70 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      750 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.47 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1263 | 2024-06-08 | FlyQuest           | L   | 0.821      | -            | -                | -                | -         |    -3.64 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1373 | 2024-06-07 | FlyQuest           | W   | 0.809      | 0.333        | 0.104 (0.028)    | 0.293 (0.079)    | 0 (0.000) |    22.25 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1444 | 2024-06-06 | Bad News Kangaroos | W   | 0.802      | 0.333        | 0.017 (0.004)    | 0.226 (0.060)    | 0 (0.000) |    12.11 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1848 | 2024-05-22 | Vantage            | W   | 0.702      | 0.333        | -                | 0.069 (0.016)    | 0 (0.000) |     6.05 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1853 | 2024-05-22 | Vantage            | W   | 0.702      | -            | -                | -                | 0 (0.000) |     6.36 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2106 | 2024-05-15 | Canon Event        | W   | 0.656      | -            | -                | -                | 0 (0.000) |     2.78 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2111 | 2024-05-15 | Canon Event        | W   | 0.656      | -            | -                | -                | 0 (0.000) |     2.86 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2299 | 2024-05-08 | KZG                | W   | 0.609      | 0.333        | 0.005 (0.001)    | 0.111 (0.023)    | -         |     5.94 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2302 | 2024-05-08 | KZG                | W   | 0.609      | 0.333        | 0.005 (0.001)    | 0.111 (0.023)    | -         |     6.22 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2533 | 2024-04-26 | MIBR               | L   | 0.535      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2555 | 2024-04-26 | KZG                | W   | 0.529      | 0.500        | 0.005 (0.001)    | 0.111 (0.029)    | 1 (0.529) |     5.64 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2558 | 2024-04-25 | Rebels             | L   | 0.528      | -            | -                | -                | -         |    -4.26 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2689 | 2024-04-19 | Bad News Kangaroos | L   | 0.488      | -            | -                | -                | -         |    -7.88 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2731 | 2024-04-19 | FlyQuest           | L   | 0.483      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2737 | 2024-04-18 | Bad News Kangaroos | W   | 0.482      | 0.143        | 0.017 (0.001)    | -                | -         |     7.39 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2813 | 2024-04-17 | Arcade             | W   | 0.469      | -            | -                | -                | -         |     4.79 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2817 | 2024-04-17 | Canon Event        | W   | 0.469      | -            | -                | -                | -         |     2.26 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2986 | 2024-04-10 | Bad News Kangaroos | L   | 0.422      | -            | -                | -                | -         |    -6.82 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     2993 | 2024-04-10 | Bad News Kangaroos | W   | 0.422      | 0.333        | 0.017 (0.002)    | 0.226 (0.032)    | -         |     6.62 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3346 | 2024-03-27 | Arcade             | W   | 0.329      | -            | -                | -                | -         |     3.58 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3351 | 2024-03-27 | Arcade             | W   | 0.329      | -            | -                | -                | -         |     3.67 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3618 | 2024-03-13 | FlyQuest           | L   | 0.236      | -            | -                | -                | -         |    -0.82 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3626 | 2024-03-13 | FlyQuest           | L   | 0.236      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3793 | 2024-03-06 | Mindfreak          | W   | 0.189      | -            | -                | -                | -         |     2.03 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3799 | 2024-03-06 | Mindfreak          | W   | 0.189      | -            | -                | -                | -         |     2.06 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4048 | 2024-02-23 | FlyQuest           | L   | 0.109      | -            | -                | -                | -         |    -0.38 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4050 | 2024-02-22 | Bad News Kangaroos | W   | 0.108      | -            | -                | -                | -         |     0.99 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4067 | 2024-02-22 | FlyQuest           | L   | 0.102      | -            | -                | -                | -         |    -0.35 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4070 | 2024-02-21 | Vantage            | W   | 0.101      | -            | -                | -                | -         |     1.05 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4097 | 2024-02-21 | DXA                | W   | 0.096      | -            | -                | -                | -         |     1.16 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4101 | 2024-02-21 | DXA                | W   | 0.096      | -            | -                | -                | -         |     1.16 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,269.58)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.821 | $2,000.00      | $1,642.78       |
| 2024-04-28 |      0.542 | $3,000.00      | $1,626.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
