### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1056.6<br />
<br />
Final Rank Value (1056.6) = Starting Rank Value (958.6) + Head To Head Adjustments (98.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.491[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.6
- 400 + ( ( 0.273 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 958.6


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
|           43 |     2201 | 2024-05-11 | B8                | L   | 0.636      | -            | -                | -                | -         |   -10.02 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2229 | 2024-05-09 | Sampi             | W   | 0.625      | 0.435        | -                | 1.000 (0.272)    | 0 (0.000) |     6.23 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2271 | 2024-05-07 | 1WIN              | L   | 0.612      | -            | -                | -                | -         |   -13.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2295 | 2024-05-06 | Insilio           | W   | 0.603      | -            | -                | -                | 0 (0.000) |     6.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2359 | 2024-05-02 | AMKAL             | L   | 0.579      | -            | -                | -                | -         |    -7.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2395 | 2024-05-01 | MOUZ NXT          | L   | 0.570      | -            | -                | -                | -         |    -9.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2427 | 2024-04-30 | Permitta          | W   | 0.563      | 0.384        | -                | 0.876 (0.189)    | 0 (0.000) |     5.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2450 | 2024-04-28 | B8                | W   | 0.552      | 0.500        | 0.165 (0.046)    | 0.913 (0.252)    | 0 (0.000) |     7.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2500 | 2024-04-26 | ex-Guild Eagles   | W   | 0.538      | -            | -                | -                | 0 (0.000) |     4.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2507 | 2024-04-26 | DMS               | W   | 0.537      | -            | -                | -                | 0 (0.000) |     4.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2549 | 2024-04-24 | Permitta          | W   | 0.525      | 0.435        | -                | 0.876 (0.200)    | 0 (0.000) |     6.31 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2550 | 2024-04-24 | Nemiga            | L   | 0.524      | -            | -                | -                | -         |    -6.01 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2569 | 2024-04-23 | B8                | W   | 0.518      | 0.500        | 0.165 (0.043)    | 0.913 (0.236)    | 0 (0.000) |     7.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2578 | 2024-04-23 | Sashi             | L   | 0.516      | -            | -                | -                | -         |    -5.99 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2586 | 2024-04-22 | Sangal            | W   | 0.511      | 0.500        | 0.219 (0.056)    | 0.862 (0.220)    | 0 (0.000) |     9.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2588 | 2024-04-22 | Gaimin Gladiators | W   | 0.510      | -            | -                | -                | 0 (0.000) |     7.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2603 | 2024-04-21 | Illuminar         | W   | 0.505      | -            | -                | -                | -         |     0.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2609 | 2024-04-21 | BIG               | W   | 0.503      | 0.384        | 0.155 (0.030)    | -                | -         |    12.90 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2632 | 2024-04-20 | MOUZ NXT          | W   | 0.498      | 0.500        | 0.139 (0.035)    | 1.000 (0.249)    | -         |     8.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2689 | 2024-04-19 | Sampi             | W   | 0.490      | 0.384        | -                | 1.000 (0.188)    | -         |     5.63 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2746 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.483      | 0.500        | 0.032 (0.008)    | -                | -         |     6.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2781 | 2024-04-17 | 3DMAX             | L   | 0.476      | -            | -                | -                | -         |    -0.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2800 | 2024-04-16 | KOI               | W   | 0.472      | 0.384        | 0.059 (0.011)    | -                | -         |     9.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2810 | 2024-04-16 | SINNERS           | W   | 0.469      | 0.384        | -                | 0.758 (0.137)    | -         |    10.01 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2990 | 2024-04-09 | Alliance          | W   | 0.425      | -            | -                | -                | -         |     4.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     2998 | 2024-04-09 | HAVU              | W   | 0.424      | -            | -                | -                | -         |     2.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3082 | 2024-04-05 | BetBoom           | L   | 0.398      | -            | -                | -                | -         |    -1.11 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3085 | 2024-04-05 | Alliance          | W   | 0.398      | -            | -                | -                | -         |     4.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3124 | 2024-04-04 | Benched Heroes    | W   | 0.391      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3131 | 2024-04-04 | BetBoom           | L   | 0.391      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3201 | 2024-04-02 | Passion UA        | W   | 0.378      | 0.384        | 0.172 (0.025)    | 1.000 (0.145)    | -         |     6.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3223 | 2024-04-01 | Enterprise        | L   | 0.371      | -            | -                | -                | -         |    -7.01 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3577 | 2024-03-13 | Sashi             | W   | 0.243      | -            | -                | -                | -         |     5.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3675 | 2024-03-09 | Endpoint          | W   | 0.216      | -            | -                | -                | -         |     2.64 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3742 | 2024-03-06 | fnatic            | L   | 0.198      | -            | -                | -                | -         |    -0.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3788 | 2024-03-05 | BetBoom           | W   | 0.191      | 0.500        | 0.252 (0.024)    | -                | -         |     5.55 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3796 | 2024-03-04 | Rebels            | W   | 0.186      | -            | -                | -                | -         |     3.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3805 | 2024-03-04 | AURA              | W   | 0.183      | -            | -                | -                | -         |     0.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3869 | 2024-03-01 | Young Ninjas      | W   | 0.165      | -            | -                | -                | -         |     1.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3884 | 2024-02-29 | AURA              | W   | 0.157      | -            | -                | -                | -         |     0.35 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3900 | 2024-02-28 | BIG               | W   | 0.150      | 0.500        | 0.155 (0.012)    | -                | -         |     4.15 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3935 | 2024-02-26 | MOUZ NXT          | L   | 0.137      | -            | -                | -                | -         |    -1.66 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4335 | 2024-02-08 | Passion UA        | W   | 0.017      | -            | -                | -                | -         |     0.35 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,903.19)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.685 | $500.00        | $342.50         |
| 2024-05-12 |      0.645 | $2,000.00      | $1,289.86       |
| 2024-04-24 |      0.524 | $25,000.00     | $13,111.11      |
| 2024-04-22 |      0.510 | $20,000.00     | $10,208.33      |
| 2024-03-06 |      0.198 | $25,000.00     | $4,951.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
