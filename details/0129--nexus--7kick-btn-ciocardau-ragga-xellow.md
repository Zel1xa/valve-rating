### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [129](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  784.9<br />
<br />
Final Rank Value (784.9) = Starting Rank Value (836.5) + Head To Head Adjustments (-51.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.5
- 400 + ( ( 0.213 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 836.5


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
|           61 |      183 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.509 (0.073)    | 0 (0.000) |    15.73 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      245 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.67 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      378 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.93 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      522 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.98 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      565 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.453 (0.151)    | 0 (0.000) |    23.86 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      608 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.395 (0.132)    | 0 (0.000) |    26.06 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      624 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.24 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      702 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -10.99 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      728 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      793 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.797 (0.266)    | 0 (0.000) |    25.54 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      801 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.58 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      820 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.06 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      863 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.32 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      894 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.17 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1135 | 2024-06-12 | Permitta          | L   | 0.844      | -            | -                | -                | -         |    -6.64 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1158 | 2024-06-11 | FAVBET            | L   | 0.838      | -            | -                | -                | -         |   -10.69 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1254 | 2024-06-09 | EYEBALLERS        | L   | 0.823      | -            | -                | -                | -         |    -7.52 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1279 | 2024-06-08 | Enterprise        | L   | 0.818      | -            | -                | -                | -         |    -8.09 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1354 | 2024-06-07 | Astralis Talent   | W   | 0.811      | -            | -                | -                | 0 (0.000) |    13.07 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1366 | 2024-06-07 | 9INE              | L   | 0.810      | -            | -                | -                | -         |    -8.12 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1392 | 2024-06-06 | 3DMAX             | L   | 0.805      | -            | -                | -                | -         |    -0.41 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1488 | 2024-06-05 | BLEED             | L   | 0.796      | -            | -                | -                | -         |    -0.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1728 | 2024-05-27 | The Prodigies     | L   | 0.738      | -            | -                | -                | -         |   -18.24 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1736 | 2024-05-27 | MOUZ NXT          | L   | 0.736      | -            | -                | -                | -         |    -4.00 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1771 | 2024-05-25 | Permitta          | L   | 0.723      | -            | -                | -                | -         |    -8.02 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1798 | 2024-05-23 | RUBY              | L   | 0.711      | -            | -                | -                | -         |    -6.60 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1913 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.691      | 0.435        | 0.031 (0.009)    | 0.560 (0.168)    | 0 (0.000) |    14.81 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1918 | 2024-05-20 | PERA              | L   | 0.691      | -            | -                | -                | -         |    -6.55 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2015 | 2024-05-17 | Passion UA        | L   | 0.669      | -            | -                | -                | -         |    -4.42 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2112 | 2024-05-15 | Space             | L   | 0.655      | -            | -                | -                | -         |    -9.16 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2181 | 2024-05-13 | Sampi             | L   | 0.643      | -            | -                | -                | -         |    -6.97 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2391 | 2024-05-03 | ENCE Academy      | L   | 0.576      | -            | -                | -                | -         |   -11.39 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2436 | 2024-05-01 | Insilio           | L   | 0.563      | -            | -                | -                | -         |    -6.52 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2468 | 2024-04-30 | fnatic            | L   | 0.555      | -            | -                | -                | -         |    -0.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2472 | 2024-04-29 | Endpoint          | L   | 0.551      | -            | -                | -                | -         |    -7.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2477 | 2024-04-29 | VP.Prodigy        | L   | 0.550      | -            | -                | -                | -         |    -8.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2482 | 2024-04-29 | LEON              | W   | 0.549      | -            | -                | -                | 0 (0.000) |     5.25 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2487 | 2024-04-29 | Enterprise        | W   | 0.549      | 0.384        | 0.039 (0.008)    | 0.625 (0.132)    | 0 (0.000) |     9.99 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2503 | 2024-04-28 | brazylijski luz   | L   | 0.542      | -            | -                | -                | -         |    -8.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2571 | 2024-04-25 | Metizport         | W   | 0.524      | 0.384        | 0.033 (0.007)    | -                | -         |     9.61 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2579 | 2024-04-25 | Grannys Knockers  | L   | 0.523      | -            | -                | -                | -         |   -10.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2600 | 2024-04-24 | AMKAL             | L   | 0.516      | -            | -                | -                | -         |    -2.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2618 | 2024-04-23 | Illuminar         | L   | 0.509      | -            | -                | -                | -         |   -13.55 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2631 | 2024-04-22 | Zero Tenacity     | L   | 0.503      | -            | -                | -                | -         |    -3.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2642 | 2024-04-21 | Young Ninjas      | W   | 0.498      | -            | -                | -                | -         |     5.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2646 | 2024-04-21 | PARIVISION        | L   | 0.497      | -            | -                | -                | -         |    -3.94 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2682 | 2024-04-20 | Permitta          | W   | 0.490      | 0.500        | -                | 0.876 (0.214)    | -         |    10.11 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2752 | 2024-04-18 | Young Ninjas      | L   | 0.478      | -            | -                | -                | -         |    -9.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2783 | 2024-04-18 | Enterprise        | L   | 0.476      | -            | -                | -                | -         |    -6.25 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     2981 | 2024-04-10 | B8                | W   | 0.423      | 0.384        | 0.165 (0.027)    | 0.951 (0.155)    | -         |    10.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3125 | 2024-04-05 | SINNERS           | L   | 0.391      | -            | -                | -                | -         |    -2.01 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3267 | 2024-04-01 | Sashi             | W   | 0.362      | 0.384        | 0.184 (0.026)    | 0.961 (0.134)    | -         |     9.52 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3376 | 2024-03-25 | Sashi             | L   | 0.318      | -            | -                | -                | -         |    -1.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3637 | 2024-03-12 | Nemiga            | W   | 0.231      | 0.372        | 0.317 (0.027)    | 0.733 (0.063)    | -         |     6.32 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3659 | 2024-03-11 | RUBY              | W   | 0.224      | 0.372        | 0.095 (0.008)    | -                | -         |     4.42 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3699 | 2024-03-09 | INGLORIOUS        | W   | 0.211      | -            | -                | -                | -         |     1.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3723 | 2024-03-08 | FAVBET            | W   | 0.204      | -            | -                | -                | -         |     2.57 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3869 | 2024-03-03 | TSM               | L   | 0.171      | -            | -                | -                | -         |    -3.85 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4117 | 2024-02-20 | ex-Guild Eagles   | L   | 0.090      | -            | -                | -                | -         |    -1.52 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4138 | 2024-02-19 | Monte             | L   | 0.085      | -            | -                | -                | -         |    -0.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4144 | 2024-02-19 | Astralis          | L   | 0.083      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,436.08)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.571 | $1,000.00      | $570.83         |
| 2024-03-25 |      0.318 | $4,300.00      | $1,365.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
