### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1294.0<br />
<br />
Final Rank Value (1294.0) = Starting Rank Value (1411.5) + Head To Head Adjustments (-117.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.527[<sup>1</sup>](#table2)
- Bounty Collected: 0.521[<sup>2</sup>](#table1)
- Opponent Network: 0.326[<sup>2</sup>](#table1)
- LAN Wins: 0.605[<sup>2</sup>](#table1)

The average of these factors is 0.495<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1411.5
- 400 + ( ( 0.495 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1411.5


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
|           32 |       64 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.96 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       75 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.53 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      164 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.36 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      320 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     6.65 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      337 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |   -10.02 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      370 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    28.54 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      399 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.22 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      405 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.93 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      532 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.59 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      664 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.159)    | 0.734 (0.367)    | 0 (0.000) |     9.49 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      786 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.459 (0.230)    | 0 (0.000) |     2.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1031 | 2024-06-15 | Monte             | L   | 0.867      | -            | -                | -                | -         |   -22.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1042 | 2024-06-15 | 3DMAX             | L   | 0.865      | -            | -                | -                | -         |   -10.33 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1084 | 2024-06-14 | Monte             | W   | 0.859      | -            | -                | -                | 0 (0.000) |     4.00 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1114 | 2024-06-13 | Aurora Young Blud | W   | 0.852      | -            | -                | -                | -         |     1.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1140 | 2024-06-12 | B8                | W   | 0.846      | 0.143        | 0.165 (0.020)    | -                | -         |     6.02 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1186 | 2024-06-10 | Nemiga            | L   | 0.832      | -            | -                | -                | -         |   -19.94 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1236 | 2024-06-09 | MOUZ NXT          | W   | 0.826      | 0.500        | 0.139 (0.057)    | 1.000 (0.413)    | -         |     4.79 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1277 | 2024-06-08 | 9INE              | W   | 0.821      | 0.500        | -                | 0.537 (0.221)    | -         |     1.90 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1334 | 2024-06-07 | Rebels            | L   | 0.814      | -            | -                | -                | -         |   -22.55 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1483 | 2024-06-05 | Nexus             | W   | 0.799      | -            | -                | -                | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1574 | 2024-06-02 | The MongolZ       | L   | 0.779      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1578 | 2024-06-01 | Aurora            | W   | 0.777      | 0.500        | 0.423 (0.164)    | 0.793 (0.308)    | 1 (0.777) |    17.50 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1608 | 2024-06-01 | The MongolZ       | L   | 0.772      | -            | -                | -                | -         |    -1.20 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1666 | 2024-05-29 | ATOX              | W   | 0.757      | -            | -                | -                | 1 (0.757) |     1.49 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1690 | 2024-05-28 | Chinggis Warriors | W   | 0.750      | -            | -                | -                | 1 (0.750) |     0.68 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1879 | 2024-05-21 | Zero Tenacity     | L   | 0.700      | -            | -                | -                | -         |   -18.25 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1912 | 2024-05-20 | 9 Pandas          | W   | 0.693      | 0.500        | 0.081 (0.028)    | 0.690 (0.239)    | -         |     2.68 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1949 | 2024-05-19 | MOUZ NXT          | W   | 0.685      | 0.500        | 0.139 (0.048)    | 1.000 (0.342)    | -         |     3.05 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2003 | 2024-05-17 | Monte             | L   | 0.673      | -            | -                | -                | -         |   -18.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2092 | 2024-05-15 | Gaimin Gladiators | L   | 0.659      | -            | -                | -                | -         |   -18.82 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2103 | 2024-05-15 | MOUZ NXT          | W   | 0.658      | 0.500        | 0.139 (0.046)    | 1.000 (0.329)    | -         |     2.34 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,884.14)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $2,000.00      | $1,747.04       |
| 2024-06-11 |      0.840 | $12,500.00     | $10,498.84      |
| 2024-06-02 |      0.779 | $25,000.00     | $19,465.86      |
| 2024-05-22 |      0.707 | $12,500.00     | $8,832.18       |
| 2024-05-18 |      0.680 | $500.00        | $340.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
