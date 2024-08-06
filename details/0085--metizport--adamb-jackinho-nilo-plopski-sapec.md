### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, Plopski, Sapec<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  922.5<br />
<br />
Final Rank Value (922.5) = Starting Rank Value (901.4) + Head To Head Adjustments (21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.409[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.4
- 400 + ( ( 0.244 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 901.4


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
|           62 |        0 | 2024-08-06 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.39 | adamb, Jackinho, nilo, Plopski, Sapec |
|           61 |        3 | 2024-08-06 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.42 | adamb, Jackinho, nilo, Plopski, Sapec |
|           60 |      148 | 2024-08-01 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | -                | 0.537 (0.077)    | 0 (0.000) |    13.87 | adamb, L00m1, nilo, Plopski, Sapec    |
|           59 |      157 | 2024-08-01 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -13.90 | adamb, Jackinho, nilo, Plopski, Sapec |
|           58 |      260 | 2024-07-30 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.61 | adamb, Jackinho, nilo, Plopski, Sapec |
|           57 |      307 | 2024-07-28 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -14.26 | adamb, Jackinho, nilo, Plopski, Sapec |
|           56 |      475 | 2024-07-23 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -17.35 | adamb, Jackinho, nilo, Plopski, Sapec |
|           55 |      493 | 2024-07-22 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.49 | adamb, Jackinho, nilo, Plopski, Sapec |
|           54 |      594 | 2024-07-19 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.96 | adamb, Jackinho, nilo, Plopski, Sapec |
|           53 |      653 | 2024-07-18 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -18.19 | adamb, Jackinho, nilo, Plopski, Sapec |
|           52 |      772 | 2024-07-16 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.502 (0.218)    | 0 (0.000) |    11.99 | adamb, Jackinho, nilo, Plopski, Sapec |
|           51 |     1836 | 2024-05-23 | Space             | L   | 0.699      | -            | -                | -                | -         |   -14.14 | abdi, adamb, Jackinho, nilo, Plopski  |
|           50 |     1942 | 2024-05-20 | Zero Tenacity     | L   | 0.681      | -            | -                | -                | -         |    -7.70 | adamb, Jackinho, nilo, Plopski, ztr   |
|           49 |     1994 | 2024-05-18 | Ninjas in Pyjamas | W   | 0.668      | 0.500        | 0.253 (0.085)    | 0.531 (0.177)    | 0 (0.000) |    20.40 | adamb, Jackinho, nilo, Plopski, ztr   |
|           48 |     2080 | 2024-05-16 | Rare Atom         | W   | 0.653      | 0.500        | -                | 0.426 (0.139)    | 0 (0.000) |     3.30 | adamb, Jackinho, nilo, Plopski, ztr   |
|           47 |     2266 | 2024-05-11 | BetBoom           | L   | 0.620      | -            | -                | -                | -         |    -1.68 | adamb, Jackinho, nilo, Plopski, ztr   |
|           46 |     2280 | 2024-05-10 | EYEBALLERS        | W   | 0.614      | 0.435        | -                | 0.488 (0.130)    | 0 (0.000) |     8.55 | adamb, Jackinho, nilo, Plopski, ztr   |
|           45 |     2404 | 2024-05-04 | AMKAL             | L   | 0.572      | -            | -                | -                | -         |    -4.38 | adamb, Jackinho, nilo, susp, ztr      |
|           44 |     2420 | 2024-05-03 | Zero Tenacity     | W   | 0.566      | 0.435        | 0.143 (0.035)    | 1.000 (0.246)    | 0 (0.000) |    11.89 | adamb, Jackinho, nilo, susp, ztr      |
|           43 |     2440 | 2024-05-02 | Sangal            | W   | 0.560      | 0.435        | 0.219 (0.053)    | 0.846 (0.206)    | 0 (0.000) |    13.17 | adamb, Jackinho, nilo, susp, ztr      |
|           42 |     2601 | 2024-04-25 | Nexus             | L   | 0.514      | -            | -                | -                | -         |   -10.43 | adamb, Jackinho, nilo, susp, ztr      |
|           41 |     2643 | 2024-04-23 | Alliance          | W   | 0.500      | -            | -                | -                | -         |     6.40 | adamb, Jackinho, nilo, p1ke, susp     |
|           40 |     2753 | 2024-04-19 | FURIA             | L   | 0.473      | -            | -                | -                | -         |    -0.24 | adamb, Jackinho, Plopski, susp, ztr   |
|           39 |     2788 | 2024-04-18 | Imperial          | L   | 0.468      | -            | -                | -                | -         |    -1.89 | adamb, Jackinho, Plopski, susp, ztr   |
|           38 |     3068 | 2024-04-09 | ex-Guild Eagles   | L   | 0.407      | -            | -                | -                | -         |    -8.70 | adamb, Jackinho, nilo, susp, ztr      |
|           37 |     3083 | 2024-04-08 | Aurora            | L   | 0.402      | -            | -                | -                | -         |    -0.22 | adamb, Jackinho, nilo, susp, ztr      |
|           36 |     3094 | 2024-04-08 | 9 Pandas          | L   | 0.400      | -            | -                | -                | -         |    -5.45 | adamb, Jackinho, nilo, susp, ztr      |
|           35 |     3121 | 2024-04-07 | EYEBALLERS        | W   | 0.394      | 0.330        | -                | 0.488 (0.064)    | -         |     5.43 | adamb, Jackinho, nilo, susp, ztr      |
|           34 |     3130 | 2024-04-07 | Johnny Speeds     | W   | 0.392      | 0.330        | 0.122 (0.016)    | 1.000 (0.130)    | -         |    10.88 | adamb, Jackinho, nilo, susp, ztr      |
|           33 |     3146 | 2024-04-06 | Young Gods        | W   | 0.386      | -            | -                | -                | -         |     2.87 | adamb, Jackinho, nilo, susp, ztr      |
|           32 |     3200 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.373      | -            | -                | -                | -         |    -0.18 | adamb, Jackinho, nilo, susp, ztr      |
|           31 |     3229 | 2024-04-03 | Monte             | W   | 0.368      | -            | -                | -                | -         |     6.77 | adamb, Jackinho, nilo, susp, ztr      |
|           30 |     3238 | 2024-04-03 | FAVBET            | W   | 0.367      | -            | -                | -                | -         |     3.73 | adamb, Jackinho, nilo, susp, ztr      |
|           29 |     3270 | 2024-04-02 | B8                | W   | 0.361      | 0.143        | 0.170 (0.009)    | -                | -         |     8.17 | adamb, Jackinho, nilo, susp, ztr      |
|           28 |     3278 | 2024-04-02 | Aurora            | L   | 0.360      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr      |
|           27 |     3292 | 2024-04-01 | PARIVISION        | L   | 0.354      | -            | -                | -                | -         |    -2.71 | adamb, Jackinho, nilo, susp, ztr      |
|           26 |     3360 | 2024-03-27 | Aurora            | L   | 0.322      | -            | -                | -                | -         |    -0.14 | adamb, Jackinho, nilo, susp, ztr      |
|           25 |     3366 | 2024-03-27 | NAVI Junior       | W   | 0.321      | -            | -                | -                | -         |     2.45 | adamb, Jackinho, nilo, susp, ztr      |
|           24 |     3569 | 2024-03-15 | kONO              | L   | 0.241      | -            | -                | -                | -         |    -4.92 | adamb, Jackinho, nilo, susp, ztr      |
|           23 |     3606 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.233      | -            | -                | -                | -         |    -3.13 | adamb, Jackinho, nilo, susp, ztr      |
|           22 |     3641 | 2024-03-13 | HEROIC            | L   | 0.227      | -            | -                | -                | -         |    -0.20 | adamb, Jackinho, nilo, susp, ztr      |
|           21 |     3664 | 2024-03-12 | B8                | W   | 0.221      | 0.143        | 0.170 (0.005)    | -                | -         |     5.08 | adamb, Jackinho, nilo, susp, ztr      |
|           20 |     3672 | 2024-03-12 | Apeks             | W   | 0.220      | -            | -                | -                | -         |     3.39 | adamb, Jackinho, nilo, susp, ztr      |
|           19 |     3683 | 2024-03-11 | ex-Preasy         | W   | 0.215      | -            | -                | -                | -         |     2.32 | adamb, Jackinho, nilo, susp, ztr      |
|           18 |     3694 | 2024-03-11 | ENCE              | L   | 0.214      | -            | -                | -                | -         |    -0.27 | adamb, Jackinho, nilo, susp, ztr      |
|           17 |     3704 | 2024-03-10 | Spirit            | L   | 0.208      | -            | -                | -                | -         |    -0.03 | adamb, Jackinho, nilo, susp, ztr      |
|           16 |     3730 | 2024-03-09 | Monte             | W   | 0.201      | 0.535        | 0.057 (0.006)    | -                | -         |     3.88 | adamb, Jackinho, nilo, susp, ztr      |
|           15 |     3736 | 2024-03-09 | EYEBALLERS        | L   | 0.200      | -            | -                | -                | -         |    -3.22 | adamb, Jackinho, nilo, susp, ztr      |
|           14 |     3741 | 2024-03-09 | Lemondogs         | W   | 0.200      | -            | -                | -                | -         |     0.34 | adamb, Jackinho, nilo, susp, ztr      |
|           13 |     3761 | 2024-03-08 | Secret            | W   | 0.193      | -            | -                | -                | -         |     0.67 | adamb, Jackinho, nilo, susp, ztr      |
|           12 |     3802 | 2024-03-06 | Falcons           | W   | 0.182      | 0.535        | 0.219 (0.021)    | -                | -         |     5.41 | adamb, Jackinho, nilo, susp, ztr      |
|           11 |     3883 | 2024-03-03 | The Chosen Few    | W   | 0.162      | -            | -                | -                | -         |     1.10 | adamb, Jackinho, nilo, susp, ztr      |
|           10 |     3889 | 2024-03-03 | ILIN              | W   | 0.161      | -            | -                | -                | -         |     0.29 | adamb, Jackinho, nilo, susp, ztr      |
|            9 |     3894 | 2024-03-03 | RUSH B            | W   | 0.161      | -            | -                | -                | -         |     2.24 | adamb, Jackinho, nilo, susp, ztr      |
|            8 |     3905 | 2024-03-03 | ECLOT             | L   | 0.160      | -            | -                | -                | -         |    -0.73 | adamb, Jackinho, nilo, susp, ztr      |
|            7 |     3953 | 2024-02-29 | Endpoint          | W   | 0.140      | -            | -                | -                | -         |     2.14 | adamb, Jackinho, nilo, susp, ztr      |
|            6 |     3988 | 2024-02-27 | ex-Guild Eagles   | L   | 0.128      | -            | -                | -                | -         |    -2.50 | adamb, Jackinho, nilo, susp, ztr      |
|            5 |     4361 | 2024-02-11 | Apeks             | W   | 0.022      | -            | -                | -                | -         |     0.34 | adamb, Jackinho, nilo, susp, ztr      |
|            4 |     4366 | 2024-02-11 | ex-Sprout         | W   | 0.020      | -            | -                | -                | -         |     0.06 | adamb, Jackinho, nilo, susp, ztr      |
|            3 |     4373 | 2024-02-10 | FURIA             | W   | 0.014      | -            | -                | -                | -         |     0.45 | adamb, Jackinho, nilo, susp, ztr      |
|            2 |     4376 | 2024-02-10 | Apeks             | L   | 0.014      | -            | -                | -                | -         |    -0.22 | adamb, Jackinho, nilo, susp, ztr      |
|            1 |     4378 | 2024-02-10 | FURIA             | W   | 0.013      | -            | -                | -                | -         |     0.42 | adamb, Jackinho, nilo, susp, ztr      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,549.15)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.628 | $2,000.00      | $1,255.23       |
| 2024-05-04 |      0.574 | $5,000.00      | $2,870.37       |
| 2024-04-20 |      0.482 | $5,000.00      | $2,410.19       |
| 2024-04-07 |      0.394 | $6,110.00      | $2,409.49       |
| 2024-03-10 |      0.208 | $12,500.00     | $2,603.88       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
