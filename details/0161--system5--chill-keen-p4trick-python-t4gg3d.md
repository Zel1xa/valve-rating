### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  690.0<br />
<br />
Final Rank Value (690.0) = Starting Rank Value (678.4) + Head To Head Adjustments (11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.4
- 400 + ( ( 0.135 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 678.4


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
|           12 |      890 | 2024-06-16 | EYEBALLERS | L   | 0.895      | -            | -                | -                | -         |    -7.17 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |      918 | 2024-06-15 | RUBY       | W   | 0.888      | 0.143        | 0.097 (0.012)    | 0.544 (0.069)    | 0 (0.000) |    21.57 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |      952 | 2024-06-14 | Nemiga     | L   | 0.881      | -            | -                | -                | -         |    -1.86 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1736 | 2024-05-22 | PERA       | L   | 0.728      | -            | -                | -                | -         |    -4.13 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1793 | 2024-05-21 | Space      | L   | 0.722      | -            | -                | -                | -         |    -6.15 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2079 | 2024-05-14 | Norway     | W   | 0.675      | 0.500        | 0.006 (0.002)    | 0.106 (0.036)    | 0 (0.000) |    11.51 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2626 | 2024-04-20 | 9INE       | W   | 0.514      | 0.500        | 0.000 (0.000)    | 0.093 (0.024)    | 0 (0.000) |     4.81 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3151 | 2024-04-03 | Betera     | L   | 0.402      | -            | -                | -                | -         |    -5.67 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3242 | 2024-03-29 | RUSH B     | L   | 0.369      | -            | -                | -                | -         |    -3.27 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3331 | 2024-03-26 | Monte      | L   | 0.349      | -            | -                | -                | -         |    -1.47 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3566 | 2024-03-13 | SAW        | L   | 0.262      | -            | -                | -                | -         |    -0.44 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     3954 | 2024-02-26 | PERA       | W   | 0.155      | 0.500        | 0.048 (0.004)    | 0.452 (0.035)    | 0 (0.000) |     3.91 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($423.85)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
