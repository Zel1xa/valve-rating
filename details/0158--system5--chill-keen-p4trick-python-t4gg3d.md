### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [158](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  690.2<br />
<br />
Final Rank Value (690.2) = Starting Rank Value (678.2) + Head To Head Adjustments (12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.2
- 400 + ( ( 0.135 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 678.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      845 | 2024-06-16 | EYEBALLERS | L   | 0.899      | -            | -                | -                | -         |    -7.18 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |      875 | 2024-06-15 | RUBY       | W   | 0.892      | 0.143        | 0.096 (0.012)    | 0.506 (0.065)    | 0 (0.000) |    21.65 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |      916 | 2024-06-14 | Nemiga     | L   | 0.886      | -            | -                | -                | -         |    -1.78 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1682 | 2024-05-22 | PERA       | L   | 0.733      | -            | -                | -                | -         |    -4.05 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1725 | 2024-05-21 | Space      | L   | 0.726      | -            | -                | -                | -         |    -6.19 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     1993 | 2024-05-14 | Norway     | W   | 0.679      | 0.500        | 0.006 (0.002)    | 0.106 (0.036)    | 0 (0.000) |    11.60 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2526 | 2024-04-20 | 9INE       | W   | 0.518      | 0.500        | 0.000 (0.000)    | 0.067 (0.017)    | 0 (0.000) |     4.87 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3044 | 2024-04-03 | Betera     | L   | 0.406      | -            | -                | -                | -         |    -5.71 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3129 | 2024-03-29 | RUSH B     | L   | 0.373      | -            | -                | -                | -         |    -3.34 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3215 | 2024-03-26 | Monte      | L   | 0.353      | -            | -                | -                | -         |    -1.47 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3443 | 2024-03-13 | SAW        | L   | 0.266      | -            | -                | -                | -         |    -0.45 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     3823 | 2024-02-26 | PERA       | W   | 0.160      | 0.500        | 0.048 (0.004)    | 0.452 (0.036)    | 0 (0.000) |     4.04 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($426.02)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
