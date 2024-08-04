### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  905.9<br />
<br />
Final Rank Value (905.9) = Starting Rank Value (832.2) + Head To Head Adjustments (73.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.403[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.086[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 832.2
- 400 + ( ( 0.211 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 832.2


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
|           47 |     2369 | 2024-05-04 | AMKAL             | L   | 0.585      | -            | -                | -                | -         |    -3.66 | adamb, Jackinho, nilo, susp, ztr    |
|           46 |     2385 | 2024-05-03 | Zero Tenacity     | W   | 0.579      | 0.435        | 0.137 (0.034)    | 1.000 (0.252)    | 0 (0.000) |    13.10 | adamb, Jackinho, nilo, susp, ztr    |
|           45 |     2405 | 2024-05-02 | Sangal            | W   | 0.573      | 0.435        | 0.219 (0.055)    | 0.861 (0.215)    | 0 (0.000) |    14.24 | adamb, Jackinho, nilo, susp, ztr    |
|           44 |     2566 | 2024-04-25 | Nexus             | L   | 0.527      | -            | -                | -                | -         |    -9.68 | adamb, Jackinho, nilo, susp, ztr    |
|           43 |     2608 | 2024-04-23 | Alliance          | W   | 0.513      | 0.384        | 0.017 (0.003)    | 0.300 (0.059)    | 0 (0.000) |     7.69 | adamb, Jackinho, nilo, p1ke, susp   |
|           42 |     2718 | 2024-04-19 | FURIA             | L   | 0.486      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, Plopski, susp, ztr |
|           41 |     2753 | 2024-04-18 | Imperial          | L   | 0.480      | -            | -                | -                | -         |    -1.44 | adamb, Jackinho, Plopski, susp, ztr |
|           40 |     3033 | 2024-04-09 | ex-Guild Eagles   | L   | 0.419      | -            | -                | -                | -         |    -8.11 | adamb, Jackinho, nilo, susp, ztr    |
|           39 |     3048 | 2024-04-08 | Aurora            | L   | 0.414      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr    |
|           38 |     3059 | 2024-04-08 | 9 Pandas          | L   | 0.413      | -            | -                | -                | -         |    -4.63 | adamb, Jackinho, nilo, susp, ztr    |
|           37 |     3086 | 2024-04-07 | EYEBALLERS        | W   | 0.407      | 0.330        | -                | 0.509 (0.069)    | 0 (0.000) |     6.54 | adamb, Jackinho, nilo, susp, ztr    |
|           36 |     3095 | 2024-04-07 | Johnny Speeds     | W   | 0.405      | 0.330        | 0.122 (0.016)    | 0.941 (0.126)    | 0 (0.000) |    11.58 | adamb, Jackinho, nilo, susp, ztr    |
|           35 |     3111 | 2024-04-06 | Young Gods        | W   | 0.399      | -            | -                | -                | 0 (0.000) |     3.69 | adamb, Jackinho, nilo, susp, ztr    |
|           34 |     3165 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.386      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           33 |     3194 | 2024-04-03 | Monte             | W   | 0.381      | 0.143        | 0.058 (0.003)    | -                | 0 (0.000) |     7.94 | adamb, Jackinho, nilo, susp, ztr    |
|           32 |     3203 | 2024-04-03 | FAVBET            | W   | 0.379      | 0.143        | -                | 0.340 (0.018)    | 0 (0.000) |     4.71 | adamb, Jackinho, nilo, susp, ztr    |
|           31 |     3235 | 2024-04-02 | B8                | W   | 0.374      | 0.143        | 0.165 (0.009)    | 0.912 (0.049)    | 0 (0.000) |     9.16 | adamb, Jackinho, nilo, susp, ztr    |
|           30 |     3243 | 2024-04-02 | Aurora            | L   | 0.373      | -            | -                | -                | -         |    -0.13 | adamb, Jackinho, nilo, susp, ztr    |
|           29 |     3257 | 2024-04-01 | PARIVISION        | L   | 0.367      | -            | -                | -                | -         |    -2.24 | adamb, Jackinho, nilo, susp, ztr    |
|           28 |     3325 | 2024-03-27 | Aurora            | L   | 0.335      | -            | -                | -                | -         |    -0.11 | adamb, Jackinho, nilo, susp, ztr    |
|           27 |     3331 | 2024-03-27 | NAVI Junior       | W   | 0.334      | -            | -                | -                | 0 (0.000) |     3.01 | adamb, Jackinho, nilo, susp, ztr    |
|           26 |     3534 | 2024-03-15 | kONO              | L   | 0.254      | -            | -                | -                | -         |    -4.60 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     3571 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.246      | -            | -                | -                | -         |    -2.70 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     3606 | 2024-03-13 | HEROIC            | L   | 0.240      | -            | -                | -                | -         |    -0.15 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     3629 | 2024-03-12 | B8                | W   | 0.234      | 0.143        | 0.165 (0.006)    | 0.912 (0.031)    | -         |     5.83 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     3637 | 2024-03-12 | Apeks             | W   | 0.233      | -            | -                | -                | -         |     4.27 | adamb, Jackinho, nilo, susp, ztr    |
|           21 |     3648 | 2024-03-11 | ex-Preasy         | W   | 0.228      | -            | -                | -                | -         |     3.10 | adamb, Jackinho, nilo, susp, ztr    |
|           20 |     3659 | 2024-03-11 | ENCE              | L   | 0.226      | -            | -                | -                | -         |    -0.21 | adamb, Jackinho, nilo, susp, ztr    |
|           19 |     3669 | 2024-03-10 | Spirit            | L   | 0.221      | -            | -                | -                | -         |    -0.02 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     3695 | 2024-03-09 | Monte             | W   | 0.214      | 0.535        | 0.058 (0.007)    | 0.160 (0.018)    | -         |     4.71 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     3701 | 2024-03-09 | EYEBALLERS        | L   | 0.213      | -            | -                | -                | -         |    -2.83 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     3706 | 2024-03-09 | Lemondogs         | W   | 0.213      | -            | -                | -                | -         |     0.51 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     3726 | 2024-03-08 | Secret            | W   | 0.206      | -            | -                | -                | -         |     0.98 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     3767 | 2024-03-06 | Falcons           | W   | 0.194      | 0.535        | 0.223 (0.023)    | 0.246 (0.026)    | -         |     5.89 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     3848 | 2024-03-03 | The Chosen Few    | W   | 0.174      | -            | -                | -                | -         |     1.57 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     3854 | 2024-03-03 | ILIN              | W   | 0.174      | -            | -                | -                | -         |     0.44 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     3859 | 2024-03-03 | RUSH B            | W   | 0.174      | -            | -                | -                | -         |     2.92 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     3870 | 2024-03-03 | ECLOT             | L   | 0.173      | -            | -                | -                | -         |    -0.57 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     3918 | 2024-02-29 | Endpoint          | W   | 0.153      | -            | -                | -                | -         |     2.79 | adamb, Jackinho, nilo, susp, ztr    |
|            8 |     3938 | 2024-02-28 | INGLORIOUS        | W   | 0.145      | -            | -                | -                | -         |     0.73 | adamb, Jackinho, spooke, susp, ztr  |
|            7 |     3953 | 2024-02-27 | ex-Guild Eagles   | L   | 0.140      | -            | -                | -                | -         |    -2.33 | adamb, Jackinho, nilo, susp, ztr    |
|            6 |     4326 | 2024-02-11 | Apeks             | W   | 0.034      | -            | -                | -                | -         |     0.65 | adamb, Jackinho, nilo, susp, ztr    |
|            5 |     4331 | 2024-02-11 | ex-Sprout         | W   | 0.033      | -            | -                | -                | -         |     0.15 | adamb, Jackinho, nilo, susp, ztr    |
|            4 |     4338 | 2024-02-10 | FURIA             | W   | 0.027      | 0.143        | 0.284 (0.001)    | -                | -         |     0.85 | adamb, Jackinho, nilo, susp, ztr    |
|            3 |     4341 | 2024-02-10 | Apeks             | L   | 0.027      | -            | -                | -                | -         |    -0.34 | adamb, Jackinho, nilo, susp, ztr    |
|            2 |     4343 | 2024-02-10 | FURIA             | W   | 0.026      | -            | -                | -                | -         |     0.82 | adamb, Jackinho, nilo, susp, ztr    |
|            1 |     4378 | 2024-02-07 | ex-Sprout         | W   | 0.006      | -            | -                | -                | -         |     0.03 | adamb, Jackinho, nilo, susp, ztr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,659.49)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      0.587 | $5,000.00      | $2,934.26       |
| 2024-04-20 |      0.495 | $5,000.00      | $2,474.07       |
| 2024-04-07 |      0.407 | $6,110.00      | $2,487.56       |
| 2024-03-10 |      0.221 | $12,500.00     | $2,763.60       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
