### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1675.1<br />
<br />
Final Rank Value (1675.1) = Starting Rank Value (1714.9) + Head To Head Adjustments (-39.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.760[<sup>1</sup>](#table2)
- Bounty Collected: 0.632[<sup>2</sup>](#table1)
- Opponent Network: 0.288[<sup>2</sup>](#table1)
- LAN Wins: 0.873[<sup>2</sup>](#table1)

The average of these factors is 0.638<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1714.9
- 400 + ( ( 0.638 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1714.9


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
|           37 |       35 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -23.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      408 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.97 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      452 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.591 (0.591)    | 0.385 (0.385)    | 1 (1.000) |    21.93 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      561 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.318 (0.318)    | 0.366 (0.366)    | 1 (1.000) |    12.31 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      914 | 2024-06-15 | Natus Vincere | L   | 0.889      | -            | -                | -                | -         |    -5.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |      945 | 2024-06-14 | Astralis      | W   | 0.882      | 0.729        | 0.359 (0.231)    | 0.385 (0.248)    | 1 (0.882) |    14.34 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |      981 | 2024-06-13 | Spirit        | L   | 0.875      | -            | -                | -                | -         |    -5.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1021 | 2024-06-12 | Vitality      | W   | 0.868      | 0.729        | 0.591 (0.374)    | 0.385 (0.243)    | 1 (0.868) |    20.38 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1584 | 2024-05-29 | BIG           | L   | 0.775      | -            | -                | -                | -         |   -22.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1599 | 2024-05-28 | FaZe          | L   | 0.769      | -            | -                | -                | -         |    -9.09 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1620 | 2024-05-27 | HEROIC        | W   | 0.763      | 0.624        | 0.209 (0.099)    | 0.381 (0.181)    | 1 (0.763) |     8.09 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1940 | 2024-05-17 | Falcons       | L   | 0.693      | -            | -                | -                | -         |   -17.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     1979 | 2024-05-16 | MOUZ          | L   | 0.686      | -            | -                | -                | -         |    -4.93 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2084 | 2024-05-14 | Falcons       | W   | 0.675      | 0.769        | 0.206 (0.107)    | -                | 1 (0.675) |     3.91 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2209 | 2024-05-09 | Complexity    | L   | 0.641      | -            | -                | -                | -         |   -11.08 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2230 | 2024-05-08 | The MongolZ   | W   | 0.635      | 0.889        | 1.000 (0.564)    | 0.719 (0.406)    | 1 (0.635) |    15.39 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2246 | 2024-05-07 | GamerLegion   | W   | 0.628      | 0.889        | 0.176 (0.099)    | -                | 1 (0.628) |     0.98 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2437 | 2024-04-28 | SAW           | W   | 0.567      | 0.889        | -                | 0.544 (0.274)    | 1 (0.567) |     1.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2469 | 2024-04-27 | fnatic        | W   | 0.560      | 0.889        | 0.292 (0.145)    | 0.529 (0.263)    | 1 (0.560) |     2.38 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2511 | 2024-04-25 | FaZe          | L   | 0.548      | -            | -                | -                | -         |    -7.32 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2534 | 2024-04-24 | SAW           | W   | 0.541      | 0.889        | -                | 0.544 (0.262)    | -         |     0.95 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2559 | 2024-04-23 | fnatic        | L   | 0.533      | -            | -                | -                | -         |   -14.76 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2864 | 2024-04-12 | G2            | L   | 0.459      | -            | -                | -                | -         |    -2.57 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2948 | 2024-04-10 | Astralis      | L   | 0.446      | -            | -                | -                | -         |    -7.38 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3000 | 2024-04-08 | FlyQuest      | W   | 0.438      | -            | -                | -                | -         |     0.70 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3030 | 2024-04-08 | Wildcard      | W   | 0.432      | -            | -                | -                | -         |     0.03 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3343 | 2024-03-24 | G2            | L   | 0.334      | -            | -                | -                | -         |    -1.85 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3357 | 2024-03-23 | Eternal Fire  | L   | 0.327      | -            | -                | -                | -         |    -4.98 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3374 | 2024-03-22 | HEROIC        | W   | 0.320      | -            | -                | -                | -         |     3.29 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3388 | 2024-03-21 | paiN          | W   | 0.315      | 1.000        | 0.300 (0.095)    | 0.801 (0.252)    | -         |     1.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3398 | 2024-03-21 | Imperial      | L   | 0.314      | -            | -                | -                | -         |    -9.10 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3605 | 2024-03-12 | HEROIC        | W   | 0.255      | -            | -                | -                | -         |     2.49 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3621 | 2024-03-11 | Apeks         | W   | 0.249      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3632 | 2024-03-11 | B8            | W   | 0.247      | -            | -                | -                | -         |     0.23 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4230 | 2024-02-15 | Natus Vincere | W   | 0.081      | -            | -                | -                | -         |     2.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4262 | 2024-02-14 | fnatic        | W   | 0.075      | -            | -                | -                | -         |     0.31 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4281 | 2024-02-14 | SAW           | W   | 0.073      | -            | -                | -                | -         |     0.11 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($158,273.29)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.48) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.894 | $40,000.00     | $35,755.56      |
| 2024-06-02 |      0.802 | $5,000.00      | $4,008.33       |
| 2024-05-12 |      0.661 | $32,000.00     | $21,146.67      |
| 2024-04-14 |      0.473 | $10,000.00     | $4,729.40       |
| 2024-03-31 |      0.382 | $20,000.00     | $7,633.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
