### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  759.0<br />
<br />
Final Rank Value (759.0) = Starting Rank Value (758.3) + Head To Head Adjustments (0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.3
- 400 + ( ( 0.175 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 758.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2433 | 2024-04-26 | TYLOO    | L   | 0.540      | -            | -                | -                | -         |    -8.53 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     2465 | 2024-04-25 | M80      | L   | 0.533      | -            | -                | -                | -         |    -1.15 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     2504 | 2024-04-23 | Vitality | L   | 0.519      | -            | -                | -                | -         |    -0.04 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     2729 | 2024-04-16 | W7M      | L   | 0.475      | -            | -                | -                | -         |    -6.30 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     2794 | 2024-04-12 | Galorys  | L   | 0.448      | -            | -                | -                | -         |    -4.86 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     2846 | 2024-04-10 | ODDIK    | W   | 0.435      | 0.450        | 0.098 (0.019)    | 0.857 (0.168)    | 0 (0.000) |     9.93 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     2850 | 2024-04-10 | ODDIK    | L   | 0.435      | -            | -                | -                | -         |    -3.81 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     2947 | 2024-04-08 | paiN     | L   | 0.420      | -            | -                | -                | -         |    -0.43 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     2987 | 2024-04-07 | BESTIA   | W   | 0.413      | 0.435        | 0.091 (0.016)    | 0.756 (0.136)    | 0 (0.000) |    10.01 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     2998 | 2024-04-06 | ODDIK    | W   | 0.407      | 0.143        | 0.098 (0.006)    | 0.857 (0.050)    | 0 (0.000) |     9.78 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     3017 | 2024-04-05 | paiN     | L   | 0.400      | -            | -                | -                | -         |    -0.36 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     3037 | 2024-04-04 | paiN     | L   | 0.395      | -            | -                | -                | -         |    -0.36 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     3044 | 2024-04-04 | paiN     | L   | 0.395      | -            | -                | -                | -         |    -0.36 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     3122 | 2024-04-02 | BESTIA   | L   | 0.382      | -            | -                | -                | -         |    -2.55 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     3126 | 2024-04-02 | MIBR     | L   | 0.381      | -            | -                | -                | -         |    -0.29 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,433.54)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.834 | $5,000.00      | $4,171.99       |
| 2024-05-12 |      0.646 | $3,500.00      | $2,261.55       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
