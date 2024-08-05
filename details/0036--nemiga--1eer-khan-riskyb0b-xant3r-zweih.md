### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1152.3<br />
<br />
Final Rank Value (1152.3) = Starting Rank Value (1171.0) + Head To Head Adjustments (-18.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.667[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.333[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.377<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1171.0
- 400 + ( ( 0.377 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1171.0


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
|           57 |       11 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.423 (0.211)    | 0.792 (0.396)    | 0 (0.000) |    26.32 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       44 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -24.05 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       86 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.91 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |       91 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.01 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      158 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      218 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      569 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -21.05 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      603 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.29 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      669 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.48 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      731 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.38 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      776 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.39 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1031 | 2024-06-15 | Zero Tenacity     | W   | 0.864      | -            | -                | -                | 0 (0.000) |    10.51 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1069 | 2024-06-14 | System5           | W   | 0.858      | -            | -                | -                | 0 (0.000) |     1.66 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1103 | 2024-06-13 | Verdant           | W   | 0.851      | -            | -                | -                | 0 (0.000) |     5.25 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1136 | 2024-06-12 | FAVBET            | L   | 0.844      | -            | -                | -                | -         |   -23.12 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1151 | 2024-06-11 | Permitta          | W   | 0.838      | -            | -                | -                | -         |     5.44 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1161 | 2024-06-11 | Rhyno             | W   | 0.837      | -            | -                | -                | -         |     7.49 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1191 | 2024-06-10 | BLEED             | W   | 0.830      | 0.500        | 0.126 (0.052)    | -                | -         |    19.88 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1258 | 2024-06-09 | Zero Tenacity     | W   | 0.822      | 0.500        | 0.137 (0.056)    | 1.000 (0.411)    | -         |    10.98 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1419 | 2024-06-06 | Sampi             | W   | 0.804      | 0.500        | -                | 1.000 (0.402)    | -         |     6.13 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1523 | 2024-06-04 | CYBERSHOKE        | W   | 0.791      | -            | -                | -                | -         |     4.86 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1571 | 2024-06-02 | Grannys Knockers  | L   | 0.777      | -            | -                | -                | -         |   -21.57 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1663 | 2024-05-30 | DMS               | L   | 0.757      | -            | -                | -                | -         |   -18.76 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2255 | 2024-05-10 | RUBY              | L   | 0.622      | -            | -                | -                | -         |   -15.49 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2301 | 2024-05-08 | 1WIN              | L   | 0.609      | -            | -                | -                | -         |   -14.92 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2319 | 2024-05-07 | SINNERS           | W   | 0.603      | -            | -                | -                | -         |     6.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2345 | 2024-05-05 | VP.Prodigy        | W   | 0.591      | -            | -                | -                | -         |     2.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2381 | 2024-05-03 | MOUZ NXT          | W   | 0.577      | 0.500        | 0.139 (0.040)    | 1.000 (0.289)    | -         |     5.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2406 | 2024-05-02 | Passion UA        | W   | 0.571      | 0.500        | 0.172 (0.049)    | 1.000 (0.285)    | -         |     5.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2424 | 2024-05-01 | B8                | W   | 0.565      | 0.500        | 0.165 (0.047)    | 0.951 (0.268)    | -         |     5.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2470 | 2024-04-29 | MOUZ NXT          | W   | 0.551      | 0.500        | 0.139 (0.038)    | 1.000 (0.276)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2502 | 2024-04-28 | Grannys Knockers  | L   | 0.542      | -            | -                | -                | -         |   -15.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2524 | 2024-04-27 | 1WIN              | W   | 0.537      | -            | -                | -                | -         |     3.80 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2550 | 2024-04-26 | Sangal            | L   | 0.530      | -            | -                | -                | -         |    -9.62 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2591 | 2024-04-24 | BLEED             | W   | 0.517      | -            | -                | -                | -         |     5.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2615 | 2024-04-23 | Zero Tenacity     | W   | 0.510      | 0.500        | 0.137 (0.035)    | 1.000 (0.255)    | -         |     5.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2636 | 2024-04-22 | MOUZ NXT          | W   | 0.502      | 0.500        | -                | 1.000 (0.251)    | -         |     5.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2651 | 2024-04-21 | 1WIN              | W   | 0.496      | -            | -                | -                | -         |     3.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2684 | 2024-04-20 | Gaimin Gladiators | L   | 0.489      | -            | -                | -                | -         |   -10.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2719 | 2024-04-19 | Sangal            | W   | 0.484      | 0.500        | 0.219 (0.053)    | -                | -         |     7.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2769 | 2024-04-18 | Secret            | W   | 0.477      | -            | -                | -                | -         |     0.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2806 | 2024-04-17 | Alliance          | W   | 0.471      | -            | -                | -                | -         |     2.23 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2998 | 2024-04-09 | FlyQuest          | L   | 0.421      | -            | -                | -                | -         |    -6.65 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3046 | 2024-04-09 | Steel Helmet      | W   | 0.415      | -            | -                | -                | 1 (0.415) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3075 | 2024-04-08 | FaZe              | L   | 0.409      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3268 | 2024-04-01 | Zero Tenacity     | W   | 0.362      | -            | -                | -                | -         |     4.65 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3400 | 2024-03-22 | Sashi             | L   | 0.298      | -            | -                | -                | -         |    -5.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3637 | 2024-03-12 | Nexus             | L   | 0.231      | -            | -                | -                | -         |    -6.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3666 | 2024-03-11 | Sashi             | W   | 0.224      | -            | -                | -                | -         |     3.15 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3681 | 2024-03-10 | Endpoint          | W   | 0.217      | -            | -                | -                | -         |     1.16 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3753 | 2024-03-07 | Zero Tenacity     | W   | 0.198      | -            | -                | -                | -         |     2.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3815 | 2024-03-05 | KOI               | L   | 0.185      | -            | -                | -                | -         |    -3.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3822 | 2024-03-05 | GUN5              | W   | 0.184      | -            | -                | -                | -         |     0.08 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4339 | 2024-02-10 | Sashi             | W   | 0.025      | -            | -                | -                | -         |     0.39 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4355 | 2024-02-09 | AMKAL             | W   | 0.018      | -            | -                | -                | -         |     0.27 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4370 | 2024-02-08 | Sashi             | W   | 0.012      | -            | -                | -                | -         |     0.18 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4376 | 2024-02-08 | BetBoom           | W   | 0.010      | -            | -                | -                | -         |     0.26 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102,343.28)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.837 | $50,000.00     | $41,861.11      |
| 2024-05-09 |      0.616 | $4,000.00      | $2,465.56       |
| 2024-05-03 |      0.577 | $50,000.00     | $28,861.11      |
| 2024-04-24 |      0.517 | $50,000.00     | $25,861.11      |
| 2024-04-14 |      0.449 | $5,000.00      | $2,246.64       |
| 2024-03-25 |      0.318 | $3,300.00      | $1,047.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
