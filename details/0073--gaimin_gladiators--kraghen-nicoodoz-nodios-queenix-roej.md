### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.1<br />
<br />
Final Rank Value (945.1) = Starting Rank Value (964.6) + Head To Head Adjustments (-19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.395[<sup>2</sup>](#table1)
- Opponent Network: 0.132[<sup>2</sup>](#table1)
- LAN Wins: 0.164[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 964.6
- 400 + ( ( 0.276 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 964.6


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
|           53 |      282 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.15 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           52 |     1031 | 2024-06-14 | GUN5             | L   | 0.865      | -            | -                | -                | -         |   -12.71 | kraghen, Nodios, Patti, Queenix, salazar |
|           51 |     1157 | 2024-06-10 | Enterprise       | L   | 0.836      | -            | -                | -                | -         |   -15.72 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1213 | 2024-06-09 | 5W               | L   | 0.830      | -            | -                | -                | -         |   -14.34 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1257 | 2024-06-08 | EYEBALLERS       | W   | 0.824      | 0.450        | -                | 0.510 (0.189)    | 0 (0.000) |    10.37 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1313 | 2024-06-07 | 3DMAX            | L   | 0.818      | -            | -                | -                | -         |    -1.47 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1378 | 2024-06-06 | Astralis Talent  | W   | 0.811      | 0.450        | -                | 0.162 (0.059)    | 0 (0.000) |     5.94 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1630 | 2024-05-30 | Lynn Vision      | L   | 0.762      | -            | -                | -                | -         |   -12.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1673 | 2024-05-28 | The MongolZ      | L   | 0.750      | -            | -                | -                | -         |    -0.16 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1959 | 2024-05-17 | ENCE             | L   | 0.679      | -            | -                | -                | -         |    -2.31 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     1965 | 2024-05-17 | GamerLegion      | L   | 0.678      | -            | -                | -                | -         |    -6.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     1971 | 2024-05-17 | Rebels           | L   | 0.677      | -            | -                | -                | -         |   -10.76 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     2057 | 2024-05-15 | BLEED            | W   | 0.664      | 0.384        | 0.126 (0.032)    | 0.516 (0.132)    | 0 (0.000) |    18.94 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2282 | 2024-05-07 | Grannys Knockers | L   | 0.609      | -            | -                | -                | -         |   -14.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2293 | 2024-05-06 | 500              | W   | 0.604      | -            | -                | -                | -         |     0.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2304 | 2024-05-05 | Sashi            | W   | 0.598      | 0.143        | 0.184 (0.016)    | 0.964 (0.082)    | -         |    14.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2313 | 2024-05-05 | Kronjyllands     | W   | 0.597      | -            | -                | -                | -         |     0.64 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2344 | 2024-05-03 | AMKAL            | L   | 0.584      | -            | -                | -                | -         |    -5.45 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2365 | 2024-05-02 | HAVU             | W   | 0.578      | -            | -                | -                | -         |     3.02 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2377 | 2024-05-02 | SINNERS          | W   | 0.577      | 0.435        | 0.037 (0.009)    | 0.758 (0.190)    | -         |    10.24 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2410 | 2024-04-30 | AMKAL            | L   | 0.565      | -            | -                | -                | -         |    -5.33 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2439 | 2024-04-29 | kONO             | L   | 0.557      | -            | -                | -                | -         |   -13.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2465 | 2024-04-28 | 9 Pandas         | L   | 0.549      | -            | -                | -                | -         |    -9.65 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2512 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.536      | -            | -                | -                | -         |   -10.24 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2573 | 2024-04-23 | Sashi            | L   | 0.517      | -            | -                | -                | -         |    -5.28 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2588 | 2024-04-22 | BLEED            | L   | 0.510      | -            | -                | -                | -         |    -7.87 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2606 | 2024-04-21 | AMKAL            | W   | 0.504      | 0.384        | 0.130 (0.025)    | 0.477 (0.092)    | -         |    10.33 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2643 | 2024-04-20 | Nemiga           | W   | 0.497      | 0.384        | 0.318 (0.061)    | 0.695 (0.133)    | -         |    10.56 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     2785 | 2024-04-17 | SINNERS          | W   | 0.476      | 0.384        | 0.037 (0.007)    | 0.758 (0.139)    | -         |     9.60 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     2806 | 2024-04-16 | Permitta         | W   | 0.470      | 0.384        | -                | 0.876 (0.158)    | -         |     6.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3134 | 2024-04-04 | JANO             | W   | 0.390      | -            | -                | -                | -         |     1.71 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3349 | 2024-03-23 | G2               | L   | 0.311      | -            | -                | -                | -         |    -0.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3358 | 2024-03-22 | FURIA            | W   | 0.305      | 1.000        | 0.284 (0.087)    | 0.491 (0.150)    | 1 (0.305) |     9.44 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3378 | 2024-03-21 | Cloud9           | L   | 0.299      | -            | -                | -                | -         |    -3.97 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3393 | 2024-03-21 | MOUZ             | L   | 0.297      | -            | -                | -                | -         |    -0.08 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3425 | 2024-03-19 | Imperial         | W   | 0.285      | 0.143        | 0.238 (0.010)    | -                | 1 (0.285) |     7.46 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3440 | 2024-03-18 | Lynn Vision      | W   | 0.277      | -            | -                | -                | 1 (0.277) |     4.47 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3459 | 2024-03-17 | The MongolZ      | W   | 0.272      | 0.143        | 1.000 (0.039)    | -                | 1 (0.272) |     8.53 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3471 | 2024-03-17 | Cloud9           | L   | 0.270      | -            | -                | -                | -         |    -3.55 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3806 | 2024-03-04 | BetBoom          | L   | 0.183      | -            | -                | -                | -         |    -0.46 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3812 | 2024-03-03 | ex-Preasy        | L   | 0.179      | -            | -                | -                | -         |    -4.19 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3819 | 2024-03-03 | fnatic           | W   | 0.179      | 0.143        | 0.371 (0.009)    | -                | -         |     5.41 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3828 | 2024-03-03 | SINNERS          | W   | 0.178      | -            | -                | -                | -         |     3.65 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3835 | 2024-03-03 | Monte            | W   | 0.176      | -            | -                | -                | -         |     3.00 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     3851 | 2024-03-02 | PARIVISION       | W   | 0.171      | -            | -                | -                | -         |     3.64 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     3875 | 2024-02-29 | 3DMAX            | L   | 0.159      | -            | -                | -                | -         |    -0.09 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     4022 | 2024-02-22 | ex-Guild Eagles  | W   | 0.111      | -            | -                | -                | 1 (0.111) |     1.06 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     4050 | 2024-02-21 | Apeks            | L   | 0.103      | -            | -                | -                | -         |    -1.90 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4080 | 2024-02-20 | OG               | W   | 0.097      | -            | -                | -                | 1 (0.097) |     1.66 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4095 | 2024-02-19 | MOUZ             | L   | 0.092      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4105 | 2024-02-19 | Monte            | W   | 0.090      | -            | -                | -                | 1 (0.090) |     1.56 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4323 | 2024-02-09 | ex-Preasy        | L   | 0.023      | -            | -                | -                | -         |    -0.53 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4341 | 2024-02-07 | TSM              | W   | 0.010      | -            | -                | -                | -         |     0.05 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,417.36)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.685 | $1,000.00      | $685.00         |
| 2024-05-04 |      0.591 | $2,000.00      | $1,182.78       |
| 2024-05-02 |      0.578 | $1,000.00      | $578.06         |
| 2024-04-22 |      0.510 | $5,000.00      | $2,552.08       |
| 2024-03-31 |      0.365 | $20,000.00     | $7,305.56       |
| 2024-02-09 |      0.023 | $5,000.00      | $113.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
