### Roster Details<br />
Team Name: GL Academy<br />
Roster: darber, Goody, leaf, rud, Tree60<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  652.6<br />
<br />
Final Rank Value (652.6) = Starting Rank Value (674.3) + Head To Head Adjustments (-21.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.3
- 400 + ( ( 0.142 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 674.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |       22 | 2024-09-07 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -3.56 | darber, Goody, leaf, rud, Tree60 |
|           13 |       77 | 2024-09-05 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |    -4.43 | darber, Goody, leaf, rud, Tree60 |
|           12 |     1780 | 2024-07-18 | Astralis Talent | L   | 0.853      | -            | -                | -                | -         |   -13.45 | darber, Goody, leaf, rud, Tree60 |
|           11 |     1841 | 2024-07-17 | K10             | L   | 0.847      | -            | -                | -                | -         |   -13.75 | darber, Goody, leaf, rud, Tree60 |
|           10 |     2708 | 2024-06-03 | Qiang           | L   | 0.555      | -            | -                | -                | -         |    -4.27 | darber, Goody, leaf, rud, Tree60 |
|            9 |     2867 | 2024-05-28 | UNiTY           | W   | 0.515      | 0.379        | 0.026 (0.005)    | 0.394 (0.077)    | 0 (0.000) |    12.19 | darber, Goody, leaf, rud, Tree60 |
|            8 |     2959 | 2024-05-23 | Apogee          | L   | 0.481      | -            | -                | -                | -         |    -6.01 | darber, Goody, leaf, rud, Tree60 |
|            7 |     3523 | 2024-05-05 | MOUZ NXT        | L   | 0.359      | -            | -                | -                | -         |    -1.89 | darber, Goody, leaf, rud, shadiy |
|            6 |     3533 | 2024-05-04 | B8              | L   | 0.353      | -            | -                | -                | -         |    -1.38 | darber, Goody, leaf, rud, shadiy |
|            5 |     3605 | 2024-05-01 | RUBY            | W   | 0.332      | 0.435        | 0.073 (0.011)    | 0.390 (0.056)    | 0 (0.000) |     7.84 | darber, Goody, leaf, rud, shadiy |
|            4 |     3609 | 2024-04-30 | Sampi           | L   | 0.328      | -            | -                | -                | -         |    -2.32 | darber, Goody, leaf, rud, sSen   |
|            3 |     3694 | 2024-04-27 | K10             | W   | 0.306      | 0.143        | 0.006 (0.000)    | 0.096 (0.004)    | 0 (0.000) |     4.51 | darber, Goody, leaf, rud, sSen   |
|            2 |     4440 | 2024-03-30 | NAVI Junior     | W   | 0.120      | 0.333        | 0.001 (0.000)    | 0.144 (0.006)    | 0 (0.000) |     1.90 | darber, Goody, leaf, nestee, rud |
|            1 |     4468 | 2024-03-28 | Passion UA      | W   | 0.106      | 0.333        | 0.164 (0.006)    | 1.000 (0.035)    | 0 (0.000) |     2.94 | darber, Goody, leaf, nestee, rud |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($718.33)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
