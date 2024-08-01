### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.0<br />
<br />
Final Rank Value (956.0) = Starting Rank Value (980.6) + Head To Head Adjustments (-24.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.178[<sup>2</sup>](#table1)

The average of these factors is 0.282<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 980.6
- 400 + ( ( 0.282 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 980.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |      203 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.37 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           53 |      960 | 2024-06-14 | GUN5             | L   | 0.880      | -            | -                | -                | -         |   -12.53 | kraghen, Nodios, Patti, Queenix, salazar |
|           52 |     1087 | 2024-06-10 | Enterprise       | L   | 0.851      | -            | -                | -                | -         |   -16.45 | kraghen, Nodios, Patti, Queenix, salazar |
|           51 |     1144 | 2024-06-09 | 5W               | L   | 0.844      | -            | -                | -                | -         |   -14.80 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1189 | 2024-06-08 | EYEBALLERS       | W   | 0.839      | 0.450        | -                | 0.512 (0.194)    | 0 (0.000) |    10.28 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1252 | 2024-06-07 | 3DMAX            | L   | 0.833      | -            | -                | -                | -         |    -1.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1319 | 2024-06-06 | Astralis Talent  | W   | 0.826      | 0.450        | -                | 0.201 (0.075)    | 0 (0.000) |     5.97 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1575 | 2024-05-30 | Lynn Vision      | L   | 0.777      | -            | -                | -                | -         |   -12.79 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1618 | 2024-05-28 | The MongolZ      | L   | 0.764      | -            | -                | -                | -         |    -0.17 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1932 | 2024-05-17 | ENCE             | L   | 0.694      | -            | -                | -                | -         |    -2.47 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1938 | 2024-05-17 | GamerLegion      | L   | 0.693      | -            | -                | -                | -         |    -6.82 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     1944 | 2024-05-17 | Rebels           | L   | 0.692      | -            | -                | -                | -         |   -11.16 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     2034 | 2024-05-15 | BLEED            | W   | 0.679      | 0.384        | 0.128 (0.033)    | 0.513 (0.134)    | 0 (0.000) |    19.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     2266 | 2024-05-07 | Grannys Knockers | L   | 0.624      | -            | -                | -                | -         |   -15.10 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2277 | 2024-05-06 | 500              | W   | 0.619      | -            | -                | -                | -         |     0.62 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2288 | 2024-05-05 | Sashi            | W   | 0.613      | 0.143        | 0.186 (0.016)    | 0.970 (0.085)    | -         |    14.56 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2297 | 2024-05-05 | Kronjyllands     | W   | 0.612      | -            | -                | -                | -         |     0.61 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2328 | 2024-05-03 | AMKAL            | L   | 0.599      | -            | -                | -                | -         |    -5.83 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2350 | 2024-05-02 | HAVU             | W   | 0.593      | -            | -                | -                | -         |     3.00 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2362 | 2024-05-02 | SINNERS          | W   | 0.591      | 0.435        | 0.038 (0.010)    | 0.768 (0.197)    | -         |     9.77 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2397 | 2024-04-30 | AMKAL            | L   | 0.580      | -            | -                | -                | -         |    -5.68 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2426 | 2024-04-29 | kONO             | L   | 0.572      | -            | -                | -                | -         |   -13.30 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2452 | 2024-04-28 | 9 Pandas         | L   | 0.564      | -            | -                | -                | -         |   -10.23 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2500 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.551      | -            | -                | -                | -         |   -10.85 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2563 | 2024-04-23 | Sashi            | L   | 0.532      | -            | -                | -                | -         |    -5.61 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2579 | 2024-04-22 | BLEED            | L   | 0.525      | -            | -                | -                | -         |    -8.37 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2598 | 2024-04-21 | AMKAL            | W   | 0.519      | 0.384        | 0.132 (0.026)    | 0.482 (0.096)    | -         |    10.37 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2637 | 2024-04-20 | Nemiga           | W   | 0.511      | 0.384        | 0.324 (0.064)    | 0.697 (0.137)    | -         |    10.76 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2782 | 2024-04-17 | SINNERS          | W   | 0.491      | 0.384        | 0.038 (0.007)    | 0.768 (0.145)    | -         |     9.01 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     2804 | 2024-04-16 | Permitta         | W   | 0.485      | 0.384        | -                | 0.801 (0.149)    | -         |     6.30 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     3134 | 2024-04-04 | JANO             | W   | 0.404      | -            | -                | -                | -         |     1.70 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3361 | 2024-03-23 | G2               | L   | 0.326      | -            | -                | -                | -         |    -0.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3370 | 2024-03-22 | FURIA            | W   | 0.320      | 1.000        | 0.286 (0.092)    | 0.494 (0.158)    | 1 (0.320) |     9.89 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3390 | 2024-03-21 | Cloud9           | L   | 0.314      | -            | -                | -                | -         |    -4.10 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3405 | 2024-03-21 | MOUZ             | L   | 0.312      | -            | -                | -                | -         |    -0.08 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3437 | 2024-03-19 | Imperial         | W   | 0.300      | 0.143        | 0.239 (0.010)    | -                | 1 (0.300) |     7.79 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3452 | 2024-03-18 | Lynn Vision      | W   | 0.292      | -            | -                | -                | 1 (0.292) |     4.65 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3471 | 2024-03-17 | The MongolZ      | W   | 0.287      | 0.143        | 1.000 (0.041)    | -                | 1 (0.287) |     8.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3483 | 2024-03-17 | Cloud9           | L   | 0.285      | -            | -                | -                | -         |    -3.68 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3830 | 2024-03-04 | BetBoom          | L   | 0.198      | -            | -                | -                | -         |    -0.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3836 | 2024-03-03 | ex-Preasy        | L   | 0.194      | -            | -                | -                | -         |    -4.59 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3843 | 2024-03-03 | fnatic           | W   | 0.193      | 0.143        | 0.292 (0.008)    | -                | -         |     5.40 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3852 | 2024-03-03 | SINNERS          | W   | 0.193      | -            | -                | -                | -         |     3.56 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3859 | 2024-03-03 | Monte            | W   | 0.191      | -            | -                | -                | -         |     3.24 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3875 | 2024-03-02 | PARIVISION       | W   | 0.185      | -            | -                | -                | -         |     3.88 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     3900 | 2024-02-29 | 3DMAX            | L   | 0.174      | -            | -                | -                | -         |    -0.11 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     4055 | 2024-02-22 | ex-Guild Eagles  | W   | 0.125      | -            | -                | -                | 1 (0.125) |     1.16 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     4085 | 2024-02-21 | Apeks            | L   | 0.118      | -            | -                | -                | -         |    -2.18 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     4114 | 2024-02-20 | OG               | W   | 0.111      | -            | -                | -                | 1 (0.111) |     1.84 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4129 | 2024-02-19 | MOUZ             | L   | 0.107      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4139 | 2024-02-19 | Monte            | W   | 0.105      | -            | -                | -                | 1 (0.105) |     1.81 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4368 | 2024-02-09 | ex-Preasy        | L   | 0.037      | -            | -                | -                | -         |    -0.88 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4386 | 2024-02-07 | TSM              | W   | 0.025      | -            | -                | -                | -         |     0.12 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4408 | 2024-02-05 | ex-Preasy        | W   | 0.011      | -            | -                | -                | -         |     0.09 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,917.92)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.700 | $1,000.00      | $699.72         |
| 2024-05-04 |      0.606 | $2,000.00      | $1,212.22       |
| 2024-05-02 |      0.593 | $1,000.00      | $592.78         |
| 2024-04-22 |      0.525 | $5,000.00      | $2,625.69       |
| 2024-03-31 |      0.380 | $20,000.00     | $7,600.00       |
| 2024-02-09 |      0.037 | $5,000.00      | $187.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
