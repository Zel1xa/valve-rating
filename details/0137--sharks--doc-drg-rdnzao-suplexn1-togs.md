### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [35]( ../standings_americas.md)<br />
<br />
Final Rank Value:  759.7<br />
<br />
Final Rank Value (759.7) = Starting Rank Value (758.0) + Head To Head Adjustments (1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.369[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.0
- 400 + ( ( 0.174 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 758.0


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
|           15 |     2567 | 2024-04-26 | TYLOO    | L   | 0.522      | -            | -                | -                | -         |    -8.16 | doc, drg, rdnzao, supLexN1, togs  |
|           14 |     2600 | 2024-04-25 | M80      | L   | 0.515      | -            | -                | -                | -         |    -1.14 | doc, drg, rdnzao, supLexN1, togs  |
|           13 |     2639 | 2024-04-23 | Vitality | L   | 0.501      | -            | -                | -                | -         |    -0.04 | doc, drg, rdnzao, supLexN1, togs  |
|           12 |     2864 | 2024-04-16 | W7M      | L   | 0.457      | -            | -                | -                | -         |    -5.95 | doc, drg, rdnzao, supLexN1, togs  |
|           11 |     2929 | 2024-04-12 | Galorys  | L   | 0.430      | -            | -                | -                | -         |    -4.46 | doc, drg, rdnzao, supLexN1, togs  |
|           10 |     2981 | 2024-04-10 | ODDIK    | W   | 0.417      | 0.450        | 0.099 (0.019)    | 0.823 (0.154)    | 0 (0.000) |     9.66 | doc, drg, lukiz, rdnzao, supLexN1 |
|            9 |     2985 | 2024-04-10 | ODDIK    | L   | 0.417      | -            | -                | -                | -         |    -3.50 | doc, drg, lukiz, rdnzao, supLexN1 |
|            8 |     3082 | 2024-04-08 | paiN     | L   | 0.402      | -            | -                | -                | -         |    -0.34 | doc, drg, rdnzao, supLexN1, togs  |
|            7 |     3122 | 2024-04-07 | BESTIA   | W   | 0.394      | 0.435        | 0.096 (0.016)    | 0.793 (0.136)    | 0 (0.000) |     9.69 | doc, drg, rdnzao, supLexN1, togs  |
|            6 |     3133 | 2024-04-06 | ODDIK    | W   | 0.389      | 0.143        | 0.099 (0.006)    | 0.823 (0.046)    | 0 (0.000) |     9.46 | doc, drg, gafolo, supLexN1, togs  |
|            5 |     3152 | 2024-04-05 | paiN     | L   | 0.382      | -            | -                | -                | -         |    -0.28 | doc, drg, gafolo, supLexN1, togs  |
|            4 |     3172 | 2024-04-04 | paiN     | L   | 0.377      | -            | -                | -                | -         |    -0.28 | doc, drg, gafolo, supLexN1, togs  |
|            3 |     3179 | 2024-04-04 | paiN     | L   | 0.377      | -            | -                | -                | -         |    -0.28 | doc, drg, gafolo, supLexN1, togs  |
|            2 |     3257 | 2024-04-02 | BESTIA   | L   | 0.364      | -            | -                | -                | -         |    -2.33 | doc, drg, rdnzao, supLexN1, togs  |
|            1 |     3261 | 2024-04-02 | MIBR     | L   | 0.363      | -            | -                | -                | -         |    -0.30 | doc, drg, rdnzao, supLexN1, togs  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,279.68)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.816 | $5,000.00      | $4,081.48       |
| 2024-05-12 |      0.628 | $3,500.00      | $2,198.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
