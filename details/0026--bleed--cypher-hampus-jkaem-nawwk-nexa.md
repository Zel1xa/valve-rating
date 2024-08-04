### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1290.9<br />
<br />
Final Rank Value (1290.9) = Starting Rank Value (1409.4) + Head To Head Adjustments (-118.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.527[<sup>1</sup>](#table2)
- Bounty Collected: 0.521[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.604[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1409.4
- 400 + ( ( 0.494 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1409.4


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
|           32 |       31 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.94 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       42 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.56 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      130 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.48 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      286 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     6.66 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      303 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |   -10.04 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      336 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.720 (0.469)    | 1 (1.000) |    28.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      365 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.25 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      371 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.99 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      498 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.53 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      630 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.318 (0.159)    | 0.695 (0.348)    | 0 (0.000) |     9.19 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      753 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.419 (0.210)    | 0 (0.000) |     2.36 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |      996 | 2024-06-15 | Monte             | L   | 0.871      | -            | -                | -                | -         |   -22.85 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1007 | 2024-06-15 | 3DMAX             | L   | 0.870      | -            | -                | -                | -         |   -10.44 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1049 | 2024-06-14 | Monte             | W   | 0.863      | -            | -                | -                | 0 (0.000) |     4.04 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1079 | 2024-06-13 | Aurora Young Blud | W   | 0.857      | -            | -                | -                | -         |     1.47 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1105 | 2024-06-12 | B8                | W   | 0.851      | 0.143        | 0.165 (0.020)    | -                | -         |     6.09 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1151 | 2024-06-10 | Nemiga            | L   | 0.837      | -            | -                | -                | -         |   -20.36 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1201 | 2024-06-09 | MOUZ NXT          | W   | 0.830      | 0.500        | 0.139 (0.058)    | 1.000 (0.415)    | -         |     4.84 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1242 | 2024-06-08 | 9INE              | W   | 0.825      | 0.500        | -                | 0.535 (0.221)    | -         |     1.92 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1299 | 2024-06-07 | Rebels            | L   | 0.819      | -            | -                | -                | -         |   -22.65 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1448 | 2024-06-05 | Nexus             | W   | 0.804      | -            | -                | -                | -         |     0.77 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1539 | 2024-06-02 | The MongolZ       | L   | 0.783      | -            | -                | -                | -         |    -1.32 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1543 | 2024-06-01 | Aurora            | W   | 0.781      | 0.500        | 0.424 (0.166)    | 0.794 (0.310)    | 1 (0.781) |    17.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1573 | 2024-06-01 | The MongolZ       | L   | 0.776      | -            | -                | -                | -         |    -1.21 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1631 | 2024-05-29 | ATOX              | W   | 0.761      | -            | -                | -                | 1 (0.761) |     1.51 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1655 | 2024-05-28 | Chinggis Warriors | W   | 0.755      | -            | -                | -                | 1 (0.755) |     0.69 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1844 | 2024-05-21 | Zero Tenacity     | L   | 0.704      | -            | -                | -                | -         |   -18.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1877 | 2024-05-20 | 9 Pandas          | W   | 0.698      | 0.500        | 0.082 (0.028)    | 0.691 (0.241)    | -         |     2.79 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1914 | 2024-05-19 | MOUZ NXT          | W   | 0.689      | 0.500        | 0.139 (0.048)    | 1.000 (0.345)    | -         |     3.08 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     1968 | 2024-05-17 | Monte             | L   | 0.678      | -            | -                | -                | -         |   -18.99 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2057 | 2024-05-15 | Gaimin Gladiators | L   | 0.664      | -            | -                | -                | -         |   -18.94 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2068 | 2024-05-15 | MOUZ NXT          | W   | 0.663      | 0.500        | 0.139 (0.046)    | 1.000 (0.331)    | -         |     2.36 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,122.34)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.878 | $2,000.00      | $1,756.11       |
| 2024-06-11 |      0.844 | $12,500.00     | $10,555.56      |
| 2024-06-02 |      0.783 | $25,000.00     | $19,579.28      |
| 2024-05-22 |      0.711 | $12,500.00     | $8,888.89       |
| 2024-05-18 |      0.685 | $500.00        | $342.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
