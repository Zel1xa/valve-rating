### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.2<br />
<br />
Final Rank Value (944.2) = Starting Rank Value (960.1) + Head To Head Adjustments (-15.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 960.1
- 400 + ( ( 0.273 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 960.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      559 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.16 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      591 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.64 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      819 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.566 (0.210)    | 0 (0.000) |    11.19 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      878 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.550 (0.204)    | 0 (0.000) |    12.58 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     1004 | 2024-06-18 | kONO            | L   | 0.877      | -            | -                | -                | -         |   -17.88 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     1007 | 2024-06-17 | K10             | W   | 0.872      | -            | -                | -                | 0 (0.000) |     5.04 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1036 | 2024-06-16 | Verdant         | W   | 0.864      | 0.333        | 0.015 (0.004)    | 0.294 (0.085)    | 0 (0.000) |    10.15 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1579 | 2024-06-03 | Enterprise      | L   | 0.777      | -            | -                | -                | -         |   -13.93 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1588 | 2024-06-02 | ECLOT           | L   | 0.773      | -            | -                | -                | -         |    -6.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1594 | 2024-06-02 | SINNERS         | W   | 0.772      | 0.346        | 0.037 (0.010)    | 0.809 (0.216)    | 1 (0.772) |    15.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1603 | 2024-06-02 | Passion UA      | L   | 0.771      | -            | -                | -                | -         |    -8.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1620 | 2024-06-01 | ECLOT           | L   | 0.766      | -            | -                | -                | -         |    -6.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1663 | 2024-05-31 | SINNERS         | W   | 0.759      | 0.346        | 0.037 (0.010)    | 0.809 (0.212)    | 1 (0.759) |    15.96 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1667 | 2024-05-31 | Johnny Speeds   | W   | 0.757      | 0.371        | 0.122 (0.034)    | 1.000 (0.281)    | 0 (0.000) |    20.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1712 | 2024-05-29 | Rebels          | W   | 0.745      | 0.371        | 0.038 (0.011)    | 0.591 (0.163)    | 0 (0.000) |    13.86 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1725 | 2024-05-28 | GL Academy      | L   | 0.740      | -            | -                | -                | -         |   -17.21 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1795 | 2024-05-25 | Serbia          | L   | 0.718      | -            | -                | -                | -         |   -16.65 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1820 | 2024-05-23 | SINNERS         | L   | 0.706      | -            | -                | -                | -         |    -7.90 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1913 | 2024-05-21 | Rebels          | W   | 0.691      | 0.371        | 0.038 (0.010)    | 0.591 (0.151)    | 0 (0.000) |    12.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2200 | 2024-05-13 | Johnny Speeds   | L   | 0.639      | -            | -                | -                | -         |    -2.82 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2803 | 2024-04-18 | Johnny Speeds   | L   | 0.471      | -            | -                | -                | -         |    -2.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2850 | 2024-04-17 | Viperio         | W   | 0.464      | -            | -                | -                | -         |     1.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2873 | 2024-04-16 | Lilmix          | W   | 0.458      | -            | -                | -                | -         |     0.60 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2904 | 2024-04-14 | Sashi           | L   | 0.444      | -            | -                | -                | -         |    -3.90 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3018 | 2024-04-10 | SINNERS         | L   | 0.417      | -            | -                | -                | -         |    -3.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3138 | 2024-04-06 | Sashi           | L   | 0.391      | -            | -                | -                | -         |    -3.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3150 | 2024-04-05 | ECLOT           | W   | 0.384      | 0.333        | 0.062 (0.008)    | 0.550 (0.070)    | -         |     9.58 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3195 | 2024-04-04 | Sashi           | L   | 0.378      | -            | -                | -                | -         |    -3.36 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3274 | 2024-04-02 | Illuminar       | W   | 0.365      | -            | -                | -                | -         |     0.90 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3529 | 2024-03-17 | SINNERS         | L   | 0.259      | -            | -                | -                | -         |    -2.24 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3541 | 2024-03-16 | ECLOT           | L   | 0.253      | -            | -                | -                | -         |    -1.74 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3556 | 2024-03-15 | SINNERS         | W   | 0.247      | 0.345        | 0.037 (0.003)    | 0.809 (0.069)    | 1 (0.247) |     5.70 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,908.02)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.877 | $3,000.00      | $2,632.50       |
| 2024-06-02 |      0.773 | $3,048.00      | $2,356.13       |
| 2024-04-18 |      0.471 | $3,000.00      | $1,414.17       |
| 2024-04-06 |      0.391 | $3,000.00      | $1,172.50       |
| 2024-03-17 |      0.260 | $1,279.00      | $332.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
