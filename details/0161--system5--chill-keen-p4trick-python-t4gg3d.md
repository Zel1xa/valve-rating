### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  685.6<br />
<br />
Final Rank Value (685.6) = Starting Rank Value (674.3) + Head To Head Adjustments (11.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.3
- 400 + ( ( 0.134 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 674.3


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
|           12 |     1022 | 2024-06-16 | EYEBALLERS | L   | 0.864      | -            | -                | -                | -         |    -6.88 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |     1052 | 2024-06-15 | RUBY       | W   | 0.858      | 0.143        | 0.095 (0.012)    | 0.491 (0.060)    | 0 (0.000) |    20.95 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     1093 | 2024-06-14 | Nemiga     | L   | 0.851      | -            | -                | -                | -         |    -1.65 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1859 | 2024-05-22 | PERA       | L   | 0.698      | -            | -                | -                | -         |    -3.87 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1902 | 2024-05-21 | Space      | L   | 0.691      | -            | -                | -                | -         |    -5.99 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2170 | 2024-05-14 | Norway     | W   | 0.645      | 0.500        | 0.006 (0.002)    | 0.106 (0.034)    | 0 (0.000) |    10.97 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2703 | 2024-04-20 | 9INE       | W   | 0.483      | 0.500        | 0.000 (0.000)    | 0.066 (0.016)    | 0 (0.000) |     4.60 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3221 | 2024-04-03 | Betera     | L   | 0.371      | -            | -                | -                | -         |    -5.27 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3306 | 2024-03-29 | RUSH B     | L   | 0.338      | -            | -                | -                | -         |    -2.79 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3392 | 2024-03-26 | Monte      | L   | 0.318      | -            | -                | -                | -         |    -1.47 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3620 | 2024-03-13 | SAW        | L   | 0.232      | -            | -                | -                | -         |    -0.42 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     4000 | 2024-02-26 | PERA       | W   | 0.125      | 0.500        | 0.048 (0.003)    | 0.445 (0.028)    | 0 (0.000) |     3.16 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($408.72)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
