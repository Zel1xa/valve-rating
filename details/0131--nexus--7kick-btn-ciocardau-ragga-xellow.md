### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.2<br />
<br />
Final Rank Value (786.2) = Starting Rank Value (836.9) + Head To Head Adjustments (-50.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.9
- 400 + ( ( 0.213 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 836.9


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
|           61 |      204 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.500 (0.071)    | 0 (0.000) |    15.77 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      266 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.66 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      399 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.97 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      543 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.99 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      586 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.446 (0.149)    | 0 (0.000) |    23.82 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      629 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.430 (0.143)    | 0 (0.000) |    26.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      645 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.28 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      723 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -10.99 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      749 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      814 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.809 (0.270)    | 0 (0.000) |    25.65 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      822 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.62 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      841 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.02 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      884 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.37 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      915 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.15 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1156 | 2024-06-12 | Permitta          | L   | 0.840      | -            | -                | -                | -         |    -6.62 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1179 | 2024-06-11 | FAVBET            | L   | 0.833      | -            | -                | -                | -         |   -10.58 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1275 | 2024-06-09 | EYEBALLERS        | L   | 0.818      | -            | -                | -                | -         |    -7.50 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1300 | 2024-06-08 | Enterprise        | L   | 0.814      | -            | -                | -                | -         |    -7.99 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1375 | 2024-06-07 | Astralis Talent   | W   | 0.806      | -            | -                | -                | 0 (0.000) |    12.90 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1387 | 2024-06-07 | 9INE              | L   | 0.805      | -            | -                | -                | -         |    -8.07 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1413 | 2024-06-06 | 3DMAX             | L   | 0.801      | -            | -                | -                | -         |    -0.40 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1509 | 2024-06-05 | BLEED             | L   | 0.792      | -            | -                | -                | -         |    -0.74 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1749 | 2024-05-27 | The Prodigies     | L   | 0.734      | -            | -                | -                | -         |   -18.15 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1757 | 2024-05-27 | MOUZ NXT          | L   | 0.731      | -            | -                | -                | -         |    -3.93 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1792 | 2024-05-25 | Permitta          | L   | 0.719      | -            | -                | -                | -         |    -7.94 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1819 | 2024-05-23 | RUBY              | L   | 0.706      | -            | -                | -                | -         |    -6.57 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1934 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.687      | 0.435        | 0.031 (0.009)    | 0.550 (0.164)    | 0 (0.000) |    14.72 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1939 | 2024-05-20 | PERA              | L   | 0.686      | -            | -                | -                | -         |    -6.53 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2036 | 2024-05-17 | Passion UA        | L   | 0.665      | -            | -                | -                | -         |    -4.36 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2133 | 2024-05-15 | Space             | L   | 0.651      | -            | -                | -                | -         |    -9.14 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2202 | 2024-05-13 | Sampi             | L   | 0.638      | -            | -                | -                | -         |    -6.96 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2412 | 2024-05-03 | ENCE Academy      | L   | 0.571      | -            | -                | -                | -         |   -11.31 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2457 | 2024-05-01 | Insilio           | L   | 0.559      | -            | -                | -                | -         |    -6.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2489 | 2024-04-30 | fnatic            | L   | 0.551      | -            | -                | -                | -         |    -0.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2493 | 2024-04-29 | Endpoint          | L   | 0.546      | -            | -                | -                | -         |    -7.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2498 | 2024-04-29 | VP.Prodigy        | L   | 0.545      | -            | -                | -                | -         |    -8.04 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2503 | 2024-04-29 | LEON              | W   | 0.545      | -            | -                | -                | 0 (0.000) |     5.20 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2508 | 2024-04-29 | Enterprise        | W   | 0.544      | 0.384        | 0.039 (0.008)    | 0.616 (0.129)    | 0 (0.000) |     9.91 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2524 | 2024-04-28 | brazylijski luz   | L   | 0.538      | -            | -                | -                | -         |    -8.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2592 | 2024-04-25 | Metizport         | W   | 0.520      | 0.384        | 0.032 (0.006)    | -                | -         |     9.49 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2600 | 2024-04-25 | Grannys Knockers  | L   | 0.518      | -            | -                | -                | -         |   -10.12 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2621 | 2024-04-24 | AMKAL             | L   | 0.511      | -            | -                | -                | -         |    -2.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2639 | 2024-04-23 | Illuminar         | L   | 0.505      | -            | -                | -                | -         |   -13.45 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2652 | 2024-04-22 | Zero Tenacity     | L   | 0.499      | -            | -                | -                | -         |    -3.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2663 | 2024-04-21 | Young Ninjas      | W   | 0.494      | -            | -                | -                | -         |     6.00 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2667 | 2024-04-21 | PARIVISION        | L   | 0.493      | -            | -                | -                | -         |    -3.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2703 | 2024-04-20 | Permitta          | W   | 0.485      | 0.500        | -                | 0.863 (0.209)    | -         |    10.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2773 | 2024-04-18 | Young Ninjas      | L   | 0.474      | -            | -                | -                | -         |    -9.20 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2804 | 2024-04-18 | Enterprise        | L   | 0.471      | -            | -                | -                | -         |    -6.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3002 | 2024-04-10 | B8                | W   | 0.419      | 0.384        | 0.165 (0.026)    | 0.935 (0.151)    | -         |     9.99 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3146 | 2024-04-05 | SINNERS           | L   | 0.386      | -            | -                | -                | -         |    -1.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3288 | 2024-04-01 | Sashi             | W   | 0.358      | 0.384        | 0.184 (0.025)    | 0.983 (0.135)    | -         |     9.40 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3397 | 2024-03-25 | Sashi             | L   | 0.313      | -            | -                | -                | -         |    -1.58 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3658 | 2024-03-12 | Nemiga            | W   | 0.227      | 0.372        | 0.316 (0.027)    | 0.722 (0.061)    | -         |     6.20 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3680 | 2024-03-11 | RUBY              | W   | 0.220      | 0.372        | 0.095 (0.008)    | -                | -         |     4.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3720 | 2024-03-09 | INGLORIOUS        | W   | 0.207      | -            | -                | -                | -         |     1.06 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3744 | 2024-03-08 | FAVBET            | W   | 0.200      | -            | -                | -                | -         |     2.52 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3890 | 2024-03-03 | TSM               | L   | 0.167      | -            | -                | -                | -         |    -3.75 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4138 | 2024-02-20 | ex-Guild Eagles   | L   | 0.086      | -            | -                | -                | -         |    -1.44 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4159 | 2024-02-19 | Monte             | L   | 0.080      | -            | -                | -                | -         |    -0.75 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4165 | 2024-02-19 | Astralis          | L   | 0.079      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,412.53)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.566 | $1,000.00      | $566.39         |
| 2024-03-25 |      0.313 | $4,300.00      | $1,346.14       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
