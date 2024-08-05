### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  814.0<br />
<br />
Final Rank Value (814.0) = Starting Rank Value (781.8) + Head To Head Adjustments (32.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.8
- 400 + ( ( 0.185 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 781.8


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
|           37 |      293 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.40 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      297 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.71 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      477 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |     8.14 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      482 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.91 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      595 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.45 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      597 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.19 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1110 | 2024-06-08 | FlyQuest           | L   | 0.849      | -            | -                | -                | -         |    -3.48 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1220 | 2024-06-07 | FlyQuest           | W   | 0.837      | 0.333        | 0.105 (0.029)    | 0.298 (0.083)    | 0 (0.000) |    23.29 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1291 | 2024-06-06 | Bad News Kangaroos | W   | 0.830      | 0.333        | 0.003 (0.001)    | 0.143 (0.040)    | 0 (0.000) |     8.71 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1695 | 2024-05-22 | Vantage            | W   | 0.730      | 0.333        | -                | 0.076 (0.018)    | 0 (0.000) |     6.21 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1700 | 2024-05-22 | Vantage            | W   | 0.730      | 0.333        | -                | 0.076 (0.018)    | 0 (0.000) |     6.54 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     1953 | 2024-05-15 | Canon Event        | W   | 0.684      | -            | -                | -                | 0 (0.000) |     2.79 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     1958 | 2024-05-15 | Canon Event        | W   | 0.684      | -            | -                | -                | 0 (0.000) |     2.87 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2146 | 2024-05-08 | KZG                | W   | 0.637      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.11 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2149 | 2024-05-08 | KZG                | W   | 0.637      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.41 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2380 | 2024-04-26 | MIBR               | L   | 0.562      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2402 | 2024-04-26 | KZG                | W   | 0.557      | 0.500        | 0.006 (0.002)    | 0.113 (0.032)    | 1 (0.557) |     5.87 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2405 | 2024-04-25 | Rebels             | L   | 0.556      | -            | -                | -                | -         |    -4.44 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2536 | 2024-04-19 | Bad News Kangaroos | L   | 0.516      | -            | -                | -                | -         |    -8.55 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2578 | 2024-04-19 | FlyQuest           | L   | 0.511      | -            | -                | -                | -         |    -1.65 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2584 | 2024-04-18 | Bad News Kangaroos | W   | 0.509      | 0.143        | 0.017 (0.001)    | -                | -         |     7.59 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2660 | 2024-04-17 | Arcade             | W   | 0.497      | -            | -                | -                | -         |     4.88 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2664 | 2024-04-17 | Canon Event        | W   | 0.497      | -            | -                | -                | -         |     2.31 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2833 | 2024-04-10 | Bad News Kangaroos | L   | 0.450      | -            | -                | -                | -         |    -7.49 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     2840 | 2024-04-10 | Bad News Kangaroos | W   | 0.450      | 0.333        | 0.017 (0.003)    | -                | -         |     6.84 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3193 | 2024-03-27 | Arcade             | W   | 0.357      | -            | -                | -                | -         |     3.73 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3198 | 2024-03-27 | Arcade             | W   | 0.357      | -            | -                | -                | -         |     3.84 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3465 | 2024-03-13 | FlyQuest           | L   | 0.264      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3473 | 2024-03-13 | FlyQuest           | L   | 0.264      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3640 | 2024-03-06 | Mindfreak          | W   | 0.217      | -            | -                | -                | -         |     2.32 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3646 | 2024-03-06 | Mindfreak          | W   | 0.217      | -            | -                | -                | -         |     2.36 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     3895 | 2024-02-23 | FlyQuest           | L   | 0.137      | -            | -                | -                | -         |    -0.42 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     3897 | 2024-02-22 | Bad News Kangaroos | W   | 0.136      | -            | -                | -                | -         |     2.05 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     3914 | 2024-02-22 | FlyQuest           | L   | 0.130      | -            | -                | -                | -         |    -0.40 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     3917 | 2024-02-21 | Vantage            | W   | 0.129      | -            | -                | -                | -         |     1.35 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     3944 | 2024-02-21 | DXA                | W   | 0.124      | -            | -                | -                | -         |     1.45 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     3948 | 2024-02-21 | DXA                | W   | 0.124      | -            | -                | -                | -         |     1.47 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,409.33)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.849 | $2,000.00      | $1,698.68       |
| 2024-04-28 |      0.570 | $3,000.00      | $1,710.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
