### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1069.5<br />
<br />
Final Rank Value (1069.5) = Starting Rank Value (1104.3) + Head To Head Adjustments (-34.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.503[<sup>2</sup>](#table1)
- Opponent Network: 0.282[<sup>2</sup>](#table1)
- LAN Wins: 0.229[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1104.3
- 400 + ( ( 0.344 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1104.3


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
|           54 |        3 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.36 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       43 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.32 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       58 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.13 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       69 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.395 (0.198)    | 0 (0.000) |    10.29 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      110 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.690 (0.345)    | 0 (0.000) |    13.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      225 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.83 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      325 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      338 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      370 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.50 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      408 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    30.78 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      415 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1087 | 2024-06-14 | Permitta          | L   | 0.856      | -            | -                | -                | -         |   -19.04 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1188 | 2024-06-10 | RUSH B            | W   | 0.830      | -            | -                | -                | 0 (0.000) |     8.22 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1194 | 2024-06-10 | 3DMAX             | L   | 0.830      | -            | -                | -                | -         |    -3.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1200 | 2024-06-10 | SINNERS           | L   | 0.829      | -            | -                | -                | -         |   -14.56 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1231 | 2024-06-09 | Aurora            | L   | 0.824      | -            | -                | -                | -         |    -3.34 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1237 | 2024-06-09 | 9 Pandas          | W   | 0.823      | -            | -                | -                | 0 (0.000) |    12.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1248 | 2024-06-09 | Monte             | W   | 0.823      | -            | -                | -                | 0 (0.000) |    10.35 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1250 | 2024-06-09 | SAW               | L   | 0.823      | -            | -                | -                | -         |    -9.86 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1470 | 2024-06-05 | Aurora            | L   | 0.798      | -            | -                | -                | -         |    -2.07 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1517 | 2024-06-04 | Monte             | W   | 0.791      | 0.500        | 0.080 (0.032)    | 0.619 (0.245)    | 0 (0.000) |    10.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1922 | 2024-05-20 | Sangal            | L   | 0.690      | -            | -                | -                | -         |    -9.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2001 | 2024-05-17 | Zero Tenacity     | W   | 0.671      | 0.500        | 0.137 (0.046)    | 1.000 (0.336)    | -         |    10.43 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2032 | 2024-05-16 | Aurora            | L   | 0.665      | -            | -                | -                | -         |    -1.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2048 | 2024-05-16 | Eternal Fire      | L   | 0.663      | -            | -                | -                | -         |    -0.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2087 | 2024-05-15 | B8                | W   | 0.658      | 0.500        | 0.165 (0.054)    | 0.951 (0.313)    | -         |    11.47 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2272 | 2024-05-09 | Endpoint          | L   | 0.617      | -            | -                | -                | -         |   -13.23 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2429 | 2024-05-01 | Passion UA        | L   | 0.564      | -            | -                | -                | -         |   -10.31 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2445 | 2024-05-01 | fnatic            | L   | 0.562      | -            | -                | -                | -         |    -1.48 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2471 | 2024-04-29 | 3DMAX             | L   | 0.551      | -            | -                | -                | -         |    -0.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2480 | 2024-04-29 | Zero Tenacity     | W   | 0.550      | 0.500        | 0.137 (0.038)    | 1.000 (0.275)    | -         |     8.19 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2516 | 2024-04-27 | Sangal            | W   | 0.537      | 0.500        | 0.219 (0.059)    | 0.861 (0.231)    | -         |     9.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2546 | 2024-04-26 | SINNERS           | W   | 0.530      | 0.435        | -                | 0.797 (0.184)    | -         |     9.55 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2575 | 2024-04-25 | ex-Guild Eagles   | W   | 0.524      | -            | -                | -                | -         |     4.05 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2594 | 2024-04-24 | MOUZ NXT          | W   | 0.517      | 0.435        | 0.139 (0.031)    | 1.000 (0.225)    | -         |     7.89 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2646 | 2024-04-21 | Nexus             | W   | 0.497      | -            | -                | -                | -         |     3.94 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2649 | 2024-04-21 | B8                | L   | 0.496      | -            | -                | -                | -         |    -8.08 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2705 | 2024-04-19 | Zero Tenacity     | L   | 0.485      | -            | -                | -                | -         |    -7.69 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2804 | 2024-04-17 | HAVU              | W   | 0.471      | -            | -                | -                | -         |     1.65 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2807 | 2024-04-17 | Permitta          | L   | 0.470      | -            | -                | -                | -         |    -9.57 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2931 | 2024-04-11 | 500               | L   | 0.431      | -            | -                | -                | -         |   -11.92 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2966 | 2024-04-10 | Aurora            | L   | 0.425      | -            | -                | -                | -         |    -0.59 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3026 | 2024-04-09 | RUSH B            | L   | 0.418      | -            | -                | -                | -         |   -10.27 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3195 | 2024-04-03 | MOUZ NXT          | L   | 0.378      | -            | -                | -                | -         |    -7.03 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3207 | 2024-04-03 | Space             | W   | 0.377      | -            | -                | -                | -         |     2.01 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3243 | 2024-04-02 | AMKAL             | L   | 0.371      | -            | -                | -                | -         |    -5.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3250 | 2024-04-02 | Insilio           | L   | 0.370      | -            | -                | -                | -         |    -8.94 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3262 | 2024-04-01 | Metizport         | W   | 0.364      | -            | -                | -                | -         |     2.21 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3428 | 2024-03-21 | FORZE             | W   | 0.291      | -            | -                | -                | -         |     2.24 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3610 | 2024-03-13 | 3DMAX             | W   | 0.237      | 0.500        | 0.507 (0.060)    | -                | -         |     7.17 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3726 | 2024-03-08 | B8                | W   | 0.204      | -            | -                | -                | -         |     3.10 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3782 | 2024-03-06 | Apeks             | W   | 0.191      | -            | -                | -                | -         |     1.52 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3893 | 2024-03-02 | Gaimin Gladiators | L   | 0.163      | -            | -                | -                | -         |    -3.52 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3925 | 2024-02-29 | Monte             | L   | 0.150      | -            | -                | -                | -         |    -3.08 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,642.05)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.824 | $6,500.00      | $5,356.63       |
| 2024-05-02 |      0.571 | $500.00        | $285.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
