### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  904.2<br />
<br />
Final Rank Value (904.2) = Starting Rank Value (832.2) + Head To Head Adjustments (72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.402[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 832.2
- 400 + ( ( 0.211 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 832.2


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
|           46 |     2396 | 2024-05-04 | AMKAL             | L   | 0.578      | -            | -                | -                | -         |    -3.59 | adamb, Jackinho, nilo, susp, ztr    |
|           45 |     2412 | 2024-05-03 | Zero Tenacity     | W   | 0.571      | 0.435        | 0.143 (0.035)    | 1.000 (0.248)    | 0 (0.000) |    13.04 | adamb, Jackinho, nilo, susp, ztr    |
|           44 |     2432 | 2024-05-02 | Sangal            | W   | 0.565      | 0.435        | 0.219 (0.054)    | 0.866 (0.213)    | 0 (0.000) |    14.14 | adamb, Jackinho, nilo, susp, ztr    |
|           43 |     2593 | 2024-04-25 | Nexus             | L   | 0.520      | -            | -                | -                | -         |    -9.47 | adamb, Jackinho, nilo, susp, ztr    |
|           42 |     2635 | 2024-04-23 | Alliance          | W   | 0.505      | 0.384        | 0.017 (0.003)    | 0.292 (0.057)    | 0 (0.000) |     7.61 | adamb, Jackinho, nilo, p1ke, susp   |
|           41 |     2745 | 2024-04-19 | FURIA             | L   | 0.479      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, Plopski, susp, ztr |
|           40 |     2780 | 2024-04-18 | Imperial          | L   | 0.473      | -            | -                | -                | -         |    -1.44 | adamb, Jackinho, Plopski, susp, ztr |
|           39 |     3060 | 2024-04-09 | ex-Guild Eagles   | L   | 0.412      | -            | -                | -                | -         |    -7.95 | adamb, Jackinho, nilo, susp, ztr    |
|           38 |     3075 | 2024-04-08 | Aurora            | L   | 0.407      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr    |
|           37 |     3086 | 2024-04-08 | 9 Pandas          | L   | 0.405      | -            | -                | -                | -         |    -4.55 | adamb, Jackinho, nilo, susp, ztr    |
|           36 |     3113 | 2024-04-07 | EYEBALLERS        | W   | 0.400      | 0.330        | -                | 0.500 (0.066)    | 0 (0.000) |     6.46 | adamb, Jackinho, nilo, susp, ztr    |
|           35 |     3122 | 2024-04-07 | Johnny Speeds     | W   | 0.398      | 0.330        | 0.122 (0.016)    | 1.000 (0.131)    | 0 (0.000) |    11.39 | adamb, Jackinho, nilo, susp, ztr    |
|           34 |     3138 | 2024-04-06 | Young Gods        | W   | 0.391      | 0.330        | 0.007 (0.001)    | -                | 0 (0.000) |     3.66 | adamb, Jackinho, nilo, susp, ztr    |
|           33 |     3192 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.379      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           32 |     3221 | 2024-04-03 | Monte             | W   | 0.373      | 0.143        | 0.057 (0.003)    | -                | 0 (0.000) |     7.77 | adamb, Jackinho, nilo, susp, ztr    |
|           31 |     3230 | 2024-04-03 | FAVBET            | W   | 0.372      | 0.143        | -                | 0.334 (0.018)    | 0 (0.000) |     4.65 | adamb, Jackinho, nilo, susp, ztr    |
|           30 |     3262 | 2024-04-02 | B8                | W   | 0.366      | 0.143        | 0.165 (0.009)    | 0.935 (0.049)    | 0 (0.000) |     8.99 | adamb, Jackinho, nilo, susp, ztr    |
|           29 |     3270 | 2024-04-02 | Aurora            | L   | 0.365      | -            | -                | -                | -         |    -0.13 | adamb, Jackinho, nilo, susp, ztr    |
|           28 |     3284 | 2024-04-01 | PARIVISION        | L   | 0.359      | -            | -                | -                | -         |    -2.13 | adamb, Jackinho, nilo, susp, ztr    |
|           27 |     3352 | 2024-03-27 | Aurora            | L   | 0.327      | -            | -                | -                | -         |    -0.11 | adamb, Jackinho, nilo, susp, ztr    |
|           26 |     3358 | 2024-03-27 | NAVI Junior       | W   | 0.327      | -            | -                | -                | 0 (0.000) |     2.96 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     3561 | 2024-03-15 | kONO              | L   | 0.246      | -            | -                | -                | -         |    -4.44 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     3598 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.239      | -            | -                | -                | -         |    -2.60 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     3633 | 2024-03-13 | HEROIC            | L   | 0.232      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     3656 | 2024-03-12 | B8                | W   | 0.227      | 0.143        | 0.165 (0.005)    | 0.935 (0.030)    | -         |     5.65 | adamb, Jackinho, nilo, susp, ztr    |
|           21 |     3664 | 2024-03-12 | Apeks             | W   | 0.226      | -            | -                | -                | -         |     4.12 | adamb, Jackinho, nilo, susp, ztr    |
|           20 |     3675 | 2024-03-11 | ex-Preasy         | W   | 0.220      | -            | -                | -                | -         |     2.98 | adamb, Jackinho, nilo, susp, ztr    |
|           19 |     3686 | 2024-03-11 | ENCE              | L   | 0.219      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     3696 | 2024-03-10 | Spirit            | L   | 0.214      | -            | -                | -                | -         |    -0.02 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     3722 | 2024-03-09 | Monte             | W   | 0.206      | 0.535        | 0.057 (0.006)    | 0.155 (0.017)    | -         |     4.53 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     3728 | 2024-03-09 | EYEBALLERS        | L   | 0.206      | -            | -                | -                | -         |    -2.72 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     3733 | 2024-03-09 | Lemondogs         | W   | 0.205      | -            | -                | -                | -         |     0.49 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     3753 | 2024-03-08 | Secret            | W   | 0.198      | -            | -                | -                | -         |     0.95 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     3794 | 2024-03-06 | Falcons           | W   | 0.187      | 0.535        | 0.221 (0.022)    | 0.242 (0.024)    | -         |     5.66 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     3875 | 2024-03-03 | The Chosen Few    | W   | 0.167      | -            | -                | -                | -         |     1.50 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     3881 | 2024-03-03 | ILIN              | W   | 0.167      | -            | -                | -                | -         |     0.42 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     3886 | 2024-03-03 | RUSH B            | W   | 0.166      | -            | -                | -                | -         |     2.81 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     3897 | 2024-03-03 | ECLOT             | L   | 0.165      | -            | -                | -                | -         |    -0.54 | adamb, Jackinho, nilo, susp, ztr    |
|            8 |     3945 | 2024-02-29 | Endpoint          | W   | 0.145      | -            | -                | -                | -         |     2.65 | adamb, Jackinho, nilo, susp, ztr    |
|            7 |     3965 | 2024-02-28 | INGLORIOUS        | W   | 0.138      | -            | -                | -                | -         |     0.70 | adamb, Jackinho, spooke, susp, ztr  |
|            6 |     3980 | 2024-02-27 | ex-Guild Eagles   | L   | 0.133      | -            | -                | -                | -         |    -2.21 | adamb, Jackinho, nilo, susp, ztr    |
|            5 |     4353 | 2024-02-11 | Apeks             | W   | 0.027      | -            | -                | -                | -         |     0.50 | adamb, Jackinho, nilo, susp, ztr    |
|            4 |     4358 | 2024-02-11 | ex-Sprout         | W   | 0.025      | -            | -                | -                | -         |     0.11 | adamb, Jackinho, nilo, susp, ztr    |
|            3 |     4365 | 2024-02-10 | FURIA             | W   | 0.020      | -            | -                | -                | -         |     0.61 | adamb, Jackinho, nilo, susp, ztr    |
|            2 |     4368 | 2024-02-10 | Apeks             | L   | 0.019      | -            | -                | -                | -         |    -0.24 | adamb, Jackinho, nilo, susp, ztr    |
|            1 |     4370 | 2024-02-10 | FURIA             | W   | 0.019      | -            | -                | -                | -         |     0.58 | adamb, Jackinho, nilo, susp, ztr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,443.60)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      0.579 | $5,000.00      | $2,896.53       |
| 2024-04-20 |      0.487 | $5,000.00      | $2,436.34       |
| 2024-04-07 |      0.400 | $6,110.00      | $2,441.45       |
| 2024-03-10 |      0.214 | $12,500.00     | $2,669.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
