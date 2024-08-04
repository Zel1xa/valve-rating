### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1056.7<br />
<br />
Final Rank Value (1056.7) = Starting Rank Value (957.6) + Head To Head Adjustments (99.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.490[<sup>1</sup>](#table2)
- Bounty Collected: 0.393[<sup>2</sup>](#table1)
- Opponent Network: 0.208[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.6
- 400 + ( ( 0.273 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 957.6


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
|           43 |     2236 | 2024-05-11 | B8                | L   | 0.632      | -            | -                | -                | -         |    -9.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2264 | 2024-05-09 | Sampi             | W   | 0.621      | 0.435        | -                | 1.000 (0.270)    | 0 (0.000) |     6.20 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2306 | 2024-05-07 | 1WIN              | L   | 0.607      | -            | -                | -                | -         |   -12.62 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2330 | 2024-05-06 | Insilio           | W   | 0.599      | -            | -                | -                | 0 (0.000) |     6.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2394 | 2024-05-02 | AMKAL             | L   | 0.574      | -            | -                | -                | -         |    -7.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2430 | 2024-05-01 | MOUZ NXT          | L   | 0.566      | -            | -                | -                | -         |    -9.64 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2462 | 2024-04-30 | Permitta          | W   | 0.558      | 0.384        | -                | 0.876 (0.188)    | 0 (0.000) |     5.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2485 | 2024-04-28 | B8                | W   | 0.547      | 0.500        | 0.165 (0.045)    | 0.912 (0.250)    | 0 (0.000) |     7.82 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2535 | 2024-04-26 | ex-Guild Eagles   | W   | 0.534      | -            | -                | -                | 0 (0.000) |     3.97 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2543 | 2024-04-26 | DMS               | W   | 0.532      | -            | -                | -                | 0 (0.000) |     4.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2585 | 2024-04-24 | Permitta          | W   | 0.520      | 0.435        | -                | 0.876 (0.198)    | 0 (0.000) |     6.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2586 | 2024-04-24 | Nemiga            | L   | 0.520      | -            | -                | -                | -         |    -5.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2605 | 2024-04-23 | B8                | W   | 0.513      | 0.500        | 0.165 (0.042)    | 0.912 (0.234)    | 0 (0.000) |     7.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2614 | 2024-04-23 | Sashi             | L   | 0.512      | -            | -                | -                | -         |    -5.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2622 | 2024-04-22 | Sangal            | W   | 0.507      | 0.500        | 0.219 (0.055)    | 0.861 (0.218)    | 0 (0.000) |     9.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2624 | 2024-04-22 | Gaimin Gladiators | W   | 0.506      | -            | -                | -                | 0 (0.000) |     7.82 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2639 | 2024-04-21 | Illuminar         | W   | 0.501      | -            | -                | -                | -         |     0.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2645 | 2024-04-21 | BIG               | W   | 0.499      | 0.384        | 0.155 (0.030)    | -                | -         |    12.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2668 | 2024-04-20 | MOUZ NXT          | W   | 0.493      | 0.500        | 0.139 (0.034)    | 1.000 (0.247)    | -         |     8.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2725 | 2024-04-19 | Sampi             | W   | 0.485      | 0.384        | -                | 1.000 (0.187)    | -         |     5.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2782 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.478      | 0.500        | 0.031 (0.008)    | -                | -         |     6.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2817 | 2024-04-17 | 3DMAX             | L   | 0.472      | -            | -                | -                | -         |    -0.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2836 | 2024-04-16 | KOI               | W   | 0.467      | 0.384        | 0.058 (0.010)    | -                | -         |     8.97 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2846 | 2024-04-16 | SINNERS           | W   | 0.465      | 0.384        | -                | 0.797 (0.142)    | -         |    10.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3026 | 2024-04-09 | Alliance          | W   | 0.420      | -            | -                | -                | -         |     4.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3034 | 2024-04-09 | HAVU              | W   | 0.419      | -            | -                | -                | -         |     2.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3118 | 2024-04-05 | BetBoom           | L   | 0.394      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3121 | 2024-04-05 | Alliance          | W   | 0.393      | -            | -                | -                | -         |     4.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3160 | 2024-04-04 | Benched Heroes    | W   | 0.387      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3167 | 2024-04-04 | BetBoom           | L   | 0.386      | -            | -                | -                | -         |    -1.06 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3237 | 2024-04-02 | Passion UA        | W   | 0.373      | 0.384        | 0.172 (0.025)    | 1.000 (0.143)    | -         |     6.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3259 | 2024-04-01 | Enterprise        | L   | 0.366      | -            | -                | -                | -         |    -6.90 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3614 | 2024-03-13 | Sashi             | W   | 0.239      | -            | -                | -                | -         |     5.31 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3712 | 2024-03-09 | Endpoint          | W   | 0.212      | -            | -                | -                | -         |     2.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3779 | 2024-03-06 | fnatic            | L   | 0.194      | -            | -                | -                | -         |    -0.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3825 | 2024-03-05 | BetBoom           | W   | 0.186      | 0.500        | 0.251 (0.023)    | -                | -         |     5.42 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3833 | 2024-03-04 | Rebels            | W   | 0.181      | -            | -                | -                | -         |     3.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3842 | 2024-03-04 | AURA              | W   | 0.179      | -            | -                | -                | -         |     0.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3906 | 2024-03-01 | Young Ninjas      | W   | 0.160      | -            | -                | -                | -         |     1.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3921 | 2024-02-29 | AURA              | W   | 0.152      | -            | -                | -                | -         |     0.34 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3937 | 2024-02-28 | BIG               | W   | 0.145      | 0.500        | 0.155 (0.011)    | -                | -         |     4.03 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3972 | 2024-02-26 | MOUZ NXT          | L   | 0.133      | -            | -                | -                | -         |    -1.59 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4373 | 2024-02-08 | Passion UA        | W   | 0.012      | -            | -                | -                | -         |     0.26 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,574.26)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.680 | $500.00        | $340.23         |
| 2024-05-12 |      0.640 | $2,000.00      | $1,280.79       |
| 2024-04-24 |      0.520 | $25,000.00     | $12,997.69      |
| 2024-04-22 |      0.506 | $20,000.00     | $10,117.59      |
| 2024-03-06 |      0.194 | $25,000.00     | $4,837.96       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
