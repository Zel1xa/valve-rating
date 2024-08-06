### Roster Details<br />
Team Name: Mindfreak<br />
Roster: Forleks, gump, Sliimey, supar, tucks<br />
Global Rank: [159](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
<br />
Final Rank Value:  687.8<br />
<br />
Final Rank Value (687.8) = Starting Rank Value (666.5) + Head To Head Adjustments (21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.5
- 400 + ( ( 0.130 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 666.5


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
|           12 |     3023 | 2024-04-10 | DXA                | W   | 0.413      | 0.333        | 0.002 (0.000)    | 0.217 (0.030)    | 0 (0.000) |     6.31 | Forleks, gump, Sliimey, supar, tucks |
|           11 |     3027 | 2024-04-10 | DXA                | W   | 0.412      | 0.333        | 0.002 (0.000)    | 0.217 (0.030)    | 0 (0.000) |     6.54 | Forleks, gump, Sliimey, supar, tucks |
|           10 |     3253 | 2024-04-03 | Canon Event        | W   | 0.366      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.16 | Forleks, gump, Sliimey, supar, tucks |
|            9 |     3258 | 2024-04-03 | Canon Event        | W   | 0.366      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.24 | Forleks, gump, Sliimey, supar, tucks |
|            8 |     3382 | 2024-03-27 | Bad News Kangaroos | W   | 0.320      | 0.333        | 0.016 (0.002)    | 0.217 (0.023)    | 0 (0.000) |     6.74 | Forleks, gump, Sliimey, supar, tucks |
|            7 |     3387 | 2024-03-27 | Bad News Kangaroos | L   | 0.319      | -            | -                | -                | -         |    -3.37 | Forleks, gump, Sliimey, supar, tucks |
|            6 |     3828 | 2024-03-06 | Rooster            | L   | 0.180      | -            | -                | -                | -         |    -1.93 | Forleks, gump, Sliimey, supar, tucks |
|            5 |     3834 | 2024-03-06 | Rooster            | L   | 0.179      | -            | -                | -                | -         |    -1.96 | Forleks, gump, Sliimey, supar, tucks |
|            4 |     4130 | 2024-02-21 | KZG                | W   | 0.086      | 0.333        | 0.005 (0.000)    | 0.106 (0.003)    | 0 (0.000) |     1.49 | Forleks, gump, Sliimey, supar, tucks |
|            3 |     4135 | 2024-02-21 | KZG                | W   | 0.086      | 0.333        | 0.005 (0.000)    | 0.106 (0.003)    | 0 (0.000) |     1.50 | Forleks, gump, Sliimey, supar, tucks |
|            2 |     4332 | 2024-02-13 | KZG                | L   | 0.039      | -            | -                | -                | -         |    -0.54 | deStiny, gump, Sliimey, supar, tucks |
|            1 |     4355 | 2024-02-13 | DEMESIS            | W   | 0.033      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.19 | deStiny, gump, Sliimey, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,136.20)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
