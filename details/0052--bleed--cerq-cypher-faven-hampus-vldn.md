### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1055.3<br />
<br />
Final Rank Value (1055.3) = Starting Rank Value (956.6) + Head To Head Adjustments (98.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.488[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.203[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.271<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.6
- 400 + ( ( 0.271 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 956.6


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
|           42 |     2281 | 2024-05-11 | B8                | L   | 0.619      | -            | -                | -                | -         |    -9.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           41 |     2309 | 2024-05-09 | Sampi             | W   | 0.608      | 0.435        | -                | 1.000 (0.264)    | 0 (0.000) |     6.12 | CYPHER, draken, faveN, hampus, VLDN |
|           40 |     2351 | 2024-05-07 | 1WIN              | L   | 0.594      | -            | -                | -                | -         |   -12.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2375 | 2024-05-06 | Insilio           | W   | 0.586      | -            | -                | -                | 0 (0.000) |     6.31 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2439 | 2024-05-02 | AMKAL             | L   | 0.561      | -            | -                | -                | -         |    -6.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2475 | 2024-05-01 | MOUZ NXT          | L   | 0.553      | -            | -                | -                | -         |    -9.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2507 | 2024-04-30 | Permitta          | W   | 0.545      | 0.384        | -                | 0.919 (0.193)    | 0 (0.000) |     6.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2530 | 2024-04-28 | B8                | W   | 0.534      | 0.500        | 0.170 (0.046)    | 0.912 (0.244)    | 0 (0.000) |     7.79 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2580 | 2024-04-26 | ex-Guild Eagles   | W   | 0.521      | -            | -                | -                | 0 (0.000) |     3.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2588 | 2024-04-26 | DMS               | W   | 0.519      | -            | -                | -                | 0 (0.000) |     4.77 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2630 | 2024-04-24 | Permitta          | W   | 0.507      | 0.435        | 0.039 (0.009)    | 0.919 (0.203)    | 0 (0.000) |     6.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2631 | 2024-04-24 | Nemiga            | L   | 0.507      | -            | -                | -                | -         |    -5.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2650 | 2024-04-23 | B8                | W   | 0.500      | 0.500        | 0.170 (0.043)    | 0.912 (0.228)    | 0 (0.000) |     7.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2659 | 2024-04-23 | Sashi             | L   | 0.499      | -            | -                | -                | -         |    -5.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2667 | 2024-04-22 | Sangal            | W   | 0.494      | 0.500        | 0.219 (0.054)    | 0.846 (0.209)    | 0 (0.000) |     9.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2669 | 2024-04-22 | Gaimin Gladiators | W   | 0.493      | -            | -                | -                | 0 (0.000) |     7.54 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2684 | 2024-04-21 | Illuminar         | W   | 0.487      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2690 | 2024-04-21 | BIG               | W   | 0.486      | 0.384        | 0.154 (0.029)    | -                | -         |    12.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2713 | 2024-04-20 | MOUZ NXT          | W   | 0.480      | 0.500        | 0.139 (0.033)    | 0.962 (0.231)    | -         |     8.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2770 | 2024-04-19 | Sampi             | W   | 0.472      | 0.384        | -                | 1.000 (0.181)    | -         |     5.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2827 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.465      | -            | -                | -                | -         |     6.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2862 | 2024-04-17 | 3DMAX             | L   | 0.459      | -            | -                | -                | -         |    -0.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2881 | 2024-04-16 | KOI               | W   | 0.454      | 0.384        | 0.058 (0.010)    | -                | -         |     8.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2891 | 2024-04-16 | SINNERS           | W   | 0.452      | 0.384        | -                | 0.790 (0.137)    | -         |    10.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3071 | 2024-04-09 | Alliance          | W   | 0.407      | -            | -                | -                | -         |     4.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3079 | 2024-04-09 | HAVU              | W   | 0.406      | -            | -                | -                | -         |     2.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3163 | 2024-04-05 | BetBoom           | L   | 0.381      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3166 | 2024-04-05 | Alliance          | W   | 0.380      | -            | -                | -                | -         |     4.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3205 | 2024-04-04 | Benched Heroes    | W   | 0.374      | -            | -                | -                | -         |     0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3212 | 2024-04-04 | BetBoom           | L   | 0.373      | -            | -                | -                | -         |    -1.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3282 | 2024-04-02 | Passion UA        | W   | 0.360      | 0.384        | 0.173 (0.024)    | 1.000 (0.138)    | -         |     6.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3304 | 2024-04-01 | Enterprise        | L   | 0.353      | -            | -                | -                | -         |    -6.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3659 | 2024-03-13 | Sashi             | W   | 0.225      | -            | -                | -                | -         |     5.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3757 | 2024-03-09 | Endpoint          | W   | 0.199      | -            | -                | -                | -         |     2.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3824 | 2024-03-06 | fnatic            | L   | 0.180      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3870 | 2024-03-05 | BetBoom           | W   | 0.173      | 0.500        | 0.248 (0.021)    | -                | -         |     5.03 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3878 | 2024-03-04 | Rebels            | W   | 0.168      | -            | -                | -                | -         |     2.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3887 | 2024-03-04 | AURA              | W   | 0.165      | -            | -                | -                | -         |     0.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3951 | 2024-03-01 | Young Ninjas      | W   | 0.147      | -            | -                | -                | -         |     1.14 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            3 |     3966 | 2024-02-29 | AURA              | W   | 0.139      | -            | -                | -                | -         |     0.30 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            2 |     3982 | 2024-02-28 | BIG               | W   | 0.132      | 0.500        | 0.154 (0.010)    | -                | -         |     3.66 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            1 |     4017 | 2024-02-26 | MOUZ NXT          | L   | 0.120      | -            | -                | -                | -         |    -1.41 | CeRq, faveN, hampus, lauNX, VLDN    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,627.73)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.667 | $500.00        | $333.70         |
| 2024-05-12 |      0.627 | $2,000.00      | $1,254.68       |
| 2024-04-24 |      0.507 | $25,000.00     | $12,671.30      |
| 2024-04-22 |      0.493 | $20,000.00     | $9,856.48       |
| 2024-03-06 |      0.180 | $25,000.00     | $4,511.57       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
