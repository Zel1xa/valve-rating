### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1647.6<br />
<br />
Final Rank Value (1647.6) = Starting Rank Value (1699.8) + Head To Head Adjustments (-52.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.768[<sup>1</sup>](#table2)
- Bounty Collected: 0.639[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 0.844[<sup>2</sup>](#table1)

The average of these factors is 0.632<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1699.8
- 400 + ( ( 0.632 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1699.8


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
|           38 |      140 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.81 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      192 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.02 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      561 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.76 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      603 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.647 (0.647)    | 0.367 (0.367)    | 1 (1.000) |    22.20 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      705 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.341 (0.341)    | 0.364 (0.364)    | 1 (1.000) |    13.07 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1057 | 2024-06-15 | Natus Vincere | L   | 0.856      | -            | -                | -                | -         |    -5.10 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1094 | 2024-06-14 | Astralis      | W   | 0.849      | 0.729        | 0.389 (0.241)    | 0.403 (0.249)    | 1 (0.849) |    15.21 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1131 | 2024-06-13 | Spirit        | L   | 0.842      | -            | -                | -                | -         |    -5.29 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1171 | 2024-06-12 | Vitality      | W   | 0.835      | 0.729        | 0.647 (0.394)    | 0.367 (0.223)    | 1 (0.835) |    19.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1717 | 2024-05-29 | BIG           | L   | 0.742      | -            | -                | -                | -         |   -20.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1732 | 2024-05-28 | FaZe          | L   | 0.736      | -            | -                | -                | -         |    -9.45 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1753 | 2024-05-27 | HEROIC        | W   | 0.730      | 0.624        | 0.225 (0.102)    | 0.355 (0.161)    | 1 (0.730) |     7.98 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2045 | 2024-05-17 | Falcons       | L   | 0.660      | -            | -                | -                | -         |   -16.89 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2084 | 2024-05-16 | MOUZ          | L   | 0.653      | -            | -                | -                | -         |    -5.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2183 | 2024-05-14 | Falcons       | W   | 0.642      | 0.769        | 0.220 (0.108)    | -                | 1 (0.642) |     3.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2305 | 2024-05-09 | Complexity    | L   | 0.608      | -            | -                | -                | -         |   -10.10 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2324 | 2024-05-08 | The MongolZ   | W   | 0.602      | 0.889        | 1.000 (0.535)    | 0.694 (0.371)    | 1 (0.602) |    14.73 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2340 | 2024-05-07 | GamerLegion   | W   | 0.595      | 0.889        | 0.173 (0.091)    | -                | 1 (0.595) |     0.91 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2528 | 2024-04-28 | SAW           | W   | 0.534      | 0.889        | -                | 0.516 (0.245)    | 1 (0.534) |     1.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2559 | 2024-04-27 | fnatic        | W   | 0.527      | 0.889        | 0.371 (0.174)    | 0.680 (0.319)    | 1 (0.527) |     4.98 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2602 | 2024-04-25 | FaZe          | L   | 0.515      | -            | -                | -                | -         |    -7.39 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2625 | 2024-04-24 | SAW           | W   | 0.508      | 0.889        | -                | 0.516 (0.233)    | -         |     0.85 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2648 | 2024-04-23 | fnatic        | L   | 0.500      | -            | -                | -                | -         |   -11.22 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2944 | 2024-04-12 | G2            | L   | 0.426      | -            | -                | -                | -         |    -2.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     3028 | 2024-04-10 | Astralis      | L   | 0.413      | -            | -                | -                | -         |    -5.89 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3080 | 2024-04-08 | FlyQuest      | W   | 0.405      | -            | -                | -                | -         |     0.61 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3110 | 2024-04-08 | Wildcard      | W   | 0.399      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3410 | 2024-03-24 | G2            | L   | 0.301      | -            | -                | -                | -         |    -1.54 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3424 | 2024-03-23 | Eternal Fire  | L   | 0.294      | -            | -                | -                | -         |    -4.54 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3441 | 2024-03-22 | HEROIC        | W   | 0.287      | -            | -                | -                | -         |     2.91 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3455 | 2024-03-21 | paiN          | W   | 0.282      | 1.000        | 0.324 (0.091)    | 0.838 (0.236)    | -         |     1.45 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3465 | 2024-03-21 | Imperial      | L   | 0.281      | -            | -                | -                | -         |    -8.17 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3667 | 2024-03-12 | HEROIC        | W   | 0.222      | -            | -                | -                | -         |     2.15 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3683 | 2024-03-11 | Apeks         | W   | 0.216      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3694 | 2024-03-11 | B8            | W   | 0.214      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4276 | 2024-02-15 | Natus Vincere | W   | 0.048      | -            | -                | -                | -         |     1.24 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4308 | 2024-02-14 | fnatic        | W   | 0.042      | -            | -                | -                | -         |     0.41 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4327 | 2024-02-14 | SAW           | W   | 0.040      | -            | -                | -                | -         |     0.06 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($159,736.34)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.861 | $40,000.00     | $34,433.33      |
| 2024-06-02 |      0.769 | $5,000.00      | $3,843.06       |
| 2024-05-12 |      0.628 | $32,000.00     | $20,088.89      |
| 2024-04-14 |      0.440 | $10,000.00     | $4,398.84       |
| 2024-03-31 |      0.349 | $20,000.00     | $6,972.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
