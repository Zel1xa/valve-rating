### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1298.2<br />
<br />
Final Rank Value (1298.2) = Starting Rank Value (1414.7) + Head To Head Adjustments (-116.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.520[<sup>2</sup>](#table1)
- Opponent Network: 0.327[<sup>2</sup>](#table1)
- LAN Wins: 0.605[<sup>2</sup>](#table1)

The average of these factors is 0.495<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.7
- 400 + ( ( 0.495 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1414.7


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
|           32 |       92 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.99 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |      104 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.48 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      192 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.18 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      349 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.565 (0.367)    | 1 (1.000) |     6.65 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      366 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.96 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      399 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    28.51 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      428 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.18 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      434 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.83 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      561 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.62 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      693 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.315 (0.158)    | 0.721 (0.360)    | 0 (0.000) |     9.38 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      815 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.532 (0.266)    | 0 (0.000) |     2.70 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1060 | 2024-06-15 | Monte             | L   | 0.857      | -            | -                | -                | -         |   -22.59 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1071 | 2024-06-15 | 3DMAX             | L   | 0.856      | -            | -                | -                | -         |   -10.13 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1113 | 2024-06-14 | Monte             | W   | 0.849      | -            | -                | -                | 0 (0.000) |     3.90 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1143 | 2024-06-13 | Aurora Young Blud | W   | 0.843      | -            | -                | -                | -         |     1.71 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1169 | 2024-06-12 | B8                | W   | 0.837      | 0.143        | 0.164 (0.020)    | -                | -         |     5.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1215 | 2024-06-10 | Nemiga            | L   | 0.823      | -            | -                | -                | -         |   -19.82 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1265 | 2024-06-09 | MOUZ NXT          | W   | 0.816      | 0.500        | 0.139 (0.057)    | 0.986 (0.402)    | -         |     4.73 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1306 | 2024-06-08 | 9INE              | W   | 0.811      | 0.500        | -                | 0.533 (0.216)    | -         |     1.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1363 | 2024-06-07 | Rebels            | L   | 0.805      | -            | -                | -                | -         |   -22.37 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1512 | 2024-06-05 | Nexus             | W   | 0.790      | -            | -                | -                | -         |     0.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1603 | 2024-06-02 | The MongolZ       | L   | 0.769      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1607 | 2024-06-01 | Aurora            | W   | 0.768      | 0.500        | 0.421 (0.162)    | 0.777 (0.298)    | 1 (0.768) |    17.36 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1637 | 2024-06-01 | The MongolZ       | L   | 0.762      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1695 | 2024-05-29 | ATOX              | W   | 0.748      | -            | -                | -                | 1 (0.748) |     1.44 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1719 | 2024-05-28 | Chinggis Warriors | W   | 0.741      | -            | -                | -                | 1 (0.741) |     0.97 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1908 | 2024-05-21 | Zero Tenacity     | L   | 0.691      | -            | -                | -                | -         |   -18.06 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1941 | 2024-05-20 | 9 Pandas          | W   | 0.684      | 0.500        | 0.081 (0.028)    | 0.717 (0.245)    | -         |     2.59 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1978 | 2024-05-19 | MOUZ NXT          | W   | 0.676      | 0.500        | 0.139 (0.047)    | 0.986 (0.333)    | -         |     2.98 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2032 | 2024-05-17 | Monte             | L   | 0.664      | -            | -                | -                | -         |   -18.67 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2121 | 2024-05-15 | Gaimin Gladiators | L   | 0.650      | -            | -                | -                | -         |   -18.63 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2132 | 2024-05-15 | MOUZ NXT          | W   | 0.649      | 0.500        | 0.139 (0.045)    | 0.986 (0.320)    | -         |     2.29 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,393.17)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $2,000.00      | $1,728.33       |
| 2024-06-11 |      0.831 | $12,500.00     | $10,381.94      |
| 2024-06-02 |      0.769 | $25,000.00     | $19,232.06      |
| 2024-05-22 |      0.697 | $12,500.00     | $8,715.28       |
| 2024-05-18 |      0.671 | $500.00        | $335.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
