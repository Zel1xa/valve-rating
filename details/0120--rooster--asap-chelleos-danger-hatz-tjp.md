### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  805.5<br />
<br />
Final Rank Value (805.5) = Starting Rank Value (775.3) + Head To Head Adjustments (30.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.3
- 400 + ( ( 0.184 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 775.3


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
|           37 |      407 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.20 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      412 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.54 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      591 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     8.34 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      597 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.70 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      709 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.53 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      712 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.28 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1223 | 2024-06-08 | FlyQuest           | L   | 0.829      | -            | -                | -                | -         |    -3.58 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1333 | 2024-06-07 | FlyQuest           | W   | 0.816      | 0.333        | 0.104 (0.028)    | 0.291 (0.079)    | 0 (0.000) |    22.54 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1404 | 2024-06-06 | Bad News Kangaroos | W   | 0.809      | 0.333        | 0.003 (0.001)    | 0.145 (0.039)    | 0 (0.000) |     8.62 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1808 | 2024-05-22 | Vantage            | W   | 0.710      | 0.333        | -                | 0.071 (0.017)    | 0 (0.000) |     6.18 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1813 | 2024-05-22 | Vantage            | W   | 0.709      | 0.333        | -                | 0.071 (0.017)    | 0 (0.000) |     6.50 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2066 | 2024-05-15 | Canon Event        | W   | 0.663      | -            | -                | -                | 0 (0.000) |     2.83 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2071 | 2024-05-15 | Canon Event        | W   | 0.663      | -            | -                | -                | 0 (0.000) |     2.91 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2259 | 2024-05-08 | KZG                | W   | 0.616      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     6.05 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2262 | 2024-05-08 | KZG                | W   | 0.616      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     6.34 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2493 | 2024-04-26 | MIBR               | L   | 0.542      | -            | -                | -                | -         |    -0.45 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2514 | 2024-04-26 | KZG                | W   | 0.536      | 0.500        | 0.005 (0.001)    | 0.112 (0.030)    | 1 (0.536) |     5.77 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2517 | 2024-04-25 | Rebels             | L   | 0.535      | -            | -                | -                | -         |    -4.26 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2648 | 2024-04-19 | Bad News Kangaroos | L   | 0.495      | -            | -                | -                | -         |    -8.23 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2690 | 2024-04-19 | FlyQuest           | L   | 0.490      | -            | -                | -                | -         |    -1.72 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2696 | 2024-04-18 | Bad News Kangaroos | W   | 0.489      | 0.143        | 0.017 (0.001)    | -                | -         |     7.25 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2772 | 2024-04-17 | Arcade             | W   | 0.477      | -            | -                | -                | -         |     4.75 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2776 | 2024-04-17 | Canon Event        | W   | 0.476      | -            | -                | -                | -         |     2.31 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2945 | 2024-04-10 | Bad News Kangaroos | L   | 0.430      | -            | -                | -                | -         |    -7.17 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     2952 | 2024-04-10 | Bad News Kangaroos | W   | 0.429      | 0.333        | 0.017 (0.002)    | -                | -         |     6.50 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3305 | 2024-03-27 | Arcade             | W   | 0.337      | -            | -                | -                | -         |     3.56 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3310 | 2024-03-27 | Arcade             | W   | 0.336      | -            | -                | -                | -         |     3.66 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3576 | 2024-03-13 | FlyQuest           | L   | 0.243      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3584 | 2024-03-13 | FlyQuest           | L   | 0.243      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3751 | 2024-03-06 | Mindfreak          | W   | 0.197      | -            | -                | -                | -         |     2.13 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3757 | 2024-03-06 | Mindfreak          | W   | 0.196      | -            | -                | -                | -         |     2.16 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4006 | 2024-02-23 | FlyQuest           | L   | 0.116      | -            | -                | -                | -         |    -0.39 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4008 | 2024-02-22 | Bad News Kangaroos | W   | 0.115      | -            | -                | -                | -         |     1.73 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4025 | 2024-02-22 | FlyQuest           | L   | 0.110      | -            | -                | -                | -         |    -0.37 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4028 | 2024-02-21 | Vantage            | W   | 0.108      | -            | -                | -                | -         |     1.15 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4055 | 2024-02-21 | DXA                | W   | 0.103      | -            | -                | -                | -         |     1.22 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4059 | 2024-02-21 | DXA                | W   | 0.103      | -            | -                | -                | -         |     1.23 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,305.69)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.829 | $2,000.00      | $1,657.22       |
| 2024-04-28 |      0.549 | $3,000.00      | $1,648.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
