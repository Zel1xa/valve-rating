### Roster Details<br />
Team Name: GL Academy<br />
Roster: darber, Goody, leaf, rud, Tree60<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  723.5<br />
<br />
Final Rank Value (723.5) = Starting Rank Value (733.0) + Head To Head Adjustments (-9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 733.0
- 400 + ( ( 0.163 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 733.0


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
|           12 |      584 | 2024-07-18 | Astralis Talent | L   | 1.000      | -            | -                | -                | -         |   -16.37 | darber, Goody, leaf, rud, Tree60 |
|           11 |      645 | 2024-07-17 | K10             | L   | 1.000      | -            | -                | -                | -         |   -17.57 | darber, Goody, leaf, rud, Tree60 |
|           10 |     1509 | 2024-06-03 | PERA            | L   | 0.789      | -            | -                | -                | -         |    -6.57 | darber, Goody, leaf, rud, Tree60 |
|            9 |     1668 | 2024-05-28 | UNiTY           | W   | 0.749      | 0.379        | 0.025 (0.007)    | 0.305 (0.087)    | 0 (0.000) |    17.25 | darber, Goody, leaf, rud, Tree60 |
|            8 |     1760 | 2024-05-23 | brazylijski luz | L   | 0.715      | -            | -                | -                | -         |    -8.81 | darber, Goody, leaf, rud, Tree60 |
|            7 |     2324 | 2024-05-05 | MOUZ NXT        | L   | 0.593      | -            | -                | -                | -         |    -3.46 | darber, Goody, leaf, rud, shadiy |
|            6 |     2334 | 2024-05-04 | B8              | L   | 0.587      | -            | -                | -                | -         |    -3.18 | darber, Goody, leaf, rud, shadiy |
|            5 |     2406 | 2024-05-01 | RUBY            | W   | 0.566      | 0.435        | 0.095 (0.023)    | 0.502 (0.124)    | 0 (0.000) |    12.99 | darber, Goody, leaf, rud, shadiy |
|            4 |     2410 | 2024-04-30 | Sampi           | L   | 0.563      | -            | -                | -                | -         |    -5.04 | darber, Goody, leaf, rud, sSen   |
|            3 |     2495 | 2024-04-27 | K10             | W   | 0.540      | 0.143        | 0.008 (0.001)    | 0.133 (0.010)    | 0 (0.000) |     7.03 | darber, Goody, leaf, rud, sSen   |
|            2 |     3241 | 2024-03-30 | NAVI Junior     | W   | 0.354      | 0.333        | 0.003 (0.000)    | 0.031 (0.004)    | 0 (0.000) |     4.96 | darber, Goody, leaf, nestee, rud |
|            1 |     3269 | 2024-03-28 | Passion UA      | W   | 0.341      | 0.333        | 0.172 (0.020)    | 1.000 (0.114)    | 0 (0.000) |     9.24 | darber, Goody, leaf, nestee, rud |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,123.33)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
