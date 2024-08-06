### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  789.0<br />
<br />
Final Rank Value (789.0) = Starting Rank Value (839.6) + Head To Head Adjustments (-50.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.354[<sup>2</sup>](#table1)
- Opponent Network: 0.153[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 839.6
- 400 + ( ( 0.214 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 839.6


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
|           61 |      211 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.499 (0.071)    | 0 (0.000) |    15.79 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      273 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.68 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      406 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.99 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      550 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.01 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      593 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.445 (0.148)    | 0 (0.000) |    23.72 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      636 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.471 (0.157)    | 0 (0.000) |    26.23 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      652 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.37 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      730 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.07 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      756 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.29 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      821 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.808 (0.269)    | 0 (0.000) |    25.60 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      829 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.64 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      848 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.92 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      891 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.39 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      922 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.08 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1163 | 2024-06-12 | Permitta          | L   | 0.835      | -            | -                | -                | -         |    -6.52 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1186 | 2024-06-11 | FAVBET            | L   | 0.829      | -            | -                | -                | -         |   -10.63 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1282 | 2024-06-09 | EYEBALLERS        | L   | 0.813      | -            | -                | -                | -         |    -7.43 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1307 | 2024-06-08 | Enterprise        | L   | 0.809      | -            | -                | -                | -         |    -7.99 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1382 | 2024-06-07 | Astralis Talent   | W   | 0.801      | -            | -                | -                | 0 (0.000) |    12.71 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1394 | 2024-06-07 | 9INE              | L   | 0.801      | -            | -                | -                | -         |    -8.11 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1420 | 2024-06-06 | 3DMAX             | L   | 0.796      | -            | -                | -                | -         |    -0.40 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1516 | 2024-06-05 | BLEED             | L   | 0.787      | -            | -                | -                | -         |    -0.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1756 | 2024-05-27 | The Prodigies     | L   | 0.729      | -            | -                | -                | -         |   -18.11 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1764 | 2024-05-27 | MOUZ NXT          | L   | 0.726      | -            | -                | -                | -         |    -3.95 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1799 | 2024-05-25 | Permitta          | L   | 0.714      | -            | -                | -                | -         |    -7.77 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1826 | 2024-05-23 | RUBY              | L   | 0.701      | -            | -                | -                | -         |    -6.48 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1941 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.682      | 0.435        | 0.031 (0.009)    | 0.549 (0.163)    | 0 (0.000) |    14.56 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1946 | 2024-05-20 | PERA              | L   | 0.681      | -            | -                | -                | -         |    -6.58 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2043 | 2024-05-17 | Passion UA        | L   | 0.660      | -            | -                | -                | -         |    -4.34 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2140 | 2024-05-15 | Space             | L   | 0.646      | -            | -                | -                | -         |    -9.06 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2209 | 2024-05-13 | Sampi             | L   | 0.634      | -            | -                | -                | -         |    -6.96 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2419 | 2024-05-03 | ENCE Academy      | L   | 0.566      | -            | -                | -                | -         |   -11.29 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2464 | 2024-05-01 | Insilio           | L   | 0.554      | -            | -                | -                | -         |    -6.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2496 | 2024-04-30 | fnatic            | L   | 0.546      | -            | -                | -                | -         |    -0.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2500 | 2024-04-29 | Endpoint          | L   | 0.542      | -            | -                | -                | -         |    -7.12 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2505 | 2024-04-29 | VP.Prodigy        | L   | 0.541      | -            | -                | -                | -         |    -8.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2510 | 2024-04-29 | LEON              | W   | 0.540      | -            | -                | -                | 0 (0.000) |     5.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2515 | 2024-04-29 | Enterprise        | W   | 0.539      | 0.384        | 0.039 (0.008)    | 0.616 (0.128)    | 0 (0.000) |     9.80 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2531 | 2024-04-28 | brazylijski luz   | L   | 0.533      | -            | -                | -                | -         |    -8.65 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2599 | 2024-04-25 | Metizport         | W   | 0.515      | 0.384        | 0.036 (0.007)    | 0.444 (0.088)    | -         |    10.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2607 | 2024-04-25 | Grannys Knockers  | L   | 0.514      | -            | -                | -                | -         |   -10.08 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2628 | 2024-04-24 | AMKAL             | L   | 0.507      | -            | -                | -                | -         |    -2.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2646 | 2024-04-23 | Illuminar         | L   | 0.500      | -            | -                | -                | -         |   -13.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2659 | 2024-04-22 | Zero Tenacity     | L   | 0.494      | -            | -                | -                | -         |    -3.58 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2670 | 2024-04-21 | Young Ninjas      | W   | 0.489      | -            | -                | -                | -         |     5.87 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2674 | 2024-04-21 | PARIVISION        | L   | 0.488      | -            | -                | -                | -         |    -3.79 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2710 | 2024-04-20 | Permitta          | W   | 0.481      | 0.500        | -                | 0.940 (0.226)    | -         |    10.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2780 | 2024-04-18 | Young Ninjas      | L   | 0.469      | -            | -                | -                | -         |    -9.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2811 | 2024-04-18 | Enterprise        | L   | 0.467      | -            | -                | -                | -         |    -6.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3009 | 2024-04-10 | B8                | W   | 0.414      | 0.384        | 0.164 (0.026)    | 0.933 (0.148)    | -         |     9.86 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3153 | 2024-04-05 | SINNERS           | L   | 0.382      | -            | -                | -                | -         |    -1.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3295 | 2024-04-01 | Sashi             | W   | 0.353      | 0.384        | 0.184 (0.025)    | 0.980 (0.133)    | -         |     9.26 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3404 | 2024-03-25 | Sashi             | L   | 0.308      | -            | -                | -                | -         |    -1.57 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3665 | 2024-03-12 | Nemiga            | W   | 0.222      | 0.372        | 0.315 (0.026)    | -                | -         |     6.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3687 | 2024-03-11 | RUBY              | W   | 0.215      | 0.372        | 0.095 (0.008)    | -                | -         |     4.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3727 | 2024-03-09 | INGLORIOUS        | W   | 0.202      | -            | -                | -                | -         |     1.01 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3751 | 2024-03-08 | FAVBET            | W   | 0.195      | -            | -                | -                | -         |     2.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3897 | 2024-03-03 | TSM               | L   | 0.162      | -            | -                | -                | -         |    -3.67 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4145 | 2024-02-20 | ex-Guild Eagles   | L   | 0.081      | -            | -                | -                | -         |    -1.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4166 | 2024-02-19 | Monte             | L   | 0.075      | -            | -                | -                | -         |    -0.72 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4172 | 2024-02-19 | Astralis          | L   | 0.074      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,387.50)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.562 | $1,000.00      | $561.67         |
| 2024-03-25 |      0.308 | $4,300.00      | $1,325.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
