### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1056.0<br />
<br />
Final Rank Value (1056.0) = Starting Rank Value (957.4) + Head To Head Adjustments (98.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.489[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.4
- 400 + ( ( 0.272 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 957.4


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
|           43 |     2263 | 2024-05-11 | B8                | L   | 0.624      | -            | -                | -                | -         |    -9.77 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2291 | 2024-05-09 | Sampi             | W   | 0.613      | 0.435        | -                | 1.000 (0.267)    | 0 (0.000) |     6.14 | CYPHER, draken, faveN, hampus, VLDN |
|           41 |     2333 | 2024-05-07 | 1WIN              | L   | 0.599      | -            | -                | -                | -         |   -12.28 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2357 | 2024-05-06 | Insilio           | W   | 0.591      | -            | -                | -                | 0 (0.000) |     6.30 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2421 | 2024-05-02 | AMKAL             | L   | 0.567      | -            | -                | -                | -         |    -7.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2457 | 2024-05-01 | MOUZ NXT          | L   | 0.558      | -            | -                | -                | -         |    -9.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2489 | 2024-04-30 | Permitta          | W   | 0.551      | 0.384        | -                | 0.902 (0.191)    | 0 (0.000) |     5.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2512 | 2024-04-28 | B8                | W   | 0.540      | 0.500        | 0.165 (0.044)    | 0.935 (0.252)    | 0 (0.000) |     7.77 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2562 | 2024-04-26 | ex-Guild Eagles   | W   | 0.526      | -            | -                | -                | 0 (0.000) |     3.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2570 | 2024-04-26 | DMS               | W   | 0.525      | -            | -                | -                | 0 (0.000) |     4.81 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2612 | 2024-04-24 | Permitta          | W   | 0.513      | 0.435        | -                | 0.902 (0.201)    | 0 (0.000) |     6.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2613 | 2024-04-24 | Nemiga            | L   | 0.512      | -            | -                | -                | -         |    -5.48 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     2632 | 2024-04-23 | B8                | W   | 0.506      | 0.500        | 0.165 (0.042)    | 0.935 (0.236)    | 0 (0.000) |     7.75 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     2641 | 2024-04-23 | Sashi             | L   | 0.504      | -            | -                | -                | -         |    -5.73 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     2649 | 2024-04-22 | Sangal            | W   | 0.499      | 0.500        | 0.219 (0.055)    | 0.866 (0.216)    | 0 (0.000) |     9.56 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     2651 | 2024-04-22 | Gaimin Gladiators | W   | 0.498      | -            | -                | -                | 0 (0.000) |     7.65 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     2666 | 2024-04-21 | Illuminar         | W   | 0.493      | -            | -                | -                | -         |     0.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     2672 | 2024-04-21 | BIG               | W   | 0.491      | 0.384        | 0.154 (0.029)    | -                | -         |    12.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     2695 | 2024-04-20 | MOUZ NXT          | W   | 0.486      | 0.500        | 0.139 (0.034)    | 0.987 (0.240)    | -         |     8.38 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     2752 | 2024-04-19 | Sampi             | W   | 0.478      | 0.384        | -                | 1.000 (0.184)    | -         |     5.53 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     2809 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.471      | 0.500        | 0.031 (0.007)    | -                | -         |     6.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     2844 | 2024-04-17 | 3DMAX             | L   | 0.464      | -            | -                | -                | -         |    -0.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     2863 | 2024-04-16 | KOI               | W   | 0.459      | 0.384        | 0.058 (0.010)    | -                | -         |     8.80 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     2873 | 2024-04-16 | SINNERS           | W   | 0.457      | 0.384        | -                | 0.809 (0.142)    | -         |    10.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3053 | 2024-04-09 | Alliance          | W   | 0.413      | -            | -                | -                | -         |     4.24 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3061 | 2024-04-09 | HAVU              | W   | 0.412      | -            | -                | -                | -         |     2.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3145 | 2024-04-05 | BetBoom           | L   | 0.386      | -            | -                | -                | -         |    -1.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3148 | 2024-04-05 | Alliance          | W   | 0.385      | -            | -                | -                | -         |     4.12 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3187 | 2024-04-04 | Benched Heroes    | W   | 0.379      | -            | -                | -                | -         |     0.45 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3194 | 2024-04-04 | BetBoom           | L   | 0.378      | -            | -                | -                | -         |    -1.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3264 | 2024-04-02 | Passion UA        | W   | 0.366      | 0.384        | 0.173 (0.024)    | 1.000 (0.141)    | -         |     6.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3286 | 2024-04-01 | Enterprise        | L   | 0.358      | -            | -                | -                | -         |    -6.72 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3641 | 2024-03-13 | Sashi             | W   | 0.231      | -            | -                | -                | -         |     5.16 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3739 | 2024-03-09 | Endpoint          | W   | 0.204      | -            | -                | -                | -         |     2.52 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     3806 | 2024-03-06 | fnatic            | L   | 0.186      | -            | -                | -                | -         |    -0.22 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     3852 | 2024-03-05 | BetBoom           | W   | 0.178      | 0.500        | 0.249 (0.022)    | -                | -         |     5.20 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     3860 | 2024-03-04 | Rebels            | W   | 0.173      | -            | -                | -                | -         |     3.00 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     3869 | 2024-03-04 | AURA              | W   | 0.171      | -            | -                | -                | -         |     0.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     3933 | 2024-03-01 | Young Ninjas      | W   | 0.153      | -            | -                | -                | -         |     1.18 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     3948 | 2024-02-29 | AURA              | W   | 0.145      | -            | -                | -                | -         |     0.31 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     3964 | 2024-02-28 | BIG               | W   | 0.138      | 0.500        | 0.154 (0.011)    | -                | -         |     3.81 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     3999 | 2024-02-26 | MOUZ NXT          | L   | 0.125      | -            | -                | -                | -         |    -1.48 | CeRq, faveN, hampus, lauNX, VLDN    |
|            1 |     4400 | 2024-02-08 | Passion UA        | W   | 0.005      | -            | -                | -                | -         |     0.10 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,027.15)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.673 | $500.00        | $336.46         |
| 2024-05-12 |      0.633 | $2,000.00      | $1,265.69       |
| 2024-04-24 |      0.512 | $25,000.00     | $12,809.03      |
| 2024-04-22 |      0.498 | $20,000.00     | $9,966.67       |
| 2024-03-06 |      0.186 | $25,000.00     | $4,649.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
