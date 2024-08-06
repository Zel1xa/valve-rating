### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1256.9<br />
<br />
Final Rank Value (1256.9) = Starting Rank Value (1414.5) + Head To Head Adjustments (-157.6)<br />

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
|           35 |        5 | 2024-08-06 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -27.22 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           34 |        8 | 2024-08-06 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -17.44 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           33 |       15 | 2024-08-06 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.94 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           32 |      113 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -30.00 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      125 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.46 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      213 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.15 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      370 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.590 (0.384)    | 1 (1.000) |     6.68 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      387 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.91 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      420 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    28.47 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      449 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.17 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      455 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.88 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      582 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.59 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      714 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.314 (0.157)    | 0.704 (0.352)    | 0 (0.000) |     9.32 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      836 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.522 (0.261)    | 0 (0.000) |     3.06 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1081 | 2024-06-15 | Monte             | L   | 0.853      | -            | -                | -                | -         |   -22.50 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1092 | 2024-06-15 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |   -10.05 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1134 | 2024-06-14 | Monte             | W   | 0.845      | -            | -                | -                | -         |     3.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1164 | 2024-06-13 | Aurora Young Blud | W   | 0.839      | -            | -                | -                | -         |     1.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1190 | 2024-06-12 | B8                | W   | 0.832      | 0.143        | 0.170 (0.020)    | -                | -         |     5.84 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1236 | 2024-06-10 | Nemiga            | L   | 0.819      | -            | -                | -                | -         |   -19.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1286 | 2024-06-09 | MOUZ NXT          | W   | 0.812      | 0.500        | 0.139 (0.056)    | 0.961 (0.390)    | -         |     4.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1327 | 2024-06-08 | 9INE              | W   | 0.807      | 0.500        | -                | 0.523 (0.211)    | -         |     1.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1384 | 2024-06-07 | Rebels            | L   | 0.801      | -            | -                | -                | -         |   -22.27 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1533 | 2024-06-05 | Nexus             | W   | 0.786      | -            | -                | -                | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1624 | 2024-06-02 | The MongolZ       | L   | 0.765      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1628 | 2024-06-01 | Aurora            | W   | 0.763      | 0.500        | 0.420 (0.160)    | 0.758 (0.289)    | 1 (0.763) |    17.35 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1658 | 2024-06-01 | The MongolZ       | L   | 0.758      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1716 | 2024-05-29 | ATOX              | W   | 0.743      | -            | -                | -                | 1 (0.743) |     1.42 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1740 | 2024-05-28 | Chinggis Warriors | W   | 0.737      | -            | -                | -                | 1 (0.737) |     2.40 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1929 | 2024-05-21 | Zero Tenacity     | L   | 0.686      | -            | -                | -                | -         |   -17.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1962 | 2024-05-20 | 9 Pandas          | W   | 0.680      | 0.500        | 0.081 (0.028)    | 0.700 (0.238)    | -         |     2.65 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1999 | 2024-05-19 | MOUZ NXT          | W   | 0.671      | 0.500        | 0.139 (0.047)    | 0.961 (0.323)    | -         |     2.98 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2053 | 2024-05-17 | Monte             | L   | 0.660      | -            | -                | -                | -         |   -18.54 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2142 | 2024-05-15 | Gaimin Gladiators | L   | 0.646      | -            | -                | -                | -         |   -18.52 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2153 | 2024-05-15 | MOUZ NXT          | W   | 0.645      | 0.500        | 0.139 (0.045)    | 0.961 (0.310)    | -         |     2.29 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,174.42)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $2,000.00      | $1,720.00       |
| 2024-06-11 |      0.826 | $12,500.00     | $10,329.86      |
| 2024-06-02 |      0.765 | $25,000.00     | $19,127.89      |
| 2024-05-22 |      0.693 | $12,500.00     | $8,663.19       |
| 2024-05-18 |      0.667 | $500.00        | $333.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
