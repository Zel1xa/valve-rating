### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1096.9<br />
<br />
Final Rank Value (1096.9) = Starting Rank Value (1102.2) + Head To Head Adjustments (-5.3)<br />

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
|           53 |       16 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.22 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       32 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.20 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       41 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.354 (0.177)    | 0 (0.000) |    10.32 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |       83 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.082 (0.041)    | 0.690 (0.345)    | 0 (0.000) |    13.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      196 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      297 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.63 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      310 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      342 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.55 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      380 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    30.78 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      387 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1059 | 2024-06-14 | Permitta          | L   | 0.860      | -            | -                | -                | -         |   -19.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1160 | 2024-06-10 | RUSH B            | W   | 0.833      | -            | -                | -                | 0 (0.000) |     8.29 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1166 | 2024-06-10 | 3DMAX             | L   | 0.833      | -            | -                | -                | -         |    -3.45 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1172 | 2024-06-10 | SINNERS           | L   | 0.833      | -            | -                | -                | -         |   -15.21 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1203 | 2024-06-09 | Aurora            | L   | 0.827      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1209 | 2024-06-09 | 9 Pandas          | W   | 0.827      | -            | -                | -                | 0 (0.000) |    12.71 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1220 | 2024-06-09 | Monte             | W   | 0.826      | -            | -                | -                | 0 (0.000) |    10.45 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1222 | 2024-06-09 | SAW               | L   | 0.826      | -            | -                | -                | -         |    -9.81 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1442 | 2024-06-05 | Aurora            | L   | 0.801      | -            | -                | -                | -         |    -2.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1489 | 2024-06-04 | Monte             | W   | 0.795      | 0.500        | 0.080 (0.032)    | 0.619 (0.246)    | 0 (0.000) |    10.58 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1894 | 2024-05-20 | Sangal            | L   | 0.693      | -            | -                | -                | -         |    -9.82 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1973 | 2024-05-17 | Zero Tenacity     | W   | 0.675      | 0.500        | 0.137 (0.046)    | 1.000 (0.337)    | -         |    10.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2004 | 2024-05-16 | Aurora            | L   | 0.669      | -            | -                | -                | -         |    -1.41 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2020 | 2024-05-16 | Eternal Fire      | L   | 0.667      | -            | -                | -                | -         |    -0.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2059 | 2024-05-15 | B8                | W   | 0.662      | 0.500        | 0.165 (0.055)    | 0.912 (0.302)    | -         |    11.57 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2244 | 2024-05-09 | Endpoint          | L   | 0.621      | -            | -                | -                | -         |   -13.27 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2401 | 2024-05-01 | Passion UA        | L   | 0.567      | -            | -                | -                | -         |   -10.38 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2417 | 2024-05-01 | fnatic            | L   | 0.565      | -            | -                | -                | -         |    -1.48 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2443 | 2024-04-29 | 3DMAX             | L   | 0.555      | -            | -                | -                | -         |    -0.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2452 | 2024-04-29 | Zero Tenacity     | W   | 0.553      | 0.500        | 0.137 (0.038)    | 1.000 (0.277)    | -         |     8.20 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2488 | 2024-04-27 | Sangal            | W   | 0.541      | 0.500        | 0.219 (0.059)    | 0.861 (0.233)    | -         |     9.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2518 | 2024-04-26 | SINNERS           | W   | 0.534      | 0.435        | -                | 0.757 (0.176)    | -         |     8.59 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2547 | 2024-04-25 | ex-Guild Eagles   | W   | 0.527      | -            | -                | -                | -         |     4.16 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2566 | 2024-04-24 | MOUZ NXT          | W   | 0.520      | 0.435        | 0.139 (0.031)    | 1.000 (0.226)    | -         |     7.96 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2618 | 2024-04-21 | Nexus             | W   | 0.501      | -            | -                | -                | -         |     3.98 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2621 | 2024-04-21 | B8                | L   | 0.500      | -            | -                | -                | -         |    -8.10 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2677 | 2024-04-19 | Zero Tenacity     | L   | 0.488      | -            | -                | -                | -         |    -7.75 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2776 | 2024-04-17 | HAVU              | W   | 0.475      | -            | -                | -                | -         |     1.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2779 | 2024-04-17 | Permitta          | L   | 0.474      | -            | -                | -                | -         |    -9.62 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2903 | 2024-04-11 | 500               | L   | 0.434      | -            | -                | -                | -         |   -12.00 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2938 | 2024-04-10 | Aurora            | L   | 0.428      | -            | -                | -                | -         |    -0.60 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     2998 | 2024-04-09 | RUSH B            | L   | 0.422      | -            | -                | -                | -         |   -10.34 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3167 | 2024-04-03 | MOUZ NXT          | L   | 0.382      | -            | -                | -                | -         |    -7.08 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3179 | 2024-04-03 | Space             | W   | 0.380      | -            | -                | -                | -         |     2.07 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3215 | 2024-04-02 | AMKAL             | L   | 0.374      | -            | -                | -                | -         |    -5.61 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3222 | 2024-04-02 | Insilio           | L   | 0.373      | -            | -                | -                | -         |    -9.00 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3234 | 2024-04-01 | Metizport         | W   | 0.368      | -            | -                | -                | -         |     2.95 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3400 | 2024-03-21 | FORZE             | W   | 0.294      | -            | -                | -                | -         |     2.29 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3582 | 2024-03-13 | 3DMAX             | W   | 0.241      | 0.500        | 0.506 (0.061)    | -                | -         |     7.27 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3698 | 2024-03-08 | B8                | W   | 0.208      | -            | -                | -                | -         |     3.17 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3754 | 2024-03-06 | Apeks             | W   | 0.194      | -            | -                | -                | -         |     1.57 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3865 | 2024-03-02 | Gaimin Gladiators | L   | 0.167      | -            | -                | -                | -         |    -3.57 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3897 | 2024-02-29 | Monte             | L   | 0.153      | -            | -                | -                | -         |    -3.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,666.19)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $6,500.00      | $5,379.05       |
| 2024-05-02 |      0.574 | $500.00        | $287.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
