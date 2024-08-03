### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1642.1<br />
<br />
Final Rank Value (1642.1) = Starting Rank Value (1705.2) + Head To Head Adjustments (-63.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.637[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 0.850[<sup>2</sup>](#table1)

The average of these factors is 0.638<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1705.2
- 400 + ( ( 0.638 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1705.2


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
|           38 |       52 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.72 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |       99 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -21.58 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      467 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.87 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      509 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.650 (0.650)    | 0.396 (0.396)    | 1 (1.000) |    22.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      611 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.313 (0.313)    | 0.394 (0.394)    | 1 (1.000) |    12.84 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      944 | 2024-06-15 | Natus Vincere | L   | 0.874      | -            | -                | -                | -         |    -5.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |      974 | 2024-06-14 | Astralis      | W   | 0.867      | 0.729        | 0.353 (0.223)    | 0.396 (0.250)    | 1 (0.867) |    14.62 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1009 | 2024-06-13 | Spirit        | L   | 0.861      | -            | -                | -                | -         |    -5.25 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1048 | 2024-06-12 | Vitality      | W   | 0.853      | 0.729        | 0.650 (0.404)    | 0.396 (0.247)    | 1 (0.853) |    20.45 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1582 | 2024-05-29 | BIG           | L   | 0.760      | -            | -                | -                | -         |   -20.80 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1597 | 2024-05-28 | FaZe          | L   | 0.754      | -            | -                | -                | -         |    -9.27 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1618 | 2024-05-27 | HEROIC        | W   | 0.748      | 0.624        | 0.230 (0.107)    | 0.388 (0.181)    | 1 (0.748) |     8.15 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1908 | 2024-05-17 | Falcons       | L   | 0.679      | -            | -                | -                | -         |   -17.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     1947 | 2024-05-16 | MOUZ          | L   | 0.672      | -            | -                | -                | -         |    -6.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2046 | 2024-05-14 | Falcons       | W   | 0.660      | 0.769        | 0.225 (0.114)    | -                | 1 (0.660) |     3.76 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2168 | 2024-05-09 | Complexity    | L   | 0.626      | -            | -                | -                | -         |   -10.37 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2186 | 2024-05-08 | The MongolZ   | W   | 0.620      | 0.889        | 1.000 (0.551)    | 0.745 (0.411)    | 1 (0.620) |    15.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2202 | 2024-05-07 | GamerLegion   | W   | 0.614      | 0.889        | 0.174 (0.095)    | -                | 1 (0.614) |     0.96 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2390 | 2024-04-28 | SAW           | W   | 0.553      | 0.889        | -                | 0.560 (0.275)    | 1 (0.553) |     1.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2421 | 2024-04-27 | fnatic        | W   | 0.545      | 0.889        | 0.290 (0.140)    | 0.627 (0.304)    | 1 (0.545) |     2.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2463 | 2024-04-25 | FaZe          | L   | 0.534      | -            | -                | -                | -         |    -7.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2486 | 2024-04-24 | SAW           | W   | 0.526      | 0.889        | -                | 0.560 (0.262)    | -         |     0.91 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2509 | 2024-04-23 | fnatic        | L   | 0.519      | -            | -                | -                | -         |   -14.32 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2805 | 2024-04-12 | G2            | L   | 0.444      | -            | -                | -                | -         |    -2.38 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2889 | 2024-04-10 | Astralis      | L   | 0.431      | -            | -                | -                | -         |    -6.87 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     2941 | 2024-04-08 | FlyQuest      | W   | 0.424      | -            | -                | -                | -         |     0.65 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     2971 | 2024-04-08 | Wildcard      | W   | 0.417      | -            | -                | -                | -         |     0.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3268 | 2024-03-24 | G2            | L   | 0.319      | -            | -                | -                | -         |    -1.68 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3281 | 2024-03-23 | Eternal Fire  | L   | 0.312      | -            | -                | -                | -         |    -4.84 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3297 | 2024-03-22 | HEROIC        | W   | 0.305      | -            | -                | -                | -         |     3.12 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3311 | 2024-03-21 | paiN          | W   | 0.300      | 1.000        | 0.324 (0.097)    | 0.859 (0.258)    | -         |     1.26 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3321 | 2024-03-21 | Imperial      | L   | 0.299      | -            | -                | -                | -         |    -8.78 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3521 | 2024-03-12 | HEROIC        | W   | 0.240      | -            | -                | -                | -         |     2.34 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3536 | 2024-03-11 | Apeks         | W   | 0.234      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3547 | 2024-03-11 | B8            | W   | 0.233      | -            | -                | -                | -         |     0.22 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4128 | 2024-02-15 | Natus Vincere | W   | 0.066      | -            | -                | -                | -         |     1.71 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4160 | 2024-02-14 | fnatic        | W   | 0.061      | -            | -                | -                | -         |     0.24 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4179 | 2024-02-14 | SAW           | W   | 0.058      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($161,702.96)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.879 | $40,000.00     | $35,168.52      |
| 2024-06-02 |      0.787 | $5,000.00      | $3,934.95       |
| 2024-05-12 |      0.646 | $32,000.00     | $20,677.04      |
| 2024-04-14 |      0.458 | $10,000.00     | $4,582.64       |
| 2024-03-31 |      0.367 | $20,000.00     | $7,339.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
