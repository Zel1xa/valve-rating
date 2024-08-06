### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  860.2<br />
<br />
Final Rank Value (860.2) = Starting Rank Value (890.7) + Head To Head Adjustments (-30.5)<br />

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
|           56 |      197 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      207 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.023 (0.010)    | 0.919 (0.392)    | 0 (0.000) |    19.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      252 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      321 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.429 (0.187)    | 0 (0.000) |    17.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      354 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      406 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.63 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      525 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      598 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.537 (0.233)    | 0 (0.000) |    15.55 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      712 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      721 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      772 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.99 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      819 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.00 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      880 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      885 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.523 (0.187)    | 0 (0.000) |    16.96 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      905 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      925 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.97 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1106 | 2024-06-14 | GamerLegion      | L   | 0.847      | -            | -                | -                | -         |    -4.44 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1216 | 2024-06-10 | MOUZ NXT         | W   | 0.820      | 0.450        | 0.139 (0.051)    | 0.962 (0.355)    | 0 (0.000) |    20.02 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1346 | 2024-06-08 | Entropiq         | W   | 0.805      | -            | -                | -                | 0 (0.000) |     1.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1370 | 2024-06-07 | 9INE             | L   | 0.801      | -            | -                | -                | -         |   -11.29 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1458 | 2024-06-06 | NAVI Junior      | L   | 0.793      | -            | -                | -                | -         |   -17.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1470 | 2024-06-06 | 5W               | L   | 0.792      | -            | -                | -                | -         |   -11.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1544 | 2024-06-04 | Rhyno            | L   | 0.781      | -            | -                | -                | -         |    -9.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1765 | 2024-05-27 | Rhyno            | L   | 0.726      | -            | -                | -                | -         |    -9.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1817 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.706      | 0.435        | 0.031 (0.010)    | 0.537 (0.165)    | 0 (0.000) |    10.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1871 | 2024-05-22 | Permitta         | L   | 0.694      | -            | -                | -                | -         |   -11.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1921 | 2024-05-21 | RUBY             | L   | 0.685      | -            | -                | -                | -         |   -10.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1974 | 2024-05-19 | Sangal           | L   | 0.673      | -            | -                | -                | -         |    -6.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2039 | 2024-05-17 | Zero Tenacity    | L   | 0.660      | -            | -                | -                | -         |    -6.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2125 | 2024-05-15 | Passion UA       | W   | 0.647      | 0.435        | 0.173 (0.049)    | 1.000 (0.281)    | 0 (0.000) |    12.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2133 | 2024-05-15 | Sashi            | L   | 0.646      | -            | -                | -                | -         |    -3.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2189 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.639      | -            | -                | -                | -         |    -9.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2251 | 2024-05-11 | MOUZ NXT         | L   | 0.621      | -            | -                | -                | -         |    -6.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2302 | 2024-05-09 | PARIVISION       | W   | 0.607      | 0.435        | -                | 0.590 (0.156)    | -         |    13.18 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2384 | 2024-05-05 | SINNERS          | L   | 0.580      | -            | -                | -                | -         |    -5.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2405 | 2024-05-04 | Sampi            | W   | 0.572      | 0.435        | 0.027 (0.007)    | 1.000 (0.249)    | -         |     8.74 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2431 | 2024-05-02 | MOUZ NXT         | W   | 0.561      | 0.435        | 0.139 (0.034)    | 0.962 (0.235)    | -         |    11.91 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2443 | 2024-05-02 | Grannys Knockers | W   | 0.560      | -            | -                | -                | -         |     5.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2482 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.547      | 0.396        | 0.031 (0.007)    | -                | -         |    10.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2487 | 2024-04-30 | ENCE Academy     | W   | 0.546      | -            | -                | -                | -         |     4.43 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2502 | 2024-04-29 | Nexus            | W   | 0.541      | -            | -                | -                | -         |     7.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2516 | 2024-04-29 | Alliance         | L   | 0.539      | -            | -                | -                | -         |    -9.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2626 | 2024-04-24 | SINNERS          | W   | 0.507      | 0.384        | 0.037 (0.007)    | -                | -         |    12.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2858 | 2024-04-17 | EYEBALLERS       | W   | 0.459      | -            | -                | -                | -         |     7.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3573 | 2024-03-15 | ex-sYnck         | W   | 0.240      | -            | -                | -                | -         |     0.80 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3604 | 2024-03-14 | The Chosen Few   | L   | 0.234      | -            | -                | -                | -         |    -5.59 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3676 | 2024-03-12 | Secret           | W   | 0.219      | -            | -                | -                | -         |     0.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3711 | 2024-03-10 | Nemiga           | L   | 0.207      | -            | -                | -                | -         |    -1.12 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3747 | 2024-03-09 | BLEED            | L   | 0.199      | -            | -                | -                | -         |    -2.46 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3779 | 2024-03-07 | kONO             | W   | 0.188      | -            | -                | -                | -         |     2.31 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3815 | 2024-03-06 | V1dar            | W   | 0.180      | -            | -                | -                | -         |     0.66 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3858 | 2024-03-05 | AURA             | W   | 0.174      | -            | -                | -                | -         |     0.53 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3953 | 2024-02-29 | Metizport        | L   | 0.140      | -            | -                | -                | -         |    -2.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4010 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.119      | -            | -                | -                | -         |    -1.40 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4388 | 2024-02-09 | 3DMAX            | L   | 0.007      | -            | -                | -                | -         |    -0.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4394 | 2024-02-09 | fnatic           | L   | 0.007      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,754.12)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.866 | $2,500.00      | $2,165.05       |
| 2024-05-18 |      0.668 | $500.00        | $333.84         |
| 2024-05-12 |      0.628 | $2,000.00      | $1,255.23       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
