### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  769.2<br />
<br />
Final Rank Value (769.2) = Starting Rank Value (689.3) + Head To Head Adjustments (79.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.3
- 400 + ( ( 0.141 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 689.3


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
|           27 |      185 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.226 (0.032)    | 0 (0.000) |    10.96 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      229 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.47 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      449 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    10.53 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      453 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    11.40 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      631 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | gump, pain, Sliimey, supar, tucks   |
|           22 |      634 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.31 | gump, pain, Sliimey, supar, tucks   |
|           21 |      748 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.70 | gump, pain, Sliimey, supar, tucks   |
|           20 |      750 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.47 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1318 | 2024-06-08 | FlyQuest           | L   | 0.815      | -            | -                | -                | -         |    -2.07 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1375 | 2024-06-07 | Bad News Kangaroos | W   | 0.809      | 0.333        | 0.017 (0.004)    | 0.226 (0.061)    | 0 (0.000) |    15.10 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1443 | 2024-06-06 | Vantage            | W   | 0.802      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.43 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1849 | 2024-05-22 | FlyQuest           | L   | 0.702      | -            | -                | -                | -         |    -1.37 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1854 | 2024-05-22 | FlyQuest           | L   | 0.702      | -            | -                | -                | -         |    -1.39 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2300 | 2024-05-08 | Arcade             | W   | 0.609      | 0.333        | 0.002 (0.000)    | 0.136 (0.028)    | 0 (0.000) |     7.65 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2303 | 2024-05-08 | Arcade             | W   | 0.609      | 0.333        | 0.002 (0.000)    | 0.136 (0.028)    | 0 (0.000) |     8.06 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2633 | 2024-04-22 | Vantage            | W   | 0.503      | 0.333        | 0.002 (0.000)    | 0.069 (0.012)    | -         |     6.95 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2635 | 2024-04-22 | Vantage            | W   | 0.502      | 0.333        | 0.002 (0.000)    | 0.069 (0.012)    | -         |     7.26 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2732 | 2024-04-19 | Bad News Kangaroos | L   | 0.483      | -            | -                | -                | -         |    -5.83 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2738 | 2024-04-18 | FlyQuest           | L   | 0.482      | -            | -                | -                | -         |    -1.04 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2790 | 2024-04-18 | DXA                | W   | 0.475      | 0.143        | -                | 0.226 (0.015)    | -         |     6.81 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2815 | 2024-04-17 | KZG                | W   | 0.469      | 0.143        | 0.005 (0.000)    | 0.111 (0.007)    | -         |     7.16 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4124 | 2024-02-20 | Vantage            | L   | 0.089      | -            | -                | -                | -         |    -1.56 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4129 | 2024-02-20 | RKON               | W   | 0.089      | -            | -                | -                | -         |     0.72 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4153 | 2024-02-18 | FlyQuest           | L   | 0.082      | -            | -                | -                | -         |    -0.18 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4168 | 2024-02-18 | Vantage            | W   | 0.076      | -            | -                | -                | -         |     1.07 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4169 | 2024-02-18 | Vantage            | W   | 0.076      | -            | -                | -                | -         |     1.07 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4174 | 2024-02-18 | gfg123321          | W   | 0.075      | -            | -                | -                | -         |     0.39 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,149.94)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
