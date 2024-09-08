### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [141](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
<br />
Final Rank Value:  715.7<br />
<br />
Final Rank Value (715.7) = Starting Rank Value (715.1) + Head To Head Adjustments (0.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 715.1
- 400 + ( ( 0.163 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 715.1


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
|           15 |     3702 | 2024-04-26 | TYLOO    | L   | 0.301      | -            | -                | -                | -         |    -4.97 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     3735 | 2024-04-25 | M80      | L   | 0.294      | -            | -                | -                | -         |    -1.02 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     3774 | 2024-04-23 | Vitality | L   | 0.280      | -            | -                | -                | -         |    -0.01 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     3999 | 2024-04-16 | W7M      | L   | 0.236      | -            | -                | -                | -         |    -3.11 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     4064 | 2024-04-12 | Galorys  | L   | 0.209      | -            | -                | -                | -         |    -3.18 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     4116 | 2024-04-10 | ODDIK    | W   | 0.196      | 0.450        | 0.190 (0.017)    | 0.839 (0.074)    | 0 (0.000) |     5.54 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     4120 | 2024-04-10 | ODDIK    | L   | 0.196      | -            | -                | -                | -         |    -0.65 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     4217 | 2024-04-08 | paiN     | L   | 0.182      | -            | -                | -                | -         |    -0.03 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     4257 | 2024-04-07 | BESTIA   | W   | 0.174      | 0.435        | 0.107 (0.008)    | 0.807 (0.061)    | 0 (0.000) |     4.29 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     4268 | 2024-04-06 | ODDIK    | W   | 0.168      | 0.143        | 0.190 (0.005)    | 0.839 (0.020)    | 0 (0.000) |     4.82 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     4287 | 2024-04-05 | paiN     | L   | 0.161      | -            | -                | -                | -         |    -0.02 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     4307 | 2024-04-04 | paiN     | L   | 0.156      | -            | -                | -                | -         |    -0.02 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     4314 | 2024-04-04 | paiN     | L   | 0.156      | -            | -                | -                | -         |    -0.02 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     4392 | 2024-04-02 | BESTIA   | L   | 0.143      | -            | -                | -                | -         |    -0.92 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     4396 | 2024-04-02 | MIBR     | L   | 0.142      | -            | -                | -                | -         |    -0.11 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,402.59)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.595 | $5,000.00      | $2,977.31       |
| 2024-05-12 |      0.407 | $3,500.00      | $1,425.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
