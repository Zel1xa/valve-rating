### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1117.3<br />
<br />
Final Rank Value (1117.3) = Starting Rank Value (1149.1) + Head To Head Adjustments (-31.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.667[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1149.1
- 400 + ( ( 0.366 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1149.1


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
|           56 |       18 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.64 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       60 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.70 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |       65 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.82 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      130 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.88 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      190 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.45 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      541 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.75 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      572 | 2024-07-18 | PERA              | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | 0 (0.000) |     8.73 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      641 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.15 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      702 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.72 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      751 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.72 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1003 | 2024-06-15 | Zero Tenacity     | W   | 0.868      | -            | -                | -                | 0 (0.000) |    10.98 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1041 | 2024-06-14 | System5           | W   | 0.861      | -            | -                | -                | 0 (0.000) |     1.78 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1075 | 2024-06-13 | Verdant           | W   | 0.855      | -            | -                | -                | 0 (0.000) |     5.55 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1108 | 2024-06-12 | FAVBET            | L   | 0.848      | -            | -                | -                | -         |   -22.98 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1123 | 2024-06-11 | Permitta          | W   | 0.842      | -            | -                | -                | 0 (0.000) |     5.76 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1133 | 2024-06-11 | Rhyno             | W   | 0.841      | -            | -                | -                | -         |     7.93 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1163 | 2024-06-10 | BLEED             | W   | 0.833      | 0.500        | 0.126 (0.053)    | -                | -         |    20.29 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1230 | 2024-06-09 | Zero Tenacity     | W   | 0.826      | 0.500        | 0.137 (0.057)    | 1.000 (0.413)    | -         |    11.53 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1391 | 2024-06-06 | Sampi             | W   | 0.807      | 0.500        | -                | 1.000 (0.404)    | -         |     6.50 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1495 | 2024-06-04 | CYBERSHOKE        | W   | 0.794      | -            | -                | -                | -         |     5.21 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1543 | 2024-06-02 | Grannys Knockers  | L   | 0.780      | -            | -                | -                | -         |   -21.45 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1635 | 2024-05-30 | DMS               | L   | 0.760      | -            | -                | -                | -         |   -18.50 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2227 | 2024-05-10 | RUBY              | L   | 0.626      | -            | -                | -                | -         |   -15.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2273 | 2024-05-08 | 1WIN              | L   | 0.612      | -            | -                | -                | -         |   -14.81 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2291 | 2024-05-07 | SINNERS           | W   | 0.606      | -            | -                | -                | -         |     6.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2317 | 2024-05-05 | VP.Prodigy        | W   | 0.594      | -            | -                | -                | -         |     2.96 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2353 | 2024-05-03 | MOUZ NXT          | W   | 0.581      | 0.500        | 0.139 (0.040)    | 1.000 (0.290)    | -         |     6.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2378 | 2024-05-02 | Passion UA        | W   | 0.574      | 0.500        | 0.172 (0.049)    | 1.000 (0.287)    | -         |     5.98 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2396 | 2024-05-01 | B8                | W   | 0.568      | 0.500        | 0.165 (0.047)    | 0.912 (0.259)    | -         |     6.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2442 | 2024-04-29 | MOUZ NXT          | W   | 0.555      | 0.500        | 0.139 (0.039)    | 1.000 (0.277)    | -         |     6.23 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2474 | 2024-04-28 | Grannys Knockers  | L   | 0.546      | -            | -                | -                | -         |   -15.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2496 | 2024-04-27 | 1WIN              | W   | 0.540      | -            | -                | -                | -         |     4.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2522 | 2024-04-26 | Sangal            | L   | 0.533      | -            | -                | -                | -         |    -9.36 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2563 | 2024-04-24 | BLEED             | W   | 0.521      | -            | -                | -                | -         |     5.94 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2587 | 2024-04-23 | Zero Tenacity     | W   | 0.513      | 0.500        | 0.137 (0.035)    | 1.000 (0.257)    | -         |     6.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2608 | 2024-04-22 | MOUZ NXT          | W   | 0.506      | 0.500        | 0.139 (0.035)    | 1.000 (0.253)    | -         |     5.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2623 | 2024-04-21 | 1WIN              | W   | 0.500      | -            | -                | -                | -         |     3.80 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2656 | 2024-04-20 | Gaimin Gladiators | L   | 0.493      | -            | -                | -                | -         |   -10.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2691 | 2024-04-19 | Sangal            | W   | 0.487      | 0.500        | 0.219 (0.053)    | -                | -         |     7.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2741 | 2024-04-18 | Secret            | W   | 0.481      | -            | -                | -                | -         |     0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2778 | 2024-04-17 | Alliance          | W   | 0.474      | -            | -                | -                | -         |     2.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2970 | 2024-04-09 | FlyQuest          | L   | 0.425      | -            | -                | -                | -         |    -6.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3018 | 2024-04-09 | Steel Helmet      | W   | 0.419      | -            | -                | -                | 1 (0.419) |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3047 | 2024-04-08 | FaZe              | L   | 0.412      | -            | -                | -                | -         |    -0.57 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3240 | 2024-04-01 | Zero Tenacity     | W   | 0.366      | -            | -                | -                | -         |     4.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3372 | 2024-03-22 | Sashi             | L   | 0.302      | -            | -                | -                | -         |    -4.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3609 | 2024-03-12 | Nexus             | L   | 0.235      | -            | -                | -                | -         |    -6.31 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3638 | 2024-03-11 | Sashi             | W   | 0.227      | -            | -                | -                | -         |     3.40 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3653 | 2024-03-10 | Endpoint          | W   | 0.221      | -            | -                | -                | -         |     1.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3725 | 2024-03-07 | Zero Tenacity     | W   | 0.201      | -            | -                | -                | -         |     2.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3787 | 2024-03-05 | KOI               | L   | 0.188      | -            | -                | -                | -         |    -3.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3794 | 2024-03-05 | GUN5              | W   | 0.188      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4311 | 2024-02-10 | Sashi             | W   | 0.029      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4327 | 2024-02-09 | AMKAL             | W   | 0.022      | -            | -                | -                | -         |     0.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4342 | 2024-02-08 | Sashi             | W   | 0.015      | -            | -                | -                | -         |     0.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4348 | 2024-02-08 | BetBoom           | W   | 0.014      | -            | -                | -                | -         |     0.36 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102,903.07)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.841 | $50,000.00     | $42,033.56      |
| 2024-05-09 |      0.620 | $4,000.00      | $2,479.35       |
| 2024-05-03 |      0.581 | $50,000.00     | $29,033.56      |
| 2024-04-24 |      0.521 | $50,000.00     | $26,033.56      |
| 2024-04-14 |      0.453 | $5,000.00      | $2,263.89       |
| 2024-03-25 |      0.321 | $3,300.00      | $1,059.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
