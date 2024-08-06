### Roster Details<br />
Team Name: CatEvil<br />
Roster: Biuckmt, BZA, Roninbaby, splashske, tanxiaomei<br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [19]( ../standings_asia.md)<br />
<br />
Final Rank Value:  641.8<br />
<br />
Final Rank Value (641.8) = Starting Rank Value (586.9) + Head To Head Adjustments (54.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.091<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 586.9
- 400 + ( ( 0.091 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 586.9


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
|           11 |      151 | 2024-08-01 | ATOX         | L   | 1.000      | -            | -                | -                | -         |    -6.58 | Biuckmt, BZA, Roninbaby, splashske, tanxiaomei |
|           10 |      162 | 2024-08-01 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |    -6.81 | Biuckmt, BZA, Roninbaby, splashske, tanxiaomei |
|            9 |      279 | 2024-07-29 | Bromo        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.118 (0.017)    | 0 (0.000) |    10.47 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            8 |      280 | 2024-07-29 | -72c         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.039 (0.006)    | 0 (0.000) |    15.67 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            7 |      306 | 2024-07-28 | NE           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.72 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            6 |      338 | 2024-07-27 | Rare Atom    | L   | 1.000      | -            | -                | -                | -         |    -5.39 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            5 |      361 | 2024-07-26 | FengDa       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.88 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            4 |      853 | 2024-07-13 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |    -5.77 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            3 |      879 | 2024-07-11 | The MongolZ  | W   | 1.000      | 0.143        | 1.000 (0.143)    | 0.709 (0.101)    | 0 (0.000) |    31.46 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            2 |      880 | 2024-07-11 | Steel Helmet | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.000 (0.000)    | 0 (0.000) |    14.07 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |
|            1 |      884 | 2024-07-11 | Rare Atom    | L   | 1.000      | -            | -                | -                | -         |    -5.84 | Biuckmt, BZA, lan, Roninbaby, tanxiaomei       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
