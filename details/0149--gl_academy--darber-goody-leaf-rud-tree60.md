### Roster Details<br />
Team Name: GL Academy<br />
Roster: darber, Goody, leaf, rud, Tree60<br />
Global Rank: [149](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  722.8<br />
<br />
Final Rank Value (722.8) = Starting Rank Value (732.4) + Head To Head Adjustments (-9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.4
- 400 + ( ( 0.162 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 732.4


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
|           12 |      648 | 2024-07-18 | Astralis Talent | L   | 1.000      | -            | -                | -                | -         |   -16.30 | darber, Goody, leaf, rud, Tree60 |
|           11 |      709 | 2024-07-17 | K10             | L   | 1.000      | -            | -                | -                | -         |   -17.52 | darber, Goody, leaf, rud, Tree60 |
|           10 |     1573 | 2024-06-03 | PERA            | L   | 0.776      | -            | -                | -                | -         |    -6.38 | darber, Goody, leaf, rud, Tree60 |
|            9 |     1732 | 2024-05-28 | UNiTY           | W   | 0.736      | 0.379        | 0.024 (0.007)    | 0.300 (0.083)    | 0 (0.000) |    17.10 | darber, Goody, leaf, rud, Tree60 |
|            8 |     1824 | 2024-05-23 | brazylijski luz | L   | 0.702      | -            | -                | -                | -         |    -8.62 | darber, Goody, leaf, rud, Tree60 |
|            7 |     2388 | 2024-05-05 | MOUZ NXT        | L   | 0.580      | -            | -                | -                | -         |    -3.29 | darber, Goody, leaf, rud, shadiy |
|            6 |     2398 | 2024-05-04 | B8              | L   | 0.574      | -            | -                | -                | -         |    -3.05 | darber, Goody, leaf, rud, shadiy |
|            5 |     2470 | 2024-05-01 | RUBY            | W   | 0.553      | 0.435        | 0.095 (0.023)    | 0.491 (0.118)    | 0 (0.000) |    12.75 | darber, Goody, leaf, rud, shadiy |
|            4 |     2474 | 2024-04-30 | Sampi           | L   | 0.549      | -            | -                | -                | -         |    -4.89 | darber, Goody, leaf, rud, sSen   |
|            3 |     2559 | 2024-04-27 | K10             | W   | 0.526      | 0.143        | 0.008 (0.001)    | 0.132 (0.010)    | 0 (0.000) |     6.90 | darber, Goody, leaf, rud, sSen   |
|            2 |     3305 | 2024-03-30 | NAVI Junior     | W   | 0.341      | 0.333        | 0.003 (0.000)    | 0.029 (0.003)    | 0 (0.000) |     4.78 | darber, Goody, leaf, nestee, rud |
|            1 |     3333 | 2024-03-28 | Passion UA      | W   | 0.327      | 0.333        | 0.173 (0.019)    | 1.000 (0.109)    | 0 (0.000) |     8.95 | darber, Goody, leaf, nestee, rud |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,043.33)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
