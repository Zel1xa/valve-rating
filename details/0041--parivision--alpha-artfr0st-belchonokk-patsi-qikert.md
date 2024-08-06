### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1119.6<br />
<br />
Final Rank Value (1119.6) = Starting Rank Value (1150.1) + Head To Head Adjustments (-30.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.511[<sup>2</sup>](#table1)
- Opponent Network: 0.284[<sup>2</sup>](#table1)
- LAN Wins: 0.231[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1150.1
- 400 + ( ( 0.365 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1150.1


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
|           57 |        0 | 2024-08-06 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.42 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           56 |       14 | 2024-08-06 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    11.34 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           55 |       34 | 2024-08-05 | ENCE              | W   | 1.000      | 0.435        | 0.173 (0.075)    | -                | 0 (0.000) |    25.21 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |       49 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       89 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.75 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |      104 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.54 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |      115 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     9.83 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      156 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.040)    | 0.700 (0.350)    | 0 (0.000) |    12.64 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      271 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.58 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      371 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -7.17 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      384 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.15 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      416 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -6.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      454 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    30.67 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      461 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.67 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1133 | 2024-06-14 | Permitta          | L   | 0.845      | -            | -                | -                | -         |   -19.11 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1234 | 2024-06-10 | RUSH B            | W   | 0.819      | -            | -                | -                | 0 (0.000) |     7.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1240 | 2024-06-10 | 3DMAX             | L   | 0.819      | -            | -                | -                | -         |    -3.69 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1246 | 2024-06-10 | SINNERS           | L   | 0.818      | -            | -                | -                | -         |   -15.02 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1277 | 2024-06-09 | Aurora            | L   | 0.813      | -            | -                | -                | -         |    -3.58 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1283 | 2024-06-09 | 9 Pandas          | W   | 0.812      | -            | -                | -                | 0 (0.000) |    11.66 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1294 | 2024-06-09 | Monte             | W   | 0.812      | -            | -                | -                | -         |     9.34 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1296 | 2024-06-09 | SAW               | L   | 0.812      | -            | -                | -                | -         |   -10.80 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1516 | 2024-06-05 | Aurora            | L   | 0.787      | -            | -                | -                | -         |    -2.28 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1563 | 2024-06-04 | Monte             | W   | 0.780      | 0.500        | 0.080 (0.031)    | 0.598 (0.233)    | -         |     9.34 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1968 | 2024-05-20 | Sangal            | L   | 0.679      | -            | -                | -                | -         |    -9.81 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2047 | 2024-05-17 | Zero Tenacity     | W   | 0.660      | 0.500        | 0.143 (0.047)    | 1.000 (0.330)    | -         |     9.42 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2078 | 2024-05-16 | Aurora            | L   | 0.654      | -            | -                | -                | -         |    -1.57 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2094 | 2024-05-16 | Eternal Fire      | L   | 0.652      | -            | -                | -                | -         |    -0.85 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2133 | 2024-05-15 | B8                | W   | 0.647      | 0.500        | 0.170 (0.055)    | 0.912 (0.295)    | -         |    10.41 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2318 | 2024-05-09 | Endpoint          | L   | 0.606      | -            | -                | -                | -         |   -13.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2475 | 2024-05-01 | Passion UA        | L   | 0.553      | -            | -                | -                | -         |   -10.76 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2491 | 2024-05-01 | fnatic            | L   | 0.551      | -            | -                | -                | -         |    -1.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2517 | 2024-04-29 | 3DMAX             | L   | 0.540      | -            | -                | -                | -         |    -0.96 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2526 | 2024-04-29 | Zero Tenacity     | W   | 0.539      | 0.500        | 0.143 (0.038)    | 1.000 (0.269)    | -         |     7.27 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2562 | 2024-04-27 | Sangal            | W   | 0.526      | 0.500        | 0.288 (0.076)    | 0.858 (0.226)    | -         |     9.22 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2592 | 2024-04-26 | SINNERS           | W   | 0.519      | -            | -                | -                | -         |     8.64 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2621 | 2024-04-25 | ex-Guild Eagles   | W   | 0.513      | -            | -                | -                | -         |     3.41 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2640 | 2024-04-24 | MOUZ NXT          | W   | 0.506      | 0.435        | 0.139 (0.030)    | 0.961 (0.211)    | -         |     6.96 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2692 | 2024-04-21 | Nexus             | W   | 0.486      | -            | -                | -                | -         |     3.30 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2695 | 2024-04-21 | B8                | L   | 0.485      | -            | -                | -                | -         |    -8.69 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2751 | 2024-04-19 | Zero Tenacity     | L   | 0.474      | -            | -                | -                | -         |    -8.30 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2850 | 2024-04-17 | HAVU              | W   | 0.460      | -            | -                | -                | -         |     1.30 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2853 | 2024-04-17 | Permitta          | L   | 0.459      | -            | -                | -                | -         |    -9.62 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2977 | 2024-04-11 | 500               | L   | 0.420      | -            | -                | -                | -         |   -11.91 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     3012 | 2024-04-10 | Aurora            | L   | 0.414      | -            | -                | -                | -         |    -0.69 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3072 | 2024-04-09 | RUSH B            | L   | 0.407      | -            | -                | -                | -         |   -10.47 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3241 | 2024-04-03 | MOUZ NXT          | L   | 0.367      | -            | -                | -                | -         |    -7.40 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3253 | 2024-04-03 | Space             | W   | 0.366      | -            | -                | -                | -         |     1.64 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3289 | 2024-04-02 | AMKAL             | L   | 0.360      | -            | -                | -                | -         |    -6.08 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3296 | 2024-04-02 | Insilio           | L   | 0.359      | -            | -                | -                | -         |    -9.10 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3308 | 2024-04-01 | Metizport         | W   | 0.353      | -            | -                | -                | -         |     2.36 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3474 | 2024-03-21 | FORZE             | W   | 0.280      | -            | -                | -                | -         |     1.77 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3656 | 2024-03-13 | 3DMAX             | W   | 0.226      | 0.500        | 0.510 (0.058)    | -                | -         |     6.77 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3772 | 2024-03-08 | B8                | W   | 0.193      | -            | -                | -                | -         |     2.57 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3828 | 2024-03-06 | Apeks             | W   | 0.180      | -            | -                | -                | -         |     1.16 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3939 | 2024-03-02 | Gaimin Gladiators | L   | 0.152      | -            | -                | -                | -         |    -3.56 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3971 | 2024-02-29 | Monte             | L   | 0.139      | -            | -                | -                | -         |    -3.11 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,565.24)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-09 |      0.813 | $6,500.00      | $5,285.31       |
| 2024-05-02 |      0.560 | $500.00        | $279.93         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
