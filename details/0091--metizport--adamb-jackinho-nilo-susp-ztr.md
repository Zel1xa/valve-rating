### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  902.5<br />
<br />
Final Rank Value (902.5) = Starting Rank Value (831.4) + Head To Head Adjustments (71.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.210<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.4
- 400 + ( ( 0.210 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 831.4


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
|           46 |     2402 | 2024-05-04 | AMKAL             | L   | 0.573      | -            | -                | -                | -         |    -3.54 | adamb, Jackinho, nilo, susp, ztr    |
|           45 |     2418 | 2024-05-03 | Zero Tenacity     | W   | 0.567      | 0.435        | 0.143 (0.035)    | 1.000 (0.246)    | 0 (0.000) |    12.97 | adamb, Jackinho, nilo, susp, ztr    |
|           44 |     2438 | 2024-05-02 | Sangal            | W   | 0.561      | 0.435        | 0.219 (0.053)    | 0.865 (0.211)    | 0 (0.000) |    14.07 | adamb, Jackinho, nilo, susp, ztr    |
|           43 |     2599 | 2024-04-25 | Nexus             | L   | 0.515      | -            | -                | -                | -         |    -9.34 | adamb, Jackinho, nilo, susp, ztr    |
|           42 |     2641 | 2024-04-23 | Alliance          | W   | 0.501      | 0.384        | 0.017 (0.003)    | 0.289 (0.056)    | 0 (0.000) |     7.57 | adamb, Jackinho, nilo, p1ke, susp   |
|           41 |     2751 | 2024-04-19 | FURIA             | L   | 0.474      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, Plopski, susp, ztr |
|           40 |     2786 | 2024-04-18 | Imperial          | L   | 0.469      | -            | -                | -                | -         |    -1.43 | adamb, Jackinho, Plopski, susp, ztr |
|           39 |     3066 | 2024-04-09 | ex-Guild Eagles   | L   | 0.407      | -            | -                | -                | -         |    -7.85 | adamb, Jackinho, nilo, susp, ztr    |
|           38 |     3081 | 2024-04-08 | Aurora            | L   | 0.402      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr    |
|           37 |     3092 | 2024-04-08 | 9 Pandas          | L   | 0.401      | -            | -                | -                | -         |    -4.50 | adamb, Jackinho, nilo, susp, ztr    |
|           36 |     3119 | 2024-04-07 | EYEBALLERS        | W   | 0.395      | 0.330        | -                | 0.499 (0.065)    | 0 (0.000) |     6.43 | adamb, Jackinho, nilo, susp, ztr    |
|           35 |     3128 | 2024-04-07 | Johnny Speeds     | W   | 0.393      | 0.330        | 0.122 (0.016)    | 1.000 (0.130)    | 0 (0.000) |    11.28 | adamb, Jackinho, nilo, susp, ztr    |
|           34 |     3144 | 2024-04-06 | Young Gods        | W   | 0.387      | 0.330        | 0.007 (0.001)    | -                | 0 (0.000) |     3.64 | adamb, Jackinho, nilo, susp, ztr    |
|           33 |     3198 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.374      | -            | -                | -                | -         |    -0.13 | adamb, Jackinho, nilo, susp, ztr    |
|           32 |     3227 | 2024-04-03 | Monte             | W   | 0.369      | 0.143        | 0.057 (0.003)    | -                | 0 (0.000) |     7.68 | adamb, Jackinho, nilo, susp, ztr    |
|           31 |     3236 | 2024-04-03 | FAVBET            | W   | 0.368      | 0.143        | -                | 0.333 (0.017)    | 0 (0.000) |     4.61 | adamb, Jackinho, nilo, susp, ztr    |
|           30 |     3268 | 2024-04-02 | B8                | W   | 0.362      | 0.143        | 0.164 (0.008)    | 0.933 (0.048)    | 0 (0.000) |     8.89 | adamb, Jackinho, nilo, susp, ztr    |
|           29 |     3276 | 2024-04-02 | Aurora            | L   | 0.361      | -            | -                | -                | -         |    -0.12 | adamb, Jackinho, nilo, susp, ztr    |
|           28 |     3290 | 2024-04-01 | PARIVISION        | L   | 0.355      | -            | -                | -                | -         |    -2.08 | adamb, Jackinho, nilo, susp, ztr    |
|           27 |     3358 | 2024-03-27 | Aurora            | L   | 0.323      | -            | -                | -                | -         |    -0.10 | adamb, Jackinho, nilo, susp, ztr    |
|           26 |     3364 | 2024-03-27 | NAVI Junior       | W   | 0.322      | -            | -                | -                | 0 (0.000) |     2.93 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     3567 | 2024-03-15 | kONO              | L   | 0.242      | -            | -                | -                | -         |    -4.31 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     3604 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.234      | -            | -                | -                | -         |    -2.54 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     3639 | 2024-03-13 | HEROIC            | L   | 0.228      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     3662 | 2024-03-12 | B8                | W   | 0.222      | 0.143        | 0.164 (0.005)    | 0.933 (0.030)    | -         |     5.55 | adamb, Jackinho, nilo, susp, ztr    |
|           21 |     3670 | 2024-03-12 | Apeks             | W   | 0.221      | -            | -                | -                | -         |     4.03 | adamb, Jackinho, nilo, susp, ztr    |
|           20 |     3681 | 2024-03-11 | ex-Preasy         | W   | 0.216      | -            | -                | -                | -         |     2.92 | adamb, Jackinho, nilo, susp, ztr    |
|           19 |     3692 | 2024-03-11 | ENCE              | L   | 0.215      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     3702 | 2024-03-10 | Spirit            | L   | 0.209      | -            | -                | -                | -         |    -0.02 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     3728 | 2024-03-09 | Monte             | W   | 0.202      | 0.535        | 0.057 (0.006)    | 0.153 (0.016)    | -         |     4.43 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     3734 | 2024-03-09 | EYEBALLERS        | L   | 0.201      | -            | -                | -                | -         |    -2.65 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     3739 | 2024-03-09 | Lemondogs         | W   | 0.201      | -            | -                | -                | -         |     0.48 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     3759 | 2024-03-08 | Secret            | W   | 0.194      | -            | -                | -                | -         |     0.93 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     3800 | 2024-03-06 | Falcons           | W   | 0.183      | 0.535        | 0.220 (0.021)    | 0.242 (0.024)    | -         |     5.53 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     3881 | 2024-03-03 | The Chosen Few    | W   | 0.163      | -            | -                | -                | -         |     1.47 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     3887 | 2024-03-03 | ILIN              | W   | 0.162      | -            | -                | -                | -         |     0.42 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     3892 | 2024-03-03 | RUSH B            | W   | 0.162      | -            | -                | -                | -         |     2.74 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     3903 | 2024-03-03 | ECLOT             | L   | 0.161      | -            | -                | -                | -         |    -0.53 | adamb, Jackinho, nilo, susp, ztr    |
|            8 |     3951 | 2024-02-29 | Endpoint          | W   | 0.141      | -            | -                | -                | -         |     2.58 | adamb, Jackinho, nilo, susp, ztr    |
|            7 |     3971 | 2024-02-28 | INGLORIOUS        | W   | 0.133      | -            | -                | -                | -         |     0.68 | adamb, Jackinho, spooke, susp, ztr  |
|            6 |     3986 | 2024-02-27 | ex-Guild Eagles   | L   | 0.129      | -            | -                | -                | -         |    -2.14 | adamb, Jackinho, nilo, susp, ztr    |
|            5 |     4359 | 2024-02-11 | Apeks             | W   | 0.023      | -            | -                | -                | -         |     0.42 | adamb, Jackinho, nilo, susp, ztr    |
|            4 |     4364 | 2024-02-11 | ex-Sprout         | W   | 0.021      | -            | -                | -                | -         |     0.09 | adamb, Jackinho, nilo, susp, ztr    |
|            3 |     4371 | 2024-02-10 | FURIA             | W   | 0.015      | -            | -                | -                | -         |     0.48 | adamb, Jackinho, nilo, susp, ztr    |
|            2 |     4374 | 2024-02-10 | Apeks             | L   | 0.015      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr    |
|            1 |     4376 | 2024-02-10 | FURIA             | W   | 0.014      | -            | -                | -                | -         |     0.45 | adamb, Jackinho, nilo, susp, ztr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,320.41)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      0.575 | $5,000.00      | $2,875.00       |
| 2024-04-20 |      0.483 | $5,000.00      | $2,414.81       |
| 2024-04-07 |      0.395 | $6,110.00      | $2,415.15       |
| 2024-03-10 |      0.209 | $12,500.00     | $2,615.45       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
