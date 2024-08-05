### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1298.1<br />
<br />
Final Rank Value (1298.1) = Starting Rank Value (1414.8) + Head To Head Adjustments (-116.7)<br />

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
|           32 |       90 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.99 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      102 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.50 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      190 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.20 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      347 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.565 (0.367)    | 1 (1.000) |     6.65 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      364 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.98 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      397 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    28.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      426 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.19 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      432 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.82 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      559 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.61 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      691 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.316 (0.158)    | 0.722 (0.361)    | 0 (0.000) |     9.40 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      813 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.532 (0.266)    | 0 (0.000) |     2.71 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1058 | 2024-06-15 | Monte             | L   | 0.859      | -            | -                | -                | -         |   -22.63 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1069 | 2024-06-15 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |   -10.18 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1111 | 2024-06-14 | Monte             | W   | 0.851      | -            | -                | -                | 0 (0.000) |     3.91 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1141 | 2024-06-13 | Aurora Young Blud | W   | 0.845      | -            | -                | -                | -         |     1.72 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1167 | 2024-06-12 | B8                | W   | 0.838      | 0.143        | 0.165 (0.020)    | -                | -         |     5.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1213 | 2024-06-10 | Nemiga            | L   | 0.825      | -            | -                | -                | -         |   -19.85 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1263 | 2024-06-09 | MOUZ NXT          | W   | 0.818      | 0.500        | 0.139 (0.057)    | 0.987 (0.404)    | -         |     4.75 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1304 | 2024-06-08 | 9INE              | W   | 0.813      | 0.500        | -                | 0.533 (0.217)    | -         |     1.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1361 | 2024-06-07 | Rebels            | L   | 0.807      | -            | -                | -                | -         |   -22.41 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1510 | 2024-06-05 | Nexus             | W   | 0.792      | -            | -                | -                | -         |     0.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1601 | 2024-06-02 | The MongolZ       | L   | 0.771      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1605 | 2024-06-01 | Aurora            | W   | 0.769      | 0.500        | 0.422 (0.162)    | 0.778 (0.299)    | 1 (0.769) |    17.40 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1635 | 2024-06-01 | The MongolZ       | L   | 0.764      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1693 | 2024-05-29 | ATOX              | W   | 0.749      | -            | -                | -                | 1 (0.749) |     1.44 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1717 | 2024-05-28 | Chinggis Warriors | W   | 0.743      | -            | -                | -                | 1 (0.743) |     0.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1906 | 2024-05-21 | Zero Tenacity     | L   | 0.692      | -            | -                | -                | -         |   -18.10 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1939 | 2024-05-20 | 9 Pandas          | W   | 0.686      | 0.500        | 0.081 (0.028)    | 0.717 (0.246)    | -         |     2.61 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1976 | 2024-05-19 | MOUZ NXT          | W   | 0.677      | 0.500        | 0.139 (0.047)    | 0.987 (0.334)    | -         |     2.99 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2030 | 2024-05-17 | Monte             | L   | 0.666      | -            | -                | -                | -         |   -18.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2119 | 2024-05-15 | Gaimin Gladiators | L   | 0.652      | -            | -                | -                | -         |   -18.67 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2130 | 2024-05-15 | MOUZ NXT          | W   | 0.651      | 0.500        | 0.139 (0.045)    | 0.987 (0.321)    | -         |     2.30 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,487.96)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $2,000.00      | $1,731.94       |
| 2024-06-11 |      0.832 | $12,500.00     | $10,404.51      |
| 2024-06-02 |      0.771 | $25,000.00     | $19,277.20      |
| 2024-05-22 |      0.699 | $12,500.00     | $8,737.85       |
| 2024-05-18 |      0.673 | $500.00        | $336.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
