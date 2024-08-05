### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  811.1<br />
<br />
Final Rank Value (811.1) = Starting Rank Value (778.5) + Head To Head Adjustments (32.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.5
- 400 + ( ( 0.185 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 778.5


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
|           37 |      468 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.36 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      472 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.68 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      652 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |     8.68 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      657 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.35 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      770 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.224 (0.075)    | 0 (0.000) |     9.71 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      772 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.224 (0.075)    | 0 (0.000) |    10.49 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1285 | 2024-06-08 | FlyQuest           | L   | 0.817      | -            | -                | -                | -         |    -3.65 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1395 | 2024-06-07 | FlyQuest           | W   | 0.804      | 0.333        | 0.104 (0.028)    | 0.286 (0.077)    | 0 (0.000) |    22.09 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1466 | 2024-06-06 | Bad News Kangaroos | W   | 0.797      | 0.333        | 0.017 (0.004)    | 0.222 (0.059)    | 0 (0.000) |    12.03 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1870 | 2024-05-22 | Vantage            | W   | 0.698      | 0.333        | -                | 0.067 (0.016)    | 0 (0.000) |     6.03 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1875 | 2024-05-22 | Vantage            | W   | 0.697      | -            | -                | -                | 0 (0.000) |     6.34 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2128 | 2024-05-15 | Canon Event        | W   | 0.651      | -            | -                | -                | 0 (0.000) |     2.78 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2133 | 2024-05-15 | Canon Event        | W   | 0.651      | -            | -                | -                | 0 (0.000) |     2.85 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2321 | 2024-05-08 | KZG                | W   | 0.604      | 0.333        | 0.005 (0.001)    | 0.109 (0.022)    | -         |     5.92 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2324 | 2024-05-08 | KZG                | W   | 0.604      | 0.333        | 0.005 (0.001)    | 0.109 (0.022)    | -         |     6.20 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2555 | 2024-04-26 | MIBR               | L   | 0.530      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2577 | 2024-04-26 | KZG                | W   | 0.524      | 0.500        | 0.005 (0.001)    | 0.109 (0.029)    | 1 (0.524) |     5.61 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2580 | 2024-04-25 | Rebels             | L   | 0.523      | -            | -                | -                | -         |    -4.22 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2711 | 2024-04-19 | Bad News Kangaroos | L   | 0.483      | -            | -                | -                | -         |    -7.80 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2753 | 2024-04-19 | FlyQuest           | L   | 0.478      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2759 | 2024-04-18 | Bad News Kangaroos | W   | 0.477      | 0.143        | 0.017 (0.001)    | -                | -         |     7.32 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2835 | 2024-04-17 | Arcade             | W   | 0.465      | -            | -                | -                | -         |     4.75 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2839 | 2024-04-17 | Canon Event        | W   | 0.464      | -            | -                | -                | -         |     2.25 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3008 | 2024-04-10 | Bad News Kangaroos | L   | 0.418      | -            | -                | -                | -         |    -6.75 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3015 | 2024-04-10 | Bad News Kangaroos | W   | 0.417      | 0.333        | 0.017 (0.002)    | 0.222 (0.031)    | -         |     6.54 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3368 | 2024-03-27 | Arcade             | W   | 0.325      | -            | -                | -                | -         |     3.53 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3373 | 2024-03-27 | Arcade             | W   | 0.324      | -            | -                | -                | -         |     3.63 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3640 | 2024-03-13 | FlyQuest           | L   | 0.231      | -            | -                | -                | -         |    -0.82 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3648 | 2024-03-13 | FlyQuest           | L   | 0.231      | -            | -                | -                | -         |    -0.82 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3815 | 2024-03-06 | Mindfreak          | W   | 0.185      | -            | -                | -                | -         |     1.98 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3821 | 2024-03-06 | Mindfreak          | W   | 0.184      | -            | -                | -                | -         |     2.01 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4070 | 2024-02-23 | FlyQuest           | L   | 0.104      | -            | -                | -                | -         |    -0.36 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4072 | 2024-02-22 | Bad News Kangaroos | W   | 0.103      | -            | -                | -                | -         |     0.95 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4089 | 2024-02-22 | FlyQuest           | L   | 0.098      | -            | -                | -                | -         |    -0.34 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4092 | 2024-02-21 | Vantage            | W   | 0.096      | -            | -                | -                | -         |     1.01 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4119 | 2024-02-21 | DXA                | W   | 0.091      | -            | -                | -                | -         |     1.10 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4123 | 2024-02-21 | DXA                | W   | 0.091      | -            | -                | -                | -         |     1.11 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,245.28)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.817 | $2,000.00      | $1,633.06       |
| 2024-04-28 |      0.537 | $3,000.00      | $1,612.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
