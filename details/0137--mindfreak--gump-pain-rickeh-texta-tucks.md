### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  758.5<br />
<br />
Final Rank Value (758.5) = Starting Rank Value (681.4) + Head To Head Adjustments (77.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.4
- 400 + ( ( 0.138 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 681.4


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
|           26 |      146 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.227 (0.032)    | 0 (0.000) |    10.84 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      190 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.59 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      410 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    10.18 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      415 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    11.01 | gump, pain, Rickeh, Texta, tucks    |
|           22 |      592 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.34 | gump, pain, Sliimey, supar, tucks   |
|           21 |      596 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.53 | gump, pain, Sliimey, supar, tucks   |
|           20 |      709 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.53 | gump, pain, Sliimey, supar, tucks   |
|           19 |      712 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.28 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1278 | 2024-06-08 | FlyQuest           | L   | 0.823      | -            | -                | -                | -         |    -1.97 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1335 | 2024-06-07 | Bad News Kangaroos | W   | 0.816      | 0.333        | 0.003 (0.001)    | 0.145 (0.040)    | 0 (0.000) |    11.78 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1403 | 2024-06-06 | Vantage            | W   | 0.809      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.70 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1809 | 2024-05-22 | FlyQuest           | L   | 0.710      | -            | -                | -                | -         |    -1.33 | gump, pain, Sliimey, supar, tucks   |
|           14 |     1814 | 2024-05-22 | FlyQuest           | L   | 0.709      | -            | -                | -                | -         |    -1.35 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2260 | 2024-05-08 | Arcade             | W   | 0.616      | 0.333        | 0.002 (0.001)    | 0.137 (0.028)    | 0 (0.000) |     7.71 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2263 | 2024-05-08 | Arcade             | W   | 0.616      | 0.333        | 0.002 (0.001)    | 0.137 (0.028)    | 0 (0.000) |     8.13 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2592 | 2024-04-22 | Vantage            | W   | 0.510      | 0.333        | 0.002 (0.000)    | 0.071 (0.012)    | -         |     7.24 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2594 | 2024-04-22 | Vantage            | W   | 0.510      | 0.333        | 0.002 (0.000)    | 0.071 (0.012)    | -         |     7.57 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2691 | 2024-04-19 | Bad News Kangaroos | L   | 0.490      | -            | -                | -                | -         |    -6.03 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2697 | 2024-04-18 | FlyQuest           | L   | 0.489      | -            | -                | -                | -         |    -1.00 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2749 | 2024-04-18 | DXA                | W   | 0.482      | 0.143        | -                | 0.227 (0.016)    | -         |     6.91 | gump, pain, Sliimey, supar, tucks   |
|            6 |     2774 | 2024-04-17 | KZG                | W   | 0.476      | 0.143        | 0.005 (0.000)    | 0.112 (0.008)    | -         |     7.44 | gump, pain, Sliimey, supar, tucks   |
|            5 |     4082 | 2024-02-20 | Vantage            | L   | 0.097      | -            | -                | -                | -         |    -1.65 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4087 | 2024-02-20 | RKON               | W   | 0.096      | -            | -                | -                | -         |     0.81 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4111 | 2024-02-18 | FlyQuest           | L   | 0.089      | -            | -                | -                | -         |    -0.18 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4126 | 2024-02-18 | Vantage            | W   | 0.083      | -            | -                | -                | -         |     1.21 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4131 | 2024-02-18 | gfg123321          | W   | 0.083      | -            | -                | -                | -         |     0.45 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,160.06)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
