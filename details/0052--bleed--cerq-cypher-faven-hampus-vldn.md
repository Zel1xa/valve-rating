### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1057.2<br />
<br />
Final Rank Value (1057.2) = Starting Rank Value (958.5) + Head To Head Adjustments (98.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.490[<sup>1</sup>](#table2)
- Bounty Collected: 0.393[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.5
- 400 + ( ( 0.273 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 958.5


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
|           43 |     2237 | 2024-05-11 | B8                | L   | 0.631      | -            | -                | -                | -         |    -9.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2265 | 2024-05-09 | Sampi             | W   | 0.621      | 0.435        | -                | 1.000 (0.270)    | 0 (0.000) |     6.18 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2307 | 2024-05-07 | 1WIN              | L   | 0.607      | -            | -                | -                | -         |   -12.63 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2331 | 2024-05-06 | Insilio           | W   | 0.598      | -            | -                | -                | 0 (0.000) |     6.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2395 | 2024-05-02 | AMKAL             | L   | 0.574      | -            | -                | -                | -         |    -7.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2431 | 2024-05-01 | MOUZ NXT          | L   | 0.565      | -            | -                | -                | -         |    -9.64 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2463 | 2024-04-30 | Permitta          | W   | 0.558      | 0.384        | -                | 0.876 (0.188)    | 0 (0.000) |     5.67 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2486 | 2024-04-28 | B8                | W   | 0.547      | 0.500        | 0.165 (0.045)    | 0.951 (0.260)    | 0 (0.000) |     7.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2536 | 2024-04-26 | ex-Guild Eagles   | W   | 0.533      | -            | -                | -                | 0 (0.000) |     3.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2544 | 2024-04-26 | DMS               | W   | 0.532      | -            | -                | -                | 0 (0.000) |     4.84 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2586 | 2024-04-24 | Permitta          | W   | 0.520      | 0.435        | -                | 0.876 (0.198)    | 0 (0.000) |     6.26 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2587 | 2024-04-24 | Nemiga            | L   | 0.520      | -            | -                | -                | -         |    -5.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2606 | 2024-04-23 | B8                | W   | 0.513      | 0.500        | 0.165 (0.042)    | 0.951 (0.244)    | 0 (0.000) |     7.78 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2615 | 2024-04-23 | Sashi             | L   | 0.512      | -            | -                | -                | -         |    -5.87 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2623 | 2024-04-22 | Sangal            | W   | 0.506      | 0.500        | 0.219 (0.055)    | 0.861 (0.218)    | 0 (0.000) |     9.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2625 | 2024-04-22 | Gaimin Gladiators | W   | 0.506      | -            | -                | -                | 0 (0.000) |     7.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2640 | 2024-04-21 | Illuminar         | W   | 0.500      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2646 | 2024-04-21 | BIG               | W   | 0.498      | 0.384        | 0.155 (0.030)    | -                | -         |    12.76 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2669 | 2024-04-20 | MOUZ NXT          | W   | 0.493      | 0.500        | 0.139 (0.034)    | 1.000 (0.246)    | -         |     8.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2726 | 2024-04-19 | Sampi             | W   | 0.485      | 0.384        | -                | 1.000 (0.186)    | -         |     5.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2783 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.478      | 0.500        | 0.031 (0.008)    | -                | -         |     6.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2818 | 2024-04-17 | 3DMAX             | L   | 0.472      | -            | -                | -                | -         |    -0.47 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2837 | 2024-04-16 | KOI               | W   | 0.467      | 0.384        | 0.058 (0.010)    | -                | -         |     8.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2847 | 2024-04-16 | SINNERS           | W   | 0.465      | 0.384        | -                | 0.797 (0.142)    | -         |    10.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3027 | 2024-04-09 | Alliance          | W   | 0.420      | -            | -                | -                | -         |     4.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3035 | 2024-04-09 | HAVU              | W   | 0.419      | -            | -                | -                | -         |     2.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3119 | 2024-04-05 | BetBoom           | L   | 0.393      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3122 | 2024-04-05 | Alliance          | W   | 0.393      | -            | -                | -                | -         |     4.17 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3161 | 2024-04-04 | Benched Heroes    | W   | 0.386      | -            | -                | -                | -         |     0.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3168 | 2024-04-04 | BetBoom           | L   | 0.386      | -            | -                | -                | -         |    -1.06 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3238 | 2024-04-02 | Passion UA        | W   | 0.373      | 0.384        | 0.172 (0.025)    | 1.000 (0.143)    | -         |     6.90 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3260 | 2024-04-01 | Enterprise        | L   | 0.366      | -            | -                | -                | -         |    -6.91 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3615 | 2024-03-13 | Sashi             | W   | 0.238      | -            | -                | -                | -         |     5.29 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3713 | 2024-03-09 | Endpoint          | W   | 0.212      | -            | -                | -                | -         |     2.58 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3780 | 2024-03-06 | fnatic            | L   | 0.193      | -            | -                | -                | -         |    -0.23 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3826 | 2024-03-05 | BetBoom           | W   | 0.186      | 0.500        | 0.251 (0.023)    | -                | -         |     5.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3834 | 2024-03-04 | Rebels            | W   | 0.181      | -            | -                | -                | -         |     3.12 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3843 | 2024-03-04 | AURA              | W   | 0.178      | -            | -                | -                | -         |     0.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3907 | 2024-03-01 | Young Ninjas      | W   | 0.160      | -            | -                | -                | -         |     1.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3922 | 2024-02-29 | AURA              | W   | 0.152      | -            | -                | -                | -         |     0.33 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3938 | 2024-02-28 | BIG               | W   | 0.145      | 0.500        | 0.155 (0.011)    | -                | -         |     4.01 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3973 | 2024-02-26 | MOUZ NXT          | L   | 0.132      | -            | -                | -                | -         |    -1.59 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4374 | 2024-02-08 | Passion UA        | W   | 0.012      | -            | -                | -                | -         |     0.25 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,552.44)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.680 | $500.00        | $340.08         |
| 2024-05-12 |      0.640 | $2,000.00      | $1,280.19       |
| 2024-04-24 |      0.520 | $25,000.00     | $12,990.16      |
| 2024-04-22 |      0.506 | $20,000.00     | $10,111.57      |
| 2024-03-06 |      0.193 | $25,000.00     | $4,830.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
