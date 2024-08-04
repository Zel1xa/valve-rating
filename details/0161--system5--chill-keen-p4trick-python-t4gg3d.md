### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  685.5<br />
<br />
Final Rank Value (685.5) = Starting Rank Value (674.2) + Head To Head Adjustments (11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.2
- 400 + ( ( 0.134 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 674.2


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
|           12 |      962 | 2024-06-16 | EYEBALLERS | L   | 0.875      | -            | -                | -                | -         |    -6.98 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |      992 | 2024-06-15 | RUBY       | W   | 0.869      | 0.143        | 0.095 (0.012)    | 0.502 (0.062)    | 0 (0.000) |    21.11 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     1033 | 2024-06-14 | Nemiga     | L   | 0.862      | -            | -                | -                | -         |    -1.79 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1799 | 2024-05-22 | PERA       | L   | 0.709      | -            | -                | -                | -         |    -3.97 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1842 | 2024-05-21 | Space      | L   | 0.702      | -            | -                | -                | -         |    -6.01 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2110 | 2024-05-14 | Norway     | W   | 0.656      | 0.500        | 0.006 (0.002)    | 0.107 (0.035)    | 0 (0.000) |    11.16 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2643 | 2024-04-20 | 9INE       | W   | 0.494      | 0.500        | 0.000 (0.000)    | 0.067 (0.016)    | 0 (0.000) |     4.70 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3161 | 2024-04-03 | Betera     | L   | 0.382      | -            | -                | -                | -         |    -5.41 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3246 | 2024-03-29 | RUSH B     | L   | 0.349      | -            | -                | -                | -         |    -3.06 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3332 | 2024-03-26 | Monte      | L   | 0.329      | -            | -                | -                | -         |    -1.48 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3560 | 2024-03-13 | SAW        | L   | 0.242      | -            | -                | -                | -         |    -0.44 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     3940 | 2024-02-26 | PERA       | W   | 0.136      | 0.500        | 0.048 (0.003)    | 0.453 (0.031)    | 0 (0.000) |     3.42 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($414.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
