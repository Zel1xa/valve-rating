### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1156.7<br />
<br />
Final Rank Value (1156.7) = Starting Rank Value (1169.9) + Head To Head Adjustments (-13.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.665[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.374<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1169.9
- 400 + ( ( 0.374 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1169.9


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
|           56 |       58 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.420 (0.210)    | 0.758 (0.379)    | 0 (0.000) |    26.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       91 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.65 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      134 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.94 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      138 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.99 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      205 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.74 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      265 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      616 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.87 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      650 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.20 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      716 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.33 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      778 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.26 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |      823 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | 0 (0.000) |     9.55 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           45 |     1078 | 2024-06-15 | Zero Tenacity     | W   | 0.853      | -            | -                | -                | 0 (0.000) |    10.56 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1116 | 2024-06-14 | System5           | W   | 0.847      | -            | -                | -                | 0 (0.000) |     1.63 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1150 | 2024-06-13 | Verdant           | W   | 0.840      | -            | -                | -                | 0 (0.000) |     5.31 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1183 | 2024-06-12 | FAVBET            | L   | 0.833      | -            | -                | -                | -         |   -22.76 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1198 | 2024-06-11 | Permitta          | W   | 0.827      | -            | -                | -                | -         |     5.72 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           40 |     1208 | 2024-06-11 | Rhyno             | W   | 0.826      | -            | -                | -                | -         |     7.47 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1238 | 2024-06-10 | BLEED             | W   | 0.819      | 0.500        | 0.125 (0.051)    | -                | -         |    19.74 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1305 | 2024-06-09 | Zero Tenacity     | W   | 0.811      | 0.500        | 0.143 (0.058)    | 1.000 (0.406)    | -         |    11.04 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1466 | 2024-06-06 | Sampi             | W   | 0.793      | 0.500        | -                | 1.000 (0.396)    | -         |     6.24 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1570 | 2024-06-04 | CYBERSHOKE        | W   | 0.780      | -            | -                | -                | -         |     4.77 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           35 |     1618 | 2024-06-02 | Grannys Knockers  | L   | 0.766      | -            | -                | -                | -         |   -21.28 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     1710 | 2024-05-30 | DMS               | L   | 0.746      | -            | -                | -                | -         |   -18.42 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           33 |     2302 | 2024-05-10 | RUBY              | L   | 0.611      | -            | -                | -                | -         |   -15.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2348 | 2024-05-08 | 1WIN              | L   | 0.598      | -            | -                | -                | -         |   -14.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2366 | 2024-05-07 | SINNERS           | W   | 0.592      | -            | -                | -                | -         |     6.59 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2392 | 2024-05-05 | VP.Prodigy        | W   | 0.580      | -            | -                | -                | -         |     2.71 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2428 | 2024-05-03 | MOUZ NXT          | W   | 0.566      | 0.500        | 0.139 (0.039)    | 0.961 (0.272)    | -         |     5.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2453 | 2024-05-02 | Passion UA        | W   | 0.560      | 0.500        | 0.173 (0.048)    | 1.000 (0.280)    | -         |     5.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2471 | 2024-05-01 | B8                | W   | 0.554      | 0.500        | 0.170 (0.047)    | 0.912 (0.252)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2517 | 2024-04-29 | MOUZ NXT          | W   | 0.540      | 0.500        | 0.139 (0.037)    | 0.961 (0.260)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2549 | 2024-04-28 | Grannys Knockers  | L   | 0.532      | -            | -                | -                | -         |   -15.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2571 | 2024-04-27 | 1WIN              | W   | 0.526      | -            | -                | -                | -         |     3.88 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2597 | 2024-04-26 | Sangal            | L   | 0.519      | -            | -                | -                | -         |    -8.81 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2638 | 2024-04-24 | BLEED             | W   | 0.506      | -            | -                | -                | -         |     5.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2662 | 2024-04-23 | Zero Tenacity     | W   | 0.499      | 0.500        | 0.143 (0.036)    | 1.000 (0.249)    | -         |     5.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2683 | 2024-04-22 | MOUZ NXT          | W   | 0.491      | 0.500        | -                | 0.961 (0.236)    | -         |     5.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2698 | 2024-04-21 | 1WIN              | W   | 0.485      | -            | -                | -                | -         |     3.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2731 | 2024-04-20 | Gaimin Gladiators | L   | 0.478      | -            | -                | -                | -         |   -10.62 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2766 | 2024-04-19 | Sangal            | W   | 0.473      | 0.500        | 0.288 (0.068)    | -                | -         |     7.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2816 | 2024-04-18 | Secret            | W   | 0.466      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2853 | 2024-04-17 | Alliance          | W   | 0.460      | -            | -                | -                | -         |     2.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3045 | 2024-04-09 | FlyQuest          | L   | 0.410      | -            | -                | -                | -         |    -6.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3093 | 2024-04-09 | Steel Helmet      | W   | 0.404      | -            | -                | -                | 1 (0.404) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3122 | 2024-04-08 | FaZe              | L   | 0.398      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3315 | 2024-04-01 | Zero Tenacity     | W   | 0.351      | -            | -                | -                | -         |     4.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3447 | 2024-03-22 | Sashi             | L   | 0.287      | -            | -                | -                | -         |    -4.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3684 | 2024-03-12 | Nexus             | L   | 0.220      | -            | -                | -                | -         |    -5.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3713 | 2024-03-11 | Sashi             | W   | 0.213      | -            | -                | -                | -         |     3.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3728 | 2024-03-10 | Endpoint          | W   | 0.207      | -            | -                | -                | -         |     1.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3800 | 2024-03-07 | Zero Tenacity     | W   | 0.187      | -            | -                | -                | -         |     2.40 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3862 | 2024-03-05 | KOI               | L   | 0.174      | -            | -                | -                | -         |    -3.43 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     3869 | 2024-03-05 | GUN5              | W   | 0.173      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4386 | 2024-02-10 | Sashi             | W   | 0.014      | -            | -                | -                | -         |     0.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4402 | 2024-02-09 | AMKAL             | W   | 0.007      | -            | -                | -                | -         |     0.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4417 | 2024-02-08 | Sashi             | W   | 0.001      | -            | -                | -                | -         |     0.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100,562.49)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.826 | $50,000.00     | $41,312.50      |
| 2024-05-09 |      0.605 | $4,000.00      | $2,421.67       |
| 2024-05-03 |      0.566 | $50,000.00     | $28,312.50      |
| 2024-04-24 |      0.506 | $50,000.00     | $25,312.50      |
| 2024-04-14 |      0.438 | $5,000.00      | $2,191.78       |
| 2024-03-25 |      0.307 | $3,300.00      | $1,011.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
