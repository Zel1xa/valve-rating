### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  803.2<br />
<br />
Final Rank Value (803.2) = Starting Rank Value (774.9) + Head To Head Adjustments (28.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.293[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.9
- 400 + ( ( 0.182 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 774.9


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
|           37 |      476 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.13 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      480 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.48 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      660 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |     8.48 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      665 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.56 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      778 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.218 (0.073)    | 0 (0.000) |     9.61 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      780 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.218 (0.073)    | 0 (0.000) |    10.37 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1293 | 2024-06-08 | FlyQuest           | L   | 0.811      | -            | -                | -                | -         |    -3.54 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1403 | 2024-06-07 | FlyQuest           | W   | 0.799      | 0.333        | 0.104 (0.028)    | 0.274 (0.073)    | 0 (0.000) |    22.02 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1474 | 2024-06-06 | Bad News Kangaroos | W   | 0.792      | 0.333        | 0.003 (0.001)    | 0.142 (0.037)    | 0 (0.000) |     8.51 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1878 | 2024-05-22 | Vantage            | W   | 0.692      | 0.333        | -                | 0.064 (0.015)    | 0 (0.000) |     6.08 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1883 | 2024-05-22 | Vantage            | W   | 0.692      | 0.333        | -                | 0.064 (0.015)    | 0 (0.000) |     6.39 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2136 | 2024-05-15 | Canon Event        | W   | 0.646      | -            | -                | -                | 0 (0.000) |     2.82 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2141 | 2024-05-15 | Canon Event        | W   | 0.645      | -            | -                | -                | 0 (0.000) |     2.90 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2329 | 2024-05-08 | KZG                | W   | 0.599      | 0.333        | 0.005 (0.001)    | 0.106 (0.021)    | -         |     5.96 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2332 | 2024-05-08 | KZG                | W   | 0.599      | 0.333        | 0.005 (0.001)    | 0.106 (0.021)    | -         |     6.25 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2563 | 2024-04-26 | MIBR               | L   | 0.524      | -            | -                | -                | -         |    -0.45 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2585 | 2024-04-26 | KZG                | W   | 0.519      | 0.500        | 0.005 (0.001)    | 0.106 (0.028)    | 1 (0.519) |     5.65 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2588 | 2024-04-25 | Rebels             | L   | 0.518      | -            | -                | -                | -         |    -4.08 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2719 | 2024-04-19 | Bad News Kangaroos | L   | 0.478      | -            | -                | -                | -         |    -7.96 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2761 | 2024-04-19 | FlyQuest           | L   | 0.473      | -            | -                | -                | -         |    -1.70 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2767 | 2024-04-18 | Bad News Kangaroos | W   | 0.471      | 0.143        | 0.016 (0.001)    | -                | -         |     6.98 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2843 | 2024-04-17 | Arcade             | W   | 0.459      | -            | -                | -                | -         |     4.61 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2847 | 2024-04-17 | Canon Event        | W   | 0.459      | -            | -                | -                | -         |     2.27 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3016 | 2024-04-10 | Bad News Kangaroos | L   | 0.412      | -            | -                | -                | -         |    -6.90 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3023 | 2024-04-10 | Bad News Kangaroos | W   | 0.412      | 0.333        | 0.016 (0.002)    | -                | -         |     6.22 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3376 | 2024-03-27 | Arcade             | W   | 0.319      | -            | -                | -                | -         |     3.39 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3381 | 2024-03-27 | Arcade             | W   | 0.319      | -            | -                | -                | -         |     3.48 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3648 | 2024-03-13 | FlyQuest           | L   | 0.226      | -            | -                | -                | -         |    -0.80 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3656 | 2024-03-13 | FlyQuest           | L   | 0.226      | -            | -                | -                | -         |    -0.80 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3823 | 2024-03-06 | Mindfreak          | W   | 0.179      | -            | -                | -                | -         |     1.95 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3829 | 2024-03-06 | Mindfreak          | W   | 0.179      | -            | -                | -                | -         |     1.97 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4078 | 2024-02-23 | FlyQuest           | L   | 0.099      | -            | -                | -                | -         |    -0.34 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4080 | 2024-02-22 | Bad News Kangaroos | W   | 0.098      | -            | -                | -                | -         |     1.46 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4097 | 2024-02-22 | FlyQuest           | L   | 0.092      | -            | -                | -                | -         |    -0.32 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4100 | 2024-02-21 | Vantage            | W   | 0.091      | -            | -                | -                | -         |     0.96 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4127 | 2024-02-21 | DXA                | W   | 0.086      | -            | -                | -                | -         |     1.02 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4131 | 2024-02-21 | DXA                | W   | 0.086      | -            | -                | -                | -         |     1.02 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,219.12)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.811 | $2,000.00      | $1,622.59       |
| 2024-04-28 |      0.532 | $3,000.00      | $1,596.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
