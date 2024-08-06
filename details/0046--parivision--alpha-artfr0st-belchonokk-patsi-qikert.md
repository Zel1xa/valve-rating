### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.2<br />
<br />
Final Rank Value (1100.2) = Starting Rank Value (1110.6) + Head To Head Adjustments (-10.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.509[<sup>2</sup>](#table1)
- Opponent Network: 0.283[<sup>2</sup>](#table1)
- LAN Wins: 0.231[<sup>2</sup>](#table1)

The average of these factors is 0.346<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1110.6
- 400 + ( ( 0.346 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1110.6


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
|           55 |       16 | 2024-08-05 | ENCE              | W   | 1.000      | 0.435        | 0.173 (0.075)    | 0.431 (0.187)    | 0 (0.000) |    25.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |       31 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       71 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       86 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.06 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       97 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | -                | 0.471 (0.235)    | 0 (0.000) |    10.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      138 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.716 (0.358)    | 0 (0.000) |    13.17 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      253 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.00 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      353 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.67 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      366 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.48 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      398 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.54 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      436 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.709 (0.461)    | 1 (1.000) |    30.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      443 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1115 | 2024-06-14 | Permitta          | L   | 0.847      | -            | -                | -                | -         |   -18.80 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1216 | 2024-06-10 | RUSH B            | W   | 0.821      | -            | -                | -                | 0 (0.000) |     7.99 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1222 | 2024-06-10 | 3DMAX             | L   | 0.820      | -            | -                | -                | -         |    -3.35 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1228 | 2024-06-10 | SINNERS           | L   | 0.820      | -            | -                | -                | -         |   -14.35 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1259 | 2024-06-09 | Aurora            | L   | 0.815      | -            | -                | -                | -         |    -3.27 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1265 | 2024-06-09 | 9 Pandas          | W   | 0.814      | -            | -                | -                | 0 (0.000) |    12.30 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1276 | 2024-06-09 | Monte             | W   | 0.814      | -            | -                | -                | 0 (0.000) |    10.12 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1278 | 2024-06-09 | SAW               | L   | 0.813      | -            | -                | -                | -         |   -10.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1498 | 2024-06-05 | Aurora            | L   | 0.789      | -            | -                | -                | -         |    -2.04 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1545 | 2024-06-04 | Monte             | W   | 0.782      | 0.500        | 0.080 (0.031)    | 0.611 (0.239)    | -         |    10.21 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1950 | 2024-05-20 | Sangal            | L   | 0.681      | -            | -                | -                | -         |    -9.62 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2029 | 2024-05-17 | Zero Tenacity     | W   | 0.662      | 0.500        | 0.143 (0.047)    | 1.000 (0.331)    | -         |    10.16 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2060 | 2024-05-16 | Aurora            | L   | 0.656      | -            | -                | -                | -         |    -1.38 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2076 | 2024-05-16 | Eternal Fire      | L   | 0.654      | -            | -                | -                | -         |    -0.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2115 | 2024-05-15 | B8                | W   | 0.649      | 0.500        | 0.164 (0.053)    | 0.933 (0.303)    | -         |    11.16 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2300 | 2024-05-09 | Endpoint          | L   | 0.608      | -            | -                | -                | -         |   -13.16 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2457 | 2024-05-01 | Passion UA        | L   | 0.555      | -            | -                | -                | -         |   -10.14 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2473 | 2024-05-01 | fnatic            | L   | 0.553      | -            | -                | -                | -         |    -1.51 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2499 | 2024-04-29 | 3DMAX             | L   | 0.542      | -            | -                | -                | -         |    -0.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2508 | 2024-04-29 | Zero Tenacity     | W   | 0.541      | 0.500        | 0.143 (0.039)    | 1.000 (0.270)    | -         |     7.98 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2544 | 2024-04-27 | Sangal            | W   | 0.528      | 0.500        | 0.219 (0.058)    | 0.865 (0.228)    | -         |     9.43 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2574 | 2024-04-26 | SINNERS           | W   | 0.521      | -            | -                | -                | -         |     9.36 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2603 | 2024-04-25 | ex-Guild Eagles   | W   | 0.514      | -            | -                | -                | -         |     3.88 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2622 | 2024-04-24 | MOUZ NXT          | W   | 0.508      | 0.435        | 0.139 (0.031)    | 0.984 (0.217)    | -         |     7.67 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2674 | 2024-04-21 | Nexus             | W   | 0.488      | -            | -                | -                | -         |     3.79 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2677 | 2024-04-21 | B8                | L   | 0.487      | -            | -                | -                | -         |    -8.05 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2733 | 2024-04-19 | Zero Tenacity     | L   | 0.476      | -            | -                | -                | -         |    -7.62 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2832 | 2024-04-17 | HAVU              | W   | 0.462      | -            | -                | -                | -         |     1.56 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2835 | 2024-04-17 | Permitta          | L   | 0.461      | -            | -                | -                | -         |    -9.29 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2959 | 2024-04-11 | 500               | L   | 0.422      | -            | -                | -                | -         |   -11.73 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2994 | 2024-04-10 | Aurora            | L   | 0.416      | -            | -                | -                | -         |    -0.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3054 | 2024-04-09 | RUSH B            | L   | 0.409      | -            | -                | -                | -         |   -10.11 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3223 | 2024-04-03 | MOUZ NXT          | L   | 0.369      | -            | -                | -                | -         |    -6.90 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3235 | 2024-04-03 | Space             | W   | 0.368      | -            | -                | -                | -         |     1.94 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3271 | 2024-04-02 | AMKAL             | L   | 0.361      | -            | -                | -                | -         |    -5.52 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3278 | 2024-04-02 | Insilio           | L   | 0.361      | -            | -                | -                | -         |    -8.76 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3290 | 2024-04-01 | Metizport         | W   | 0.355      | -            | -                | -                | -         |     2.74 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3456 | 2024-03-21 | FORZE             | W   | 0.281      | -            | -                | -                | -         |     2.09 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3638 | 2024-03-13 | 3DMAX             | W   | 0.228      | 0.500        | 0.509 (0.058)    | -                | -         |     6.89 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3754 | 2024-03-08 | B8                | W   | 0.195      | -            | -                | -                | -         |     2.90 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3810 | 2024-03-06 | Apeks             | W   | 0.182      | -            | -                | -                | -         |     1.39 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3921 | 2024-03-02 | Gaimin Gladiators | L   | 0.154      | -            | -                | -                | -         |    -3.38 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3953 | 2024-02-29 | Monte             | L   | 0.141      | -            | -                | -                | -         |    -2.95 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,577.88)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $6,500.00      | $5,297.05       |
| 2024-05-02 |      0.562 | $500.00        | $280.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
