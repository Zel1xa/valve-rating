### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.8<br />
<br />
Final Rank Value (851.8) = Starting Rank Value (890.8) + Head To Head Adjustments (-39.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.8
- 400 + ( ( 0.240 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 890.8


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
|           57 |      163 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      173 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.876 (0.373)    | 0 (0.000) |    19.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      218 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      287 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    17.60 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      320 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      372 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      491 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      564 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.560 (0.243)    | 0 (0.000) |    15.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      678 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      687 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      738 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -17.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      785 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      846 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      851 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.537 (0.192)    | 0 (0.000) |    17.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      871 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      891 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1072 | 2024-06-14 | GamerLegion      | L   | 0.860      | -            | -                | -                | -         |    -4.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1182 | 2024-06-10 | MOUZ NXT         | W   | 0.832      | 0.450        | 0.139 (0.052)    | 1.000 (0.375)    | 0 (0.000) |    20.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1312 | 2024-06-08 | Entropiq         | W   | 0.818      | -            | -                | -                | 0 (0.000) |     1.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1336 | 2024-06-07 | 9INE             | L   | 0.814      | -            | -                | -                | -         |   -11.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1424 | 2024-06-06 | NAVI Junior      | L   | 0.805      | -            | -                | -                | -         |   -21.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1436 | 2024-06-06 | 5W               | L   | 0.805      | -            | -                | -                | -         |   -11.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1510 | 2024-06-04 | Rhyno            | L   | 0.794      | -            | -                | -                | -         |    -9.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1731 | 2024-05-27 | Rhyno            | L   | 0.739      | -            | -                | -                | -         |    -9.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1783 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.719      | 0.435        | 0.031 (0.010)    | 0.560 (0.175)    | 0 (0.000) |    10.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1837 | 2024-05-22 | Permitta         | L   | 0.706      | -            | -                | -                | -         |   -11.99 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1887 | 2024-05-21 | RUBY             | L   | 0.698      | -            | -                | -                | -         |   -10.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1940 | 2024-05-19 | Sangal           | L   | 0.686      | -            | -                | -                | -         |    -6.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     2005 | 2024-05-17 | Zero Tenacity    | L   | 0.673      | -            | -                | -                | -         |    -6.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2091 | 2024-05-15 | Passion UA       | W   | 0.659      | 0.435        | 0.172 (0.049)    | 1.000 (0.287)    | 0 (0.000) |    12.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2099 | 2024-05-15 | Sashi            | L   | 0.658      | -            | -                | -                | -         |    -3.53 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2155 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.652      | -            | -                | -                | -         |    -9.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2217 | 2024-05-11 | MOUZ NXT         | L   | 0.634      | -            | -                | -                | -         |    -7.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2268 | 2024-05-09 | PARIVISION       | W   | 0.620      | -            | -                | -                | -         |    13.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2350 | 2024-05-05 | SINNERS          | L   | 0.592      | -            | -                | -                | -         |    -6.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2371 | 2024-05-04 | Sampi            | W   | 0.585      | 0.435        | 0.027 (0.007)    | 1.000 (0.254)    | -         |     8.94 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2397 | 2024-05-02 | MOUZ NXT         | W   | 0.574      | 0.435        | 0.139 (0.035)    | 1.000 (0.249)    | -         |    12.12 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2409 | 2024-05-02 | Grannys Knockers | W   | 0.572      | -            | -                | -                | -         |     5.43 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2448 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.560      | 0.396        | 0.031 (0.007)    | -                | -         |    10.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2453 | 2024-04-30 | ENCE Academy     | W   | 0.559      | -            | -                | -                | -         |     4.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2468 | 2024-04-29 | Nexus            | W   | 0.553      | -            | -                | -                | -         |     7.22 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2482 | 2024-04-29 | Alliance         | L   | 0.551      | -            | -                | -                | -         |    -9.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2592 | 2024-04-24 | SINNERS          | W   | 0.519      | 0.384        | 0.037 (0.007)    | 0.797 (0.159)    | -         |    12.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2824 | 2024-04-17 | EYEBALLERS       | W   | 0.471      | -            | -                | -                | -         |     7.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3539 | 2024-03-15 | ex-sYnck         | W   | 0.252      | -            | -                | -                | -         |     0.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3570 | 2024-03-14 | The Chosen Few   | L   | 0.247      | -            | -                | -                | -         |    -5.89 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3642 | 2024-03-12 | Secret           | W   | 0.232      | -            | -                | -                | -         |     0.90 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3677 | 2024-03-10 | Nemiga           | L   | 0.220      | -            | -                | -                | -         |    -1.17 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3713 | 2024-03-09 | BLEED            | L   | 0.212      | -            | -                | -                | -         |    -2.58 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3745 | 2024-03-07 | kONO             | W   | 0.200      | -            | -                | -                | -         |     2.43 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3781 | 2024-03-06 | V1dar            | W   | 0.193      | -            | -                | -                | -         |     0.71 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3824 | 2024-03-05 | AURA             | W   | 0.186      | -            | -                | -                | -         |     0.59 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3919 | 2024-02-29 | Metizport        | L   | 0.153      | -            | -                | -                | -         |    -2.78 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3976 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.132      | -            | -                | -                | -         |    -1.55 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4354 | 2024-02-09 | 3DMAX            | L   | 0.020      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4360 | 2024-02-09 | fnatic           | L   | 0.019      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4381 | 2024-02-07 | Permitta         | W   | 0.005      | -            | -                | -                | -         |     0.09 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,816.50)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.878 | $2,500.00      | $2,196.24       |
| 2024-05-18 |      0.680 | $500.00        | $340.08         |
| 2024-05-12 |      0.640 | $2,000.00      | $1,280.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
