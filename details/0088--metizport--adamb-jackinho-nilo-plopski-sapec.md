### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  902.0<br />
<br />
Final Rank Value (902.0) = Starting Rank Value (901.5) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.383[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.5
- 400 + ( ( 0.245 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 901.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |       88 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -13.93 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      192 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.65 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |      238 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.30 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      406 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.37 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      424 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.66 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      525 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.80 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      585 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.29 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      704 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    11.61 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |     1766 | 2024-05-23 | Space             | L   | 0.716      | -            | -                | -                | -         |   -14.54 | abdi, adamb, Jackinho, nilo, Plopski  |
|           52 |     1872 | 2024-05-20 | Zero Tenacity     | L   | 0.699      | -            | -                | -                | -         |    -8.10 | adamb, Jackinho, nilo, Plopski, ztr   |
|           51 |     1924 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.685      | 0.500        | 0.223 (0.076)    | 0.553 (0.190)    | 0 (0.000) |    20.87 | adamb, Jackinho, nilo, Plopski, ztr   |
|           50 |     2010 | 2024-05-16 | Rare Atom         | W   | 0.670      | 0.500        | -                | 0.479 (0.161)    | 0 (0.000) |     4.26 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     2196 | 2024-05-11 | BetBoom           | L   | 0.637      | -            | -                | -                | -         |    -1.72 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2210 | 2024-05-10 | EYEBALLERS        | W   | 0.631      | 0.435        | -                | 0.510 (0.140)    | 0 (0.000) |     8.70 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2334 | 2024-05-04 | AMKAL             | L   | 0.590      | -            | -                | -                | -         |    -4.54 | adamb, Jackinho, nilo, susp, ztr      |
|           46 |     2350 | 2024-05-03 | Zero Tenacity     | W   | 0.583      | 0.435        | 0.137 (0.035)    | 1.000 (0.254)    | 0 (0.000) |    12.04 | adamb, Jackinho, nilo, susp, ztr      |
|           45 |     2370 | 2024-05-02 | Sangal            | W   | 0.578      | 0.435        | 0.219 (0.055)    | 0.862 (0.216)    | 0 (0.000) |    13.34 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2530 | 2024-04-25 | Nexus             | L   | 0.532      | -            | -                | -                | -         |   -10.91 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2572 | 2024-04-23 | Alliance          | W   | 0.517      | 0.384        | -                | 0.302 (0.060)    | 0 (0.000) |     6.57 | adamb, Jackinho, nilo, p1ke, susp     |
|           42 |     2682 | 2024-04-19 | FURIA             | L   | 0.491      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, Plopski, susp, ztr   |
|           41 |     2717 | 2024-04-18 | Imperial          | L   | 0.485      | -            | -                | -                | -         |    -1.87 | adamb, Jackinho, Plopski, susp, ztr   |
|           40 |     2997 | 2024-04-09 | ex-Guild Eagles   | L   | 0.424      | -            | -                | -                | -         |    -9.08 | adamb, Jackinho, nilo, susp, ztr      |
|           39 |     3012 | 2024-04-08 | Aurora            | L   | 0.419      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, nilo, susp, ztr      |
|           38 |     3023 | 2024-04-08 | 9 Pandas          | L   | 0.417      | -            | -                | -                | -         |    -5.65 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3050 | 2024-04-07 | EYEBALLERS        | W   | 0.412      | 0.330        | -                | 0.510 (0.069)    | 0 (0.000) |     5.61 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3059 | 2024-04-07 | Johnny Speeds     | W   | 0.410      | 0.330        | 0.122 (0.017)    | 0.901 (0.122)    | -         |    11.25 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3075 | 2024-04-06 | Young Gods        | W   | 0.403      | -            | -                | -                | -         |     2.94 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3129 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.391      | -            | -                | -                | -         |    -0.21 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3158 | 2024-04-03 | Monte             | W   | 0.385      | -            | -                | -                | -         |     7.16 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3167 | 2024-04-03 | FAVBET            | W   | 0.384      | -            | -                | -                | -         |     3.83 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3199 | 2024-04-02 | B8                | W   | 0.378      | 0.143        | 0.165 (0.009)    | -                | -         |     8.52 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3207 | 2024-04-02 | Aurora            | L   | 0.377      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3221 | 2024-04-01 | PARIVISION        | L   | 0.371      | -            | -                | -                | -         |    -2.97 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3289 | 2024-03-27 | Aurora            | L   | 0.339      | -            | -                | -                | -         |    -0.16 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3295 | 2024-03-27 | NAVI Junior       | W   | 0.339      | -            | -                | -                | -         |     2.36 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3498 | 2024-03-15 | kONO              | L   | 0.258      | -            | -                | -                | -         |    -5.35 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3535 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.251      | -            | -                | -                | -         |    -3.41 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3569 | 2024-03-13 | HEROIC            | L   | 0.244      | -            | -                | -                | -         |    -0.21 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3592 | 2024-03-12 | B8                | W   | 0.239      | 0.143        | 0.165 (0.006)    | -                | -         |     5.46 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3600 | 2024-03-12 | Apeks             | W   | 0.238      | -            | -                | -                | -         |     3.71 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3611 | 2024-03-11 | ex-Preasy         | W   | 0.232      | -            | -                | -                | -         |     2.56 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3622 | 2024-03-11 | ENCE              | L   | 0.231      | -            | -                | -                | -         |    -0.31 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3632 | 2024-03-10 | Spirit            | L   | 0.226      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3658 | 2024-03-09 | Monte             | W   | 0.218      | 0.535        | 0.060 (0.007)    | -                | -         |     4.27 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3664 | 2024-03-09 | EYEBALLERS        | L   | 0.218      | -            | -                | -                | -         |    -3.52 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3669 | 2024-03-09 | Lemondogs         | W   | 0.217      | -            | -                | -                | -         |     0.37 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3689 | 2024-03-08 | Secret            | W   | 0.211      | -            | -                | -                | -         |     0.72 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3730 | 2024-03-06 | Falcons           | W   | 0.199      | 0.535        | 0.225 (0.024)    | -                | -         |     5.93 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3811 | 2024-03-03 | The Chosen Few    | W   | 0.179      | -            | -                | -                | -         |     1.22 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3817 | 2024-03-03 | ILIN              | W   | 0.179      | -            | -                | -                | -         |     0.32 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3822 | 2024-03-03 | RUSH B            | W   | 0.178      | -            | -                | -                | -         |     2.36 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3833 | 2024-03-03 | ECLOT             | L   | 0.177      | -            | -                | -                | -         |    -0.82 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3881 | 2024-02-29 | Endpoint          | W   | 0.158      | -            | -                | -                | -         |     2.40 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3916 | 2024-02-27 | ex-Guild Eagles   | L   | 0.145      | -            | -                | -                | -         |    -2.82 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     4288 | 2024-02-11 | Apeks             | W   | 0.039      | -            | -                | -                | -         |     0.62 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     4293 | 2024-02-11 | ex-Sprout         | W   | 0.037      | -            | -                | -                | -         |     0.12 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4300 | 2024-02-10 | FURIA             | W   | 0.032      | -            | -                | -                | -         |     0.99 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4303 | 2024-02-10 | Apeks             | L   | 0.031      | -            | -                | -                | -         |    -0.49 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4305 | 2024-02-10 | FURIA             | W   | 0.031      | -            | -                | -                | -         |     0.96 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4340 | 2024-02-07 | ex-Sprout         | W   | 0.011      | -            | -                | -                | -         |     0.04 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4348 | 2024-02-06 | Into the Breach   | L   | 0.004      | -            | -                | -                | -         |    -0.12 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,079.16)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.645 | $2,000.00      | $1,289.86       |
| 2024-05-04 |      0.591 | $5,000.00      | $2,956.94       |
| 2024-04-20 |      0.499 | $5,000.00      | $2,496.76       |
| 2024-04-07 |      0.412 | $6,110.00      | $2,515.28       |
| 2024-03-10 |      0.226 | $12,500.00     | $2,820.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
