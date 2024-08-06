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
Final Rank Value (1299.7) = Starting Rank Value (1414.7) + Head To Head Adjustments (-115.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.520[<sup>2</sup>](#table1)
- Opponent Network: 0.326[<sup>2</sup>](#table1)
- LAN Wins: 0.606[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.7
- 400 + ( ( 0.494 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1414.7


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
|           33 |        0 | 2024-08-06 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.95 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           32 |       96 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.99 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      108 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.44 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      196 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.21 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      353 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.564 (0.367)    | 1 (1.000) |     6.67 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      370 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.93 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      403 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.709 (0.461)    | 1 (1.000) |    28.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      432 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.18 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      438 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.81 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      565 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.62 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      697 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.315 (0.157)    | 0.720 (0.360)    | 0 (0.000) |     9.36 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      819 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.533 (0.266)    | 0 (0.000) |     2.70 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1064 | 2024-06-15 | Monte             | L   | 0.855      | -            | -                | -                | -         |   -22.51 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1075 | 2024-06-15 | 3DMAX             | L   | 0.853      | -            | -                | -                | -         |   -10.05 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1117 | 2024-06-14 | Monte             | W   | 0.847      | -            | -                | -                | -         |     3.90 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1147 | 2024-06-13 | Aurora Young Blud | W   | 0.840      | -            | -                | -                | -         |     1.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1173 | 2024-06-12 | B8                | W   | 0.834      | 0.143        | 0.164 (0.020)    | -                | -         |     5.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1219 | 2024-06-10 | Nemiga            | L   | 0.821      | -            | -                | -                | -         |   -19.77 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1269 | 2024-06-09 | MOUZ NXT          | W   | 0.814      | 0.500        | 0.139 (0.056)    | 0.984 (0.400)    | -         |     4.72 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1310 | 2024-06-08 | 9INE              | W   | 0.809      | 0.500        | -                | 0.534 (0.216)    | -         |     1.85 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1367 | 2024-06-07 | Rebels            | L   | 0.802      | -            | -                | -                | -         |   -22.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1516 | 2024-06-05 | Nexus             | W   | 0.787      | -            | -                | -                | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1607 | 2024-06-02 | The MongolZ       | L   | 0.767      | -            | -                | -                | -         |    -1.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1611 | 2024-06-01 | Aurora            | W   | 0.765      | 0.500        | 0.421 (0.161)    | 0.776 (0.297)    | 1 (0.765) |    17.35 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1641 | 2024-06-01 | The MongolZ       | L   | 0.760      | -            | -                | -                | -         |    -1.18 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1699 | 2024-05-29 | ATOX              | W   | 0.745      | -            | -                | -                | 1 (0.745) |     1.43 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1723 | 2024-05-28 | Chinggis Warriors | W   | 0.738      | -            | -                | -                | 1 (0.738) |     0.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1912 | 2024-05-21 | Zero Tenacity     | L   | 0.688      | -            | -                | -                | -         |   -17.91 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1945 | 2024-05-20 | 9 Pandas          | W   | 0.681      | 0.500        | 0.081 (0.028)    | 0.716 (0.244)    | -         |     2.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1982 | 2024-05-19 | MOUZ NXT          | W   | 0.673      | 0.500        | 0.139 (0.047)    | 0.984 (0.331)    | -         |     2.98 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2036 | 2024-05-17 | Monte             | L   | 0.661      | -            | -                | -                | -         |   -18.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2125 | 2024-05-15 | Gaimin Gladiators | L   | 0.647      | -            | -                | -                | -         |   -18.56 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2136 | 2024-05-15 | MOUZ NXT          | W   | 0.646      | 0.500        | 0.139 (0.045)    | 0.984 (0.318)    | -         |     2.29 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,261.92)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.862 | $2,000.00      | $1,723.33       |
| 2024-06-11 |      0.828 | $12,500.00     | $10,350.69      |
| 2024-06-02 |      0.767 | $25,000.00     | $19,169.56      |
| 2024-05-22 |      0.695 | $12,500.00     | $8,684.03       |
| 2024-05-18 |      0.669 | $500.00        | $334.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
