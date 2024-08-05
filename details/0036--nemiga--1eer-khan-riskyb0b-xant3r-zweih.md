### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1152.8<br />
<br />
Final Rank Value (1152.8) = Starting Rank Value (1170.3) + Head To Head Adjustments (-17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.332[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.376<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1170.3
- 400 + ( ( 0.376 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1170.3


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
|           57 |       23 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.422 (0.211)    | 0.788 (0.394)    | 0 (0.000) |    26.34 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       57 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -24.04 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |      100 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.91 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      104 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.98 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      171 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.63 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      231 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      582 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.95 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      616 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.29 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      682 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.41 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      744 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.38 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      789 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.51 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1044 | 2024-06-15 | Zero Tenacity     | W   | 0.861      | -            | -                | -                | 0 (0.000) |    10.50 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1082 | 2024-06-14 | System5           | W   | 0.854      | -            | -                | -                | 0 (0.000) |     1.66 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1116 | 2024-06-13 | Verdant           | W   | 0.848      | -            | -                | -                | 0 (0.000) |     5.24 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1149 | 2024-06-12 | FAVBET            | L   | 0.841      | -            | -                | -                | -         |   -23.03 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1164 | 2024-06-11 | Permitta          | W   | 0.835      | -            | -                | -                | -         |     5.42 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1174 | 2024-06-11 | Rhyno             | W   | 0.834      | -            | -                | -                | -         |     7.46 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1204 | 2024-06-10 | BLEED             | W   | 0.826      | 0.500        | 0.126 (0.052)    | -                | -         |    19.86 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1271 | 2024-06-09 | Zero Tenacity     | W   | 0.819      | 0.500        | 0.137 (0.056)    | 1.000 (0.409)    | -         |    10.96 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1432 | 2024-06-06 | Sampi             | W   | 0.801      | 0.500        | -                | 1.000 (0.400)    | -         |     6.19 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1536 | 2024-06-04 | CYBERSHOKE        | W   | 0.787      | -            | -                | -                | -         |     4.85 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1584 | 2024-06-02 | Grannys Knockers  | L   | 0.774      | -            | -                | -                | -         |   -21.48 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1676 | 2024-05-30 | DMS               | L   | 0.754      | -            | -                | -                | -         |   -18.61 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2268 | 2024-05-10 | RUBY              | L   | 0.619      | -            | -                | -                | -         |   -15.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2314 | 2024-05-08 | 1WIN              | L   | 0.606      | -            | -                | -                | -         |   -14.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2332 | 2024-05-07 | SINNERS           | W   | 0.599      | -            | -                | -                | -         |     6.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2358 | 2024-05-05 | VP.Prodigy        | W   | 0.588      | -            | -                | -                | -         |     2.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2394 | 2024-05-03 | MOUZ NXT          | W   | 0.574      | 0.500        | 0.139 (0.040)    | 1.000 (0.287)    | -         |     5.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2419 | 2024-05-02 | Passion UA        | W   | 0.567      | 0.500        | 0.173 (0.049)    | 1.000 (0.284)    | -         |     5.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2437 | 2024-05-01 | B8                | W   | 0.561      | 0.500        | 0.165 (0.046)    | 0.947 (0.266)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2483 | 2024-04-29 | MOUZ NXT          | W   | 0.548      | 0.500        | 0.139 (0.038)    | 1.000 (0.274)    | -         |     5.86 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2515 | 2024-04-28 | Grannys Knockers  | L   | 0.539      | -            | -                | -                | -         |   -15.44 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2537 | 2024-04-27 | 1WIN              | W   | 0.533      | -            | -                | -                | -         |     3.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2563 | 2024-04-26 | Sangal            | L   | 0.526      | -            | -                | -                | -         |    -9.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2604 | 2024-04-24 | BLEED             | W   | 0.514      | -            | -                | -                | -         |     5.49 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2628 | 2024-04-23 | Zero Tenacity     | W   | 0.506      | 0.500        | 0.137 (0.035)    | 1.000 (0.253)    | -         |     5.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2649 | 2024-04-22 | MOUZ NXT          | W   | 0.499      | 0.500        | -                | 1.000 (0.249)    | -         |     5.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2664 | 2024-04-21 | 1WIN              | W   | 0.493      | -            | -                | -                | -         |     3.65 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2697 | 2024-04-20 | Gaimin Gladiators | L   | 0.486      | -            | -                | -                | -         |   -10.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2732 | 2024-04-19 | Sangal            | W   | 0.481      | 0.500        | 0.219 (0.053)    | -                | -         |     7.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2782 | 2024-04-18 | Secret            | W   | 0.474      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2819 | 2024-04-17 | Alliance          | W   | 0.467      | -            | -                | -                | -         |     2.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     3011 | 2024-04-09 | FlyQuest          | L   | 0.418      | -            | -                | -                | -         |    -6.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3059 | 2024-04-09 | Steel Helmet      | W   | 0.412      | -            | -                | -                | 1 (0.412) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3088 | 2024-04-08 | FaZe              | L   | 0.405      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3281 | 2024-04-01 | Zero Tenacity     | W   | 0.359      | -            | -                | -                | -         |     4.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3413 | 2024-03-22 | Sashi             | L   | 0.295      | -            | -                | -                | -         |    -5.05 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3650 | 2024-03-12 | Nexus             | L   | 0.228      | -            | -                | -                | -         |    -6.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3679 | 2024-03-11 | Sashi             | W   | 0.220      | -            | -                | -                | -         |     3.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3694 | 2024-03-10 | Endpoint          | W   | 0.214      | -            | -                | -                | -         |     1.15 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3766 | 2024-03-07 | Zero Tenacity     | W   | 0.194      | -            | -                | -                | -         |     2.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3828 | 2024-03-05 | KOI               | L   | 0.182      | -            | -                | -                | -         |    -3.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3835 | 2024-03-05 | GUN5              | W   | 0.181      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4352 | 2024-02-10 | Sashi             | W   | 0.022      | -            | -                | -                | -         |     0.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4368 | 2024-02-09 | AMKAL             | W   | 0.015      | -            | -                | -                | -         |     0.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4383 | 2024-02-08 | Sashi             | W   | 0.008      | -            | -                | -                | -         |     0.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4389 | 2024-02-08 | BetBoom           | W   | 0.007      | -            | -                | -                | -         |     0.18 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($101,802.28)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.834 | $50,000.00     | $41,694.44      |
| 2024-05-09 |      0.613 | $4,000.00      | $2,452.22       |
| 2024-05-03 |      0.574 | $50,000.00     | $28,694.44      |
| 2024-04-24 |      0.514 | $50,000.00     | $25,694.44      |
| 2024-04-14 |      0.446 | $5,000.00      | $2,229.98       |
| 2024-03-25 |      0.314 | $3,300.00      | $1,036.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
