### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  685.8<br />
<br />
Final Rank Value (685.8) = Starting Rank Value (674.2) + Head To Head Adjustments (11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.2
- 400 + ( ( 0.134 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 674.2


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
|           12 |     1026 | 2024-06-16 | EYEBALLERS | L   | 0.862      | -            | -                | -                | -         |    -6.76 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |     1056 | 2024-06-15 | RUBY       | W   | 0.855      | 0.143        | 0.095 (0.012)    | 0.491 (0.060)    | 0 (0.000) |    20.99 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     1097 | 2024-06-14 | Nemiga     | L   | 0.849      | -            | -                | -                | -         |    -1.64 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1863 | 2024-05-22 | PERA       | L   | 0.696      | -            | -                | -                | -         |    -3.85 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1906 | 2024-05-21 | Space      | L   | 0.689      | -            | -                | -                | -         |    -5.89 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2174 | 2024-05-14 | Norway     | W   | 0.642      | 0.500        | 0.006 (0.002)    | 0.106 (0.034)    | 0 (0.000) |    10.93 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2707 | 2024-04-20 | 9INE       | W   | 0.481      | 0.500        | 0.000 (0.000)    | 0.066 (0.016)    | 0 (0.000) |     4.58 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3225 | 2024-04-03 | Betera     | L   | 0.369      | -            | -                | -                | -         |    -5.23 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3310 | 2024-03-29 | RUSH B     | L   | 0.336      | -            | -                | -                | -         |    -2.76 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3396 | 2024-03-26 | Monte      | L   | 0.316      | -            | -                | -                | -         |    -1.46 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3624 | 2024-03-13 | SAW        | L   | 0.229      | -            | -                | -                | -         |    -0.42 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     4004 | 2024-02-26 | PERA       | W   | 0.122      | 0.500        | 0.048 (0.003)    | 0.445 (0.027)    | 0 (0.000) |     3.10 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($407.47)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
