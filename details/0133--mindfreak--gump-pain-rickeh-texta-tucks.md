### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  771.8<br />
<br />
Final Rank Value (771.8) = Starting Rank Value (684.6) + Head To Head Adjustments (87.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 684.6
- 400 + ( ( 0.138 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 684.6


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
|           26 |       64 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.228 (0.033)    | 0 (0.000) |    10.42 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      109 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.04 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      329 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.138 (0.046)    | 0 (0.000) |     9.87 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      334 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.138 (0.046)    | 0 (0.000) |    10.66 | gump, pain, Rickeh, Texta, tucks    |
|           22 |      520 | 2024-07-18 | MANTRA             | W   | 1.000      | 0.333        | -                | 0.039 (0.013)    | 0 (0.000) |     7.55 | gump, pain, Sliimey, supar, tucks   |
|           21 |      526 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.06 | gump, pain, Sliimey, supar, tucks   |
|           20 |      640 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.34 | gump, pain, Sliimey, supar, tucks   |
|           19 |      646 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.07 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1210 | 2024-06-08 | FlyQuest           | L   | 0.838      | -            | -                | -                | -         |    -1.92 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1272 | 2024-06-07 | Bad News Kangaroos | W   | 0.831      | 0.333        | 0.003 (0.001)    | 0.144 (0.040)    | 0 (0.000) |    11.99 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1343 | 2024-06-06 | Vantage            | W   | 0.824      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.72 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1764 | 2024-05-22 | FlyQuest           | L   | 0.725      | -            | -                | -                | -         |    -1.27 | gump, pain, Sliimey, supar, tucks   |
|           14 |     1769 | 2024-05-22 | FlyQuest           | L   | 0.724      | -            | -                | -                | -         |    -1.29 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2242 | 2024-05-08 | Arcade             | W   | 0.631      | 0.333        | 0.003 (0.001)    | 0.138 (0.029)    | 0 (0.000) |     7.87 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2245 | 2024-05-08 | Arcade             | W   | 0.631      | 0.333        | 0.003 (0.001)    | 0.138 (0.029)    | 0 (0.000) |     8.30 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2581 | 2024-04-22 | Vantage            | W   | 0.525      | 0.333        | 0.002 (0.000)    | 0.075 (0.013)    | -         |     7.43 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2583 | 2024-04-22 | Vantage            | W   | 0.525      | 0.333        | 0.002 (0.000)    | 0.075 (0.013)    | -         |     7.79 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2684 | 2024-04-19 | Bad News Kangaroos | L   | 0.505      | -            | -                | -                | -         |    -6.12 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2690 | 2024-04-18 | FlyQuest           | L   | 0.504      | -            | -                | -                | -         |    -0.96 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2743 | 2024-04-18 | DXA                | W   | 0.497      | 0.143        | -                | 0.228 (0.016)    | -         |     7.10 | gump, pain, Sliimey, supar, tucks   |
|            6 |     2769 | 2024-04-17 | KZG                | W   | 0.491      | 0.143        | 0.006 (0.000)    | -                | -         |     7.66 | gump, pain, Sliimey, supar, tucks   |
|            5 |     4114 | 2024-02-20 | Vantage            | L   | 0.112      | -            | -                | -                | -         |    -1.91 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4119 | 2024-02-20 | RKON               | W   | 0.111      | -            | -                | -                | -         |     0.92 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4143 | 2024-02-18 | FlyQuest           | L   | 0.104      | -            | -                | -                | -         |    -0.20 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4158 | 2024-02-18 | Vantage            | W   | 0.098      | -            | -                | -                | -         |     1.42 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4163 | 2024-02-18 | gfg123321          | W   | 0.098      | -            | -                | -                | -         |     0.52 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,181.06)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
