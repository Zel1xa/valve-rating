### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  759.8<br />
<br />
Final Rank Value (759.8) = Starting Rank Value (757.9) + Head To Head Adjustments (1.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 757.9
- 400 + ( ( 0.175 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 757.9


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
|           15 |     2539 | 2024-04-26 | TYLOO    | L   | 0.531      | -            | -                | -                | -         |    -8.39 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     2572 | 2024-04-25 | M80      | L   | 0.524      | -            | -                | -                | -         |    -1.15 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     2611 | 2024-04-23 | Vitality | L   | 0.510      | -            | -                | -                | -         |    -0.04 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     2836 | 2024-04-16 | W7M      | L   | 0.466      | -            | -                | -                | -         |    -6.07 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     2901 | 2024-04-12 | Galorys  | L   | 0.439      | -            | -                | -                | -         |    -4.55 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     2953 | 2024-04-10 | ODDIK    | W   | 0.426      | 0.450        | 0.099 (0.019)    | 0.833 (0.160)    | 0 (0.000) |     9.88 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     2957 | 2024-04-10 | ODDIK    | L   | 0.426      | -            | -                | -                | -         |    -3.57 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     3054 | 2024-04-08 | paiN     | L   | 0.412      | -            | -                | -                | -         |    -0.34 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     3094 | 2024-04-07 | BESTIA   | W   | 0.404      | 0.435        | 0.095 (0.017)    | 0.802 (0.141)    | 0 (0.000) |     9.92 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     3105 | 2024-04-06 | ODDIK    | W   | 0.398      | 0.143        | 0.099 (0.006)    | 0.833 (0.047)    | 0 (0.000) |     9.70 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     3124 | 2024-04-05 | paiN     | L   | 0.391      | -            | -                | -                | -         |    -0.28 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     3144 | 2024-04-04 | paiN     | L   | 0.386      | -            | -                | -                | -         |    -0.28 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     3151 | 2024-04-04 | paiN     | L   | 0.386      | -            | -                | -                | -         |    -0.28 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     3229 | 2024-04-02 | BESTIA   | L   | 0.373      | -            | -                | -                | -         |    -2.38 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     3233 | 2024-04-02 | MIBR     | L   | 0.372      | -            | -                | -                | -         |    -0.30 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,357.59)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.825 | $5,000.00      | $4,127.31       |
| 2024-05-12 |      0.637 | $3,500.00      | $2,230.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
