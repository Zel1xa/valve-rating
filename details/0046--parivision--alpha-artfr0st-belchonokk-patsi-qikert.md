### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1098.5<br />
<br />
Final Rank Value (1098.5) = Starting Rank Value (1109.6) + Head To Head Adjustments (-11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.509[<sup>2</sup>](#table1)
- Opponent Network: 0.283[<sup>2</sup>](#table1)
- LAN Wins: 0.230[<sup>2</sup>](#table1)

The average of these factors is 0.346<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1109.6
- 400 + ( ( 0.346 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1109.6


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
|           55 |        9 | 2024-08-05 | ENCE              | W   | 1.000      | 0.435        | 0.174 (0.076)    | 0.432 (0.188)    | 0 (0.000) |    25.62 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |       24 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       64 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       79 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.09 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       90 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | -                | 0.430 (0.215)    | 0 (0.000) |    10.49 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      131 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.718 (0.359)    | 0 (0.000) |    13.24 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      246 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      346 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.64 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      359 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.53 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      391 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      429 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      436 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1108 | 2024-06-14 | Permitta          | L   | 0.852      | -            | -                | -                | -         |   -19.01 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1209 | 2024-06-10 | RUSH B            | W   | 0.826      | -            | -                | -                | 0 (0.000) |     8.09 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1215 | 2024-06-10 | 3DMAX             | L   | 0.825      | -            | -                | -                | -         |    -3.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1221 | 2024-06-10 | SINNERS           | L   | 0.825      | -            | -                | -                | -         |   -14.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1252 | 2024-06-09 | Aurora            | L   | 0.819      | -            | -                | -                | -         |    -3.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1258 | 2024-06-09 | 9 Pandas          | W   | 0.819      | -            | -                | -                | 0 (0.000) |    12.44 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1269 | 2024-06-09 | Monte             | W   | 0.818      | -            | -                | -                | 0 (0.000) |    10.20 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1271 | 2024-06-09 | SAW               | L   | 0.818      | -            | -                | -                | -         |    -9.97 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1491 | 2024-06-05 | Aurora            | L   | 0.793      | -            | -                | -                | -         |    -2.06 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1538 | 2024-06-04 | Monte             | W   | 0.787      | 0.500        | 0.080 (0.032)    | 0.611 (0.240)    | -         |    10.30 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1943 | 2024-05-20 | Sangal            | L   | 0.685      | -            | -                | -                | -         |    -9.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2022 | 2024-05-17 | Zero Tenacity     | W   | 0.667      | 0.500        | 0.143 (0.048)    | 1.000 (0.333)    | -         |    10.24 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2053 | 2024-05-16 | Aurora            | L   | 0.661      | -            | -                | -                | -         |    -1.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2069 | 2024-05-16 | Eternal Fire      | L   | 0.659      | -            | -                | -                | -         |    -0.73 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2108 | 2024-05-15 | B8                | W   | 0.654      | 0.500        | 0.165 (0.054)    | 0.935 (0.306)    | -         |    11.28 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2293 | 2024-05-09 | Endpoint          | L   | 0.613      | -            | -                | -                | -         |   -13.24 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2450 | 2024-05-01 | Passion UA        | L   | 0.559      | -            | -                | -                | -         |   -10.26 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2466 | 2024-05-01 | fnatic            | L   | 0.557      | -            | -                | -                | -         |    -1.50 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2492 | 2024-04-29 | 3DMAX             | L   | 0.547      | -            | -                | -                | -         |    -0.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2501 | 2024-04-29 | Zero Tenacity     | W   | 0.545      | 0.500        | 0.143 (0.039)    | 1.000 (0.273)    | -         |     8.09 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2537 | 2024-04-27 | Sangal            | W   | 0.533      | 0.500        | 0.219 (0.058)    | 0.866 (0.231)    | -         |     9.52 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2567 | 2024-04-26 | SINNERS           | W   | 0.526      | -            | -                | -                | -         |     9.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2596 | 2024-04-25 | ex-Guild Eagles   | W   | 0.519      | -            | -                | -                | -         |     3.93 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2615 | 2024-04-24 | MOUZ NXT          | W   | 0.512      | 0.435        | 0.139 (0.031)    | 0.987 (0.220)    | -         |     7.77 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2667 | 2024-04-21 | Nexus             | W   | 0.493      | -            | -                | -                | -         |     3.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2670 | 2024-04-21 | B8                | L   | 0.492      | -            | -                | -                | -         |    -8.11 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2726 | 2024-04-19 | Zero Tenacity     | L   | 0.480      | -            | -                | -                | -         |    -7.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2825 | 2024-04-17 | HAVU              | W   | 0.467      | -            | -                | -                | -         |     1.59 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2828 | 2024-04-17 | Permitta          | L   | 0.466      | -            | -                | -                | -         |    -9.57 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2952 | 2024-04-11 | 500               | L   | 0.426      | -            | -                | -                | -         |   -11.84 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2987 | 2024-04-10 | Aurora            | L   | 0.420      | -            | -                | -                | -         |    -0.59 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3047 | 2024-04-09 | RUSH B            | L   | 0.414      | -            | -                | -                | -         |   -10.21 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3216 | 2024-04-03 | MOUZ NXT          | L   | 0.374      | -            | -                | -                | -         |    -6.97 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3228 | 2024-04-03 | Space             | W   | 0.372      | -            | -                | -                | -         |     1.94 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3264 | 2024-04-02 | AMKAL             | L   | 0.366      | -            | -                | -                | -         |    -5.61 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3271 | 2024-04-02 | Insilio           | L   | 0.366      | -            | -                | -                | -         |    -8.88 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3283 | 2024-04-01 | Metizport         | W   | 0.360      | -            | -                | -                | -         |     2.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3449 | 2024-03-21 | FORZE             | W   | 0.286      | -            | -                | -                | -         |     2.15 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3631 | 2024-03-13 | 3DMAX             | W   | 0.233      | 0.500        | 0.508 (0.059)    | -                | -         |     7.03 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3747 | 2024-03-08 | B8                | W   | 0.200      | -            | -                | -                | -         |     2.99 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3803 | 2024-03-06 | Apeks             | W   | 0.186      | -            | -                | -                | -         |     1.44 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3914 | 2024-03-02 | Gaimin Gladiators | L   | 0.159      | -            | -                | -                | -         |    -3.46 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3946 | 2024-02-29 | Monte             | L   | 0.146      | -            | -                | -                | -         |    -3.03 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,610.94)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.820 | $6,500.00      | $5,327.74       |
| 2024-05-02 |      0.566 | $500.00        | $283.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
