### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  772.3<br />
<br />
Final Rank Value (772.3) = Starting Rank Value (685.0) + Head To Head Adjustments (87.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.0
- 400 + ( ( 0.138 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 685.0


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
|           26 |       60 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.228 (0.033)    | 0 (0.000) |    10.42 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      105 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.03 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      325 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.138 (0.046)    | 0 (0.000) |     9.86 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      330 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.138 (0.046)    | 0 (0.000) |    10.66 | gump, pain, Rickeh, Texta, tucks    |
|           22 |      516 | 2024-07-18 | MANTRA             | W   | 1.000      | 0.333        | -                | 0.039 (0.013)    | 0 (0.000) |     7.54 | gump, pain, Sliimey, supar, tucks   |
|           21 |      522 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.05 | gump, pain, Sliimey, supar, tucks   |
|           20 |      636 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.33 | gump, pain, Sliimey, supar, tucks   |
|           19 |      642 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.06 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1206 | 2024-06-08 | FlyQuest           | L   | 0.839      | -            | -                | -                | -         |    -1.93 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1268 | 2024-06-07 | Bad News Kangaroos | W   | 0.832      | 0.333        | 0.003 (0.001)    | 0.144 (0.040)    | 0 (0.000) |    12.01 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1339 | 2024-06-06 | Vantage            | W   | 0.826      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.72 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1760 | 2024-05-22 | FlyQuest           | L   | 0.726      | -            | -                | -                | -         |    -1.28 | gump, pain, Sliimey, supar, tucks   |
|           14 |     1765 | 2024-05-22 | FlyQuest           | L   | 0.726      | -            | -                | -                | -         |    -1.30 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2238 | 2024-05-08 | Arcade             | W   | 0.633      | 0.333        | 0.003 (0.001)    | 0.138 (0.029)    | 0 (0.000) |     7.88 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2241 | 2024-05-08 | Arcade             | W   | 0.632      | 0.333        | 0.003 (0.001)    | 0.138 (0.029)    | 0 (0.000) |     8.32 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2577 | 2024-04-22 | Vantage            | W   | 0.526      | 0.333        | 0.002 (0.000)    | 0.075 (0.013)    | -         |     7.45 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2579 | 2024-04-22 | Vantage            | W   | 0.526      | 0.333        | 0.002 (0.000)    | 0.075 (0.013)    | -         |     7.80 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2680 | 2024-04-19 | Bad News Kangaroos | L   | 0.506      | -            | -                | -                | -         |    -6.13 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2686 | 2024-04-18 | FlyQuest           | L   | 0.505      | -            | -                | -                | -         |    -0.96 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2739 | 2024-04-18 | DXA                | W   | 0.499      | 0.143        | -                | 0.228 (0.016)    | -         |     7.12 | gump, pain, Sliimey, supar, tucks   |
|            6 |     2765 | 2024-04-17 | KZG                | W   | 0.493      | 0.143        | 0.006 (0.000)    | -                | -         |     7.68 | gump, pain, Sliimey, supar, tucks   |
|            5 |     4110 | 2024-02-20 | Vantage            | L   | 0.113      | -            | -                | -                | -         |    -1.93 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4115 | 2024-02-20 | RKON               | W   | 0.112      | -            | -                | -                | -         |     0.94 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4139 | 2024-02-18 | FlyQuest           | L   | 0.105      | -            | -                | -                | -         |    -0.20 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4154 | 2024-02-18 | Vantage            | W   | 0.100      | -            | -                | -                | -         |     1.44 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4159 | 2024-02-18 | gfg123321          | W   | 0.099      | -            | -                | -                | -         |     0.53 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,183.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
