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
Final Rank Value (1055.2) = Starting Rank Value (956.8) + Head To Head Adjustments (98.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.489[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.206[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.271<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.8
- 400 + ( ( 0.271 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 956.8


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
|           43 |     2265 | 2024-05-11 | B8                | L   | 0.622      | -            | -                | -                | -         |    -9.73 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2293 | 2024-05-09 | Sampi             | W   | 0.612      | 0.435        | -                | 1.000 (0.266)    | 0 (0.000) |     6.13 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2335 | 2024-05-07 | 1WIN              | L   | 0.598      | -            | -                | -                | -         |   -12.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2359 | 2024-05-06 | Insilio           | W   | 0.589      | -            | -                | -                | 0 (0.000) |     6.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2423 | 2024-05-02 | AMKAL             | L   | 0.565      | -            | -                | -                | -         |    -7.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2459 | 2024-05-01 | MOUZ NXT          | L   | 0.556      | -            | -                | -                | -         |    -9.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2491 | 2024-04-30 | Permitta          | W   | 0.549      | 0.384        | -                | 0.901 (0.190)    | 0 (0.000) |     5.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2514 | 2024-04-28 | B8                | W   | 0.538      | 0.500        | 0.164 (0.044)    | 0.934 (0.251)    | 0 (0.000) |     7.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2564 | 2024-04-26 | ex-Guild Eagles   | W   | 0.524      | -            | -                | -                | 0 (0.000) |     3.91 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2572 | 2024-04-26 | DMS               | W   | 0.523      | -            | -                | -                | 0 (0.000) |     4.81 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2614 | 2024-04-24 | Permitta          | W   | 0.511      | 0.435        | -                | 0.901 (0.200)    | 0 (0.000) |     6.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2615 | 2024-04-24 | Nemiga            | L   | 0.511      | -            | -                | -                | -         |    -5.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2634 | 2024-04-23 | B8                | W   | 0.504      | 0.500        | 0.164 (0.041)    | 0.934 (0.235)    | 0 (0.000) |     7.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2643 | 2024-04-23 | Sashi             | L   | 0.502      | -            | -                | -                | -         |    -5.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2651 | 2024-04-22 | Sangal            | W   | 0.497      | 0.500        | 0.219 (0.054)    | 0.866 (0.215)    | 0 (0.000) |     9.55 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2653 | 2024-04-22 | Gaimin Gladiators | W   | 0.497      | -            | -                | -                | 0 (0.000) |     7.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2668 | 2024-04-21 | Illuminar         | W   | 0.491      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2674 | 2024-04-21 | BIG               | W   | 0.489      | 0.384        | 0.154 (0.029)    | -                | -         |    12.56 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2697 | 2024-04-20 | MOUZ NXT          | W   | 0.484      | 0.500        | 0.139 (0.034)    | 0.986 (0.238)    | -         |     8.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2754 | 2024-04-19 | Sampi             | W   | 0.476      | 0.384        | -                | 1.000 (0.183)    | -         |     5.52 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2811 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.469      | 0.500        | 0.031 (0.007)    | -                | -         |     6.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2846 | 2024-04-17 | 3DMAX             | L   | 0.463      | -            | -                | -                | -         |    -0.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2865 | 2024-04-16 | KOI               | W   | 0.458      | 0.384        | 0.058 (0.010)    | -                | -         |     8.77 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2875 | 2024-04-16 | SINNERS           | W   | 0.456      | 0.384        | -                | 0.808 (0.141)    | -         |    10.65 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3055 | 2024-04-09 | Alliance          | W   | 0.411      | -            | -                | -                | -         |     4.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3063 | 2024-04-09 | HAVU              | W   | 0.410      | -            | -                | -                | -         |     2.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3147 | 2024-04-05 | BetBoom           | L   | 0.384      | -            | -                | -                | -         |    -1.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3150 | 2024-04-05 | Alliance          | W   | 0.384      | -            | -                | -                | -         |     4.10 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3189 | 2024-04-04 | Benched Heroes    | W   | 0.377      | -            | -                | -                | -         |     0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3196 | 2024-04-04 | BetBoom           | L   | 0.377      | -            | -                | -                | -         |    -1.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3266 | 2024-04-02 | Passion UA        | W   | 0.364      | 0.384        | 0.173 (0.024)    | 1.000 (0.140)    | -         |     6.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3288 | 2024-04-01 | Enterprise        | L   | 0.357      | -            | -                | -                | -         |    -6.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3643 | 2024-03-13 | Sashi             | W   | 0.229      | -            | -                | -                | -         |     5.12 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3741 | 2024-03-09 | Endpoint          | W   | 0.203      | -            | -                | -                | -         |     2.50 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3808 | 2024-03-06 | fnatic            | L   | 0.184      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3854 | 2024-03-05 | BetBoom           | W   | 0.177      | 0.500        | 0.249 (0.022)    | -                | -         |     5.14 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3862 | 2024-03-04 | Rebels            | W   | 0.172      | -            | -                | -                | -         |     2.97 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3871 | 2024-03-04 | AURA              | W   | 0.169      | -            | -                | -                | -         |     0.36 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3935 | 2024-03-01 | Young Ninjas      | W   | 0.151      | -            | -                | -                | -         |     1.17 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3950 | 2024-02-29 | AURA              | W   | 0.143      | -            | -                | -                | -         |     0.31 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3966 | 2024-02-28 | BIG               | W   | 0.136      | 0.500        | 0.154 (0.010)    | -                | -         |     3.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     4001 | 2024-02-26 | MOUZ NXT          | L   | 0.123      | -            | -                | -                | -         |    -1.46 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4402 | 2024-02-08 | Passion UA        | W   | 0.003      | -            | -                | -                | -         |     0.06 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,896.25)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.671 | $500.00        | $335.56         |
| 2024-05-12 |      0.631 | $2,000.00      | $1,262.08       |
| 2024-04-24 |      0.511 | $25,000.00     | $12,763.89      |
| 2024-04-22 |      0.497 | $20,000.00     | $9,930.56       |
| 2024-03-06 |      0.184 | $25,000.00     | $4,604.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
