### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1055.2<br />
<br />
Final Rank Value (1055.2) = Starting Rank Value (965.7) + Head To Head Adjustments (89.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.395[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 965.7
- 400 + ( ( 0.275 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 965.7


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
|           44 |     2177 | 2024-05-11 | B8                | L   | 0.652      | -            | -                | -                | -         |   -10.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           43 |     2205 | 2024-05-09 | Sampi             | W   | 0.642      | 0.435        | -                | 1.000 (0.279)    | 0 (0.000) |     6.30 | CYPHER, draken, faveN, hampus, VLDN |
|           42 |     2249 | 2024-05-07 | 1WIN              | L   | 0.628      | -            | -                | -                | -         |   -13.51 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           41 |     2273 | 2024-05-06 | Insilio           | W   | 0.620      | -            | -                | -                | 0 (0.000) |     6.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2337 | 2024-05-02 | AMKAL             | L   | 0.595      | -            | -                | -                | -         |    -7.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2375 | 2024-05-01 | MOUZ NXT          | L   | 0.587      | -            | -                | -                | -         |    -9.66 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2408 | 2024-04-30 | Permitta          | W   | 0.579      | 0.384        | -                | 0.801 (0.178)    | 0 (0.000) |     5.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2431 | 2024-04-28 | B8                | W   | 0.568      | 0.500        | 0.168 (0.048)    | 0.878 (0.250)    | 0 (0.000) |     8.12 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2482 | 2024-04-26 | ex-Guild Eagles   | W   | 0.555      | -            | -                | -                | 0 (0.000) |     4.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2489 | 2024-04-26 | DMS               | W   | 0.553      | -            | -                | -                | 0 (0.000) |     5.17 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2531 | 2024-04-24 | Permitta          | W   | 0.541      | 0.435        | -                | 0.801 (0.189)    | 0 (0.000) |     6.72 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2532 | 2024-04-24 | Nemiga            | L   | 0.541      | -            | -                | -                | -         |    -6.11 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2547 | 2024-04-23 | MOUZ NXT          | L   | 0.536      | -            | -                | -                | -         |    -8.81 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2553 | 2024-04-23 | B8                | W   | 0.534      | 0.500        | 0.168 (0.045)    | 0.878 (0.234)    | 0 (0.000) |     7.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2562 | 2024-04-23 | Sashi             | L   | 0.533      | -            | -                | -                | -         |    -6.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2571 | 2024-04-22 | Sangal            | W   | 0.527      | 0.500        | 0.221 (0.058)    | 0.823 (0.217)    | 0 (0.000) |     9.63 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2573 | 2024-04-22 | Gaimin Gladiators | W   | 0.527      | 0.384        | 0.040 (0.008)    | -                | 0 (0.000) |     8.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2589 | 2024-04-21 | Illuminar         | W   | 0.521      | -            | -                | -                | -         |     0.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2595 | 2024-04-21 | BIG               | W   | 0.520      | 0.384        | 0.132 (0.026)    | -                | -         |    12.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2620 | 2024-04-20 | MOUZ NXT          | W   | 0.514      | 0.500        | 0.141 (0.036)    | 1.000 (0.257)    | -         |     8.97 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2678 | 2024-04-19 | Sampi             | W   | 0.506      | 0.384        | -                | 1.000 (0.195)    | -         |     5.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2736 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.499      | 0.500        | 0.032 (0.008)    | -                | -         |     6.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2772 | 2024-04-17 | 3DMAX             | L   | 0.493      | -            | -                | -                | -         |    -0.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2791 | 2024-04-16 | KOI               | W   | 0.488      | -            | -                | -                | -         |     6.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2802 | 2024-04-16 | SINNERS           | W   | 0.486      | 0.384        | -                | 0.768 (0.143)    | -         |     9.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2983 | 2024-04-09 | Alliance          | W   | 0.441      | -            | -                | -                | -         |     4.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     2991 | 2024-04-09 | HAVU              | W   | 0.440      | -            | -                | -                | -         |     2.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3075 | 2024-04-05 | BetBoom           | L   | 0.415      | -            | -                | -                | -         |    -1.14 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3078 | 2024-04-05 | Alliance          | W   | 0.414      | -            | -                | -                | -         |     4.31 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3117 | 2024-04-04 | Benched Heroes    | W   | 0.408      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3125 | 2024-04-04 | BetBoom           | L   | 0.407      | -            | -                | -                | -         |    -1.10 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3202 | 2024-04-02 | Passion UA        | W   | 0.394      | 0.384        | 0.172 (0.026)    | 1.000 (0.152)    | -         |     7.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3224 | 2024-04-01 | Enterprise        | L   | 0.387      | -            | -                | -                | -         |    -7.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3588 | 2024-03-13 | Sashi             | W   | 0.259      | -            | -                | -                | -         |     5.72 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3688 | 2024-03-09 | Endpoint          | W   | 0.233      | -            | -                | -                | -         |     2.99 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3755 | 2024-03-06 | fnatic            | L   | 0.214      | -            | -                | -                | -         |    -0.73 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3806 | 2024-03-05 | BetBoom           | W   | 0.207      | 0.500        | 0.257 (0.027)    | -                | -         |     6.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3814 | 2024-03-04 | Rebels            | W   | 0.202      | -            | -                | -                | -         |     3.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3823 | 2024-03-04 | AURA              | W   | 0.199      | -            | -                | -                | -         |     0.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3888 | 2024-03-01 | Young Ninjas      | W   | 0.181      | -            | -                | -                | -         |     1.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3903 | 2024-02-29 | AURA              | W   | 0.173      | -            | -                | -                | -         |     0.38 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3920 | 2024-02-28 | BIG               | W   | 0.166      | 0.500        | 0.132 (0.011)    | -                | -         |     4.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3955 | 2024-02-26 | MOUZ NXT          | L   | 0.154      | -            | -                | -                | -         |    -1.77 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4374 | 2024-02-08 | Passion UA        | W   | 0.033      | -            | -                | -                | -         |     0.70 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,091.39)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.701 | $500.00        | $350.69         |
| 2024-05-12 |      0.661 | $2,000.00      | $1,322.64       |
| 2024-04-24 |      0.541 | $25,000.00     | $13,520.83      |
| 2024-04-22 |      0.527 | $20,000.00     | $10,536.11      |
| 2024-03-06 |      0.214 | $25,000.00     | $5,361.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
