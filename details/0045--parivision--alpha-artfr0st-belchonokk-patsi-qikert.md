### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1098.5<br />
<br />
Final Rank Value (1098.5) = Starting Rank Value (1103.6) + Head To Head Adjustments (-5.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.503[<sup>2</sup>](#table1)
- Opponent Network: 0.281[<sup>2</sup>](#table1)
- LAN Wins: 0.229[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1103.6
- 400 + ( ( 0.344 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1103.6


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
|           53 |       37 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.25 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       53 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.15 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       63 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.394 (0.197)    | 0 (0.000) |    10.30 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      104 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.690 (0.345)    | 0 (0.000) |    13.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      219 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.86 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      320 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      333 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.62 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      365 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.58 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      403 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      410 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1082 | 2024-06-14 | Permitta          | L   | 0.859      | -            | -                | -                | -         |   -19.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1183 | 2024-06-10 | RUSH B            | W   | 0.833      | -            | -                | -                | 0 (0.000) |     8.28 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1189 | 2024-06-10 | 3DMAX             | L   | 0.832      | -            | -                | -                | -         |    -3.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1195 | 2024-06-10 | SINNERS           | L   | 0.832      | -            | -                | -                | -         |   -14.59 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1226 | 2024-06-09 | Aurora            | L   | 0.826      | -            | -                | -                | -         |    -3.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1232 | 2024-06-09 | 9 Pandas          | W   | 0.826      | -            | -                | -                | 0 (0.000) |    12.69 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1243 | 2024-06-09 | Monte             | W   | 0.826      | -            | -                | -                | 0 (0.000) |    10.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1245 | 2024-06-09 | SAW               | L   | 0.825      | -            | -                | -                | -         |    -9.84 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1465 | 2024-06-05 | Aurora            | L   | 0.800      | -            | -                | -                | -         |    -2.09 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1512 | 2024-06-04 | Monte             | W   | 0.794      | 0.500        | 0.080 (0.032)    | 0.619 (0.246)    | 0 (0.000) |    10.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1917 | 2024-05-20 | Sangal            | L   | 0.693      | -            | -                | -                | -         |    -9.80 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1996 | 2024-05-17 | Zero Tenacity     | W   | 0.674      | 0.500        | 0.137 (0.046)    | 1.000 (0.337)    | -         |    10.46 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2027 | 2024-05-16 | Aurora            | L   | 0.668      | -            | -                | -                | -         |    -1.42 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2043 | 2024-05-16 | Eternal Fire      | L   | 0.666      | -            | -                | -                | -         |    -0.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2082 | 2024-05-15 | B8                | W   | 0.661      | 0.500        | 0.165 (0.055)    | 0.912 (0.301)    | -         |    11.54 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2267 | 2024-05-09 | Endpoint          | L   | 0.620      | -            | -                | -                | -         |   -13.26 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2424 | 2024-05-01 | Passion UA        | L   | 0.567      | -            | -                | -                | -         |   -10.35 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2440 | 2024-05-01 | fnatic            | L   | 0.565      | -            | -                | -                | -         |    -1.48 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2466 | 2024-04-29 | 3DMAX             | L   | 0.554      | -            | -                | -                | -         |    -0.85 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2475 | 2024-04-29 | Zero Tenacity     | W   | 0.552      | 0.500        | 0.137 (0.038)    | 1.000 (0.276)    | -         |     8.21 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2511 | 2024-04-27 | Sangal            | W   | 0.540      | 0.500        | 0.219 (0.059)    | 0.861 (0.233)    | -         |     9.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2541 | 2024-04-26 | SINNERS           | W   | 0.533      | 0.435        | -                | 0.797 (0.185)    | -         |     9.61 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2570 | 2024-04-25 | ex-Guild Eagles   | W   | 0.526      | -            | -                | -                | -         |     4.10 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2589 | 2024-04-24 | MOUZ NXT          | W   | 0.520      | 0.435        | 0.139 (0.031)    | 1.000 (0.226)    | -         |     7.94 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2641 | 2024-04-21 | Nexus             | W   | 0.500      | -            | -                | -                | -         |     3.98 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2644 | 2024-04-21 | B8                | L   | 0.499      | -            | -                | -                | -         |    -8.11 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2700 | 2024-04-19 | Zero Tenacity     | L   | 0.487      | -            | -                | -                | -         |    -7.75 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2799 | 2024-04-17 | HAVU              | W   | 0.474      | -            | -                | -                | -         |     1.67 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2802 | 2024-04-17 | Permitta          | L   | 0.473      | -            | -                | -                | -         |    -9.60 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2926 | 2024-04-11 | 500               | L   | 0.434      | -            | -                | -                | -         |   -11.98 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2961 | 2024-04-10 | Aurora            | L   | 0.427      | -            | -                | -                | -         |    -0.60 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3021 | 2024-04-09 | RUSH B            | L   | 0.421      | -            | -                | -                | -         |   -10.32 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3190 | 2024-04-03 | MOUZ NXT          | L   | 0.381      | -            | -                | -                | -         |    -7.08 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3202 | 2024-04-03 | Space             | W   | 0.380      | -            | -                | -                | -         |     2.03 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3238 | 2024-04-02 | AMKAL             | L   | 0.373      | -            | -                | -                | -         |    -5.61 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3245 | 2024-04-02 | Insilio           | L   | 0.373      | -            | -                | -                | -         |    -8.99 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3257 | 2024-04-01 | Metizport         | W   | 0.367      | -            | -                | -                | -         |     2.24 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3423 | 2024-03-21 | FORZE             | W   | 0.293      | -            | -                | -                | -         |     2.27 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3605 | 2024-03-13 | 3DMAX             | W   | 0.240      | 0.500        | 0.506 (0.061)    | -                | -         |     7.25 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3721 | 2024-03-08 | B8                | W   | 0.207      | -            | -                | -                | -         |     3.16 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3777 | 2024-03-06 | Apeks             | W   | 0.194      | -            | -                | -                | -         |     1.55 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3888 | 2024-03-02 | Gaimin Gladiators | L   | 0.166      | -            | -                | -                | -         |    -3.56 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3920 | 2024-02-29 | Monte             | L   | 0.153      | -            | -                | -                | -         |    -3.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,660.84)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.827 | $6,500.00      | $5,374.09       |
| 2024-05-02 |      0.574 | $500.00        | $286.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
