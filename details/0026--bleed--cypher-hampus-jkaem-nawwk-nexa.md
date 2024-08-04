### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1292.6<br />
<br />
Final Rank Value (1292.6) = Starting Rank Value (1410.5) + Head To Head Adjustments (-117.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.527[<sup>1</sup>](#table2)
- Bounty Collected: 0.521[<sup>2</sup>](#table1)
- Opponent Network: 0.325[<sup>2</sup>](#table1)
- LAN Wins: 0.605[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1410.5
- 400 + ( ( 0.494 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1410.5


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
|           32 |       43 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.95 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       54 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.52 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      141 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.43 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      297 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     6.63 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      314 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |   -10.00 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      347 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    28.55 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      376 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.23 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      382 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.90 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      509 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.57 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      641 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.159)    | 0.695 (0.347)    | 0 (0.000) |     9.15 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      764 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.459 (0.230)    | 0 (0.000) |     2.53 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1008 | 2024-06-15 | Monte             | L   | 0.867      | -            | -                | -                | -         |   -22.77 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1019 | 2024-06-15 | 3DMAX             | L   | 0.866      | -            | -                | -                | -         |   -10.34 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1061 | 2024-06-14 | Monte             | W   | 0.859      | -            | -                | -                | 0 (0.000) |     4.01 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1091 | 2024-06-13 | Aurora Young Blud | W   | 0.853      | -            | -                | -                | -         |     1.59 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1117 | 2024-06-12 | B8                | W   | 0.847      | 0.143        | 0.165 (0.020)    | -                | -         |     6.02 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1163 | 2024-06-10 | Nemiga            | L   | 0.833      | -            | -                | -                | -         |   -20.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1213 | 2024-06-09 | MOUZ NXT          | W   | 0.827      | 0.500        | 0.139 (0.057)    | 1.000 (0.413)    | -         |     4.80 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1254 | 2024-06-08 | 9INE              | W   | 0.822      | 0.500        | -                | 0.537 (0.221)    | -         |     1.91 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1311 | 2024-06-07 | Rebels            | L   | 0.815      | -            | -                | -                | -         |   -22.57 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1460 | 2024-06-05 | Nexus             | W   | 0.800      | -            | -                | -                | -         |     0.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1551 | 2024-06-02 | The MongolZ       | L   | 0.779      | -            | -                | -                | -         |    -1.30 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1555 | 2024-06-01 | Aurora            | W   | 0.778      | 0.500        | 0.423 (0.165)    | 0.793 (0.308)    | 1 (0.778) |    17.54 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1585 | 2024-06-01 | The MongolZ       | L   | 0.773      | -            | -                | -                | -         |    -1.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1643 | 2024-05-29 | ATOX              | W   | 0.758      | -            | -                | -                | 1 (0.758) |     1.50 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1667 | 2024-05-28 | Chinggis Warriors | W   | 0.751      | -            | -                | -                | 1 (0.751) |     0.69 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1856 | 2024-05-21 | Zero Tenacity     | L   | 0.701      | -            | -                | -                | -         |   -18.21 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1889 | 2024-05-20 | 9 Pandas          | W   | 0.694      | 0.500        | 0.082 (0.028)    | 0.690 (0.240)    | -         |     2.69 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1926 | 2024-05-19 | MOUZ NXT          | W   | 0.686      | 0.500        | 0.139 (0.048)    | 1.000 (0.343)    | -         |     3.05 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     1980 | 2024-05-17 | Monte             | L   | 0.674      | -            | -                | -                | -         |   -18.90 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2069 | 2024-05-15 | Gaimin Gladiators | L   | 0.660      | -            | -                | -                | -         |   -18.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2080 | 2024-05-15 | MOUZ NXT          | W   | 0.659      | 0.500        | 0.139 (0.046)    | 1.000 (0.330)    | -         |     2.34 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,924.25)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $2,000.00      | $1,748.56       |
| 2024-06-11 |      0.841 | $12,500.00     | $10,508.39      |
| 2024-06-02 |      0.779 | $25,000.00     | $19,484.95      |
| 2024-05-22 |      0.707 | $12,500.00     | $8,841.72       |
| 2024-05-18 |      0.681 | $500.00        | $340.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
