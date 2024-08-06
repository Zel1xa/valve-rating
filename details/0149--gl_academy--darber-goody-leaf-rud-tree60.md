### Roster Details<br />
Team Name: GL Academy<br />
Roster: darber, Goody, leaf, rud, Tree60<br />
Global Rank: [149](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  724.2<br />
<br />
Final Rank Value (724.2) = Starting Rank Value (733.8) + Head To Head Adjustments (-9.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 733.8
- 400 + ( ( 0.162 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 733.8


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
|           12 |      650 | 2024-07-18 | Astralis Talent | L   | 1.000      | -            | -                | -                | -         |   -16.30 | darber, Goody, leaf, rud, Tree60 |
|           11 |      711 | 2024-07-17 | K10             | L   | 1.000      | -            | -                | -                | -         |   -17.55 | darber, Goody, leaf, rud, Tree60 |
|           10 |     1575 | 2024-06-03 | PERA            | L   | 0.775      | -            | -                | -                | -         |    -6.41 | darber, Goody, leaf, rud, Tree60 |
|            9 |     1734 | 2024-05-28 | UNiTY           | W   | 0.735      | 0.379        | 0.024 (0.007)    | 0.331 (0.092)    | 0 (0.000) |    17.03 | darber, Goody, leaf, rud, Tree60 |
|            8 |     1826 | 2024-05-23 | brazylijski luz | L   | 0.701      | -            | -                | -                | -         |    -8.66 | darber, Goody, leaf, rud, Tree60 |
|            7 |     2390 | 2024-05-05 | MOUZ NXT        | L   | 0.579      | -            | -                | -                | -         |    -3.31 | darber, Goody, leaf, rud, shadiy |
|            6 |     2400 | 2024-05-04 | B8              | L   | 0.573      | -            | -                | -                | -         |    -3.05 | darber, Goody, leaf, rud, shadiy |
|            5 |     2472 | 2024-05-01 | RUBY            | W   | 0.552      | 0.435        | 0.095 (0.023)    | 0.480 (0.115)    | 0 (0.000) |    12.71 | darber, Goody, leaf, rud, shadiy |
|            4 |     2476 | 2024-04-30 | Sampi           | L   | 0.548      | -            | -                | -                | -         |    -4.93 | darber, Goody, leaf, rud, sSen   |
|            3 |     2561 | 2024-04-27 | K10             | W   | 0.525      | 0.143        | 0.008 (0.001)    | 0.129 (0.010)    | 0 (0.000) |     6.86 | darber, Goody, leaf, rud, sSen   |
|            2 |     3307 | 2024-03-30 | NAVI Junior     | W   | 0.340      | 0.333        | 0.003 (0.000)    | 0.115 (0.013)    | 0 (0.000) |     5.02 | darber, Goody, leaf, nestee, rud |
|            1 |     3335 | 2024-03-28 | Passion UA      | W   | 0.326      | 0.333        | 0.173 (0.019)    | 1.000 (0.109)    | 0 (0.000) |     8.91 | darber, Goody, leaf, nestee, rud |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,037.78)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
