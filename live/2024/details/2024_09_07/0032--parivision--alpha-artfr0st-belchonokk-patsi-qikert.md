### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [32](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [24]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  1121.8<br />
<br />
Final Rank Value (1121.8) = Starting Rank Value (1094.3) + Head To Head Adjustments (27.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.427[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.189[<sup>2</sup>](#table1)

The average of these factors is 0.355<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.3
- 400 + ( ( 0.355 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 1094.3


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
|           70 |       96 | 2024-09-04 | Monte             | W   | 1.000      | 0.384        | -                | 0.716 (0.275)    | 0 (0.000) |    13.04 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           69 |      254 | 2024-08-29 | AMKAL             | W   | 1.000      | 0.384        | 0.123 (0.047)    | -                | 0 (0.000) |    11.84 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           68 |      366 | 2024-08-27 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |   -25.19 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           67 |      467 | 2024-08-25 | Monte Gen         | L   | 1.000      | -            | -                | -                | -         |   -25.50 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           66 |      527 | 2024-08-23 | GamerLegion       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.66 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           65 |      562 | 2024-08-22 | B8                | W   | 1.000      | 0.143        | 0.176 (0.025)    | -                | 0 (0.000) |    15.57 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           64 |      595 | 2024-08-21 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.34 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           63 |      616 | 2024-08-21 | Enterprise        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.09 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           62 |      657 | 2024-08-20 | 9 Pandas          | W   | 1.000      | 0.500        | 0.059 (0.029)    | 0.757 (0.378)    | 0 (0.000) |    15.79 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           61 |      688 | 2024-08-19 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -4.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           60 |      783 | 2024-08-15 | OG                | L   | 1.000      | -            | -                | -                | -         |   -21.90 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           59 |      788 | 2024-08-15 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           58 |      801 | 2024-08-15 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.45 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           57 |      839 | 2024-08-13 | RUSH B            | W   | 1.000      | -            | -                | -                | -         |     8.49 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           56 |      885 | 2024-08-12 | Monte             | W   | 1.000      | 0.500        | -                | 0.716 (0.358)    | -         |    11.67 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           55 |      971 | 2024-08-09 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -4.20 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |     1050 | 2024-08-07 | SINNERS           | W   | 0.994      | -            | -                | -                | -         |    11.78 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |     1081 | 2024-08-06 | Sangal            | L   | 0.989      | -            | -                | -                | -         |    -6.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |     1095 | 2024-08-06 | Aurora Young Blud | W   | 0.987      | 0.435        | -                | 0.693 (0.298)    | -         |    11.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |     1115 | 2024-08-05 | ENCE              | W   | 0.981      | 0.435        | 0.131 (0.056)    | -                | -         |    21.57 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |     1132 | 2024-08-04 | Betera            | L   | 0.976      | -            | -                | -                | -         |   -28.47 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |     1171 | 2024-08-03 | GUN5              | L   | 0.969      | -            | -                | -                | -         |   -23.53 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |     1186 | 2024-08-03 | CYBERSHOKE        | W   | 0.967      | 0.435        | -                | 0.722 (0.303)    | -         |     8.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |     1197 | 2024-08-02 | TSM               | W   | 0.963      | 0.500        | 0.057 (0.028)    | 0.925 (0.445)    | -         |    11.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |     1238 | 2024-08-01 | 9 Pandas          | W   | 0.956      | 0.500        | 0.059 (0.028)    | 0.757 (0.362)    | -         |    13.28 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |     1353 | 2024-07-30 | Permitta          | W   | 0.940      | -            | -                | -                | -         |     8.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |     1453 | 2024-07-26 | BLEED             | L   | 0.915      | -            | -                | -                | -         |    -9.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1466 | 2024-07-26 | True Rippers      | W   | 0.914      | -            | -                | -                | 1 (0.914) |     2.72 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1498 | 2024-07-25 | ENCE              | L   | 0.908      | -            | -                | -                | -         |    -8.81 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1536 | 2024-07-24 | The MongolZ       | W   | 0.901      | 0.650        | 0.864 (0.506)    | 0.641 (0.376)    | 1 (0.901) |    27.54 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1543 | 2024-07-24 | Aurora            | L   | 0.900      | -            | -                | -                | -         |    -4.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     2218 | 2024-06-14 | Permitta          | L   | 0.634      | -            | -                | -                | -         |   -14.32 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     2319 | 2024-06-10 | RUSH B            | W   | 0.608      | -            | -                | -                | -         |     5.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     2325 | 2024-06-10 | 3DMAX             | L   | 0.608      | -            | -                | -                | -         |    -1.69 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     2331 | 2024-06-10 | SINNERS           | L   | 0.607      | -            | -                | -                | -         |   -10.07 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     2362 | 2024-06-09 | Aurora            | L   | 0.602      | -            | -                | -                | -         |    -3.92 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     2368 | 2024-06-09 | 9 Pandas          | W   | 0.601      | -            | -                | -                | -         |     9.26 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     2379 | 2024-06-09 | Monte             | W   | 0.601      | -            | -                | -                | -         |     6.82 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           32 |     2381 | 2024-06-09 | SAW               | L   | 0.601      | -            | -                | -                | -         |    -2.01 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           31 |     2601 | 2024-06-05 | Aurora            | L   | 0.576      | -            | -                | -                | -         |    -2.91 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           30 |     2648 | 2024-06-04 | Monte             | W   | 0.569      | -            | -                | -                | -         |     6.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           29 |     3053 | 2024-05-20 | Sangal            | L   | 0.468      | -            | -                | -                | -         |    -4.46 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     3132 | 2024-05-17 | Zero Tenacity     | W   | 0.449      | 0.500        | 0.138 (0.031)    | 1.000 (0.225)    | -         |     6.47 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     3163 | 2024-05-16 | Aurora            | L   | 0.443      | -            | -                | -                | -         |    -2.10 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     3179 | 2024-05-16 | Eternal Fire      | L   | 0.441      | -            | -                | -                | -         |    -0.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     3218 | 2024-05-15 | B8                | W   | 0.436      | 0.500        | 0.176 (0.038)    | 1.000 (0.218)    | -         |     6.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     3403 | 2024-05-09 | Endpoint          | L   | 0.395      | -            | -                | -                | -         |    -6.98 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     3560 | 2024-05-01 | Passion UA        | L   | 0.342      | -            | -                | -                | -         |    -6.47 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     3576 | 2024-05-01 | fnatic            | L   | 0.340      | -            | -                | -                | -         |    -2.14 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     3602 | 2024-04-29 | 3DMAX             | L   | 0.329      | -            | -                | -                | -         |    -0.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     3611 | 2024-04-29 | Zero Tenacity     | W   | 0.328      | -            | -                | -                | -         |     4.54 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     3647 | 2024-04-27 | Sangal            | W   | 0.315      | 0.500        | 0.248 (0.039)    | -                | -         |     7.27 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     3677 | 2024-04-26 | SINNERS           | W   | 0.308      | -            | -                | -                | -         |     5.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     3706 | 2024-04-25 | ex-Guild Eagles   | W   | 0.302      | -            | -                | -                | -         |     1.47 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     3725 | 2024-04-24 | MOUZ NXT          | W   | 0.295      | -            | -                | -                | -         |     3.67 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     3777 | 2024-04-21 | Nexus             | W   | 0.275      | -            | -                | -                | -         |     1.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           14 |     3780 | 2024-04-21 | B8                | L   | 0.274      | -            | -                | -                | -         |    -4.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           13 |     3836 | 2024-04-19 | Zero Tenacity     | L   | 0.263      | -            | -                | -                | -         |    -4.55 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           12 |     3935 | 2024-04-17 | HAVU              | W   | 0.249      | -            | -                | -                | -         |     0.43 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           11 |     3938 | 2024-04-17 | Permitta          | L   | 0.248      | -            | -                | -                | -         |    -5.20 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           10 |     4062 | 2024-04-11 | 500               | L   | 0.209      | -            | -                | -                | -         |    -6.01 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|            9 |     4097 | 2024-04-10 | Aurora            | L   | 0.203      | -            | -                | -                | -         |    -0.83 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     4157 | 2024-04-09 | RUSH B            | L   | 0.196      | -            | -                | -                | -         |    -4.85 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     4326 | 2024-04-03 | MOUZ NXT          | L   | 0.156      | -            | -                | -                | -         |    -3.19 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     4338 | 2024-04-03 | Space             | W   | 0.155      | -            | -                | -                | -         |     0.85 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     4374 | 2024-04-02 | AMKAL             | L   | 0.149      | -            | -                | -                | -         |    -2.27 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     4381 | 2024-04-02 | Insilio           | L   | 0.148      | -            | -                | -                | -         |    -3.53 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     4393 | 2024-04-01 | Metizport         | W   | 0.142      | -            | -                | -                | -         |     0.57 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     4559 | 2024-03-21 | FORZE             | W   | 0.068      | -            | -                | -                | -         |     0.34 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     4741 | 2024-03-13 | 3DMAX             | W   | 0.015      | -            | -                | -                | -         |     0.46 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,976.35)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      0.989 | $10,000.00     | $9,888.89       |
| 2024-06-09 |      0.602 | $6,500.00      | $3,913.09       |
| 2024-05-02 |      0.349 | $500.00        | $174.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
