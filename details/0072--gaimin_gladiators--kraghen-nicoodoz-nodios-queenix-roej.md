### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.7<br />
<br />
Final Rank Value (946.7) = Starting Rank Value (968.3) + Head To Head Adjustments (-21.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.395[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.165[<sup>2</sup>](#table1)

The average of these factors is 0.278<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 968.3
- 400 + ( ( 0.278 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 968.3


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
|           53 |      259 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.54 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           52 |      983 | 2024-06-14 | GUN5             | L   | 0.867      | -            | -                | -                | -         |   -12.70 | kraghen, Nodios, Patti, Queenix, salazar |
|           51 |     1103 | 2024-06-10 | Enterprise       | L   | 0.838      | -            | -                | -                | -         |   -15.77 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1158 | 2024-06-09 | 5W               | L   | 0.831      | -            | -                | -                | -         |   -14.38 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1199 | 2024-06-08 | EYEBALLERS       | W   | 0.826      | 0.450        | -                | 0.528 (0.196)    | 0 (0.000) |    10.33 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1253 | 2024-06-07 | 3DMAX            | L   | 0.819      | -            | -                | -                | -         |    -1.54 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1318 | 2024-06-06 | Astralis Talent  | W   | 0.813      | 0.450        | -                | 0.168 (0.061)    | 0 (0.000) |     5.82 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1567 | 2024-05-30 | Lynn Vision      | L   | 0.764      | -            | -                | -                | -         |   -12.62 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1610 | 2024-05-28 | The MongolZ      | L   | 0.751      | -            | -                | -                | -         |    -0.16 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1894 | 2024-05-17 | ENCE             | L   | 0.681      | -            | -                | -                | -         |    -2.41 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     1900 | 2024-05-17 | GamerLegion      | L   | 0.680      | -            | -                | -                | -         |    -6.61 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     1906 | 2024-05-17 | Rebels           | L   | 0.679      | -            | -                | -                | -         |   -10.93 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     1992 | 2024-05-15 | BLEED            | W   | 0.666      | 0.384        | 0.126 (0.032)    | 0.534 (0.137)    | 0 (0.000) |    19.01 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2216 | 2024-05-07 | Grannys Knockers | L   | 0.611      | -            | -                | -                | -         |   -15.07 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2227 | 2024-05-06 | 500              | W   | 0.606      | -            | -                | -                | -         |     0.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2238 | 2024-05-05 | Sashi            | W   | 0.600      | 0.143        | 0.184 (0.016)    | 0.998 (0.085)    | -         |    14.42 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2247 | 2024-05-05 | Kronjyllands     | W   | 0.599      | -            | -                | -                | -         |     0.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2278 | 2024-05-03 | AMKAL            | L   | 0.586      | -            | -                | -                | -         |    -5.53 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2299 | 2024-05-02 | HAVU             | W   | 0.580      | -            | -                | -                | -         |     3.01 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2311 | 2024-05-02 | SINNERS          | W   | 0.578      | 0.435        | 0.037 (0.009)    | 0.784 (0.197)    | -         |    10.26 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2344 | 2024-04-30 | AMKAL            | L   | 0.567      | -            | -                | -                | -         |    -5.36 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2373 | 2024-04-29 | kONO             | L   | 0.559      | -            | -                | -                | -         |   -13.13 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2399 | 2024-04-28 | 9 Pandas         | L   | 0.551      | -            | -                | -                | -         |    -9.79 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2446 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.538      | -            | -                | -                | -         |   -10.32 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2507 | 2024-04-23 | Sashi            | L   | 0.519      | -            | -                | -                | -         |    -5.20 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2522 | 2024-04-22 | BLEED            | L   | 0.512      | -            | -                | -                | -         |    -7.98 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2540 | 2024-04-21 | AMKAL            | W   | 0.506      | 0.384        | 0.130 (0.025)    | 0.494 (0.096)    | -         |    10.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2577 | 2024-04-20 | Nemiga           | W   | 0.498      | 0.384        | 0.318 (0.061)    | 0.719 (0.138)    | -         |    10.56 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     2719 | 2024-04-17 | SINNERS          | W   | 0.478      | 0.384        | 0.037 (0.007)    | 0.784 (0.144)    | -         |     9.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     2740 | 2024-04-16 | Permitta         | W   | 0.472      | 0.384        | -                | 0.887 (0.161)    | -         |     6.60 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3068 | 2024-04-04 | JANO             | W   | 0.391      | -            | -                | -                | -         |     1.70 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3279 | 2024-03-23 | G2               | L   | 0.313      | -            | -                | -                | -         |    -0.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3287 | 2024-03-22 | FURIA            | W   | 0.307      | 1.000        | 0.284 (0.087)    | 0.508 (0.156)    | 1 (0.307) |     9.49 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3307 | 2024-03-21 | Cloud9           | L   | 0.301      | -            | -                | -                | -         |    -3.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3322 | 2024-03-21 | MOUZ             | L   | 0.299      | -            | -                | -                | -         |    -0.11 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3354 | 2024-03-19 | Imperial         | W   | 0.287      | 0.143        | 0.234 (0.010)    | -                | 1 (0.287) |     7.27 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3369 | 2024-03-18 | Lynn Vision      | W   | 0.279      | -            | -                | -                | 1 (0.279) |     4.45 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3388 | 2024-03-17 | The MongolZ      | W   | 0.274      | 0.143        | 1.000 (0.039)    | -                | 1 (0.274) |     8.58 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3400 | 2024-03-17 | Cloud9           | L   | 0.272      | -            | -                | -                | -         |    -3.58 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3733 | 2024-03-04 | BetBoom          | L   | 0.185      | -            | -                | -                | -         |    -0.47 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3739 | 2024-03-03 | ex-Preasy        | L   | 0.181      | -            | -                | -                | -         |    -4.26 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3746 | 2024-03-03 | fnatic           | W   | 0.180      | 0.143        | 0.290 (0.007)    | -                | -         |     5.05 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3755 | 2024-03-03 | SINNERS          | W   | 0.180      | -            | -                | -                | -         |     3.69 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3762 | 2024-03-03 | Monte            | W   | 0.178      | -            | -                | -                | -         |     3.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     3778 | 2024-03-02 | PARIVISION       | W   | 0.172      | -            | -                | -                | -         |     3.67 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     3802 | 2024-02-29 | 3DMAX            | L   | 0.161      | -            | -                | -                | -         |    -0.10 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     3949 | 2024-02-22 | ex-Guild Eagles  | W   | 0.112      | -            | -                | -                | 1 (0.112) |     1.06 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     3978 | 2024-02-21 | Apeks            | L   | 0.105      | -            | -                | -                | -         |    -1.95 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4007 | 2024-02-20 | OG               | W   | 0.098      | -            | -                | -                | 1 (0.098) |     1.64 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4022 | 2024-02-19 | MOUZ             | L   | 0.094      | -            | -                | -                | -         |    -0.03 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4032 | 2024-02-19 | Monte            | W   | 0.092      | -            | -                | -                | 1 (0.092) |     1.58 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4250 | 2024-02-09 | ex-Preasy        | L   | 0.024      | -            | -                | -                | -         |    -0.57 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4268 | 2024-02-07 | TSM              | W   | 0.012      | -            | -                | -                | -         |     0.06 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,475.60)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.687 | $1,000.00      | $686.71         |
| 2024-05-04 |      0.593 | $2,000.00      | $1,186.20       |
| 2024-05-02 |      0.580 | $1,000.00      | $579.77         |
| 2024-04-22 |      0.512 | $5,000.00      | $2,560.65       |
| 2024-03-31 |      0.367 | $20,000.00     | $7,339.81       |
| 2024-02-09 |      0.024 | $5,000.00      | $122.45         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
