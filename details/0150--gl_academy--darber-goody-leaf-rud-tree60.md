### Roster Details<br />
Team Name: GL Academy<br />
Roster: darber, Goody, leaf, rud, Tree60<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  723.1<br />
<br />
Final Rank Value (723.1) = Starting Rank Value (732.7) + Head To Head Adjustments (-9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.7
- 400 + ( ( 0.162 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 732.7


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
|           12 |      641 | 2024-07-18 | Astralis Talent | L   | 1.000      | -            | -                | -                | -         |   -16.33 | darber, Goody, leaf, rud, Tree60 |
|           11 |      702 | 2024-07-17 | K10             | L   | 1.000      | -            | -                | -                | -         |   -17.54 | darber, Goody, leaf, rud, Tree60 |
|           10 |     1566 | 2024-06-03 | PERA            | L   | 0.780      | -            | -                | -                | -         |    -6.43 | darber, Goody, leaf, rud, Tree60 |
|            9 |     1725 | 2024-05-28 | UNiTY           | W   | 0.740      | 0.379        | 0.025 (0.007)    | 0.300 (0.084)    | 0 (0.000) |    17.21 | darber, Goody, leaf, rud, Tree60 |
|            8 |     1817 | 2024-05-23 | brazylijski luz | L   | 0.707      | -            | -                | -                | -         |    -8.67 | darber, Goody, leaf, rud, Tree60 |
|            7 |     2381 | 2024-05-05 | MOUZ NXT        | L   | 0.585      | -            | -                | -                | -         |    -3.33 | darber, Goody, leaf, rud, shadiy |
|            6 |     2391 | 2024-05-04 | B8              | L   | 0.579      | -            | -                | -                | -         |    -3.09 | darber, Goody, leaf, rud, shadiy |
|            5 |     2463 | 2024-05-01 | RUBY            | W   | 0.558      | 0.435        | 0.095 (0.023)    | 0.492 (0.119)    | 0 (0.000) |    12.73 | darber, Goody, leaf, rud, shadiy |
|            4 |     2467 | 2024-04-30 | Sampi           | L   | 0.554      | -            | -                | -                | -         |    -4.96 | darber, Goody, leaf, rud, sSen   |
|            3 |     2552 | 2024-04-27 | K10             | W   | 0.531      | 0.143        | 0.008 (0.001)    | 0.132 (0.010)    | 0 (0.000) |     6.94 | darber, Goody, leaf, rud, sSen   |
|            2 |     3298 | 2024-03-30 | NAVI Junior     | W   | 0.345      | 0.333        | 0.003 (0.000)    | 0.029 (0.003)    | 0 (0.000) |     4.84 | darber, Goody, leaf, nestee, rud |
|            1 |     3326 | 2024-03-28 | Passion UA      | W   | 0.332      | 0.333        | 0.173 (0.019)    | 1.000 (0.111)    | 0 (0.000) |     9.06 | darber, Goody, leaf, nestee, rud |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,071.67)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
