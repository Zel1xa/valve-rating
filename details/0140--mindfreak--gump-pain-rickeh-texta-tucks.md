### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  747.1<br />
<br />
Final Rank Value (747.1) = Starting Rank Value (680.2) + Head To Head Adjustments (66.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.2
- 400 + ( ( 0.137 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 680.2


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
|           25 |      167 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.60 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      387 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.142 (0.047)    | 0 (0.000) |    10.27 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      392 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.142 (0.047)    | 0 (0.000) |    11.11 | gump, pain, Rickeh, Texta, tucks    |
|           22 |      569 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | gump, pain, Sliimey, supar, tucks   |
|           21 |      575 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.55 | gump, pain, Sliimey, supar, tucks   |
|           20 |      683 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.51 | gump, pain, Sliimey, supar, tucks   |
|           19 |      688 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.26 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1218 | 2024-06-08 | FlyQuest           | L   | 0.824      | -            | -                | -                | -         |    -1.96 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1275 | 2024-06-07 | Bad News Kangaroos | W   | 0.818      | 0.333        | 0.003 (0.001)    | 0.150 (0.041)    | 0 (0.000) |    11.83 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1343 | 2024-06-06 | Vantage            | W   | 0.811      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.74 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1745 | 2024-05-22 | FlyQuest           | L   | 0.711      | -            | -                | -                | -         |    -1.32 | gump, pain, Sliimey, supar, tucks   |
|           14 |     1750 | 2024-05-22 | FlyQuest           | L   | 0.711      | -            | -                | -                | -         |    -1.34 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2194 | 2024-05-08 | Arcade             | W   | 0.618      | 0.333        | 0.002 (0.001)    | 0.142 (0.029)    | 0 (0.000) |     7.87 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2197 | 2024-05-08 | Arcade             | W   | 0.618      | 0.333        | 0.002 (0.001)    | 0.142 (0.029)    | 0 (0.000) |     8.30 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2526 | 2024-04-22 | Vantage            | W   | 0.512      | 0.333        | 0.002 (0.000)    | 0.074 (0.013)    | 0 (0.000) |     7.30 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2528 | 2024-04-22 | Vantage            | W   | 0.511      | 0.333        | 0.002 (0.000)    | 0.074 (0.013)    | -         |     7.63 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2625 | 2024-04-19 | Bad News Kangaroos | L   | 0.492      | -            | -                | -                | -         |    -6.00 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2631 | 2024-04-18 | FlyQuest           | L   | 0.490      | -            | -                | -                | -         |    -0.99 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2683 | 2024-04-18 | DXA                | W   | 0.484      | 0.143        | 0.002 (0.000)    | 0.235 (0.016)    | -         |     6.97 | gump, pain, Sliimey, supar, tucks   |
|            6 |     2708 | 2024-04-17 | KZG                | W   | 0.478      | 0.143        | 0.005 (0.000)    | 0.116 (0.008)    | -         |     7.07 | gump, pain, Sliimey, supar, tucks   |
|            5 |     4009 | 2024-02-20 | Vantage            | L   | 0.098      | -            | -                | -                | -         |    -1.67 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4014 | 2024-02-20 | RKON               | W   | 0.098      | -            | -                | -                | -         |     0.82 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4038 | 2024-02-18 | FlyQuest           | L   | 0.091      | -            | -                | -                | -         |    -0.18 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4053 | 2024-02-18 | Vantage            | W   | 0.085      | 0.143        | -                | 0.074 (0.001)    | -         |     1.24 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4058 | 2024-02-18 | gfg123321          | W   | 0.084      | -            | -                | -                | -         |     0.46 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,162.45)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
