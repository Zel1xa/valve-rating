### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1158.0<br />
<br />
Final Rank Value (1158.0) = Starting Rank Value (1163.2) + Head To Head Adjustments (-5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.672[<sup>1</sup>](#table2)
- Bounty Collected: 0.437[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.051[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1163.2
- 400 + ( ( 0.371 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1163.2


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
|           54 |       32 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.99 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |       94 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.46 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      450 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.91 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      485 | 2024-07-18 | PERA              | W   | 1.000      | 0.500        | -                | 0.452 (0.226)    | 0 (0.000) |     8.69 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      554 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -8.83 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      617 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.75 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      667 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.49 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      921 | 2024-06-15 | Zero Tenacity     | W   | 0.888      | -            | -                | -                | 0 (0.000) |     9.39 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           46 |      952 | 2024-06-14 | System5           | W   | 0.881      | -            | -                | -                | 0 (0.000) |     1.86 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |      985 | 2024-06-13 | Verdant           | W   | 0.875      | -            | -                | -                | 0 (0.000) |     5.83 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1018 | 2024-06-12 | FAVBET            | L   | 0.868      | -            | -                | -                | -         |   -23.41 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1034 | 2024-06-11 | Permitta          | W   | 0.862      | -            | -                | -                | 0 (0.000) |     5.89 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1044 | 2024-06-11 | Rhyno             | W   | 0.861      | -            | -                | -                | -         |     8.49 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           41 |     1075 | 2024-06-10 | BLEED             | W   | 0.853      | 0.500        | 0.128 (0.055)    | -                | -         |    21.04 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1143 | 2024-06-09 | Zero Tenacity     | W   | 0.846      | 0.500        | 0.139 (0.059)    | 1.000 (0.423)    | -         |    10.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1314 | 2024-06-06 | Sampi             | W   | 0.828      | 0.500        | -                | 1.000 (0.414)    | -         |     6.56 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1421 | 2024-06-04 | CYBERSHOKE        | W   | 0.814      | -            | -                | -                | -         |     5.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1470 | 2024-06-02 | Grannys Knockers  | L   | 0.801      | -            | -                | -                | -         |   -21.90 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           36 |     1562 | 2024-05-30 | DMS               | L   | 0.781      | -            | -                | -                | -         |   -18.90 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     2191 | 2024-05-10 | RUBY              | L   | 0.646      | -            | -                | -                | -         |   -15.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           34 |     2239 | 2024-05-08 | 1WIN              | L   | 0.633      | -            | -                | -                | -         |   -15.57 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2257 | 2024-05-07 | SINNERS           | W   | 0.626      | -            | -                | -                | -         |     5.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2283 | 2024-05-05 | VP.Prodigy        | W   | 0.614      | -            | -                | -                | -         |     3.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2319 | 2024-05-03 | MOUZ NXT          | W   | 0.601      | 0.500        | 0.141 (0.042)    | 1.000 (0.300)    | -         |     5.83 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2345 | 2024-05-02 | Passion UA        | W   | 0.594      | 0.500        | 0.172 (0.051)    | 1.000 (0.297)    | -         |     6.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2364 | 2024-05-01 | B8                | W   | 0.588      | 0.500        | 0.168 (0.049)    | 0.878 (0.258)    | -         |     6.39 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2411 | 2024-04-29 | MOUZ NXT          | W   | 0.575      | 0.500        | 0.141 (0.041)    | 1.000 (0.287)    | -         |     6.79 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2443 | 2024-04-28 | Grannys Knockers  | L   | 0.566      | -            | -                | -                | -         |   -15.95 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2466 | 2024-04-27 | 1WIN              | W   | 0.560      | -            | -                | -                | -         |     3.87 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2490 | 2024-04-26 | Sangal            | L   | 0.553      | -            | -                | -                | -         |    -9.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2532 | 2024-04-24 | BLEED             | W   | 0.541      | -            | -                | -                | -         |     6.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2551 | 2024-04-23 | SINNERS           | L   | 0.535      | -            | -                | -                | -         |   -10.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2558 | 2024-04-23 | Zero Tenacity     | W   | 0.533      | 0.500        | 0.139 (0.037)    | 1.000 (0.267)    | -         |     6.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2580 | 2024-04-22 | MOUZ NXT          | W   | 0.526      | 0.500        | 0.141 (0.037)    | 1.000 (0.263)    | -         |     5.96 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2596 | 2024-04-21 | 1WIN              | W   | 0.520      | -            | -                | -                | -         |     3.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2631 | 2024-04-20 | Gaimin Gladiators | L   | 0.513      | -            | -                | -                | -         |   -10.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2667 | 2024-04-19 | Sangal            | W   | 0.507      | 0.500        | 0.221 (0.056)    | -                | -         |     7.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2718 | 2024-04-18 | Secret            | W   | 0.501      | -            | -                | -                | -         |     0.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2756 | 2024-04-17 | Alliance          | W   | 0.494      | -            | -                | -                | -         |     2.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2950 | 2024-04-09 | FlyQuest          | L   | 0.445      | -            | -                | -                | -         |    -6.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     2998 | 2024-04-09 | Steel Helmet      | W   | 0.439      | -            | -                | -                | 1 (0.439) |     0.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3027 | 2024-04-08 | FaZe              | L   | 0.432      | -            | -                | -                | -         |    -0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3228 | 2024-04-01 | Zero Tenacity     | W   | 0.386      | -            | -                | -                | -         |     5.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3365 | 2024-03-22 | Sashi             | L   | 0.322      | -            | -                | -                | -         |    -5.38 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3607 | 2024-03-12 | Nexus             | L   | 0.255      | -            | -                | -                | -         |    -6.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3636 | 2024-03-11 | Sashi             | W   | 0.247      | -            | -                | -                | -         |     3.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3651 | 2024-03-10 | Endpoint          | W   | 0.241      | -            | -                | -                | -         |     1.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3724 | 2024-03-07 | Zero Tenacity     | W   | 0.221      | -            | -                | -                | -         |     2.86 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3786 | 2024-03-05 | KOI               | L   | 0.208      | -            | -                | -                | -         |    -5.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3798 | 2024-03-05 | GUN5              | W   | 0.208      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4334 | 2024-02-10 | Sashi             | W   | 0.049      | -            | -                | -                | -         |     0.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4350 | 2024-02-09 | AMKAL             | W   | 0.042      | -            | -                | -                | -         |     0.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4366 | 2024-02-08 | Sashi             | W   | 0.035      | -            | -                | -                | -         |     0.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4372 | 2024-02-08 | BetBoom           | W   | 0.034      | -            | -                | -                | -         |     0.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,175.37)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.861 | $50,000.00     | $43,041.67      |
| 2024-05-09 |      0.640 | $4,000.00      | $2,560.00       |
| 2024-05-03 |      0.601 | $50,000.00     | $30,041.67      |
| 2024-04-24 |      0.541 | $50,000.00     | $27,041.67      |
| 2024-04-14 |      0.473 | $5,000.00      | $2,364.70       |
| 2024-03-25 |      0.341 | $3,300.00      | $1,125.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
