### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1256.8<br />
<br />
Final Rank Value (1256.8) = Starting Rank Value (1414.5) + Head To Head Adjustments (-157.7)<br />

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
|           35 |        1 | 2024-08-06 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -27.22 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           34 |        4 | 2024-08-06 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -17.44 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           33 |       11 | 2024-08-06 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.94 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           32 |      109 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -30.00 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      121 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.47 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      209 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.15 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      366 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.590 (0.384)    | 1 (1.000) |     6.66 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      383 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.91 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      416 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    28.48 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      445 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.17 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      451 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.87 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      578 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.59 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      710 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.314 (0.157)    | 0.704 (0.352)    | 0 (0.000) |     9.32 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      832 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.521 (0.261)    | 0 (0.000) |     3.06 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1077 | 2024-06-15 | Monte             | L   | 0.853      | -            | -                | -                | -         |   -22.50 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1088 | 2024-06-15 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |   -10.06 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1130 | 2024-06-14 | Monte             | W   | 0.845      | -            | -                | -                | -         |     3.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1160 | 2024-06-13 | Aurora Young Blud | W   | 0.839      | -            | -                | -                | -         |     1.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1186 | 2024-06-12 | B8                | W   | 0.833      | 0.143        | 0.170 (0.020)    | -                | -         |     5.84 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1232 | 2024-06-10 | Nemiga            | L   | 0.819      | -            | -                | -                | -         |   -19.77 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1282 | 2024-06-09 | MOUZ NXT          | W   | 0.813      | 0.500        | 0.139 (0.056)    | 0.962 (0.391)    | -         |     4.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1323 | 2024-06-08 | 9INE              | W   | 0.807      | 0.500        | -                | 0.523 (0.211)    | -         |     1.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1380 | 2024-06-07 | Rebels            | L   | 0.801      | -            | -                | -                | -         |   -22.27 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1529 | 2024-06-05 | Nexus             | W   | 0.786      | -            | -                | -                | -         |     0.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1620 | 2024-06-02 | The MongolZ       | L   | 0.765      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1624 | 2024-06-01 | Aurora            | W   | 0.764      | 0.500        | 0.420 (0.160)    | 0.758 (0.290)    | 1 (0.764) |    17.36 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1654 | 2024-06-01 | The MongolZ       | L   | 0.759      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1712 | 2024-05-29 | ATOX              | W   | 0.744      | -            | -                | -                | 1 (0.744) |     1.42 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1736 | 2024-05-28 | Chinggis Warriors | W   | 0.737      | -            | -                | -                | 1 (0.737) |     2.41 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1925 | 2024-05-21 | Zero Tenacity     | L   | 0.687      | -            | -                | -                | -         |   -17.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1958 | 2024-05-20 | 9 Pandas          | W   | 0.680      | 0.500        | 0.081 (0.028)    | 0.700 (0.238)    | -         |     2.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1995 | 2024-05-19 | MOUZ NXT          | W   | 0.672      | 0.500        | 0.139 (0.047)    | 0.962 (0.323)    | -         |     2.98 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2049 | 2024-05-17 | Monte             | L   | 0.660      | -            | -                | -                | -         |   -18.55 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2138 | 2024-05-15 | Gaimin Gladiators | L   | 0.646      | -            | -                | -                | -         |   -18.52 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2149 | 2024-05-15 | MOUZ NXT          | W   | 0.645      | 0.500        | 0.139 (0.045)    | 0.962 (0.310)    | -         |     2.29 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,189.00)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $2,000.00      | $1,720.56       |
| 2024-06-11 |      0.827 | $12,500.00     | $10,333.33      |
| 2024-06-02 |      0.765 | $25,000.00     | $19,134.84      |
| 2024-05-22 |      0.693 | $12,500.00     | $8,666.67       |
| 2024-05-18 |      0.667 | $500.00        | $333.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
