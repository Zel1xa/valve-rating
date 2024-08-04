### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1294.1<br />
<br />
Final Rank Value (1294.1) = Starting Rank Value (1411.5) + Head To Head Adjustments (-117.4)<br />

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
|           32 |       65 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.96 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       76 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.53 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      165 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.37 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      321 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     6.66 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      338 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |   -10.00 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      371 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    28.53 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      400 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.22 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      406 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.94 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      533 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.59 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      665 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.159)    | 0.734 (0.367)    | 0 (0.000) |     9.50 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      787 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.460 (0.230)    | 0 (0.000) |     2.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1032 | 2024-06-15 | Monte             | L   | 0.866      | -            | -                | -                | -         |   -22.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1043 | 2024-06-15 | 3DMAX             | L   | 0.865      | -            | -                | -                | -         |   -10.32 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1085 | 2024-06-14 | Monte             | W   | 0.858      | -            | -                | -                | 0 (0.000) |     4.00 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1115 | 2024-06-13 | Aurora Young Blud | W   | 0.852      | -            | -                | -                | -         |     1.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1141 | 2024-06-12 | B8                | W   | 0.846      | 0.143        | 0.165 (0.020)    | -                | -         |     6.02 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1187 | 2024-06-10 | Nemiga            | L   | 0.832      | -            | -                | -                | -         |   -19.92 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1237 | 2024-06-09 | MOUZ NXT          | W   | 0.825      | 0.500        | 0.139 (0.057)    | 1.000 (0.413)    | -         |     4.79 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1278 | 2024-06-08 | 9INE              | W   | 0.820      | 0.500        | -                | 0.537 (0.220)    | -         |     1.90 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1335 | 2024-06-07 | Rebels            | L   | 0.814      | -            | -                | -                | -         |   -22.54 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1484 | 2024-06-05 | Nexus             | W   | 0.799      | -            | -                | -                | -         |     0.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1575 | 2024-06-02 | The MongolZ       | L   | 0.778      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1579 | 2024-06-01 | Aurora            | W   | 0.777      | 0.500        | 0.423 (0.164)    | 0.793 (0.308)    | 1 (0.777) |    17.52 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1609 | 2024-06-01 | The MongolZ       | L   | 0.772      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1667 | 2024-05-29 | ATOX              | W   | 0.757      | -            | -                | -                | 1 (0.757) |     1.49 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1691 | 2024-05-28 | Chinggis Warriors | W   | 0.750      | -            | -                | -                | 1 (0.750) |     0.68 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1880 | 2024-05-21 | Zero Tenacity     | L   | 0.700      | -            | -                | -                | -         |   -18.23 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1913 | 2024-05-20 | 9 Pandas          | W   | 0.693      | 0.500        | 0.081 (0.028)    | 0.690 (0.239)    | -         |     2.68 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1950 | 2024-05-19 | MOUZ NXT          | W   | 0.685      | 0.500        | 0.139 (0.048)    | 1.000 (0.342)    | -         |     3.05 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2004 | 2024-05-17 | Monte             | L   | 0.673      | -            | -                | -                | -         |   -18.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2093 | 2024-05-15 | Gaimin Gladiators | L   | 0.659      | -            | -                | -                | -         |   -18.82 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2104 | 2024-05-15 | MOUZ NXT          | W   | 0.658      | 0.500        | 0.139 (0.046)    | 1.000 (0.329)    | -         |     2.34 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,868.34)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $2,000.00      | $1,746.44       |
| 2024-06-11 |      0.840 | $12,500.00     | $10,495.08      |
| 2024-06-02 |      0.778 | $25,000.00     | $19,458.33      |
| 2024-05-22 |      0.706 | $12,500.00     | $8,828.41       |
| 2024-05-18 |      0.680 | $500.00        | $340.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
