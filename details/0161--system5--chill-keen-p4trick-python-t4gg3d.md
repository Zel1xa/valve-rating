### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  685.4<br />
<br />
Final Rank Value (685.4) = Starting Rank Value (674.1) + Head To Head Adjustments (11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.1
- 400 + ( ( 0.134 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 674.1


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
|           12 |     1011 | 2024-06-16 | EYEBALLERS | L   | 0.868      | -            | -                | -                | -         |    -6.96 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |     1041 | 2024-06-15 | RUBY       | W   | 0.861      | 0.143        | 0.095 (0.012)    | 0.499 (0.061)    | 0 (0.000) |    20.97 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     1082 | 2024-06-14 | Nemiga     | L   | 0.854      | -            | -                | -                | -         |    -1.66 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1848 | 2024-05-22 | PERA       | L   | 0.701      | -            | -                | -                | -         |    -3.87 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1891 | 2024-05-21 | Space      | L   | 0.695      | -            | -                | -                | -         |    -6.01 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2159 | 2024-05-14 | Norway     | W   | 0.648      | 0.500        | 0.006 (0.002)    | 0.107 (0.035)    | 0 (0.000) |    11.03 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2692 | 2024-04-20 | 9INE       | W   | 0.487      | 0.500        | 0.000 (0.000)    | 0.067 (0.016)    | 0 (0.000) |     4.63 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3210 | 2024-04-03 | Betera     | L   | 0.375      | -            | -                | -                | -         |    -5.31 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3295 | 2024-03-29 | RUSH B     | L   | 0.342      | -            | -                | -                | -         |    -2.82 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3381 | 2024-03-26 | Monte      | L   | 0.322      | -            | -                | -                | -         |    -1.47 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3609 | 2024-03-13 | SAW        | L   | 0.235      | -            | -                | -                | -         |    -0.43 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     3989 | 2024-02-26 | PERA       | W   | 0.128      | 0.500        | 0.048 (0.003)    | 0.451 (0.029)    | 0 (0.000) |     3.25 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($410.38)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
