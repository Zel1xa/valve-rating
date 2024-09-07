### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [141](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Americas]( ../../standings_americas_2024_09_07.md)<br />
Regional Rank: [39]( ../../standings_americas_2024_09_07.md)<br />
<br />
Final Rank Value:  720.5<br />
<br />
Final Rank Value (720.5) = Starting Rank Value (719.6) + Head To Head Adjustments (0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 719.6
- 400 + ( ( 0.163 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 719.6


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
|           15 |     3670 | 2024-04-26 | TYLOO    | L   | 0.309      | -            | -                | -                | -         |    -5.11 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     3703 | 2024-04-25 | M80      | L   | 0.302      | -            | -                | -                | -         |    -1.01 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     3742 | 2024-04-23 | Vitality | L   | 0.288      | -            | -                | -                | -         |    -0.01 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     3967 | 2024-04-16 | W7M      | L   | 0.244      | -            | -                | -                | -         |    -3.19 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     4032 | 2024-04-12 | Galorys  | L   | 0.217      | -            | -                | -                | -         |    -3.28 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     4084 | 2024-04-10 | ODDIK    | W   | 0.204      | 0.450        | 0.188 (0.017)    | 0.866 (0.080)    | 0 (0.000) |     5.78 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     4088 | 2024-04-10 | ODDIK    | L   | 0.204      | -            | -                | -                | -         |    -0.66 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     4185 | 2024-04-08 | paiN     | L   | 0.189      | -            | -                | -                | -         |    -0.03 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     4225 | 2024-04-07 | BESTIA   | W   | 0.182      | 0.435        | 0.107 (0.008)    | 0.833 (0.066)    | 0 (0.000) |     4.51 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     4236 | 2024-04-06 | ODDIK    | W   | 0.176      | 0.143        | 0.188 (0.005)    | 0.866 (0.022)    | 0 (0.000) |     5.06 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     4255 | 2024-04-05 | paiN     | L   | 0.169      | -            | -                | -                | -         |    -0.02 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     4275 | 2024-04-04 | paiN     | L   | 0.164      | -            | -                | -                | -         |    -0.02 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     4282 | 2024-04-04 | paiN     | L   | 0.164      | -            | -                | -                | -         |    -0.02 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     4360 | 2024-04-02 | BESTIA   | L   | 0.151      | -            | -                | -                | -         |    -0.95 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     4364 | 2024-04-02 | MIBR     | L   | 0.150      | -            | -                | -                | -         |    -0.10 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,469.88)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.603 | $5,000.00      | $3,016.90       |
| 2024-05-12 |      0.415 | $3,500.00      | $1,452.99       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
