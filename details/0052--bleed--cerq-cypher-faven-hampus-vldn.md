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
Final Rank Value (1055.3) = Starting Rank Value (957.0) + Head To Head Adjustments (98.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.489[<sup>1</sup>](#table2)
- Bounty Collected: 0.392[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.0
- 400 + ( ( 0.272 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 957.0


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
|           43 |     2254 | 2024-05-11 | B8                | L   | 0.626      | -            | -                | -                | -         |    -9.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2282 | 2024-05-09 | Sampi             | W   | 0.615      | 0.435        | -                | 1.000 (0.267)    | 0 (0.000) |     6.15 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2324 | 2024-05-07 | 1WIN              | L   | 0.601      | -            | -                | -                | -         |   -12.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2348 | 2024-05-06 | Insilio           | W   | 0.593      | -            | -                | -                | 0 (0.000) |     6.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2412 | 2024-05-02 | AMKAL             | L   | 0.568      | -            | -                | -                | -         |    -7.10 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2448 | 2024-05-01 | MOUZ NXT          | L   | 0.560      | -            | -                | -                | -         |    -9.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2480 | 2024-04-30 | Permitta          | W   | 0.552      | 0.384        | -                | 0.873 (0.185)    | 0 (0.000) |     5.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2503 | 2024-04-28 | B8                | W   | 0.541      | 0.500        | 0.165 (0.045)    | 0.947 (0.256)    | 0 (0.000) |     7.79 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2553 | 2024-04-26 | ex-Guild Eagles   | W   | 0.528      | -            | -                | -                | 0 (0.000) |     3.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2561 | 2024-04-26 | DMS               | W   | 0.526      | -            | -                | -                | 0 (0.000) |     4.84 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2603 | 2024-04-24 | Permitta          | W   | 0.514      | 0.435        | -                | 0.873 (0.195)    | 0 (0.000) |     6.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2604 | 2024-04-24 | Nemiga            | L   | 0.514      | -            | -                | -                | -         |    -5.49 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2623 | 2024-04-23 | B8                | W   | 0.507      | 0.500        | 0.165 (0.042)    | 0.947 (0.240)    | 0 (0.000) |     7.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2632 | 2024-04-23 | Sashi             | L   | 0.506      | -            | -                | -                | -         |    -5.75 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2640 | 2024-04-22 | Sangal            | W   | 0.501      | 0.500        | 0.219 (0.055)    | 0.877 (0.219)    | 0 (0.000) |     9.56 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2642 | 2024-04-22 | Gaimin Gladiators | W   | 0.500      | -            | -                | -                | 0 (0.000) |     7.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2657 | 2024-04-21 | Illuminar         | W   | 0.495      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2663 | 2024-04-21 | BIG               | W   | 0.493      | 0.384        | 0.155 (0.029)    | -                | -         |    12.65 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2686 | 2024-04-20 | MOUZ NXT          | W   | 0.487      | 0.500        | 0.139 (0.034)    | 1.000 (0.244)    | -         |     8.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2743 | 2024-04-19 | Sampi             | W   | 0.479      | 0.384        | -                | 1.000 (0.184)    | -         |     5.54 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2800 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.472      | 0.500        | 0.031 (0.007)    | -                | -         |     6.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2835 | 2024-04-17 | 3DMAX             | L   | 0.466      | -            | -                | -                | -         |    -0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2854 | 2024-04-16 | KOI               | W   | 0.461      | 0.384        | 0.058 (0.010)    | -                | -         |     8.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2864 | 2024-04-16 | SINNERS           | W   | 0.459      | 0.384        | -                | 0.794 (0.140)    | -         |    10.63 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3044 | 2024-04-09 | Alliance          | W   | 0.414      | -            | -                | -                | -         |     4.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3052 | 2024-04-09 | HAVU              | W   | 0.413      | -            | -                | -                | -         |     2.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3136 | 2024-04-05 | BetBoom           | L   | 0.388      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3139 | 2024-04-05 | Alliance          | W   | 0.387      | -            | -                | -                | -         |     4.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3178 | 2024-04-04 | Benched Heroes    | W   | 0.381      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3185 | 2024-04-04 | BetBoom           | L   | 0.380      | -            | -                | -                | -         |    -1.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3255 | 2024-04-02 | Passion UA        | W   | 0.367      | 0.384        | 0.173 (0.024)    | 1.000 (0.141)    | -         |     6.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3277 | 2024-04-01 | Enterprise        | L   | 0.360      | -            | -                | -                | -         |    -6.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3632 | 2024-03-13 | Sashi             | W   | 0.233      | -            | -                | -                | -         |     5.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3730 | 2024-03-09 | Endpoint          | W   | 0.206      | -            | -                | -                | -         |     2.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3797 | 2024-03-06 | fnatic            | L   | 0.188      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3843 | 2024-03-05 | BetBoom           | W   | 0.180      | 0.500        | 0.249 (0.022)    | -                | -         |     5.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3851 | 2024-03-04 | Rebels            | W   | 0.175      | -            | -                | -                | -         |     3.03 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3860 | 2024-03-04 | AURA              | W   | 0.172      | -            | -                | -                | -         |     0.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3924 | 2024-03-01 | Young Ninjas      | W   | 0.154      | -            | -                | -                | -         |     1.17 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3939 | 2024-02-29 | AURA              | W   | 0.146      | -            | -                | -                | -         |     0.32 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3955 | 2024-02-28 | BIG               | W   | 0.139      | 0.500        | 0.155 (0.011)    | -                | -         |     3.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3990 | 2024-02-26 | MOUZ NXT          | L   | 0.127      | -            | -                | -                | -         |    -1.50 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4391 | 2024-02-08 | Passion UA        | W   | 0.006      | -            | -                | -                | -         |     0.13 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,137.92)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.674 | $500.00        | $337.22         |
| 2024-05-12 |      0.634 | $2,000.00      | $1,268.75       |
| 2024-04-24 |      0.514 | $25,000.00     | $12,847.22      |
| 2024-04-22 |      0.500 | $20,000.00     | $9,997.22       |
| 2024-03-06 |      0.188 | $25,000.00     | $4,687.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
