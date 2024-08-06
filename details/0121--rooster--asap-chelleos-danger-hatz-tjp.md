### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  810.3<br />
<br />
Final Rank Value (810.3) = Starting Rank Value (778.2) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.2
- 400 + ( ( 0.184 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 778.2


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
|           37 |      474 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.34 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      478 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.66 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      658 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |     8.71 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      663 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.32 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      776 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.223 (0.074)    | 0 (0.000) |     9.73 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      778 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.223 (0.074)    | 0 (0.000) |    10.50 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1291 | 2024-06-08 | FlyQuest           | L   | 0.812      | -            | -                | -                | -         |    -3.65 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1401 | 2024-06-07 | FlyQuest           | W   | 0.799      | 0.333        | 0.104 (0.028)    | 0.284 (0.076)    | 0 (0.000) |    21.95 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1472 | 2024-06-06 | Bad News Kangaroos | W   | 0.793      | 0.333        | 0.016 (0.004)    | 0.222 (0.059)    | 0 (0.000) |    11.96 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1876 | 2024-05-22 | Vantage            | W   | 0.693      | 0.333        | -                | 0.066 (0.015)    | 0 (0.000) |     6.01 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1881 | 2024-05-22 | Vantage            | W   | 0.693      | -            | -                | -                | 0 (0.000) |     6.32 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2134 | 2024-05-15 | Canon Event        | W   | 0.647      | -            | -                | -                | 0 (0.000) |     2.78 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2139 | 2024-05-15 | Canon Event        | W   | 0.646      | -            | -                | -                | 0 (0.000) |     2.85 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2327 | 2024-05-08 | KZG                | W   | 0.600      | 0.333        | 0.005 (0.001)    | 0.109 (0.022)    | -         |     5.90 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2330 | 2024-05-08 | KZG                | W   | 0.600      | 0.333        | 0.005 (0.001)    | 0.109 (0.022)    | -         |     6.17 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2561 | 2024-04-26 | MIBR               | L   | 0.525      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2583 | 2024-04-26 | KZG                | W   | 0.520      | 0.500        | 0.005 (0.001)    | 0.109 (0.028)    | 1 (0.520) |     5.58 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2586 | 2024-04-25 | Rebels             | L   | 0.518      | -            | -                | -                | -         |    -4.16 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2717 | 2024-04-19 | Bad News Kangaroos | L   | 0.479      | -            | -                | -                | -         |    -7.74 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2759 | 2024-04-19 | FlyQuest           | L   | 0.473      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2765 | 2024-04-18 | Bad News Kangaroos | W   | 0.472      | 0.143        | 0.016 (0.001)    | -                | -         |     7.24 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2841 | 2024-04-17 | Arcade             | W   | 0.460      | -            | -                | -                | -         |     4.71 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2845 | 2024-04-17 | Canon Event        | W   | 0.460      | -            | -                | -                | -         |     2.24 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3014 | 2024-04-10 | Bad News Kangaroos | L   | 0.413      | -            | -                | -                | -         |    -6.69 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3021 | 2024-04-10 | Bad News Kangaroos | W   | 0.413      | 0.333        | 0.016 (0.002)    | 0.222 (0.031)    | -         |     6.47 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3374 | 2024-03-27 | Arcade             | W   | 0.320      | -            | -                | -                | -         |     3.49 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3379 | 2024-03-27 | Arcade             | W   | 0.320      | -            | -                | -                | -         |     3.58 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3646 | 2024-03-13 | FlyQuest           | L   | 0.227      | -            | -                | -                | -         |    -0.81 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3654 | 2024-03-13 | FlyQuest           | L   | 0.227      | -            | -                | -                | -         |    -0.81 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3821 | 2024-03-06 | Mindfreak          | W   | 0.180      | -            | -                | -                | -         |     1.94 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3827 | 2024-03-06 | Mindfreak          | W   | 0.180      | -            | -                | -                | -         |     1.97 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4076 | 2024-02-23 | FlyQuest           | L   | 0.100      | -            | -                | -                | -         |    -0.35 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4078 | 2024-02-22 | Bad News Kangaroos | W   | 0.099      | -            | -                | -                | -         |     0.91 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4095 | 2024-02-22 | FlyQuest           | L   | 0.093      | -            | -                | -                | -         |    -0.33 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4098 | 2024-02-21 | Vantage            | W   | 0.092      | -            | -                | -                | -         |     0.96 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4125 | 2024-02-21 | DXA                | W   | 0.087      | -            | -                | -                | -         |     1.05 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4129 | 2024-02-21 | DXA                | W   | 0.087      | -            | -                | -                | -         |     1.05 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,223.75)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.812 | $2,000.00      | $1,624.44       |
| 2024-04-28 |      0.533 | $3,000.00      | $1,599.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
