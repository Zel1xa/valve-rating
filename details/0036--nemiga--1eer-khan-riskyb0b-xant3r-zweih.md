### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1152.7<br />
<br />
Final Rank Value (1152.7) = Starting Rank Value (1171.6) + Head To Head Adjustments (-18.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.667[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.334[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.377<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1171.6
- 400 + ( ( 0.377 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1171.6


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
|           57 |        6 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.423 (0.212)    | 0.793 (0.396)    | 0 (0.000) |    26.28 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       40 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -24.05 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       82 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.93 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |       87 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.03 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      154 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      214 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      565 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -21.06 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      599 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.37 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      665 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.50 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      727 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.38 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      772 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.38 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1027 | 2024-06-15 | Zero Tenacity     | W   | 0.867      | -            | -                | -                | 0 (0.000) |    10.53 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1065 | 2024-06-14 | System5           | W   | 0.860      | -            | -                | -                | 0 (0.000) |     1.66 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1099 | 2024-06-13 | Verdant           | W   | 0.854      | -            | -                | -                | 0 (0.000) |     5.25 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1132 | 2024-06-12 | FAVBET            | L   | 0.847      | -            | -                | -                | -         |   -23.19 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1147 | 2024-06-11 | Permitta          | W   | 0.840      | -            | -                | -                | -         |     5.45 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1157 | 2024-06-11 | Rhyno             | W   | 0.840      | -            | -                | -                | -         |     7.51 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1187 | 2024-06-10 | BLEED             | W   | 0.832      | 0.500        | 0.126 (0.052)    | -                | -         |    19.92 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1254 | 2024-06-09 | Zero Tenacity     | W   | 0.825      | 0.500        | 0.137 (0.056)    | 1.000 (0.412)    | -         |    11.00 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1415 | 2024-06-06 | Sampi             | W   | 0.806      | 0.500        | -                | 1.000 (0.403)    | -         |     6.14 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1519 | 2024-06-04 | CYBERSHOKE        | W   | 0.793      | -            | -                | -                | -         |     4.86 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1567 | 2024-06-02 | Grannys Knockers  | L   | 0.779      | -            | -                | -                | -         |   -21.64 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1659 | 2024-05-30 | DMS               | L   | 0.759      | -            | -                | -                | -         |   -18.83 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2251 | 2024-05-10 | RUBY              | L   | 0.625      | -            | -                | -                | -         |   -15.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2297 | 2024-05-08 | 1WIN              | L   | 0.611      | -            | -                | -                | -         |   -14.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2315 | 2024-05-07 | SINNERS           | W   | 0.605      | -            | -                | -                | -         |     6.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2341 | 2024-05-05 | VP.Prodigy        | W   | 0.593      | -            | -                | -                | -         |     2.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2377 | 2024-05-03 | MOUZ NXT          | W   | 0.580      | 0.500        | 0.139 (0.040)    | 1.000 (0.290)    | -         |     5.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2402 | 2024-05-02 | Passion UA        | W   | 0.573      | 0.500        | 0.172 (0.049)    | 1.000 (0.286)    | -         |     5.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2420 | 2024-05-01 | B8                | W   | 0.567      | 0.500        | 0.165 (0.047)    | 0.951 (0.270)    | -         |     5.87 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2466 | 2024-04-29 | MOUZ NXT          | W   | 0.554      | 0.500        | 0.139 (0.038)    | 1.000 (0.277)    | -         |     5.86 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2498 | 2024-04-28 | Grannys Knockers  | L   | 0.545      | -            | -                | -                | -         |   -15.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2520 | 2024-04-27 | 1WIN              | W   | 0.539      | -            | -                | -                | -         |     3.81 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2546 | 2024-04-26 | Sangal            | L   | 0.532      | -            | -                | -                | -         |    -9.68 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2587 | 2024-04-24 | BLEED             | W   | 0.520      | -            | -                | -                | -         |     5.58 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2611 | 2024-04-23 | Zero Tenacity     | W   | 0.512      | 0.500        | -                | 1.000 (0.256)    | -         |     5.92 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2632 | 2024-04-22 | MOUZ NXT          | W   | 0.505      | 0.500        | 0.139 (0.035)    | 1.000 (0.252)    | -         |     5.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2647 | 2024-04-21 | 1WIN              | W   | 0.498      | -            | -                | -                | -         |     3.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2680 | 2024-04-20 | Gaimin Gladiators | L   | 0.492      | -            | -                | -                | -         |   -10.81 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2715 | 2024-04-19 | Sangal            | W   | 0.486      | 0.500        | 0.219 (0.053)    | -                | -         |     7.08 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2765 | 2024-04-18 | Secret            | W   | 0.480      | -            | -                | -                | -         |     0.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2802 | 2024-04-17 | Alliance          | W   | 0.473      | -            | -                | -                | -         |     2.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2994 | 2024-04-09 | FlyQuest          | L   | 0.424      | -            | -                | -                | -         |    -6.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3042 | 2024-04-09 | Steel Helmet      | W   | 0.418      | -            | -                | -                | 1 (0.418) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3071 | 2024-04-08 | FaZe              | L   | 0.411      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3264 | 2024-04-01 | Zero Tenacity     | W   | 0.365      | -            | -                | -                | -         |     4.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3396 | 2024-03-22 | Sashi             | L   | 0.300      | -            | -                | -                | -         |    -5.17 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3633 | 2024-03-12 | Nexus             | L   | 0.234      | -            | -                | -                | -         |    -6.39 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3662 | 2024-03-11 | Sashi             | W   | 0.226      | -            | -                | -                | -         |     3.17 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3677 | 2024-03-10 | Endpoint          | W   | 0.220      | -            | -                | -                | -         |     1.17 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3749 | 2024-03-07 | Zero Tenacity     | W   | 0.200      | -            | -                | -                | -         |     2.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3811 | 2024-03-05 | KOI               | L   | 0.187      | -            | -                | -                | -         |    -3.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3818 | 2024-03-05 | GUN5              | W   | 0.187      | -            | -                | -                | -         |     0.08 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4335 | 2024-02-10 | Sashi             | W   | 0.028      | -            | -                | -                | -         |     0.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4351 | 2024-02-09 | AMKAL             | W   | 0.021      | -            | -                | -                | -         |     0.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4366 | 2024-02-08 | Sashi             | W   | 0.014      | -            | -                | -                | -         |     0.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4372 | 2024-02-08 | BetBoom           | W   | 0.013      | -            | -                | -                | -         |     0.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102,730.25)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.840 | $50,000.00     | $41,980.32      |
| 2024-05-09 |      0.619 | $4,000.00      | $2,475.09       |
| 2024-05-03 |      0.580 | $50,000.00     | $28,980.32      |
| 2024-04-24 |      0.520 | $50,000.00     | $25,980.32      |
| 2024-04-14 |      0.452 | $5,000.00      | $2,258.56       |
| 2024-03-25 |      0.320 | $3,300.00      | $1,055.62       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
