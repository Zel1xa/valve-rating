### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  907.5<br />
<br />
Final Rank Value (907.5) = Starting Rank Value (902.3) + Head To Head Adjustments (5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.3
- 400 + ( ( 0.246 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 902.3


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
|           61 |       99 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.12 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      203 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.60 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |      249 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.51 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      417 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.62 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      435 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.91 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      536 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.58 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      596 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -18.50 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      715 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    11.62 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |     1778 | 2024-05-23 | Space             | L   | 0.712      | -            | -                | -                | -         |   -14.47 | abdi, adamb, Jackinho, nilo, Plopski  |
|           52 |     1884 | 2024-05-20 | Zero Tenacity     | L   | 0.695      | -            | -                | -                | -         |    -8.04 | adamb, Jackinho, nilo, Plopski, ztr   |
|           51 |     1936 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.682      | 0.500        | 0.255 (0.087)    | 0.553 (0.188)    | 0 (0.000) |    20.80 | adamb, Jackinho, nilo, Plopski, ztr   |
|           50 |     2022 | 2024-05-16 | Rare Atom         | W   | 0.667      | 0.500        | -                | 0.480 (0.160)    | 0 (0.000) |     4.26 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     2208 | 2024-05-11 | BetBoom           | L   | 0.633      | -            | -                | -                | -         |    -1.71 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2222 | 2024-05-10 | EYEBALLERS        | W   | 0.627      | 0.435        | -                | 0.510 (0.139)    | 0 (0.000) |     8.64 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2346 | 2024-05-04 | AMKAL             | L   | 0.586      | -            | -                | -                | -         |    -4.53 | adamb, Jackinho, nilo, susp, ztr      |
|           46 |     2362 | 2024-05-03 | Zero Tenacity     | W   | 0.580      | 0.435        | 0.137 (0.034)    | 1.000 (0.252)    | 0 (0.000) |    11.97 | adamb, Jackinho, nilo, susp, ztr      |
|           45 |     2382 | 2024-05-02 | Sangal            | W   | 0.574      | 0.435        | 0.219 (0.055)    | 0.861 (0.215)    | 0 (0.000) |    13.28 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2543 | 2024-04-25 | Nexus             | L   | 0.528      | -            | -                | -                | -         |   -10.84 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2585 | 2024-04-23 | Alliance          | W   | 0.514      | 0.384        | -                | 0.300 (0.059)    | 0 (0.000) |     6.51 | adamb, Jackinho, nilo, p1ke, susp     |
|           42 |     2695 | 2024-04-19 | FURIA             | L   | 0.487      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, Plopski, susp, ztr   |
|           41 |     2730 | 2024-04-18 | Imperial          | L   | 0.481      | -            | -                | -                | -         |    -1.88 | adamb, Jackinho, Plopski, susp, ztr   |
|           40 |     3010 | 2024-04-09 | ex-Guild Eagles   | L   | 0.420      | -            | -                | -                | -         |    -9.02 | adamb, Jackinho, nilo, susp, ztr      |
|           39 |     3025 | 2024-04-08 | Aurora            | L   | 0.415      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, nilo, susp, ztr      |
|           38 |     3036 | 2024-04-08 | 9 Pandas          | L   | 0.414      | -            | -                | -                | -         |    -5.61 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3063 | 2024-04-07 | EYEBALLERS        | W   | 0.408      | 0.330        | -                | 0.510 (0.069)    | 0 (0.000) |     5.55 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3072 | 2024-04-07 | Johnny Speeds     | W   | 0.406      | 0.330        | 0.122 (0.016)    | 0.902 (0.121)    | -         |    11.15 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3088 | 2024-04-06 | Young Gods        | W   | 0.399      | -            | -                | -                | -         |     2.92 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3142 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.387      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3171 | 2024-04-03 | Monte             | W   | 0.381      | -            | -                | -                | -         |     7.04 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3180 | 2024-04-03 | FAVBET            | W   | 0.380      | -            | -                | -                | -         |     3.81 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3212 | 2024-04-02 | B8                | W   | 0.375      | 0.143        | 0.165 (0.009)    | -                | -         |     8.42 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3220 | 2024-04-02 | Aurora            | L   | 0.374      | -            | -                | -                | -         |    -0.19 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3234 | 2024-04-01 | PARIVISION        | L   | 0.368      | -            | -                | -                | -         |    -2.95 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3302 | 2024-03-27 | Aurora            | L   | 0.335      | -            | -                | -                | -         |    -0.16 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3308 | 2024-03-27 | NAVI Junior       | W   | 0.335      | -            | -                | -                | -         |     2.33 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3511 | 2024-03-15 | kONO              | L   | 0.254      | -            | -                | -                | -         |    -5.28 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3548 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.247      | -            | -                | -                | -         |    -3.36 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3583 | 2024-03-13 | HEROIC            | L   | 0.241      | -            | -                | -                | -         |    -0.21 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3606 | 2024-03-12 | B8                | W   | 0.235      | 0.143        | 0.165 (0.006)    | -                | -         |     5.36 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3614 | 2024-03-12 | Apeks             | W   | 0.234      | -            | -                | -                | -         |     3.63 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3625 | 2024-03-11 | ex-Preasy         | W   | 0.228      | -            | -                | -                | -         |     2.49 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3636 | 2024-03-11 | ENCE              | L   | 0.227      | -            | -                | -                | -         |    -0.31 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3646 | 2024-03-10 | Spirit            | L   | 0.222      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3672 | 2024-03-09 | Monte             | W   | 0.214      | 0.535        | 0.058 (0.007)    | -                | -         |     4.17 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3678 | 2024-03-09 | EYEBALLERS        | L   | 0.214      | -            | -                | -                | -         |    -3.47 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3683 | 2024-03-09 | Lemondogs         | W   | 0.214      | -            | -                | -                | -         |     0.36 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3703 | 2024-03-08 | Secret            | W   | 0.207      | -            | -                | -                | -         |     0.71 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3744 | 2024-03-06 | Falcons           | W   | 0.195      | 0.535        | 0.224 (0.023)    | -                | -         |     5.82 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3825 | 2024-03-03 | The Chosen Few    | W   | 0.175      | -            | -                | -                | -         |     1.19 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3831 | 2024-03-03 | ILIN              | W   | 0.175      | -            | -                | -                | -         |     0.31 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3836 | 2024-03-03 | RUSH B            | W   | 0.175      | -            | -                | -                | -         |     2.41 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3847 | 2024-03-03 | ECLOT             | L   | 0.173      | -            | -                | -                | -         |    -0.80 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3895 | 2024-02-29 | Endpoint          | W   | 0.154      | -            | -                | -                | -         |     2.33 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3930 | 2024-02-27 | ex-Guild Eagles   | L   | 0.141      | -            | -                | -                | -         |    -2.76 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     4303 | 2024-02-11 | Apeks             | W   | 0.035      | -            | -                | -                | -         |     0.55 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     4308 | 2024-02-11 | ex-Sprout         | W   | 0.033      | -            | -                | -                | -         |     0.11 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4315 | 2024-02-10 | FURIA             | W   | 0.028      | -            | -                | -                | -         |     0.87 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4318 | 2024-02-10 | Apeks             | L   | 0.027      | -            | -                | -                | -         |    -0.43 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4320 | 2024-02-10 | FURIA             | W   | 0.027      | -            | -                | -                | -         |     0.84 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4355 | 2024-02-07 | ex-Sprout         | W   | 0.007      | -            | -                | -                | -         |     0.02 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4363 | 2024-02-06 | Into the Breach   | L   | 0.001      | -            | -                | -                | -         |    -0.01 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,963.66)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.641 | $2,000.00      | $1,282.31       |
| 2024-05-04 |      0.588 | $5,000.00      | $2,938.08       |
| 2024-04-20 |      0.496 | $5,000.00      | $2,477.89       |
| 2024-04-07 |      0.408 | $6,110.00      | $2,492.23       |
| 2024-03-10 |      0.222 | $12,500.00     | $2,773.15       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
