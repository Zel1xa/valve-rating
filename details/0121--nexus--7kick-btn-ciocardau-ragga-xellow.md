### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  805.0<br />
<br />
Final Rank Value (805.0) = Starting Rank Value (842.6) + Head To Head Adjustments (-37.6)<br />

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
|           63 |       61 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.52 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           62 |      125 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -5.24 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           61 |      258 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.86 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      405 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      450 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.452 (0.151)    | 0 (0.000) |    23.08 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      497 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.039 (0.013)    | 0.347 (0.116)    | 0 (0.000) |    25.40 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      513 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.64 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           56 |      589 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           55 |      619 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.55 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           54 |      689 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.038 (0.013)    | 0.768 (0.256)    | 0 (0.000) |    24.20 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           53 |      696 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -11.11 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      703 | 2024-07-14 | Rebels            | W   | 1.000      | 0.143        | -                | 0.635 (0.091)    | 0 (0.000) |    25.43 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      718 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.14 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      760 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |    -9.85 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      791 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.13 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |     1021 | 2024-06-12 | Permitta          | L   | 0.867      | -            | -                | -                | -         |    -6.92 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           47 |     1045 | 2024-06-11 | FAVBET            | L   | 0.860      | -            | -                | -                | -         |   -10.85 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1143 | 2024-06-09 | EYEBALLERS        | L   | 0.845      | -            | -                | -                | -         |    -7.59 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1169 | 2024-06-08 | Enterprise        | L   | 0.840      | -            | -                | -                | -         |    -8.42 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1251 | 2024-06-07 | Astralis Talent   | W   | 0.833      | -            | -                | -                | 0 (0.000) |    13.67 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1263 | 2024-06-07 | 9INE              | L   | 0.832      | -            | -                | -                | -         |    -7.66 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1291 | 2024-06-06 | 3DMAX             | L   | 0.828      | -            | -                | -                | -         |    -0.45 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1390 | 2024-06-05 | BLEED             | L   | 0.819      | -            | -                | -                | -         |    -0.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1631 | 2024-05-27 | The Prodigies     | L   | 0.760      | -            | -                | -                | -         |   -18.76 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1640 | 2024-05-27 | MOUZ NXT          | L   | 0.758      | -            | -                | -                | -         |    -4.20 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1676 | 2024-05-25 | Permitta          | L   | 0.745      | -            | -                | -                | -         |    -8.46 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1703 | 2024-05-23 | RUBY              | L   | 0.733      | -            | -                | -                | -         |    -6.48 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1835 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.714      | 0.435        | 0.032 (0.010)    | 0.563 (0.175)    | 0 (0.000) |    14.88 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1841 | 2024-05-20 | PERA              | L   | 0.713      | -            | -                | -                | -         |    -6.88 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1946 | 2024-05-17 | Passion UA        | L   | 0.692      | -            | -                | -                | -         |    -4.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2049 | 2024-05-15 | Space             | L   | 0.677      | -            | -                | -                | -         |    -9.37 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2121 | 2024-05-13 | Sampi             | L   | 0.665      | -            | -                | -                | -         |    -7.47 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2333 | 2024-05-03 | ENCE Academy      | L   | 0.598      | -            | -                | -                | -         |   -12.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           30 |     2380 | 2024-05-01 | Insilio           | L   | 0.585      | -            | -                | -                | -         |    -6.79 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2413 | 2024-04-30 | fnatic            | L   | 0.578      | -            | -                | -                | -         |    -0.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2417 | 2024-04-29 | Endpoint          | L   | 0.573      | -            | -                | -                | -         |    -7.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2422 | 2024-04-29 | VP.Prodigy        | L   | 0.572      | -            | -                | -                | -         |    -8.44 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2427 | 2024-04-29 | LEON              | W   | 0.572      | -            | -                | -                | 0 (0.000) |     5.39 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2432 | 2024-04-29 | Enterprise        | W   | 0.571      | 0.384        | 0.040 (0.009)    | 0.622 (0.137)    | -         |    10.15 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2448 | 2024-04-28 | brazylijski luz   | L   | 0.565      | -            | -                | -                | -         |    -8.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2516 | 2024-04-25 | Metizport         | W   | 0.547      | 0.384        | 0.038 (0.008)    | 0.425 (0.089)    | -         |    11.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2524 | 2024-04-25 | Grannys Knockers  | L   | 0.545      | -            | -                | -                | -         |   -10.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2545 | 2024-04-24 | AMKAL             | L   | 0.538      | -            | -                | -                | -         |    -2.73 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2565 | 2024-04-23 | Illuminar         | L   | 0.532      | -            | -                | -                | -         |   -14.16 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2579 | 2024-04-22 | Zero Tenacity     | L   | 0.525      | -            | -                | -                | -         |    -3.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2591 | 2024-04-21 | Young Ninjas      | W   | 0.520      | -            | -                | -                | -         |     6.29 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2595 | 2024-04-21 | PARIVISION        | L   | 0.519      | -            | -                | -                | -         |    -4.30 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2633 | 2024-04-20 | Permitta          | W   | 0.512      | 0.500        | -                | 0.801 (0.205)    | -         |    10.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2705 | 2024-04-18 | Young Ninjas      | L   | 0.500      | -            | -                | -                | -         |    -9.76 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2736 | 2024-04-18 | Enterprise        | L   | 0.498      | -            | -                | -                | -         |    -6.75 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2937 | 2024-04-10 | B8                | W   | 0.446      | 0.384        | 0.168 (0.029)    | 0.878 (0.150)    | -         |    10.67 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3081 | 2024-04-05 | SINNERS           | L   | 0.413      | -            | -                | -                | -         |    -3.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3231 | 2024-04-01 | Sashi             | W   | 0.385      | 0.384        | 0.187 (0.028)    | 0.970 (0.143)    | -         |    10.06 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3345 | 2024-03-25 | Sashi             | L   | 0.340      | -            | -                | -                | -         |    -1.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3611 | 2024-03-12 | Nemiga            | W   | 0.254      | 0.372        | 0.324 (0.031)    | -                | -         |     6.86 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3633 | 2024-03-11 | RUBY              | W   | 0.247      | 0.372        | 0.097 (0.009)    | -                | -         |     4.99 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3674 | 2024-03-09 | INGLORIOUS        | W   | 0.233      | -            | -                | -                | -         |     1.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3698 | 2024-03-08 | FAVBET            | W   | 0.227      | -            | -                | -                | -         |     2.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3849 | 2024-03-03 | TSM               | L   | 0.193      | -            | -                | -                | -         |    -4.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     4107 | 2024-02-20 | ex-Guild Eagles   | L   | 0.112      | -            | -                | -                | -         |    -1.87 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4128 | 2024-02-19 | Monte             | L   | 0.107      | -            | -                | -                | -         |    -0.94 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4134 | 2024-02-19 | Astralis          | L   | 0.106      | -            | -                | -                | -         |    -0.03 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4442 | 2024-02-03 | 500               | L   | 0.000      | -            | -                | -                | -         |    -0.00 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,553.86)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.593 | $1,000.00      | $593.06         |
| 2024-03-25 |      0.340 | $4,300.00      | $1,460.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
