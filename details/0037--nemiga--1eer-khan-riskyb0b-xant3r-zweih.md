### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1167.7<br />
<br />
Final Rank Value (1167.7) = Starting Rank Value (1164.6) + Head To Head Adjustments (3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.670[<sup>1</sup>](#table2)
- Bounty Collected: 0.437[<sup>2</sup>](#table1)
- Opponent Network: 0.325[<sup>2</sup>](#table1)
- LAN Wins: 0.051[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1164.6
- 400 + ( ( 0.371 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1164.6


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
|           53 |        5 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.77 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |       65 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      416 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -21.08 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      450 | 2024-07-18 | PERA              | W   | 1.000      | 0.500        | -                | 0.452 (0.226)    | 0 (0.000) |     8.48 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      516 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.20 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      578 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.44 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      623 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.171 (0.085)    | 1.000 (0.500)    | 0 (0.000) |     9.38 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |      878 | 2024-06-15 | Zero Tenacity     | W   | 0.892      | -            | -                | -                | 0 (0.000) |    11.08 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |      916 | 2024-06-14 | System5           | W   | 0.886      | -            | -                | -                | 0 (0.000) |     1.78 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |      950 | 2024-06-13 | Verdant           | W   | 0.879      | -            | -                | -                | 0 (0.000) |     5.57 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |      983 | 2024-06-12 | FAVBET            | L   | 0.872      | -            | -                | -                | -         |   -23.72 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |      998 | 2024-06-11 | Permitta          | W   | 0.866      | -            | -                | -                | 0 (0.000) |     5.58 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1008 | 2024-06-11 | Rhyno             | W   | 0.865      | -            | -                | -                | -         |     8.18 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1038 | 2024-06-10 | BLEED             | W   | 0.858      | 0.500        | 0.127 (0.055)    | -                | -         |    20.86 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1105 | 2024-06-09 | Zero Tenacity     | W   | 0.850      | 0.500        | 0.138 (0.058)    | 1.000 (0.425)    | -         |    11.66 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1266 | 2024-06-06 | Sampi             | W   | 0.832      | 0.500        | -                | 1.000 (0.416)    | -         |     6.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1370 | 2024-06-04 | CYBERSHOKE        | W   | 0.819      | -            | -                | -                | -         |     5.21 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1418 | 2024-06-02 | Grannys Knockers  | L   | 0.805      | -            | -                | -                | -         |   -22.17 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1510 | 2024-05-30 | DMS               | L   | 0.785      | -            | -                | -                | -         |   -19.20 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2102 | 2024-05-10 | RUBY              | L   | 0.650      | -            | -                | -                | -         |   -15.87 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2148 | 2024-05-08 | 1WIN              | L   | 0.637      | -            | -                | -                | -         |   -15.92 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2166 | 2024-05-07 | SINNERS           | W   | 0.631      | -            | -                | -                | -         |     5.29 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2192 | 2024-05-05 | VP.Prodigy        | W   | 0.619      | -            | -                | -                | -         |     2.95 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2228 | 2024-05-03 | MOUZ NXT          | W   | 0.605      | 0.500        | 0.140 (0.042)    | 1.000 (0.303)    | -         |     6.08 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2253 | 2024-05-02 | Passion UA        | W   | 0.599      | 0.500        | 0.171 (0.051)    | 1.000 (0.299)    | -         |     5.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2271 | 2024-05-01 | B8                | W   | 0.593      | 0.500        | 0.167 (0.049)    | 0.879 (0.260)    | -         |     6.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2317 | 2024-04-29 | MOUZ NXT          | W   | 0.579      | 0.500        | 0.140 (0.040)    | 1.000 (0.290)    | -         |     6.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2349 | 2024-04-28 | Grannys Knockers  | L   | 0.570      | -            | -                | -                | -         |   -16.26 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2371 | 2024-04-27 | 1WIN              | W   | 0.564      | -            | -                | -                | -         |     3.68 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2397 | 2024-04-26 | Sangal            | L   | 0.558      | -            | -                | -                | -         |   -10.28 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2438 | 2024-04-24 | BLEED             | W   | 0.545      | -            | -                | -                | -         |     6.19 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2462 | 2024-04-23 | Zero Tenacity     | W   | 0.538      | 0.500        | 0.138 (0.037)    | 1.000 (0.269)    | -         |     6.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2483 | 2024-04-22 | MOUZ NXT          | W   | 0.530      | 0.500        | 0.140 (0.037)    | 1.000 (0.265)    | -         |     5.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2498 | 2024-04-21 | 1WIN              | W   | 0.524      | -            | -                | -                | -         |     3.44 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2531 | 2024-04-20 | Gaimin Gladiators | L   | 0.517      | -            | -                | -                | -         |   -10.88 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2566 | 2024-04-19 | Sangal            | W   | 0.512      | 0.500        | 0.219 (0.056)    | -                | -         |     7.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2616 | 2024-04-18 | Secret            | W   | 0.505      | -            | -                | -                | -         |     0.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2653 | 2024-04-17 | Alliance          | W   | 0.499      | -            | -                | -                | -         |     2.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2845 | 2024-04-09 | FlyQuest          | L   | 0.449      | -            | -                | -                | -         |    -6.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     2893 | 2024-04-09 | Steel Helmet      | W   | 0.443      | -            | -                | -                | 1 (0.443) |     0.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     2922 | 2024-04-08 | FaZe              | L   | 0.437      | -            | -                | -                | -         |    -0.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3115 | 2024-04-01 | Zero Tenacity     | W   | 0.390      | -            | -                | -                | -         |     5.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3247 | 2024-03-22 | Sashi             | L   | 0.326      | -            | -                | -                | -         |    -5.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3484 | 2024-03-12 | Nexus             | L   | 0.259      | -            | -                | -                | -         |    -7.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3513 | 2024-03-11 | Sashi             | W   | 0.252      | -            | -                | -                | -         |     3.65 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3528 | 2024-03-10 | Endpoint          | W   | 0.245      | -            | -                | -                | -         |     1.37 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3600 | 2024-03-07 | Zero Tenacity     | W   | 0.225      | -            | -                | -                | -         |     2.94 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3662 | 2024-03-05 | KOI               | L   | 0.213      | -            | -                | -                | -         |    -3.97 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3669 | 2024-03-05 | GUN5              | W   | 0.212      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4186 | 2024-02-10 | Sashi             | W   | 0.053      | -            | -                | -                | -         |     0.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4202 | 2024-02-09 | AMKAL             | W   | 0.046      | -            | -                | -                | -         |     0.71 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4217 | 2024-02-08 | Sashi             | W   | 0.039      | -            | -                | -                | -         |     0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4223 | 2024-02-08 | BetBoom           | W   | 0.038      | -            | -                | -                | -         |     1.00 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,879.42)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.865 | $50,000.00     | $43,258.56      |
| 2024-05-09 |      0.644 | $4,000.00      | $2,577.35       |
| 2024-05-03 |      0.605 | $50,000.00     | $30,258.56      |
| 2024-04-24 |      0.545 | $50,000.00     | $27,258.56      |
| 2024-04-14 |      0.477 | $5,000.00      | $2,386.39       |
| 2024-03-25 |      0.345 | $3,300.00      | $1,139.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
