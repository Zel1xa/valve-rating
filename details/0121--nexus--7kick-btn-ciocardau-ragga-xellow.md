### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  805.5<br />
<br />
Final Rank Value (805.5) = Starting Rank Value (843.3) + Head To Head Adjustments (-37.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 843.3
- 400 + ( ( 0.215 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 843.3


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
|           65 |       57 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.49 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           64 |      121 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -5.26 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           63 |      254 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.85 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           62 |      401 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           61 |      446 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.452 (0.151)    | 0 (0.000) |    23.07 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      493 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.039 (0.013)    | 0.347 (0.116)    | 0 (0.000) |    25.40 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      509 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.63 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           58 |      585 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -12.94 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           57 |      615 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.69 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      685 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.038 (0.013)    | 0.768 (0.256)    | 0 (0.000) |    24.21 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      692 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -11.10 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           54 |      699 | 2024-07-14 | Rebels            | W   | 1.000      | 0.143        | -                | 0.635 (0.091)    | 0 (0.000) |    25.43 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           53 |      714 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.18 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      756 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |    -9.84 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      787 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.12 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |     1017 | 2024-06-12 | Permitta          | L   | 0.868      | -            | -                | -                | -         |    -6.93 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           49 |     1041 | 2024-06-11 | FAVBET            | L   | 0.861      | -            | -                | -                | -         |   -10.87 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           48 |     1139 | 2024-06-09 | EYEBALLERS        | L   | 0.846      | -            | -                | -                | -         |    -7.60 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           47 |     1165 | 2024-06-08 | Enterprise        | L   | 0.842      | -            | -                | -                | -         |    -8.43 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1247 | 2024-06-07 | Astralis Talent   | W   | 0.834      | -            | -                | -                | 0 (0.000) |    13.69 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1259 | 2024-06-07 | 9INE              | L   | 0.833      | -            | -                | -                | -         |    -7.67 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1287 | 2024-06-06 | 3DMAX             | L   | 0.829      | -            | -                | -                | -         |    -0.45 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1386 | 2024-06-05 | BLEED             | L   | 0.820      | -            | -                | -                | -         |    -0.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1627 | 2024-05-27 | The Prodigies     | L   | 0.762      | -            | -                | -                | -         |   -18.80 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1636 | 2024-05-27 | MOUZ NXT          | L   | 0.759      | -            | -                | -                | -         |    -4.20 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1672 | 2024-05-25 | Permitta          | L   | 0.747      | -            | -                | -                | -         |    -8.48 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1699 | 2024-05-23 | RUBY              | L   | 0.734      | -            | -                | -                | -         |    -6.49 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1831 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.715      | 0.435        | 0.032 (0.010)    | 0.564 (0.175)    | 0 (0.000) |    14.91 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1837 | 2024-05-20 | PERA              | L   | 0.714      | -            | -                | -                | -         |    -6.91 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1942 | 2024-05-17 | Passion UA        | L   | 0.693      | -            | -                | -                | -         |    -4.76 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     2045 | 2024-05-15 | Space             | L   | 0.679      | -            | -                | -                | -         |    -9.38 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     2117 | 2024-05-13 | Sampi             | L   | 0.666      | -            | -                | -                | -         |    -7.48 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2329 | 2024-05-03 | ENCE Academy      | L   | 0.599      | -            | -                | -                | -         |   -12.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           32 |     2376 | 2024-05-01 | Insilio           | L   | 0.587      | -            | -                | -                | -         |    -6.80 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           31 |     2409 | 2024-04-30 | fnatic            | L   | 0.579      | -            | -                | -                | -         |    -0.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           30 |     2413 | 2024-04-29 | Endpoint          | L   | 0.575      | -            | -                | -                | -         |    -7.15 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2418 | 2024-04-29 | VP.Prodigy        | L   | 0.573      | -            | -                | -                | -         |    -8.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2423 | 2024-04-29 | LEON              | W   | 0.573      | -            | -                | -                | 0 (0.000) |     5.39 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2428 | 2024-04-29 | Enterprise        | W   | 0.572      | 0.384        | 0.040 (0.009)    | 0.622 (0.137)    | -         |    10.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2444 | 2024-04-28 | brazylijski luz   | L   | 0.566      | -            | -                | -                | -         |    -8.86 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2512 | 2024-04-25 | Metizport         | W   | 0.548      | 0.384        | 0.038 (0.008)    | 0.425 (0.090)    | -         |    11.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2520 | 2024-04-25 | Grannys Knockers  | L   | 0.546      | -            | -                | -                | -         |   -10.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2541 | 2024-04-24 | AMKAL             | L   | 0.539      | -            | -                | -                | -         |    -2.73 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2561 | 2024-04-23 | Illuminar         | L   | 0.533      | -            | -                | -                | -         |   -14.21 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2575 | 2024-04-22 | Zero Tenacity     | L   | 0.527      | -            | -                | -                | -         |    -3.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2587 | 2024-04-21 | Young Ninjas      | W   | 0.522      | -            | -                | -                | -         |     6.31 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2591 | 2024-04-21 | PARIVISION        | L   | 0.521      | -            | -                | -                | -         |    -4.31 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2629 | 2024-04-20 | Permitta          | W   | 0.513      | 0.500        | -                | 0.801 (0.206)    | -         |    10.38 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2701 | 2024-04-18 | Young Ninjas      | L   | 0.502      | -            | -                | -                | -         |    -9.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2732 | 2024-04-18 | Enterprise        | L   | 0.499      | -            | -                | -                | -         |    -6.76 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2933 | 2024-04-10 | B8                | W   | 0.447      | 0.384        | 0.168 (0.029)    | 0.878 (0.151)    | -         |    10.70 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     3077 | 2024-04-05 | SINNERS           | L   | 0.414      | -            | -                | -                | -         |    -3.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     3227 | 2024-04-01 | Sashi             | W   | 0.386      | 0.384        | 0.187 (0.028)    | 0.971 (0.144)    | -         |    10.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3341 | 2024-03-25 | Sashi             | L   | 0.341      | -            | -                | -                | -         |    -1.75 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3607 | 2024-03-12 | Nemiga            | W   | 0.255      | 0.372        | 0.324 (0.031)    | -                | -         |     6.90 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3629 | 2024-03-11 | RUBY              | W   | 0.248      | 0.372        | 0.097 (0.009)    | -                | -         |     5.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3670 | 2024-03-09 | INGLORIOUS        | W   | 0.235      | -            | -                | -                | -         |     1.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3694 | 2024-03-08 | FAVBET            | W   | 0.228      | -            | -                | -                | -         |     2.85 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3845 | 2024-03-03 | TSM               | L   | 0.195      | -            | -                | -                | -         |    -4.38 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     4103 | 2024-02-20 | ex-Guild Eagles   | L   | 0.114      | -            | -                | -                | -         |    -1.89 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     4124 | 2024-02-19 | Monte             | L   | 0.108      | -            | -                | -                | -         |    -0.94 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     4130 | 2024-02-19 | Astralis          | L   | 0.107      | -            | -                | -                | -         |    -0.03 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4438 | 2024-02-03 | 500               | L   | 0.002      | -            | -                | -                | -         |    -0.03 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4442 | 2024-02-03 | Jake Bube         | W   | 0.001      | -            | -                | -                | -         |     0.00 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4449 | 2024-02-03 | North Macedonia   | L   | 0.000      | -            | -                | -                | -         |    -0.01 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,561.22)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.594 | $1,000.00      | $594.44         |
| 2024-03-25 |      0.341 | $4,300.00      | $1,466.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
