### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1291.1<br />
<br />
Final Rank Value (1291.1) = Starting Rank Value (1409.5) + Head To Head Adjustments (-118.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.527[<sup>1</sup>](#table2)
- Bounty Collected: 0.521[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.605[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1409.5
- 400 + ( ( 0.494 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1409.5


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
|           32 |       35 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.94 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       46 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.52 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      133 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.45 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      289 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     6.65 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      306 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |   -10.02 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      339 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    28.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      368 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.24 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      374 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -13.00 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      501 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.56 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      633 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.159)    | 0.695 (0.347)    | 0 (0.000) |     9.17 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      756 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.420 (0.210)    | 0 (0.000) |     2.35 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1000 | 2024-06-15 | Monte             | L   | 0.868      | -            | -                | -                | -         |   -22.79 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1011 | 2024-06-15 | 3DMAX             | L   | 0.867      | -            | -                | -                | -         |   -10.35 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1053 | 2024-06-14 | Monte             | W   | 0.860      | -            | -                | -                | 0 (0.000) |     4.01 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1083 | 2024-06-13 | Aurora Young Blud | W   | 0.854      | -            | -                | -                | -         |     1.46 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1109 | 2024-06-12 | B8                | W   | 0.847      | 0.143        | 0.165 (0.020)    | -                | -         |     6.05 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1155 | 2024-06-10 | Nemiga            | L   | 0.834      | -            | -                | -                | -         |   -20.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1205 | 2024-06-09 | MOUZ NXT          | W   | 0.827      | 0.500        | 0.139 (0.058)    | 1.000 (0.414)    | -         |     4.80 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1246 | 2024-06-08 | 9INE              | W   | 0.822      | 0.500        | -                | 0.537 (0.221)    | -         |     1.92 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1303 | 2024-06-07 | Rebels            | L   | 0.816      | -            | -                | -                | -         |   -22.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1452 | 2024-06-05 | Nexus             | W   | 0.801      | -            | -                | -                | -         |     0.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1543 | 2024-06-02 | The MongolZ       | L   | 0.780      | -            | -                | -                | -         |    -1.31 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1547 | 2024-06-01 | Aurora            | W   | 0.778      | 0.500        | 0.424 (0.165)    | 0.793 (0.309)    | 1 (0.778) |    17.52 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1577 | 2024-06-01 | The MongolZ       | L   | 0.773      | -            | -                | -                | -         |    -1.20 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1635 | 2024-05-29 | ATOX              | W   | 0.758      | -            | -                | -                | 1 (0.758) |     1.50 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1659 | 2024-05-28 | Chinggis Warriors | W   | 0.752      | -            | -                | -                | 1 (0.752) |     0.69 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1848 | 2024-05-21 | Zero Tenacity     | L   | 0.701      | -            | -                | -                | -         |   -18.22 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1881 | 2024-05-20 | 9 Pandas          | W   | 0.695      | 0.500        | 0.082 (0.028)    | 0.690 (0.240)    | -         |     2.69 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1918 | 2024-05-19 | MOUZ NXT          | W   | 0.686      | 0.500        | 0.139 (0.048)    | 1.000 (0.343)    | -         |     3.06 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     1972 | 2024-05-17 | Monte             | L   | 0.675      | -            | -                | -                | -         |   -18.91 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2061 | 2024-05-15 | Gaimin Gladiators | L   | 0.661      | -            | -                | -                | -         |   -18.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2072 | 2024-05-15 | MOUZ NXT          | W   | 0.660      | 0.500        | 0.139 (0.046)    | 1.000 (0.330)    | -         |     2.35 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,961.92)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.875 | $2,000.00      | $1,750.00       |
| 2024-06-11 |      0.841 | $12,500.00     | $10,517.36      |
| 2024-06-02 |      0.780 | $25,000.00     | $19,502.89      |
| 2024-05-22 |      0.708 | $12,500.00     | $8,850.69       |
| 2024-05-18 |      0.682 | $500.00        | $340.97         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
