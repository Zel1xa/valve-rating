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
Final Rank Value (1055.3) = Starting Rank Value (957.7) + Head To Head Adjustments (97.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.490[<sup>1</sup>](#table2)
- Bounty Collected: 0.393[<sup>2</sup>](#table1)
- Opponent Network: 0.208[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.7
- 400 + ( ( 0.273 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 957.7


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
|           43 |     2205 | 2024-05-11 | B8                | L   | 0.633      | -            | -                | -                | -         |    -9.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2233 | 2024-05-09 | Sampi             | W   | 0.622      | 0.435        | -                | 1.000 (0.270)    | 0 (0.000) |     6.22 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2275 | 2024-05-07 | 1WIN              | L   | 0.608      | -            | -                | -                | -         |   -13.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2299 | 2024-05-06 | Insilio           | W   | 0.600      | -            | -                | -                | 0 (0.000) |     6.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2363 | 2024-05-02 | AMKAL             | L   | 0.576      | -            | -                | -                | -         |    -7.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2399 | 2024-05-01 | MOUZ NXT          | L   | 0.567      | -            | -                | -                | -         |    -9.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2431 | 2024-04-30 | Permitta          | W   | 0.560      | 0.384        | -                | 0.876 (0.188)    | 0 (0.000) |     5.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2454 | 2024-04-28 | B8                | W   | 0.549      | 0.500        | 0.165 (0.045)    | 0.912 (0.250)    | 0 (0.000) |     7.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2504 | 2024-04-26 | ex-Guild Eagles   | W   | 0.535      | -            | -                | -                | 0 (0.000) |     4.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2512 | 2024-04-26 | DMS               | W   | 0.534      | -            | -                | -                | 0 (0.000) |     4.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2554 | 2024-04-24 | Permitta          | W   | 0.522      | 0.435        | -                | 0.876 (0.199)    | 0 (0.000) |     6.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2555 | 2024-04-24 | Nemiga            | L   | 0.521      | -            | -                | -                | -         |    -5.96 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2574 | 2024-04-23 | B8                | W   | 0.515      | 0.500        | 0.165 (0.043)    | 0.912 (0.235)    | 0 (0.000) |     7.84 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2583 | 2024-04-23 | Sashi             | L   | 0.513      | -            | -                | -                | -         |    -5.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2591 | 2024-04-22 | Sangal            | W   | 0.508      | 0.500        | 0.219 (0.056)    | 0.862 (0.219)    | 0 (0.000) |     9.57 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2593 | 2024-04-22 | Gaimin Gladiators | W   | 0.507      | -            | -                | -                | 0 (0.000) |     7.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2608 | 2024-04-21 | Illuminar         | W   | 0.502      | -            | -                | -                | -         |     0.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2614 | 2024-04-21 | BIG               | W   | 0.500      | 0.384        | 0.155 (0.030)    | -                | -         |    12.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2637 | 2024-04-20 | MOUZ NXT          | W   | 0.495      | 0.500        | 0.139 (0.034)    | 1.000 (0.247)    | -         |     8.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2694 | 2024-04-19 | Sampi             | W   | 0.487      | 0.384        | -                | 1.000 (0.187)    | -         |     5.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2751 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.480      | 0.500        | 0.031 (0.008)    | -                | -         |     6.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2786 | 2024-04-17 | 3DMAX             | L   | 0.473      | -            | -                | -                | -         |    -0.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2805 | 2024-04-16 | KOI               | W   | 0.468      | 0.384        | 0.058 (0.011)    | -                | -         |     8.99 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2815 | 2024-04-16 | SINNERS           | W   | 0.466      | 0.384        | -                | 0.758 (0.136)    | -         |     9.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2995 | 2024-04-09 | Alliance          | W   | 0.422      | -            | -                | -                | -         |     4.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3003 | 2024-04-09 | HAVU              | W   | 0.421      | -            | -                | -                | -         |     2.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3087 | 2024-04-05 | BetBoom           | L   | 0.395      | -            | -                | -                | -         |    -1.10 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3090 | 2024-04-05 | Alliance          | W   | 0.394      | -            | -                | -                | -         |     4.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3129 | 2024-04-04 | Benched Heroes    | W   | 0.388      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3136 | 2024-04-04 | BetBoom           | L   | 0.388      | -            | -                | -                | -         |    -1.06 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3206 | 2024-04-02 | Passion UA        | W   | 0.375      | 0.384        | 0.172 (0.025)    | 1.000 (0.144)    | -         |     6.89 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3228 | 2024-04-01 | Enterprise        | L   | 0.367      | -            | -                | -                | -         |    -6.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3583 | 2024-03-13 | Sashi             | W   | 0.240      | -            | -                | -                | -         |     5.31 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3681 | 2024-03-09 | Endpoint          | W   | 0.213      | -            | -                | -                | -         |     2.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3748 | 2024-03-06 | fnatic            | L   | 0.195      | -            | -                | -                | -         |    -0.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3794 | 2024-03-05 | BetBoom           | W   | 0.188      | 0.500        | 0.251 (0.024)    | -                | -         |     5.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3802 | 2024-03-04 | Rebels            | W   | 0.182      | -            | -                | -                | -         |     3.16 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3811 | 2024-03-04 | AURA              | W   | 0.180      | -            | -                | -                | -         |     0.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3875 | 2024-03-01 | Young Ninjas      | W   | 0.162      | -            | -                | -                | -         |     1.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3890 | 2024-02-29 | AURA              | W   | 0.154      | -            | -                | -                | -         |     0.34 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3906 | 2024-02-28 | BIG               | W   | 0.147      | 0.500        | 0.155 (0.011)    | -                | -         |     4.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3941 | 2024-02-26 | MOUZ NXT          | L   | 0.134      | -            | -                | -                | -         |    -1.61 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4342 | 2024-02-08 | Passion UA        | W   | 0.014      | -            | -                | -                | -         |     0.29 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,681.67)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.682 | $500.00        | $340.97         |
| 2024-05-12 |      0.642 | $2,000.00      | $1,283.75       |
| 2024-04-24 |      0.521 | $25,000.00     | $13,034.72      |
| 2024-04-22 |      0.507 | $20,000.00     | $10,147.22      |
| 2024-03-06 |      0.195 | $25,000.00     | $4,875.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
