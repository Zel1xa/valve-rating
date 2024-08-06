### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  903.4<br />
<br />
Final Rank Value (903.4) = Starting Rank Value (831.8) + Head To Head Adjustments (71.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.402[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.8
- 400 + ( ( 0.211 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 831.8


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
|           46 |     2398 | 2024-05-04 | AMKAL             | L   | 0.576      | -            | -                | -                | -         |    -3.58 | adamb, Jackinho, nilo, susp, ztr    |
|           45 |     2414 | 2024-05-03 | Zero Tenacity     | W   | 0.569      | 0.435        | 0.143 (0.035)    | 1.000 (0.247)    | 0 (0.000) |    13.01 | adamb, Jackinho, nilo, susp, ztr    |
|           44 |     2434 | 2024-05-02 | Sangal            | W   | 0.564      | 0.435        | 0.219 (0.054)    | 0.866 (0.212)    | 0 (0.000) |    14.11 | adamb, Jackinho, nilo, susp, ztr    |
|           43 |     2595 | 2024-04-25 | Nexus             | L   | 0.518      | -            | -                | -                | -         |    -9.43 | adamb, Jackinho, nilo, susp, ztr    |
|           42 |     2637 | 2024-04-23 | Alliance          | W   | 0.503      | 0.384        | 0.017 (0.003)    | 0.291 (0.056)    | 0 (0.000) |     7.59 | adamb, Jackinho, nilo, p1ke, susp   |
|           41 |     2747 | 2024-04-19 | FURIA             | L   | 0.477      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, Plopski, susp, ztr |
|           40 |     2782 | 2024-04-18 | Imperial          | L   | 0.471      | -            | -                | -                | -         |    -1.44 | adamb, Jackinho, Plopski, susp, ztr |
|           39 |     3062 | 2024-04-09 | ex-Guild Eagles   | L   | 0.410      | -            | -                | -                | -         |    -7.91 | adamb, Jackinho, nilo, susp, ztr    |
|           38 |     3077 | 2024-04-08 | Aurora            | L   | 0.405      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr    |
|           37 |     3088 | 2024-04-08 | 9 Pandas          | L   | 0.404      | -            | -                | -                | -         |    -4.53 | adamb, Jackinho, nilo, susp, ztr    |
|           36 |     3115 | 2024-04-07 | EYEBALLERS        | W   | 0.398      | 0.330        | -                | 0.500 (0.066)    | 0 (0.000) |     6.45 | adamb, Jackinho, nilo, susp, ztr    |
|           35 |     3124 | 2024-04-07 | Johnny Speeds     | W   | 0.396      | 0.330        | 0.122 (0.016)    | 1.000 (0.131)    | 0 (0.000) |    11.34 | adamb, Jackinho, nilo, susp, ztr    |
|           34 |     3140 | 2024-04-06 | Young Gods        | W   | 0.389      | 0.330        | 0.007 (0.001)    | -                | 0 (0.000) |     3.65 | adamb, Jackinho, nilo, susp, ztr    |
|           33 |     3194 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.377      | -            | -                | -                | -         |    -0.13 | adamb, Jackinho, nilo, susp, ztr    |
|           32 |     3223 | 2024-04-03 | Monte             | W   | 0.371      | 0.143        | 0.057 (0.003)    | -                | 0 (0.000) |     7.73 | adamb, Jackinho, nilo, susp, ztr    |
|           31 |     3232 | 2024-04-03 | FAVBET            | W   | 0.370      | 0.143        | -                | 0.333 (0.018)    | 0 (0.000) |     4.63 | adamb, Jackinho, nilo, susp, ztr    |
|           30 |     3264 | 2024-04-02 | B8                | W   | 0.365      | 0.143        | 0.164 (0.009)    | 0.934 (0.049)    | 0 (0.000) |     8.95 | adamb, Jackinho, nilo, susp, ztr    |
|           29 |     3272 | 2024-04-02 | Aurora            | L   | 0.363      | -            | -                | -                | -         |    -0.12 | adamb, Jackinho, nilo, susp, ztr    |
|           28 |     3286 | 2024-04-01 | PARIVISION        | L   | 0.357      | -            | -                | -                | -         |    -2.11 | adamb, Jackinho, nilo, susp, ztr    |
|           27 |     3354 | 2024-03-27 | Aurora            | L   | 0.325      | -            | -                | -                | -         |    -0.11 | adamb, Jackinho, nilo, susp, ztr    |
|           26 |     3360 | 2024-03-27 | NAVI Junior       | W   | 0.325      | -            | -                | -                | 0 (0.000) |     2.94 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     3563 | 2024-03-15 | kONO              | L   | 0.244      | -            | -                | -                | -         |    -4.40 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     3600 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.237      | -            | -                | -                | -         |    -2.57 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     3635 | 2024-03-13 | HEROIC            | L   | 0.230      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     3658 | 2024-03-12 | B8                | W   | 0.225      | 0.143        | 0.164 (0.005)    | 0.934 (0.030)    | -         |     5.61 | adamb, Jackinho, nilo, susp, ztr    |
|           21 |     3666 | 2024-03-12 | Apeks             | W   | 0.224      | -            | -                | -                | -         |     4.08 | adamb, Jackinho, nilo, susp, ztr    |
|           20 |     3677 | 2024-03-11 | ex-Preasy         | W   | 0.218      | -            | -                | -                | -         |     2.96 | adamb, Jackinho, nilo, susp, ztr    |
|           19 |     3688 | 2024-03-11 | ENCE              | L   | 0.217      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     3698 | 2024-03-10 | Spirit            | L   | 0.212      | -            | -                | -                | -         |    -0.02 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     3724 | 2024-03-09 | Monte             | W   | 0.204      | 0.535        | 0.057 (0.006)    | 0.154 (0.017)    | -         |     4.49 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     3730 | 2024-03-09 | EYEBALLERS        | L   | 0.204      | -            | -                | -                | -         |    -2.69 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     3735 | 2024-03-09 | Lemondogs         | W   | 0.203      | -            | -                | -                | -         |     0.49 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     3755 | 2024-03-08 | Secret            | W   | 0.197      | -            | -                | -                | -         |     0.94 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     3796 | 2024-03-06 | Falcons           | W   | 0.185      | 0.535        | 0.221 (0.022)    | 0.242 (0.024)    | -         |     5.61 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     3877 | 2024-03-03 | The Chosen Few    | W   | 0.165      | -            | -                | -                | -         |     1.49 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     3883 | 2024-03-03 | ILIN              | W   | 0.165      | -            | -                | -                | -         |     0.42 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     3888 | 2024-03-03 | RUSH B            | W   | 0.164      | -            | -                | -                | -         |     2.78 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     3899 | 2024-03-03 | ECLOT             | L   | 0.163      | -            | -                | -                | -         |    -0.54 | adamb, Jackinho, nilo, susp, ztr    |
|            8 |     3947 | 2024-02-29 | Endpoint          | W   | 0.144      | -            | -                | -                | -         |     2.62 | adamb, Jackinho, nilo, susp, ztr    |
|            7 |     3967 | 2024-02-28 | INGLORIOUS        | W   | 0.136      | -            | -                | -                | -         |     0.69 | adamb, Jackinho, spooke, susp, ztr  |
|            6 |     3982 | 2024-02-27 | ex-Guild Eagles   | L   | 0.131      | -            | -                | -                | -         |    -2.18 | adamb, Jackinho, nilo, susp, ztr    |
|            5 |     4355 | 2024-02-11 | Apeks             | W   | 0.025      | -            | -                | -                | -         |     0.47 | adamb, Jackinho, nilo, susp, ztr    |
|            4 |     4360 | 2024-02-11 | ex-Sprout         | W   | 0.023      | -            | -                | -                | -         |     0.10 | adamb, Jackinho, nilo, susp, ztr    |
|            3 |     4367 | 2024-02-10 | FURIA             | W   | 0.018      | -            | -                | -                | -         |     0.56 | adamb, Jackinho, nilo, susp, ztr    |
|            2 |     4370 | 2024-02-10 | Apeks             | L   | 0.017      | -            | -                | -                | -         |    -0.22 | adamb, Jackinho, nilo, susp, ztr    |
|            1 |     4372 | 2024-02-10 | FURIA             | W   | 0.017      | -            | -                | -                | -         |     0.53 | adamb, Jackinho, nilo, susp, ztr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,391.94)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      0.578 | $5,000.00      | $2,887.50       |
| 2024-04-20 |      0.485 | $5,000.00      | $2,427.31       |
| 2024-04-07 |      0.398 | $6,110.00      | $2,430.42       |
| 2024-03-10 |      0.212 | $12,500.00     | $2,646.70       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
