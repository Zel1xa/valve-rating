### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  853.8<br />
<br />
Final Rank Value (853.8) = Starting Rank Value (890.9) + Head To Head Adjustments (-37.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.371[<sup>2</sup>](#table1)
- Opponent Network: 0.249[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.9
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 890.9


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
|           57 |      128 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      138 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.876 (0.373)    | 0 (0.000) |    19.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      183 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      252 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    17.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      284 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.82 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      337 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      456 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      529 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.561 (0.244)    | 0 (0.000) |    15.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      643 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -11.47 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      653 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      704 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      750 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.03 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      810 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      815 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.535 (0.192)    | 0 (0.000) |    17.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      835 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      855 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1036 | 2024-06-14 | GamerLegion      | L   | 0.864      | -            | -                | -                | -         |    -4.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1146 | 2024-06-10 | MOUZ NXT         | W   | 0.837      | 0.450        | 0.139 (0.052)    | 1.000 (0.377)    | 0 (0.000) |    20.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1276 | 2024-06-08 | Entropiq         | W   | 0.823      | -            | -                | -                | 0 (0.000) |     1.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1300 | 2024-06-07 | 9INE             | L   | 0.819      | -            | -                | -                | -         |   -11.41 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1388 | 2024-06-06 | NAVI Junior      | L   | 0.810      | -            | -                | -                | -         |   -21.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1400 | 2024-06-06 | 5W               | L   | 0.809      | -            | -                | -                | -         |   -11.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1474 | 2024-06-04 | Rhyno            | L   | 0.799      | -            | -                | -                | -         |    -9.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1695 | 2024-05-27 | Rhyno            | L   | 0.744      | -            | -                | -                | -         |    -9.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1747 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.724      | 0.435        | 0.032 (0.010)    | 0.561 (0.176)    | 0 (0.000) |    10.97 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1801 | 2024-05-22 | Permitta         | L   | 0.711      | -            | -                | -                | -         |   -12.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1851 | 2024-05-21 | RUBY             | L   | 0.703      | -            | -                | -                | -         |   -10.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1904 | 2024-05-19 | Sangal           | L   | 0.691      | -            | -                | -                | -         |    -6.44 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1969 | 2024-05-17 | Zero Tenacity    | L   | 0.677      | -            | -                | -                | -         |    -6.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2055 | 2024-05-15 | Passion UA       | W   | 0.664      | 0.435        | 0.172 (0.050)    | 1.000 (0.289)    | 0 (0.000) |    12.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2063 | 2024-05-15 | Sashi            | L   | 0.663      | -            | -                | -                | -         |    -3.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2119 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.657      | -            | -                | -                | -         |    -9.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2181 | 2024-05-11 | MOUZ NXT         | L   | 0.639      | -            | -                | -                | -         |    -7.15 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2232 | 2024-05-09 | PARIVISION       | W   | 0.624      | -            | -                | -                | -         |    13.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2314 | 2024-05-05 | SINNERS          | L   | 0.597      | -            | -                | -                | -         |    -7.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2335 | 2024-05-04 | Sampi            | W   | 0.589      | 0.435        | 0.027 (0.007)    | 1.000 (0.256)    | -         |     9.01 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2361 | 2024-05-02 | MOUZ NXT         | W   | 0.579      | 0.435        | 0.139 (0.035)    | 1.000 (0.251)    | -         |    12.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2373 | 2024-05-02 | Grannys Knockers | W   | 0.577      | -            | -                | -                | -         |     5.47 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2412 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.564      | 0.396        | 0.032 (0.007)    | -                | -         |    10.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2417 | 2024-04-30 | ENCE Academy     | W   | 0.564      | -            | -                | -                | -         |     4.60 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2432 | 2024-04-29 | Nexus            | W   | 0.558      | -            | -                | -                | -         |     7.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2446 | 2024-04-29 | Alliance         | L   | 0.556      | -            | -                | -                | -         |    -9.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2555 | 2024-04-24 | SINNERS          | W   | 0.524      | 0.384        | 0.037 (0.008)    | 0.758 (0.153)    | -         |    12.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2787 | 2024-04-17 | EYEBALLERS       | W   | 0.476      | -            | -                | -                | -         |     7.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3502 | 2024-03-15 | ex-sYnck         | W   | 0.257      | -            | -                | -                | -         |     0.87 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3533 | 2024-03-14 | The Chosen Few   | L   | 0.252      | -            | -                | -                | -         |    -6.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3604 | 2024-03-12 | Secret           | W   | 0.236      | -            | -                | -                | -         |     0.92 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3639 | 2024-03-10 | Nemiga           | L   | 0.225      | -            | -                | -                | -         |    -1.32 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3675 | 2024-03-09 | BLEED            | L   | 0.216      | -            | -                | -                | -         |    -2.64 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3707 | 2024-03-07 | kONO             | W   | 0.205      | -            | -                | -                | -         |     2.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3743 | 2024-03-06 | V1dar            | W   | 0.198      | -            | -                | -                | -         |     0.72 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3786 | 2024-03-05 | AURA             | W   | 0.191      | -            | -                | -                | -         |     0.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3881 | 2024-02-29 | Metizport        | L   | 0.158      | -            | -                | -                | -         |    -2.40 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3938 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.136      | -            | -                | -                | -         |    -1.60 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4315 | 2024-02-09 | 3DMAX            | L   | 0.025      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4321 | 2024-02-09 | fnatic           | L   | 0.024      | -            | -                | -                | -         |    -0.02 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4342 | 2024-02-07 | Permitta         | W   | 0.010      | -            | -                | -                | -         |     0.18 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,840.69)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.883 | $2,500.00      | $2,208.33       |
| 2024-05-18 |      0.685 | $500.00        | $342.50         |
| 2024-05-12 |      0.645 | $2,000.00      | $1,289.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
