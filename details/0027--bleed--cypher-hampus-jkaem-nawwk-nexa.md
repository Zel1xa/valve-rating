### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1282.4<br />
<br />
Final Rank Value (1282.4) = Starting Rank Value (1414.5) + Head To Head Adjustments (-132.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.520[<sup>2</sup>](#table1)
- Opponent Network: 0.321[<sup>2</sup>](#table1)
- LAN Wins: 0.606[<sup>2</sup>](#table1)

The average of these factors is 0.493<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.5
- 400 + ( ( 0.493 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1414.5


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
|           34 |        1 | 2024-08-06 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -17.43 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           33 |        7 | 2024-08-06 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.94 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           32 |       98 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.98 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      110 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.43 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      198 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.18 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      355 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.590 (0.384)    | 1 (1.000) |     6.68 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      372 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.90 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      405 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    28.50 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      434 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.18 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      440 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.80 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      567 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.63 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      699 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.314 (0.157)    | 0.704 (0.352)    | 0 (0.000) |     9.36 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      821 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.521 (0.261)    | 0 (0.000) |     3.08 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1066 | 2024-06-15 | Monte             | L   | 0.854      | -            | -                | -                | -         |   -22.50 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1077 | 2024-06-15 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |   -10.02 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1119 | 2024-06-14 | Monte             | W   | 0.846      | -            | -                | -                | -         |     3.88 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1149 | 2024-06-13 | Aurora Young Blud | W   | 0.839      | -            | -                | -                | -         |     1.99 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1175 | 2024-06-12 | B8                | W   | 0.833      | 0.143        | 0.170 (0.020)    | -                | -         |     5.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1221 | 2024-06-10 | Nemiga            | L   | 0.820      | -            | -                | -                | -         |   -19.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1271 | 2024-06-09 | MOUZ NXT          | W   | 0.813      | 0.500        | 0.139 (0.056)    | 0.962 (0.391)    | -         |     4.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1312 | 2024-06-08 | 9INE              | W   | 0.808      | 0.500        | -                | 0.523 (0.211)    | -         |     1.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1369 | 2024-06-07 | Rebels            | L   | 0.801      | -            | -                | -                | -         |   -22.26 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1518 | 2024-06-05 | Nexus             | W   | 0.786      | -            | -                | -                | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1609 | 2024-06-02 | The MongolZ       | L   | 0.766      | -            | -                | -                | -         |    -1.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1613 | 2024-06-01 | Aurora            | W   | 0.764      | 0.500        | 0.420 (0.161)    | 0.759 (0.290)    | 1 (0.764) |    17.37 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1643 | 2024-06-01 | The MongolZ       | L   | 0.759      | -            | -                | -                | -         |    -1.18 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1701 | 2024-05-29 | ATOX              | W   | 0.744      | -            | -                | -                | 1 (0.744) |     1.42 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1725 | 2024-05-28 | Chinggis Warriors | W   | 0.737      | -            | -                | -                | 1 (0.737) |     0.48 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1914 | 2024-05-21 | Zero Tenacity     | L   | 0.687      | -            | -                | -                | -         |   -17.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1947 | 2024-05-20 | 9 Pandas          | W   | 0.680      | 0.500        | 0.081 (0.028)    | 0.700 (0.238)    | -         |     2.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1984 | 2024-05-19 | MOUZ NXT          | W   | 0.672      | 0.500        | 0.139 (0.047)    | 0.962 (0.323)    | -         |     2.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2038 | 2024-05-17 | Monte             | L   | 0.660      | -            | -                | -                | -         |   -18.57 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2127 | 2024-05-15 | Gaimin Gladiators | L   | 0.647      | -            | -                | -                | -         |   -18.54 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2138 | 2024-05-15 | MOUZ NXT          | W   | 0.645      | 0.500        | 0.139 (0.045)    | 0.962 (0.310)    | -         |     2.29 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,213.31)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $2,000.00      | $1,721.48       |
| 2024-06-11 |      0.827 | $12,500.00     | $10,339.12      |
| 2024-06-02 |      0.766 | $25,000.00     | $19,146.41      |
| 2024-05-22 |      0.694 | $12,500.00     | $8,672.45       |
| 2024-05-18 |      0.668 | $500.00        | $333.84         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
