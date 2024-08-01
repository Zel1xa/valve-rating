### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  805.1<br />
<br />
Final Rank Value (805.1) = Starting Rank Value (842.6) + Head To Head Adjustments (-37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 842.6
- 400 + ( ( 0.215 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 842.6


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
|           62 |       64 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.51 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           61 |      127 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -5.24 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      260 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.86 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      407 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.29 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      452 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.452 (0.151)    | 0 (0.000) |    23.16 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      499 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.039 (0.013)    | 0.347 (0.116)    | 0 (0.000) |    25.41 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      515 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.64 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           55 |      591 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           54 |      621 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.55 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           53 |      691 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.038 (0.013)    | 0.768 (0.256)    | 0 (0.000) |    24.21 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      698 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -11.11 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      705 | 2024-07-14 | Rebels            | W   | 1.000      | 0.143        | -                | 0.635 (0.091)    | 0 (0.000) |    25.43 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      720 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.13 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      762 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |    -9.85 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      793 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.13 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1023 | 2024-06-12 | Permitta          | L   | 0.866      | -            | -                | -                | -         |    -6.95 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1047 | 2024-06-11 | FAVBET            | L   | 0.860      | -            | -                | -                | -         |   -10.85 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1145 | 2024-06-09 | EYEBALLERS        | L   | 0.844      | -            | -                | -                | -         |    -7.59 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1171 | 2024-06-08 | Enterprise        | L   | 0.840      | -            | -                | -                | -         |    -8.42 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1253 | 2024-06-07 | Astralis Talent   | W   | 0.833      | -            | -                | -                | 0 (0.000) |    13.66 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1265 | 2024-06-07 | 9INE              | L   | 0.832      | -            | -                | -                | -         |    -7.65 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1293 | 2024-06-06 | 3DMAX             | L   | 0.827      | -            | -                | -                | -         |    -0.45 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1392 | 2024-06-05 | BLEED             | L   | 0.818      | -            | -                | -                | -         |    -0.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1633 | 2024-05-27 | The Prodigies     | L   | 0.760      | -            | -                | -                | -         |   -18.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1642 | 2024-05-27 | MOUZ NXT          | L   | 0.757      | -            | -                | -                | -         |    -4.20 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1678 | 2024-05-25 | Permitta          | L   | 0.745      | -            | -                | -                | -         |    -8.50 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1705 | 2024-05-23 | RUBY              | L   | 0.733      | -            | -                | -                | -         |    -6.49 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1837 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.713      | 0.435        | 0.032 (0.010)    | 0.563 (0.175)    | 0 (0.000) |    14.87 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1843 | 2024-05-20 | PERA              | L   | 0.713      | -            | -                | -                | -         |    -6.88 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     1948 | 2024-05-17 | Passion UA        | L   | 0.691      | -            | -                | -                | -         |    -4.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2051 | 2024-05-15 | Space             | L   | 0.677      | -            | -                | -                | -         |    -9.36 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2123 | 2024-05-13 | Sampi             | L   | 0.665      | -            | -                | -                | -         |    -7.47 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2335 | 2024-05-03 | ENCE Academy      | L   | 0.598      | -            | -                | -                | -         |   -12.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2382 | 2024-05-01 | Insilio           | L   | 0.585      | -            | -                | -                | -         |    -6.79 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2415 | 2024-04-30 | fnatic            | L   | 0.577      | -            | -                | -                | -         |    -0.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2419 | 2024-04-29 | Endpoint          | L   | 0.573      | -            | -                | -                | -         |    -7.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2424 | 2024-04-29 | VP.Prodigy        | L   | 0.572      | -            | -                | -                | -         |    -8.44 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2429 | 2024-04-29 | LEON              | W   | 0.571      | -            | -                | -                | 0 (0.000) |     5.38 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2434 | 2024-04-29 | Enterprise        | W   | 0.571      | 0.384        | 0.040 (0.009)    | 0.622 (0.136)    | -         |    10.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2450 | 2024-04-28 | brazylijski luz   | L   | 0.564      | -            | -                | -                | -         |    -8.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2518 | 2024-04-25 | Metizport         | W   | 0.546      | 0.384        | 0.038 (0.008)    | 0.424 (0.089)    | -         |    11.16 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2526 | 2024-04-25 | Grannys Knockers  | L   | 0.545      | -            | -                | -                | -         |   -10.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2547 | 2024-04-24 | AMKAL             | L   | 0.538      | -            | -                | -                | -         |    -2.73 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2567 | 2024-04-23 | Illuminar         | L   | 0.531      | -            | -                | -                | -         |   -14.16 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2581 | 2024-04-22 | Zero Tenacity     | L   | 0.525      | -            | -                | -                | -         |    -3.96 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2593 | 2024-04-21 | Young Ninjas      | W   | 0.520      | -            | -                | -                | -         |     6.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2597 | 2024-04-21 | PARIVISION        | L   | 0.519      | -            | -                | -                | -         |    -4.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2635 | 2024-04-20 | Permitta          | W   | 0.512      | 0.500        | -                | 0.801 (0.205)    | -         |    10.29 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2707 | 2024-04-18 | Young Ninjas      | L   | 0.500      | -            | -                | -                | -         |    -9.76 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2738 | 2024-04-18 | Enterprise        | L   | 0.498      | -            | -                | -                | -         |    -6.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     2939 | 2024-04-10 | B8                | W   | 0.445      | 0.384        | 0.168 (0.029)    | 0.878 (0.150)    | -         |    10.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3083 | 2024-04-05 | SINNERS           | L   | 0.413      | -            | -                | -                | -         |    -3.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3233 | 2024-04-01 | Sashi             | W   | 0.384      | 0.384        | 0.186 (0.028)    | 0.970 (0.143)    | -         |    10.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3347 | 2024-03-25 | Sashi             | L   | 0.339      | -            | -                | -                | -         |    -1.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3613 | 2024-03-12 | Nemiga            | W   | 0.253      | 0.372        | 0.324 (0.031)    | -                | -         |     6.85 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3635 | 2024-03-11 | RUBY              | W   | 0.246      | 0.372        | 0.097 (0.009)    | -                | -         |     4.99 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3676 | 2024-03-09 | INGLORIOUS        | W   | 0.233      | -            | -                | -                | -         |     1.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3700 | 2024-03-08 | FAVBET            | W   | 0.226      | -            | -                | -                | -         |     2.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3851 | 2024-03-03 | TSM               | L   | 0.193      | -            | -                | -                | -         |    -4.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4109 | 2024-02-20 | ex-Guild Eagles   | L   | 0.112      | -            | -                | -                | -         |    -1.86 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4130 | 2024-02-19 | Monte             | L   | 0.107      | -            | -                | -                | -         |    -0.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4136 | 2024-02-19 | Astralis          | L   | 0.105      | -            | -                | -                | -         |    -0.03 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,552.39)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.593 | $1,000.00      | $592.78         |
| 2024-03-25 |      0.339 | $4,300.00      | $1,459.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
