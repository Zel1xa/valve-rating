### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  764.9<br />
<br />
Final Rank Value (764.9) = Starting Rank Value (685.1) + Head To Head Adjustments (79.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.1
- 400 + ( ( 0.138 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 685.1


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
|           27 |       32 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.228 (0.033)    | 0 (0.000) |    10.70 | gump, pain, Rickeh, Texta, tucks    |
|           26 |       76 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      296 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.139 (0.046)    | 0 (0.000) |    10.05 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      300 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.139 (0.046)    | 0 (0.000) |    10.87 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      478 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.20 | gump, pain, Sliimey, supar, tucks   |
|           22 |      481 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.38 | gump, pain, Sliimey, supar, tucks   |
|           21 |      595 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.45 | gump, pain, Sliimey, supar, tucks   |
|           20 |      597 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.19 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1165 | 2024-06-08 | FlyQuest           | L   | 0.843      | -            | -                | -                | -         |    -1.89 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1222 | 2024-06-07 | Bad News Kangaroos | W   | 0.837      | 0.333        | 0.003 (0.001)    | 0.143 (0.040)    | 0 (0.000) |    11.98 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1290 | 2024-06-06 | Vantage            | W   | 0.830      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.71 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1696 | 2024-05-22 | FlyQuest           | L   | 0.730      | -            | -                | -                | -         |    -1.25 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1701 | 2024-05-22 | FlyQuest           | L   | 0.730      | -            | -                | -                | -         |    -1.27 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2147 | 2024-05-08 | Arcade             | W   | 0.637      | 0.333        | 0.003 (0.001)    | 0.139 (0.029)    | 0 (0.000) |     7.90 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2150 | 2024-05-08 | Arcade             | W   | 0.637      | 0.333        | 0.003 (0.001)    | 0.139 (0.029)    | 0 (0.000) |     8.34 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2480 | 2024-04-22 | Vantage            | W   | 0.531      | 0.333        | 0.002 (0.000)    | 0.076 (0.013)    | -         |     7.46 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2482 | 2024-04-22 | Vantage            | W   | 0.530      | 0.333        | 0.002 (0.000)    | 0.076 (0.013)    | -         |     7.82 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2579 | 2024-04-19 | Bad News Kangaroos | L   | 0.511      | -            | -                | -                | -         |    -6.20 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2585 | 2024-04-18 | FlyQuest           | L   | 0.509      | -            | -                | -                | -         |    -0.94 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2637 | 2024-04-18 | DXA                | W   | 0.503      | 0.143        | -                | 0.228 (0.016)    | -         |     7.14 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2662 | 2024-04-17 | KZG                | W   | 0.497      | 0.143        | 0.006 (0.000)    | 0.113 (0.008)    | -         |     7.71 | gump, pain, Sliimey, supar, tucks   |
|            6 |     3971 | 2024-02-20 | Vantage            | L   | 0.117      | -            | -                | -                | -         |    -2.02 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     3976 | 2024-02-20 | RKON               | W   | 0.117      | -            | -                | -                | -         |     0.96 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4000 | 2024-02-18 | FlyQuest           | L   | 0.110      | -            | -                | -                | -         |    -0.20 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4015 | 2024-02-18 | Vantage            | W   | 0.104      | -            | -                | -                | -         |     1.51 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4016 | 2024-02-18 | Vantage            | W   | 0.104      | -            | -                | -                | -         |     1.49 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4021 | 2024-02-18 | gfg123321          | W   | 0.103      | -            | -                | -                | -         |     0.55 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,189.07)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
