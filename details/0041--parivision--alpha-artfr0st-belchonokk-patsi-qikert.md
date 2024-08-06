### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1112.6<br />
<br />
Final Rank Value (1112.6) = Starting Rank Value (1112.0) + Head To Head Adjustments (0.6)<br />

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
|           56 |        5 | 2024-08-06 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.521 (0.227)    | 0 (0.000) |    11.91 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           55 |       23 | 2024-08-05 | ENCE              | W   | 1.000      | 0.435        | 0.173 (0.075)    | -                | 0 (0.000) |    25.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |       37 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       75 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       89 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       99 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | -                | 0.461 (0.230)    | 0 (0.000) |    10.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      140 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.040)    | 0.700 (0.350)    | 0 (0.000) |    13.13 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      255 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.02 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      355 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      368 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.47 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      400 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.55 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      438 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    30.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      445 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.36 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1117 | 2024-06-14 | Permitta          | L   | 0.846      | -            | -                | -                | -         |   -18.71 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1218 | 2024-06-10 | RUSH B            | W   | 0.820      | -            | -                | -                | 0 (0.000) |     7.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1224 | 2024-06-10 | 3DMAX             | L   | 0.819      | -            | -                | -                | -         |    -3.35 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1230 | 2024-06-10 | SINNERS           | L   | 0.819      | -            | -                | -                | -         |   -14.48 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1261 | 2024-06-09 | Aurora            | L   | 0.814      | -            | -                | -                | -         |    -3.26 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1267 | 2024-06-09 | 9 Pandas          | W   | 0.813      | -            | -                | -                | 0 (0.000) |    12.24 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1278 | 2024-06-09 | Monte             | W   | 0.813      | -            | -                | -                | -         |    10.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1280 | 2024-06-09 | SAW               | L   | 0.813      | -            | -                | -                | -         |   -10.09 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1500 | 2024-06-05 | Aurora            | L   | 0.788      | -            | -                | -                | -         |    -2.04 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1547 | 2024-06-04 | Monte             | W   | 0.781      | 0.500        | 0.080 (0.031)    | 0.598 (0.233)    | -         |    10.13 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1952 | 2024-05-20 | Sangal            | L   | 0.680      | -            | -                | -                | -         |    -9.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2031 | 2024-05-17 | Zero Tenacity     | W   | 0.661      | 0.500        | 0.143 (0.047)    | 1.000 (0.331)    | -         |    10.11 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2062 | 2024-05-16 | Aurora            | L   | 0.655      | -            | -                | -                | -         |    -1.37 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2078 | 2024-05-16 | Eternal Fire      | L   | 0.653      | -            | -                | -                | -         |    -0.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2117 | 2024-05-15 | B8                | W   | 0.648      | 0.500        | 0.170 (0.055)    | 0.912 (0.296)    | -         |    11.14 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2302 | 2024-05-09 | Endpoint          | L   | 0.607      | -            | -                | -                | -         |   -13.18 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2459 | 2024-05-01 | Passion UA        | L   | 0.554      | -            | -                | -                | -         |   -10.15 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2475 | 2024-05-01 | fnatic            | L   | 0.552      | -            | -                | -                | -         |    -1.52 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2501 | 2024-04-29 | 3DMAX             | L   | 0.541      | -            | -                | -                | -         |    -0.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2510 | 2024-04-29 | Zero Tenacity     | W   | 0.540      | 0.500        | 0.143 (0.039)    | 1.000 (0.270)    | -         |     7.94 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2546 | 2024-04-27 | Sangal            | W   | 0.527      | 0.500        | 0.219 (0.058)    | 0.846 (0.223)    | -         |     9.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2576 | 2024-04-26 | SINNERS           | W   | 0.520      | -            | -                | -                | -         |     9.32 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2605 | 2024-04-25 | ex-Guild Eagles   | W   | 0.514      | -            | -                | -                | -         |     3.86 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2624 | 2024-04-24 | MOUZ NXT          | W   | 0.507      | 0.435        | 0.139 (0.031)    | 0.962 (0.212)    | -         |     7.62 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2676 | 2024-04-21 | Nexus             | W   | 0.487      | -            | -                | -                | -         |     3.77 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2679 | 2024-04-21 | B8                | L   | 0.486      | -            | -                | -                | -         |    -8.03 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2735 | 2024-04-19 | Zero Tenacity     | L   | 0.475      | -            | -                | -                | -         |    -7.65 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2834 | 2024-04-17 | HAVU              | W   | 0.461      | -            | -                | -                | -         |     1.54 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2837 | 2024-04-17 | Permitta          | L   | 0.460      | -            | -                | -                | -         |    -9.29 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2961 | 2024-04-11 | 500               | L   | 0.421      | -            | -                | -                | -         |   -11.71 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2996 | 2024-04-10 | Aurora            | L   | 0.415      | -            | -                | -                | -         |    -0.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3056 | 2024-04-09 | RUSH B            | L   | 0.408      | -            | -                | -                | -         |   -10.11 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3225 | 2024-04-03 | MOUZ NXT          | L   | 0.368      | -            | -                | -                | -         |    -6.91 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3237 | 2024-04-03 | Space             | W   | 0.367      | -            | -                | -                | -         |     1.91 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3273 | 2024-04-02 | AMKAL             | L   | 0.361      | -            | -                | -                | -         |    -5.54 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3280 | 2024-04-02 | Insilio           | L   | 0.360      | -            | -                | -                | -         |    -8.75 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3292 | 2024-04-01 | Metizport         | W   | 0.354      | -            | -                | -                | -         |     2.71 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3458 | 2024-03-21 | FORZE             | W   | 0.280      | -            | -                | -                | -         |     2.09 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3640 | 2024-03-13 | 3DMAX             | W   | 0.227      | 0.500        | 0.510 (0.058)    | -                | -         |     6.86 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3756 | 2024-03-08 | B8                | W   | 0.194      | -            | -                | -                | -         |     2.90 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3812 | 2024-03-06 | Apeks             | W   | 0.181      | -            | -                | -                | -         |     1.37 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3923 | 2024-03-02 | Gaimin Gladiators | L   | 0.153      | -            | -                | -                | -         |    -3.37 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3955 | 2024-02-29 | Monte             | L   | 0.140      | -            | -                | -                | -         |    -2.94 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,571.40)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $6,500.00      | $5,291.03       |
| 2024-05-02 |      0.561 | $500.00        | $280.37         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
