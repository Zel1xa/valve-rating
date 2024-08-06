### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  919.6<br />
<br />
Final Rank Value (919.6) = Starting Rank Value (902.1) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.409[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.1
- 400 + ( ( 0.244 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 902.1


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
|           61 |        2 | 2024-08-06 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.49 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      153 | 2024-08-01 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | -                | 0.537 (0.077)    | 0 (0.000) |    13.73 | adamb, L00m1, nilo, Plopski, Sapec    |
|           59 |      162 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.04 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      265 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.58 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      312 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.42 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      480 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.39 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      498 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.65 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      599 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.92 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |      658 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -18.41 | adamb, Jackinho, nilo, Plopski, Sapec |
|           52 |      777 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.502 (0.218)    | 0 (0.000) |    11.81 | adamb, Jackinho, nilo, Plopski, Sapec |
|           51 |     1841 | 2024-05-23 | Space             | L   | 0.699      | -            | -                | -                | -         |   -14.26 | abdi, adamb, Jackinho, nilo, Plopski  |
|           50 |     1947 | 2024-05-20 | Zero Tenacity     | L   | 0.682      | -            | -                | -                | -         |    -7.84 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     1999 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.668      | 0.500        | 0.254 (0.085)    | 0.531 (0.178)    | 0 (0.000) |    20.39 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2085 | 2024-05-16 | Rare Atom         | W   | 0.653      | 0.500        | -                | 0.464 (0.152)    | 0 (0.000) |     7.68 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2271 | 2024-05-11 | BetBoom           | L   | 0.620      | -            | -                | -                | -         |    -1.69 | adamb, Jackinho, nilo, Plopski, ztr   |
|           46 |     2285 | 2024-05-10 | EYEBALLERS        | W   | 0.614      | 0.435        | -                | 0.488 (0.130)    | 0 (0.000) |     8.54 | adamb, Jackinho, nilo, Plopski, ztr   |
|           45 |     2409 | 2024-05-04 | AMKAL             | L   | 0.573      | -            | -                | -                | -         |    -4.40 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2425 | 2024-05-03 | Zero Tenacity     | W   | 0.566      | 0.435        | 0.143 (0.035)    | 1.000 (0.246)    | 0 (0.000) |    11.88 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2445 | 2024-05-02 | Sangal            | W   | 0.560      | 0.435        | 0.219 (0.053)    | 0.846 (0.206)    | 0 (0.000) |    13.16 | adamb, Jackinho, nilo, susp, ztr      |
|           42 |     2606 | 2024-04-25 | Nexus             | L   | 0.515      | -            | -                | -                | -         |   -10.45 | adamb, Jackinho, nilo, susp, ztr      |
|           41 |     2648 | 2024-04-23 | Alliance          | W   | 0.500      | -            | -                | -                | 0 (0.000) |     6.39 | adamb, Jackinho, nilo, p1ke, susp     |
|           40 |     2758 | 2024-04-19 | FURIA             | L   | 0.474      | -            | -                | -                | -         |    -0.24 | adamb, Jackinho, Plopski, susp, ztr   |
|           39 |     2793 | 2024-04-18 | Imperial          | L   | 0.468      | -            | -                | -                | -         |    -1.89 | adamb, Jackinho, Plopski, susp, ztr   |
|           38 |     3073 | 2024-04-09 | ex-Guild Eagles   | L   | 0.407      | -            | -                | -                | -         |    -8.72 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3088 | 2024-04-08 | Aurora            | L   | 0.402      | -            | -                | -                | -         |    -0.23 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3099 | 2024-04-08 | 9 Pandas          | L   | 0.400      | -            | -                | -                | -         |    -5.46 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3126 | 2024-04-07 | EYEBALLERS        | W   | 0.395      | 0.330        | -                | 0.488 (0.064)    | -         |     5.42 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3135 | 2024-04-07 | Johnny Speeds     | W   | 0.393      | 0.330        | 0.122 (0.016)    | 1.000 (0.130)    | -         |    10.89 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3151 | 2024-04-06 | Young Gods        | W   | 0.386      | -            | -                | -                | -         |     2.86 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3205 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.374      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3234 | 2024-04-03 | Monte             | W   | 0.368      | -            | -                | -                | -         |     6.76 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3243 | 2024-04-03 | FAVBET            | W   | 0.367      | -            | -                | -                | -         |     3.73 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3275 | 2024-04-02 | B8                | W   | 0.361      | 0.143        | 0.170 (0.009)    | -                | -         |     8.17 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3283 | 2024-04-02 | Aurora            | L   | 0.360      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3297 | 2024-04-01 | PARIVISION        | L   | 0.354      | -            | -                | -                | -         |    -2.72 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3365 | 2024-03-27 | Aurora            | L   | 0.322      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3371 | 2024-03-27 | NAVI Junior       | W   | 0.322      | -            | -                | -                | -         |     2.44 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3574 | 2024-03-15 | kONO              | L   | 0.241      | -            | -                | -                | -         |    -4.93 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3611 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.234      | -            | -                | -                | -         |    -3.15 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3646 | 2024-03-13 | HEROIC            | L   | 0.227      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3669 | 2024-03-12 | B8                | W   | 0.222      | 0.143        | 0.170 (0.005)    | -                | -         |     5.09 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3677 | 2024-03-12 | Apeks             | W   | 0.221      | -            | -                | -                | -         |     3.39 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3688 | 2024-03-11 | ex-Preasy         | W   | 0.215      | -            | -                | -                | -         |     2.32 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3699 | 2024-03-11 | ENCE              | L   | 0.214      | -            | -                | -                | -         |    -0.27 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3709 | 2024-03-10 | Spirit            | L   | 0.209      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3735 | 2024-03-09 | Monte             | W   | 0.201      | 0.535        | 0.057 (0.006)    | -                | -         |     3.88 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3741 | 2024-03-09 | EYEBALLERS        | L   | 0.201      | -            | -                | -                | -         |    -3.23 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3746 | 2024-03-09 | Lemondogs         | W   | 0.200      | -            | -                | -                | -         |     0.34 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3766 | 2024-03-08 | Secret            | W   | 0.194      | -            | -                | -                | -         |     0.67 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3807 | 2024-03-06 | Falcons           | W   | 0.182      | 0.535        | 0.220 (0.021)    | -                | -         |     5.42 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3888 | 2024-03-03 | The Chosen Few    | W   | 0.162      | -            | -                | -                | -         |     1.10 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3894 | 2024-03-03 | ILIN              | W   | 0.162      | -            | -                | -                | -         |     0.29 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3899 | 2024-03-03 | RUSH B            | W   | 0.161      | -            | -                | -                | -         |     2.24 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3910 | 2024-03-03 | ECLOT             | L   | 0.160      | -            | -                | -                | -         |    -0.73 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     3958 | 2024-02-29 | Endpoint          | W   | 0.140      | -            | -                | -                | -         |     2.14 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     3993 | 2024-02-27 | ex-Guild Eagles   | L   | 0.128      | -            | -                | -                | -         |    -2.50 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4366 | 2024-02-11 | Apeks             | W   | 0.022      | -            | -                | -                | -         |     0.34 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4371 | 2024-02-11 | ex-Sprout         | W   | 0.020      | -            | -                | -                | -         |     0.06 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4378 | 2024-02-10 | FURIA             | W   | 0.015      | -            | -                | -                | -         |     0.46 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4381 | 2024-02-10 | Apeks             | L   | 0.014      | -            | -                | -                | -         |    -0.22 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4383 | 2024-02-10 | FURIA             | W   | 0.014      | -            | -                | -                | -         |     0.43 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,557.66)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.628 | $2,000.00      | $1,255.79       |
| 2024-05-04 |      0.574 | $5,000.00      | $2,871.76       |
| 2024-04-20 |      0.482 | $5,000.00      | $2,411.57       |
| 2024-04-07 |      0.395 | $6,110.00      | $2,411.19       |
| 2024-03-10 |      0.209 | $12,500.00     | $2,607.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
