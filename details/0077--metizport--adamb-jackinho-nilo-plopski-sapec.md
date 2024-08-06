### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  955.1<br />
<br />
Final Rank Value (955.1) = Starting Rank Value (905.3) + Head To Head Adjustments (49.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.409[<sup>1</sup>](#table2)
- Bounty Collected: 0.387[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.3
- 400 + ( ( 0.246 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 905.3


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
|           63 |        0 | 2024-08-06 | BLEED             | W   | 1.000      | 0.143        | 0.126 (0.018)    | 0.538 (0.077)    | 0 (0.000) |    27.22 | adamb, Jackinho, nilo, Plopski, Sapec |
|           62 |        2 | 2024-08-06 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.26 | adamb, Jackinho, nilo, Plopski, Sapec |
|           61 |        6 | 2024-08-06 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.51 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      158 | 2024-08-01 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | -                | 0.537 (0.077)    | 0 (0.000) |    13.69 | adamb, L00m1, nilo, Plopski, Sapec    |
|           59 |      167 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.08 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      270 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.56 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      317 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.45 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      485 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.41 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      503 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.54 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      604 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.88 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |      663 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -18.42 | adamb, Jackinho, nilo, Plopski, Sapec |
|           52 |      782 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |    11.79 | adamb, Jackinho, nilo, Plopski, Sapec |
|           51 |     1846 | 2024-05-23 | Space             | L   | 0.698      | -            | -                | -                | -         |   -14.24 | abdi, adamb, Jackinho, nilo, Plopski  |
|           50 |     1952 | 2024-05-20 | Zero Tenacity     | L   | 0.681      | -            | -                | -                | -         |    -7.88 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     2004 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.668      | 0.500        | 0.253 (0.085)    | 0.531 (0.177)    | 0 (0.000) |    20.36 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2090 | 2024-05-16 | Rare Atom         | W   | 0.653      | 0.500        | -                | 0.465 (0.152)    | 0 (0.000) |     7.66 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2276 | 2024-05-11 | BetBoom           | L   | 0.619      | -            | -                | -                | -         |    -1.70 | adamb, Jackinho, nilo, Plopski, ztr   |
|           46 |     2290 | 2024-05-10 | EYEBALLERS        | W   | 0.614      | 0.435        | -                | 0.488 (0.130)    | 0 (0.000) |     8.48 | adamb, Jackinho, nilo, Plopski, ztr   |
|           45 |     2414 | 2024-05-04 | AMKAL             | L   | 0.572      | -            | -                | -                | -         |    -4.42 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2430 | 2024-05-03 | Zero Tenacity     | W   | 0.566      | 0.435        | 0.143 (0.035)    | 1.000 (0.246)    | 0 (0.000) |    11.83 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2450 | 2024-05-02 | Sangal            | W   | 0.560      | 0.435        | 0.219 (0.053)    | 0.846 (0.206)    | -         |    13.17 | adamb, Jackinho, nilo, susp, ztr      |
|           42 |     2611 | 2024-04-25 | Nexus             | L   | 0.514      | -            | -                | -                | -         |   -10.46 | adamb, Jackinho, nilo, susp, ztr      |
|           41 |     2653 | 2024-04-23 | Alliance          | W   | 0.500      | -            | -                | -                | -         |     6.34 | adamb, Jackinho, nilo, p1ke, susp     |
|           40 |     2763 | 2024-04-19 | FURIA             | L   | 0.473      | -            | -                | -                | -         |    -0.24 | adamb, Jackinho, Plopski, susp, ztr   |
|           39 |     2798 | 2024-04-18 | Imperial          | L   | 0.467      | -            | -                | -                | -         |    -1.91 | adamb, Jackinho, Plopski, susp, ztr   |
|           38 |     3078 | 2024-04-09 | ex-Guild Eagles   | L   | 0.406      | -            | -                | -                | -         |    -8.74 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3093 | 2024-04-08 | Aurora            | L   | 0.401      | -            | -                | -                | -         |    -0.23 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3104 | 2024-04-08 | 9 Pandas          | L   | 0.400      | -            | -                | -                | -         |    -5.50 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3131 | 2024-04-07 | EYEBALLERS        | W   | 0.394      | -            | -                | -                | -         |     5.37 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3140 | 2024-04-07 | Johnny Speeds     | W   | 0.392      | 0.330        | 0.122 (0.016)    | 1.000 (0.130)    | -         |    10.87 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3156 | 2024-04-06 | Young Gods        | W   | 0.385      | -            | -                | -                | -         |     2.83 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3210 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.373      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3239 | 2024-04-03 | Monte             | W   | 0.368      | -            | -                | -                | -         |     6.71 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3248 | 2024-04-03 | FAVBET            | W   | 0.366      | -            | -                | -                | -         |     3.68 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3280 | 2024-04-02 | B8                | W   | 0.361      | 0.143        | 0.170 (0.009)    | -                | -         |     8.12 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3288 | 2024-04-02 | Aurora            | L   | 0.360      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3302 | 2024-04-01 | PARIVISION        | L   | 0.354      | -            | -                | -                | -         |    -2.74 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3370 | 2024-03-27 | Aurora            | L   | 0.322      | -            | -                | -                | -         |    -0.15 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3376 | 2024-03-27 | NAVI Junior       | W   | 0.321      | -            | -                | -                | -         |     2.42 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3579 | 2024-03-15 | kONO              | L   | 0.240      | -            | -                | -                | -         |    -4.95 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3616 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.233      | -            | -                | -                | -         |    -3.16 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3651 | 2024-03-13 | HEROIC            | L   | 0.227      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3674 | 2024-03-12 | B8                | W   | 0.221      | 0.143        | 0.170 (0.005)    | -                | -         |     5.05 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3682 | 2024-03-12 | Apeks             | W   | 0.220      | -            | -                | -                | -         |     3.35 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3693 | 2024-03-11 | ex-Preasy         | W   | 0.214      | -            | -                | -                | -         |     2.29 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3704 | 2024-03-11 | ENCE              | L   | 0.213      | -            | -                | -                | -         |    -0.27 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3714 | 2024-03-10 | Spirit            | L   | 0.208      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3740 | 2024-03-09 | Monte             | W   | 0.201      | 0.535        | 0.057 (0.006)    | -                | -         |     3.85 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3746 | 2024-03-09 | EYEBALLERS        | L   | 0.200      | -            | -                | -                | -         |    -3.25 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3751 | 2024-03-09 | Lemondogs         | W   | 0.200      | -            | -                | -                | -         |     0.33 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3771 | 2024-03-08 | Secret            | W   | 0.193      | -            | -                | -                | -         |     0.66 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3812 | 2024-03-06 | Falcons           | W   | 0.181      | 0.535        | 0.219 (0.021)    | -                | -         |     5.40 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3893 | 2024-03-03 | The Chosen Few    | W   | 0.161      | -            | -                | -                | -         |     1.08 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3899 | 2024-03-03 | ILIN              | W   | 0.161      | -            | -                | -                | -         |     0.28 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3904 | 2024-03-03 | RUSH B            | W   | 0.161      | -            | -                | -                | -         |     2.21 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3915 | 2024-03-03 | ECLOT             | L   | 0.160      | -            | -                | -                | -         |    -0.74 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     3963 | 2024-02-29 | Endpoint          | W   | 0.140      | -            | -                | -                | -         |     2.13 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     3998 | 2024-02-27 | ex-Guild Eagles   | L   | 0.127      | -            | -                | -                | -         |    -2.51 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4371 | 2024-02-11 | Apeks             | W   | 0.021      | -            | -                | -                | -         |     0.33 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4376 | 2024-02-11 | ex-Sprout         | W   | 0.020      | -            | -                | -                | -         |     0.06 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4383 | 2024-02-10 | FURIA             | W   | 0.014      | -            | -                | -                | -         |     0.44 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4386 | 2024-02-10 | Apeks             | L   | 0.013      | -            | -                | -                | -         |    -0.22 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4388 | 2024-02-10 | FURIA             | W   | 0.013      | -            | -                | -                | -         |     0.41 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,540.65)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.627 | $2,000.00      | $1,254.68       |
| 2024-05-04 |      0.574 | $5,000.00      | $2,868.98       |
| 2024-04-20 |      0.482 | $5,000.00      | $2,408.80       |
| 2024-04-07 |      0.394 | $6,110.00      | $2,407.79       |
| 2024-03-10 |      0.208 | $12,500.00     | $2,600.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
