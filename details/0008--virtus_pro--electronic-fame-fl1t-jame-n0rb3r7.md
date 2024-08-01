### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1676.0<br />
<br />
Final Rank Value (1676.0) = Starting Rank Value (1713.7) + Head To Head Adjustments (-37.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.760[<sup>1</sup>](#table2)
- Bounty Collected: 0.632[<sup>2</sup>](#table1)
- Opponent Network: 0.289[<sup>2</sup>](#table1)
- LAN Wins: 0.873[<sup>2</sup>](#table1)

The average of these factors is 0.639<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1713.7
- 400 + ( ( 0.639 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1713.7


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
|           37 |       42 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -21.21 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      414 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.93 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      458 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.590 (0.590)    | 0.384 (0.384)    | 1 (1.000) |    21.90 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      564 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.318 (0.318)    | 0.366 (0.366)    | 1 (1.000) |    12.36 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      920 | 2024-06-15 | Natus Vincere | L   | 0.887      | -            | -                | -                | -         |    -5.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |      951 | 2024-06-14 | Astralis      | W   | 0.880      | 0.729        | 0.359 (0.230)    | 0.385 (0.247)    | 1 (0.880) |    14.43 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |      987 | 2024-06-13 | Spirit        | L   | 0.874      | -            | -                | -                | -         |    -5.43 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1027 | 2024-06-12 | Vitality      | W   | 0.866      | 0.729        | 0.590 (0.373)    | 0.384 (0.243)    | 1 (0.866) |    20.32 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1590 | 2024-05-29 | BIG           | L   | 0.773      | -            | -                | -                | -         |   -22.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1605 | 2024-05-28 | FaZe          | L   | 0.767      | -            | -                | -                | -         |    -9.09 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1626 | 2024-05-27 | HEROIC        | W   | 0.761      | 0.624        | 0.208 (0.099)    | 0.380 (0.181)    | 1 (0.761) |     8.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1946 | 2024-05-17 | Falcons       | L   | 0.692      | -            | -                | -                | -         |   -17.40 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     1985 | 2024-05-16 | MOUZ          | L   | 0.685      | -            | -                | -                | -         |    -4.90 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2090 | 2024-05-14 | Falcons       | W   | 0.673      | 0.769        | 0.205 (0.106)    | -                | 1 (0.673) |     3.88 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2215 | 2024-05-09 | Complexity    | L   | 0.639      | -            | -                | -                | -         |   -11.06 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2236 | 2024-05-08 | The MongolZ   | W   | 0.633      | 0.889        | 1.000 (0.563)    | 0.719 (0.405)    | 1 (0.633) |    15.38 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2252 | 2024-05-07 | GamerLegion   | W   | 0.627      | 0.889        | 0.176 (0.098)    | -                | 1 (0.627) |     0.98 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2443 | 2024-04-28 | SAW           | W   | 0.566      | 0.889        | -                | 0.544 (0.273)    | 1 (0.566) |     1.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2475 | 2024-04-27 | fnatic        | W   | 0.558      | 0.889        | 0.292 (0.145)    | 0.568 (0.282)    | 1 (0.558) |     2.37 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2517 | 2024-04-25 | FaZe          | L   | 0.547      | -            | -                | -                | -         |    -7.31 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2540 | 2024-04-24 | SAW           | W   | 0.539      | 0.889        | -                | 0.544 (0.261)    | -         |     0.95 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2565 | 2024-04-23 | fnatic        | L   | 0.532      | -            | -                | -                | -         |   -14.71 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2870 | 2024-04-12 | G2            | L   | 0.457      | -            | -                | -                | -         |    -2.54 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2954 | 2024-04-10 | Astralis      | L   | 0.444      | -            | -                | -                | -         |    -7.35 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3006 | 2024-04-08 | FlyQuest      | W   | 0.437      | -            | -                | -                | -         |     0.69 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3036 | 2024-04-08 | Wildcard      | W   | 0.430      | -            | -                | -                | -         |     0.03 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3349 | 2024-03-24 | G2            | L   | 0.332      | -            | -                | -                | -         |    -1.83 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3363 | 2024-03-23 | Eternal Fire  | L   | 0.325      | -            | -                | -                | -         |    -4.94 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3380 | 2024-03-22 | HEROIC        | W   | 0.318      | -            | -                | -                | -         |     3.27 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3394 | 2024-03-21 | paiN          | W   | 0.313      | 1.000        | 0.300 (0.094)    | 0.801 (0.251)    | -         |     1.24 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3404 | 2024-03-21 | Imperial      | L   | 0.312      | -            | -                | -                | -         |    -9.06 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3611 | 2024-03-12 | HEROIC        | W   | 0.253      | -            | -                | -                | -         |     2.47 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3627 | 2024-03-11 | Apeks         | W   | 0.247      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3638 | 2024-03-11 | B8            | W   | 0.246      | -            | -                | -                | -         |     0.23 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4236 | 2024-02-15 | Natus Vincere | W   | 0.079      | -            | -                | -                | -         |     2.05 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4268 | 2024-02-14 | fnatic        | W   | 0.074      | -            | -                | -                | -         |     0.30 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4287 | 2024-02-14 | SAW           | W   | 0.071      | -            | -                | -                | -         |     0.11 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($158,094.95)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.48) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.892 | $40,000.00     | $35,688.89      |
| 2024-06-02 |      0.800 | $5,000.00      | $4,000.00       |
| 2024-05-12 |      0.659 | $32,000.00     | $21,093.33      |
| 2024-04-14 |      0.471 | $10,000.00     | $4,712.73       |
| 2024-03-31 |      0.380 | $20,000.00     | $7,600.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
