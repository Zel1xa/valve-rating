### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1297.9<br />
<br />
Final Rank Value (1297.9) = Starting Rank Value (1414.8) + Head To Head Adjustments (-116.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.520[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.605[<sup>2</sup>](#table1)

The average of these factors is 0.495<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.8
- 400 + ( ( 0.495 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1414.8


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
|           32 |       89 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.99 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      101 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.52 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      189 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.18 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      346 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.565 (0.367)    | 1 (1.000) |     6.64 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      363 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.98 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      396 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    28.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      425 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.19 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      431 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.81 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      558 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.62 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      690 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.316 (0.158)    | 0.722 (0.361)    | 0 (0.000) |     9.39 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      812 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.532 (0.266)    | 0 (0.000) |     2.71 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1057 | 2024-06-15 | Monte             | L   | 0.859      | -            | -                | -                | -         |   -22.64 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1068 | 2024-06-15 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |   -10.21 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1110 | 2024-06-14 | Monte             | W   | 0.851      | -            | -                | -                | 0 (0.000) |     3.91 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1140 | 2024-06-13 | Aurora Young Blud | W   | 0.845      | -            | -                | -                | -         |     1.72 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1166 | 2024-06-12 | B8                | W   | 0.839      | 0.143        | 0.165 (0.020)    | -                | -         |     5.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1212 | 2024-06-10 | Nemiga            | L   | 0.825      | -            | -                | -                | -         |   -19.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1262 | 2024-06-09 | MOUZ NXT          | W   | 0.819      | 0.500        | 0.139 (0.057)    | 0.987 (0.404)    | -         |     4.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1303 | 2024-06-08 | 9INE              | W   | 0.814      | 0.500        | -                | 0.533 (0.217)    | -         |     1.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1360 | 2024-06-07 | Rebels            | L   | 0.807      | -            | -                | -                | -         |   -22.43 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1509 | 2024-06-05 | Nexus             | W   | 0.792      | -            | -                | -                | -         |     0.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1600 | 2024-06-02 | The MongolZ       | L   | 0.772      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1604 | 2024-06-01 | Aurora            | W   | 0.770      | 0.500        | 0.422 (0.162)    | 0.779 (0.300)    | 1 (0.770) |    17.40 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1634 | 2024-06-01 | The MongolZ       | L   | 0.765      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1692 | 2024-05-29 | ATOX              | W   | 0.750      | -            | -                | -                | 1 (0.750) |     1.44 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1716 | 2024-05-28 | Chinggis Warriors | W   | 0.743      | -            | -                | -                | 1 (0.743) |     0.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1905 | 2024-05-21 | Zero Tenacity     | L   | 0.693      | -            | -                | -                | -         |   -18.11 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1938 | 2024-05-20 | 9 Pandas          | W   | 0.686      | 0.500        | 0.081 (0.028)    | 0.718 (0.246)    | -         |     2.61 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1975 | 2024-05-19 | MOUZ NXT          | W   | 0.678      | 0.500        | 0.139 (0.047)    | 0.987 (0.335)    | -         |     2.99 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2029 | 2024-05-17 | Monte             | L   | 0.666      | -            | -                | -                | -         |   -18.73 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2118 | 2024-05-15 | Gaimin Gladiators | L   | 0.652      | -            | -                | -                | -         |   -18.68 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2129 | 2024-05-15 | MOUZ NXT          | W   | 0.651      | 0.500        | 0.139 (0.045)    | 0.987 (0.321)    | -         |     2.30 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,509.84)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $2,000.00      | $1,732.78       |
| 2024-06-11 |      0.833 | $12,500.00     | $10,409.72      |
| 2024-06-02 |      0.772 | $25,000.00     | $19,287.62      |
| 2024-05-22 |      0.699 | $12,500.00     | $8,743.06       |
| 2024-05-18 |      0.673 | $500.00        | $336.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
