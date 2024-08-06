### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  923.7<br />
<br />
Final Rank Value (923.7) = Starting Rank Value (902.3) + Head To Head Adjustments (21.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.409[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.3
- 400 + ( ( 0.245 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 902.3


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
|           60 |      146 | 2024-08-01 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | -                | 0.549 (0.078)    | 0 (0.000) |    13.70 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |      155 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.06 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      258 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.58 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      305 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.44 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      473 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.38 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      491 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.73 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      592 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.77 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |      651 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -18.37 | adamb, Jackinho, nilo, Plopski, Sapec |
|           52 |      770 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.513 (0.223)    | 0 (0.000) |    11.69 | adamb, Jackinho, nilo, Plopski, Sapec |
|           51 |     1834 | 2024-05-23 | Space             | L   | 0.699      | -            | -                | -                | -         |   -14.26 | abdi, adamb, Jackinho, nilo, Plopski  |
|           50 |     1940 | 2024-05-20 | Zero Tenacity     | L   | 0.682      | -            | -                | -                | -         |    -7.84 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     1992 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.669      | 0.500        | 0.254 (0.085)    | 0.543 (0.182)    | 0 (0.000) |    20.41 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2078 | 2024-05-16 | Rare Atom         | W   | 0.654      | 0.500        | -                | 0.475 (0.155)    | 0 (0.000) |     7.68 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2264 | 2024-05-11 | BetBoom           | L   | 0.621      | -            | -                | -                | -         |    -1.68 | adamb, Jackinho, nilo, Plopski, ztr   |
|           46 |     2278 | 2024-05-10 | EYEBALLERS        | W   | 0.615      | 0.435        | -                | 0.499 (0.133)    | 0 (0.000) |     8.55 | adamb, Jackinho, nilo, Plopski, ztr   |
|           45 |     2402 | 2024-05-04 | AMKAL             | L   | 0.573      | -            | -                | -                | -         |    -4.39 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2418 | 2024-05-03 | Zero Tenacity     | W   | 0.567      | 0.435        | 0.143 (0.035)    | 1.000 (0.246)    | 0 (0.000) |    11.91 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2438 | 2024-05-02 | Sangal            | W   | 0.561      | 0.435        | 0.219 (0.053)    | 0.865 (0.211)    | 0 (0.000) |    13.17 | adamb, Jackinho, nilo, susp, ztr      |
|           42 |     2599 | 2024-04-25 | Nexus             | L   | 0.515      | -            | -                | -                | -         |   -10.46 | adamb, Jackinho, nilo, susp, ztr      |
|           41 |     2641 | 2024-04-23 | Alliance          | W   | 0.501      | -            | -                | -                | 0 (0.000) |     6.39 | adamb, Jackinho, nilo, p1ke, susp     |
|           40 |     2751 | 2024-04-19 | FURIA             | L   | 0.474      | -            | -                | -                | -         |    -0.24 | adamb, Jackinho, Plopski, susp, ztr   |
|           39 |     2786 | 2024-04-18 | Imperial          | L   | 0.469      | -            | -                | -                | -         |    -1.88 | adamb, Jackinho, Plopski, susp, ztr   |
|           38 |     3066 | 2024-04-09 | ex-Guild Eagles   | L   | 0.407      | -            | -                | -                | -         |    -8.74 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3081 | 2024-04-08 | Aurora            | L   | 0.402      | -            | -                | -                | -         |    -0.23 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3092 | 2024-04-08 | 9 Pandas          | L   | 0.401      | -            | -                | -                | -         |    -5.46 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3119 | 2024-04-07 | EYEBALLERS        | W   | 0.395      | 0.330        | -                | 0.499 (0.065)    | -         |     5.43 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3128 | 2024-04-07 | Johnny Speeds     | W   | 0.393      | 0.330        | 0.122 (0.016)    | 1.000 (0.130)    | -         |    10.90 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3144 | 2024-04-06 | Young Gods        | W   | 0.387      | -            | -                | -                | -         |     2.86 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3198 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.374      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3227 | 2024-04-03 | Monte             | W   | 0.369      | -            | -                | -                | -         |     6.78 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3236 | 2024-04-03 | FAVBET            | W   | 0.368      | -            | -                | -                | -         |     3.70 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3268 | 2024-04-02 | B8                | W   | 0.362      | 0.143        | 0.164 (0.008)    | -                | -         |     8.16 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3276 | 2024-04-02 | Aurora            | L   | 0.361      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3290 | 2024-04-01 | PARIVISION        | L   | 0.355      | -            | -                | -                | -         |    -2.74 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3358 | 2024-03-27 | Aurora            | L   | 0.323      | -            | -                | -                | -         |    -0.15 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3364 | 2024-03-27 | NAVI Junior       | W   | 0.322      | -            | -                | -                | -         |     2.25 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3567 | 2024-03-15 | kONO              | L   | 0.242      | -            | -                | -                | -         |    -4.96 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3604 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.234      | -            | -                | -                | -         |    -3.17 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3639 | 2024-03-13 | HEROIC            | L   | 0.228      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3662 | 2024-03-12 | B8                | W   | 0.222      | 0.143        | 0.164 (0.005)    | -                | -         |     5.08 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3670 | 2024-03-12 | Apeks             | W   | 0.221      | -            | -                | -                | -         |     3.40 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3681 | 2024-03-11 | ex-Preasy         | W   | 0.216      | -            | -                | -                | -         |     2.33 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3692 | 2024-03-11 | ENCE              | L   | 0.215      | -            | -                | -                | -         |    -0.27 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3702 | 2024-03-10 | Spirit            | L   | 0.209      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3728 | 2024-03-09 | Monte             | W   | 0.202      | 0.535        | 0.057 (0.006)    | -                | -         |     3.90 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3734 | 2024-03-09 | EYEBALLERS        | L   | 0.201      | -            | -                | -                | -         |    -3.24 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3739 | 2024-03-09 | Lemondogs         | W   | 0.201      | -            | -                | -                | -         |     0.34 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3759 | 2024-03-08 | Secret            | W   | 0.194      | -            | -                | -                | -         |     0.67 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3800 | 2024-03-06 | Falcons           | W   | 0.183      | 0.535        | 0.220 (0.021)    | -                | -         |     5.44 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3881 | 2024-03-03 | The Chosen Few    | W   | 0.163      | -            | -                | -                | -         |     1.10 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3887 | 2024-03-03 | ILIN              | W   | 0.162      | -            | -                | -                | -         |     0.29 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3892 | 2024-03-03 | RUSH B            | W   | 0.162      | -            | -                | -                | -         |     2.25 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3903 | 2024-03-03 | ECLOT             | L   | 0.161      | -            | -                | -                | -         |    -0.74 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     3951 | 2024-02-29 | Endpoint          | W   | 0.141      | -            | -                | -                | -         |     2.15 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     3986 | 2024-02-27 | ex-Guild Eagles   | L   | 0.129      | -            | -                | -                | -         |    -2.52 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4359 | 2024-02-11 | Apeks             | W   | 0.023      | -            | -                | -                | -         |     0.35 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4364 | 2024-02-11 | ex-Sprout         | W   | 0.021      | -            | -                | -                | -         |     0.06 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4371 | 2024-02-10 | FURIA             | W   | 0.015      | -            | -                | -                | -         |     0.48 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4374 | 2024-02-10 | Apeks             | L   | 0.015      | -            | -                | -                | -         |    -0.23 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4376 | 2024-02-10 | FURIA             | W   | 0.014      | -            | -                | -                | -         |     0.45 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,577.50)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.629 | $2,000.00      | $1,257.08       |
| 2024-05-04 |      0.575 | $5,000.00      | $2,875.00       |
| 2024-04-20 |      0.483 | $5,000.00      | $2,414.81       |
| 2024-04-07 |      0.395 | $6,110.00      | $2,415.15       |
| 2024-03-10 |      0.209 | $12,500.00     | $2,615.45       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
