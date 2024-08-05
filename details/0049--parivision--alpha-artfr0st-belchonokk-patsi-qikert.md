### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1071.1<br />
<br />
Final Rank Value (1071.1) = Starting Rank Value (1106.5) + Head To Head Adjustments (-35.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.503[<sup>2</sup>](#table1)
- Opponent Network: 0.285[<sup>2</sup>](#table1)
- LAN Wins: 0.230[<sup>2</sup>](#table1)

The average of these factors is 0.345<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1106.5
- 400 + ( ( 0.345 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1106.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |       16 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       55 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.34 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       71 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.11 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       81 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.435 (0.217)    | 0 (0.000) |    10.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      122 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.727 (0.363)    | 0 (0.000) |    13.27 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      238 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.81 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      338 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.64 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      351 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.56 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      383 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      421 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      428 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1100 | 2024-06-14 | Permitta          | L   | 0.853      | -            | -                | -                | -         |   -19.00 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1201 | 2024-06-10 | RUSH B            | W   | 0.827      | -            | -                | -                | 0 (0.000) |     8.14 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1207 | 2024-06-10 | 3DMAX             | L   | 0.826      | -            | -                | -                | -         |    -3.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1213 | 2024-06-10 | SINNERS           | L   | 0.826      | -            | -                | -                | -         |   -14.45 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1244 | 2024-06-09 | Aurora            | L   | 0.820      | -            | -                | -                | -         |    -3.32 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1250 | 2024-06-09 | 9 Pandas          | W   | 0.820      | -            | -                | -                | 0 (0.000) |    12.50 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1261 | 2024-06-09 | Monte             | W   | 0.820      | -            | -                | -                | 0 (0.000) |    10.29 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1263 | 2024-06-09 | SAW               | L   | 0.819      | -            | -                | -                | -         |    -9.90 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1483 | 2024-06-05 | Aurora            | L   | 0.794      | -            | -                | -                | -         |    -2.06 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1530 | 2024-06-04 | Monte             | W   | 0.788      | 0.500        | 0.080 (0.032)    | 0.618 (0.244)    | 0 (0.000) |    10.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1935 | 2024-05-20 | Sangal            | L   | 0.687      | -            | -                | -                | -         |    -9.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2014 | 2024-05-17 | Zero Tenacity     | W   | 0.668      | 0.500        | 0.137 (0.046)    | 1.000 (0.334)    | -         |    10.35 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2045 | 2024-05-16 | Aurora            | L   | 0.662      | -            | -                | -                | -         |    -1.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2061 | 2024-05-16 | Eternal Fire      | L   | 0.660      | -            | -                | -                | -         |    -0.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2100 | 2024-05-15 | B8                | W   | 0.655      | 0.500        | 0.165 (0.054)    | 0.947 (0.310)    | -         |    11.36 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2285 | 2024-05-09 | Endpoint          | L   | 0.614      | -            | -                | -                | -         |   -13.20 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2442 | 2024-05-01 | Passion UA        | L   | 0.561      | -            | -                | -                | -         |   -10.26 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2458 | 2024-05-01 | fnatic            | L   | 0.559      | -            | -                | -                | -         |    -1.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2484 | 2024-04-29 | 3DMAX             | L   | 0.548      | -            | -                | -                | -         |    -0.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2493 | 2024-04-29 | Zero Tenacity     | W   | 0.546      | 0.500        | 0.137 (0.037)    | 1.000 (0.273)    | -         |     8.12 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2529 | 2024-04-27 | Sangal            | W   | 0.534      | 0.500        | 0.219 (0.058)    | 0.877 (0.234)    | -         |     9.58 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2559 | 2024-04-26 | SINNERS           | W   | 0.527      | 0.435        | -                | 0.794 (0.182)    | -         |     9.45 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2588 | 2024-04-25 | ex-Guild Eagles   | W   | 0.520      | -            | -                | -                | -         |     3.98 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2607 | 2024-04-24 | MOUZ NXT          | W   | 0.514      | 0.435        | 0.139 (0.031)    | 1.000 (0.223)    | -         |     7.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2659 | 2024-04-21 | Nexus             | W   | 0.494      | -            | -                | -                | -         |     3.88 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2662 | 2024-04-21 | B8                | L   | 0.493      | -            | -                | -                | -         |    -8.07 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2718 | 2024-04-19 | Zero Tenacity     | L   | 0.481      | -            | -                | -                | -         |    -7.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2817 | 2024-04-17 | HAVU              | W   | 0.468      | -            | -                | -                | -         |     1.62 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2820 | 2024-04-17 | Permitta          | L   | 0.467      | -            | -                | -                | -         |    -9.54 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2944 | 2024-04-11 | 500               | L   | 0.427      | -            | -                | -                | -         |   -11.85 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2979 | 2024-04-10 | Aurora            | L   | 0.421      | -            | -                | -                | -         |    -0.59 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3039 | 2024-04-09 | RUSH B            | L   | 0.415      | -            | -                | -                | -         |   -10.21 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3208 | 2024-04-03 | MOUZ NXT          | L   | 0.375      | -            | -                | -                | -         |    -6.96 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3220 | 2024-04-03 | Space             | W   | 0.374      | -            | -                | -                | -         |     1.98 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3256 | 2024-04-02 | AMKAL             | L   | 0.367      | -            | -                | -                | -         |    -5.57 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3263 | 2024-04-02 | Insilio           | L   | 0.367      | -            | -                | -                | -         |    -8.88 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3275 | 2024-04-01 | Metizport         | W   | 0.361      | -            | -                | -                | -         |     2.16 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3441 | 2024-03-21 | FORZE             | W   | 0.287      | -            | -                | -                | -         |     2.18 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3623 | 2024-03-13 | 3DMAX             | W   | 0.234      | 0.500        | 0.508 (0.059)    | -                | -         |     7.07 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3739 | 2024-03-08 | B8                | W   | 0.201      | -            | -                | -                | -         |     3.04 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3795 | 2024-03-06 | Apeks             | W   | 0.188      | -            | -                | -                | -         |     1.47 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3906 | 2024-03-02 | Gaimin Gladiators | L   | 0.160      | -            | -                | -                | -         |    -3.47 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3938 | 2024-02-29 | Monte             | L   | 0.147      | -            | -                | -                | -         |    -3.03 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,618.72)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.821 | $6,500.00      | $5,334.97       |
| 2024-05-02 |      0.568 | $500.00        | $283.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
