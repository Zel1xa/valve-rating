### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1112.0<br />
<br />
Final Rank Value (1112.0) = Starting Rank Value (1112.0) + Head To Head Adjustments (-0.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.509[<sup>2</sup>](#table1)
- Opponent Network: 0.282[<sup>2</sup>](#table1)
- LAN Wins: 0.231[<sup>2</sup>](#table1)

The average of these factors is 0.346<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1112.0
- 400 + ( ( 0.346 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1112.0


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
|           56 |        2 | 2024-08-06 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.521 (0.226)    | 0 (0.000) |    11.27 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           55 |       20 | 2024-08-05 | ENCE              | W   | 1.000      | 0.435        | 0.173 (0.075)    | -                | 0 (0.000) |    25.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |       35 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       75 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       90 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |      101 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | -                | 0.461 (0.230)    | 0 (0.000) |    10.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      142 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.040)    | 0.700 (0.350)    | 0 (0.000) |    13.13 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      257 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.98 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      357 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.69 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      370 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.48 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      402 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.55 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      440 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    30.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      447 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.35 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1119 | 2024-06-14 | Permitta          | L   | 0.847      | -            | -                | -                | -         |   -18.81 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1220 | 2024-06-10 | RUSH B            | W   | 0.821      | -            | -                | -                | 0 (0.000) |     7.96 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1226 | 2024-06-10 | 3DMAX             | L   | 0.820      | -            | -                | -                | -         |    -3.36 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1232 | 2024-06-10 | SINNERS           | L   | 0.820      | -            | -                | -                | -         |   -14.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1263 | 2024-06-09 | Aurora            | L   | 0.814      | -            | -                | -                | -         |    -3.25 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1269 | 2024-06-09 | 9 Pandas          | W   | 0.814      | -            | -                | -                | 0 (0.000) |    12.25 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1280 | 2024-06-09 | Monte             | W   | 0.813      | -            | -                | -                | -         |    10.07 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1282 | 2024-06-09 | SAW               | L   | 0.813      | -            | -                | -                | -         |   -10.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1502 | 2024-06-05 | Aurora            | L   | 0.788      | -            | -                | -                | -         |    -2.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1549 | 2024-06-04 | Monte             | W   | 0.782      | 0.500        | 0.080 (0.031)    | 0.598 (0.234)    | -         |    10.15 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1954 | 2024-05-20 | Sangal            | L   | 0.680      | -            | -                | -                | -         |    -9.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2033 | 2024-05-17 | Zero Tenacity     | W   | 0.662      | 0.500        | 0.143 (0.047)    | 1.000 (0.331)    | -         |    10.12 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2064 | 2024-05-16 | Aurora            | L   | 0.656      | -            | -                | -                | -         |    -1.37 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2080 | 2024-05-16 | Eternal Fire      | L   | 0.654      | -            | -                | -                | -         |    -0.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2119 | 2024-05-15 | B8                | W   | 0.649      | 0.500        | 0.170 (0.055)    | 0.912 (0.296)    | -         |    11.15 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2304 | 2024-05-09 | Endpoint          | L   | 0.608      | -            | -                | -                | -         |   -13.19 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2461 | 2024-05-01 | Passion UA        | L   | 0.554      | -            | -                | -                | -         |   -10.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2477 | 2024-05-01 | fnatic            | L   | 0.552      | -            | -                | -                | -         |    -1.52 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2503 | 2024-04-29 | 3DMAX             | L   | 0.542      | -            | -                | -                | -         |    -0.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2512 | 2024-04-29 | Zero Tenacity     | W   | 0.540      | 0.500        | 0.143 (0.039)    | 1.000 (0.270)    | -         |     7.95 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2548 | 2024-04-27 | Sangal            | W   | 0.528      | 0.500        | 0.219 (0.058)    | 0.846 (0.223)    | -         |     9.38 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2578 | 2024-04-26 | SINNERS           | W   | 0.521      | -            | -                | -                | -         |     9.34 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2607 | 2024-04-25 | ex-Guild Eagles   | W   | 0.514      | -            | -                | -                | -         |     3.86 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2626 | 2024-04-24 | MOUZ NXT          | W   | 0.507      | 0.435        | 0.139 (0.031)    | 0.962 (0.212)    | -         |     7.63 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2678 | 2024-04-21 | Nexus             | W   | 0.488      | -            | -                | -                | -         |     3.77 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2681 | 2024-04-21 | B8                | L   | 0.487      | -            | -                | -                | -         |    -8.04 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2737 | 2024-04-19 | Zero Tenacity     | L   | 0.475      | -            | -                | -                | -         |    -7.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2836 | 2024-04-17 | HAVU              | W   | 0.462      | -            | -                | -                | -         |     1.55 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2839 | 2024-04-17 | Permitta          | L   | 0.461      | -            | -                | -                | -         |    -9.31 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2963 | 2024-04-11 | 500               | L   | 0.421      | -            | -                | -                | -         |   -11.73 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2998 | 2024-04-10 | Aurora            | L   | 0.415      | -            | -                | -                | -         |    -0.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3058 | 2024-04-09 | RUSH B            | L   | 0.409      | -            | -                | -                | -         |   -10.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3227 | 2024-04-03 | MOUZ NXT          | L   | 0.369      | -            | -                | -                | -         |    -6.92 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3239 | 2024-04-03 | Space             | W   | 0.367      | -            | -                | -                | -         |     1.92 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3275 | 2024-04-02 | AMKAL             | L   | 0.361      | -            | -                | -                | -         |    -5.55 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3282 | 2024-04-02 | Insilio           | L   | 0.361      | -            | -                | -                | -         |    -8.77 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3294 | 2024-04-01 | Metizport         | W   | 0.355      | -            | -                | -                | -         |     2.72 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3460 | 2024-03-21 | FORZE             | W   | 0.281      | -            | -                | -                | -         |     2.08 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3642 | 2024-03-13 | 3DMAX             | W   | 0.228      | 0.500        | 0.510 (0.058)    | -                | -         |     6.88 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3758 | 2024-03-08 | B8                | W   | 0.195      | -            | -                | -                | -         |     2.91 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3814 | 2024-03-06 | Apeks             | W   | 0.181      | -            | -                | -                | -         |     1.38 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3925 | 2024-03-02 | Gaimin Gladiators | L   | 0.154      | -            | -                | -                | -         |    -3.38 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3957 | 2024-02-29 | Monte             | L   | 0.141      | -            | -                | -                | -         |    -2.95 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,575.94)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $6,500.00      | $5,295.24       |
| 2024-05-02 |      0.561 | $500.00        | $280.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
