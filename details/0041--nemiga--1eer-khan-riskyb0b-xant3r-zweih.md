### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1116.5<br />
<br />
Final Rank Value (1116.5) = Starting Rank Value (1150.0) + Head To Head Adjustments (-33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.668[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.367<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1150.0
- 400 + ( ( 0.367 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1150.0


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
|           56 |        7 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.80 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       50 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.73 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |       54 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.81 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      119 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      179 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.46 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      530 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.88 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      561 | 2024-07-18 | PERA              | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | 0 (0.000) |     8.69 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      630 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.19 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      691 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.73 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      740 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.60 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |      991 | 2024-06-15 | Zero Tenacity     | W   | 0.872      | -            | -                | -                | 0 (0.000) |    11.01 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1029 | 2024-06-14 | System5           | W   | 0.865      | -            | -                | -                | 0 (0.000) |     1.79 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1063 | 2024-06-13 | Verdant           | W   | 0.859      | -            | -                | -                | 0 (0.000) |     5.57 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1096 | 2024-06-12 | FAVBET            | L   | 0.852      | -            | -                | -                | -         |   -23.11 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1111 | 2024-06-11 | Permitta          | W   | 0.845      | -            | -                | -                | 0 (0.000) |     5.78 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1121 | 2024-06-11 | Rhyno             | W   | 0.844      | -            | -                | -                | -         |     7.99 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1151 | 2024-06-10 | BLEED             | W   | 0.837      | 0.500        | 0.126 (0.053)    | -                | -         |    20.36 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1218 | 2024-06-09 | Zero Tenacity     | W   | 0.829      | 0.500        | 0.137 (0.057)    | 1.000 (0.415)    | -         |    11.57 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1379 | 2024-06-06 | Sampi             | W   | 0.811      | 0.500        | -                | 1.000 (0.406)    | -         |     6.53 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1483 | 2024-06-04 | CYBERSHOKE        | W   | 0.798      | -            | -                | -                | -         |     5.20 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1531 | 2024-06-02 | Grannys Knockers  | L   | 0.784      | -            | -                | -                | -         |   -21.55 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1623 | 2024-05-30 | DMS               | L   | 0.764      | -            | -                | -                | -         |   -18.58 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2215 | 2024-05-10 | RUBY              | L   | 0.629      | -            | -                | -                | -         |   -15.28 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2261 | 2024-05-08 | 1WIN              | L   | 0.616      | -            | -                | -                | -         |   -15.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2279 | 2024-05-07 | SINNERS           | W   | 0.610      | -            | -                | -                | -         |     6.05 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2305 | 2024-05-05 | VP.Prodigy        | W   | 0.598      | -            | -                | -                | -         |     2.98 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2341 | 2024-05-03 | MOUZ NXT          | W   | 0.584      | 0.500        | 0.139 (0.041)    | 1.000 (0.292)    | -         |     6.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2366 | 2024-05-02 | Passion UA        | W   | 0.578      | 0.500        | 0.172 (0.050)    | 1.000 (0.289)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2384 | 2024-05-01 | B8                | W   | 0.572      | 0.500        | 0.165 (0.047)    | 0.913 (0.261)    | -         |     6.27 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2430 | 2024-04-29 | MOUZ NXT          | W   | 0.559      | 0.500        | 0.139 (0.039)    | 1.000 (0.279)    | -         |     6.26 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2462 | 2024-04-28 | Grannys Knockers  | L   | 0.550      | -            | -                | -                | -         |   -15.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2484 | 2024-04-27 | 1WIN              | W   | 0.544      | -            | -                | -                | -         |     3.70 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2509 | 2024-04-26 | Sangal            | L   | 0.537      | -            | -                | -                | -         |    -9.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2550 | 2024-04-24 | BLEED             | W   | 0.524      | -            | -                | -                | -         |     6.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2574 | 2024-04-23 | Zero Tenacity     | W   | 0.517      | 0.500        | 0.137 (0.035)    | 1.000 (0.258)    | -         |     6.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2595 | 2024-04-22 | MOUZ NXT          | W   | 0.509      | 0.500        | 0.139 (0.035)    | 1.000 (0.255)    | -         |     5.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2610 | 2024-04-21 | 1WIN              | W   | 0.503      | -            | -                | -                | -         |     3.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2643 | 2024-04-20 | Gaimin Gladiators | L   | 0.497      | -            | -                | -                | -         |   -10.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2678 | 2024-04-19 | Sangal            | W   | 0.491      | 0.500        | 0.219 (0.054)    | -                | -         |     7.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2728 | 2024-04-18 | Secret            | W   | 0.485      | -            | -                | -                | -         |     0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2765 | 2024-04-17 | Alliance          | W   | 0.478      | -            | -                | -                | -         |     2.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2957 | 2024-04-09 | FlyQuest          | L   | 0.428      | -            | -                | -                | -         |    -6.36 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3005 | 2024-04-09 | Steel Helmet      | W   | 0.423      | -            | -                | -                | 1 (0.423) |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3034 | 2024-04-08 | FaZe              | L   | 0.416      | -            | -                | -                | -         |    -0.57 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3227 | 2024-04-01 | Zero Tenacity     | W   | 0.370      | -            | -                | -                | -         |     5.02 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3359 | 2024-03-22 | Sashi             | L   | 0.305      | -            | -                | -                | -         |    -5.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3595 | 2024-03-12 | Nexus             | L   | 0.239      | -            | -                | -                | -         |    -6.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3624 | 2024-03-11 | Sashi             | W   | 0.231      | -            | -                | -                | -         |     3.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3639 | 2024-03-10 | Endpoint          | W   | 0.225      | -            | -                | -                | -         |     1.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3711 | 2024-03-07 | Zero Tenacity     | W   | 0.205      | -            | -                | -                | -         |     2.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3773 | 2024-03-05 | KOI               | L   | 0.192      | -            | -                | -                | -         |    -3.59 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3780 | 2024-03-05 | GUN5              | W   | 0.192      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4296 | 2024-02-10 | Sashi             | W   | 0.033      | -            | -                | -                | -         |     0.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4312 | 2024-02-09 | AMKAL             | W   | 0.025      | -            | -                | -                | -         |     0.40 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4327 | 2024-02-08 | Sashi             | W   | 0.019      | -            | -                | -                | -         |     0.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4333 | 2024-02-08 | BetBoom           | W   | 0.018      | -            | -                | -                | -         |     0.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,515.45)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.844 | $50,000.00     | $42,222.22      |
| 2024-05-09 |      0.624 | $4,000.00      | $2,494.44       |
| 2024-05-03 |      0.584 | $50,000.00     | $29,222.22      |
| 2024-04-24 |      0.524 | $50,000.00     | $26,222.22      |
| 2024-04-14 |      0.457 | $5,000.00      | $2,282.75       |
| 2024-03-25 |      0.325 | $3,300.00      | $1,071.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
