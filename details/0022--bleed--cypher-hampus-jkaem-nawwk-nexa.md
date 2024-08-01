### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1339.1<br />
<br />
Final Rank Value (1339.1) = Starting Rank Value (1422.0) + Head To Head Adjustments (-82.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.528[<sup>1</sup>](#table2)
- Bounty Collected: 0.523[<sup>2</sup>](#table1)
- Opponent Network: 0.319[<sup>2</sup>](#table1)
- LAN Wins: 0.616[<sup>2</sup>](#table1)

The average of these factors is 0.497<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1422.0
- 400 + ( ( 0.497 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1422.0


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
|           30 |       51 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.132 (0.019)    | -                | 0 (0.000) |    10.20 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      207 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.018 (0.012)    | 0.457 (0.297)    | 1 (1.000) |     6.62 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      224 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |   -10.20 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      257 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    28.40 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      286 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.24 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      292 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -13.55 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      422 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.56 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      560 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.324 (0.162)    | 0.697 (0.349)    | 0 (0.000) |     8.82 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      690 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.449 (0.224)    | 0 (0.000) |     2.76 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |      930 | 2024-06-15 | Monte             | L   | 0.886      | -            | -                | -                | -         |   -23.49 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |      941 | 2024-06-15 | 3DMAX             | L   | 0.884      | -            | -                | -                | -         |   -11.01 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |      977 | 2024-06-14 | Monte             | W   | 0.878      | -            | -                | -                | 0 (0.000) |     3.85 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1007 | 2024-06-13 | Aurora Young Blud | W   | 0.871      | -            | -                | -                | -         |     1.78 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1033 | 2024-06-12 | B8                | W   | 0.865      | 0.143        | 0.168 (0.021)    | -                | -         |     5.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1081 | 2024-06-10 | Nemiga            | L   | 0.852      | -            | -                | -                | -         |   -21.00 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1131 | 2024-06-09 | MOUZ NXT          | W   | 0.845      | 0.500        | 0.141 (0.060)    | 1.000 (0.422)    | -         |     4.88 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1174 | 2024-06-08 | 9INE              | W   | 0.840      | 0.500        | -                | 0.522 (0.219)    | -         |     2.31 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1238 | 2024-06-07 | Rebels            | L   | 0.833      | -            | -                | -                | -         |   -23.08 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1392 | 2024-06-05 | Nexus             | W   | 0.818      | 0.500        | -                | 0.504 (0.206)    | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1484 | 2024-06-02 | The MongolZ       | L   | 0.798      | -            | -                | -                | -         |    -1.38 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1488 | 2024-06-01 | Aurora            | W   | 0.796      | 0.500        | 0.431 (0.172)    | 0.798 (0.318)    | 1 (0.796) |    17.79 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1518 | 2024-06-01 | The MongolZ       | L   | 0.791      | -            | -                | -                | -         |    -1.26 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1576 | 2024-05-29 | ATOX              | W   | 0.776      | -            | -                | -                | 1 (0.776) |     1.52 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1600 | 2024-05-28 | Chinggis Warriors | W   | 0.769      | -            | -                | -                | 1 (0.769) |     0.51 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1806 | 2024-05-21 | Zero Tenacity     | L   | 0.719      | -            | -                | -                | -         |   -19.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1842 | 2024-05-20 | 9 Pandas          | W   | 0.713      | 0.500        | 0.083 (0.030)    | -                | -         |     2.73 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1886 | 2024-05-19 | MOUZ NXT          | W   | 0.704      | 0.500        | 0.141 (0.050)    | 1.000 (0.352)    | -         |     2.96 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     1941 | 2024-05-17 | Monte             | L   | 0.693      | -            | -                | -                | -         |   -19.60 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2034 | 2024-05-15 | Gaimin Gladiators | L   | 0.679      | -            | -                | -                | -         |   -19.35 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2045 | 2024-05-15 | MOUZ NXT          | W   | 0.677      | 0.500        | 0.141 (0.048)    | 1.000 (0.339)    | -         |     2.09 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,895.25)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $2,000.00      | $1,785.56       |
| 2024-06-11 |      0.859 | $12,500.00     | $10,739.58      |
| 2024-06-02 |      0.798 | $25,000.00     | $19,947.34      |
| 2024-05-22 |      0.726 | $12,500.00     | $9,072.92       |
| 2024-05-18 |      0.700 | $500.00        | $349.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
