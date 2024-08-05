### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  768.8<br />
<br />
Final Rank Value (768.8) = Starting Rank Value (689.3) + Head To Head Adjustments (79.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.3
- 400 + ( ( 0.141 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 689.3


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
|           27 |      198 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.225 (0.032)    | 0 (0.000) |    10.98 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      242 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.47 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      462 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    10.54 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      466 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    11.42 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      644 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.15 | gump, pain, Sliimey, supar, tucks   |
|           22 |      647 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.32 | gump, pain, Sliimey, supar, tucks   |
|           21 |      761 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.71 | gump, pain, Sliimey, supar, tucks   |
|           20 |      763 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.48 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1331 | 2024-06-08 | FlyQuest           | L   | 0.812      | -            | -                | -                | -         |    -2.07 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1388 | 2024-06-07 | Bad News Kangaroos | W   | 0.805      | 0.333        | 0.017 (0.004)    | 0.225 (0.060)    | 0 (0.000) |    15.03 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1456 | 2024-06-06 | Vantage            | W   | 0.799      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.42 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1862 | 2024-05-22 | FlyQuest           | L   | 0.699      | -            | -                | -                | -         |    -1.38 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1867 | 2024-05-22 | FlyQuest           | L   | 0.699      | -            | -                | -                | -         |    -1.40 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2313 | 2024-05-08 | Arcade             | W   | 0.606      | 0.333        | 0.002 (0.000)    | 0.136 (0.027)    | 0 (0.000) |     7.62 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2316 | 2024-05-08 | Arcade             | W   | 0.606      | 0.333        | 0.002 (0.000)    | 0.136 (0.027)    | 0 (0.000) |     8.02 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2646 | 2024-04-22 | Vantage            | W   | 0.499      | 0.333        | 0.002 (0.000)    | 0.068 (0.011)    | -         |     6.91 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2648 | 2024-04-22 | Vantage            | W   | 0.499      | 0.333        | 0.002 (0.000)    | 0.068 (0.011)    | -         |     7.22 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2745 | 2024-04-19 | Bad News Kangaroos | L   | 0.479      | -            | -                | -                | -         |    -5.79 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2751 | 2024-04-18 | FlyQuest           | L   | 0.478      | -            | -                | -                | -         |    -1.04 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2803 | 2024-04-18 | DXA                | W   | 0.472      | 0.143        | -                | 0.225 (0.015)    | -         |     6.77 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2828 | 2024-04-17 | KZG                | W   | 0.466      | 0.143        | 0.005 (0.000)    | 0.111 (0.007)    | -         |     7.12 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4137 | 2024-02-20 | Vantage            | L   | 0.086      | -            | -                | -                | -         |    -1.51 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4142 | 2024-02-20 | RKON               | W   | 0.085      | -            | -                | -                | -         |     0.69 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4166 | 2024-02-18 | FlyQuest           | L   | 0.078      | -            | -                | -                | -         |    -0.17 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4181 | 2024-02-18 | Vantage            | W   | 0.073      | -            | -                | -                | -         |     1.03 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4182 | 2024-02-18 | Vantage            | W   | 0.073      | -            | -                | -                | -         |     1.02 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4187 | 2024-02-18 | gfg123321          | W   | 0.072      | -            | -                | -                | -         |     0.38 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,145.28)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
