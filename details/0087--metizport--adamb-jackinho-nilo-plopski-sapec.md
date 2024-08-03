### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  901.4<br />
<br />
Final Rank Value (901.4) = Starting Rank Value (901.7) + Head To Head Adjustments (-0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.382[<sup>2</sup>](#table1)
- Opponent Network: 0.188[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.7
- 400 + ( ( 0.245 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 901.7


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
|           61 |       66 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.07 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      169 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.66 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |      215 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.48 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      382 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.04 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      401 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.43 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      502 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.81 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      561 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.22 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      677 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.540 (0.235)    | 0 (0.000) |    11.67 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |     1702 | 2024-05-23 | Space             | L   | 0.718      | -            | -                | -                | -         |   -14.49 | abdi, adamb, Jackinho, nilo, Plopski  |
|           52 |     1808 | 2024-05-20 | Zero Tenacity     | L   | 0.700      | -            | -                | -                | -         |    -8.17 | adamb, Jackinho, nilo, Plopski, ztr   |
|           51 |     1859 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.687      | 0.500        | 0.204 (0.070)    | 0.502 (0.172)    | 0 (0.000) |    20.67 | adamb, Jackinho, nilo, Plopski, ztr   |
|           50 |     1945 | 2024-05-16 | Rare Atom         | W   | 0.672      | 0.500        | -                | 0.495 (0.166)    | 0 (0.000) |     4.23 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     2131 | 2024-05-11 | BetBoom           | L   | 0.639      | -            | -                | -                | -         |    -1.73 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2145 | 2024-05-10 | EYEBALLERS        | W   | 0.633      | 0.435        | -                | 0.528 (0.145)    | 0 (0.000) |     8.71 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2268 | 2024-05-04 | AMKAL             | L   | 0.591      | -            | -                | -                | -         |    -4.57 | adamb, Jackinho, nilo, susp, ztr      |
|           46 |     2284 | 2024-05-03 | Zero Tenacity     | W   | 0.585      | 0.435        | 0.137 (0.035)    | 1.000 (0.254)    | 0 (0.000) |    12.01 | adamb, Jackinho, nilo, susp, ztr      |
|           45 |     2304 | 2024-05-02 | Sangal            | W   | 0.579      | 0.435        | 0.219 (0.055)    | 0.823 (0.207)    | 0 (0.000) |    13.35 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2464 | 2024-04-25 | Nexus             | L   | 0.533      | -            | -                | -                | -         |   -10.89 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2506 | 2024-04-23 | Alliance          | W   | 0.519      | 0.384        | -                | 0.313 (0.062)    | 0 (0.000) |     6.62 | adamb, Jackinho, nilo, p1ke, susp     |
|           42 |     2616 | 2024-04-19 | FURIA             | L   | 0.492      | -            | -                | -                | -         |    -0.26 | adamb, Jackinho, Plopski, susp, ztr   |
|           41 |     2651 | 2024-04-18 | Imperial          | L   | 0.487      | -            | -                | -                | -         |    -2.15 | adamb, Jackinho, Plopski, susp, ztr   |
|           40 |     2931 | 2024-04-09 | ex-Guild Eagles   | L   | 0.426      | -            | -                | -                | -         |    -9.11 | adamb, Jackinho, nilo, susp, ztr      |
|           39 |     2946 | 2024-04-08 | Aurora            | L   | 0.421      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, nilo, susp, ztr      |
|           38 |     2957 | 2024-04-08 | 9 Pandas          | L   | 0.419      | -            | -                | -                | -         |    -5.72 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     2984 | 2024-04-07 | EYEBALLERS        | W   | 0.413      | 0.330        | -                | 0.528 (0.072)    | 0 (0.000) |     5.61 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     2993 | 2024-04-07 | Johnny Speeds     | W   | 0.411      | 0.330        | 0.122 (0.017)    | 0.930 (0.126)    | -         |    11.31 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3009 | 2024-04-06 | Young Gods        | W   | 0.405      | -            | -                | -                | -         |     2.96 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3063 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.392      | -            | -                | -                | -         |    -0.29 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3092 | 2024-04-03 | Monte             | W   | 0.387      | -            | -                | -                | -         |     7.21 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3101 | 2024-04-03 | FAVBET            | W   | 0.386      | -            | -                | -                | -         |     3.86 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3133 | 2024-04-02 | B8                | W   | 0.380      | 0.143        | 0.166 (0.009)    | -                | -         |     8.57 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3141 | 2024-04-02 | Aurora            | L   | 0.379      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3155 | 2024-04-01 | PARIVISION        | L   | 0.373      | -            | -                | -                | -         |    -2.95 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3222 | 2024-03-27 | Aurora            | L   | 0.341      | -            | -                | -                | -         |    -0.16 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3228 | 2024-03-27 | NAVI Junior       | W   | 0.340      | -            | -                | -                | -         |     2.37 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3426 | 2024-03-15 | kONO              | L   | 0.260      | -            | -                | -                | -         |    -5.39 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3463 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.252      | -            | -                | -                | -         |    -3.43 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3497 | 2024-03-13 | HEROIC            | L   | 0.246      | -            | -                | -                | -         |    -0.21 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3520 | 2024-03-12 | B8                | W   | 0.241      | 0.143        | 0.166 (0.006)    | -                | -         |     5.50 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3527 | 2024-03-12 | Apeks             | W   | 0.239      | -            | -                | -                | -         |     3.73 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3538 | 2024-03-11 | ex-Preasy         | W   | 0.234      | -            | -                | -                | -         |     2.57 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3549 | 2024-03-11 | ENCE              | L   | 0.233      | -            | -                | -                | -         |    -0.31 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3559 | 2024-03-10 | Spirit            | L   | 0.227      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3586 | 2024-03-09 | Monte             | W   | 0.220      | 0.535        | 0.060 (0.007)    | -                | -         |     4.33 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3591 | 2024-03-09 | EYEBALLERS        | L   | 0.219      | -            | -                | -                | -         |    -3.53 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3596 | 2024-03-09 | Lemondogs         | W   | 0.219      | -            | -                | -                | -         |     0.37 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3616 | 2024-03-08 | Secret            | W   | 0.212      | -            | -                | -                | -         |     0.73 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3657 | 2024-03-06 | Falcons           | W   | 0.201      | 0.535        | 0.225 (0.024)    | -                | -         |     6.00 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3738 | 2024-03-03 | The Chosen Few    | W   | 0.181      | -            | -                | -                | -         |     1.23 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3744 | 2024-03-03 | ILIN              | W   | 0.180      | -            | -                | -                | -         |     0.32 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3749 | 2024-03-03 | RUSH B            | W   | 0.180      | -            | -                | -                | -         |     2.40 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3760 | 2024-03-03 | ECLOT             | L   | 0.179      | -            | -                | -                | -         |    -0.81 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3808 | 2024-02-29 | Endpoint          | W   | 0.159      | -            | -                | -                | -         |     2.44 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3843 | 2024-02-27 | ex-Guild Eagles   | L   | 0.147      | -            | -                | -                | -         |    -2.85 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     4215 | 2024-02-11 | Apeks             | W   | 0.041      | -            | -                | -                | -         |     0.64 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     4220 | 2024-02-11 | ex-Sprout         | W   | 0.039      | -            | -                | -                | -         |     0.13 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4227 | 2024-02-10 | FURIA             | W   | 0.033      | -            | -                | -                | -         |     1.04 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4230 | 2024-02-10 | Apeks             | L   | 0.033      | -            | -                | -                | -         |    -0.52 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4232 | 2024-02-10 | FURIA             | W   | 0.033      | -            | -                | -                | -         |     1.01 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4267 | 2024-02-07 | ex-Sprout         | W   | 0.013      | -            | -                | -                | -         |     0.04 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4275 | 2024-02-06 | Into the Breach   | L   | 0.006      | -            | -                | -                | -         |    -0.16 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,131.59)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.647 | $2,000.00      | $1,293.29       |
| 2024-05-04 |      0.593 | $5,000.00      | $2,965.51       |
| 2024-04-20 |      0.501 | $5,000.00      | $2,505.32       |
| 2024-04-07 |      0.413 | $6,110.00      | $2,525.75       |
| 2024-03-10 |      0.227 | $12,500.00     | $2,841.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
