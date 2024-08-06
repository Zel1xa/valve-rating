### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1299.7<br />
<br />
Final Rank Value (1299.7) = Starting Rank Value (1414.5) + Head To Head Adjustments (-114.8)<br />

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
|           33 |        3 | 2024-08-06 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.95 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           32 |      100 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.98 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      112 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.43 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      200 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.19 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      357 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.590 (0.384)    | 1 (1.000) |     6.69 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      374 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.87 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      407 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    28.50 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      436 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.18 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      442 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.79 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      569 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.62 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      701 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.315 (0.157)    | 0.704 (0.352)    | 0 (0.000) |     9.37 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      823 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.521 (0.261)    | 0 (0.000) |     2.70 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1068 | 2024-06-15 | Monte             | L   | 0.854      | -            | -                | -                | -         |   -22.51 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1079 | 2024-06-15 | 3DMAX             | L   | 0.853      | -            | -                | -                | -         |   -10.04 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1121 | 2024-06-14 | Monte             | W   | 0.846      | -            | -                | -                | -         |     3.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1151 | 2024-06-13 | Aurora Young Blud | W   | 0.840      | -            | -                | -                | -         |     1.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1177 | 2024-06-12 | B8                | W   | 0.834      | 0.143        | 0.170 (0.020)    | -                | -         |     5.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1223 | 2024-06-10 | Nemiga            | L   | 0.820      | -            | -                | -                | -         |   -19.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1273 | 2024-06-09 | MOUZ NXT          | W   | 0.814      | 0.500        | 0.139 (0.056)    | 0.962 (0.391)    | -         |     4.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1314 | 2024-06-08 | 9INE              | W   | 0.809      | 0.500        | -                | 0.523 (0.211)    | -         |     1.85 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1371 | 2024-06-07 | Rebels            | L   | 0.802      | -            | -                | -                | -         |   -22.28 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1520 | 2024-06-05 | Nexus             | W   | 0.787      | -            | -                | -                | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1611 | 2024-06-02 | The MongolZ       | L   | 0.767      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1615 | 2024-06-01 | Aurora            | W   | 0.765      | 0.500        | 0.421 (0.161)    | 0.759 (0.290)    | 1 (0.765) |    17.40 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1645 | 2024-06-01 | The MongolZ       | L   | 0.760      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1703 | 2024-05-29 | ATOX              | W   | 0.745      | -            | -                | -                | 1 (0.745) |     1.43 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1727 | 2024-05-28 | Chinggis Warriors | W   | 0.738      | -            | -                | -                | 1 (0.738) |     0.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1916 | 2024-05-21 | Zero Tenacity     | L   | 0.688      | -            | -                | -                | -         |   -17.91 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1949 | 2024-05-20 | 9 Pandas          | W   | 0.681      | 0.500        | 0.081 (0.028)    | 0.700 (0.238)    | -         |     2.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1986 | 2024-05-19 | MOUZ NXT          | W   | 0.673      | 0.500        | 0.139 (0.047)    | 0.962 (0.324)    | -         |     2.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2040 | 2024-05-17 | Monte             | L   | 0.661      | -            | -                | -                | -         |   -18.59 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2129 | 2024-05-15 | Gaimin Gladiators | L   | 0.647      | -            | -                | -                | -         |   -18.55 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2140 | 2024-05-15 | MOUZ NXT          | W   | 0.646      | 0.500        | 0.139 (0.045)    | 0.962 (0.311)    | -         |     2.29 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,247.34)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $2,000.00      | $1,722.78       |
| 2024-06-11 |      0.828 | $12,500.00     | $10,347.22      |
| 2024-06-02 |      0.767 | $25,000.00     | $19,162.62      |
| 2024-05-22 |      0.694 | $12,500.00     | $8,680.56       |
| 2024-05-18 |      0.668 | $500.00        | $334.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
