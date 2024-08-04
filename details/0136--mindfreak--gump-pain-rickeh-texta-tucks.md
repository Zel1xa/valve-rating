### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  758.8<br />
<br />
Final Rank Value (758.8) = Starting Rank Value (681.3) + Head To Head Adjustments (77.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.3
- 400 + ( ( 0.138 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 681.3


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
|           27 |      149 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.227 (0.032)    | 0 (0.000) |    10.82 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      193 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.58 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      413 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    10.16 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      418 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    10.99 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      595 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | gump, pain, Sliimey, supar, tucks   |
|           22 |      599 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.52 | gump, pain, Sliimey, supar, tucks   |
|           21 |      712 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.57 | gump, pain, Sliimey, supar, tucks   |
|           20 |      715 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.32 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1282 | 2024-06-08 | FlyQuest           | L   | 0.819      | -            | -                | -                | -         |    -1.98 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1339 | 2024-06-07 | Bad News Kangaroos | W   | 0.813      | 0.333        | 0.003 (0.001)    | 0.146 (0.040)    | 0 (0.000) |    11.71 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1407 | 2024-06-06 | Vantage            | W   | 0.806      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.66 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1813 | 2024-05-22 | FlyQuest           | L   | 0.707      | -            | -                | -                | -         |    -1.34 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1818 | 2024-05-22 | FlyQuest           | L   | 0.706      | -            | -                | -                | -         |    -1.36 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2264 | 2024-05-08 | Arcade             | W   | 0.613      | 0.333        | 0.002 (0.001)    | 0.137 (0.028)    | 0 (0.000) |     7.66 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2267 | 2024-05-08 | Arcade             | W   | 0.613      | 0.333        | 0.002 (0.001)    | 0.137 (0.028)    | 0 (0.000) |     8.07 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2597 | 2024-04-22 | Vantage            | W   | 0.507      | 0.333        | 0.002 (0.000)    | 0.070 (0.012)    | -         |     7.16 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2599 | 2024-04-22 | Vantage            | W   | 0.507      | 0.333        | 0.002 (0.000)    | 0.070 (0.012)    | -         |     7.48 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2696 | 2024-04-19 | Bad News Kangaroos | L   | 0.487      | -            | -                | -                | -         |    -6.02 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2702 | 2024-04-18 | FlyQuest           | L   | 0.486      | -            | -                | -                | -         |    -1.00 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2754 | 2024-04-18 | DXA                | W   | 0.479      | 0.143        | -                | 0.227 (0.016)    | -         |     6.84 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2779 | 2024-04-17 | KZG                | W   | 0.473      | 0.143        | 0.005 (0.000)    | 0.112 (0.008)    | -         |     7.37 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4088 | 2024-02-20 | Vantage            | L   | 0.094      | -            | -                | -                | -         |    -1.61 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4093 | 2024-02-20 | RKON               | W   | 0.093      | -            | -                | -                | -         |     0.78 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4117 | 2024-02-18 | FlyQuest           | L   | 0.086      | -            | -                | -                | -         |    -0.18 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4132 | 2024-02-18 | Vantage            | W   | 0.080      | -            | -                | -                | -         |     1.16 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4133 | 2024-02-18 | Vantage            | W   | 0.080      | -            | -                | -                | -         |     1.15 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4138 | 2024-02-18 | gfg123321          | W   | 0.080      | -            | -                | -                | -         |     0.43 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,155.78)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
