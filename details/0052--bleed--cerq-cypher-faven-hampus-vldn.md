### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1054.6<br />
<br />
Final Rank Value (1054.6) = Starting Rank Value (956.5) + Head To Head Adjustments (98.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.488[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.203[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.271<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.5
- 400 + ( ( 0.271 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 956.5


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
|           42 |     2271 | 2024-05-11 | B8                | L   | 0.619      | -            | -                | -                | -         |    -9.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           41 |     2299 | 2024-05-09 | Sampi             | W   | 0.608      | 0.435        | -                | 1.000 (0.264)    | 0 (0.000) |     6.10 | CYPHER, draken, faveN, hampus, VLDN |
|           40 |     2341 | 2024-05-07 | 1WIN              | L   | 0.594      | -            | -                | -                | -         |   -12.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2365 | 2024-05-06 | Insilio           | W   | 0.586      | -            | -                | -                | 0 (0.000) |     6.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2429 | 2024-05-02 | AMKAL             | L   | 0.561      | -            | -                | -                | -         |    -6.96 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2465 | 2024-05-01 | MOUZ NXT          | L   | 0.553      | -            | -                | -                | -         |    -9.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2497 | 2024-04-30 | Permitta          | W   | 0.545      | 0.384        | -                | 0.919 (0.193)    | 0 (0.000) |     5.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2520 | 2024-04-28 | B8                | W   | 0.535      | 0.500        | 0.170 (0.046)    | 0.912 (0.244)    | 0 (0.000) |     7.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2570 | 2024-04-26 | ex-Guild Eagles   | W   | 0.521      | -            | -                | -                | 0 (0.000) |     3.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2578 | 2024-04-26 | DMS               | W   | 0.520      | -            | -                | -                | 0 (0.000) |     4.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2620 | 2024-04-24 | Permitta          | W   | 0.508      | 0.435        | -                | 0.919 (0.203)    | 0 (0.000) |     6.42 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2621 | 2024-04-24 | Nemiga            | L   | 0.507      | -            | -                | -                | -         |    -5.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2640 | 2024-04-23 | B8                | W   | 0.500      | 0.500        | 0.170 (0.043)    | 0.912 (0.228)    | 0 (0.000) |     7.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2649 | 2024-04-23 | Sashi             | L   | 0.499      | -            | -                | -                | -         |    -5.63 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2657 | 2024-04-22 | Sangal            | W   | 0.494      | 0.500        | 0.219 (0.054)    | 0.846 (0.209)    | 0 (0.000) |     9.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2659 | 2024-04-22 | Gaimin Gladiators | W   | 0.493      | -            | -                | -                | 0 (0.000) |     7.52 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2674 | 2024-04-21 | Illuminar         | W   | 0.488      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2680 | 2024-04-21 | BIG               | W   | 0.486      | 0.384        | 0.154 (0.029)    | -                | -         |    12.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2703 | 2024-04-20 | MOUZ NXT          | W   | 0.480      | 0.500        | 0.139 (0.033)    | 0.962 (0.231)    | -         |     8.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2760 | 2024-04-19 | Sampi             | W   | 0.473      | 0.384        | -                | 1.000 (0.182)    | -         |     5.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2817 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.465      | 0.500        | 0.031 (0.007)    | -                | -         |     6.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2852 | 2024-04-17 | 3DMAX             | L   | 0.459      | -            | -                | -                | -         |    -0.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2871 | 2024-04-16 | KOI               | W   | 0.454      | 0.384        | 0.058 (0.010)    | -                | -         |     8.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2881 | 2024-04-16 | SINNERS           | W   | 0.452      | 0.384        | -                | 0.790 (0.137)    | -         |    10.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3061 | 2024-04-09 | Alliance          | W   | 0.407      | -            | -                | -                | -         |     4.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3069 | 2024-04-09 | HAVU              | W   | 0.406      | -            | -                | -                | -         |     2.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3153 | 2024-04-05 | BetBoom           | L   | 0.381      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3156 | 2024-04-05 | Alliance          | W   | 0.380      | -            | -                | -                | -         |     4.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3195 | 2024-04-04 | Benched Heroes    | W   | 0.374      | -            | -                | -                | -         |     0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3202 | 2024-04-04 | BetBoom           | L   | 0.373      | -            | -                | -                | -         |    -1.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3272 | 2024-04-02 | Passion UA        | W   | 0.361      | 0.384        | 0.173 (0.024)    | 1.000 (0.139)    | -         |     6.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3294 | 2024-04-01 | Enterprise        | L   | 0.353      | -            | -                | -                | -         |    -6.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3649 | 2024-03-13 | Sashi             | W   | 0.226      | -            | -                | -                | -         |     5.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3747 | 2024-03-09 | Endpoint          | W   | 0.199      | -            | -                | -                | -         |     2.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3814 | 2024-03-06 | fnatic            | L   | 0.181      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3860 | 2024-03-05 | BetBoom           | W   | 0.173      | 0.500        | 0.248 (0.021)    | -                | -         |     5.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3868 | 2024-03-04 | Rebels            | W   | 0.168      | -            | -                | -                | -         |     2.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3877 | 2024-03-04 | AURA              | W   | 0.166      | -            | -                | -                | -         |     0.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3941 | 2024-03-01 | Young Ninjas      | W   | 0.147      | -            | -                | -                | -         |     1.14 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            3 |     3956 | 2024-02-29 | AURA              | W   | 0.139      | -            | -                | -                | -         |     0.30 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            2 |     3972 | 2024-02-28 | BIG               | W   | 0.132      | 0.500        | 0.154 (0.010)    | -                | -         |     3.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            1 |     4007 | 2024-02-26 | MOUZ NXT          | L   | 0.120      | -            | -                | -                | -         |    -1.42 | CeRq, faveN, hampus, lauNX, VLDN    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,647.87)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.668 | $500.00        | $333.84         |
| 2024-05-12 |      0.628 | $2,000.00      | $1,255.23       |
| 2024-04-24 |      0.507 | $25,000.00     | $12,678.24      |
| 2024-04-22 |      0.493 | $20,000.00     | $9,862.04       |
| 2024-03-06 |      0.181 | $25,000.00     | $4,518.52       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
