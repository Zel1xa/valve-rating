### Roster Details<br />
Team Name: BLEED<br />
Roster: CYPHER, hampus, jkaem, nawwk, nexa<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1296.3<br />
<br />
Final Rank Value (1296.3) = Starting Rank Value (1413.3) + Head To Head Adjustments (-116.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.520[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.605[<sup>2</sup>](#table1)

The average of these factors is 0.495<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1413.3
- 400 + ( ( 0.495 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1413.3


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
|           32 |       82 | 2024-08-02 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.98 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           31 |       93 | 2024-08-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.50 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           30 |      182 | 2024-07-31 | AMKAL             | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    10.24 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           29 |      338 | 2024-07-26 | PARIVISION        | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.532 (0.346)    | 1 (1.000) |     6.64 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           28 |      355 | 2024-07-26 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -9.99 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           27 |      388 | 2024-07-25 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    28.54 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           26 |      417 | 2024-07-24 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.20 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           25 |      423 | 2024-07-24 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -12.84 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           24 |      550 | 2024-07-20 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -24.59 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           23 |      682 | 2024-07-17 | Nemiga            | W   | 1.000      | 0.500        | 0.316 (0.158)    | 0.731 (0.365)    | 0 (0.000) |     9.41 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           22 |      804 | 2024-07-15 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.499 (0.249)    | 0 (0.000) |     2.49 | CYPHER, hampus, jkaem, nawwk, nexa  |
|           21 |     1049 | 2024-06-15 | Monte             | L   | 0.861      | -            | -                | -                | -         |   -22.64 | CYPHER, faveN, hampus, jkaem, nawwk |
|           20 |     1060 | 2024-06-15 | 3DMAX             | L   | 0.859      | -            | -                | -                | -         |   -10.21 | CYPHER, faveN, hampus, jkaem, nawwk |
|           19 |     1102 | 2024-06-14 | Monte             | W   | 0.853      | -            | -                | -                | 0 (0.000) |     3.94 | CYPHER, faveN, hampus, jkaem, nawwk |
|           18 |     1132 | 2024-06-13 | Aurora Young Blud | W   | 0.846      | -            | -                | -                | -         |     1.56 | CYPHER, faveN, hampus, jkaem, nawwk |
|           17 |     1158 | 2024-06-12 | B8                | W   | 0.840      | 0.143        | 0.165 (0.020)    | -                | -         |     5.92 | CYPHER, faveN, hampus, jkaem, nawwk |
|           16 |     1204 | 2024-06-10 | Nemiga            | L   | 0.826      | -            | -                | -                | -         |   -19.86 | CYPHER, faveN, hampus, jkaem, nawwk |
|           15 |     1254 | 2024-06-09 | MOUZ NXT          | W   | 0.820      | 0.500        | 0.139 (0.057)    | 1.000 (0.410)    | -         |     4.76 | CYPHER, faveN, hampus, jkaem, nawwk |
|           14 |     1295 | 2024-06-08 | 9INE              | W   | 0.815      | 0.500        | -                | 0.539 (0.219)    | -         |     1.87 | CYPHER, faveN, hampus, jkaem, nawwk |
|           13 |     1352 | 2024-06-07 | Rebels            | L   | 0.808      | -            | -                | -                | -         |   -22.43 | CYPHER, faveN, hampus, jkaem, nawwk |
|           12 |     1501 | 2024-06-05 | Nexus             | W   | 0.793      | -            | -                | -                | -         |     0.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|           11 |     1592 | 2024-06-02 | The MongolZ       | L   | 0.773      | -            | -                | -                | -         |    -1.29 | CYPHER, faveN, hampus, jkaem, nawwk |
|           10 |     1596 | 2024-06-01 | Aurora            | W   | 0.771      | 0.500        | 0.422 (0.163)    | 0.788 (0.304)    | 1 (0.771) |    17.40 | CYPHER, faveN, hampus, jkaem, nawwk |
|            9 |     1626 | 2024-06-01 | The MongolZ       | L   | 0.766      | -            | -                | -                | -         |    -1.18 | CYPHER, faveN, hampus, jkaem, nawwk |
|            8 |     1684 | 2024-05-29 | ATOX              | W   | 0.751      | -            | -                | -                | 1 (0.751) |     1.46 | CYPHER, faveN, hampus, jkaem, nawwk |
|            7 |     1708 | 2024-05-28 | Chinggis Warriors | W   | 0.744      | -            | -                | -                | 1 (0.744) |     0.98 | CYPHER, faveN, hampus, jkaem, nawwk |
|            6 |     1897 | 2024-05-21 | Zero Tenacity     | L   | 0.694      | -            | -                | -                | -         |   -18.11 | CYPHER, faveN, hampus, jkaem, nawwk |
|            5 |     1930 | 2024-05-20 | 9 Pandas          | W   | 0.687      | 0.500        | 0.081 (0.028)    | 0.727 (0.250)    | -         |     2.62 | CYPHER, faveN, hampus, jkaem, nawwk |
|            4 |     1967 | 2024-05-19 | MOUZ NXT          | W   | 0.679      | 0.500        | 0.139 (0.047)    | 1.000 (0.339)    | -         |     3.01 | CYPHER, faveN, hampus, jkaem, nawwk |
|            3 |     2021 | 2024-05-17 | Monte             | L   | 0.667      | -            | -                | -                | -         |   -18.74 | CYPHER, faveN, hampus, jkaem, nawwk |
|            2 |     2110 | 2024-05-15 | Gaimin Gladiators | L   | 0.653      | -            | -                | -                | -         |   -18.70 | CYPHER, faveN, hampus, jkaem, nawwk |
|            1 |     2121 | 2024-05-15 | MOUZ NXT          | W   | 0.652      | 0.500        | 0.139 (0.045)    | 1.000 (0.326)    | -         |     2.31 | CYPHER, faveN, hampus, jkaem, nawwk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,568.17)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.868 | $2,000.00      | $1,735.00       |
| 2024-06-11 |      0.834 | $12,500.00     | $10,423.61      |
| 2024-06-02 |      0.773 | $25,000.00     | $19,315.39      |
| 2024-05-22 |      0.701 | $12,500.00     | $8,756.94       |
| 2024-05-18 |      0.674 | $500.00        | $337.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
