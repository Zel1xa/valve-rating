### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1098.9<br />
<br />
Final Rank Value (1098.9) = Starting Rank Value (1104.3) + Head To Head Adjustments (-5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.503[<sup>2</sup>](#table1)
- Opponent Network: 0.283[<sup>2</sup>](#table1)
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
|           53 |       38 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.27 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       54 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.14 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       64 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.394 (0.197)    | 0 (0.000) |    10.29 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      105 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.690 (0.345)    | 0 (0.000) |    13.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      220 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.85 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      321 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.66 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      334 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.61 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      366 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.59 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      404 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      411 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1083 | 2024-06-14 | Permitta          | L   | 0.859      | -            | -                | -                | -         |   -19.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1184 | 2024-06-10 | RUSH B            | W   | 0.832      | -            | -                | -                | 0 (0.000) |     8.26 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1190 | 2024-06-10 | 3DMAX             | L   | 0.832      | -            | -                | -                | -         |    -3.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1196 | 2024-06-10 | SINNERS           | L   | 0.832      | -            | -                | -                | -         |   -14.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1227 | 2024-06-09 | Aurora            | L   | 0.826      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1233 | 2024-06-09 | 9 Pandas          | W   | 0.826      | -            | -                | -                | 0 (0.000) |    12.67 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1244 | 2024-06-09 | Monte             | W   | 0.825      | -            | -                | -                | 0 (0.000) |    10.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1246 | 2024-06-09 | SAW               | L   | 0.825      | -            | -                | -                | -         |    -9.85 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1466 | 2024-06-05 | Aurora            | L   | 0.800      | -            | -                | -                | -         |    -2.09 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1513 | 2024-06-04 | Monte             | W   | 0.793      | 0.500        | 0.080 (0.032)    | 0.619 (0.246)    | 0 (0.000) |    10.50 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1918 | 2024-05-20 | Sangal            | L   | 0.692      | -            | -                | -                | -         |    -9.78 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1997 | 2024-05-17 | Zero Tenacity     | W   | 0.674      | 0.500        | 0.137 (0.046)    | 1.000 (0.337)    | -         |    10.47 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2028 | 2024-05-16 | Aurora            | L   | 0.668      | -            | -                | -                | -         |    -1.42 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2044 | 2024-05-16 | Eternal Fire      | L   | 0.666      | -            | -                | -                | -         |    -0.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2083 | 2024-05-15 | B8                | W   | 0.660      | 0.500        | 0.165 (0.055)    | 0.951 (0.314)    | -         |    11.52 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2268 | 2024-05-09 | Endpoint          | L   | 0.620      | -            | -                | -                | -         |   -13.27 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2425 | 2024-05-01 | Passion UA        | L   | 0.566      | -            | -                | -                | -         |   -10.36 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2441 | 2024-05-01 | fnatic            | L   | 0.564      | -            | -                | -                | -         |    -1.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2467 | 2024-04-29 | 3DMAX             | L   | 0.554      | -            | -                | -                | -         |    -0.85 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2476 | 2024-04-29 | Zero Tenacity     | W   | 0.552      | 0.500        | 0.137 (0.038)    | 1.000 (0.276)    | -         |     8.23 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2512 | 2024-04-27 | Sangal            | W   | 0.540      | 0.500        | 0.219 (0.059)    | 0.861 (0.232)    | -         |     9.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2542 | 2024-04-26 | SINNERS           | W   | 0.533      | 0.435        | -                | 0.797 (0.184)    | -         |     9.60 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2571 | 2024-04-25 | ex-Guild Eagles   | W   | 0.526      | -            | -                | -                | -         |     4.09 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2590 | 2024-04-24 | MOUZ NXT          | W   | 0.519      | 0.435        | 0.139 (0.031)    | 1.000 (0.226)    | -         |     7.94 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2642 | 2024-04-21 | Nexus             | W   | 0.499      | -            | -                | -                | -         |     3.97 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2645 | 2024-04-21 | B8                | L   | 0.499      | -            | -                | -                | -         |    -8.11 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2701 | 2024-04-19 | Zero Tenacity     | L   | 0.487      | -            | -                | -                | -         |    -7.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2800 | 2024-04-17 | HAVU              | W   | 0.474      | -            | -                | -                | -         |     1.67 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2803 | 2024-04-17 | Permitta          | L   | 0.473      | -            | -                | -                | -         |    -9.61 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2927 | 2024-04-11 | 500               | L   | 0.433      | -            | -                | -                | -         |   -11.98 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2962 | 2024-04-10 | Aurora            | L   | 0.427      | -            | -                | -                | -         |    -0.60 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3022 | 2024-04-09 | RUSH B            | L   | 0.420      | -            | -                | -                | -         |   -10.32 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3191 | 2024-04-03 | MOUZ NXT          | L   | 0.381      | -            | -                | -                | -         |    -7.07 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3203 | 2024-04-03 | Space             | W   | 0.379      | -            | -                | -                | -         |     2.03 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3239 | 2024-04-02 | AMKAL             | L   | 0.373      | -            | -                | -                | -         |    -5.61 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3246 | 2024-04-02 | Insilio           | L   | 0.372      | -            | -                | -                | -         |    -8.99 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3258 | 2024-04-01 | Metizport         | W   | 0.367      | -            | -                | -                | -         |     2.23 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3424 | 2024-03-21 | FORZE             | W   | 0.293      | -            | -                | -                | -         |     2.26 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3606 | 2024-03-13 | 3DMAX             | W   | 0.240      | 0.500        | 0.506 (0.061)    | -                | -         |     7.24 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3722 | 2024-03-08 | B8                | W   | 0.207      | -            | -                | -                | -         |     3.15 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3778 | 2024-03-06 | Apeks             | W   | 0.193      | -            | -                | -                | -         |     1.55 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3889 | 2024-03-02 | Gaimin Gladiators | L   | 0.166      | -            | -                | -                | -         |    -3.56 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3921 | 2024-02-29 | Monte             | L   | 0.152      | -            | -                | -                | -         |    -3.12 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,658.74)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $6,500.00      | $5,372.13       |
| 2024-05-02 |      0.573 | $500.00        | $286.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
