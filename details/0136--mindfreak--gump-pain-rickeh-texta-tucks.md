### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  768.6<br />
<br />
Final Rank Value (768.6) = Starting Rank Value (689.7) + Head To Head Adjustments (78.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.7
- 400 + ( ( 0.141 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 689.7


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
|           27 |      217 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.217 (0.031)    | 0 (0.000) |    11.02 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      261 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      481 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    10.57 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      485 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    11.46 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      663 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.15 | gump, pain, Sliimey, supar, tucks   |
|           22 |      666 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | gump, pain, Sliimey, supar, tucks   |
|           21 |      780 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.73 | gump, pain, Sliimey, supar, tucks   |
|           20 |      782 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.51 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1350 | 2024-06-08 | FlyQuest           | L   | 0.806      | -            | -                | -                | -         |    -2.08 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1407 | 2024-06-07 | Bad News Kangaroos | W   | 0.799      | 0.333        | 0.016 (0.004)    | 0.217 (0.058)    | 0 (0.000) |    14.90 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1475 | 2024-06-06 | Vantage            | W   | 0.792      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.39 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1881 | 2024-05-22 | FlyQuest           | L   | 0.693      | -            | -                | -                | -         |    -1.39 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1886 | 2024-05-22 | FlyQuest           | L   | 0.693      | -            | -                | -                | -         |    -1.41 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2332 | 2024-05-08 | Arcade             | W   | 0.600      | 0.333        | 0.002 (0.000)    | 0.130 (0.026)    | 0 (0.000) |     7.56 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2335 | 2024-05-08 | Arcade             | W   | 0.599      | 0.333        | 0.002 (0.000)    | 0.130 (0.026)    | 0 (0.000) |     7.96 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2665 | 2024-04-22 | Vantage            | W   | 0.493      | 0.333        | 0.002 (0.000)    | 0.064 (0.011)    | -         |     6.83 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2667 | 2024-04-22 | Vantage            | W   | 0.493      | 0.333        | 0.002 (0.000)    | 0.064 (0.011)    | -         |     7.13 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2764 | 2024-04-19 | Bad News Kangaroos | L   | 0.473      | -            | -                | -                | -         |    -5.74 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2770 | 2024-04-18 | FlyQuest           | L   | 0.472      | -            | -                | -                | -         |    -1.04 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2822 | 2024-04-18 | DXA                | W   | 0.466      | 0.143        | -                | 0.217 (0.014)    | -         |     6.70 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2847 | 2024-04-17 | KZG                | W   | 0.460      | 0.143        | 0.005 (0.000)    | 0.106 (0.007)    | -         |     7.04 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4156 | 2024-02-20 | Vantage            | L   | 0.080      | -            | -                | -                | -         |    -1.40 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4161 | 2024-02-20 | RKON               | W   | 0.079      | -            | -                | -                | -         |     0.64 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4185 | 2024-02-18 | FlyQuest           | L   | 0.072      | -            | -                | -                | -         |    -0.16 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4200 | 2024-02-18 | Vantage            | W   | 0.066      | -            | -                | -                | -         |     0.94 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4201 | 2024-02-18 | Vantage            | W   | 0.066      | -            | -                | -                | -         |     0.94 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4206 | 2024-02-18 | gfg123321          | W   | 0.066      | -            | -                | -                | -         |     0.34 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,136.72)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
