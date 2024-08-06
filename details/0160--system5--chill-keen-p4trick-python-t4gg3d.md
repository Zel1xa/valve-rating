### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  686.2<br />
<br />
Final Rank Value (686.2) = Starting Rank Value (674.7) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.7
- 400 + ( ( 0.134 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 674.7


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
|           12 |     1030 | 2024-06-16 | EYEBALLERS | L   | 0.862      | -            | -                | -                | -         |    -6.78 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |     1060 | 2024-06-15 | RUBY       | W   | 0.855      | 0.143        | 0.095 (0.012)    | 0.480 (0.059)    | 0 (0.000) |    20.97 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     1101 | 2024-06-14 | Nemiga     | L   | 0.848      | -            | -                | -                | -         |    -1.65 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1867 | 2024-05-22 | PERA       | L   | 0.695      | -            | -                | -                | -         |    -3.86 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1910 | 2024-05-21 | Space      | L   | 0.689      | -            | -                | -                | -         |    -5.91 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2178 | 2024-05-14 | Norway     | W   | 0.642      | 0.500        | 0.006 (0.002)    | 0.103 (0.033)    | 0 (0.000) |    10.93 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2711 | 2024-04-20 | 9INE       | W   | 0.481      | 0.500        | 0.000 (0.000)    | 0.064 (0.015)    | 0 (0.000) |     4.58 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3229 | 2024-04-03 | Betera     | L   | 0.369      | -            | -                | -                | -         |    -5.23 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3314 | 2024-03-29 | RUSH B     | L   | 0.336      | -            | -                | -                | -         |    -2.77 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3400 | 2024-03-26 | Monte      | L   | 0.316      | -            | -                | -                | -         |    -1.46 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3628 | 2024-03-13 | SAW        | L   | 0.229      | -            | -                | -                | -         |    -0.43 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     4008 | 2024-02-26 | PERA       | W   | 0.122      | 0.500        | 0.048 (0.003)    | 0.435 (0.027)    | 0 (0.000) |     3.09 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($407.33)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
