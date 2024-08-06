### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  768.6<br />
<br />
Final Rank Value (768.6) = Starting Rank Value (689.4) + Head To Head Adjustments (79.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.4
- 400 + ( ( 0.141 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 689.4


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
|           27 |      209 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.222 (0.032)    | 0 (0.000) |    11.00 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      253 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      473 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    10.56 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      477 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    11.44 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      655 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.15 | gump, pain, Sliimey, supar, tucks   |
|           22 |      658 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | gump, pain, Sliimey, supar, tucks   |
|           21 |      772 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.72 | gump, pain, Sliimey, supar, tucks   |
|           20 |      774 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.50 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1342 | 2024-06-08 | FlyQuest           | L   | 0.809      | -            | -                | -                | -         |    -2.08 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1399 | 2024-06-07 | Bad News Kangaroos | W   | 0.802      | 0.333        | 0.016 (0.004)    | 0.222 (0.059)    | 0 (0.000) |    14.96 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1467 | 2024-06-06 | Vantage            | W   | 0.795      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.40 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1873 | 2024-05-22 | FlyQuest           | L   | 0.696      | -            | -                | -                | -         |    -1.39 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1878 | 2024-05-22 | FlyQuest           | L   | 0.696      | -            | -                | -                | -         |    -1.41 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2324 | 2024-05-08 | Arcade             | W   | 0.602      | 0.333        | 0.002 (0.000)    | 0.134 (0.027)    | 0 (0.000) |     7.58 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2327 | 2024-05-08 | Arcade             | W   | 0.602      | 0.333        | 0.002 (0.000)    | 0.134 (0.027)    | 0 (0.000) |     7.99 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2657 | 2024-04-22 | Vantage            | W   | 0.496      | 0.333        | 0.002 (0.000)    | 0.067 (0.011)    | -         |     6.87 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2659 | 2024-04-22 | Vantage            | W   | 0.496      | 0.333        | 0.002 (0.000)    | 0.067 (0.011)    | -         |     7.17 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2756 | 2024-04-19 | Bad News Kangaroos | L   | 0.476      | -            | -                | -                | -         |    -5.76 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2762 | 2024-04-18 | FlyQuest           | L   | 0.475      | -            | -                | -                | -         |    -1.04 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2814 | 2024-04-18 | DXA                | W   | 0.469      | 0.143        | -                | 0.222 (0.015)    | -         |     6.73 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2839 | 2024-04-17 | KZG                | W   | 0.463      | 0.143        | 0.005 (0.000)    | 0.109 (0.007)    | -         |     7.08 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4148 | 2024-02-20 | Vantage            | L   | 0.083      | -            | -                | -                | -         |    -1.45 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4153 | 2024-02-20 | RKON               | W   | 0.082      | -            | -                | -                | -         |     0.66 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4177 | 2024-02-18 | FlyQuest           | L   | 0.075      | -            | -                | -                | -         |    -0.17 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4192 | 2024-02-18 | Vantage            | W   | 0.069      | -            | -                | -                | -         |     0.98 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4193 | 2024-02-18 | Vantage            | W   | 0.069      | -            | -                | -                | -         |     0.97 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4198 | 2024-02-18 | gfg123321          | W   | 0.069      | -            | -                | -                | -         |     0.36 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,140.61)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
