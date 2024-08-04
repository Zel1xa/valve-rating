### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  783.5<br />
<br />
Final Rank Value (783.5) = Starting Rank Value (836.8) + Head To Head Adjustments (-53.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.8
- 400 + ( ( 0.214 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 836.8


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
|           61 |      143 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.510 (0.073)    | 0 (0.000) |    15.55 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      206 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.82 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      338 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.88 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      483 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.04 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      526 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.453 (0.151)    | 0 (0.000) |    23.90 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      569 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.353 (0.118)    | 0 (0.000) |    26.04 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      586 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.21 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      661 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.16 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      689 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.30 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      754 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.758 (0.253)    | 0 (0.000) |    25.09 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      762 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.54 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      781 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.09 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      823 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      854 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.18 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1095 | 2024-06-12 | Permitta          | L   | 0.852      | -            | -                | -                | -         |    -6.72 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1118 | 2024-06-11 | FAVBET            | L   | 0.845      | -            | -                | -                | -         |   -10.80 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1214 | 2024-06-09 | EYEBALLERS        | L   | 0.830      | -            | -                | -                | -         |    -7.50 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1239 | 2024-06-08 | Enterprise        | L   | 0.825      | -            | -                | -                | -         |    -8.17 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1314 | 2024-06-07 | Astralis Talent   | W   | 0.818      | -            | -                | -                | 0 (0.000) |    13.20 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1326 | 2024-06-07 | 9INE              | L   | 0.817      | -            | -                | -                | -         |    -8.22 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1352 | 2024-06-06 | 3DMAX             | L   | 0.813      | -            | -                | -                | -         |    -0.43 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1448 | 2024-06-05 | BLEED             | L   | 0.804      | -            | -                | -                | -         |    -0.77 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1688 | 2024-05-27 | The Prodigies     | L   | 0.745      | -            | -                | -                | -         |   -18.40 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1696 | 2024-05-27 | MOUZ NXT          | L   | 0.743      | -            | -                | -                | -         |    -4.06 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1731 | 2024-05-25 | Permitta          | L   | 0.730      | -            | -                | -                | -         |    -8.15 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1758 | 2024-05-23 | RUBY              | L   | 0.718      | -            | -                | -                | -         |    -6.55 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1873 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.699      | 0.435        | 0.032 (0.010)    | 0.561 (0.170)    | 0 (0.000) |    14.90 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1878 | 2024-05-20 | PERA              | L   | 0.698      | -            | -                | -                | -         |    -6.68 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     1975 | 2024-05-17 | Passion UA        | L   | 0.677      | -            | -                | -                | -         |    -4.69 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2072 | 2024-05-15 | Space             | L   | 0.662      | -            | -                | -                | -         |    -9.17 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2141 | 2024-05-13 | Sampi             | L   | 0.650      | -            | -                | -                | -         |    -7.05 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2351 | 2024-05-03 | ENCE Academy      | L   | 0.583      | -            | -                | -                | -         |   -11.55 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2396 | 2024-05-01 | Insilio           | L   | 0.570      | -            | -                | -                | -         |    -6.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2428 | 2024-04-30 | fnatic            | L   | 0.563      | -            | -                | -                | -         |    -0.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2432 | 2024-04-29 | Endpoint          | L   | 0.558      | -            | -                | -                | -         |    -7.30 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2437 | 2024-04-29 | VP.Prodigy        | L   | 0.557      | -            | -                | -                | -         |    -8.22 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2442 | 2024-04-29 | LEON              | W   | 0.557      | -            | -                | -                | 0 (0.000) |     5.30 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2447 | 2024-04-29 | Enterprise        | W   | 0.556      | 0.384        | 0.039 (0.008)    | 0.624 (0.133)    | 0 (0.000) |    10.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2463 | 2024-04-28 | brazylijski luz   | L   | 0.550      | -            | -                | -                | -         |    -8.82 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2530 | 2024-04-25 | Metizport         | W   | 0.532      | 0.384        | 0.037 (0.008)    | 0.418 (0.085)    | -         |    10.91 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2538 | 2024-04-25 | Grannys Knockers  | L   | 0.530      | -            | -                | -                | -         |   -10.33 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2559 | 2024-04-24 | AMKAL             | L   | 0.523      | -            | -                | -                | -         |    -2.64 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2577 | 2024-04-23 | Illuminar         | L   | 0.517      | -            | -                | -                | -         |   -13.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2590 | 2024-04-22 | Zero Tenacity     | L   | 0.510      | -            | -                | -                | -         |    -3.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2601 | 2024-04-21 | Young Ninjas      | W   | 0.505      | -            | -                | -                | -         |     6.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2605 | 2024-04-21 | PARIVISION        | L   | 0.504      | -            | -                | -                | -         |    -4.03 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2641 | 2024-04-20 | Permitta          | W   | 0.497      | 0.500        | -                | 0.876 (0.218)    | -         |    10.26 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2711 | 2024-04-18 | Young Ninjas      | L   | 0.485      | -            | -                | -                | -         |    -9.52 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2742 | 2024-04-18 | Enterprise        | L   | 0.483      | -            | -                | -                | -         |    -6.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     2940 | 2024-04-10 | B8                | W   | 0.431      | 0.384        | 0.165 (0.027)    | 0.913 (0.151)    | -         |    10.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3084 | 2024-04-05 | SINNERS           | L   | 0.398      | -            | -                | -                | -         |    -2.61 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3226 | 2024-04-01 | Sashi             | W   | 0.370      | 0.384        | 0.184 (0.026)    | 0.964 (0.137)    | -         |     9.67 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3335 | 2024-03-25 | Sashi             | L   | 0.325      | -            | -                | -                | -         |    -1.67 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3595 | 2024-03-12 | Nemiga            | W   | 0.239      | 0.372        | 0.318 (0.028)    | -                | -         |     6.42 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3617 | 2024-03-11 | RUBY              | W   | 0.232      | 0.372        | 0.095 (0.008)    | -                | -         |     4.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3657 | 2024-03-09 | INGLORIOUS        | W   | 0.218      | -            | -                | -                | -         |     1.12 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3681 | 2024-03-08 | FAVBET            | W   | 0.212      | -            | -                | -                | -         |     2.65 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3827 | 2024-03-03 | TSM               | L   | 0.178      | -            | -                | -                | -         |    -4.01 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4075 | 2024-02-20 | ex-Guild Eagles   | L   | 0.097      | -            | -                | -                | -         |    -1.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4096 | 2024-02-19 | Monte             | L   | 0.092      | -            | -                | -                | -         |    -0.84 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4102 | 2024-02-19 | Astralis          | L   | 0.091      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,474.36)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.578 | $1,000.00      | $578.06         |
| 2024-03-25 |      0.325 | $4,300.00      | $1,396.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
