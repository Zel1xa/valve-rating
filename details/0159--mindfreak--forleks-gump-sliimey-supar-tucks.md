### Roster Details<br />
Team Name: Mindfreak<br />
Roster: Forleks, gump, Sliimey, supar, tucks<br />
Global Rank: [159](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  687.8<br />
<br />
Final Rank Value (687.8) = Starting Rank Value (666.2) + Head To Head Adjustments (21.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.2
- 400 + ( ( 0.130 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 666.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2881 | 2024-04-10 | DXA                | W   | 0.431      | 0.333        | 0.002 (0.000)    | 0.235 (0.034)    | 0 (0.000) |     6.41 | Forleks, gump, Sliimey, supar, tucks |
|           11 |     2885 | 2024-04-10 | DXA                | W   | 0.431      | 0.333        | 0.002 (0.000)    | 0.235 (0.034)    | 0 (0.000) |     6.66 | Forleks, gump, Sliimey, supar, tucks |
|           10 |     3111 | 2024-04-03 | Canon Event        | W   | 0.385      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.29 | Forleks, gump, Sliimey, supar, tucks |
|            9 |     3116 | 2024-04-03 | Canon Event        | W   | 0.384      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.38 | Forleks, gump, Sliimey, supar, tucks |
|            8 |     3238 | 2024-03-27 | Bad News Kangaroos | W   | 0.338      | 0.333        | 0.017 (0.002)    | 0.112 (0.013)    | 0 (0.000) |     6.98 | Forleks, gump, Sliimey, supar, tucks |
|            7 |     3243 | 2024-03-27 | Bad News Kangaroos | L   | 0.338      | -            | -                | -                | -         |    -3.73 | Forleks, gump, Sliimey, supar, tucks |
|            6 |     3678 | 2024-03-06 | Rooster            | L   | 0.198      | -            | -                | -                | -         |    -2.14 | Forleks, gump, Sliimey, supar, tucks |
|            5 |     3684 | 2024-03-06 | Rooster            | L   | 0.198      | -            | -                | -                | -         |    -2.17 | Forleks, gump, Sliimey, supar, tucks |
|            4 |     3980 | 2024-02-21 | KZG                | W   | 0.105      | 0.333        | 0.005 (0.000)    | 0.116 (0.004)    | 0 (0.000) |     1.73 | Forleks, gump, Sliimey, supar, tucks |
|            3 |     3985 | 2024-02-21 | KZG                | W   | 0.105      | 0.333        | 0.005 (0.000)    | 0.116 (0.004)    | 0 (0.000) |     1.74 | Forleks, gump, Sliimey, supar, tucks |
|            2 |     4181 | 2024-02-13 | KZG                | L   | 0.057      | -            | -                | -                | -         |    -0.85 | deStiny, gump, Sliimey, supar, tucks |
|            1 |     4204 | 2024-02-13 | DEMESIS            | W   | 0.051      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.30 | deStiny, gump, Sliimey, supar, tucks |

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
