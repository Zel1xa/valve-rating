### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1095.5<br />
<br />
Final Rank Value (1095.5) = Starting Rank Value (1102.2) + Head To Head Adjustments (-6.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.279[<sup>2</sup>](#table1)
- LAN Wins: 0.229[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1102.2
- 400 + ( ( 0.343 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1102.2


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
|           53 |        8 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       24 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.17 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       33 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.354 (0.177)    | 0 (0.000) |    10.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |       75 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.082 (0.041)    | 0.690 (0.345)    | 0 (0.000) |    13.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      188 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.87 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      289 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      302 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.67 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      334 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.63 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      372 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      379 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1051 | 2024-06-14 | Permitta          | L   | 0.860      | -            | -                | -                | -         |   -19.07 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1152 | 2024-06-10 | RUSH B            | W   | 0.834      | -            | -                | -                | 0 (0.000) |     8.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1158 | 2024-06-10 | 3DMAX             | L   | 0.834      | -            | -                | -                | -         |    -3.47 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1164 | 2024-06-10 | SINNERS           | L   | 0.833      | -            | -                | -                | -         |   -15.26 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1195 | 2024-06-09 | Aurora            | L   | 0.828      | -            | -                | -                | -         |    -3.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1201 | 2024-06-09 | 9 Pandas          | W   | 0.828      | -            | -                | -                | 0 (0.000) |    12.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1212 | 2024-06-09 | Monte             | W   | 0.827      | -            | -                | -                | 0 (0.000) |    10.45 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1214 | 2024-06-09 | SAW               | L   | 0.827      | -            | -                | -                | -         |    -9.85 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1434 | 2024-06-05 | Aurora            | L   | 0.802      | -            | -                | -                | -         |    -2.10 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1481 | 2024-06-04 | Monte             | W   | 0.795      | 0.500        | 0.080 (0.032)    | 0.618 (0.246)    | 0 (0.000) |    10.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1886 | 2024-05-20 | Sangal            | L   | 0.694      | -            | -                | -                | -         |    -9.86 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1965 | 2024-05-17 | Zero Tenacity     | W   | 0.676      | 0.500        | 0.137 (0.046)    | 1.000 (0.338)    | -         |    10.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     1996 | 2024-05-16 | Aurora            | L   | 0.670      | -            | -                | -                | -         |    -1.42 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2012 | 2024-05-16 | Eternal Fire      | L   | 0.667      | -            | -                | -                | -         |    -0.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2051 | 2024-05-15 | B8                | W   | 0.662      | 0.500        | 0.165 (0.055)    | 0.912 (0.302)    | -         |    11.59 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2236 | 2024-05-09 | Endpoint          | L   | 0.621      | -            | -                | -                | -         |   -13.28 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2393 | 2024-05-01 | Passion UA        | L   | 0.568      | -            | -                | -                | -         |   -10.41 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2409 | 2024-05-01 | fnatic            | L   | 0.566      | -            | -                | -                | -         |    -1.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2435 | 2024-04-29 | 3DMAX             | L   | 0.555      | -            | -                | -                | -         |    -0.85 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2444 | 2024-04-29 | Zero Tenacity     | W   | 0.554      | 0.500        | 0.137 (0.038)    | 1.000 (0.277)    | -         |     8.21 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2480 | 2024-04-27 | Sangal            | W   | 0.541      | 0.500        | 0.219 (0.059)    | 0.862 (0.233)    | -         |     9.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2510 | 2024-04-26 | SINNERS           | W   | 0.535      | 0.435        | -                | 0.758 (0.176)    | -         |     8.60 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2539 | 2024-04-25 | ex-Guild Eagles   | W   | 0.528      | -            | -                | -                | -         |     4.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2558 | 2024-04-24 | MOUZ NXT          | W   | 0.521      | 0.435        | 0.139 (0.031)    | 1.000 (0.226)    | -         |     7.96 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2610 | 2024-04-21 | Nexus             | W   | 0.501      | -            | -                | -                | -         |     3.99 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2613 | 2024-04-21 | B8                | L   | 0.501      | -            | -                | -                | -         |    -8.10 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2669 | 2024-04-19 | Zero Tenacity     | L   | 0.489      | -            | -                | -                | -         |    -7.76 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2768 | 2024-04-17 | HAVU              | W   | 0.476      | -            | -                | -                | -         |     1.69 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2771 | 2024-04-17 | Permitta          | L   | 0.475      | -            | -                | -                | -         |    -9.63 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2895 | 2024-04-11 | 500               | L   | 0.435      | -            | -                | -                | -         |   -12.02 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2930 | 2024-04-10 | Aurora            | L   | 0.429      | -            | -                | -                | -         |    -0.60 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     2990 | 2024-04-09 | RUSH B            | L   | 0.422      | -            | -                | -                | -         |   -10.52 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3159 | 2024-04-03 | MOUZ NXT          | L   | 0.382      | -            | -                | -                | -         |    -7.10 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3171 | 2024-04-03 | Space             | W   | 0.381      | -            | -                | -                | -         |     2.08 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3207 | 2024-04-02 | AMKAL             | L   | 0.375      | -            | -                | -                | -         |    -5.62 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3214 | 2024-04-02 | Insilio           | L   | 0.374      | -            | -                | -                | -         |    -9.04 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3226 | 2024-04-01 | Metizport         | W   | 0.368      | -            | -                | -                | -         |     2.94 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3392 | 2024-03-21 | FORZE             | W   | 0.295      | -            | -                | -                | -         |     2.30 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3574 | 2024-03-13 | 3DMAX             | W   | 0.241      | 0.500        | 0.506 (0.061)    | -                | -         |     7.29 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3690 | 2024-03-08 | B8                | W   | 0.208      | -            | -                | -                | -         |     3.19 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3746 | 2024-03-06 | Apeks             | W   | 0.195      | -            | -                | -                | -         |     1.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3857 | 2024-03-02 | Gaimin Gladiators | L   | 0.168      | -            | -                | -                | -         |    -3.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3889 | 2024-02-29 | Monte             | L   | 0.154      | -            | -                | -                | -         |    -3.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,671.22)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $6,500.00      | $5,383.72       |
| 2024-05-02 |      0.575 | $500.00        | $287.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
