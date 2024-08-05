### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  903.9<br />
<br />
Final Rank Value (903.9) = Starting Rank Value (831.5) + Head To Head Adjustments (72.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.402[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.5
- 400 + ( ( 0.211 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 831.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |     2387 | 2024-05-04 | AMKAL             | L   | 0.579      | -            | -                | -                | -         |    -3.61 | adamb, Jackinho, nilo, susp, ztr    |
|           46 |     2403 | 2024-05-03 | Zero Tenacity     | W   | 0.573      | 0.435        | 0.137 (0.034)    | 1.000 (0.249)    | 0 (0.000) |    13.04 | adamb, Jackinho, nilo, susp, ztr    |
|           45 |     2423 | 2024-05-02 | Sangal            | W   | 0.567      | 0.435        | 0.219 (0.054)    | 0.877 (0.216)    | 0 (0.000) |    14.16 | adamb, Jackinho, nilo, susp, ztr    |
|           44 |     2584 | 2024-04-25 | Nexus             | L   | 0.521      | -            | -                | -                | -         |    -9.51 | adamb, Jackinho, nilo, susp, ztr    |
|           43 |     2626 | 2024-04-23 | Alliance          | W   | 0.507      | 0.384        | 0.017 (0.003)    | 0.296 (0.058)    | 0 (0.000) |     7.64 | adamb, Jackinho, nilo, p1ke, susp   |
|           42 |     2736 | 2024-04-19 | FURIA             | L   | 0.480      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, Plopski, susp, ztr |
|           41 |     2771 | 2024-04-18 | Imperial          | L   | 0.474      | -            | -                | -                | -         |    -1.43 | adamb, Jackinho, Plopski, susp, ztr |
|           40 |     3051 | 2024-04-09 | ex-Guild Eagles   | L   | 0.413      | -            | -                | -                | -         |    -7.98 | adamb, Jackinho, nilo, susp, ztr    |
|           39 |     3066 | 2024-04-08 | Aurora            | L   | 0.408      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr    |
|           38 |     3077 | 2024-04-08 | 9 Pandas          | L   | 0.407      | -            | -                | -                | -         |    -4.56 | adamb, Jackinho, nilo, susp, ztr    |
|           37 |     3104 | 2024-04-07 | EYEBALLERS        | W   | 0.401      | 0.330        | -                | 0.507 (0.067)    | 0 (0.000) |     6.47 | adamb, Jackinho, nilo, susp, ztr    |
|           36 |     3113 | 2024-04-07 | Johnny Speeds     | W   | 0.399      | 0.330        | 0.122 (0.016)    | 0.940 (0.124)    | 0 (0.000) |    11.43 | adamb, Jackinho, nilo, susp, ztr    |
|           35 |     3129 | 2024-04-06 | Young Gods        | W   | 0.393      | 0.330        | 0.007 (0.001)    | -                | 0 (0.000) |     3.67 | adamb, Jackinho, nilo, susp, ztr    |
|           34 |     3183 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.380      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           33 |     3212 | 2024-04-03 | Monte             | W   | 0.375      | 0.143        | 0.057 (0.003)    | -                | 0 (0.000) |     7.81 | adamb, Jackinho, nilo, susp, ztr    |
|           32 |     3221 | 2024-04-03 | FAVBET            | W   | 0.373      | 0.143        | -                | 0.338 (0.018)    | 0 (0.000) |     4.67 | adamb, Jackinho, nilo, susp, ztr    |
|           31 |     3253 | 2024-04-02 | B8                | W   | 0.368      | 0.143        | 0.165 (0.009)    | 0.947 (0.050)    | 0 (0.000) |     9.03 | adamb, Jackinho, nilo, susp, ztr    |
|           30 |     3261 | 2024-04-02 | Aurora            | L   | 0.367      | -            | -                | -                | -         |    -0.13 | adamb, Jackinho, nilo, susp, ztr    |
|           29 |     3275 | 2024-04-01 | PARIVISION        | L   | 0.361      | -            | -                | -                | -         |    -2.16 | adamb, Jackinho, nilo, susp, ztr    |
|           28 |     3343 | 2024-03-27 | Aurora            | L   | 0.329      | -            | -                | -                | -         |    -0.11 | adamb, Jackinho, nilo, susp, ztr    |
|           27 |     3349 | 2024-03-27 | NAVI Junior       | W   | 0.328      | -            | -                | -                | 0 (0.000) |     2.97 | adamb, Jackinho, nilo, susp, ztr    |
|           26 |     3552 | 2024-03-15 | kONO              | L   | 0.247      | -            | -                | -                | -         |    -4.47 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     3589 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.240      | -            | -                | -                | -         |    -2.61 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     3624 | 2024-03-13 | HEROIC            | L   | 0.234      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     3647 | 2024-03-12 | B8                | W   | 0.228      | 0.143        | 0.165 (0.005)    | 0.947 (0.031)    | -         |     5.69 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     3655 | 2024-03-12 | Apeks             | W   | 0.227      | -            | -                | -                | -         |     4.15 | adamb, Jackinho, nilo, susp, ztr    |
|           21 |     3666 | 2024-03-11 | ex-Preasy         | W   | 0.222      | -            | -                | -                | -         |     3.01 | adamb, Jackinho, nilo, susp, ztr    |
|           20 |     3677 | 2024-03-11 | ENCE              | L   | 0.220      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr    |
|           19 |     3687 | 2024-03-10 | Spirit            | L   | 0.215      | -            | -                | -                | -         |    -0.02 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     3713 | 2024-03-09 | Monte             | W   | 0.208      | 0.535        | 0.057 (0.006)    | 0.157 (0.017)    | -         |     4.57 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     3719 | 2024-03-09 | EYEBALLERS        | L   | 0.207      | -            | -                | -                | -         |    -2.75 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     3724 | 2024-03-09 | Lemondogs         | W   | 0.207      | -            | -                | -                | -         |     0.50 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     3744 | 2024-03-08 | Secret            | W   | 0.200      | -            | -                | -                | -         |     0.96 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     3785 | 2024-03-06 | Falcons           | W   | 0.188      | 0.535        | 0.222 (0.022)    | 0.245 (0.025)    | -         |     5.71 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     3866 | 2024-03-03 | The Chosen Few    | W   | 0.168      | -            | -                | -                | -         |     1.52 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     3872 | 2024-03-03 | ILIN              | W   | 0.168      | -            | -                | -                | -         |     0.43 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     3877 | 2024-03-03 | RUSH B            | W   | 0.168      | -            | -                | -                | -         |     2.83 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     3888 | 2024-03-03 | ECLOT             | L   | 0.167      | -            | -                | -                | -         |    -0.55 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     3936 | 2024-02-29 | Endpoint          | W   | 0.147      | -            | -                | -                | -         |     2.68 | adamb, Jackinho, nilo, susp, ztr    |
|            8 |     3956 | 2024-02-28 | INGLORIOUS        | W   | 0.139      | -            | -                | -                | -         |     0.71 | adamb, Jackinho, spooke, susp, ztr  |
|            7 |     3971 | 2024-02-27 | ex-Guild Eagles   | L   | 0.134      | -            | -                | -                | -         |    -2.23 | adamb, Jackinho, nilo, susp, ztr    |
|            6 |     4344 | 2024-02-11 | Apeks             | W   | 0.028      | -            | -                | -                | -         |     0.53 | adamb, Jackinho, nilo, susp, ztr    |
|            5 |     4349 | 2024-02-11 | ex-Sprout         | W   | 0.027      | -            | -                | -                | -         |     0.12 | adamb, Jackinho, nilo, susp, ztr    |
|            4 |     4356 | 2024-02-10 | FURIA             | W   | 0.021      | -            | -                | -                | -         |     0.66 | adamb, Jackinho, nilo, susp, ztr    |
|            3 |     4359 | 2024-02-10 | Apeks             | L   | 0.021      | -            | -                | -                | -         |    -0.26 | adamb, Jackinho, nilo, susp, ztr    |
|            2 |     4361 | 2024-02-10 | FURIA             | W   | 0.020      | -            | -                | -                | -         |     0.63 | adamb, Jackinho, nilo, susp, ztr    |
|            1 |     4396 | 2024-02-07 | ex-Sprout         | W   | 0.000      | -            | -                | -                | -         |     0.00 | adamb, Jackinho, nilo, susp, ztr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,487.31)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      0.581 | $5,000.00      | $2,904.17       |
| 2024-04-20 |      0.489 | $5,000.00      | $2,443.98       |
| 2024-04-07 |      0.401 | $6,110.00      | $2,450.79       |
| 2024-03-10 |      0.215 | $12,500.00     | $2,688.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
