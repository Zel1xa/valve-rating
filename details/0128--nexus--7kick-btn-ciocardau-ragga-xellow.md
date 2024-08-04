### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
<br />
Final Rank Value:  784.3<br />
<br />
Final Rank Value (784.3) = Starting Rank Value (836.4) + Head To Head Adjustments (-52.0)<br />

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
|           61 |      154 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.510 (0.073)    | 0 (0.000) |    15.83 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      217 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.70 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      349 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.91 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      494 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.04 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      537 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.453 (0.151)    | 0 (0.000) |    23.93 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      580 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.354 (0.118)    | 0 (0.000) |    26.05 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      597 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.23 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      672 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.15 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      700 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      765 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.757 (0.252)    | 0 (0.000) |    25.11 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      773 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.57 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      792 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.07 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      835 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.32 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      866 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.17 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1107 | 2024-06-12 | Permitta          | L   | 0.848      | -            | -                | -                | -         |    -6.69 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1130 | 2024-06-11 | FAVBET            | L   | 0.841      | -            | -                | -                | -         |   -10.70 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1226 | 2024-06-09 | EYEBALLERS        | L   | 0.826      | -            | -                | -                | -         |    -7.48 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1251 | 2024-06-08 | Enterprise        | L   | 0.822      | -            | -                | -                | -         |    -8.15 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1326 | 2024-06-07 | Astralis Talent   | W   | 0.814      | -            | -                | -                | 0 (0.000) |    13.13 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1338 | 2024-06-07 | 9INE              | L   | 0.813      | -            | -                | -                | -         |    -8.16 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1364 | 2024-06-06 | 3DMAX             | L   | 0.809      | -            | -                | -                | -         |    -0.42 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1460 | 2024-06-05 | BLEED             | L   | 0.800      | -            | -                | -                | -         |    -0.76 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1700 | 2024-05-27 | The Prodigies     | L   | 0.742      | -            | -                | -                | -         |   -18.32 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1708 | 2024-05-27 | MOUZ NXT          | L   | 0.739      | -            | -                | -                | -         |    -4.04 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1743 | 2024-05-25 | Permitta          | L   | 0.727      | -            | -                | -                | -         |    -8.08 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1770 | 2024-05-23 | RUBY              | L   | 0.714      | -            | -                | -                | -         |    -6.54 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1885 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.695      | 0.435        | 0.031 (0.010)    | 0.560 (0.169)    | 0 (0.000) |    14.83 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1890 | 2024-05-20 | PERA              | L   | 0.694      | -            | -                | -                | -         |    -6.59 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     1987 | 2024-05-17 | Passion UA        | L   | 0.673      | -            | -                | -                | -         |    -4.53 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2084 | 2024-05-15 | Space             | L   | 0.659      | -            | -                | -                | -         |    -9.13 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2153 | 2024-05-13 | Sampi             | L   | 0.646      | -            | -                | -                | -         |    -7.01 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2363 | 2024-05-03 | ENCE Academy      | L   | 0.579      | -            | -                | -                | -         |   -11.47 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2408 | 2024-05-01 | Insilio           | L   | 0.567      | -            | -                | -                | -         |    -6.56 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2440 | 2024-04-30 | fnatic            | L   | 0.559      | -            | -                | -                | -         |    -0.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2444 | 2024-04-29 | Endpoint          | L   | 0.554      | -            | -                | -                | -         |    -7.25 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2449 | 2024-04-29 | VP.Prodigy        | L   | 0.553      | -            | -                | -                | -         |    -8.16 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2454 | 2024-04-29 | LEON              | W   | 0.553      | -            | -                | -                | 0 (0.000) |     5.27 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2459 | 2024-04-29 | Enterprise        | W   | 0.552      | 0.384        | 0.039 (0.008)    | 0.625 (0.133)    | 0 (0.000) |    10.03 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2475 | 2024-04-28 | brazylijski luz   | L   | 0.546      | -            | -                | -                | -         |    -8.73 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2543 | 2024-04-25 | Metizport         | W   | 0.528      | 0.384        | 0.037 (0.007)    | 0.417 (0.085)    | -         |    10.84 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2551 | 2024-04-25 | Grannys Knockers  | L   | 0.526      | -            | -                | -                | -         |   -10.25 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2572 | 2024-04-24 | AMKAL             | L   | 0.519      | -            | -                | -                | -         |    -2.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2590 | 2024-04-23 | Illuminar         | L   | 0.513      | -            | -                | -                | -         |   -13.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2603 | 2024-04-22 | Zero Tenacity     | L   | 0.507      | -            | -                | -                | -         |    -3.70 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2614 | 2024-04-21 | Young Ninjas      | W   | 0.502      | -            | -                | -                | -         |     5.99 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2618 | 2024-04-21 | PARIVISION        | L   | 0.501      | -            | -                | -                | -         |    -3.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2654 | 2024-04-20 | Permitta          | W   | 0.493      | 0.500        | -                | 0.876 (0.216)    | -         |    10.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2724 | 2024-04-18 | Young Ninjas      | L   | 0.482      | -            | -                | -                | -         |    -9.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2755 | 2024-04-18 | Enterprise        | L   | 0.479      | -            | -                | -                | -         |    -6.29 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     2953 | 2024-04-10 | B8                | W   | 0.427      | 0.384        | 0.165 (0.027)    | 0.912 (0.150)    | -         |    10.20 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3097 | 2024-04-05 | SINNERS           | L   | 0.394      | -            | -                | -                | -         |    -2.58 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3239 | 2024-04-01 | Sashi             | W   | 0.366      | 0.384        | 0.184 (0.026)    | 0.962 (0.135)    | -         |     9.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3348 | 2024-03-25 | Sashi             | L   | 0.321      | -            | -                | -                | -         |    -1.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3609 | 2024-03-12 | Nemiga            | W   | 0.235      | 0.372        | 0.317 (0.028)    | -                | -         |     6.31 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3631 | 2024-03-11 | RUBY              | W   | 0.228      | 0.372        | 0.095 (0.008)    | -                | -         |     4.54 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3671 | 2024-03-09 | INGLORIOUS        | W   | 0.215      | -            | -                | -                | -         |     1.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3695 | 2024-03-08 | FAVBET            | W   | 0.208      | -            | -                | -                | -         |     2.61 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3841 | 2024-03-03 | TSM               | L   | 0.175      | -            | -                | -                | -         |    -3.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4089 | 2024-02-20 | ex-Guild Eagles   | L   | 0.094      | -            | -                | -                | -         |    -1.57 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4110 | 2024-02-19 | Monte             | L   | 0.088      | -            | -                | -                | -         |    -0.81 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4116 | 2024-02-19 | Astralis          | L   | 0.087      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,454.36)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.574 | $1,000.00      | $574.28         |
| 2024-03-25 |      0.321 | $4,300.00      | $1,380.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
