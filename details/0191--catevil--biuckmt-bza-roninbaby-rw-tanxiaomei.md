### Roster Details<br />
Team Name: CatEvil<br />
Roster: Biuckmt, BZA, Roninbaby, RW, tanxiaomei<br />
Global Rank: [191](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [23]( ../standings_asia.md)<br />
<br />
Final Rank Value:  605.2<br />
<br />
Final Rank Value (605.2) = Starting Rank Value (569.1) + Head To Head Adjustments (36.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.087<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 569.1
- 400 + ( ( 0.087 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 569.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      359 | 2024-08-27 | Bromo        | L   | 1.000      | -            | -                | -                | -         |   -18.22 | Biuckmt, BZA, Roninbaby, RW, tanxiaomei        |
|           13 |      400 | 2024-08-27 | Rare Atom    | L   | 1.000      | -            | -                | -                | -         |    -5.42 | Biuckmt, BZA, Roninbaby, RW, tanxiaomei        |
|           12 |      405 | 2024-08-27 | SHPL         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.075 (0.011)    | 0 (0.000) |     7.34 | Biuckmt, BZA, Roninbaby, RW, tanxiaomei        |
|           11 |     1283 | 2024-08-01 | ATOX         | L   | 0.947      | -            | -                | -                | -         |    -8.29 | Biuckmt, BZA, Roninbaby, splashske, tanxiaomei |
|           10 |     1294 | 2024-08-01 | TYLOO        | L   | 0.945      | -            | -                | -                | -         |    -4.77 | Biuckmt, BZA, Roninbaby, splashske, tanxiaomei |
|            9 |     1411 | 2024-07-29 | Bromo        | W   | 0.926      | 0.143        | 0.000 (0.000)    | 0.255 (0.034)    | 0 (0.000) |    10.48 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            8 |     1412 | 2024-07-29 | -72c         | W   | 0.926      | 0.143        | 0.003 (0.000)    | 0.110 (0.015)    | 0 (0.000) |    14.58 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            7 |     1438 | 2024-07-28 | Niory        | W   | 0.920      | 0.143        | 0.000 (0.000)    | 0.113 (0.015)    | 0 (0.000) |     9.73 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            6 |     1470 | 2024-07-27 | Rare Atom    | L   | 0.912      | -            | -                | -                | -         |    -4.94 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            5 |     1493 | 2024-07-26 | FengDa       | W   | 0.907      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.90 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            4 |     1988 | 2024-07-13 | TYLOO        | L   | 0.819      | -            | -                | -                | -         |    -3.35 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            3 |     2014 | 2024-07-11 | The MongolZ  | W   | 0.807      | 0.143        | 0.864 (0.100)    | 0.695 (0.080)    | 0 (0.000) |    25.38 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            2 |     2015 | 2024-07-11 | Steel Helmet | W   | 0.806      | 0.143        | 0.003 (0.000)    | 0.038 (0.004)    | 0 (0.000) |    11.40 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            1 |     2019 | 2024-07-11 | Rare Atom    | L   | 0.806      | -            | -                | -                | -         |    -4.70 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
