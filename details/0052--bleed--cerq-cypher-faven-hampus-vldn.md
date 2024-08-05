### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1055.1<br />
<br />
Final Rank Value (1055.1) = Starting Rank Value (956.6) + Head To Head Adjustments (98.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.489[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.205[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.271<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.6
- 400 + ( ( 0.271 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 956.6


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
|           43 |     2262 | 2024-05-11 | B8                | L   | 0.624      | -            | -                | -                | -         |    -9.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2290 | 2024-05-09 | Sampi             | W   | 0.614      | 0.435        | -                | 1.000 (0.267)    | 0 (0.000) |     6.13 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2332 | 2024-05-07 | 1WIN              | L   | 0.600      | -            | -                | -                | -         |   -12.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2356 | 2024-05-06 | Insilio           | W   | 0.592      | -            | -                | -                | 0 (0.000) |     6.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2420 | 2024-05-02 | AMKAL             | L   | 0.567      | -            | -                | -                | -         |    -7.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2456 | 2024-05-01 | MOUZ NXT          | L   | 0.559      | -            | -                | -                | -         |    -9.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2488 | 2024-04-30 | Permitta          | W   | 0.551      | 0.384        | -                | 0.863 (0.183)    | 0 (0.000) |     5.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2511 | 2024-04-28 | B8                | W   | 0.540      | 0.500        | 0.165 (0.044)    | 0.935 (0.253)    | 0 (0.000) |     7.79 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2561 | 2024-04-26 | ex-Guild Eagles   | W   | 0.527      | -            | -                | -                | 0 (0.000) |     3.93 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2569 | 2024-04-26 | DMS               | W   | 0.525      | -            | -                | -                | 0 (0.000) |     4.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2611 | 2024-04-24 | Permitta          | W   | 0.513      | 0.435        | -                | 0.863 (0.192)    | 0 (0.000) |     6.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2612 | 2024-04-24 | Nemiga            | L   | 0.513      | -            | -                | -                | -         |    -5.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2631 | 2024-04-23 | B8                | W   | 0.506      | 0.500        | 0.165 (0.042)    | 0.935 (0.237)    | 0 (0.000) |     7.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2640 | 2024-04-23 | Sashi             | L   | 0.505      | -            | -                | -                | -         |    -5.73 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2648 | 2024-04-22 | Sangal            | W   | 0.499      | 0.500        | 0.219 (0.055)    | 0.866 (0.216)    | 0 (0.000) |     9.56 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2650 | 2024-04-22 | Gaimin Gladiators | W   | 0.499      | -            | -                | -                | 0 (0.000) |     7.66 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2665 | 2024-04-21 | Illuminar         | W   | 0.493      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2671 | 2024-04-21 | BIG               | W   | 0.492      | 0.384        | 0.154 (0.029)    | -                | -         |    12.62 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2694 | 2024-04-20 | MOUZ NXT          | W   | 0.486      | 0.500        | 0.139 (0.034)    | 0.987 (0.240)    | -         |     8.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2751 | 2024-04-19 | Sampi             | W   | 0.478      | 0.384        | -                | 1.000 (0.184)    | -         |     5.52 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2808 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.471      | 0.500        | 0.031 (0.007)    | -                | -         |     6.72 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2843 | 2024-04-17 | 3DMAX             | L   | 0.465      | -            | -                | -                | -         |    -0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2862 | 2024-04-16 | KOI               | W   | 0.460      | 0.384        | 0.058 (0.010)    | -                | -         |     8.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2872 | 2024-04-16 | SINNERS           | W   | 0.458      | 0.384        | -                | 0.809 (0.142)    | -         |    10.71 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3052 | 2024-04-09 | Alliance          | W   | 0.413      | -            | -                | -                | -         |     4.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3060 | 2024-04-09 | HAVU              | W   | 0.412      | -            | -                | -                | -         |     2.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3144 | 2024-04-05 | BetBoom           | L   | 0.387      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3147 | 2024-04-05 | Alliance          | W   | 0.386      | -            | -                | -                | -         |     4.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3186 | 2024-04-04 | Benched Heroes    | W   | 0.380      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3193 | 2024-04-04 | BetBoom           | L   | 0.379      | -            | -                | -                | -         |    -1.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3263 | 2024-04-02 | Passion UA        | W   | 0.366      | 0.384        | 0.173 (0.024)    | 1.000 (0.141)    | -         |     6.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3285 | 2024-04-01 | Enterprise        | L   | 0.359      | -            | -                | -                | -         |    -6.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3640 | 2024-03-13 | Sashi             | W   | 0.231      | -            | -                | -                | -         |     5.17 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3738 | 2024-03-09 | Endpoint          | W   | 0.205      | -            | -                | -                | -         |     2.52 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3805 | 2024-03-06 | fnatic            | L   | 0.186      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3851 | 2024-03-05 | BetBoom           | W   | 0.179      | 0.500        | 0.249 (0.022)    | -                | -         |     5.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3859 | 2024-03-04 | Rebels            | W   | 0.174      | -            | -                | -                | -         |     3.01 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3868 | 2024-03-04 | AURA              | W   | 0.171      | -            | -                | -                | -         |     0.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3932 | 2024-03-01 | Young Ninjas      | W   | 0.153      | -            | -                | -                | -         |     1.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3947 | 2024-02-29 | AURA              | W   | 0.145      | -            | -                | -                | -         |     0.32 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3963 | 2024-02-28 | BIG               | W   | 0.138      | 0.500        | 0.154 (0.011)    | -                | -         |     3.83 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3998 | 2024-02-26 | MOUZ NXT          | L   | 0.126      | -            | -                | -                | -         |    -1.48 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4399 | 2024-02-08 | Passion UA        | W   | 0.005      | -            | -                | -                | -         |     0.11 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,057.36)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.673 | $500.00        | $336.67         |
| 2024-05-12 |      0.633 | $2,000.00      | $1,266.53       |
| 2024-04-24 |      0.513 | $25,000.00     | $12,819.44      |
| 2024-04-22 |      0.499 | $20,000.00     | $9,975.00       |
| 2024-03-06 |      0.186 | $25,000.00     | $4,659.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
