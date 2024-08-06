### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1153.8<br />
<br />
Final Rank Value (1153.8) = Starting Rank Value (1169.7) + Head To Head Adjustments (-16.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.375<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1169.7
- 400 + ( ( 0.375 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1169.7


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
|           57 |       35 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.421 (0.211)    | 0.777 (0.389)    | 0 (0.000) |    26.38 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       68 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.97 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |      111 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.93 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      115 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.02 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      182 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.62 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      242 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      593 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.99 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      627 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      693 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.38 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      755 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.27 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      800 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.47 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1055 | 2024-06-15 | Zero Tenacity     | W   | 0.858      | -            | -                | -                | 0 (0.000) |    10.48 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1093 | 2024-06-14 | System5           | W   | 0.851      | -            | -                | -                | 0 (0.000) |     1.65 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1127 | 2024-06-13 | Verdant           | W   | 0.845      | -            | -                | -                | 0 (0.000) |     5.25 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1160 | 2024-06-12 | FAVBET            | L   | 0.838      | -            | -                | -                | -         |   -22.91 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1175 | 2024-06-11 | Permitta          | W   | 0.831      | -            | -                | -                | -         |     5.53 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1185 | 2024-06-11 | Rhyno             | W   | 0.831      | -            | -                | -                | -         |     7.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1215 | 2024-06-10 | BLEED             | W   | 0.823      | 0.500        | 0.126 (0.052)    | -                | -         |    19.82 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1282 | 2024-06-09 | Zero Tenacity     | W   | 0.816      | 0.500        | 0.143 (0.058)    | 1.000 (0.408)    | -         |    10.94 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1443 | 2024-06-06 | Sampi             | W   | 0.797      | 0.500        | -                | 1.000 (0.399)    | -         |     6.18 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1547 | 2024-06-04 | CYBERSHOKE        | W   | 0.784      | -            | -                | -                | -         |     4.82 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1595 | 2024-06-02 | Grannys Knockers  | L   | 0.770      | -            | -                | -                | -         |   -21.39 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1687 | 2024-05-30 | DMS               | L   | 0.750      | -            | -                | -                | -         |   -18.54 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2279 | 2024-05-10 | RUBY              | L   | 0.616      | -            | -                | -                | -         |   -15.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2325 | 2024-05-08 | 1WIN              | L   | 0.602      | -            | -                | -                | -         |   -14.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2343 | 2024-05-07 | SINNERS           | W   | 0.596      | -            | -                | -                | -         |     6.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2369 | 2024-05-05 | VP.Prodigy        | W   | 0.584      | -            | -                | -                | -         |     2.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2405 | 2024-05-03 | MOUZ NXT          | W   | 0.571      | 0.500        | 0.139 (0.040)    | 0.986 (0.281)    | -         |     5.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2430 | 2024-05-02 | Passion UA        | W   | 0.564      | 0.500        | 0.173 (0.049)    | 1.000 (0.282)    | -         |     5.71 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2448 | 2024-05-01 | B8                | W   | 0.558      | 0.500        | 0.164 (0.046)    | 0.934 (0.261)    | -         |     5.82 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2494 | 2024-04-29 | MOUZ NXT          | W   | 0.545      | 0.500        | 0.139 (0.038)    | 0.986 (0.268)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2526 | 2024-04-28 | Grannys Knockers  | L   | 0.536      | -            | -                | -                | -         |   -15.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2548 | 2024-04-27 | 1WIN              | W   | 0.530      | -            | -                | -                | -         |     3.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2574 | 2024-04-26 | Sangal            | L   | 0.523      | -            | -                | -                | -         |    -9.43 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2615 | 2024-04-24 | BLEED             | W   | 0.511      | -            | -                | -                | -         |     5.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2639 | 2024-04-23 | Zero Tenacity     | W   | 0.503      | 0.500        | 0.143 (0.036)    | 1.000 (0.252)    | -         |     5.92 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2660 | 2024-04-22 | MOUZ NXT          | W   | 0.496      | 0.500        | -                | 0.986 (0.244)    | -         |     5.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2675 | 2024-04-21 | 1WIN              | W   | 0.489      | -            | -                | -                | -         |     3.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2708 | 2024-04-20 | Gaimin Gladiators | L   | 0.483      | -            | -                | -                | -         |   -10.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2743 | 2024-04-19 | Sangal            | W   | 0.477      | 0.500        | 0.219 (0.052)    | -                | -         |     7.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2793 | 2024-04-18 | Secret            | W   | 0.471      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2830 | 2024-04-17 | Alliance          | W   | 0.464      | -            | -                | -                | -         |     2.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     3022 | 2024-04-09 | FlyQuest          | L   | 0.415      | -            | -                | -                | -         |    -6.58 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3070 | 2024-04-09 | Steel Helmet      | W   | 0.409      | -            | -                | -                | 1 (0.409) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3099 | 2024-04-08 | FaZe              | L   | 0.402      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3292 | 2024-04-01 | Zero Tenacity     | W   | 0.356      | -            | -                | -                | -         |     4.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3424 | 2024-03-22 | Sashi             | L   | 0.291      | -            | -                | -                | -         |    -4.98 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3661 | 2024-03-12 | Nexus             | L   | 0.225      | -            | -                | -                | -         |    -6.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3690 | 2024-03-11 | Sashi             | W   | 0.217      | -            | -                | -                | -         |     3.08 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3705 | 2024-03-10 | Endpoint          | W   | 0.211      | -            | -                | -                | -         |     1.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3777 | 2024-03-07 | Zero Tenacity     | W   | 0.191      | -            | -                | -                | -         |     2.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3839 | 2024-03-05 | KOI               | L   | 0.178      | -            | -                | -                | -         |    -3.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3846 | 2024-03-05 | GUN5              | W   | 0.178      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4363 | 2024-02-10 | Sashi             | W   | 0.019      | -            | -                | -                | -         |     0.28 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4379 | 2024-02-09 | AMKAL             | W   | 0.012      | -            | -                | -                | -         |     0.17 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4394 | 2024-02-08 | Sashi             | W   | 0.005      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4400 | 2024-02-08 | BetBoom           | W   | 0.004      | -            | -                | -                | -         |     0.10 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($101,261.28)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.831 | $50,000.00     | $41,527.78      |
| 2024-05-09 |      0.610 | $4,000.00      | $2,438.89       |
| 2024-05-03 |      0.571 | $50,000.00     | $28,527.78      |
| 2024-04-24 |      0.511 | $50,000.00     | $25,527.78      |
| 2024-04-14 |      0.443 | $5,000.00      | $2,213.31       |
| 2024-03-25 |      0.311 | $3,300.00      | $1,025.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
