### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1055.2<br />
<br />
Final Rank Value (1055.2) = Starting Rank Value (956.5) + Head To Head Adjustments (98.7)<br />

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
|           42 |     2286 | 2024-05-11 | B8                | L   | 0.618      | -            | -                | -                | -         |    -9.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           41 |     2314 | 2024-05-09 | Sampi             | W   | 0.607      | 0.435        | -                | 1.000 (0.264)    | 0 (0.000) |     6.12 | CYPHER, draken, faveN, hampus, VLDN |
|           40 |     2356 | 2024-05-07 | 1WIN              | L   | 0.593      | -            | -                | -                | -         |   -12.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2380 | 2024-05-06 | Insilio           | W   | 0.585      | -            | -                | -                | 0 (0.000) |     6.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2444 | 2024-05-02 | AMKAL             | L   | 0.561      | -            | -                | -                | -         |    -6.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2480 | 2024-05-01 | MOUZ NXT          | L   | 0.552      | -            | -                | -                | -         |    -9.27 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2512 | 2024-04-30 | Permitta          | W   | 0.545      | 0.384        | -                | 0.919 (0.192)    | 0 (0.000) |     6.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2535 | 2024-04-28 | B8                | W   | 0.534      | 0.500        | 0.170 (0.045)    | 0.912 (0.243)    | 0 (0.000) |     7.79 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2585 | 2024-04-26 | ex-Guild Eagles   | W   | 0.520      | -            | -                | -                | 0 (0.000) |     3.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2593 | 2024-04-26 | DMS               | W   | 0.519      | -            | -                | -                | 0 (0.000) |     4.77 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2635 | 2024-04-24 | Permitta          | W   | 0.507      | 0.435        | 0.039 (0.009)    | 0.919 (0.202)    | 0 (0.000) |     6.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2636 | 2024-04-24 | Nemiga            | L   | 0.506      | -            | -                | -                | -         |    -5.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2655 | 2024-04-23 | B8                | W   | 0.500      | 0.500        | 0.170 (0.043)    | 0.912 (0.228)    | 0 (0.000) |     7.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2664 | 2024-04-23 | Sashi             | L   | 0.498      | -            | -                | -                | -         |    -5.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2672 | 2024-04-22 | Sangal            | W   | 0.493      | 0.500        | 0.219 (0.054)    | 0.846 (0.209)    | 0 (0.000) |     9.62 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2674 | 2024-04-22 | Gaimin Gladiators | W   | 0.492      | -            | -                | -                | 0 (0.000) |     7.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2689 | 2024-04-21 | Illuminar         | W   | 0.487      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2695 | 2024-04-21 | BIG               | W   | 0.485      | 0.384        | 0.154 (0.029)    | -                | -         |    12.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2718 | 2024-04-20 | MOUZ NXT          | W   | 0.480      | 0.500        | 0.139 (0.033)    | 0.961 (0.231)    | -         |     8.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2775 | 2024-04-19 | Sampi             | W   | 0.472      | 0.384        | -                | 1.000 (0.181)    | -         |     5.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2832 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.465      | -            | -                | -                | -         |     6.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2867 | 2024-04-17 | 3DMAX             | L   | 0.458      | -            | -                | -                | -         |    -0.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2886 | 2024-04-16 | KOI               | W   | 0.453      | 0.384        | 0.058 (0.010)    | -                | -         |     8.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2896 | 2024-04-16 | SINNERS           | W   | 0.451      | 0.384        | -                | 0.800 (0.139)    | -         |    10.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3076 | 2024-04-09 | Alliance          | W   | 0.407      | -            | -                | -                | -         |     4.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3084 | 2024-04-09 | HAVU              | W   | 0.406      | -            | -                | -                | -         |     2.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3168 | 2024-04-05 | BetBoom           | L   | 0.380      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3171 | 2024-04-05 | Alliance          | W   | 0.379      | -            | -                | -                | -         |     4.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3210 | 2024-04-04 | Benched Heroes    | W   | 0.373      | -            | -                | -                | -         |     0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3217 | 2024-04-04 | BetBoom           | L   | 0.372      | -            | -                | -                | -         |    -1.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3287 | 2024-04-02 | Passion UA        | W   | 0.360      | 0.384        | 0.173 (0.024)    | 1.000 (0.138)    | -         |     6.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3309 | 2024-04-01 | Enterprise        | L   | 0.352      | -            | -                | -                | -         |    -6.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3664 | 2024-03-13 | Sashi             | W   | 0.225      | -            | -                | -                | -         |     5.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3762 | 2024-03-09 | Endpoint          | W   | 0.198      | -            | -                | -                | -         |     2.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3829 | 2024-03-06 | fnatic            | L   | 0.180      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3875 | 2024-03-05 | BetBoom           | W   | 0.172      | 0.500        | 0.248 (0.021)    | -                | -         |     5.02 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3883 | 2024-03-04 | Rebels            | W   | 0.168      | -            | -                | -                | -         |     2.91 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3892 | 2024-03-04 | AURA              | W   | 0.165      | -            | -                | -                | -         |     0.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3956 | 2024-03-01 | Young Ninjas      | W   | 0.147      | -            | -                | -                | -         |     1.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            3 |     3971 | 2024-02-29 | AURA              | W   | 0.139      | -            | -                | -                | -         |     0.30 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            2 |     3987 | 2024-02-28 | BIG               | W   | 0.132      | 0.500        | 0.154 (0.010)    | -                | -         |     3.65 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            1 |     4022 | 2024-02-26 | MOUZ NXT          | L   | 0.119      | -            | -                | -                | -         |    -1.41 | CeRq, faveN, hampus, lauNX, VLDN    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,594.17)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.667 | $500.00        | $333.47         |
| 2024-05-12 |      0.627 | $2,000.00      | $1,253.75       |
| 2024-04-24 |      0.506 | $25,000.00     | $12,659.72      |
| 2024-04-22 |      0.492 | $20,000.00     | $9,847.22       |
| 2024-03-06 |      0.180 | $25,000.00     | $4,500.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
