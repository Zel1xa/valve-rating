### Roster Details<br />
Team Name: System5<br />
Roster: Chill, keen, P4TriCK, Python, T4gg3D<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  686.6<br />
<br />
Final Rank Value (686.6) = Starting Rank Value (675.0) + Head To Head Adjustments (11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.0
- 400 + ( ( 0.134 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 675.0


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
|           12 |      922 | 2024-06-16 | EYEBALLERS | L   | 0.880      | -            | -                | -                | -         |    -7.04 | Chill, keen, P4TriCK, Python, T4gg3D |
|           11 |      947 | 2024-06-15 | RUBY       | W   | 0.873      | 0.143        | 0.095 (0.012)    | 0.520 (0.065)    | 0 (0.000) |    21.44 | Chill, keen, P4TriCK, Python, T4gg3D |
|           10 |      981 | 2024-06-14 | Nemiga     | L   | 0.867      | -            | -                | -                | -         |    -1.79 | Chill, keen, P4TriCK, Python, T4gg3D |
|            9 |     1731 | 2024-05-22 | PERA       | L   | 0.714      | -            | -                | -                | -         |    -4.01 | Chill, keen, P4TriCK, Python, T4gg3D |
|            8 |     1774 | 2024-05-21 | Space      | L   | 0.707      | -            | -                | -                | -         |    -5.99 | Chill, keen, P4TriCK, Python, T4gg3D |
|            7 |     2041 | 2024-05-14 | Norway     | W   | 0.660      | 0.500        | 0.006 (0.002)    | 0.110 (0.036)    | 0 (0.000) |    11.22 | Chill, keen, P4TriCK, Python, T4gg3D |
|            6 |     2572 | 2024-04-20 | 9INE       | W   | 0.499      | 0.500        | 0.000 (0.000)    | 0.069 (0.017)    | 0 (0.000) |     4.73 | Chill, keen, P4TriCK, Python, T4gg3D |
|            5 |     3090 | 2024-04-03 | Betera     | L   | 0.387      | -            | -                | -                | -         |    -5.47 | Chill, keen, P4TriCK, Python, shadiy |
|            4 |     3175 | 2024-03-29 | RUSH B     | L   | 0.354      | -            | -                | -                | -         |    -3.07 | Chill, keen, P4TriCK, Python, shadiy |
|            3 |     3258 | 2024-03-26 | Monte      | L   | 0.334      | -            | -                | -                | -         |    -1.48 | Chill, keen, krii, P4TriCK, Python   |
|            2 |     3483 | 2024-03-13 | SAW        | L   | 0.247      | -            | -                | -                | -         |    -0.44 | Chill, keen, krii, P4TriCK, Python   |
|            1 |     3861 | 2024-02-26 | PERA       | W   | 0.141      | 0.500        | 0.048 (0.003)    | 0.468 (0.033)    | 0 (0.000) |     3.54 | Chill, keen, krii, P4TriCK, Python   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($416.52)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
