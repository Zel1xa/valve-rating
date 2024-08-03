### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  854.7<br />
<br />
Final Rank Value (854.7) = Starting Rank Value (893.7) + Head To Head Adjustments (-38.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.371[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.7
- 400 + ( ( 0.241 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 893.7


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
|           57 |      106 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      116 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.887 (0.378)    | 0 (0.000) |    18.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      160 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      229 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.420 (0.183)    | 0 (0.000) |    18.00 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      262 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.90 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      314 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.94 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      433 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      506 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.580 (0.252)    | 0 (0.000) |    15.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      619 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -11.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      630 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      677 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      724 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      780 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      785 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.553 (0.198)    | 0 (0.000) |    17.10 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      805 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      825 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      985 | 2024-06-14 | GamerLegion      | L   | 0.866      | -            | -                | -                | -         |    -4.43 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1092 | 2024-06-10 | MOUZ NXT         | W   | 0.839      | 0.450        | 0.139 (0.053)    | 1.000 (0.378)    | 0 (0.000) |    20.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1216 | 2024-06-08 | Entropiq         | W   | 0.824      | -            | -                | -                | 0 (0.000) |     1.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1240 | 2024-06-07 | 9INE             | L   | 0.820      | -            | -                | -                | -         |   -11.43 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1328 | 2024-06-06 | NAVI Junior      | L   | 0.812      | -            | -                | -                | -         |   -21.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1340 | 2024-06-06 | 5W               | L   | 0.811      | -            | -                | -                | -         |   -11.41 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1414 | 2024-06-04 | Rhyno            | L   | 0.800      | -            | -                | -                | -         |    -9.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1632 | 2024-05-27 | Rhyno            | L   | 0.745      | -            | -                | -                | -         |    -9.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1683 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.725      | 0.435        | 0.032 (0.010)    | 0.580 (0.183)    | 0 (0.000) |    10.96 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1737 | 2024-05-22 | Permitta         | L   | 0.713      | -            | -                | -                | -         |   -12.16 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1787 | 2024-05-21 | RUBY             | L   | 0.704      | -            | -                | -                | -         |   -10.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1839 | 2024-05-19 | Sangal           | L   | 0.692      | -            | -                | -                | -         |    -6.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1904 | 2024-05-17 | Zero Tenacity    | L   | 0.679      | -            | -                | -                | -         |    -7.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     1990 | 2024-05-15 | Passion UA       | W   | 0.666      | 0.435        | 0.172 (0.050)    | 1.000 (0.289)    | 0 (0.000) |    12.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     1998 | 2024-05-15 | Sashi            | L   | 0.665      | -            | -                | -                | -         |    -3.55 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2054 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.658      | -            | -                | -                | -         |    -9.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2116 | 2024-05-11 | MOUZ NXT         | L   | 0.640      | -            | -                | -                | -         |    -7.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2167 | 2024-05-09 | PARIVISION       | W   | 0.626      | -            | -                | -                | -         |    13.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2248 | 2024-05-05 | SINNERS          | L   | 0.599      | -            | -                | -                | -         |    -7.10 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2269 | 2024-05-04 | Sampi            | W   | 0.591      | 0.435        | 0.028 (0.007)    | 1.000 (0.257)    | -         |     9.04 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2295 | 2024-05-02 | MOUZ NXT         | W   | 0.580      | 0.435        | 0.139 (0.035)    | 1.000 (0.252)    | -         |    12.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2307 | 2024-05-02 | Grannys Knockers | W   | 0.579      | -            | -                | -                | -         |     5.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2346 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.566      | 0.396        | 0.032 (0.007)    | -                | -         |    10.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2351 | 2024-04-30 | ENCE Academy     | W   | 0.565      | -            | -                | -                | -         |     4.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2366 | 2024-04-29 | Nexus            | W   | 0.560      | -            | -                | -                | -         |     7.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2380 | 2024-04-29 | Alliance         | L   | 0.558      | -            | -                | -                | -         |    -9.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2489 | 2024-04-24 | SINNERS          | W   | 0.526      | 0.384        | 0.037 (0.008)    | 0.784 (0.158)    | -         |    12.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2721 | 2024-04-17 | EYEBALLERS       | W   | 0.478      | -            | -                | -                | -         |     7.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3430 | 2024-03-15 | ex-sYnck         | W   | 0.259      | -            | -                | -                | -         |     0.86 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3461 | 2024-03-14 | The Chosen Few   | L   | 0.253      | -            | -                | -                | -         |    -6.06 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3531 | 2024-03-12 | Secret           | W   | 0.238      | -            | -                | -                | -         |     0.92 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3566 | 2024-03-10 | Nemiga           | L   | 0.226      | -            | -                | -                | -         |    -1.34 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3602 | 2024-03-09 | BLEED            | L   | 0.218      | -            | -                | -                | -         |    -2.67 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3634 | 2024-03-07 | kONO             | W   | 0.207      | -            | -                | -                | -         |     2.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3670 | 2024-03-06 | V1dar            | W   | 0.199      | -            | -                | -                | -         |     0.72 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3713 | 2024-03-05 | AURA             | W   | 0.193      | -            | -                | -                | -         |     0.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3808 | 2024-02-29 | Metizport        | L   | 0.159      | -            | -                | -                | -         |    -2.44 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3865 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.138      | -            | -                | -                | -         |    -1.63 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4242 | 2024-02-09 | 3DMAX            | L   | 0.027      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4248 | 2024-02-09 | fnatic           | L   | 0.026      | -            | -                | -                | -         |    -0.05 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4269 | 2024-02-07 | Permitta         | W   | 0.012      | -            | -                | -                | -         |     0.21 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,849.26)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.885 | $2,500.00      | $2,212.62       |
| 2024-05-18 |      0.687 | $500.00        | $343.36         |
| 2024-05-12 |      0.647 | $2,000.00      | $1,293.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
