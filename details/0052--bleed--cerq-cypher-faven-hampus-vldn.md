### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1054.8<br />
<br />
Final Rank Value (1054.8) = Starting Rank Value (956.9) + Head To Head Adjustments (97.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.488[<sup>1</sup>](#table2)
- Bounty Collected: 0.390[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.271<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.9
- 400 + ( ( 0.271 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 956.9


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
|           43 |     2269 | 2024-05-11 | B8                | L   | 0.620      | -            | -                | -                | -         |    -9.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2297 | 2024-05-09 | Sampi             | W   | 0.609      | 0.435        | -                | 1.000 (0.265)    | 0 (0.000) |     6.12 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2339 | 2024-05-07 | 1WIN              | L   | 0.595      | -            | -                | -                | -         |   -12.14 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2363 | 2024-05-06 | Insilio           | W   | 0.587      | -            | -                | -                | 0 (0.000) |     6.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2427 | 2024-05-02 | AMKAL             | L   | 0.562      | -            | -                | -                | -         |    -6.99 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2463 | 2024-05-01 | MOUZ NXT          | L   | 0.554      | -            | -                | -                | -         |    -9.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2495 | 2024-04-30 | Permitta          | W   | 0.546      | 0.384        | -                | 0.940 (0.197)    | 0 (0.000) |     5.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2518 | 2024-04-28 | B8                | W   | 0.536      | 0.500        | 0.164 (0.044)    | 0.933 (0.250)    | 0 (0.000) |     7.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2568 | 2024-04-26 | ex-Guild Eagles   | W   | 0.522      | -            | -                | -                | 0 (0.000) |     3.89 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2576 | 2024-04-26 | DMS               | W   | 0.521      | -            | -                | -                | 0 (0.000) |     4.79 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2618 | 2024-04-24 | Permitta          | W   | 0.509      | 0.435        | -                | 0.940 (0.208)    | 0 (0.000) |     6.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2619 | 2024-04-24 | Nemiga            | L   | 0.508      | -            | -                | -                | -         |    -5.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2638 | 2024-04-23 | B8                | W   | 0.501      | 0.500        | 0.164 (0.041)    | 0.933 (0.234)    | 0 (0.000) |     7.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2647 | 2024-04-23 | Sashi             | L   | 0.500      | -            | -                | -                | -         |    -5.65 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2655 | 2024-04-22 | Sangal            | W   | 0.495      | 0.500        | 0.219 (0.054)    | 0.865 (0.214)    | 0 (0.000) |     9.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2657 | 2024-04-22 | Gaimin Gladiators | W   | 0.494      | -            | -                | -                | 0 (0.000) |     7.56 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2672 | 2024-04-21 | Illuminar         | W   | 0.489      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2678 | 2024-04-21 | BIG               | W   | 0.487      | 0.384        | 0.154 (0.029)    | -                | -         |    12.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2701 | 2024-04-20 | MOUZ NXT          | W   | 0.481      | 0.500        | 0.139 (0.033)    | 0.984 (0.237)    | -         |     8.34 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2758 | 2024-04-19 | Sampi             | W   | 0.473      | 0.384        | -                | 1.000 (0.182)    | -         |     5.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2815 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.466      | 0.500        | 0.031 (0.007)    | -                | -         |     6.66 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2850 | 2024-04-17 | 3DMAX             | L   | 0.460      | -            | -                | -                | -         |    -0.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2869 | 2024-04-16 | KOI               | W   | 0.455      | 0.384        | 0.058 (0.010)    | -                | -         |     8.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2879 | 2024-04-16 | SINNERS           | W   | 0.453      | 0.384        | -                | 0.808 (0.141)    | -         |    10.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3059 | 2024-04-09 | Alliance          | W   | 0.408      | -            | -                | -                | -         |     4.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3067 | 2024-04-09 | HAVU              | W   | 0.407      | -            | -                | -                | -         |     2.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3151 | 2024-04-05 | BetBoom           | L   | 0.382      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3154 | 2024-04-05 | Alliance          | W   | 0.381      | -            | -                | -                | -         |     4.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3193 | 2024-04-04 | Benched Heroes    | W   | 0.375      | -            | -                | -                | -         |     0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3200 | 2024-04-04 | BetBoom           | L   | 0.374      | -            | -                | -                | -         |    -1.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3270 | 2024-04-02 | Passion UA        | W   | 0.362      | 0.384        | 0.173 (0.024)    | 1.000 (0.139)    | -         |     6.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3292 | 2024-04-01 | Enterprise        | L   | 0.354      | -            | -                | -                | -         |    -6.62 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3647 | 2024-03-13 | Sashi             | W   | 0.227      | -            | -                | -                | -         |     5.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3745 | 2024-03-09 | Endpoint          | W   | 0.200      | -            | -                | -                | -         |     2.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3812 | 2024-03-06 | fnatic            | L   | 0.182      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3858 | 2024-03-05 | BetBoom           | W   | 0.174      | 0.500        | 0.248 (0.022)    | -                | -         |     5.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3866 | 2024-03-04 | Rebels            | W   | 0.169      | -            | -                | -                | -         |     2.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3875 | 2024-03-04 | AURA              | W   | 0.167      | -            | -                | -                | -         |     0.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3939 | 2024-03-01 | Young Ninjas      | W   | 0.148      | -            | -                | -                | -         |     1.14 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3954 | 2024-02-29 | AURA              | W   | 0.140      | -            | -                | -                | -         |     0.30 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3970 | 2024-02-28 | BIG               | W   | 0.133      | 0.500        | 0.154 (0.010)    | -                | -         |     3.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     4005 | 2024-02-26 | MOUZ NXT          | L   | 0.121      | -            | -                | -                | -         |    -1.43 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4406 | 2024-02-08 | Passion UA        | W   | 0.000      | -            | -                | -                | -         |     0.01 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,715.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.669 | $500.00        | $334.31         |
| 2024-05-12 |      0.629 | $2,000.00      | $1,257.08       |
| 2024-04-24 |      0.508 | $25,000.00     | $12,701.39      |
| 2024-04-22 |      0.494 | $20,000.00     | $9,880.56       |
| 2024-03-06 |      0.182 | $25,000.00     | $4,541.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
