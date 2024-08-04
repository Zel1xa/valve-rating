### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  769.5<br />
<br />
Final Rank Value (769.5) = Starting Rank Value (689.4) + Head To Head Adjustments (80.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.4
- 400 + ( ( 0.141 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 689.4


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
|           27 |      181 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.226 (0.032)    | 0 (0.000) |    10.95 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      225 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.46 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      445 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    10.52 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      449 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    11.39 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      627 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.13 | gump, pain, Sliimey, supar, tucks   |
|           22 |      630 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.31 | gump, pain, Sliimey, supar, tucks   |
|           21 |      744 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.69 | gump, pain, Sliimey, supar, tucks   |
|           20 |      746 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.47 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1314 | 2024-06-08 | FlyQuest           | L   | 0.818      | -            | -                | -                | -         |    -2.06 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1371 | 2024-06-07 | Bad News Kangaroos | W   | 0.811      | 0.333        | 0.017 (0.005)    | 0.226 (0.061)    | 0 (0.000) |    15.15 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1439 | 2024-06-06 | Vantage            | W   | 0.804      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.44 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1845 | 2024-05-22 | FlyQuest           | L   | 0.705      | -            | -                | -                | -         |    -1.37 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1850 | 2024-05-22 | FlyQuest           | L   | 0.705      | -            | -                | -                | -         |    -1.39 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2296 | 2024-05-08 | Arcade             | W   | 0.612      | 0.333        | 0.002 (0.000)    | 0.137 (0.028)    | 0 (0.000) |     7.68 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2299 | 2024-05-08 | Arcade             | W   | 0.611      | 0.333        | 0.002 (0.000)    | 0.137 (0.028)    | 0 (0.000) |     8.09 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2629 | 2024-04-22 | Vantage            | W   | 0.505      | 0.333        | 0.002 (0.000)    | 0.070 (0.012)    | -         |     6.98 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2631 | 2024-04-22 | Vantage            | W   | 0.505      | 0.333        | 0.002 (0.000)    | 0.070 (0.012)    | -         |     7.29 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2728 | 2024-04-19 | Bad News Kangaroos | L   | 0.485      | -            | -                | -                | -         |    -5.85 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2734 | 2024-04-18 | FlyQuest           | L   | 0.484      | -            | -                | -                | -         |    -1.03 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2786 | 2024-04-18 | DXA                | W   | 0.478      | 0.143        | -                | 0.226 (0.015)    | -         |     6.83 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2811 | 2024-04-17 | KZG                | W   | 0.472      | 0.143        | 0.005 (0.000)    | 0.111 (0.008)    | -         |     7.20 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4120 | 2024-02-20 | Vantage            | L   | 0.092      | -            | -                | -                | -         |    -1.61 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4125 | 2024-02-20 | RKON               | W   | 0.091      | -            | -                | -                | -         |     0.74 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4149 | 2024-02-18 | FlyQuest           | L   | 0.084      | -            | -                | -                | -         |    -0.18 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4164 | 2024-02-18 | Vantage            | W   | 0.078      | -            | -                | -                | -         |     1.11 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4165 | 2024-02-18 | Vantage            | W   | 0.078      | -            | -                | -                | -         |     1.10 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4170 | 2024-02-18 | gfg123321          | W   | 0.078      | -            | -                | -                | -         |     0.41 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,153.28)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
