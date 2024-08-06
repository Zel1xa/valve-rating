### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  858.4<br />
<br />
Final Rank Value (858.4) = Starting Rank Value (890.7) + Head To Head Adjustments (-32.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.7
- 400 + ( ( 0.239 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 890.7


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
|           56 |      199 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      209 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.023 (0.010)    | 0.919 (0.392)    | 0 (0.000) |    19.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      254 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      323 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.429 (0.187)    | 0 (0.000) |    17.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      356 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      408 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.55 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      527 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      600 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.537 (0.233)    | 0 (0.000) |    15.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      714 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      723 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      774 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.68 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      821 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      882 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      887 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.523 (0.187)    | 0 (0.000) |    17.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      907 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      927 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1108 | 2024-06-14 | GamerLegion      | L   | 0.848      | -            | -                | -                | -         |    -4.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1218 | 2024-06-10 | MOUZ NXT         | W   | 0.821      | 0.450        | 0.139 (0.051)    | 0.962 (0.355)    | 0 (0.000) |    20.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1348 | 2024-06-08 | Entropiq         | W   | 0.806      | -            | -                | -                | 0 (0.000) |     1.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1372 | 2024-06-07 | 9INE             | L   | 0.802      | -            | -                | -                | -         |   -11.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1460 | 2024-06-06 | NAVI Junior      | L   | 0.794      | -            | -                | -                | -         |   -21.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1472 | 2024-06-06 | 5W               | L   | 0.793      | -            | -                | -                | -         |   -11.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1546 | 2024-06-04 | Rhyno            | L   | 0.782      | -            | -                | -                | -         |    -9.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1767 | 2024-05-27 | Rhyno            | L   | 0.727      | -            | -                | -                | -         |    -9.25 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1819 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.707      | 0.435        | 0.031 (0.010)    | 0.537 (0.165)    | 0 (0.000) |    10.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1873 | 2024-05-22 | Permitta         | L   | 0.694      | -            | -                | -                | -         |   -11.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1923 | 2024-05-21 | RUBY             | L   | 0.686      | -            | -                | -                | -         |   -10.18 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1976 | 2024-05-19 | Sangal           | L   | 0.674      | -            | -                | -                | -         |    -6.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2041 | 2024-05-17 | Zero Tenacity    | L   | 0.661      | -            | -                | -                | -         |    -6.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2127 | 2024-05-15 | Passion UA       | W   | 0.648      | 0.435        | 0.173 (0.049)    | 1.000 (0.281)    | 0 (0.000) |    12.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2135 | 2024-05-15 | Sashi            | L   | 0.646      | -            | -                | -                | -         |    -3.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2191 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.640      | -            | -                | -                | -         |    -9.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2253 | 2024-05-11 | MOUZ NXT         | L   | 0.622      | -            | -                | -                | -         |    -6.89 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2304 | 2024-05-09 | PARIVISION       | W   | 0.608      | 0.435        | -                | 0.590 (0.156)    | -         |    13.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2386 | 2024-05-05 | SINNERS          | L   | 0.581      | -            | -                | -                | -         |    -5.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2407 | 2024-05-04 | Sampi            | W   | 0.573      | 0.435        | 0.027 (0.007)    | 1.000 (0.249)    | -         |     8.75 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2433 | 2024-05-02 | MOUZ NXT         | W   | 0.562      | 0.435        | 0.139 (0.034)    | 0.962 (0.235)    | -         |    11.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2445 | 2024-05-02 | Grannys Knockers | W   | 0.560      | -            | -                | -                | -         |     5.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2484 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.548      | 0.396        | 0.031 (0.007)    | -                | -         |    10.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2489 | 2024-04-30 | ENCE Academy     | W   | 0.547      | -            | -                | -                | -         |     4.44 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2504 | 2024-04-29 | Nexus            | W   | 0.541      | -            | -                | -                | -         |     7.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2518 | 2024-04-29 | Alliance         | L   | 0.539      | -            | -                | -                | -         |    -9.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2628 | 2024-04-24 | SINNERS          | W   | 0.507      | 0.384        | 0.037 (0.007)    | -                | -         |    12.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2860 | 2024-04-17 | EYEBALLERS       | W   | 0.459      | -            | -                | -                | -         |     7.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3575 | 2024-03-15 | ex-sYnck         | W   | 0.241      | -            | -                | -                | -         |     0.80 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3606 | 2024-03-14 | The Chosen Few   | L   | 0.235      | -            | -                | -                | -         |    -5.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3678 | 2024-03-12 | Secret           | W   | 0.220      | -            | -                | -                | -         |     0.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3713 | 2024-03-10 | Nemiga           | L   | 0.208      | -            | -                | -                | -         |    -1.13 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3749 | 2024-03-09 | BLEED            | L   | 0.200      | -            | -                | -                | -         |    -2.47 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3781 | 2024-03-07 | kONO             | W   | 0.189      | -            | -                | -                | -         |     2.31 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3817 | 2024-03-06 | V1dar            | W   | 0.181      | -            | -                | -                | -         |     0.66 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3860 | 2024-03-05 | AURA             | W   | 0.174      | -            | -                | -                | -         |     0.54 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3955 | 2024-02-29 | Metizport        | L   | 0.141      | -            | -                | -                | -         |    -2.15 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4012 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.120      | -            | -                | -                | -         |    -1.41 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4390 | 2024-02-09 | 3DMAX            | L   | 0.008      | -            | -                | -                | -         |    -0.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4396 | 2024-02-09 | fnatic           | L   | 0.007      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,757.36)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.867 | $2,500.00      | $2,166.67       |
| 2024-05-18 |      0.668 | $500.00        | $334.17         |
| 2024-05-12 |      0.628 | $2,000.00      | $1,256.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
