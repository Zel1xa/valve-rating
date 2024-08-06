### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1647.9<br />
<br />
Final Rank Value (1647.9) = Starting Rank Value (1700.3) + Head To Head Adjustments (-52.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.768[<sup>1</sup>](#table2)
- Bounty Collected: 0.639[<sup>2</sup>](#table1)
- Opponent Network: 0.283[<sup>2</sup>](#table1)
- LAN Wins: 0.844[<sup>2</sup>](#table1)

The average of these factors is 0.634<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1700.3
- 400 + ( ( 0.634 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1700.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      136 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.82 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      188 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      557 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.76 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      599 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.647 (0.647)    | 0.375 (0.375)    | 1 (1.000) |    22.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      701 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.341 (0.341)    | 0.372 (0.372)    | 1 (1.000) |    13.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1053 | 2024-06-15 | Natus Vincere | L   | 0.856      | -            | -                | -                | -         |    -5.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1090 | 2024-06-14 | Astralis      | W   | 0.849      | 0.729        | 0.389 (0.241)    | 0.412 (0.255)    | 1 (0.849) |    15.21 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1127 | 2024-06-13 | Spirit        | L   | 0.843      | -            | -                | -                | -         |    -5.31 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1167 | 2024-06-12 | Vitality      | W   | 0.835      | 0.729        | 0.647 (0.394)    | 0.375 (0.228)    | 1 (0.835) |    19.93 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1713 | 2024-05-29 | BIG           | L   | 0.742      | -            | -                | -                | -         |   -20.43 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1728 | 2024-05-28 | FaZe          | L   | 0.736      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1749 | 2024-05-27 | HEROIC        | W   | 0.730      | 0.624        | 0.225 (0.102)    | 0.363 (0.165)    | 1 (0.730) |     7.99 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2041 | 2024-05-17 | Falcons       | L   | 0.661      | -            | -                | -                | -         |   -16.90 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2080 | 2024-05-16 | MOUZ          | L   | 0.653      | -            | -                | -                | -         |    -5.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2179 | 2024-05-14 | Falcons       | W   | 0.642      | 0.769        | 0.220 (0.108)    | -                | 1 (0.642) |     3.45 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2301 | 2024-05-09 | Complexity    | L   | 0.608      | -            | -                | -                | -         |   -10.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2320 | 2024-05-08 | The MongolZ   | W   | 0.602      | 0.889        | 1.000 (0.535)    | 0.709 (0.380)    | 1 (0.602) |    14.75 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2336 | 2024-05-07 | GamerLegion   | W   | 0.596      | 0.889        | 0.173 (0.091)    | -                | 1 (0.596) |     0.91 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2524 | 2024-04-28 | SAW           | W   | 0.535      | 0.889        | -                | 0.528 (0.251)    | 1 (0.535) |     1.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2555 | 2024-04-27 | fnatic        | W   | 0.527      | 0.889        | 0.371 (0.174)    | 0.695 (0.326)    | 1 (0.527) |     4.99 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2598 | 2024-04-25 | FaZe          | L   | 0.515      | -            | -                | -                | -         |    -7.40 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2621 | 2024-04-24 | SAW           | W   | 0.508      | 0.889        | -                | 0.528 (0.238)    | -         |     0.85 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2644 | 2024-04-23 | fnatic        | L   | 0.500      | -            | -                | -                | -         |   -11.22 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2940 | 2024-04-12 | G2            | L   | 0.426      | -            | -                | -                | -         |    -2.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     3024 | 2024-04-10 | Astralis      | L   | 0.413      | -            | -                | -                | -         |    -5.89 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3076 | 2024-04-08 | FlyQuest      | W   | 0.405      | -            | -                | -                | -         |     0.61 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3106 | 2024-04-08 | Wildcard      | W   | 0.399      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3406 | 2024-03-24 | G2            | L   | 0.301      | -            | -                | -                | -         |    -1.54 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3420 | 2024-03-23 | Eternal Fire  | L   | 0.294      | -            | -                | -                | -         |    -4.56 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3437 | 2024-03-22 | HEROIC        | W   | 0.287      | -            | -                | -                | -         |     2.91 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3451 | 2024-03-21 | paiN          | W   | 0.282      | 1.000        | 0.324 (0.091)    | 0.857 (0.242)    | -         |     1.45 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3461 | 2024-03-21 | Imperial      | L   | 0.281      | -            | -                | -                | -         |    -8.17 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3663 | 2024-03-12 | HEROIC        | W   | 0.222      | -            | -                | -                | -         |     2.15 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3679 | 2024-03-11 | Apeks         | W   | 0.216      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3690 | 2024-03-11 | B8            | W   | 0.215      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4272 | 2024-02-15 | Natus Vincere | W   | 0.048      | -            | -                | -                | -         |     1.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4304 | 2024-02-14 | fnatic        | W   | 0.043      | -            | -                | -                | -         |     0.42 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4323 | 2024-02-14 | SAW           | W   | 0.040      | -            | -                | -                | -         |     0.06 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($159,766.06)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.861 | $40,000.00     | $34,444.44      |
| 2024-06-02 |      0.769 | $5,000.00      | $3,844.44       |
| 2024-05-12 |      0.628 | $32,000.00     | $20,097.78      |
| 2024-04-14 |      0.440 | $10,000.00     | $4,401.62       |
| 2024-03-31 |      0.349 | $20,000.00     | $6,977.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
