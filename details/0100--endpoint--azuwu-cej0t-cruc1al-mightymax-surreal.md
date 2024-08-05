### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.5<br />
<br />
Final Rank Value (856.5) = Starting Rank Value (896.1) + Head To Head Adjustments (-39.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.372[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 896.1
- 400 + ( ( 0.241 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 896.1


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
|           57 |       14 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |       24 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.799 (0.340)    | 0 (0.000) |    19.17 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |       69 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -14.00 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      138 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.176)    | 0 (0.000) |    17.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      171 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      223 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      342 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      415 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.564 (0.245)    | 0 (0.000) |    15.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      529 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -12.00 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      538 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      589 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.43 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      636 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      697 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.63 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      702 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.487 (0.174)    | 0 (0.000) |    17.18 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      722 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      742 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      923 | 2024-06-14 | GamerLegion      | L   | 0.885      | -            | -                | -                | -         |    -4.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1033 | 2024-06-10 | MOUZ NXT         | W   | 0.858      | 0.450        | 0.140 (0.054)    | 1.000 (0.386)    | 0 (0.000) |    20.96 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1163 | 2024-06-08 | Entropiq         | W   | 0.844      | -            | -                | -                | 0 (0.000) |     1.89 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1187 | 2024-06-07 | 9INE             | L   | 0.839      | -            | -                | -                | -         |   -11.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1275 | 2024-06-06 | NAVI Junior      | L   | 0.831      | -            | -                | -                | -         |   -22.25 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1287 | 2024-06-06 | 5W               | L   | 0.830      | -            | -                | -                | -         |   -11.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1361 | 2024-06-04 | Rhyno            | L   | 0.819      | -            | -                | -                | -         |    -9.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1582 | 2024-05-27 | Rhyno            | L   | 0.764      | -            | -                | -                | -         |    -9.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1634 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.744      | 0.435        | 0.032 (0.010)    | 0.564 (0.183)    | 0 (0.000) |    11.24 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1688 | 2024-05-22 | Permitta         | L   | 0.732      | -            | -                | -                | -         |   -12.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1738 | 2024-05-21 | RUBY             | L   | 0.724      | -            | -                | -                | -         |   -10.60 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1791 | 2024-05-19 | Sangal           | L   | 0.711      | -            | -                | -                | -         |    -6.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1856 | 2024-05-17 | Zero Tenacity    | L   | 0.698      | -            | -                | -                | -         |    -7.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     1942 | 2024-05-15 | Passion UA       | W   | 0.685      | 0.435        | 0.171 (0.051)    | 1.000 (0.298)    | 0 (0.000) |    13.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     1950 | 2024-05-15 | Sashi            | L   | 0.684      | -            | -                | -                | -         |    -3.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2006 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.677      | -            | -                | -                | -         |    -9.62 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2068 | 2024-05-11 | MOUZ NXT         | L   | 0.659      | -            | -                | -                | -         |    -7.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2119 | 2024-05-09 | PARIVISION       | W   | 0.645      | -            | -                | -                | -         |    13.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2201 | 2024-05-05 | SINNERS          | L   | 0.618      | -            | -                | -                | -         |    -8.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2222 | 2024-05-04 | Sampi            | W   | 0.610      | 0.435        | 0.028 (0.007)    | 1.000 (0.265)    | -         |     9.25 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2248 | 2024-05-02 | MOUZ NXT         | W   | 0.599      | 0.435        | 0.140 (0.036)    | 1.000 (0.260)    | -         |    12.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2260 | 2024-05-02 | Grannys Knockers | W   | 0.598      | -            | -                | -                | -         |     5.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2299 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.585      | 0.396        | 0.032 (0.007)    | -                | -         |    10.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2304 | 2024-04-30 | ENCE Academy     | W   | 0.584      | -            | -                | -                | -         |     4.99 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2319 | 2024-04-29 | Nexus            | W   | 0.579      | -            | -                | -                | -         |     7.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2333 | 2024-04-29 | Alliance         | L   | 0.577      | -            | -                | -                | -         |    -9.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2443 | 2024-04-24 | SINNERS          | W   | 0.545      | 0.384        | 0.038 (0.008)    | 0.721 (0.151)    | -         |    11.99 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2675 | 2024-04-17 | EYEBALLERS       | W   | 0.497      | -            | -                | -                | -         |     7.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3390 | 2024-03-15 | ex-sYnck         | W   | 0.278      | -            | -                | -                | -         |     0.93 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3421 | 2024-03-14 | The Chosen Few   | L   | 0.272      | -            | -                | -                | -         |    -6.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3493 | 2024-03-12 | Secret           | W   | 0.257      | -            | -                | -                | -         |     0.98 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3528 | 2024-03-10 | Nemiga           | L   | 0.245      | -            | -                | -                | -         |    -1.37 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3564 | 2024-03-09 | BLEED            | L   | 0.237      | -            | -                | -                | -         |    -2.83 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3596 | 2024-03-07 | kONO             | W   | 0.226      | -            | -                | -                | -         |     2.72 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3632 | 2024-03-06 | V1dar            | W   | 0.219      | -            | -                | -                | -         |     0.79 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3675 | 2024-03-05 | AURA             | W   | 0.212      | -            | -                | -                | -         |     0.68 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3770 | 2024-02-29 | Metizport        | L   | 0.178      | -            | -                | -                | -         |    -2.70 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3827 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.157      | -            | -                | -                | -         |    -1.82 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4205 | 2024-02-09 | 3DMAX            | L   | 0.046      | -            | -                | -                | -         |    -0.02 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4211 | 2024-02-09 | fnatic           | L   | 0.045      | -            | -                | -                | -         |    -0.03 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4232 | 2024-02-07 | Permitta         | W   | 0.031      | -            | -                | -                | -         |     0.53 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,944.33)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.904 | $2,500.00      | $2,260.15       |
| 2024-05-18 |      0.706 | $500.00        | $352.86         |
| 2024-05-12 |      0.666 | $2,000.00      | $1,331.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
