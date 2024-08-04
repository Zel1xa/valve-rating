### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  783.5<br />
<br />
Final Rank Value (783.5) = Starting Rank Value (836.4) + Head To Head Adjustments (-52.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.4
- 400 + ( ( 0.213 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 836.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |      146 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.510 (0.073)    | 0 (0.000) |    15.54 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      209 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.79 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      341 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.90 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      486 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.04 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      529 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.453 (0.151)    | 0 (0.000) |    23.89 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      572 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.354 (0.118)    | 0 (0.000) |    26.05 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      589 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.22 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      664 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.16 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      692 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.30 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      757 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.758 (0.253)    | 0 (0.000) |    25.08 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      765 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.56 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      784 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.08 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      827 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.30 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      858 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.18 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1099 | 2024-06-12 | Permitta          | L   | 0.849      | -            | -                | -                | -         |    -6.71 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1122 | 2024-06-11 | FAVBET            | L   | 0.842      | -            | -                | -                | -         |   -10.79 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1218 | 2024-06-09 | EYEBALLERS        | L   | 0.827      | -            | -                | -                | -         |    -7.49 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1243 | 2024-06-08 | Enterprise        | L   | 0.822      | -            | -                | -                | -         |    -8.15 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1318 | 2024-06-07 | Astralis Talent   | W   | 0.815      | -            | -                | -                | 0 (0.000) |    13.15 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1330 | 2024-06-07 | 9INE              | L   | 0.814      | -            | -                | -                | -         |    -8.19 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1356 | 2024-06-06 | 3DMAX             | L   | 0.810      | -            | -                | -                | -         |    -0.42 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1452 | 2024-06-05 | BLEED             | L   | 0.801      | -            | -                | -                | -         |    -0.76 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1692 | 2024-05-27 | The Prodigies     | L   | 0.742      | -            | -                | -                | -         |   -18.33 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1700 | 2024-05-27 | MOUZ NXT          | L   | 0.740      | -            | -                | -                | -         |    -4.05 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1735 | 2024-05-25 | Permitta          | L   | 0.727      | -            | -                | -                | -         |    -8.12 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1762 | 2024-05-23 | RUBY              | L   | 0.715      | -            | -                | -                | -         |    -6.54 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1877 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.696      | 0.435        | 0.031 (0.010)    | 0.560 (0.169)    | 0 (0.000) |    14.84 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1882 | 2024-05-20 | PERA              | L   | 0.695      | -            | -                | -                | -         |    -6.66 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     1979 | 2024-05-17 | Passion UA        | L   | 0.674      | -            | -                | -                | -         |    -4.55 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2076 | 2024-05-15 | Space             | L   | 0.659      | -            | -                | -                | -         |    -9.14 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2145 | 2024-05-13 | Sampi             | L   | 0.647      | -            | -                | -                | -         |    -7.03 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2355 | 2024-05-03 | ENCE Academy      | L   | 0.580      | -            | -                | -                | -         |   -11.49 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2400 | 2024-05-01 | Insilio           | L   | 0.567      | -            | -                | -                | -         |    -6.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2432 | 2024-04-30 | fnatic            | L   | 0.559      | -            | -                | -                | -         |    -0.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2436 | 2024-04-29 | Endpoint          | L   | 0.555      | -            | -                | -                | -         |    -7.26 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2441 | 2024-04-29 | VP.Prodigy        | L   | 0.554      | -            | -                | -                | -         |    -8.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2446 | 2024-04-29 | LEON              | W   | 0.554      | -            | -                | -                | 0 (0.000) |     5.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2451 | 2024-04-29 | Enterprise        | W   | 0.553      | 0.384        | 0.039 (0.008)    | 0.625 (0.133)    | 0 (0.000) |    10.04 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2467 | 2024-04-28 | brazylijski luz   | L   | 0.547      | -            | -                | -                | -         |    -8.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2535 | 2024-04-25 | Metizport         | W   | 0.529      | 0.384        | 0.037 (0.008)    | 0.417 (0.085)    | -         |    10.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2543 | 2024-04-25 | Grannys Knockers  | L   | 0.527      | -            | -                | -                | -         |   -10.26 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2564 | 2024-04-24 | AMKAL             | L   | 0.520      | -            | -                | -                | -         |    -2.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2582 | 2024-04-23 | Illuminar         | L   | 0.514      | -            | -                | -                | -         |   -13.65 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2595 | 2024-04-22 | Zero Tenacity     | L   | 0.507      | -            | -                | -                | -         |    -3.71 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2606 | 2024-04-21 | Young Ninjas      | W   | 0.502      | -            | -                | -                | -         |     6.00 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2610 | 2024-04-21 | PARIVISION        | L   | 0.501      | -            | -                | -                | -         |    -3.99 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2646 | 2024-04-20 | Permitta          | W   | 0.494      | 0.500        | -                | 0.876 (0.216)    | -         |    10.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2716 | 2024-04-18 | Young Ninjas      | L   | 0.482      | -            | -                | -                | -         |    -9.47 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2747 | 2024-04-18 | Enterprise        | L   | 0.480      | -            | -                | -                | -         |    -6.30 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     2945 | 2024-04-10 | B8                | W   | 0.427      | 0.384        | 0.165 (0.027)    | 0.912 (0.150)    | -         |    10.21 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3089 | 2024-04-05 | SINNERS           | L   | 0.395      | -            | -                | -                | -         |    -2.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3231 | 2024-04-01 | Sashi             | W   | 0.367      | 0.384        | 0.184 (0.026)    | 0.962 (0.136)    | -         |     9.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3340 | 2024-03-25 | Sashi             | L   | 0.322      | -            | -                | -                | -         |    -1.65 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3601 | 2024-03-12 | Nemiga            | W   | 0.236      | 0.372        | 0.317 (0.028)    | -                | -         |     6.33 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3623 | 2024-03-11 | RUBY              | W   | 0.229      | 0.372        | 0.095 (0.008)    | -                | -         |     4.56 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3663 | 2024-03-09 | INGLORIOUS        | W   | 0.215      | -            | -                | -                | -         |     1.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3687 | 2024-03-08 | FAVBET            | W   | 0.209      | -            | -                | -                | -         |     2.61 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3833 | 2024-03-03 | TSM               | L   | 0.175      | -            | -                | -                | -         |    -3.94 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4081 | 2024-02-20 | ex-Guild Eagles   | L   | 0.094      | -            | -                | -                | -         |    -1.58 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4102 | 2024-02-19 | Monte             | L   | 0.089      | -            | -                | -                | -         |    -0.81 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4108 | 2024-02-19 | Astralis          | L   | 0.088      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,458.17)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.575 | $1,000.00      | $575.00         |
| 2024-03-25 |      0.322 | $4,300.00      | $1,383.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
