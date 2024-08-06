### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  758.0<br />
<br />
Final Rank Value (758.0) = Starting Rank Value (681.7) + Head To Head Adjustments (76.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.7
- 400 + ( ( 0.137 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 681.7


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
|           27 |      215 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.217 (0.031)    | 0 (0.000) |    10.91 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      259 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.60 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      479 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    10.23 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      483 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    11.07 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      661 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | gump, pain, Sliimey, supar, tucks   |
|           22 |      664 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.54 | gump, pain, Sliimey, supar, tucks   |
|           21 |      778 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.61 | gump, pain, Sliimey, supar, tucks   |
|           20 |      780 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.37 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1348 | 2024-06-08 | FlyQuest           | L   | 0.805      | -            | -                | -                | -         |    -1.98 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1405 | 2024-06-07 | Bad News Kangaroos | W   | 0.799      | 0.333        | 0.003 (0.001)    | 0.142 (0.038)    | 0 (0.000) |    11.54 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1473 | 2024-06-06 | Vantage            | W   | 0.792      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.58 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1879 | 2024-05-22 | FlyQuest           | L   | 0.692      | -            | -                | -                | -         |    -1.34 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1884 | 2024-05-22 | FlyQuest           | L   | 0.692      | -            | -                | -                | -         |    -1.36 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2330 | 2024-05-08 | Arcade             | W   | 0.599      | 0.333        | 0.002 (0.000)    | 0.130 (0.026)    | 0 (0.000) |     7.51 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2333 | 2024-05-08 | Arcade             | W   | 0.599      | 0.333        | 0.002 (0.000)    | 0.130 (0.026)    | 0 (0.000) |     7.90 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2663 | 2024-04-22 | Vantage            | W   | 0.493      | 0.333        | 0.002 (0.000)    | 0.064 (0.011)    | -         |     6.97 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2665 | 2024-04-22 | Vantage            | W   | 0.492      | 0.333        | 0.002 (0.000)    | 0.064 (0.011)    | -         |     7.28 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2762 | 2024-04-19 | Bad News Kangaroos | L   | 0.473      | -            | -                | -                | -         |    -5.88 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2768 | 2024-04-18 | FlyQuest           | L   | 0.471      | -            | -                | -                | -         |    -1.00 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2820 | 2024-04-18 | DXA                | W   | 0.465      | 0.143        | -                | 0.217 (0.014)    | -         |     6.67 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2845 | 2024-04-17 | KZG                | W   | 0.459      | 0.143        | 0.005 (0.000)    | 0.106 (0.007)    | -         |     7.18 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4154 | 2024-02-20 | Vantage            | L   | 0.079      | -            | -                | -                | -         |    -1.36 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4159 | 2024-02-20 | RKON               | W   | 0.079      | -            | -                | -                | -         |     0.66 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4183 | 2024-02-18 | FlyQuest           | L   | 0.072      | -            | -                | -                | -         |    -0.15 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4198 | 2024-02-18 | Vantage            | W   | 0.066      | -            | -                | -                | -         |     0.95 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4199 | 2024-02-18 | Vantage            | W   | 0.066      | -            | -                | -                | -         |     0.95 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4204 | 2024-02-18 | gfg123321          | W   | 0.065      | -            | -                | -                | -         |     0.35 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,135.81)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
