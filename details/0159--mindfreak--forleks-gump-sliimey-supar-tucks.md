### Roster Details<br />
Team Name: Mindfreak<br />
Roster: Forleks, gump, Sliimey, supar, tucks<br />
Global Rank: [159](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
<br />
Final Rank Value:  691.9<br />
<br />
Final Rank Value (691.9) = Starting Rank Value (669.1) + Head To Head Adjustments (22.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.1
- 400 + ( ( 0.131 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 669.1


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
|           12 |     2940 | 2024-04-10 | DXA                | W   | 0.446      | 0.333        | 0.002 (0.000)    | 0.228 (0.034)    | 0 (0.000) |     6.61 | Forleks, gump, Sliimey, supar, tucks |
|           11 |     2944 | 2024-04-10 | DXA                | W   | 0.446      | 0.333        | 0.002 (0.000)    | 0.228 (0.034)    | 0 (0.000) |     6.87 | Forleks, gump, Sliimey, supar, tucks |
|           10 |     3176 | 2024-04-03 | Canon Event        | W   | 0.399      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.36 | Forleks, gump, Sliimey, supar, tucks |
|            9 |     3181 | 2024-04-03 | Canon Event        | W   | 0.399      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.45 | Forleks, gump, Sliimey, supar, tucks |
|            8 |     3308 | 2024-03-27 | Bad News Kangaroos | W   | 0.353      | 0.333        | 0.017 (0.002)    | 0.111 (0.013)    | 0 (0.000) |     7.34 | Forleks, gump, Sliimey, supar, tucks |
|            7 |     3313 | 2024-03-27 | Bad News Kangaroos | L   | 0.353      | -            | -                | -                | -         |    -3.83 | Forleks, gump, Sliimey, supar, tucks |
|            6 |     3764 | 2024-03-06 | Rooster            | L   | 0.213      | -            | -                | -                | -         |    -2.27 | Forleks, gump, Sliimey, supar, tucks |
|            5 |     3770 | 2024-03-06 | Rooster            | L   | 0.213      | -            | -                | -                | -         |    -2.31 | Forleks, gump, Sliimey, supar, tucks |
|            4 |     4081 | 2024-02-21 | KZG                | W   | 0.120      | 0.333        | 0.006 (0.000)    | 0.113 (0.005)    | 0 (0.000) |     2.07 | Forleks, gump, Sliimey, supar, tucks |
|            3 |     4086 | 2024-02-21 | KZG                | W   | 0.119      | 0.333        | 0.006 (0.000)    | 0.113 (0.005)    | 0 (0.000) |     2.09 | Forleks, gump, Sliimey, supar, tucks |
|            2 |     4283 | 2024-02-13 | KZG                | L   | 0.072      | -            | -                | -                | -         |    -1.00 | deStiny, gump, Sliimey, supar, tucks |
|            1 |     4314 | 2024-02-13 | DEMESIS            | W   | 0.066      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.38 | deStiny, gump, Sliimey, supar, tucks |

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
