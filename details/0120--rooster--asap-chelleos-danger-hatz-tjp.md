### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  812.3<br />
<br />
Final Rank Value (812.3) = Starting Rank Value (778.8) + Head To Head Adjustments (33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.8
- 400 + ( ( 0.185 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 778.8


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
|           37 |      418 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.40 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      423 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.72 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      602 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |     8.61 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      608 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.42 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      720 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.69 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      723 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.46 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1235 | 2024-06-08 | FlyQuest           | L   | 0.825      | -            | -                | -                | -         |    -3.65 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1345 | 2024-06-07 | FlyQuest           | W   | 0.812      | 0.333        | 0.104 (0.028)    | 0.294 (0.080)    | 0 (0.000) |    22.35 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1416 | 2024-06-06 | Bad News Kangaroos | W   | 0.805      | 0.333        | 0.017 (0.004)    | 0.226 (0.061)    | 0 (0.000) |    12.17 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1820 | 2024-05-22 | Vantage            | W   | 0.706      | 0.333        | -                | 0.070 (0.017)    | 0 (0.000) |     6.07 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1825 | 2024-05-22 | Vantage            | W   | 0.706      | -            | -                | -                | 0 (0.000) |     6.38 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2078 | 2024-05-15 | Canon Event        | W   | 0.659      | -            | -                | -                | 0 (0.000) |     2.78 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2083 | 2024-05-15 | Canon Event        | W   | 0.659      | -            | -                | -                | 0 (0.000) |     2.86 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2271 | 2024-05-08 | KZG                | W   | 0.613      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     5.95 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2274 | 2024-05-08 | KZG                | W   | 0.612      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     6.24 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2505 | 2024-04-26 | MIBR               | L   | 0.538      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2527 | 2024-04-26 | KZG                | W   | 0.532      | 0.500        | 0.005 (0.001)    | 0.112 (0.030)    | 1 (0.532) |     5.67 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2530 | 2024-04-25 | Rebels             | L   | 0.531      | -            | -                | -                | -         |    -4.30 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2661 | 2024-04-19 | Bad News Kangaroos | L   | 0.492      | -            | -                | -                | -         |    -7.93 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2703 | 2024-04-19 | FlyQuest           | L   | 0.486      | -            | -                | -                | -         |    -1.74 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2709 | 2024-04-18 | Bad News Kangaroos | W   | 0.485      | 0.143        | 0.017 (0.001)    | -                | -         |     7.45 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2785 | 2024-04-17 | Arcade             | W   | 0.473      | -            | -                | -                | -         |     4.82 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2789 | 2024-04-17 | Canon Event        | W   | 0.473      | -            | -                | -                | -         |     2.27 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2958 | 2024-04-10 | Bad News Kangaroos | L   | 0.426      | -            | -                | -                | -         |    -6.88 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     2965 | 2024-04-10 | Bad News Kangaroos | W   | 0.426      | 0.333        | 0.017 (0.002)    | 0.226 (0.032)    | -         |     6.68 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3318 | 2024-03-27 | Arcade             | W   | 0.333      | -            | -                | -                | -         |     3.62 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3323 | 2024-03-27 | Arcade             | W   | 0.333      | -            | -                | -                | -         |     3.71 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3590 | 2024-03-13 | FlyQuest           | L   | 0.239      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3598 | 2024-03-13 | FlyQuest           | L   | 0.239      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3765 | 2024-03-06 | Mindfreak          | W   | 0.193      | -            | -                | -                | -         |     2.07 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3771 | 2024-03-06 | Mindfreak          | W   | 0.193      | -            | -                | -                | -         |     2.10 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4020 | 2024-02-23 | FlyQuest           | L   | 0.112      | -            | -                | -                | -         |    -0.39 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4022 | 2024-02-22 | Bad News Kangaroos | W   | 0.111      | -            | -                | -                | -         |     1.02 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4039 | 2024-02-22 | FlyQuest           | L   | 0.106      | -            | -                | -                | -         |    -0.36 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4042 | 2024-02-21 | Vantage            | W   | 0.105      | -            | -                | -                | -         |     1.09 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4069 | 2024-02-21 | DXA                | W   | 0.100      | -            | -                | -                | -         |     1.20 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4073 | 2024-02-21 | DXA                | W   | 0.099      | -            | -                | -                | -         |     1.21 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,286.83)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.825 | $2,000.00      | $1,649.68       |
| 2024-04-28 |      0.546 | $3,000.00      | $1,637.15       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
