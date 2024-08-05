### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.5<br />
<br />
Final Rank Value (851.5) = Starting Rank Value (890.6) + Head To Head Adjustments (-39.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.6
- 400 + ( ( 0.240 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 890.6


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
|           57 |      167 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      177 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.876 (0.373)    | 0 (0.000) |    19.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      222 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      291 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    17.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      324 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      376 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      495 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      568 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.560 (0.243)    | 0 (0.000) |    15.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      682 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      691 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      742 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -17.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      789 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      850 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      855 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.539 (0.193)    | 0 (0.000) |    17.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      875 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      895 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1076 | 2024-06-14 | GamerLegion      | L   | 0.857      | -            | -                | -                | -         |    -4.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1186 | 2024-06-10 | MOUZ NXT         | W   | 0.830      | 0.450        | 0.139 (0.052)    | 1.000 (0.374)    | 0 (0.000) |    20.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1316 | 2024-06-08 | Entropiq         | W   | 0.816      | -            | -                | -                | 0 (0.000) |     1.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1340 | 2024-06-07 | 9INE             | L   | 0.811      | -            | -                | -                | -         |   -11.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1428 | 2024-06-06 | NAVI Junior      | L   | 0.803      | -            | -                | -                | -         |   -21.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1440 | 2024-06-06 | 5W               | L   | 0.802      | -            | -                | -                | -         |   -11.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1514 | 2024-06-04 | Rhyno            | L   | 0.791      | -            | -                | -                | -         |    -9.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1735 | 2024-05-27 | Rhyno            | L   | 0.736      | -            | -                | -                | -         |    -9.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1787 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.716      | 0.435        | 0.031 (0.010)    | 0.560 (0.174)    | 0 (0.000) |    10.89 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1841 | 2024-05-22 | Permitta         | L   | 0.704      | -            | -                | -                | -         |   -11.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1891 | 2024-05-21 | RUBY             | L   | 0.696      | -            | -                | -                | -         |   -10.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1944 | 2024-05-19 | Sangal           | L   | 0.683      | -            | -                | -                | -         |    -6.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     2009 | 2024-05-17 | Zero Tenacity    | L   | 0.670      | -            | -                | -                | -         |    -6.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2095 | 2024-05-15 | Passion UA       | W   | 0.657      | 0.435        | 0.172 (0.049)    | 1.000 (0.286)    | 0 (0.000) |    12.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2103 | 2024-05-15 | Sashi            | L   | 0.656      | -            | -                | -                | -         |    -3.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2159 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.649      | -            | -                | -                | -         |    -9.24 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2221 | 2024-05-11 | MOUZ NXT         | L   | 0.631      | -            | -                | -                | -         |    -7.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2272 | 2024-05-09 | PARIVISION       | W   | 0.617      | -            | -                | -                | -         |    13.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2354 | 2024-05-05 | SINNERS          | L   | 0.590      | -            | -                | -                | -         |    -6.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2375 | 2024-05-04 | Sampi            | W   | 0.582      | 0.435        | 0.027 (0.007)    | 1.000 (0.253)    | -         |     8.91 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2401 | 2024-05-02 | MOUZ NXT         | W   | 0.571      | 0.435        | 0.139 (0.034)    | 1.000 (0.248)    | -         |    12.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2413 | 2024-05-02 | Grannys Knockers | W   | 0.570      | -            | -                | -                | -         |     5.41 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2452 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.557      | 0.396        | 0.031 (0.007)    | -                | -         |    10.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2457 | 2024-04-30 | ENCE Academy     | W   | 0.557      | -            | -                | -                | -         |     4.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2472 | 2024-04-29 | Nexus            | W   | 0.551      | -            | -                | -                | -         |     7.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2486 | 2024-04-29 | Alliance         | L   | 0.549      | -            | -                | -                | -         |    -9.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2596 | 2024-04-24 | SINNERS          | W   | 0.517      | 0.384        | 0.037 (0.007)    | 0.797 (0.158)    | -         |    12.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2828 | 2024-04-17 | EYEBALLERS       | W   | 0.469      | -            | -                | -                | -         |     7.47 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3543 | 2024-03-15 | ex-sYnck         | W   | 0.250      | -            | -                | -                | -         |     0.84 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3574 | 2024-03-14 | The Chosen Few   | L   | 0.244      | -            | -                | -                | -         |    -5.83 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3646 | 2024-03-12 | Secret           | W   | 0.229      | -            | -                | -                | -         |     0.89 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3681 | 2024-03-10 | Nemiga           | L   | 0.217      | -            | -                | -                | -         |    -1.16 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3717 | 2024-03-09 | BLEED            | L   | 0.209      | -            | -                | -                | -         |    -2.56 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3749 | 2024-03-07 | kONO             | W   | 0.198      | -            | -                | -                | -         |     2.40 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3785 | 2024-03-06 | V1dar            | W   | 0.191      | -            | -                | -                | -         |     0.70 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3828 | 2024-03-05 | AURA             | W   | 0.184      | -            | -                | -                | -         |     0.58 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3923 | 2024-02-29 | Metizport        | L   | 0.150      | -            | -                | -                | -         |    -2.74 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3980 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.129      | -            | -                | -                | -         |    -1.52 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4358 | 2024-02-09 | 3DMAX            | L   | 0.018      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4364 | 2024-02-09 | fnatic           | L   | 0.017      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4385 | 2024-02-07 | Permitta         | W   | 0.003      | -            | -                | -                | -         |     0.05 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,804.58)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.876 | $2,500.00      | $2,190.28       |
| 2024-05-18 |      0.678 | $500.00        | $338.89         |
| 2024-05-12 |      0.638 | $2,000.00      | $1,275.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
