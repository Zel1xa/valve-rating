### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
<br />
Final Rank Value:  648.7<br />
<br />
Final Rank Value (648.7) = Starting Rank Value (640.5) + Head To Head Adjustments (8.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.249[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.5
- 400 + ( ( 0.124 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 640.5


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
|           11 |     2161 | 2024-06-16 | EYEBALLERS | L   | 0.641      | -            | -                | -                | -         |    -5.47 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     2191 | 2024-06-15 | RUBY       | W   | 0.634      | 0.143        | 0.073 (0.007)    | 0.390 (0.035)    | 0 (0.000) |    15.58 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     2232 | 2024-06-14 | Nemiga     | L   | 0.628      | -            | -                | -                | -         |    -1.08 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     2998 | 2024-05-22 | Qiang      | L   | 0.475      | -            | -                | -                | -         |    -2.90 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     3041 | 2024-05-21 | Space      | L   | 0.468      | -            | -                | -                | -         |    -3.90 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     3309 | 2024-05-14 | Norway     | W   | 0.421      | 0.500        | 0.003 (0.001)    | 0.069 (0.015)    | 0 (0.000) |     6.81 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3842 | 2024-04-20 | 9INE       | W   | 0.260      | 0.500        | 0.000 (0.000)    | 0.046 (0.006)    | 0 (0.000) |     2.72 | Chill, keen, P4TriCK, Python, T4gg3D |
|            4 |     4360 | 2024-04-03 | Betera     | L   | 0.148      | -            | -                | -                | -         |    -2.21 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     4445 | 2024-03-29 | RUSH B     | L   | 0.115      | -            | -                | -                | -         |    -0.87 | Chill, keen, P4TriCK, Python, shadiy |
|            2 |     4531 | 2024-03-26 | Monte      | L   | 0.095      | -            | -                | -                | -         |    -0.46 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     4759 | 2024-03-13 | SAW        | L   | 0.008      | -            | -                | -                | -         |    -0.00 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($297.05)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
