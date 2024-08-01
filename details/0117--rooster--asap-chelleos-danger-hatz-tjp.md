### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  814.8<br />
<br />
Final Rank Value (814.8) = Starting Rank Value (781.0) + Head To Head Adjustments (33.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.0
- 400 + ( ( 0.185 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 781.0


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
|           39 |      326 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.41 | asap, chelleos, dangeR, Hatz, TjP   |
|           38 |      331 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.72 | asap, chelleos, dangeR, Hatz, TjP   |
|           37 |      519 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |     8.11 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      527 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.94 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      640 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.34 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      646 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.07 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |     1152 | 2024-06-08 | FlyQuest           | L   | 0.844      | -            | -                | -                | -         |    -3.58 | asap, chelleos, dangeR, nettik, TjP |
|           32 |     1270 | 2024-06-07 | FlyQuest           | W   | 0.831      | 0.333        | 0.106 (0.029)    | 0.323 (0.089)    | 0 (0.000) |    23.01 | asap, chelleos, dangeR, nettik, TjP |
|           31 |     1344 | 2024-06-06 | Bad News Kangaroos | W   | 0.824      | 0.333        | 0.003 (0.001)    | 0.144 (0.039)    | 0 (0.000) |     8.61 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1763 | 2024-05-22 | Vantage            | W   | 0.725      | 0.333        | -                | 0.075 (0.018)    | 0 (0.000) |     6.09 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1768 | 2024-05-22 | Vantage            | W   | 0.724      | 0.333        | -                | 0.075 (0.018)    | 0 (0.000) |     6.41 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     2041 | 2024-05-15 | Canon Event        | W   | 0.678      | -            | -                | -                | 0 (0.000) |     2.75 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     2046 | 2024-05-15 | Canon Event        | W   | 0.678      | -            | -                | -                | 0 (0.000) |     2.83 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2241 | 2024-05-08 | KZG                | W   | 0.631      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.00 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2244 | 2024-05-08 | KZG                | W   | 0.631      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.29 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2479 | 2024-04-26 | MIBR               | L   | 0.557      | -            | -                | -                | -         |    -0.51 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2500 | 2024-04-26 | KZG                | W   | 0.551      | 0.500        | 0.006 (0.002)    | 0.113 (0.031)    | 1 (0.551) |     5.75 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2503 | 2024-04-25 | Rebels             | L   | 0.550      | -            | -                | -                | -         |    -4.44 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2640 | 2024-04-19 | Bad News Kangaroos | L   | 0.510      | -            | -                | -                | -         |    -8.54 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2683 | 2024-04-19 | FlyQuest           | L   | 0.505      | -            | -                | -                | -         |    -1.72 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2689 | 2024-04-18 | Bad News Kangaroos | W   | 0.504      | 0.143        | 0.017 (0.001)    | -                | -         |     7.41 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2767 | 2024-04-17 | Arcade             | W   | 0.492      | -            | -                | -                | -         |     4.76 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2771 | 2024-04-17 | Canon Event        | W   | 0.491      | -            | -                | -                | -         |     2.26 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2942 | 2024-04-10 | Bad News Kangaroos | L   | 0.445      | -            | -                | -                | -         |    -7.48 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2949 | 2024-04-10 | Bad News Kangaroos | W   | 0.444      | 0.333        | 0.017 (0.003)    | -                | -         |     6.66 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3188 | 2024-04-03 | RKON               | W   | 0.398      | -            | -                | -                | -         |     2.12 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3189 | 2024-04-03 | RKON               | W   | 0.398      | -            | -                | -                | -         |     2.16 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3311 | 2024-03-27 | Arcade             | W   | 0.352      | -            | -                | -                | -         |     3.68 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3316 | 2024-03-27 | Arcade             | W   | 0.351      | -            | -                | -                | -         |     3.78 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3591 | 2024-03-13 | FlyQuest           | L   | 0.258      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3599 | 2024-03-13 | FlyQuest           | L   | 0.258      | -            | -                | -                | -         |    -0.85 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3768 | 2024-03-06 | Mindfreak          | W   | 0.212      | -            | -                | -                | -         |     2.26 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3774 | 2024-03-06 | Mindfreak          | W   | 0.211      | -            | -                | -                | -         |     2.30 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4036 | 2024-02-23 | FlyQuest           | L   | 0.131      | -            | -                | -                | -         |    -0.42 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4038 | 2024-02-22 | Bad News Kangaroos | W   | 0.130      | -            | -                | -                | -         |     1.96 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4056 | 2024-02-22 | FlyQuest           | L   | 0.125      | -            | -                | -                | -         |    -0.40 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4059 | 2024-02-21 | Vantage            | W   | 0.123      | -            | -                | -                | -         |     1.29 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4087 | 2024-02-21 | DXA                | W   | 0.118      | -            | -                | -                | -         |     1.39 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4091 | 2024-02-21 | DXA                | W   | 0.118      | -            | -                | -                | -         |     1.40 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,380.69)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.844 | $2,000.00      | $1,687.22       |
| 2024-04-28 |      0.564 | $3,000.00      | $1,693.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
