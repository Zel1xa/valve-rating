### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1292.4<br />
<br />
Final Rank Value (1292.4) = Starting Rank Value (1414.5) + Head To Head Adjustments (-122.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.527[<sup>1</sup>](#table2)
- Bounty Collected: 0.521[<sup>2</sup>](#table1)
- Opponent Network: 0.331[<sup>2</sup>](#table1)
- LAN Wins: 0.604[<sup>2</sup>](#table1)

The average of these factors is 0.496<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.5
- 400 + ( ( 0.496 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1414.5


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
|           32 |       26 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.95 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       36 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.77 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      108 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.33 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      263 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.018 (0.011)    | 0.553 (0.359)    | 1 (1.000) |     6.57 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      280 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |   -10.08 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      313 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.745 (0.485)    | 1 (1.000) |    28.50 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      342 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.24 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      348 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -13.50 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      475 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.83 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      607 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.318 (0.159)    | 0.719 (0.360)    | 0 (0.000) |     9.09 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      727 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.433 (0.217)    | 0 (0.000) |     2.35 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |      953 | 2024-06-15 | Monte             | L   | 0.873      | -            | -                | -                | -         |   -23.11 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |      964 | 2024-06-15 | 3DMAX             | L   | 0.871      | -            | -                | -                | -         |   -10.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |      999 | 2024-06-14 | Monte             | W   | 0.865      | -            | -                | -                | 0 (0.000) |     3.85 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1029 | 2024-06-13 | Aurora Young Blud | W   | 0.858      | -            | -                | -                | -         |     1.46 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1053 | 2024-06-12 | B8                | W   | 0.852      | 0.143        | 0.166 (0.020)    | -                | -         |     5.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1097 | 2024-06-10 | Nemiga            | L   | 0.839      | -            | -                | -                | -         |   -20.47 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1146 | 2024-06-09 | MOUZ NXT          | W   | 0.832      | 0.500        | 0.139 (0.058)    | 1.000 (0.416)    | -         |     4.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1185 | 2024-06-08 | 9INE              | W   | 0.827      | 0.500        | -                | 0.553 (0.228)    | -         |     1.91 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1239 | 2024-06-07 | Rebels            | L   | 0.820      | -            | -                | -                | -         |   -22.79 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1388 | 2024-06-05 | Nexus             | W   | 0.805      | -            | -                | -                | -         |     0.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1477 | 2024-06-02 | The MongolZ       | L   | 0.785      | -            | -                | -                | -         |    -1.33 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1481 | 2024-06-01 | Aurora            | W   | 0.783      | 0.500        | 0.425 (0.166)    | 0.809 (0.317)    | 1 (0.783) |    17.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1510 | 2024-06-01 | The MongolZ       | L   | 0.778      | -            | -                | -                | -         |    -1.21 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1568 | 2024-05-29 | ATOX              | W   | 0.763      | -            | -                | -                | 1 (0.763) |     1.47 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1592 | 2024-05-28 | Chinggis Warriors | W   | 0.756      | -            | -                | -                | 1 (0.756) |     0.68 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1780 | 2024-05-21 | Zero Tenacity     | L   | 0.706      | -            | -                | -                | -         |   -18.44 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1813 | 2024-05-20 | 9 Pandas          | W   | 0.699      | 0.500        | 0.082 (0.029)    | 0.715 (0.250)    | -         |     2.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1849 | 2024-05-19 | MOUZ NXT          | W   | 0.691      | 0.500        | 0.139 (0.048)    | 1.000 (0.346)    | -         |     2.99 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     1903 | 2024-05-17 | Monte             | L   | 0.679      | -            | -                | -                | -         |   -19.21 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     1992 | 2024-05-15 | Gaimin Gladiators | L   | 0.666      | -            | -                | -                | -         |   -19.01 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2003 | 2024-05-15 | MOUZ NXT          | W   | 0.664      | 0.500        | 0.139 (0.046)    | 1.000 (0.332)    | -         |     2.28 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,212.27)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.880 | $2,000.00      | $1,759.54       |
| 2024-06-11 |      0.846 | $12,500.00     | $10,576.97      |
| 2024-06-02 |      0.785 | $25,000.00     | $19,622.11      |
| 2024-05-22 |      0.713 | $12,500.00     | $8,910.30       |
| 2024-05-18 |      0.687 | $500.00        | $343.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
