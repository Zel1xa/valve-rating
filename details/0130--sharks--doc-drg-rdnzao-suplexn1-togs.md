### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  777.3<br />
<br />
Final Rank Value (777.3) = Starting Rank Value (763.4) + Head To Head Adjustments (13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 763.4
- 400 + ( ( 0.176 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 763.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     2481 | 2024-04-26 | TYLOO       | L   | 0.555      | -            | -                | -                | -         |    -9.09 | doc, drg, rdnzao, supLexN1, togs  |
|           16 |     2513 | 2024-04-25 | M80         | L   | 0.547      | -            | -                | -                | -         |    -1.23 | doc, drg, rdnzao, supLexN1, togs  |
|           15 |     2554 | 2024-04-23 | Vitality    | L   | 0.534      | -            | -                | -                | -         |    -0.05 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     2603 | 2024-04-20 | adalYamigos | W   | 0.516      | 0.450        | 0.000 (0.000)    | 0.086 (0.020)    | 0 (0.000) |     5.64 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     2605 | 2024-04-20 | adalYamigos | W   | 0.516      | 0.450        | 0.000 (0.000)    | 0.086 (0.020)    | 0 (0.000) |     5.88 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     2786 | 2024-04-16 | W7M         | L   | 0.490      | -            | -                | -                | -         |    -6.10 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     2852 | 2024-04-12 | Galorys     | L   | 0.462      | -            | -                | -                | -         |    -4.57 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     2905 | 2024-04-10 | ODDIK       | W   | 0.450      | 0.450        | 0.096 (0.019)    | 0.822 (0.166)    | 0 (0.000) |    10.62 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     2909 | 2024-04-10 | ODDIK       | L   | 0.450      | -            | -                | -                | -         |    -3.57 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     3006 | 2024-04-08 | paiN        | L   | 0.435      | -            | -                | -                | -         |    -0.47 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     3046 | 2024-04-07 | BESTIA      | W   | 0.427      | 0.435        | 0.089 (0.017)    | 0.738 (0.137)    | 0 (0.000) |    10.43 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     3057 | 2024-04-06 | ODDIK       | W   | 0.422      | 0.143        | 0.096 (0.006)    | 0.822 (0.050)    | 0 (0.000) |    10.48 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     3076 | 2024-04-05 | paiN        | L   | 0.414      | -            | -                | -                | -         |    -0.39 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     3096 | 2024-04-04 | paiN        | L   | 0.410      | -            | -                | -                | -         |    -0.38 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     3103 | 2024-04-04 | paiN        | L   | 0.409      | -            | -                | -                | -         |    -0.38 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     3189 | 2024-04-02 | BESTIA      | L   | 0.397      | -            | -                | -                | -         |    -2.59 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     3193 | 2024-04-02 | MIBR        | L   | 0.395      | -            | -                | -                | -         |    -0.33 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,558.29)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.849 | $5,000.00      | $4,245.37       |
| 2024-05-12 |      0.661 | $3,500.00      | $2,312.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
