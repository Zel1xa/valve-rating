### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1085.4<br />
<br />
Final Rank Value (1085.4) = Starting Rank Value (1083.8) + Head To Head Adjustments (1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.439[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.215[<sup>2</sup>](#table1)

The average of these factors is 0.334<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1083.8
- 400 + ( ( 0.334 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1083.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      178 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.72 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      340 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.507 (0.253)    | 0 (0.000) |     5.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      615 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      749 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.559 (0.280)    | 0 (0.000) |     9.93 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1015 | 2024-06-16 | 9z              | L   | 0.868      | -            | -                | -                | -         |    -3.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1065 | 2024-06-14 | RED Canids      | W   | 0.857      | 0.548        | 0.077 (0.036)    | 0.757 (0.356)    | 1 (0.857) |    16.30 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1070 | 2024-06-14 | Imperial        | W   | 0.856      | 0.548        | 0.235 (0.110)    | 0.683 (0.320)    | 1 (0.856) |    20.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1236 | 2024-06-09 | Sangal          | L   | 0.821      | -            | -                | -                | -         |    -8.45 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1424 | 2024-06-06 | SINNERS         | W   | 0.801      | 0.500        | 0.037 (0.015)    | 0.794 (0.318)    | 0 (0.000) |    10.96 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1485 | 2024-06-05 | 3DMAX           | W   | 0.794      | 0.500        | 0.508 (0.202)    | 1.000 (0.397)    | 0 (0.000) |    23.45 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1614 | 2024-06-01 | ENCE            | L   | 0.767      | -            | -                | -                | -         |    -3.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1620 | 2024-06-01 | Zero Tenacity   | L   | 0.767      | -            | -                | -                | -         |    -9.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2290 | 2024-05-09 | B8              | L   | 0.612      | -            | -                | -                | -         |    -9.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2453 | 2024-05-01 | Zero Tenacity   | L   | 0.559      | -            | -                | -                | -         |    -8.96 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2769 | 2024-04-18 | ex-Guild Eagles | L   | 0.475      | -            | -                | -                | -         |   -12.04 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2780 | 2024-04-18 | fnatic          | W   | 0.474      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.86 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2854 | 2024-04-16 | BLEED           | L   | 0.461      | -            | -                | -                | -         |    -8.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2985 | 2024-04-10 | RUSH B          | W   | 0.421      | 0.500        | -                | 0.385 (0.081)    | -         |     3.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3040 | 2024-04-09 | Aurora          | W   | 0.415      | 0.500        | 0.422 (0.087)    | 0.788 (0.163)    | -         |    12.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3046 | 2024-04-09 | Apeks           | L   | 0.414      | -            | -                | -                | -         |    -9.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3073 | 2024-04-08 | GUN5            | W   | 0.407      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3074 | 2024-04-08 | fnatic          | L   | 0.407      | -            | -                | -                | -         |    -0.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3177 | 2024-04-04 | NOM             | W   | 0.381      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3211 | 2024-04-03 | 9INE            | W   | 0.375      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3249 | 2024-04-02 | TSM             | W   | 0.368      | -            | -                | -                | -         |     1.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3316 | 2024-03-28 | EYEBALLERS      | L   | 0.334      | -            | -                | -                | -         |    -7.73 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3488 | 2024-03-18 | FURIA           | L   | 0.268      | -            | -                | -                | -         |    -0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3503 | 2024-03-17 | ENCE            | L   | 0.262      | -            | -                | -                | -         |    -0.88 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3519 | 2024-03-17 | SAW             | L   | 0.261      | -            | -                | -                | -         |    -3.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3611 | 2024-03-13 | Sangal          | W   | 0.235      | 0.500        | 0.219 (0.026)    | 0.877 (0.103)    | -         |     4.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3665 | 2024-03-11 | B8              | L   | 0.222      | -            | -                | -                | -         |    -3.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3674 | 2024-03-11 | Apeks           | L   | 0.220      | -            | -                | -                | -         |    -5.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3786 | 2024-03-06 | 9 Pandas        | W   | 0.188      | 0.500        | 0.081 (0.008)    | 0.727 (0.068)    | -         |     2.26 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3822 | 2024-03-05 | FORZE           | W   | 0.182      | -            | -                | -                | -         |     1.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3828 | 2024-03-05 | Nemiga          | W   | 0.182      | 0.143        | 0.316 (0.008)    | -                | -         |     3.56 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3836 | 2024-03-05 | ex-Sprout       | W   | 0.181      | -            | -                | -                | -         |     0.22 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3876 | 2024-03-03 | The Chosen Few  | L   | 0.168      | -            | -                | -                | -         |    -4.82 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3931 | 2024-02-29 | Aurora          | L   | 0.148      | -            | -                | -                | -         |    -0.17 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3935 | 2024-02-29 | HAVU            | W   | 0.147      | -            | -                | -                | -         |     0.49 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3944 | 2024-02-28 | FORZE           | L   | 0.142      | -            | -                | -                | -         |    -3.34 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3948 | 2024-02-28 | kONO            | W   | 0.140      | -            | -                | -                | -         |     0.77 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4239 | 2024-02-16 | fnatic          | W   | 0.059      | -            | -                | -                | 1 (0.059) |     1.75 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4263 | 2024-02-15 | 9 Pandas        | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.63 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4292 | 2024-02-14 | 3DMAX           | W   | 0.048      | -            | -                | -                | 1 (0.048) |     1.46 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4306 | 2024-02-14 | Natus Vincere   | L   | 0.046      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,749.07)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.870 | $7,000.00      | $6,087.41       |
| 2024-06-09 |      0.821 | $12,000.00     | $9,849.17       |
| 2024-03-20 |      0.281 | $10,000.00     | $2,812.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
