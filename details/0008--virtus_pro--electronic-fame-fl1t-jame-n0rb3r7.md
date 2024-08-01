### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1675.5<br />
<br />
Final Rank Value (1675.5) = Starting Rank Value (1712.8) + Head To Head Adjustments (-37.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.760[<sup>1</sup>](#table2)
- Bounty Collected: 0.632[<sup>2</sup>](#table1)
- Opponent Network: 0.287[<sup>2</sup>](#table1)
- LAN Wins: 0.873[<sup>2</sup>](#table1)

The average of these factors is 0.638<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1712.8
- 400 + ( ( 0.638 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1712.8


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
|           37 |       39 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -21.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      412 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      456 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.590 (0.590)    | 0.384 (0.384)    | 1 (1.000) |    21.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      565 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.318 (0.318)    | 0.366 (0.366)    | 1 (1.000) |    12.38 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      918 | 2024-06-15 | Natus Vincere | L   | 0.887      | -            | -                | -                | -         |    -5.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |      949 | 2024-06-14 | Astralis      | W   | 0.880      | 0.729        | 0.359 (0.230)    | 0.385 (0.247)    | 1 (0.880) |    14.45 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |      985 | 2024-06-13 | Spirit        | L   | 0.874      | -            | -                | -                | -         |    -5.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1025 | 2024-06-12 | Vitality      | W   | 0.866      | 0.729        | 0.590 (0.373)    | 0.384 (0.243)    | 1 (0.866) |    20.34 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1588 | 2024-05-29 | BIG           | L   | 0.773      | -            | -                | -                | -         |   -22.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1603 | 2024-05-28 | FaZe          | L   | 0.767      | -            | -                | -                | -         |    -9.07 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1624 | 2024-05-27 | HEROIC        | W   | 0.761      | 0.624        | 0.208 (0.099)    | 0.380 (0.181)    | 1 (0.761) |     8.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1944 | 2024-05-17 | Falcons       | L   | 0.692      | -            | -                | -                | -         |   -17.39 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     1983 | 2024-05-16 | MOUZ          | L   | 0.685      | -            | -                | -                | -         |    -4.89 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2088 | 2024-05-14 | Falcons       | W   | 0.673      | 0.769        | 0.205 (0.106)    | -                | 1 (0.673) |     3.90 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2213 | 2024-05-09 | Complexity    | L   | 0.639      | -            | -                | -                | -         |   -11.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2234 | 2024-05-08 | The MongolZ   | W   | 0.634      | 0.889        | 1.000 (0.563)    | 0.719 (0.405)    | 1 (0.634) |    15.40 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2250 | 2024-05-07 | GamerLegion   | W   | 0.627      | 0.889        | 0.176 (0.098)    | -                | 1 (0.627) |     0.98 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2441 | 2024-04-28 | SAW           | W   | 0.566      | 0.889        | -                | 0.544 (0.274)    | 1 (0.566) |     1.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2473 | 2024-04-27 | fnatic        | W   | 0.558      | 0.889        | 0.292 (0.145)    | 0.529 (0.263)    | 1 (0.558) |     2.38 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2515 | 2024-04-25 | FaZe          | L   | 0.547      | -            | -                | -                | -         |    -7.29 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2538 | 2024-04-24 | SAW           | W   | 0.539      | 0.889        | -                | 0.544 (0.261)    | -         |     0.95 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2563 | 2024-04-23 | fnatic        | L   | 0.532      | -            | -                | -                | -         |   -14.71 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2868 | 2024-04-12 | G2            | L   | 0.457      | -            | -                | -                | -         |    -2.53 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2952 | 2024-04-10 | Astralis      | L   | 0.444      | -            | -                | -                | -         |    -7.34 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3004 | 2024-04-08 | FlyQuest      | W   | 0.437      | -            | -                | -                | -         |     0.70 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3034 | 2024-04-08 | Wildcard      | W   | 0.431      | -            | -                | -                | -         |     0.03 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3347 | 2024-03-24 | G2            | L   | 0.332      | -            | -                | -                | -         |    -1.82 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3361 | 2024-03-23 | Eternal Fire  | L   | 0.325      | -            | -                | -                | -         |    -4.94 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3378 | 2024-03-22 | HEROIC        | W   | 0.319      | -            | -                | -                | -         |     3.28 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3392 | 2024-03-21 | paiN          | W   | 0.314      | 1.000        | 0.300 (0.094)    | 0.801 (0.251)    | -         |     1.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3402 | 2024-03-21 | Imperial      | L   | 0.312      | -            | -                | -                | -         |    -9.06 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3609 | 2024-03-12 | HEROIC        | W   | 0.254      | -            | -                | -                | -         |     2.48 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3625 | 2024-03-11 | Apeks         | W   | 0.247      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3636 | 2024-03-11 | B8            | W   | 0.246      | -            | -                | -                | -         |     0.23 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4234 | 2024-02-15 | Natus Vincere | W   | 0.080      | -            | -                | -                | -         |     2.06 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4266 | 2024-02-14 | fnatic        | W   | 0.074      | -            | -                | -                | -         |     0.30 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4285 | 2024-02-14 | SAW           | W   | 0.072      | -            | -                | -                | -         |     0.11 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($158,124.68)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.48) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.892 | $40,000.00     | $35,700.00      |
| 2024-06-02 |      0.800 | $5,000.00      | $4,001.39       |
| 2024-05-12 |      0.659 | $32,000.00     | $21,102.22      |
| 2024-04-14 |      0.472 | $10,000.00     | $4,715.51       |
| 2024-03-31 |      0.380 | $20,000.00     | $7,605.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
