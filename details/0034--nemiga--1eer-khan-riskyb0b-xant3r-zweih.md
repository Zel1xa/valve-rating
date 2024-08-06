### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.3<br />
<br />
Final Rank Value (1155.3) = Starting Rank Value (1168.9) + Head To Head Adjustments (-13.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.374<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1168.9
- 400 + ( ( 0.374 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1168.9


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
|           57 |       51 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.420 (0.210)    | 0.758 (0.379)    | 0 (0.000) |    26.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       84 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.67 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |      127 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.96 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      131 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.95 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      198 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.76 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      258 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      609 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.86 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      643 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.23 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      709 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.32 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      771 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.28 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      816 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | 0 (0.000) |     9.56 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1071 | 2024-06-15 | Zero Tenacity     | W   | 0.854      | -            | -                | -                | 0 (0.000) |    10.55 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1109 | 2024-06-14 | System5           | W   | 0.847      | -            | -                | -                | 0 (0.000) |     1.64 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1143 | 2024-06-13 | Verdant           | W   | 0.841      | -            | -                | -                | 0 (0.000) |     5.28 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1176 | 2024-06-12 | FAVBET            | L   | 0.834      | -            | -                | -                | -         |   -22.76 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1191 | 2024-06-11 | Permitta          | W   | 0.828      | -            | -                | -                | -         |     5.74 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1201 | 2024-06-11 | Rhyno             | W   | 0.827      | -            | -                | -                | -         |     7.50 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1231 | 2024-06-10 | BLEED             | W   | 0.819      | 0.500        | 0.126 (0.051)    | -                | -         |    19.77 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1298 | 2024-06-09 | Zero Tenacity     | W   | 0.812      | 0.500        | 0.143 (0.058)    | 1.000 (0.406)    | -         |    11.03 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1459 | 2024-06-06 | Sampi             | W   | 0.794      | 0.500        | -                | 1.000 (0.397)    | -         |     6.27 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1563 | 2024-06-04 | CYBERSHOKE        | W   | 0.780      | -            | -                | -                | -         |     4.81 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1611 | 2024-06-02 | Grannys Knockers  | L   | 0.767      | -            | -                | -                | -         |   -21.28 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1703 | 2024-05-30 | DMS               | L   | 0.747      | -            | -                | -                | -         |   -18.44 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2295 | 2024-05-10 | RUBY              | L   | 0.612      | -            | -                | -                | -         |   -15.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2341 | 2024-05-08 | 1WIN              | L   | 0.599      | -            | -                | -                | -         |   -14.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2359 | 2024-05-07 | SINNERS           | W   | 0.592      | -            | -                | -                | -         |     6.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2385 | 2024-05-05 | VP.Prodigy        | W   | 0.580      | -            | -                | -                | -         |     2.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2421 | 2024-05-03 | MOUZ NXT          | W   | 0.567      | 0.500        | 0.139 (0.039)    | 0.962 (0.273)    | -         |     5.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2446 | 2024-05-02 | Passion UA        | W   | 0.560      | 0.500        | 0.173 (0.049)    | 1.000 (0.280)    | -         |     5.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2464 | 2024-05-01 | B8                | W   | 0.554      | 0.500        | 0.170 (0.047)    | 0.912 (0.253)    | -         |     5.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2510 | 2024-04-29 | MOUZ NXT          | W   | 0.541      | 0.500        | 0.139 (0.037)    | 0.962 (0.260)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2542 | 2024-04-28 | Grannys Knockers  | L   | 0.532      | -            | -                | -                | -         |   -15.23 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2564 | 2024-04-27 | 1WIN              | W   | 0.526      | -            | -                | -                | -         |     3.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2590 | 2024-04-26 | Sangal            | L   | 0.519      | -            | -                | -                | -         |    -9.23 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2631 | 2024-04-24 | BLEED             | W   | 0.507      | -            | -                | -                | -         |     5.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2655 | 2024-04-23 | Zero Tenacity     | W   | 0.499      | 0.500        | 0.143 (0.036)    | 1.000 (0.250)    | -         |     5.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2676 | 2024-04-22 | MOUZ NXT          | W   | 0.492      | 0.500        | -                | 0.962 (0.236)    | -         |     5.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2691 | 2024-04-21 | 1WIN              | W   | 0.486      | -            | -                | -                | -         |     3.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2724 | 2024-04-20 | Gaimin Gladiators | L   | 0.479      | -            | -                | -                | -         |   -10.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2759 | 2024-04-19 | Sangal            | W   | 0.474      | 0.500        | 0.219 (0.052)    | -                | -         |     7.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2809 | 2024-04-18 | Secret            | W   | 0.467      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2846 | 2024-04-17 | Alliance          | W   | 0.460      | -            | -                | -                | -         |     2.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     3038 | 2024-04-09 | FlyQuest          | L   | 0.411      | -            | -                | -                | -         |    -6.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3086 | 2024-04-09 | Steel Helmet      | W   | 0.405      | -            | -                | -                | 1 (0.405) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3115 | 2024-04-08 | FaZe              | L   | 0.398      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3308 | 2024-04-01 | Zero Tenacity     | W   | 0.352      | -            | -                | -                | -         |     4.58 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3440 | 2024-03-22 | Sashi             | L   | 0.288      | -            | -                | -                | -         |    -4.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3677 | 2024-03-12 | Nexus             | L   | 0.221      | -            | -                | -                | -         |    -6.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3706 | 2024-03-11 | Sashi             | W   | 0.213      | -            | -                | -                | -         |     3.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3721 | 2024-03-10 | Endpoint          | W   | 0.207      | -            | -                | -                | -         |     1.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3793 | 2024-03-07 | Zero Tenacity     | W   | 0.187      | -            | -                | -                | -         |     2.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3855 | 2024-03-05 | KOI               | L   | 0.174      | -            | -                | -                | -         |    -3.44 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3862 | 2024-03-05 | GUN5              | W   | 0.174      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4379 | 2024-02-10 | Sashi             | W   | 0.015      | -            | -                | -                | -         |     0.23 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4395 | 2024-02-09 | AMKAL             | W   | 0.008      | -            | -                | -                | -         |     0.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4410 | 2024-02-08 | Sashi             | W   | 0.001      | -            | -                | -                | -         |     0.02 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4416 | 2024-02-08 | BetBoom           | W   | 0.000      | -            | -                | -                | -         |     0.00 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100,660.17)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.827 | $50,000.00     | $41,342.59      |
| 2024-05-09 |      0.606 | $4,000.00      | $2,424.07       |
| 2024-05-03 |      0.567 | $50,000.00     | $28,342.59      |
| 2024-04-24 |      0.507 | $50,000.00     | $25,342.59      |
| 2024-04-14 |      0.439 | $5,000.00      | $2,194.79       |
| 2024-03-25 |      0.307 | $3,300.00      | $1,013.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
