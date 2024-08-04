### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1116.2<br />
<br />
Final Rank Value (1116.2) = Starting Rank Value (1149.3) + Head To Head Adjustments (-33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.667[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1149.3
- 400 + ( ( 0.366 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1149.3


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
|           56 |       10 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.80 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       53 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.72 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |       57 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.80 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      122 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      182 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.46 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      533 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.78 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      564 | 2024-07-18 | PERA              | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | 0 (0.000) |     8.69 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      633 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.17 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      694 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.73 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      743 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.72 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |      995 | 2024-06-15 | Zero Tenacity     | W   | 0.869      | -            | -                | -                | 0 (0.000) |    10.99 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1033 | 2024-06-14 | System5           | W   | 0.862      | -            | -                | -                | 0 (0.000) |     1.79 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1067 | 2024-06-13 | Verdant           | W   | 0.856      | -            | -                | -                | 0 (0.000) |     5.56 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1100 | 2024-06-12 | FAVBET            | L   | 0.849      | -            | -                | -                | -         |   -23.03 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1115 | 2024-06-11 | Permitta          | W   | 0.842      | -            | -                | -                | 0 (0.000) |     5.77 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1125 | 2024-06-11 | Rhyno             | W   | 0.841      | -            | -                | -                | -         |     7.96 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1155 | 2024-06-10 | BLEED             | W   | 0.834      | 0.500        | 0.126 (0.053)    | -                | -         |    20.30 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1222 | 2024-06-09 | Zero Tenacity     | W   | 0.826      | 0.500        | 0.137 (0.057)    | 1.000 (0.413)    | -         |    11.54 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1383 | 2024-06-06 | Sampi             | W   | 0.808      | 0.500        | -                | 1.000 (0.404)    | -         |     6.51 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1487 | 2024-06-04 | CYBERSHOKE        | W   | 0.795      | -            | -                | -                | -         |     5.20 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1535 | 2024-06-02 | Grannys Knockers  | L   | 0.781      | -            | -                | -                | -         |   -21.46 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1627 | 2024-05-30 | DMS               | L   | 0.761      | -            | -                | -                | -         |   -18.50 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2219 | 2024-05-10 | RUBY              | L   | 0.626      | -            | -                | -                | -         |   -15.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2265 | 2024-05-08 | 1WIN              | L   | 0.613      | -            | -                | -                | -         |   -15.16 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2283 | 2024-05-07 | SINNERS           | W   | 0.607      | -            | -                | -                | -         |     6.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2309 | 2024-05-05 | VP.Prodigy        | W   | 0.595      | -            | -                | -                | -         |     2.97 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2345 | 2024-05-03 | MOUZ NXT          | W   | 0.581      | 0.500        | 0.139 (0.040)    | 1.000 (0.291)    | -         |     6.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2370 | 2024-05-02 | Passion UA        | W   | 0.575      | 0.500        | 0.172 (0.049)    | 1.000 (0.287)    | -         |     5.98 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2388 | 2024-05-01 | B8                | W   | 0.569      | 0.500        | 0.165 (0.047)    | 0.912 (0.259)    | -         |     6.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2434 | 2024-04-29 | MOUZ NXT          | W   | 0.556      | 0.500        | 0.139 (0.039)    | 1.000 (0.278)    | -         |     6.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2466 | 2024-04-28 | Grannys Knockers  | L   | 0.547      | -            | -                | -                | -         |   -15.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2488 | 2024-04-27 | 1WIN              | W   | 0.541      | -            | -                | -                | -         |     3.68 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2514 | 2024-04-26 | Sangal            | L   | 0.534      | -            | -                | -                | -         |    -9.39 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2555 | 2024-04-24 | BLEED             | W   | 0.521      | -            | -                | -                | -         |     5.96 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2579 | 2024-04-23 | Zero Tenacity     | W   | 0.514      | 0.500        | 0.137 (0.035)    | 1.000 (0.257)    | -         |     6.31 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2600 | 2024-04-22 | MOUZ NXT          | W   | 0.506      | 0.500        | 0.139 (0.035)    | 1.000 (0.253)    | -         |     5.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2615 | 2024-04-21 | 1WIN              | W   | 0.500      | -            | -                | -                | -         |     3.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2648 | 2024-04-20 | Gaimin Gladiators | L   | 0.493      | -            | -                | -                | -         |   -10.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2683 | 2024-04-19 | Sangal            | W   | 0.488      | 0.500        | 0.219 (0.053)    | -                | -         |     7.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2733 | 2024-04-18 | Secret            | W   | 0.482      | -            | -                | -                | -         |     0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2770 | 2024-04-17 | Alliance          | W   | 0.475      | -            | -                | -                | -         |     2.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2962 | 2024-04-09 | FlyQuest          | L   | 0.425      | -            | -                | -                | -         |    -6.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3010 | 2024-04-09 | Steel Helmet      | W   | 0.420      | -            | -                | -                | 1 (0.420) |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3039 | 2024-04-08 | FaZe              | L   | 0.413      | -            | -                | -                | -         |    -0.57 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3232 | 2024-04-01 | Zero Tenacity     | W   | 0.367      | -            | -                | -                | -         |     4.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3364 | 2024-03-22 | Sashi             | L   | 0.302      | -            | -                | -                | -         |    -4.96 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3601 | 2024-03-12 | Nexus             | L   | 0.236      | -            | -                | -                | -         |    -6.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3630 | 2024-03-11 | Sashi             | W   | 0.228      | -            | -                | -                | -         |     3.38 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3645 | 2024-03-10 | Endpoint          | W   | 0.222      | -            | -                | -                | -         |     1.31 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3717 | 2024-03-07 | Zero Tenacity     | W   | 0.202      | -            | -                | -                | -         |     2.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3779 | 2024-03-05 | KOI               | L   | 0.189      | -            | -                | -                | -         |    -3.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3786 | 2024-03-05 | GUN5              | W   | 0.189      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4303 | 2024-02-10 | Sashi             | W   | 0.029      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4319 | 2024-02-09 | AMKAL             | W   | 0.022      | -            | -                | -                | -         |     0.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4334 | 2024-02-08 | Sashi             | W   | 0.016      | -            | -                | -                | -         |     0.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4340 | 2024-02-08 | BetBoom           | W   | 0.015      | -            | -                | -                | -         |     0.38 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,019.53)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.841 | $50,000.00     | $42,069.44      |
| 2024-05-09 |      0.621 | $4,000.00      | $2,482.22       |
| 2024-05-03 |      0.581 | $50,000.00     | $29,069.44      |
| 2024-04-24 |      0.521 | $50,000.00     | $26,069.44      |
| 2024-04-14 |      0.453 | $5,000.00      | $2,267.48       |
| 2024-03-25 |      0.322 | $3,300.00      | $1,061.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
