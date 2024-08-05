### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1066.7<br />
<br />
Final Rank Value (1066.7) = Starting Rank Value (968.3) + Head To Head Adjustments (98.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 968.3
- 400 + ( ( 0.276 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 968.3


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
|           43 |     2088 | 2024-05-11 | B8                | L   | 0.657      | -            | -                | -                | -         |   -10.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2116 | 2024-05-09 | Sampi             | W   | 0.646      | 0.435        | -                | 1.000 (0.281)    | 0 (0.000) |     6.26 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2158 | 2024-05-07 | 1WIN              | L   | 0.632      | -            | -                | -                | -         |   -13.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2182 | 2024-05-06 | Insilio           | W   | 0.624      | -            | -                | -                | 0 (0.000) |     6.42 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2246 | 2024-05-02 | AMKAL             | L   | 0.599      | -            | -                | -                | -         |    -7.55 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2282 | 2024-05-01 | MOUZ NXT          | L   | 0.591      | -            | -                | -                | -         |   -10.38 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2314 | 2024-04-30 | Permitta          | W   | 0.584      | 0.384        | -                | 0.799 (0.179)    | 0 (0.000) |     5.49 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2337 | 2024-04-28 | B8                | W   | 0.573      | 0.500        | 0.167 (0.048)    | 0.879 (0.252)    | 0 (0.000) |     8.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2387 | 2024-04-26 | ex-Guild Eagles   | W   | 0.559      | -            | -                | -                | 0 (0.000) |     4.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2395 | 2024-04-26 | DMS               | W   | 0.558      | -            | -                | -                | 0 (0.000) |     4.98 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2437 | 2024-04-24 | Permitta          | W   | 0.546      | 0.435        | -                | 0.799 (0.190)    | 0 (0.000) |     6.11 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2438 | 2024-04-24 | Nemiga            | L   | 0.545      | -            | -                | -                | -         |    -6.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2457 | 2024-04-23 | B8                | W   | 0.539      | 0.500        | 0.167 (0.045)    | 0.879 (0.237)    | 0 (0.000) |     8.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2466 | 2024-04-23 | Sashi             | L   | 0.537      | -            | -                | -                | -         |    -6.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2474 | 2024-04-22 | Sangal            | W   | 0.532      | 0.500        | 0.219 (0.058)    | 0.824 (0.219)    | 0 (0.000) |     9.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2476 | 2024-04-22 | Gaimin Gladiators | W   | 0.531      | 0.384        | 0.040 (0.008)    | -                | 0 (0.000) |     8.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2491 | 2024-04-21 | Illuminar         | W   | 0.526      | -            | -                | -                | -         |     0.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2497 | 2024-04-21 | BIG               | W   | 0.524      | 0.384        | 0.157 (0.032)    | -                | -         |    12.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2520 | 2024-04-20 | MOUZ NXT          | W   | 0.519      | 0.500        | 0.140 (0.036)    | 1.000 (0.259)    | -         |     8.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2577 | 2024-04-19 | Sampi             | W   | 0.511      | 0.384        | -                | 1.000 (0.196)    | -         |     5.75 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2634 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.504      | 0.500        | -                | 0.564 (0.142)    | -         |     6.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2669 | 2024-04-17 | 3DMAX             | L   | 0.497      | -            | -                | -                | -         |    -0.51 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2688 | 2024-04-16 | KOI               | W   | 0.492      | 0.384        | 0.059 (0.011)    | -                | -         |     9.52 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2698 | 2024-04-16 | SINNERS           | W   | 0.490      | -            | -                | -                | -         |     9.51 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     2878 | 2024-04-09 | Alliance          | W   | 0.445      | -            | -                | -                | -         |     4.34 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     2886 | 2024-04-09 | HAVU              | W   | 0.444      | -            | -                | -                | -         |     2.31 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     2970 | 2024-04-05 | BetBoom           | L   | 0.419      | -            | -                | -                | -         |    -1.12 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     2973 | 2024-04-05 | Alliance          | W   | 0.418      | -            | -                | -                | -         |     4.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3012 | 2024-04-04 | Benched Heroes    | W   | 0.412      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3019 | 2024-04-04 | BetBoom           | L   | 0.411      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3089 | 2024-04-02 | Passion UA        | W   | 0.399      | 0.384        | 0.171 (0.026)    | 1.000 (0.153)    | -         |     7.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3111 | 2024-04-01 | Enterprise        | L   | 0.391      | -            | -                | -                | -         |    -7.51 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3466 | 2024-03-13 | Sashi             | W   | 0.264      | -            | -                | -                | -         |     5.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3564 | 2024-03-09 | Endpoint          | W   | 0.237      | -            | -                | -                | -         |     2.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3631 | 2024-03-06 | fnatic            | L   | 0.219      | -            | -                | -                | -         |    -0.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3677 | 2024-03-05 | BetBoom           | W   | 0.211      | 0.500        | 0.256 (0.027)    | -                | -         |     6.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3685 | 2024-03-04 | Rebels            | W   | 0.206      | -            | -                | -                | -         |     3.55 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3694 | 2024-03-04 | AURA              | W   | 0.204      | -            | -                | -                | -         |     0.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3758 | 2024-03-01 | Young Ninjas      | W   | 0.185      | -            | -                | -                | -         |     1.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3773 | 2024-02-29 | AURA              | W   | 0.177      | -            | -                | -                | -         |     0.38 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3789 | 2024-02-28 | BIG               | W   | 0.170      | 0.500        | 0.157 (0.013)    | -                | -         |     4.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3824 | 2024-02-26 | MOUZ NXT          | L   | 0.158      | -            | -                | -                | -         |    -1.91 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4225 | 2024-02-08 | Passion UA        | W   | 0.037      | -            | -                | -                | -         |     0.79 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,405.89)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.706 | $500.00        | $352.86         |
| 2024-05-12 |      0.666 | $2,000.00      | $1,331.31       |
| 2024-04-24 |      0.545 | $25,000.00     | $13,629.28      |
| 2024-04-22 |      0.531 | $20,000.00     | $10,622.87      |
| 2024-03-06 |      0.219 | $25,000.00     | $5,469.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
