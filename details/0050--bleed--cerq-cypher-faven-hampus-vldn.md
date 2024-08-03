### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1056.2<br />
<br />
Final Rank Value (1056.2) = Starting Rank Value (960.4) + Head To Head Adjustments (95.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.491[<sup>1</sup>](#table2)
- Bounty Collected: 0.393[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.274<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 960.4
- 400 + ( ( 0.274 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 960.4


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
|           43 |     2136 | 2024-05-11 | B8                | L   | 0.638      | -            | -                | -                | -         |   -10.11 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2164 | 2024-05-09 | Sampi             | W   | 0.627      | 0.435        | -                | 1.000 (0.273)    | 0 (0.000) |     6.32 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2205 | 2024-05-07 | 1WIN              | L   | 0.613      | -            | -                | -                | -         |   -13.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2229 | 2024-05-06 | Insilio           | W   | 0.605      | -            | -                | -                | 0 (0.000) |     6.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2293 | 2024-05-02 | AMKAL             | L   | 0.580      | -            | -                | -                | -         |    -7.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2329 | 2024-05-01 | MOUZ NXT          | L   | 0.572      | -            | -                | -                | -         |    -9.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2361 | 2024-04-30 | Permitta          | W   | 0.564      | 0.384        | -                | 0.887 (0.192)    | 0 (0.000) |     5.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2384 | 2024-04-28 | B8                | W   | 0.554      | 0.500        | 0.166 (0.046)    | 0.945 (0.262)    | 0 (0.000) |     7.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2434 | 2024-04-26 | ex-Guild Eagles   | W   | 0.540      | -            | -                | -                | 0 (0.000) |     4.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2441 | 2024-04-26 | DMS               | W   | 0.539      | -            | -                | -                | 0 (0.000) |     4.91 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2483 | 2024-04-24 | Permitta          | W   | 0.527      | 0.435        | -                | 0.887 (0.203)    | 0 (0.000) |     6.36 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2484 | 2024-04-24 | Nemiga            | L   | 0.526      | -            | -                | -                | -         |    -5.99 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2503 | 2024-04-23 | B8                | W   | 0.519      | 0.500        | 0.166 (0.043)    | 0.945 (0.245)    | 0 (0.000) |     7.91 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2512 | 2024-04-23 | Sashi             | L   | 0.518      | -            | -                | -                | -         |    -5.82 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2520 | 2024-04-22 | Sangal            | W   | 0.513      | 0.500        | 0.219 (0.056)    | 0.823 (0.211)    | 0 (0.000) |     9.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2522 | 2024-04-22 | Gaimin Gladiators | W   | 0.512      | 0.384        | 0.038 (0.008)    | -                | 0 (0.000) |     7.98 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2537 | 2024-04-21 | Illuminar         | W   | 0.507      | -            | -                | -                | -         |     0.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2543 | 2024-04-21 | BIG               | W   | 0.505      | 0.384        | 0.156 (0.030)    | -                | -         |    13.01 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2566 | 2024-04-20 | MOUZ NXT          | W   | 0.499      | 0.500        | 0.139 (0.035)    | 1.000 (0.250)    | -         |     8.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2623 | 2024-04-19 | Sampi             | W   | 0.492      | 0.384        | -                | 1.000 (0.189)    | -         |     5.73 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2680 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.484      | 0.500        | 0.032 (0.008)    | -                | -         |     6.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2715 | 2024-04-17 | 3DMAX             | L   | 0.478      | -            | -                | -                | -         |    -0.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2734 | 2024-04-16 | KOI               | W   | 0.473      | -            | -                | -                | -         |     6.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2744 | 2024-04-16 | SINNERS           | W   | 0.471      | 0.384        | -                | 0.784 (0.142)    | -         |    10.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2924 | 2024-04-09 | Alliance          | W   | 0.426      | -            | -                | -                | -         |     4.34 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     2932 | 2024-04-09 | HAVU              | W   | 0.425      | -            | -                | -                | -         |     2.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3016 | 2024-04-05 | BetBoom           | L   | 0.400      | -            | -                | -                | -         |    -1.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3019 | 2024-04-05 | Alliance          | W   | 0.399      | -            | -                | -                | -         |     4.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3058 | 2024-04-04 | Benched Heroes    | W   | 0.393      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3065 | 2024-04-04 | BetBoom           | L   | 0.392      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3135 | 2024-04-02 | Passion UA        | W   | 0.380      | 0.384        | 0.172 (0.025)    | 1.000 (0.146)    | -         |     6.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3157 | 2024-04-01 | Enterprise        | L   | 0.372      | -            | -                | -                | -         |    -7.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3505 | 2024-03-13 | Sashi             | W   | 0.245      | -            | -                | -                | -         |     5.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3602 | 2024-03-09 | Endpoint          | W   | 0.218      | -            | -                | -                | -         |     2.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3669 | 2024-03-06 | fnatic            | L   | 0.200      | -            | -                | -                | -         |    -0.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3715 | 2024-03-05 | BetBoom           | W   | 0.192      | 0.500        | 0.252 (0.024)    | -                | -         |     5.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3723 | 2024-03-04 | Rebels            | W   | 0.187      | -            | -                | -                | -         |     3.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3732 | 2024-03-04 | AURA              | W   | 0.185      | -            | -                | -                | -         |     0.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3796 | 2024-03-01 | Young Ninjas      | W   | 0.166      | -            | -                | -                | -         |     1.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3811 | 2024-02-29 | AURA              | W   | 0.158      | -            | -                | -                | -         |     0.35 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3827 | 2024-02-28 | BIG               | W   | 0.151      | 0.500        | 0.156 (0.012)    | -                | -         |     4.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3862 | 2024-02-26 | MOUZ NXT          | L   | 0.139      | -            | -                | -                | -         |    -1.73 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4262 | 2024-02-08 | Passion UA        | W   | 0.018      | -            | -                | -                | -         |     0.39 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,027.38)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.687 | $500.00        | $343.36         |
| 2024-05-12 |      0.647 | $2,000.00      | $1,293.29       |
| 2024-04-24 |      0.526 | $25,000.00     | $13,153.94      |
| 2024-04-22 |      0.512 | $20,000.00     | $10,242.59      |
| 2024-03-06 |      0.200 | $25,000.00     | $4,994.21       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
