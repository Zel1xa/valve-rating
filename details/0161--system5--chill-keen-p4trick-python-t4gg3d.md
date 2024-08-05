### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  685.7<br />
<br />
Final Rank Value (685.7) = Starting Rank Value (674.3) + Head To Head Adjustments (11.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
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
|           12 |     1019 | 2024-06-16 | EYEBALLERS | L   | 0.867      | -            | -                | -                | -         |    -6.91 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |     1049 | 2024-06-15 | RUBY       | W   | 0.860      | 0.143        | 0.095 (0.012)    | 0.492 (0.060)    | 0 (0.000) |    21.00 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |     1090 | 2024-06-14 | Nemiga     | L   | 0.853      | -            | -                | -                | -         |    -1.65 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1856 | 2024-05-22 | PERA       | L   | 0.700      | -            | -                | -                | -         |    -3.88 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1899 | 2024-05-21 | Space      | L   | 0.694      | -            | -                | -                | -         |    -6.01 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2167 | 2024-05-14 | Norway     | W   | 0.647      | 0.500        | 0.006 (0.002)    | 0.106 (0.034)    | 0 (0.000) |    11.01 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2700 | 2024-04-20 | 9INE       | W   | 0.486      | 0.500        | 0.000 (0.000)    | 0.066 (0.016)    | 0 (0.000) |     4.62 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3218 | 2024-04-03 | Betera     | L   | 0.374      | -            | -                | -                | -         |    -5.30 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3303 | 2024-03-29 | RUSH B     | L   | 0.341      | -            | -                | -                | -         |    -2.81 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3389 | 2024-03-26 | Monte      | L   | 0.321      | -            | -                | -                | -         |    -1.47 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3617 | 2024-03-13 | SAW        | L   | 0.234      | -            | -                | -                | -         |    -0.43 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     3997 | 2024-02-26 | PERA       | W   | 0.127      | 0.500        | 0.048 (0.003)    | 0.446 (0.028)    | 0 (0.000) |     3.22 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($409.83)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
