### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  919.1<br />
<br />
Final Rank Value (919.1) = Starting Rank Value (902.2) + Head To Head Adjustments (16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.409[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.2
- 400 + ( ( 0.244 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 902.2


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
|           61 |        0 | 2024-08-06 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.50 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      150 | 2024-08-01 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | -                | 0.537 (0.077)    | 0 (0.000) |    13.72 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |      159 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.07 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      262 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.58 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      309 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.45 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      477 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.39 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      495 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.73 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      596 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.77 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |      655 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -18.40 | adamb, Jackinho, nilo, Plopski, Sapec |
|           52 |      774 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.502 (0.218)    | 0 (0.000) |    11.68 | adamb, Jackinho, nilo, Plopski, Sapec |
|           51 |     1838 | 2024-05-23 | Space             | L   | 0.699      | -            | -                | -                | -         |   -14.27 | abdi, adamb, Jackinho, nilo, Plopski  |
|           50 |     1944 | 2024-05-20 | Zero Tenacity     | L   | 0.682      | -            | -                | -                | -         |    -7.84 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     1996 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.669      | 0.500        | 0.254 (0.085)    | 0.531 (0.178)    | 0 (0.000) |    20.40 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2082 | 2024-05-16 | Rare Atom         | W   | 0.654      | 0.500        | -                | 0.464 (0.152)    | 0 (0.000) |     7.68 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2268 | 2024-05-11 | BetBoom           | L   | 0.620      | -            | -                | -                | -         |    -1.68 | adamb, Jackinho, nilo, Plopski, ztr   |
|           46 |     2282 | 2024-05-10 | EYEBALLERS        | W   | 0.614      | 0.435        | -                | 0.488 (0.130)    | 0 (0.000) |     8.54 | adamb, Jackinho, nilo, Plopski, ztr   |
|           45 |     2406 | 2024-05-04 | AMKAL             | L   | 0.573      | -            | -                | -                | -         |    -4.40 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2422 | 2024-05-03 | Zero Tenacity     | W   | 0.567      | 0.435        | 0.143 (0.035)    | 1.000 (0.246)    | 0 (0.000) |    11.89 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2442 | 2024-05-02 | Sangal            | W   | 0.561      | 0.435        | 0.219 (0.053)    | 0.846 (0.206)    | 0 (0.000) |    13.15 | adamb, Jackinho, nilo, susp, ztr      |
|           42 |     2603 | 2024-04-25 | Nexus             | L   | 0.515      | -            | -                | -                | -         |   -10.46 | adamb, Jackinho, nilo, susp, ztr      |
|           41 |     2645 | 2024-04-23 | Alliance          | W   | 0.501      | -            | -                | -                | 0 (0.000) |     6.40 | adamb, Jackinho, nilo, p1ke, susp     |
|           40 |     2755 | 2024-04-19 | FURIA             | L   | 0.474      | -            | -                | -                | -         |    -0.24 | adamb, Jackinho, Plopski, susp, ztr   |
|           39 |     2790 | 2024-04-18 | Imperial          | L   | 0.468      | -            | -                | -                | -         |    -1.89 | adamb, Jackinho, Plopski, susp, ztr   |
|           38 |     3070 | 2024-04-09 | ex-Guild Eagles   | L   | 0.407      | -            | -                | -                | -         |    -8.73 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3085 | 2024-04-08 | Aurora            | L   | 0.402      | -            | -                | -                | -         |    -0.23 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3096 | 2024-04-08 | 9 Pandas          | L   | 0.401      | -            | -                | -                | -         |    -5.47 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3123 | 2024-04-07 | EYEBALLERS        | W   | 0.395      | 0.330        | -                | 0.488 (0.064)    | -         |     5.43 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3132 | 2024-04-07 | Johnny Speeds     | W   | 0.393      | 0.330        | 0.122 (0.016)    | 1.000 (0.130)    | -         |    10.89 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3148 | 2024-04-06 | Young Gods        | W   | 0.386      | -            | -                | -                | -         |     2.87 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3202 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.374      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3231 | 2024-04-03 | Monte             | W   | 0.368      | -            | -                | -                | -         |     6.77 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3240 | 2024-04-03 | FAVBET            | W   | 0.367      | -            | -                | -                | -         |     3.71 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3272 | 2024-04-02 | B8                | W   | 0.362      | 0.143        | 0.170 (0.009)    | -                | -         |     8.18 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3280 | 2024-04-02 | Aurora            | L   | 0.361      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3294 | 2024-04-01 | PARIVISION        | L   | 0.355      | -            | -                | -                | -         |    -2.72 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3362 | 2024-03-27 | Aurora            | L   | 0.322      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3368 | 2024-03-27 | NAVI Junior       | W   | 0.322      | -            | -                | -                | -         |     2.26 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3571 | 2024-03-15 | kONO              | L   | 0.241      | -            | -                | -                | -         |    -4.95 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3608 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.234      | -            | -                | -                | -         |    -3.15 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3643 | 2024-03-13 | HEROIC            | L   | 0.228      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3666 | 2024-03-12 | B8                | W   | 0.222      | 0.143        | 0.170 (0.005)    | -                | -         |     5.09 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3674 | 2024-03-12 | Apeks             | W   | 0.221      | -            | -                | -                | -         |     3.40 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3685 | 2024-03-11 | ex-Preasy         | W   | 0.215      | -            | -                | -                | -         |     2.33 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3696 | 2024-03-11 | ENCE              | L   | 0.214      | -            | -                | -                | -         |    -0.27 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3706 | 2024-03-10 | Spirit            | L   | 0.209      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3732 | 2024-03-09 | Monte             | W   | 0.201      | 0.535        | 0.057 (0.006)    | -                | -         |     3.89 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3738 | 2024-03-09 | EYEBALLERS        | L   | 0.201      | -            | -                | -                | -         |    -3.24 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3743 | 2024-03-09 | Lemondogs         | W   | 0.201      | -            | -                | -                | -         |     0.34 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3763 | 2024-03-08 | Secret            | W   | 0.194      | -            | -                | -                | -         |     0.67 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3804 | 2024-03-06 | Falcons           | W   | 0.182      | 0.535        | 0.220 (0.021)    | -                | -         |     5.43 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3885 | 2024-03-03 | The Chosen Few    | W   | 0.162      | -            | -                | -                | -         |     1.10 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3891 | 2024-03-03 | ILIN              | W   | 0.162      | -            | -                | -                | -         |     0.29 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3896 | 2024-03-03 | RUSH B            | W   | 0.162      | -            | -                | -                | -         |     2.25 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3907 | 2024-03-03 | ECLOT             | L   | 0.161      | -            | -                | -                | -         |    -0.74 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     3955 | 2024-02-29 | Endpoint          | W   | 0.141      | -            | -                | -                | -         |     2.15 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     3990 | 2024-02-27 | ex-Guild Eagles   | L   | 0.128      | -            | -                | -                | -         |    -2.51 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4363 | 2024-02-11 | Apeks             | W   | 0.022      | -            | -                | -                | -         |     0.35 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4368 | 2024-02-11 | ex-Sprout         | W   | 0.021      | -            | -                | -                | -         |     0.06 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4375 | 2024-02-10 | FURIA             | W   | 0.015      | -            | -                | -                | -         |     0.47 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4378 | 2024-02-10 | Apeks             | L   | 0.014      | -            | -                | -                | -         |    -0.23 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4380 | 2024-02-10 | FURIA             | W   | 0.014      | -            | -                | -                | -         |     0.44 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,568.99)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.628 | $2,000.00      | $1,256.53       |
| 2024-05-04 |      0.575 | $5,000.00      | $2,873.61       |
| 2024-04-20 |      0.483 | $5,000.00      | $2,413.43       |
| 2024-04-07 |      0.395 | $6,110.00      | $2,413.45       |
| 2024-03-10 |      0.209 | $12,500.00     | $2,611.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
