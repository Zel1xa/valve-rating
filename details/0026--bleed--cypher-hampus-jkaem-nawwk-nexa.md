### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1294.5<br />
<br />
Final Rank Value (1294.5) = Starting Rank Value (1411.6) + Head To Head Adjustments (-117.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.521[<sup>2</sup>](#table1)
- Opponent Network: 0.326[<sup>2</sup>](#table1)
- LAN Wins: 0.605[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1411.6
- 400 + ( ( 0.494 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1411.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |       68 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.97 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       80 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      168 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.33 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      325 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     6.65 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      342 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.97 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      375 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    28.55 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      404 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.22 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      410 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.78 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      537 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.60 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      669 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.158)    | 0.733 (0.367)    | 0 (0.000) |     9.48 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      791 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.460 (0.230)    | 0 (0.000) |     2.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1036 | 2024-06-15 | Monte             | L   | 0.864      | -            | -                | -                | -         |   -22.70 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1047 | 2024-06-15 | 3DMAX             | L   | 0.863      | -            | -                | -                | -         |   -10.26 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1089 | 2024-06-14 | Monte             | W   | 0.856      | -            | -                | -                | 0 (0.000) |     3.98 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1119 | 2024-06-13 | Aurora Young Blud | W   | 0.849      | -            | -                | -                | -         |     1.57 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1145 | 2024-06-12 | B8                | W   | 0.843      | 0.143        | 0.165 (0.020)    | -                | -         |     5.99 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1191 | 2024-06-10 | Nemiga            | L   | 0.830      | -            | -                | -                | -         |   -19.88 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1241 | 2024-06-09 | MOUZ NXT          | W   | 0.823      | 0.500        | 0.139 (0.057)    | 1.000 (0.412)    | -         |     4.77 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1282 | 2024-06-08 | 9INE              | W   | 0.818      | 0.500        | -                | 0.539 (0.220)    | -         |     1.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1339 | 2024-06-07 | Rebels            | L   | 0.811      | -            | -                | -                | -         |   -22.48 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1488 | 2024-06-05 | Nexus             | W   | 0.796      | -            | -                | -                | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1579 | 2024-06-02 | The MongolZ       | L   | 0.776      | -            | -                | -                | -         |    -1.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1583 | 2024-06-01 | Aurora            | W   | 0.774      | 0.500        | 0.423 (0.164)    | 0.792 (0.307)    | 1 (0.774) |    17.50 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1613 | 2024-06-01 | The MongolZ       | L   | 0.769      | -            | -                | -                | -         |    -1.18 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1671 | 2024-05-29 | ATOX              | W   | 0.754      | -            | -                | -                | 1 (0.754) |     1.48 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1695 | 2024-05-28 | Chinggis Warriors | W   | 0.748      | -            | -                | -                | 1 (0.748) |     0.68 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1884 | 2024-05-21 | Zero Tenacity     | L   | 0.697      | -            | -                | -                | -         |   -18.17 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1917 | 2024-05-20 | 9 Pandas          | W   | 0.691      | 0.500        | 0.081 (0.028)    | 0.690 (0.238)    | -         |     2.66 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1954 | 2024-05-19 | MOUZ NXT          | W   | 0.682      | 0.500        | 0.139 (0.047)    | 1.000 (0.341)    | -         |     3.03 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2008 | 2024-05-17 | Monte             | L   | 0.671      | -            | -                | -                | -         |   -18.82 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2097 | 2024-05-15 | Gaimin Gladiators | L   | 0.657      | -            | -                | -                | -         |   -18.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2108 | 2024-05-15 | MOUZ NXT          | W   | 0.656      | 0.500        | 0.139 (0.046)    | 1.000 (0.328)    | -         |     2.33 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,743.17)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.871 | $2,000.00      | $1,741.67       |
| 2024-06-11 |      0.837 | $12,500.00     | $10,465.28      |
| 2024-06-02 |      0.776 | $25,000.00     | $19,398.73      |
| 2024-05-22 |      0.704 | $12,500.00     | $8,798.61       |
| 2024-05-18 |      0.678 | $500.00        | $338.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
