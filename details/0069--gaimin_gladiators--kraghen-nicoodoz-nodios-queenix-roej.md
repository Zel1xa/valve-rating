### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.0<br />
<br />
Final Rank Value (956.0) = Starting Rank Value (980.8) + Head To Head Adjustments (-24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.178[<sup>2</sup>](#table1)

The average of these factors is 0.282<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 980.8
- 400 + ( ( 0.282 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 980.8


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
|           55 |      201 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.37 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           54 |      958 | 2024-06-14 | GUN5             | L   | 0.880      | -            | -                | -                | -         |   -12.53 | kraghen, Nodios, Patti, Queenix, salazar |
|           53 |     1085 | 2024-06-10 | Enterprise       | L   | 0.851      | -            | -                | -                | -         |   -16.45 | kraghen, Nodios, Patti, Queenix, salazar |
|           52 |     1142 | 2024-06-09 | 5W               | L   | 0.845      | -            | -                | -                | -         |   -14.80 | kraghen, Nodios, Patti, Queenix, salazar |
|           51 |     1187 | 2024-06-08 | EYEBALLERS       | W   | 0.839      | 0.450        | -                | 0.512 (0.194)    | 0 (0.000) |    10.28 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1250 | 2024-06-07 | 3DMAX            | L   | 0.833      | -            | -                | -                | -         |    -1.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1317 | 2024-06-06 | Astralis Talent  | W   | 0.826      | 0.450        | -                | 0.201 (0.075)    | 0 (0.000) |     5.97 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1573 | 2024-05-30 | Lynn Vision      | L   | 0.777      | -            | -                | -                | -         |   -12.80 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1616 | 2024-05-28 | The MongolZ      | L   | 0.765      | -            | -                | -                | -         |    -0.17 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1930 | 2024-05-17 | ENCE             | L   | 0.694      | -            | -                | -                | -         |    -2.49 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1936 | 2024-05-17 | GamerLegion      | L   | 0.693      | -            | -                | -                | -         |    -6.85 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1942 | 2024-05-17 | Rebels           | L   | 0.692      | -            | -                | -                | -         |   -11.16 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     2032 | 2024-05-15 | BLEED            | W   | 0.679      | 0.384        | 0.128 (0.033)    | 0.513 (0.134)    | 0 (0.000) |    19.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     2264 | 2024-05-07 | Grannys Knockers | L   | 0.624      | -            | -                | -                | -         |   -15.10 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     2275 | 2024-05-06 | 500              | W   | 0.619      | -            | -                | -                | -         |     0.62 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2286 | 2024-05-05 | Sashi            | W   | 0.613      | 0.143        | 0.187 (0.016)    | 0.970 (0.085)    | -         |    14.56 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2295 | 2024-05-05 | Kronjyllands     | W   | 0.612      | -            | -                | -                | -         |     0.61 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2326 | 2024-05-03 | AMKAL            | L   | 0.599      | -            | -                | -                | -         |    -5.84 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2348 | 2024-05-02 | HAVU             | W   | 0.593      | -            | -                | -                | -         |     3.00 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2360 | 2024-05-02 | SINNERS          | W   | 0.592      | 0.435        | 0.038 (0.010)    | 0.768 (0.198)    | -         |     9.76 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2395 | 2024-04-30 | AMKAL            | L   | 0.580      | -            | -                | -                | -         |    -5.69 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2424 | 2024-04-29 | kONO             | L   | 0.572      | -            | -                | -                | -         |   -13.31 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2450 | 2024-04-28 | 9 Pandas         | L   | 0.564      | -            | -                | -                | -         |   -10.24 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2498 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.551      | -            | -                | -                | -         |   -10.86 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2561 | 2024-04-23 | Sashi            | L   | 0.532      | -            | -                | -                | -         |    -5.61 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2577 | 2024-04-22 | BLEED            | L   | 0.525      | -            | -                | -                | -         |    -8.37 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2596 | 2024-04-21 | AMKAL            | W   | 0.519      | 0.384        | 0.132 (0.026)    | 0.482 (0.096)    | -         |    10.37 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2635 | 2024-04-20 | Nemiga           | W   | 0.512      | 0.384        | 0.324 (0.064)    | 0.697 (0.137)    | -         |    10.76 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2780 | 2024-04-17 | SINNERS          | W   | 0.491      | 0.384        | 0.038 (0.007)    | 0.768 (0.145)    | -         |     9.02 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2802 | 2024-04-16 | Permitta         | W   | 0.485      | 0.384        | -                | 0.801 (0.149)    | -         |     6.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     3132 | 2024-04-04 | JANO             | W   | 0.405      | -            | -                | -                | -         |     1.70 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     3359 | 2024-03-23 | G2               | L   | 0.326      | -            | -                | -                | -         |    -0.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3368 | 2024-03-22 | FURIA            | W   | 0.320      | 1.000        | 0.286 (0.092)    | 0.494 (0.158)    | 1 (0.320) |     9.90 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3388 | 2024-03-21 | Cloud9           | L   | 0.314      | -            | -                | -                | -         |    -4.10 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3403 | 2024-03-21 | MOUZ             | L   | 0.312      | -            | -                | -                | -         |    -0.08 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3435 | 2024-03-19 | Imperial         | W   | 0.300      | 0.143        | 0.239 (0.010)    | -                | 1 (0.300) |     7.80 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3450 | 2024-03-18 | Lynn Vision      | W   | 0.292      | -            | -                | -                | 1 (0.292) |     4.66 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3469 | 2024-03-17 | The MongolZ      | W   | 0.287      | 0.143        | 1.000 (0.041)    | -                | 1 (0.287) |     9.00 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3481 | 2024-03-17 | Cloud9           | L   | 0.285      | -            | -                | -                | -         |    -3.68 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3828 | 2024-03-04 | BetBoom          | L   | 0.198      | -            | -                | -                | -         |    -0.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3834 | 2024-03-03 | ex-Preasy        | L   | 0.194      | -            | -                | -                | -         |    -4.60 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3841 | 2024-03-03 | fnatic           | W   | 0.194      | 0.143        | 0.292 (0.008)    | -                | -         |     5.41 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3850 | 2024-03-03 | SINNERS          | W   | 0.193      | -            | -                | -                | -         |     3.56 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3857 | 2024-03-03 | Monte            | W   | 0.191      | -            | -                | -                | -         |     3.25 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3873 | 2024-03-02 | PARIVISION       | W   | 0.186      | -            | -                | -                | -         |     3.81 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3898 | 2024-02-29 | 3DMAX            | L   | 0.174      | -            | -                | -                | -         |    -0.11 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     4053 | 2024-02-22 | ex-Guild Eagles  | W   | 0.126      | -            | -                | -                | 1 (0.126) |     1.16 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     4083 | 2024-02-21 | Apeks            | L   | 0.118      | -            | -                | -                | -         |    -2.19 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     4112 | 2024-02-20 | OG               | W   | 0.112      | -            | -                | -                | 1 (0.112) |     1.84 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     4127 | 2024-02-19 | MOUZ             | L   | 0.107      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4137 | 2024-02-19 | Monte            | W   | 0.105      | -            | -                | -                | 1 (0.105) |     1.82 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4366 | 2024-02-09 | ex-Preasy        | L   | 0.038      | -            | -                | -                | -         |    -0.89 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4384 | 2024-02-07 | TSM              | W   | 0.025      | -            | -                | -                | -         |     0.12 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4406 | 2024-02-05 | ex-Preasy        | W   | 0.011      | -            | -                | -                | -         |     0.09 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4441 | 2024-02-03 | Sashi            | L   | 0.000      | -            | -                | -                | -         |    -0.00 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,927.36)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.700 | $1,000.00      | $700.00         |
| 2024-05-04 |      0.606 | $2,000.00      | $1,212.78       |
| 2024-05-02 |      0.593 | $1,000.00      | $593.06         |
| 2024-04-22 |      0.525 | $5,000.00      | $2,627.08       |
| 2024-03-31 |      0.380 | $20,000.00     | $7,605.56       |
| 2024-02-09 |      0.038 | $5,000.00      | $188.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
