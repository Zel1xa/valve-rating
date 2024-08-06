### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  788.9<br />
<br />
Final Rank Value (788.9) = Starting Rank Value (839.4) + Head To Head Adjustments (-50.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 839.4
- 400 + ( ( 0.214 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 839.4


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
|           61 |      215 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.488 (0.070)    | 0 (0.000) |    15.79 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      277 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.68 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      410 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.99 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      554 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -3.01 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      597 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.435 (0.145)    | 0 (0.000) |    23.72 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      640 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.461 (0.154)    | 0 (0.000) |    26.23 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      656 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.37 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      734 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.05 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      760 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.29 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      825 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.790 (0.263)    | 0 (0.000) |    25.60 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      833 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.63 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      852 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.94 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      895 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.39 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      926 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.08 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1167 | 2024-06-12 | Permitta          | L   | 0.835      | -            | -                | -                | -         |    -6.52 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1190 | 2024-06-11 | FAVBET            | L   | 0.828      | -            | -                | -                | -         |   -10.61 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1286 | 2024-06-09 | EYEBALLERS        | L   | 0.813      | -            | -                | -                | -         |    -7.43 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1311 | 2024-06-08 | Enterprise        | L   | 0.809      | -            | -                | -                | -         |    -7.99 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1386 | 2024-06-07 | Astralis Talent   | W   | 0.801      | -            | -                | -                | 0 (0.000) |    12.73 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1398 | 2024-06-07 | 9INE              | L   | 0.800      | -            | -                | -                | -         |    -8.11 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1424 | 2024-06-06 | 3DMAX             | L   | 0.796      | -            | -                | -                | -         |    -0.40 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1520 | 2024-06-05 | BLEED             | L   | 0.787      | -            | -                | -                | -         |    -0.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1760 | 2024-05-27 | The Prodigies     | L   | 0.729      | -            | -                | -                | -         |   -18.10 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1768 | 2024-05-27 | MOUZ NXT          | L   | 0.726      | -            | -                | -                | -         |    -3.95 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1803 | 2024-05-25 | Permitta          | L   | 0.714      | -            | -                | -                | -         |    -7.77 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1830 | 2024-05-23 | RUBY              | L   | 0.701      | -            | -                | -                | -         |    -6.48 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1945 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.682      | 0.435        | 0.031 (0.009)    | 0.537 (0.159)    | 0 (0.000) |    14.57 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1950 | 2024-05-20 | PERA              | L   | 0.681      | -            | -                | -                | -         |    -6.57 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2047 | 2024-05-17 | Passion UA        | L   | 0.660      | -            | -                | -                | -         |    -4.34 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2144 | 2024-05-15 | Space             | L   | 0.646      | -            | -                | -                | -         |    -9.07 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2213 | 2024-05-13 | Sampi             | L   | 0.633      | -            | -                | -                | -         |    -6.97 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2423 | 2024-05-03 | ENCE Academy      | L   | 0.566      | -            | -                | -                | -         |   -11.27 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2468 | 2024-05-01 | Insilio           | L   | 0.554      | -            | -                | -                | -         |    -6.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2500 | 2024-04-30 | fnatic            | L   | 0.546      | -            | -                | -                | -         |    -0.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2504 | 2024-04-29 | Endpoint          | L   | 0.541      | -            | -                | -                | -         |    -7.13 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2509 | 2024-04-29 | VP.Prodigy        | L   | 0.540      | -            | -                | -                | -         |    -8.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2514 | 2024-04-29 | LEON              | W   | 0.540      | -            | -                | -                | 0 (0.000) |     5.11 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2519 | 2024-04-29 | Enterprise        | W   | 0.539      | 0.384        | 0.039 (0.008)    | 0.641 (0.133)    | 0 (0.000) |     9.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2535 | 2024-04-28 | brazylijski luz   | L   | 0.533      | -            | -                | -                | -         |    -8.64 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2603 | 2024-04-25 | Metizport         | W   | 0.515      | 0.384        | 0.036 (0.007)    | 0.434 (0.086)    | -         |    10.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2611 | 2024-04-25 | Grannys Knockers  | L   | 0.513      | -            | -                | -                | -         |   -10.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2632 | 2024-04-24 | AMKAL             | L   | 0.506      | -            | -                | -                | -         |    -2.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2650 | 2024-04-23 | Illuminar         | L   | 0.500      | -            | -                | -                | -         |   -13.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2663 | 2024-04-22 | Zero Tenacity     | L   | 0.494      | -            | -                | -                | -         |    -3.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2674 | 2024-04-21 | Young Ninjas      | W   | 0.489      | -            | -                | -                | -         |     5.87 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2678 | 2024-04-21 | PARIVISION        | L   | 0.488      | -            | -                | -                | -         |    -3.77 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2714 | 2024-04-20 | Permitta          | W   | 0.480      | 0.500        | -                | 0.919 (0.221)    | -         |    10.08 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2784 | 2024-04-18 | Young Ninjas      | L   | 0.469      | -            | -                | -                | -         |    -9.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2815 | 2024-04-18 | Enterprise        | L   | 0.466      | -            | -                | -                | -         |    -6.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3013 | 2024-04-10 | B8                | W   | 0.414      | 0.384        | 0.170 (0.027)    | 0.912 (0.145)    | -         |     9.88 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3157 | 2024-04-05 | SINNERS           | L   | 0.381      | -            | -                | -                | -         |    -1.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3299 | 2024-04-01 | Sashi             | W   | 0.353      | 0.384        | 0.184 (0.025)    | 0.958 (0.130)    | -         |     9.26 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3408 | 2024-03-25 | Sashi             | L   | 0.308      | -            | -                | -                | -         |    -1.57 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3669 | 2024-03-12 | Nemiga            | W   | 0.222      | 0.372        | 0.315 (0.026)    | -                | -         |     6.04 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3691 | 2024-03-11 | RUBY              | W   | 0.215      | 0.372        | 0.095 (0.008)    | -                | -         |     4.27 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3731 | 2024-03-09 | INGLORIOUS        | W   | 0.202      | -            | -                | -                | -         |     1.01 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3755 | 2024-03-08 | FAVBET            | W   | 0.195      | -            | -                | -                | -         |     2.44 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3901 | 2024-03-03 | TSM               | L   | 0.162      | -            | -                | -                | -         |    -3.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4149 | 2024-02-20 | ex-Guild Eagles   | L   | 0.081      | -            | -                | -                | -         |    -1.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4170 | 2024-02-19 | Monte             | L   | 0.075      | -            | -                | -                | -         |    -0.71 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4176 | 2024-02-19 | Astralis          | L   | 0.074      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,386.03)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.561 | $1,000.00      | $561.39         |
| 2024-03-25 |      0.308 | $4,300.00      | $1,324.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
