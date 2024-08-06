### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.4<br />
<br />
Final Rank Value (1155.4) = Starting Rank Value (1168.8) + Head To Head Adjustments (-13.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.665[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.374<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1168.8
- 400 + ( ( 0.374 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1168.8


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
|           56 |       56 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.420 (0.210)    | 0.758 (0.379)    | 0 (0.000) |    26.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       89 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.66 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      132 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.96 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      136 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.95 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      203 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.76 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      263 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      614 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.85 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      648 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.23 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      714 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.32 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      776 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.30 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |      821 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | 0 (0.000) |     9.58 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           45 |     1076 | 2024-06-15 | Zero Tenacity     | W   | 0.854      | -            | -                | -                | 0 (0.000) |    10.55 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1114 | 2024-06-14 | System5           | W   | 0.847      | -            | -                | -                | 0 (0.000) |     1.64 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1148 | 2024-06-13 | Verdant           | W   | 0.841      | -            | -                | -                | 0 (0.000) |     5.27 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1181 | 2024-06-12 | FAVBET            | L   | 0.834      | -            | -                | -                | -         |   -22.75 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1196 | 2024-06-11 | Permitta          | W   | 0.827      | -            | -                | -                | -         |     5.74 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           40 |     1206 | 2024-06-11 | Rhyno             | W   | 0.826      | -            | -                | -                | -         |     7.51 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1236 | 2024-06-10 | BLEED             | W   | 0.819      | 0.500        | 0.126 (0.051)    | -                | -         |    19.76 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1303 | 2024-06-09 | Zero Tenacity     | W   | 0.811      | 0.500        | 0.143 (0.058)    | 1.000 (0.406)    | -         |    11.03 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1464 | 2024-06-06 | Sampi             | W   | 0.793      | 0.500        | -                | 1.000 (0.397)    | -         |     6.27 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1568 | 2024-06-04 | CYBERSHOKE        | W   | 0.780      | -            | -                | -                | -         |     4.80 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           35 |     1616 | 2024-06-02 | Grannys Knockers  | L   | 0.766      | -            | -                | -                | -         |   -21.26 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     1708 | 2024-05-30 | DMS               | L   | 0.746      | -            | -                | -                | -         |   -18.43 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           33 |     2300 | 2024-05-10 | RUBY              | L   | 0.611      | -            | -                | -                | -         |   -15.06 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2346 | 2024-05-08 | 1WIN              | L   | 0.598      | -            | -                | -                | -         |   -14.49 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2364 | 2024-05-07 | SINNERS           | W   | 0.592      | -            | -                | -                | -         |     6.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2390 | 2024-05-05 | VP.Prodigy        | W   | 0.580      | -            | -                | -                | -         |     2.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2426 | 2024-05-03 | MOUZ NXT          | W   | 0.566      | 0.500        | 0.139 (0.039)    | 0.961 (0.272)    | -         |     5.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2451 | 2024-05-02 | Passion UA        | W   | 0.560      | 0.500        | 0.173 (0.048)    | 1.000 (0.280)    | -         |     5.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2469 | 2024-05-01 | B8                | W   | 0.554      | 0.500        | 0.170 (0.047)    | 0.912 (0.253)    | -         |     5.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2515 | 2024-04-29 | MOUZ NXT          | W   | 0.541      | 0.500        | 0.139 (0.037)    | 0.961 (0.260)    | -         |     5.83 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2547 | 2024-04-28 | Grannys Knockers  | L   | 0.532      | -            | -                | -                | -         |   -15.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2569 | 2024-04-27 | 1WIN              | W   | 0.526      | -            | -                | -                | -         |     3.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2595 | 2024-04-26 | Sangal            | L   | 0.519      | -            | -                | -                | -         |    -9.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2636 | 2024-04-24 | BLEED             | W   | 0.506      | -            | -                | -                | -         |     5.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2660 | 2024-04-23 | Zero Tenacity     | W   | 0.499      | 0.500        | 0.143 (0.036)    | 1.000 (0.249)    | -         |     5.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2681 | 2024-04-22 | MOUZ NXT          | W   | 0.491      | 0.500        | -                | 0.961 (0.236)    | -         |     5.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2696 | 2024-04-21 | 1WIN              | W   | 0.485      | -            | -                | -                | -         |     3.65 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2729 | 2024-04-20 | Gaimin Gladiators | L   | 0.478      | -            | -                | -                | -         |   -10.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2764 | 2024-04-19 | Sangal            | W   | 0.473      | 0.500        | 0.219 (0.052)    | -                | -         |     7.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2814 | 2024-04-18 | Secret            | W   | 0.467      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2851 | 2024-04-17 | Alliance          | W   | 0.460      | -            | -                | -                | -         |     2.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3043 | 2024-04-09 | FlyQuest          | L   | 0.410      | -            | -                | -                | -         |    -6.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3091 | 2024-04-09 | Steel Helmet      | W   | 0.405      | -            | -                | -                | 1 (0.405) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3120 | 2024-04-08 | FaZe              | L   | 0.398      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3313 | 2024-04-01 | Zero Tenacity     | W   | 0.352      | -            | -                | -                | -         |     4.58 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3445 | 2024-03-22 | Sashi             | L   | 0.287      | -            | -                | -                | -         |    -4.88 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3682 | 2024-03-12 | Nexus             | L   | 0.221      | -            | -                | -                | -         |    -5.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3711 | 2024-03-11 | Sashi             | W   | 0.213      | -            | -                | -                | -         |     3.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3726 | 2024-03-10 | Endpoint          | W   | 0.207      | -            | -                | -                | -         |     1.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3798 | 2024-03-07 | Zero Tenacity     | W   | 0.187      | -            | -                | -                | -         |     2.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3860 | 2024-03-05 | KOI               | L   | 0.174      | -            | -                | -                | -         |    -3.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     3867 | 2024-03-05 | GUN5              | W   | 0.174      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4384 | 2024-02-10 | Sashi             | W   | 0.014      | -            | -                | -                | -         |     0.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4400 | 2024-02-09 | AMKAL             | W   | 0.007      | -            | -                | -                | -         |     0.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4415 | 2024-02-08 | Sashi             | W   | 0.001      | -            | -                | -                | -         |     0.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100,585.03)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.826 | $50,000.00     | $41,319.44      |
| 2024-05-09 |      0.606 | $4,000.00      | $2,422.22       |
| 2024-05-03 |      0.566 | $50,000.00     | $28,319.44      |
| 2024-04-24 |      0.506 | $50,000.00     | $25,319.44      |
| 2024-04-14 |      0.438 | $5,000.00      | $2,192.48       |
| 2024-03-25 |      0.307 | $3,300.00      | $1,012.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
