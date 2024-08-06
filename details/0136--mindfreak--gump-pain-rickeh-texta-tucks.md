### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  768.5<br />
<br />
Final Rank Value (768.5) = Starting Rank Value (689.7) + Head To Head Adjustments (78.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
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
|           27 |      225 | 2024-07-31 | DXA                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.217 (0.031)    | 0 (0.000) |    11.02 | gump, pain, Rickeh, Texta, tucks    |
|           26 |      269 | 2024-07-30 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | gump, pain, Rickeh, Texta, tucks    |
|           25 |      489 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    10.58 | gump, pain, Rickeh, Texta, tucks    |
|           24 |      493 | 2024-07-23 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    11.46 | gump, pain, Rickeh, Texta, tucks    |
|           23 |      671 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.16 | gump, pain, Sliimey, supar, tucks   |
|           22 |      674 | 2024-07-18 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | gump, pain, Sliimey, supar, tucks   |
|           21 |      788 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -9.73 | gump, pain, Sliimey, supar, tucks   |
|           20 |      790 | 2024-07-16 | Rooster            | L   | 1.000      | -            | -                | -                | -         |   -10.51 | gump, pain, Sliimey, supar, tucks   |
|           19 |     1358 | 2024-06-08 | FlyQuest           | L   | 0.805      | -            | -                | -                | -         |    -2.08 | gump, pain, Sliimey, supar, tucks   |
|           18 |     1415 | 2024-06-07 | Bad News Kangaroos | W   | 0.798      | 0.333        | 0.016 (0.004)    | 0.217 (0.058)    | 0 (0.000) |    14.88 | gump, pain, Sliimey, supar, tucks   |
|           17 |     1483 | 2024-06-06 | Vantage            | W   | 0.792      | 0.333        | 0.002 (0.001)    | -                | 0 (0.000) |     6.39 | gump, pain, Sliimey, supar, tucks   |
|           16 |     1889 | 2024-05-22 | FlyQuest           | L   | 0.692      | -            | -                | -                | -         |    -1.39 | gump, pain, Sliimey, supar, tucks   |
|           15 |     1894 | 2024-05-22 | FlyQuest           | L   | 0.692      | -            | -                | -                | -         |    -1.41 | gump, pain, Sliimey, supar, tucks   |
|           14 |     2340 | 2024-05-08 | Arcade             | W   | 0.599      | 0.333        | 0.002 (0.000)    | 0.130 (0.026)    | 0 (0.000) |     7.55 | gump, pain, Sliimey, supar, tucks   |
|           13 |     2343 | 2024-05-08 | Arcade             | W   | 0.599      | 0.333        | 0.002 (0.000)    | 0.130 (0.026)    | 0 (0.000) |     7.95 | gump, pain, Sliimey, supar, tucks   |
|           12 |     2673 | 2024-04-22 | Vantage            | W   | 0.492      | 0.333        | 0.002 (0.000)    | 0.064 (0.011)    | -         |     6.82 | gump, pain, Sliimey, supar, tucks   |
|           11 |     2675 | 2024-04-22 | Vantage            | W   | 0.492      | 0.333        | 0.002 (0.000)    | 0.064 (0.011)    | -         |     7.12 | gump, pain, Sliimey, supar, tucks   |
|           10 |     2772 | 2024-04-19 | Bad News Kangaroos | L   | 0.472      | -            | -                | -                | -         |    -5.73 | gump, pain, Sliimey, supar, tucks   |
|            9 |     2778 | 2024-04-18 | FlyQuest           | L   | 0.471      | -            | -                | -                | -         |    -1.04 | gump, pain, Sliimey, supar, tucks   |
|            8 |     2830 | 2024-04-18 | DXA                | W   | 0.465      | 0.143        | -                | 0.217 (0.014)    | -         |     6.68 | gump, pain, Sliimey, supar, tucks   |
|            7 |     2855 | 2024-04-17 | KZG                | W   | 0.459      | 0.143        | 0.005 (0.000)    | 0.106 (0.007)    | -         |     7.03 | gump, pain, Sliimey, supar, tucks   |
|            6 |     4164 | 2024-02-20 | Vantage            | L   | 0.079      | -            | -                | -                | -         |    -1.38 | gump, Rickeh, Sliimey, supar, tucks |
|            5 |     4169 | 2024-02-20 | RKON               | W   | 0.078      | -            | -                | -                | -         |     0.63 | gump, Rickeh, Sliimey, supar, tucks |
|            4 |     4193 | 2024-02-18 | FlyQuest           | L   | 0.071      | -            | -                | -                | -         |    -0.16 | gump, Rickeh, Sliimey, supar, tucks |
|            3 |     4208 | 2024-02-18 | Vantage            | W   | 0.066      | -            | -                | -                | -         |     0.93 | gump, Rickeh, Sliimey, supar, tucks |
|            2 |     4209 | 2024-02-18 | Vantage            | W   | 0.066      | -            | -                | -                | -         |     0.92 | gump, Rickeh, Sliimey, supar, tucks |
|            1 |     4214 | 2024-02-18 | gfg123321          | W   | 0.065      | -            | -                | -                | -         |     0.34 | gump, Rickeh, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,135.43)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
