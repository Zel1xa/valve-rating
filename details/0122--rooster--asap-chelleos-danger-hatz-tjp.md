### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  811.2<br />
<br />
Final Rank Value (811.2) = Starting Rank Value (778.4) + Head To Head Adjustments (32.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.4
- 400 + ( ( 0.185 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 778.4


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
|           37 |      459 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.37 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      463 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.69 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      643 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.225 (0.075)    | 0 (0.000) |     8.66 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      648 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.37 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      761 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.226 (0.075)    | 0 (0.000) |     9.71 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      763 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.226 (0.075)    | 0 (0.000) |    10.48 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1276 | 2024-06-08 | FlyQuest           | L   | 0.818      | -            | -                | -                | -         |    -3.64 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1386 | 2024-06-07 | FlyQuest           | W   | 0.805      | 0.333        | 0.104 (0.028)    | 0.290 (0.078)    | 0 (0.000) |    22.14 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1457 | 2024-06-06 | Bad News Kangaroos | W   | 0.799      | 0.333        | 0.017 (0.004)    | 0.225 (0.060)    | 0 (0.000) |    12.06 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1861 | 2024-05-22 | Vantage            | W   | 0.699      | 0.333        | -                | 0.068 (0.016)    | 0 (0.000) |     6.04 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1866 | 2024-05-22 | Vantage            | W   | 0.699      | -            | -                | -                | 0 (0.000) |     6.35 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2119 | 2024-05-15 | Canon Event        | W   | 0.652      | -            | -                | -                | 0 (0.000) |     2.78 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2124 | 2024-05-15 | Canon Event        | W   | 0.652      | -            | -                | -                | 0 (0.000) |     2.85 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2312 | 2024-05-08 | KZG                | W   | 0.606      | 0.333        | 0.005 (0.001)    | 0.111 (0.022)    | -         |     5.92 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2315 | 2024-05-08 | KZG                | W   | 0.606      | 0.333        | 0.005 (0.001)    | 0.111 (0.022)    | -         |     6.20 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2546 | 2024-04-26 | MIBR               | L   | 0.531      | -            | -                | -                | -         |    -0.45 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2568 | 2024-04-26 | KZG                | W   | 0.526      | 0.500        | 0.005 (0.001)    | 0.111 (0.029)    | 1 (0.526) |     5.62 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2571 | 2024-04-25 | Rebels             | L   | 0.524      | -            | -                | -                | -         |    -4.23 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2702 | 2024-04-19 | Bad News Kangaroos | L   | 0.485      | -            | -                | -                | -         |    -7.83 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2744 | 2024-04-19 | FlyQuest           | L   | 0.479      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2750 | 2024-04-18 | Bad News Kangaroos | W   | 0.478      | 0.143        | 0.017 (0.001)    | -                | -         |     7.34 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2826 | 2024-04-17 | Arcade             | W   | 0.466      | -            | -                | -                | -         |     4.76 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2830 | 2024-04-17 | Canon Event        | W   | 0.466      | -            | -                | -                | -         |     2.25 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2999 | 2024-04-10 | Bad News Kangaroos | L   | 0.419      | -            | -                | -                | -         |    -6.77 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3006 | 2024-04-10 | Bad News Kangaroos | W   | 0.419      | 0.333        | 0.017 (0.002)    | 0.225 (0.031)    | -         |     6.57 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3359 | 2024-03-27 | Arcade             | W   | 0.326      | -            | -                | -                | -         |     3.55 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3364 | 2024-03-27 | Arcade             | W   | 0.326      | -            | -                | -                | -         |     3.64 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3631 | 2024-03-13 | FlyQuest           | L   | 0.233      | -            | -                | -                | -         |    -0.82 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3639 | 2024-03-13 | FlyQuest           | L   | 0.233      | -            | -                | -                | -         |    -0.82 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3806 | 2024-03-06 | Mindfreak          | W   | 0.186      | -            | -                | -                | -         |     2.00 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3812 | 2024-03-06 | Mindfreak          | W   | 0.186      | -            | -                | -                | -         |     2.03 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4061 | 2024-02-23 | FlyQuest           | L   | 0.106      | -            | -                | -                | -         |    -0.37 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4063 | 2024-02-22 | Bad News Kangaroos | W   | 0.105      | -            | -                | -                | -         |     0.96 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4080 | 2024-02-22 | FlyQuest           | L   | 0.099      | -            | -                | -                | -         |    -0.34 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4083 | 2024-02-21 | Vantage            | W   | 0.098      | -            | -                | -                | -         |     1.02 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4110 | 2024-02-21 | DXA                | W   | 0.093      | -            | -                | -                | -         |     1.12 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4114 | 2024-02-21 | DXA                | W   | 0.092      | -            | -                | -                | -         |     1.12 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,252.92)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.818 | $2,000.00      | $1,636.11       |
| 2024-04-28 |      0.539 | $3,000.00      | $1,616.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
