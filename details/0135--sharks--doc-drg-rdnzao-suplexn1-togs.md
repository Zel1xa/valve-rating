### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  763.8<br />
<br />
Final Rank Value (763.8) = Starting Rank Value (762.0) + Head To Head Adjustments (1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.0
- 400 + ( ( 0.176 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 762.0


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
|           15 |     2386 | 2024-04-26 | TYLOO    | L   | 0.559      | -            | -                | -                | -         |    -8.82 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     2419 | 2024-04-25 | M80      | L   | 0.552      | -            | -                | -                | -         |    -1.14 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     2458 | 2024-04-23 | Vitality | L   | 0.538      | -            | -                | -                | -         |    -0.04 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     2683 | 2024-04-16 | W7M      | L   | 0.494      | -            | -                | -                | -         |    -6.54 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     2748 | 2024-04-12 | Galorys  | L   | 0.467      | -            | -                | -                | -         |    -4.99 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     2800 | 2024-04-10 | ODDIK    | W   | 0.454      | 0.450        | 0.097 (0.020)    | 0.781 (0.160)    | 0 (0.000) |    10.43 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     2804 | 2024-04-10 | ODDIK    | L   | 0.454      | -            | -                | -                | -         |    -3.91 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     2901 | 2024-04-08 | paiN     | L   | 0.439      | -            | -                | -                | -         |    -0.33 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     2941 | 2024-04-07 | BESTIA   | W   | 0.432      | 0.435        | 0.095 (0.018)    | 0.731 (0.137)    | 0 (0.000) |    10.55 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     2952 | 2024-04-06 | ODDIK    | W   | 0.426      | 0.143        | 0.097 (0.006)    | 0.781 (0.048)    | 0 (0.000) |    10.32 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     2971 | 2024-04-05 | paiN     | L   | 0.419      | -            | -                | -                | -         |    -0.27 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     2991 | 2024-04-04 | paiN     | L   | 0.414      | -            | -                | -                | -         |    -0.27 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     2998 | 2024-04-04 | paiN     | L   | 0.414      | -            | -                | -                | -         |    -0.27 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     3076 | 2024-04-02 | BESTIA   | L   | 0.401      | -            | -                | -                | -         |    -2.60 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     3080 | 2024-04-02 | MIBR     | L   | 0.400      | -            | -                | -                | -         |    -0.31 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,595.16)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.853 | $5,000.00      | $4,267.06       |
| 2024-05-12 |      0.665 | $3,500.00      | $2,328.10       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
