### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  776.7<br />
<br />
Final Rank Value (776.7) = Starting Rank Value (762.9) + Head To Head Adjustments (13.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.9
- 400 + ( ( 0.176 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 762.9


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
|           17 |     2485 | 2024-04-26 | TYLOO       | L   | 0.553      | -            | -                | -                | -         |    -9.07 | doc, drg, rdnzao, supLexN1, togs  |
|           16 |     2517 | 2024-04-25 | M80         | L   | 0.546      | -            | -                | -                | -         |    -1.22 | doc, drg, rdnzao, supLexN1, togs  |
|           15 |     2558 | 2024-04-23 | Vitality    | L   | 0.533      | -            | -                | -                | -         |    -0.05 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     2607 | 2024-04-20 | adalYamigos | W   | 0.515      | 0.450        | 0.000 (0.000)    | 0.085 (0.020)    | 0 (0.000) |     5.61 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     2609 | 2024-04-20 | adalYamigos | W   | 0.515      | 0.450        | 0.000 (0.000)    | 0.085 (0.020)    | 0 (0.000) |     5.85 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     2790 | 2024-04-16 | W7M         | L   | 0.489      | -            | -                | -                | -         |    -6.08 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     2856 | 2024-04-12 | Galorys     | L   | 0.461      | -            | -                | -                | -         |    -4.55 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     2909 | 2024-04-10 | ODDIK       | W   | 0.449      | 0.450        | 0.096 (0.019)    | 0.822 (0.166)    | 0 (0.000) |    10.58 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     2913 | 2024-04-10 | ODDIK       | L   | 0.448      | -            | -                | -                | -         |    -3.56 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     3010 | 2024-04-08 | paiN        | L   | 0.434      | -            | -                | -                | -         |    -0.47 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     3050 | 2024-04-07 | BESTIA      | W   | 0.426      | 0.435        | 0.089 (0.016)    | 0.738 (0.137)    | 0 (0.000) |    10.39 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     3061 | 2024-04-06 | ODDIK       | W   | 0.420      | 0.143        | 0.096 (0.006)    | 0.822 (0.049)    | 0 (0.000) |    10.44 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     3080 | 2024-04-05 | paiN        | L   | 0.413      | -            | -                | -                | -         |    -0.39 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     3100 | 2024-04-04 | paiN        | L   | 0.408      | -            | -                | -                | -         |    -0.39 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     3107 | 2024-04-04 | paiN        | L   | 0.408      | -            | -                | -                | -         |    -0.39 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     3193 | 2024-04-02 | BESTIA      | L   | 0.395      | -            | -                | -                | -         |    -2.59 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     3197 | 2024-04-02 | MIBR        | L   | 0.394      | -            | -                | -                | -         |    -0.33 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,546.48)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $5,000.00      | $4,238.43       |
| 2024-05-12 |      0.659 | $3,500.00      | $2,308.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
