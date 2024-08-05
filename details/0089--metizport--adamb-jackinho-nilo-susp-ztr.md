### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  905.0<br />
<br />
Final Rank Value (905.0) = Starting Rank Value (831.9) + Head To Head Adjustments (73.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.402[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.086[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.9
- 400 + ( ( 0.211 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 831.9


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
|           47 |     2374 | 2024-05-04 | AMKAL             | L   | 0.583      | -            | -                | -                | -         |    -3.63 | adamb, Jackinho, nilo, susp, ztr    |
|           46 |     2390 | 2024-05-03 | Zero Tenacity     | W   | 0.576      | 0.435        | 0.137 (0.034)    | 1.000 (0.250)    | 0 (0.000) |    13.08 | adamb, Jackinho, nilo, susp, ztr    |
|           45 |     2410 | 2024-05-02 | Sangal            | W   | 0.570      | 0.435        | 0.219 (0.054)    | 0.861 (0.213)    | 0 (0.000) |    14.22 | adamb, Jackinho, nilo, susp, ztr    |
|           44 |     2571 | 2024-04-25 | Nexus             | L   | 0.524      | -            | -                | -                | -         |    -9.61 | adamb, Jackinho, nilo, susp, ztr    |
|           43 |     2613 | 2024-04-23 | Alliance          | W   | 0.510      | 0.384        | 0.017 (0.003)    | 0.298 (0.059)    | 0 (0.000) |     7.67 | adamb, Jackinho, nilo, p1ke, susp   |
|           42 |     2723 | 2024-04-19 | FURIA             | L   | 0.484      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, Plopski, susp, ztr |
|           41 |     2758 | 2024-04-18 | Imperial          | L   | 0.478      | -            | -                | -                | -         |    -1.43 | adamb, Jackinho, Plopski, susp, ztr |
|           40 |     3038 | 2024-04-09 | ex-Guild Eagles   | L   | 0.417      | -            | -                | -                | -         |    -8.06 | adamb, Jackinho, nilo, susp, ztr    |
|           39 |     3053 | 2024-04-08 | Aurora            | L   | 0.412      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr    |
|           38 |     3064 | 2024-04-08 | 9 Pandas          | L   | 0.410      | -            | -                | -                | -         |    -4.60 | adamb, Jackinho, nilo, susp, ztr    |
|           37 |     3091 | 2024-04-07 | EYEBALLERS        | W   | 0.404      | 0.330        | -                | 0.509 (0.068)    | 0 (0.000) |     6.51 | adamb, Jackinho, nilo, susp, ztr    |
|           36 |     3100 | 2024-04-07 | Johnny Speeds     | W   | 0.403      | 0.330        | 0.122 (0.016)    | 0.942 (0.125)    | 0 (0.000) |    11.51 | adamb, Jackinho, nilo, susp, ztr    |
|           35 |     3116 | 2024-04-06 | Young Gods        | W   | 0.396      | -            | -                | -                | 0 (0.000) |     3.68 | adamb, Jackinho, nilo, susp, ztr    |
|           34 |     3170 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.383      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           33 |     3199 | 2024-04-03 | Monte             | W   | 0.378      | 0.143        | 0.057 (0.003)    | -                | 0 (0.000) |     7.88 | adamb, Jackinho, nilo, susp, ztr    |
|           32 |     3208 | 2024-04-03 | FAVBET            | W   | 0.377      | 0.143        | -                | 0.340 (0.018)    | 0 (0.000) |     4.68 | adamb, Jackinho, nilo, susp, ztr    |
|           31 |     3240 | 2024-04-02 | B8                | W   | 0.371      | 0.143        | 0.165 (0.009)    | 0.951 (0.050)    | 0 (0.000) |     9.10 | adamb, Jackinho, nilo, susp, ztr    |
|           30 |     3248 | 2024-04-02 | Aurora            | L   | 0.370      | -            | -                | -                | -         |    -0.13 | adamb, Jackinho, nilo, susp, ztr    |
|           29 |     3262 | 2024-04-01 | PARIVISION        | L   | 0.364      | -            | -                | -                | -         |    -2.21 | adamb, Jackinho, nilo, susp, ztr    |
|           28 |     3330 | 2024-03-27 | Aurora            | L   | 0.332      | -            | -                | -                | -         |    -0.11 | adamb, Jackinho, nilo, susp, ztr    |
|           27 |     3336 | 2024-03-27 | NAVI Junior       | W   | 0.332      | -            | -                | -                | 0 (0.000) |     2.99 | adamb, Jackinho, nilo, susp, ztr    |
|           26 |     3539 | 2024-03-15 | kONO              | L   | 0.251      | -            | -                | -                | -         |    -4.54 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     3576 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.243      | -            | -                | -                | -         |    -2.66 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     3611 | 2024-03-13 | HEROIC            | L   | 0.237      | -            | -                | -                | -         |    -0.15 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     3634 | 2024-03-12 | B8                | W   | 0.232      | 0.143        | 0.165 (0.005)    | 0.951 (0.031)    | -         |     5.77 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     3642 | 2024-03-12 | Apeks             | W   | 0.230      | -            | -                | -                | -         |     4.22 | adamb, Jackinho, nilo, susp, ztr    |
|           21 |     3653 | 2024-03-11 | ex-Preasy         | W   | 0.225      | -            | -                | -                | -         |     3.06 | adamb, Jackinho, nilo, susp, ztr    |
|           20 |     3664 | 2024-03-11 | ENCE              | L   | 0.224      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr    |
|           19 |     3674 | 2024-03-10 | Spirit            | L   | 0.218      | -            | -                | -                | -         |    -0.02 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     3700 | 2024-03-09 | Monte             | W   | 0.211      | 0.535        | 0.057 (0.006)    | 0.159 (0.018)    | -         |     4.65 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     3706 | 2024-03-09 | EYEBALLERS        | L   | 0.210      | -            | -                | -                | -         |    -2.79 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     3711 | 2024-03-09 | Lemondogs         | W   | 0.210      | -            | -                | -                | -         |     0.50 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     3731 | 2024-03-08 | Secret            | W   | 0.203      | -            | -                | -                | -         |     0.97 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     3772 | 2024-03-06 | Falcons           | W   | 0.192      | 0.535        | 0.223 (0.023)    | 0.246 (0.025)    | -         |     5.81 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     3853 | 2024-03-03 | The Chosen Few    | W   | 0.172      | -            | -                | -                | -         |     1.54 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     3859 | 2024-03-03 | ILIN              | W   | 0.171      | -            | -                | -                | -         |     0.44 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     3864 | 2024-03-03 | RUSH B            | W   | 0.171      | -            | -                | -                | -         |     2.88 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     3875 | 2024-03-03 | ECLOT             | L   | 0.170      | -            | -                | -                | -         |    -0.56 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     3923 | 2024-02-29 | Endpoint          | W   | 0.150      | -            | -                | -                | -         |     2.74 | adamb, Jackinho, nilo, susp, ztr    |
|            8 |     3943 | 2024-02-28 | INGLORIOUS        | W   | 0.142      | -            | -                | -                | -         |     0.72 | adamb, Jackinho, spooke, susp, ztr  |
|            7 |     3958 | 2024-02-27 | ex-Guild Eagles   | L   | 0.138      | -            | -                | -                | -         |    -2.29 | adamb, Jackinho, nilo, susp, ztr    |
|            6 |     4331 | 2024-02-11 | Apeks             | W   | 0.032      | -            | -                | -                | -         |     0.59 | adamb, Jackinho, nilo, susp, ztr    |
|            5 |     4336 | 2024-02-11 | ex-Sprout         | W   | 0.030      | -            | -                | -                | -         |     0.13 | adamb, Jackinho, nilo, susp, ztr    |
|            4 |     4343 | 2024-02-10 | FURIA             | W   | 0.024      | 0.143        | 0.284 (0.001)    | -                | -         |     0.76 | adamb, Jackinho, nilo, susp, ztr    |
|            3 |     4346 | 2024-02-10 | Apeks             | L   | 0.024      | -            | -                | -                | -         |    -0.31 | adamb, Jackinho, nilo, susp, ztr    |
|            2 |     4348 | 2024-02-10 | FURIA             | W   | 0.024      | -            | -                | -                | -         |     0.74 | adamb, Jackinho, nilo, susp, ztr    |
|            1 |     4383 | 2024-02-07 | ex-Sprout         | W   | 0.004      | -            | -                | -                | -         |     0.02 | adamb, Jackinho, nilo, susp, ztr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,582.67)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      0.584 | $5,000.00      | $2,920.83       |
| 2024-04-20 |      0.492 | $5,000.00      | $2,460.65       |
| 2024-04-07 |      0.404 | $6,110.00      | $2,471.16       |
| 2024-03-10 |      0.218 | $12,500.00     | $2,730.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
