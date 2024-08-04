### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.7<br />
<br />
Final Rank Value (851.7) = Starting Rank Value (890.9) + Head To Head Adjustments (-39.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.9
- 400 + ( ( 0.240 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 890.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |      162 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      172 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.876 (0.373)    | 0 (0.000) |    19.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      217 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      286 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    17.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      319 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      371 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      490 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      563 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.560 (0.243)    | 0 (0.000) |    15.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      677 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      686 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      737 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -17.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      784 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      845 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      850 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.537 (0.192)    | 0 (0.000) |    17.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      870 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      890 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1071 | 2024-06-14 | GamerLegion      | L   | 0.860      | -            | -                | -                | -         |    -4.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1181 | 2024-06-10 | MOUZ NXT         | W   | 0.833      | 0.450        | 0.139 (0.052)    | 1.000 (0.375)    | 0 (0.000) |    20.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1311 | 2024-06-08 | Entropiq         | W   | 0.818      | -            | -                | -                | 0 (0.000) |     1.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1335 | 2024-06-07 | 9INE             | L   | 0.814      | -            | -                | -                | -         |   -11.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1423 | 2024-06-06 | NAVI Junior      | L   | 0.806      | -            | -                | -                | -         |   -21.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1435 | 2024-06-06 | 5W               | L   | 0.805      | -            | -                | -                | -         |   -11.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1509 | 2024-06-04 | Rhyno            | L   | 0.794      | -            | -                | -                | -         |    -9.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1730 | 2024-05-27 | Rhyno            | L   | 0.739      | -            | -                | -                | -         |    -9.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1782 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.719      | 0.435        | 0.031 (0.010)    | 0.560 (0.175)    | 0 (0.000) |    10.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1836 | 2024-05-22 | Permitta         | L   | 0.707      | -            | -                | -                | -         |   -12.00 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1886 | 2024-05-21 | RUBY             | L   | 0.698      | -            | -                | -                | -         |   -10.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1939 | 2024-05-19 | Sangal           | L   | 0.686      | -            | -                | -                | -         |    -6.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     2004 | 2024-05-17 | Zero Tenacity    | L   | 0.673      | -            | -                | -                | -         |    -6.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2090 | 2024-05-15 | Passion UA       | W   | 0.660      | 0.435        | 0.172 (0.049)    | 1.000 (0.287)    | 0 (0.000) |    12.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2098 | 2024-05-15 | Sashi            | L   | 0.659      | -            | -                | -                | -         |    -3.53 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2154 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.652      | -            | -                | -                | -         |    -9.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2216 | 2024-05-11 | MOUZ NXT         | L   | 0.634      | -            | -                | -                | -         |    -7.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2267 | 2024-05-09 | PARIVISION       | W   | 0.620      | -            | -                | -                | -         |    13.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2349 | 2024-05-05 | SINNERS          | L   | 0.593      | -            | -                | -                | -         |    -6.10 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2370 | 2024-05-04 | Sampi            | W   | 0.585      | 0.435        | 0.027 (0.007)    | 1.000 (0.254)    | -         |     8.95 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2396 | 2024-05-02 | MOUZ NXT         | W   | 0.574      | 0.435        | 0.139 (0.035)    | 1.000 (0.249)    | -         |    12.12 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2408 | 2024-05-02 | Grannys Knockers | W   | 0.572      | -            | -                | -                | -         |     5.43 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2447 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.560      | 0.396        | 0.031 (0.007)    | -                | -         |    10.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2452 | 2024-04-30 | ENCE Academy     | W   | 0.559      | -            | -                | -                | -         |     4.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2467 | 2024-04-29 | Nexus            | W   | 0.554      | -            | -                | -                | -         |     7.22 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2481 | 2024-04-29 | Alliance         | L   | 0.552      | -            | -                | -                | -         |    -9.41 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2591 | 2024-04-24 | SINNERS          | W   | 0.519      | 0.384        | 0.037 (0.007)    | 0.797 (0.159)    | -         |    12.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2823 | 2024-04-17 | EYEBALLERS       | W   | 0.472      | -            | -                | -                | -         |     7.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3538 | 2024-03-15 | ex-sYnck         | W   | 0.253      | -            | -                | -                | -         |     0.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3569 | 2024-03-14 | The Chosen Few   | L   | 0.247      | -            | -                | -                | -         |    -5.89 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3641 | 2024-03-12 | Secret           | W   | 0.232      | -            | -                | -                | -         |     0.90 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3676 | 2024-03-10 | Nemiga           | L   | 0.220      | -            | -                | -                | -         |    -1.18 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3712 | 2024-03-09 | BLEED            | L   | 0.212      | -            | -                | -                | -         |    -2.60 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3744 | 2024-03-07 | kONO             | W   | 0.201      | -            | -                | -                | -         |     2.43 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3780 | 2024-03-06 | V1dar            | W   | 0.193      | -            | -                | -                | -         |     0.71 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3823 | 2024-03-05 | AURA             | W   | 0.186      | -            | -                | -                | -         |     0.59 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3918 | 2024-02-29 | Metizport        | L   | 0.153      | -            | -                | -                | -         |    -2.79 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3975 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.132      | -            | -                | -                | -         |    -1.55 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4353 | 2024-02-09 | 3DMAX            | L   | 0.020      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4359 | 2024-02-09 | fnatic           | L   | 0.019      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4380 | 2024-02-07 | Permitta         | W   | 0.005      | -            | -                | -                | -         |     0.10 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,818.01)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.879 | $2,500.00      | $2,196.99       |
| 2024-05-18 |      0.680 | $500.00        | $340.23         |
| 2024-05-12 |      0.640 | $2,000.00      | $1,280.79       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
