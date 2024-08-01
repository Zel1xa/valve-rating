### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  903.8<br />
<br />
Final Rank Value (903.8) = Starting Rank Value (905.4) + Head To Head Adjustments (-1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.184[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.4
- 400 + ( ( 0.245 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 905.4


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
|           67 |        0 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.10 | adamb, Jackinho, nilo, Plopski, Sapec |
|           66 |      106 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.64 | adamb, Jackinho, nilo, Plopski, Sapec |
|           65 |      153 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.50 | adamb, Jackinho, nilo, Plopski, Sapec |
|           64 |      321 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -16.61 | adamb, Jackinho, nilo, Plopski, Sapec |
|           63 |      340 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.71 | adamb, Jackinho, nilo, Plopski, Sapec |
|           62 |      445 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.77 | adamb, Jackinho, nilo, Plopski, Sapec |
|           61 |      508 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -26.34 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      629 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.555 (0.241)    | 0 (0.000) |    12.68 | adamb, Jackinho, nilo, Plopski, Sapec |
|           59 |     1707 | 2024-05-23 | Space             | L   | 0.732      | -            | -                | -                | -         |   -14.75 | abdi, adamb, Jackinho, nilo, Plopski  |
|           58 |     1830 | 2024-05-20 | Zero Tenacity     | L   | 0.715      | -            | -                | -                | -         |    -8.74 | adamb, Jackinho, nilo, Plopski, ztr   |
|           57 |     1890 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.702      | 0.500        | 0.207 (0.073)    | 0.409 (0.143)    | 0 (0.000) |    20.38 | adamb, Jackinho, nilo, Plopski, ztr   |
|           56 |     1977 | 2024-05-16 | Rare Atom         | W   | 0.687      | 0.500        | -                | 0.436 (0.150)    | 0 (0.000) |     3.40 | adamb, Jackinho, nilo, Plopski, ztr   |
|           55 |     2172 | 2024-05-11 | BetBoom           | L   | 0.653      | -            | -                | -                | -         |    -1.73 | adamb, Jackinho, nilo, Plopski, ztr   |
|           54 |     2186 | 2024-05-10 | EYEBALLERS        | W   | 0.647      | 0.435        | -                | 0.513 (0.144)    | 0 (0.000) |     8.94 | adamb, Jackinho, nilo, Plopski, ztr   |
|           53 |     2312 | 2024-05-04 | AMKAL             | L   | 0.606      | -            | -                | -                | -         |    -4.67 | adamb, Jackinho, nilo, susp, ztr      |
|           52 |     2328 | 2024-05-03 | Zero Tenacity     | W   | 0.600      | 0.435        | 0.139 (0.036)    | 1.000 (0.261)    | 0 (0.000) |    12.21 | adamb, Jackinho, nilo, susp, ztr      |
|           51 |     2349 | 2024-05-02 | Sangal            | W   | 0.594      | 0.435        | 0.221 (0.057)    | 0.823 (0.212)    | 0 (0.000) |    13.56 | adamb, Jackinho, nilo, susp, ztr      |
|           50 |     2512 | 2024-04-25 | Nexus             | L   | 0.548      | -            | -                | -                | -         |   -11.19 | adamb, Jackinho, nilo, susp, ztr      |
|           49 |     2556 | 2024-04-23 | Alliance          | W   | 0.534      | 0.384        | -                | 0.319 (0.066)    | 0 (0.000) |     6.79 | adamb, Jackinho, nilo, p1ke, susp     |
|           48 |     2671 | 2024-04-19 | FURIA             | L   | 0.507      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, Plopski, susp, ztr   |
|           47 |     2707 | 2024-04-18 | Imperial          | L   | 0.501      | -            | -                | -                | -         |    -1.90 | adamb, Jackinho, Plopski, susp, ztr   |
|           46 |     2990 | 2024-04-09 | ex-Guild Eagles   | L   | 0.440      | -            | -                | -                | -         |    -9.34 | adamb, Jackinho, nilo, susp, ztr      |
|           45 |     3005 | 2024-04-08 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -0.25 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     3016 | 2024-04-08 | 9 Pandas          | L   | 0.434      | -            | -                | -                | -         |    -5.86 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     3043 | 2024-04-07 | EYEBALLERS        | W   | 0.428      | 0.330        | -                | 0.513 (0.072)    | 0 (0.000) |     5.84 | adamb, Jackinho, nilo, susp, ztr      |
|           42 |     3052 | 2024-04-07 | Johnny Speeds     | W   | 0.426      | 0.330        | 0.124 (0.017)    | 0.818 (0.115)    | -         |    11.77 | adamb, Jackinho, nilo, susp, ztr      |
|           41 |     3068 | 2024-04-06 | Young Gods        | W   | 0.419      | -            | -                | -                | -         |     3.09 | adamb, Jackinho, nilo, susp, ztr      |
|           40 |     3123 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.407      | -            | -                | -                | -         |    -0.57 | adamb, Jackinho, nilo, susp, ztr      |
|           39 |     3153 | 2024-04-03 | Monte             | W   | 0.402      | -            | -                | -                | -         |     7.68 | adamb, Jackinho, nilo, susp, ztr      |
|           38 |     3166 | 2024-04-03 | FAVBET            | W   | 0.400      | -            | -                | -                | -         |     4.06 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3200 | 2024-04-02 | B8                | W   | 0.395      | 0.143        | 0.168 (0.009)    | -                | -         |     8.99 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3208 | 2024-04-02 | Aurora            | L   | 0.394      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3222 | 2024-04-01 | PARIVISION        | L   | 0.388      | -            | -                | -                | -         |    -3.14 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3291 | 2024-03-27 | Aurora            | L   | 0.355      | -            | -                | -                | -         |    -0.16 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3297 | 2024-03-27 | NAVI Junior       | W   | 0.355      | -            | -                | -                | -         |     2.49 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3504 | 2024-03-15 | kONO              | L   | 0.274      | -            | -                | -                | -         |    -5.61 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3545 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.267      | -            | -                | -                | -         |    -3.62 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3580 | 2024-03-13 | HEROIC            | L   | 0.261      | -            | -                | -                | -         |    -0.22 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3604 | 2024-03-12 | B8                | W   | 0.255      | 0.143        | 0.168 (0.006)    | -                | -         |     5.90 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3612 | 2024-03-12 | Apeks             | W   | 0.254      | -            | -                | -                | -         |     4.11 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3623 | 2024-03-11 | ex-Preasy         | W   | 0.248      | -            | -                | -                | -         |     2.83 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3634 | 2024-03-11 | ENCE              | L   | 0.247      | -            | -                | -                | -         |    -0.31 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3644 | 2024-03-10 | Spirit            | L   | 0.242      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3672 | 2024-03-09 | Monte             | W   | 0.235      | 0.535        | 0.062 (0.008)    | -                | -         |     4.75 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3677 | 2024-03-09 | EYEBALLERS        | L   | 0.234      | -            | -                | -                | -         |    -3.71 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3682 | 2024-03-09 | Lemondogs         | W   | 0.234      | -            | -                | -                | -         |     0.39 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3702 | 2024-03-08 | Secret            | W   | 0.227      | -            | -                | -                | -         |     0.79 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3743 | 2024-03-06 | Falcons           | W   | 0.215      | 0.535        | 0.206 (0.024)    | -                | -         |     6.46 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3829 | 2024-03-03 | The Chosen Few    | W   | 0.195      | -            | -                | -                | -         |     1.35 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3835 | 2024-03-03 | ILIN              | W   | 0.195      | -            | -                | -                | -         |     0.35 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3840 | 2024-03-03 | RUSH B            | W   | 0.195      | -            | -                | -                | -         |     2.58 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3851 | 2024-03-03 | ECLOT             | L   | 0.194      | -            | -                | -                | -         |    -1.45 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3900 | 2024-02-29 | Endpoint          | W   | 0.174      | -            | -                | -                | -         |     2.82 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3936 | 2024-02-27 | ex-Guild Eagles   | L   | 0.161      | -            | -                | -                | -         |    -3.08 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     4184 | 2024-02-16 | ex-Anonymo        | L   | 0.091      | -            | -                | -                | -         |    -2.60 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     4325 | 2024-02-11 | Apeks             | W   | 0.055      | -            | -                | -                | -         |     0.91 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     4326 | 2024-02-11 | Alliance          | L   | 0.055      | -            | -                | -                | -         |    -1.00 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     4331 | 2024-02-11 | ex-Sprout         | W   | 0.054      | -            | -                | -                | -         |     0.18 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     4338 | 2024-02-10 | FURIA             | W   | 0.048      | -            | -                | -                | -         |     1.50 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     4341 | 2024-02-10 | Apeks             | L   | 0.047      | -            | -                | -                | -         |    -0.72 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     4343 | 2024-02-10 | FURIA             | W   | 0.047      | -            | -                | -                | -         |     1.47 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     4379 | 2024-02-07 | ex-Sprout         | W   | 0.027      | -            | -                | -                | -         |     0.09 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4387 | 2024-02-06 | Into the Breach   | L   | 0.021      | -            | -                | -                | -         |    -0.55 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4400 | 2024-02-05 | TSM               | L   | 0.013      | -            | -                | -                | -         |    -0.33 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4407 | 2024-02-04 | 500               | L   | 0.009      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4411 | 2024-02-04 | TMVG              | W   | 0.008      | -            | -                | -                | -         |     0.02 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4424 | 2024-02-04 | DUSTY             | W   | 0.006      | -            | -                | -                | -         |     0.04 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,580.82)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.661 | $2,000.00      | $1,322.64       |
| 2024-05-04 |      0.608 | $5,000.00      | $3,038.89       |
| 2024-04-20 |      0.516 | $5,000.00      | $2,578.70       |
| 2024-04-07 |      0.428 | $6,110.00      | $2,615.42       |
| 2024-03-10 |      0.242 | $12,500.00     | $3,025.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
