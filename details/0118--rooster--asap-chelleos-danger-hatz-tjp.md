### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  805.3<br />
<br />
Final Rank Value (805.3) = Starting Rank Value (776.0) + Head To Head Adjustments (29.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.0
- 400 + ( ( 0.184 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 776.0


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
|           37 |      384 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.18 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      389 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.53 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      568 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.235 (0.078)    | 0 (0.000) |     8.33 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      576 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.71 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      683 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.214 (0.071)    | 0 (0.000) |     9.51 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      688 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.214 (0.071)    | 0 (0.000) |    10.26 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1168 | 2024-06-08 | FlyQuest           | L   | 0.830      | -            | -                | -                | -         |    -3.57 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1273 | 2024-06-07 | FlyQuest           | W   | 0.818      | 0.333        | 0.104 (0.028)    | 0.302 (0.082)    | 0 (0.000) |    22.60 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1344 | 2024-06-06 | Bad News Kangaroos | W   | 0.811      | 0.333        | 0.003 (0.001)    | 0.150 (0.041)    | 0 (0.000) |     8.65 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1744 | 2024-05-22 | Vantage            | W   | 0.711      | 0.333        | -                | 0.074 (0.018)    | 0 (0.000) |     6.20 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1749 | 2024-05-22 | Vantage            | W   | 0.711      | 0.333        | -                | 0.074 (0.018)    | 0 (0.000) |     6.52 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2001 | 2024-05-15 | Canon Event        | W   | 0.665      | -            | -                | -                | 0 (0.000) |     2.83 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2006 | 2024-05-15 | Canon Event        | W   | 0.664      | -            | -                | -                | 0 (0.000) |     2.91 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2193 | 2024-05-08 | KZG                | W   | 0.618      | 0.333        | 0.005 (0.001)    | 0.116 (0.024)    | -         |     5.63 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2196 | 2024-05-08 | KZG                | W   | 0.618      | 0.333        | 0.005 (0.001)    | 0.116 (0.024)    | -         |     5.89 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2427 | 2024-04-26 | MIBR               | L   | 0.543      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2448 | 2024-04-26 | KZG                | W   | 0.538      | 0.500        | 0.005 (0.001)    | 0.116 (0.031)    | 1 (0.538) |     5.35 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2451 | 2024-04-25 | Rebels             | L   | 0.537      | -            | -                | -                | -         |    -4.34 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2582 | 2024-04-19 | Bad News Kangaroos | L   | 0.497      | -            | -                | -                | -         |    -8.26 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2624 | 2024-04-19 | FlyQuest           | L   | 0.492      | -            | -                | -                | -         |    -1.72 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2630 | 2024-04-18 | Bad News Kangaroos | W   | 0.490      | 0.143        | 0.017 (0.001)    | -                | -         |     7.28 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2706 | 2024-04-17 | Arcade             | W   | 0.478      | -            | -                | -                | -         |     4.83 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2710 | 2024-04-17 | Canon Event        | W   | 0.478      | -            | -                | -                | -         |     2.30 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2879 | 2024-04-10 | Bad News Kangaroos | L   | 0.431      | -            | -                | -                | -         |    -7.20 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     2886 | 2024-04-10 | Bad News Kangaroos | W   | 0.431      | 0.333        | 0.017 (0.002)    | -                | -         |     6.53 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3237 | 2024-03-27 | Arcade             | W   | 0.338      | -            | -                | -                | -         |     3.63 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3242 | 2024-03-27 | Arcade             | W   | 0.338      | -            | -                | -                | -         |     3.73 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3504 | 2024-03-13 | FlyQuest           | L   | 0.245      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3512 | 2024-03-13 | FlyQuest           | L   | 0.245      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3678 | 2024-03-06 | Mindfreak          | W   | 0.198      | -            | -                | -                | -         |     2.14 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3684 | 2024-03-06 | Mindfreak          | W   | 0.198      | -            | -                | -                | -         |     2.17 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     3933 | 2024-02-23 | FlyQuest           | L   | 0.118      | -            | -                | -                | -         |    -0.40 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     3935 | 2024-02-22 | Bad News Kangaroos | W   | 0.117      | -            | -                | -                | -         |     1.75 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     3952 | 2024-02-22 | FlyQuest           | L   | 0.111      | -            | -                | -                | -         |    -0.37 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     3955 | 2024-02-21 | Vantage            | W   | 0.110      | -            | -                | -                | -         |     1.17 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     3982 | 2024-02-21 | DXA                | W   | 0.105      | -            | -                | -                | -         |     1.24 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     3986 | 2024-02-21 | DXA                | W   | 0.105      | -            | -                | -                | -         |     1.25 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,314.26)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.830 | $2,000.00      | $1,660.65       |
| 2024-04-28 |      0.551 | $3,000.00      | $1,653.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
