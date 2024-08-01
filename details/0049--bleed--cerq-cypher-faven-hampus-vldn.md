### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1054.0<br />
<br />
Final Rank Value (1054.0) = Starting Rank Value (964.5) + Head To Head Adjustments (89.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.395[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.274<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 964.5
- 400 + ( ( 0.274 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 964.5


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
|           44 |     2181 | 2024-05-11 | B8                | L   | 0.651      | -            | -                | -                | -         |   -10.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           43 |     2209 | 2024-05-09 | Sampi             | W   | 0.640      | 0.435        | -                | 1.000 (0.278)    | 0 (0.000) |     6.29 | CYPHER, draken, faveN, hampus, VLDN |
|           42 |     2253 | 2024-05-07 | 1WIN              | L   | 0.627      | -            | -                | -                | -         |   -13.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           41 |     2277 | 2024-05-06 | Insilio           | W   | 0.618      | -            | -                | -                | 0 (0.000) |     6.66 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2341 | 2024-05-02 | AMKAL             | L   | 0.594      | -            | -                | -                | -         |    -7.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2379 | 2024-05-01 | MOUZ NXT          | L   | 0.585      | -            | -                | -                | -         |    -9.63 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2412 | 2024-04-30 | Permitta          | W   | 0.578      | 0.384        | -                | 0.801 (0.178)    | 0 (0.000) |     5.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2435 | 2024-04-28 | B8                | W   | 0.567      | 0.500        | 0.168 (0.048)    | 0.878 (0.249)    | 0 (0.000) |     8.11 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2486 | 2024-04-26 | ex-Guild Eagles   | W   | 0.553      | -            | -                | -                | 0 (0.000) |     4.34 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2493 | 2024-04-26 | DMS               | W   | 0.552      | -            | -                | -                | 0 (0.000) |     5.17 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2535 | 2024-04-24 | Permitta          | W   | 0.540      | 0.435        | -                | 0.801 (0.188)    | 0 (0.000) |     6.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2536 | 2024-04-24 | Nemiga            | L   | 0.539      | -            | -                | -                | -         |    -6.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2551 | 2024-04-23 | MOUZ NXT          | L   | 0.534      | -            | -                | -                | -         |    -8.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2557 | 2024-04-23 | B8                | W   | 0.533      | 0.500        | 0.168 (0.045)    | 0.878 (0.234)    | 0 (0.000) |     7.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2566 | 2024-04-23 | Sashi             | L   | 0.531      | -            | -                | -                | -         |    -6.11 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2575 | 2024-04-22 | Sangal            | W   | 0.526      | 0.500        | 0.221 (0.058)    | 0.823 (0.217)    | 0 (0.000) |     9.62 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2577 | 2024-04-22 | Gaimin Gladiators | W   | 0.525      | 0.384        | 0.040 (0.008)    | -                | 0 (0.000) |     8.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2593 | 2024-04-21 | Illuminar         | W   | 0.520      | -            | -                | -                | -         |     0.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2599 | 2024-04-21 | BIG               | W   | 0.518      | 0.384        | 0.132 (0.026)    | -                | -         |    12.10 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2624 | 2024-04-20 | MOUZ NXT          | W   | 0.513      | 0.500        | 0.141 (0.036)    | 1.000 (0.256)    | -         |     8.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2682 | 2024-04-19 | Sampi             | W   | 0.505      | 0.384        | -                | 1.000 (0.194)    | -         |     5.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2740 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.498      | 0.500        | 0.032 (0.008)    | -                | -         |     6.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2776 | 2024-04-17 | 3DMAX             | L   | 0.491      | -            | -                | -                | -         |    -0.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2795 | 2024-04-16 | KOI               | W   | 0.487      | -            | -                | -                | -         |     6.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2806 | 2024-04-16 | SINNERS           | W   | 0.484      | 0.384        | -                | 0.768 (0.143)    | -         |     9.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2987 | 2024-04-09 | Alliance          | W   | 0.440      | -            | -                | -                | -         |     4.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     2995 | 2024-04-09 | HAVU              | W   | 0.439      | -            | -                | -                | -         |     2.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3079 | 2024-04-05 | BetBoom           | L   | 0.413      | -            | -                | -                | -         |    -1.14 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3082 | 2024-04-05 | Alliance          | W   | 0.412      | -            | -                | -                | -         |     4.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3121 | 2024-04-04 | Benched Heroes    | W   | 0.406      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3129 | 2024-04-04 | BetBoom           | L   | 0.406      | -            | -                | -                | -         |    -1.10 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3206 | 2024-04-02 | Passion UA        | W   | 0.393      | 0.384        | 0.173 (0.026)    | 1.000 (0.151)    | -         |     7.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3228 | 2024-04-01 | Enterprise        | L   | 0.386      | -            | -                | -                | -         |    -7.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3592 | 2024-03-13 | Sashi             | W   | 0.258      | -            | -                | -                | -         |     5.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3692 | 2024-03-09 | Endpoint          | W   | 0.231      | -            | -                | -                | -         |     2.97 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3759 | 2024-03-06 | fnatic            | L   | 0.213      | -            | -                | -                | -         |    -0.72 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3810 | 2024-03-05 | BetBoom           | W   | 0.206      | 0.500        | 0.257 (0.026)    | -                | -         |     6.00 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3818 | 2024-03-04 | Rebels            | W   | 0.201      | -            | -                | -                | -         |     3.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3827 | 2024-03-04 | AURA              | W   | 0.198      | -            | -                | -                | -         |     0.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3892 | 2024-03-01 | Young Ninjas      | W   | 0.180      | -            | -                | -                | -         |     1.36 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3907 | 2024-02-29 | AURA              | W   | 0.172      | -            | -                | -                | -         |     0.38 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3924 | 2024-02-28 | BIG               | W   | 0.165      | 0.500        | 0.132 (0.011)    | -                | -         |     4.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3959 | 2024-02-26 | MOUZ NXT          | L   | 0.152      | -            | -                | -                | -         |    -1.75 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4378 | 2024-02-08 | Passion UA        | W   | 0.032      | -            | -                | -                | -         |     0.67 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,990.69)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.700 | $500.00        | $350.00         |
| 2024-05-12 |      0.660 | $2,000.00      | $1,319.86       |
| 2024-04-24 |      0.539 | $25,000.00     | $13,486.11      |
| 2024-04-22 |      0.525 | $20,000.00     | $10,508.33      |
| 2024-03-06 |      0.213 | $25,000.00     | $5,326.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
