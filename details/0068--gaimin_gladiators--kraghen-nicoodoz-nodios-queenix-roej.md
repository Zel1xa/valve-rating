### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  957.3<br />
<br />
Final Rank Value (957.3) = Starting Rank Value (982.3) + Head To Head Adjustments (-25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.179[<sup>2</sup>](#table1)

The average of these factors is 0.283<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 982.3
- 400 + ( ( 0.283 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 982.3


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
|           55 |      197 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.42 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           54 |      954 | 2024-06-14 | GUN5             | L   | 0.881      | -            | -                | -                | -         |   -12.57 | kraghen, Nodios, Patti, Queenix, salazar |
|           53 |     1081 | 2024-06-10 | Enterprise       | L   | 0.853      | -            | -                | -                | -         |   -16.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           52 |     1138 | 2024-06-09 | 5W               | L   | 0.846      | -            | -                | -                | -         |   -14.85 | kraghen, Nodios, Patti, Queenix, salazar |
|           51 |     1183 | 2024-06-08 | EYEBALLERS       | W   | 0.841      | 0.450        | -                | 0.513 (0.194)    | 0 (0.000) |    10.27 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1246 | 2024-06-07 | 3DMAX            | L   | 0.834      | -            | -                | -                | -         |    -1.64 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1313 | 2024-06-06 | Astralis Talent  | W   | 0.828      | 0.450        | -                | 0.201 (0.075)    | 0 (0.000) |     5.96 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1569 | 2024-05-30 | Lynn Vision      | L   | 0.779      | -            | -                | -                | -         |   -12.83 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1612 | 2024-05-28 | The MongolZ      | L   | 0.766      | -            | -                | -                | -         |    -0.17 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1926 | 2024-05-17 | ENCE             | L   | 0.696      | -            | -                | -                | -         |    -2.49 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1932 | 2024-05-17 | GamerLegion      | L   | 0.694      | -            | -                | -                | -         |    -6.86 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1938 | 2024-05-17 | Rebels           | L   | 0.693      | -            | -                | -                | -         |   -11.20 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     2028 | 2024-05-15 | BLEED            | W   | 0.680      | 0.384        | 0.128 (0.034)    | 0.513 (0.134)    | 0 (0.000) |    19.39 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     2260 | 2024-05-07 | Grannys Knockers | L   | 0.626      | -            | -                | -                | -         |   -15.15 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     2271 | 2024-05-06 | 500              | W   | 0.620      | -            | -                | -                | -         |     0.62 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2282 | 2024-05-05 | Sashi            | W   | 0.615      | 0.143        | 0.187 (0.016)    | 0.971 (0.085)    | -         |    14.59 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2291 | 2024-05-05 | Kronjyllands     | W   | 0.614      | -            | -                | -                | -         |     0.61 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2322 | 2024-05-03 | AMKAL            | L   | 0.601      | -            | -                | -                | -         |    -5.86 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2344 | 2024-05-02 | HAVU             | W   | 0.594      | -            | -                | -                | -         |     2.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2356 | 2024-05-02 | SINNERS          | W   | 0.593      | 0.435        | 0.038 (0.010)    | 0.768 (0.198)    | -         |     9.77 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2391 | 2024-04-30 | AMKAL            | L   | 0.581      | -            | -                | -                | -         |    -5.71 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2420 | 2024-04-29 | kONO             | L   | 0.573      | -            | -                | -                | -         |   -13.36 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2446 | 2024-04-28 | 9 Pandas         | L   | 0.566      | -            | -                | -                | -         |   -10.28 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2494 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.553      | -            | -                | -                | -         |   -10.91 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2557 | 2024-04-23 | Sashi            | L   | 0.534      | -            | -                | -                | -         |    -5.64 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2573 | 2024-04-22 | BLEED            | L   | 0.527      | -            | -                | -                | -         |    -8.40 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2592 | 2024-04-21 | AMKAL            | W   | 0.521      | 0.384        | 0.132 (0.026)    | 0.482 (0.096)    | -         |    10.38 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2631 | 2024-04-20 | Nemiga           | W   | 0.513      | 0.384        | 0.324 (0.064)    | 0.697 (0.137)    | -         |    10.78 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2776 | 2024-04-17 | SINNERS          | W   | 0.493      | 0.384        | 0.038 (0.007)    | 0.768 (0.145)    | -         |     9.03 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2798 | 2024-04-16 | Permitta         | W   | 0.487      | 0.384        | -                | 0.801 (0.150)    | -         |     6.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     3128 | 2024-04-04 | JANO             | W   | 0.406      | -            | -                | -                | -         |     1.69 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     3355 | 2024-03-23 | G2               | L   | 0.328      | -            | -                | -                | -         |    -0.05 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3364 | 2024-03-22 | FURIA            | W   | 0.322      | 1.000        | 0.286 (0.092)    | 0.495 (0.159)    | 1 (0.322) |     9.94 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3384 | 2024-03-21 | Cloud9           | L   | 0.315      | -            | -                | -                | -         |    -4.11 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3399 | 2024-03-21 | MOUZ             | L   | 0.313      | -            | -                | -                | -         |    -0.08 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3431 | 2024-03-19 | Imperial         | W   | 0.302      | 0.143        | 0.240 (0.010)    | -                | 1 (0.302) |     7.84 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3446 | 2024-03-18 | Lynn Vision      | W   | 0.294      | -            | -                | -                | 1 (0.294) |     4.67 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3465 | 2024-03-17 | The MongolZ      | W   | 0.288      | 0.143        | 1.000 (0.041)    | -                | 1 (0.288) |     9.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3477 | 2024-03-17 | Cloud9           | L   | 0.287      | -            | -                | -                | -         |    -3.70 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3824 | 2024-03-04 | BetBoom          | L   | 0.199      | -            | -                | -                | -         |    -0.51 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3830 | 2024-03-03 | ex-Preasy        | L   | 0.195      | -            | -                | -                | -         |    -4.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3837 | 2024-03-03 | fnatic           | W   | 0.195      | 0.143        | 0.292 (0.008)    | -                | -         |     5.45 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3846 | 2024-03-03 | SINNERS          | W   | 0.195      | -            | -                | -                | -         |     3.59 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3853 | 2024-03-03 | Monte            | W   | 0.193      | -            | -                | -                | -         |     3.27 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3869 | 2024-03-02 | PARIVISION       | W   | 0.187      | -            | -                | -                | -         |     3.84 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3894 | 2024-02-29 | 3DMAX            | L   | 0.175      | -            | -                | -                | -         |    -0.11 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     4049 | 2024-02-22 | ex-Guild Eagles  | W   | 0.127      | -            | -                | -                | 1 (0.127) |     1.17 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     4079 | 2024-02-21 | Apeks            | L   | 0.120      | -            | -                | -                | -         |    -2.21 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     4108 | 2024-02-20 | OG               | W   | 0.113      | -            | -                | -                | 1 (0.113) |     1.86 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     4123 | 2024-02-19 | MOUZ             | L   | 0.109      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4133 | 2024-02-19 | Monte            | W   | 0.107      | -            | -                | -                | 1 (0.107) |     1.84 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4362 | 2024-02-09 | ex-Preasy        | L   | 0.039      | -            | -                | -                | -         |    -0.93 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4380 | 2024-02-07 | TSM              | W   | 0.027      | -            | -                | -                | -         |     0.13 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4402 | 2024-02-05 | ex-Preasy        | W   | 0.013      | -            | -                | -                | -         |     0.10 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4437 | 2024-02-03 | Sashi            | L   | 0.002      | -            | -                | -                | -         |    -0.01 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,974.58)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.701 | $1,000.00      | $701.39         |
| 2024-05-04 |      0.608 | $2,000.00      | $1,215.56       |
| 2024-05-02 |      0.594 | $1,000.00      | $594.44         |
| 2024-04-22 |      0.527 | $5,000.00      | $2,634.03       |
| 2024-03-31 |      0.382 | $20,000.00     | $7,633.33       |
| 2024-02-09 |      0.039 | $5,000.00      | $195.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
