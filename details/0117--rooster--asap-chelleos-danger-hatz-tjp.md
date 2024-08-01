### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  815.4<br />
<br />
Final Rank Value (815.4) = Starting Rank Value (781.5) + Head To Head Adjustments (33.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.5
- 400 + ( ( 0.185 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 781.5


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
|           39 |      322 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.42 | asap, chelleos, dangeR, Hatz, TjP   |
|           38 |      327 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.73 | asap, chelleos, dangeR, Hatz, TjP   |
|           37 |      515 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |     8.10 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      523 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.95 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      636 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.33 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      642 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.06 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |     1148 | 2024-06-08 | FlyQuest           | L   | 0.845      | -            | -                | -                | -         |    -3.62 | asap, chelleos, dangeR, nettik, TjP |
|           32 |     1266 | 2024-06-07 | FlyQuest           | W   | 0.832      | 0.333        | 0.106 (0.029)    | 0.323 (0.090)    | 0 (0.000) |    23.02 | asap, chelleos, dangeR, nettik, TjP |
|           31 |     1340 | 2024-06-06 | Bad News Kangaroos | W   | 0.826      | 0.333        | 0.003 (0.001)    | 0.144 (0.039)    | 0 (0.000) |     8.61 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1759 | 2024-05-22 | Vantage            | W   | 0.726      | 0.333        | -                | 0.075 (0.018)    | 0 (0.000) |     6.09 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1764 | 2024-05-22 | Vantage            | W   | 0.726      | 0.333        | -                | 0.075 (0.018)    | 0 (0.000) |     6.41 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     2037 | 2024-05-15 | Canon Event        | W   | 0.679      | -            | -                | -                | 0 (0.000) |     2.75 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     2042 | 2024-05-15 | Canon Event        | W   | 0.679      | -            | -                | -                | 0 (0.000) |     2.82 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2237 | 2024-05-08 | KZG                | W   | 0.633      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.01 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2240 | 2024-05-08 | KZG                | W   | 0.632      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.30 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2475 | 2024-04-26 | MIBR               | L   | 0.558      | -            | -                | -                | -         |    -0.51 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2496 | 2024-04-26 | KZG                | W   | 0.553      | 0.500        | 0.006 (0.002)    | 0.113 (0.031)    | 1 (0.553) |     5.75 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2499 | 2024-04-25 | Rebels             | L   | 0.551      | -            | -                | -                | -         |    -4.45 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2636 | 2024-04-19 | Bad News Kangaroos | L   | 0.512      | -            | -                | -                | -         |    -8.56 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2679 | 2024-04-19 | FlyQuest           | L   | 0.506      | -            | -                | -                | -         |    -1.72 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2685 | 2024-04-18 | Bad News Kangaroos | W   | 0.505      | 0.143        | 0.017 (0.001)    | -                | -         |     7.43 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2763 | 2024-04-17 | Arcade             | W   | 0.493      | -            | -                | -                | -         |     4.77 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2767 | 2024-04-17 | Canon Event        | W   | 0.493      | -            | -                | -                | -         |     2.26 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2938 | 2024-04-10 | Bad News Kangaroos | L   | 0.446      | -            | -                | -                | -         |    -7.50 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2945 | 2024-04-10 | Bad News Kangaroos | W   | 0.446      | 0.333        | 0.017 (0.003)    | -                | -         |     6.68 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3184 | 2024-04-03 | RKON               | W   | 0.399      | -            | -                | -                | -         |     2.12 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3185 | 2024-04-03 | RKON               | W   | 0.399      | -            | -                | -                | -         |     2.17 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3307 | 2024-03-27 | Arcade             | W   | 0.353      | -            | -                | -                | -         |     3.69 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3312 | 2024-03-27 | Arcade             | W   | 0.353      | -            | -                | -                | -         |     3.79 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3587 | 2024-03-13 | FlyQuest           | L   | 0.260      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3595 | 2024-03-13 | FlyQuest           | L   | 0.259      | -            | -                | -                | -         |    -0.85 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3764 | 2024-03-06 | Mindfreak          | W   | 0.213      | -            | -                | -                | -         |     2.27 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3770 | 2024-03-06 | Mindfreak          | W   | 0.213      | -            | -                | -                | -         |     2.31 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4032 | 2024-02-23 | FlyQuest           | L   | 0.133      | -            | -                | -                | -         |    -0.42 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4034 | 2024-02-22 | Bad News Kangaroos | W   | 0.132      | -            | -                | -                | -         |     1.98 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4052 | 2024-02-22 | FlyQuest           | L   | 0.126      | -            | -                | -                | -         |    -0.40 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4055 | 2024-02-21 | Vantage            | W   | 0.125      | -            | -                | -                | -         |     1.31 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4083 | 2024-02-21 | DXA                | W   | 0.120      | -            | -                | -                | -         |     1.40 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4087 | 2024-02-21 | DXA                | W   | 0.119      | -            | -                | -                | -         |     1.41 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,387.64)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.845 | $2,000.00      | $1,690.00       |
| 2024-04-28 |      0.566 | $3,000.00      | $1,697.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
