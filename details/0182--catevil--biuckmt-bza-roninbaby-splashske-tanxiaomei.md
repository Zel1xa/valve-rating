### Roster Details<br />
Team Name: CatEvil<br />
Roster: Biuckmt, BZA, Roninbaby, splashske, tanxiaomei<br />
Global Rank: [182](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
<br />
Final Rank Value:  627.7<br />
<br />
Final Rank Value (627.7) = Starting Rank Value (586.2) + Head To Head Adjustments (41.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.091<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 586.2
- 400 + ( ( 0.091 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 586.2


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
|           11 |       85 | 2024-08-01 | ATOX         | L   | 1.000      | -            | -                | -                | -         |    -6.45 | Biuckmt, BZA, Roninbaby, splashske, tanxiaomei |
|           10 |       95 | 2024-08-01 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |   -10.80 | Biuckmt, BZA, Roninbaby, splashske, tanxiaomei |
|            9 |      212 | 2024-07-29 | Bromo        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.118 (0.017)    | 0 (0.000) |    10.85 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            8 |      213 | 2024-07-29 | -72c         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.039 (0.006)    | 0 (0.000) |    16.09 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            7 |      239 | 2024-07-28 | NE           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.05 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            6 |      271 | 2024-07-27 | Rare Atom    | L   | 1.000      | -            | -                | -                | -         |    -8.57 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            5 |      294 | 2024-07-26 | FengDa       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.13 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            4 |      785 | 2024-07-13 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |    -9.76 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            3 |      811 | 2024-07-11 | The MongolZ  | W   | 1.000      | 0.143        | 1.000 (0.143)    | 0.720 (0.103)    | 0 (0.000) |    31.46 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            2 |      812 | 2024-07-11 | Steel Helmet | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.000 (0.000)    | 0 (0.000) |    14.25 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            1 |      816 | 2024-07-11 | Rare Atom    | L   | 1.000      | -            | -                | -                | -         |    -9.75 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
