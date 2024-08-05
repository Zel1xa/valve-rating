### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
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
- 400 + ( ( 0.134 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 674.1


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
|           12 |      998 | 2024-06-16 | EYEBALLERS | L   | 0.871      | -            | -                | -                | -         |    -6.99 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |     1028 | 2024-06-15 | RUBY       | W   | 0.864      | 0.143        | 0.095 (0.012)    | 0.501 (0.062)    | 0 (0.000) |    20.97 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     1069 | 2024-06-14 | Nemiga     | L   | 0.858      | -            | -                | -                | -         |    -1.66 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1835 | 2024-05-22 | PERA       | L   | 0.705      | -            | -                | -                | -         |    -3.90 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1878 | 2024-05-21 | Space      | L   | 0.698      | -            | -                | -                | -         |    -6.04 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2146 | 2024-05-14 | Norway     | W   | 0.651      | 0.500        | 0.006 (0.002)    | 0.107 (0.035)    | 0 (0.000) |    11.09 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2679 | 2024-04-20 | 9INE       | W   | 0.490      | 0.500        | 0.000 (0.000)    | 0.067 (0.016)    | 0 (0.000) |     4.66 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3197 | 2024-04-03 | Betera     | L   | 0.378      | -            | -                | -                | -         |    -5.36 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3282 | 2024-03-29 | RUSH B     | L   | 0.345      | -            | -                | -                | -         |    -2.85 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3368 | 2024-03-26 | Monte      | L   | 0.325      | -            | -                | -                | -         |    -1.48 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3596 | 2024-03-13 | SAW        | L   | 0.238      | -            | -                | -                | -         |    -0.43 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     3976 | 2024-02-26 | PERA       | W   | 0.132      | 0.500        | 0.048 (0.003)    | 0.453 (0.030)    | 0 (0.000) |     3.33 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($412.05)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
