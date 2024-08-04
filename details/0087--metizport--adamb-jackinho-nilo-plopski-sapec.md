### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  901.2<br />
<br />
Final Rank Value (901.2) = Starting Rank Value (901.0) + Head To Head Adjustments (0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.383[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.0
- 400 + ( ( 0.245 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 901.0


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
|           61 |       91 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -13.92 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      195 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.66 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |      241 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.29 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      409 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.34 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      427 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.63 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      528 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.83 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      588 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.27 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      707 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    11.64 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |     1770 | 2024-05-23 | Space             | L   | 0.713      | -            | -                | -                | -         |   -14.46 | abdi, adamb, Jackinho, nilo, Plopski  |
|           52 |     1876 | 2024-05-20 | Zero Tenacity     | L   | 0.696      | -            | -                | -                | -         |    -8.04 | adamb, Jackinho, nilo, Plopski, ztr   |
|           51 |     1928 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.682      | 0.500        | 0.222 (0.076)    | 0.553 (0.189)    | 0 (0.000) |    20.78 | adamb, Jackinho, nilo, Plopski, ztr   |
|           50 |     2014 | 2024-05-16 | Rare Atom         | W   | 0.667      | 0.500        | -                | 0.480 (0.160)    | 0 (0.000) |     4.25 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     2200 | 2024-05-11 | BetBoom           | L   | 0.634      | -            | -                | -                | -         |    -1.71 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2214 | 2024-05-10 | EYEBALLERS        | W   | 0.628      | 0.435        | -                | 0.510 (0.139)    | 0 (0.000) |     8.67 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2338 | 2024-05-04 | AMKAL             | L   | 0.587      | -            | -                | -                | -         |    -4.51 | adamb, Jackinho, nilo, susp, ztr      |
|           46 |     2354 | 2024-05-03 | Zero Tenacity     | W   | 0.580      | 0.435        | 0.137 (0.035)    | 1.000 (0.252)    | 0 (0.000) |    12.01 | adamb, Jackinho, nilo, susp, ztr      |
|           45 |     2374 | 2024-05-02 | Sangal            | W   | 0.574      | 0.435        | 0.219 (0.055)    | 0.862 (0.215)    | 0 (0.000) |    13.29 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2535 | 2024-04-25 | Nexus             | L   | 0.529      | -            | -                | -                | -         |   -10.83 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2577 | 2024-04-23 | Alliance          | W   | 0.514      | 0.384        | -                | 0.300 (0.059)    | 0 (0.000) |     6.54 | adamb, Jackinho, nilo, p1ke, susp     |
|           42 |     2687 | 2024-04-19 | FURIA             | L   | 0.488      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, Plopski, susp, ztr   |
|           41 |     2722 | 2024-04-18 | Imperial          | L   | 0.482      | -            | -                | -                | -         |    -1.87 | adamb, Jackinho, Plopski, susp, ztr   |
|           40 |     3002 | 2024-04-09 | ex-Guild Eagles   | L   | 0.421      | -            | -                | -                | -         |    -9.01 | adamb, Jackinho, nilo, susp, ztr      |
|           39 |     3017 | 2024-04-08 | Aurora            | L   | 0.416      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, nilo, susp, ztr      |
|           38 |     3028 | 2024-04-08 | 9 Pandas          | L   | 0.414      | -            | -                | -                | -         |    -5.62 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3055 | 2024-04-07 | EYEBALLERS        | W   | 0.409      | 0.330        | -                | 0.510 (0.069)    | 0 (0.000) |     5.58 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3064 | 2024-04-07 | Johnny Speeds     | W   | 0.407      | 0.330        | 0.122 (0.016)    | 0.901 (0.121)    | -         |    11.18 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3080 | 2024-04-06 | Young Gods        | W   | 0.400      | -            | -                | -                | -         |     2.94 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3134 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.388      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3163 | 2024-04-03 | Monte             | W   | 0.382      | -            | -                | -                | -         |     7.09 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3172 | 2024-04-03 | FAVBET            | W   | 0.381      | -            | -                | -                | -         |     3.81 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3204 | 2024-04-02 | B8                | W   | 0.375      | 0.143        | 0.165 (0.009)    | -                | -         |     8.46 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3212 | 2024-04-02 | Aurora            | L   | 0.374      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3226 | 2024-04-01 | PARIVISION        | L   | 0.368      | -            | -                | -                | -         |    -2.94 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3294 | 2024-03-27 | Aurora            | L   | 0.336      | -            | -                | -                | -         |    -0.16 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3300 | 2024-03-27 | NAVI Junior       | W   | 0.336      | -            | -                | -                | -         |     2.34 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3503 | 2024-03-15 | kONO              | L   | 0.255      | -            | -                | -                | -         |    -5.28 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3540 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.248      | -            | -                | -                | -         |    -3.36 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3575 | 2024-03-13 | HEROIC            | L   | 0.241      | -            | -                | -                | -         |    -0.21 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3598 | 2024-03-12 | B8                | W   | 0.236      | 0.143        | 0.165 (0.006)    | -                | -         |     5.39 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3606 | 2024-03-12 | Apeks             | W   | 0.235      | -            | -                | -                | -         |     3.66 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3617 | 2024-03-11 | ex-Preasy         | W   | 0.229      | -            | -                | -                | -         |     2.52 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3628 | 2024-03-11 | ENCE              | L   | 0.228      | -            | -                | -                | -         |    -0.31 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3638 | 2024-03-10 | Spirit            | L   | 0.223      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3664 | 2024-03-09 | Monte             | W   | 0.215      | 0.535        | 0.059 (0.007)    | -                | -         |     4.21 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3670 | 2024-03-09 | EYEBALLERS        | L   | 0.215      | -            | -                | -                | -         |    -3.47 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3675 | 2024-03-09 | Lemondogs         | W   | 0.214      | -            | -                | -                | -         |     0.36 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3695 | 2024-03-08 | Secret            | W   | 0.207      | -            | -                | -                | -         |     0.72 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3736 | 2024-03-06 | Falcons           | W   | 0.196      | 0.535        | 0.224 (0.023)    | -                | -         |     5.84 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3817 | 2024-03-03 | The Chosen Few    | W   | 0.176      | -            | -                | -                | -         |     1.20 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3823 | 2024-03-03 | ILIN              | W   | 0.176      | -            | -                | -                | -         |     0.32 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3828 | 2024-03-03 | RUSH B            | W   | 0.175      | -            | -                | -                | -         |     2.32 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3839 | 2024-03-03 | ECLOT             | L   | 0.174      | -            | -                | -                | -         |    -0.80 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3887 | 2024-02-29 | Endpoint          | W   | 0.154      | -            | -                | -                | -         |     2.35 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3922 | 2024-02-27 | ex-Guild Eagles   | L   | 0.142      | -            | -                | -                | -         |    -2.77 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     4295 | 2024-02-11 | Apeks             | W   | 0.036      | -            | -                | -                | -         |     0.57 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     4300 | 2024-02-11 | ex-Sprout         | W   | 0.034      | -            | -                | -                | -         |     0.11 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4307 | 2024-02-10 | FURIA             | W   | 0.029      | -            | -                | -                | -         |     0.89 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4310 | 2024-02-10 | Apeks             | L   | 0.028      | -            | -                | -                | -         |    -0.44 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4312 | 2024-02-10 | FURIA             | W   | 0.028      | -            | -                | -                | -         |     0.86 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4347 | 2024-02-07 | ex-Sprout         | W   | 0.008      | -            | -                | -                | -         |     0.03 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4355 | 2024-02-06 | Into the Breach   | L   | 0.001      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,985.63)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.642 | $2,000.00      | $1,283.75       |
| 2024-05-04 |      0.588 | $5,000.00      | $2,941.67       |
| 2024-04-20 |      0.496 | $5,000.00      | $2,481.48       |
| 2024-04-07 |      0.409 | $6,110.00      | $2,496.61       |
| 2024-03-10 |      0.223 | $12,500.00     | $2,782.12       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
