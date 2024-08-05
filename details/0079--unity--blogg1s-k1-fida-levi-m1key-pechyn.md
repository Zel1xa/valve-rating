### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.5<br />
<br />
Final Rank Value (944.5) = Starting Rank Value (960.0) + Head To Head Adjustments (-15.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.204[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 960.0
- 400 + ( ( 0.273 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 960.0


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
|           32 |      560 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.11 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      592 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.61 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      820 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.566 (0.210)    | 0 (0.000) |    11.19 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      879 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.550 (0.204)    | 0 (0.000) |    12.60 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     1005 | 2024-06-18 | kONO            | L   | 0.877      | -            | -                | -                | -         |   -17.88 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     1008 | 2024-06-17 | K10             | W   | 0.871      | -            | -                | -                | 0 (0.000) |     5.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1037 | 2024-06-16 | Verdant         | W   | 0.864      | 0.333        | 0.015 (0.004)    | 0.294 (0.085)    | 0 (0.000) |    10.15 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1580 | 2024-06-03 | Enterprise      | L   | 0.777      | -            | -                | -                | -         |   -13.88 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1589 | 2024-06-02 | ECLOT           | L   | 0.773      | -            | -                | -                | -         |    -6.49 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1595 | 2024-06-02 | SINNERS         | W   | 0.772      | 0.346        | 0.037 (0.010)    | 0.809 (0.216)    | 1 (0.772) |    15.42 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1604 | 2024-06-02 | Passion UA      | L   | 0.770      | -            | -                | -                | -         |    -8.85 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1621 | 2024-06-01 | ECLOT           | L   | 0.766      | -            | -                | -                | -         |    -6.61 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1664 | 2024-05-31 | SINNERS         | W   | 0.758      | 0.346        | 0.037 (0.010)    | 0.809 (0.212)    | 1 (0.758) |    15.96 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1668 | 2024-05-31 | Johnny Speeds   | W   | 0.757      | 0.371        | 0.122 (0.034)    | 1.000 (0.281)    | 0 (0.000) |    20.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1713 | 2024-05-29 | Rebels          | W   | 0.745      | 0.371        | 0.038 (0.011)    | 0.591 (0.163)    | 0 (0.000) |    13.87 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1726 | 2024-05-28 | GL Academy      | L   | 0.740      | -            | -                | -                | -         |   -17.20 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1796 | 2024-05-25 | Serbia          | L   | 0.718      | -            | -                | -                | -         |   -16.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1821 | 2024-05-23 | SINNERS         | L   | 0.706      | -            | -                | -                | -         |    -7.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1914 | 2024-05-21 | Rebels          | W   | 0.690      | 0.371        | 0.038 (0.010)    | 0.591 (0.151)    | 0 (0.000) |    12.20 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2201 | 2024-05-13 | Johnny Speeds   | L   | 0.638      | -            | -                | -                | -         |    -2.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2804 | 2024-04-18 | Johnny Speeds   | L   | 0.471      | -            | -                | -                | -         |    -2.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2851 | 2024-04-17 | Viperio         | W   | 0.464      | -            | -                | -                | -         |     1.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2874 | 2024-04-16 | Lilmix          | W   | 0.457      | -            | -                | -                | -         |     0.60 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2905 | 2024-04-14 | Sashi           | L   | 0.444      | -            | -                | -                | -         |    -3.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3019 | 2024-04-10 | SINNERS         | L   | 0.417      | -            | -                | -                | -         |    -3.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3139 | 2024-04-06 | Sashi           | L   | 0.390      | -            | -                | -                | -         |    -3.50 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3151 | 2024-04-05 | ECLOT           | W   | 0.384      | 0.333        | 0.062 (0.008)    | 0.550 (0.070)    | -         |     9.58 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3196 | 2024-04-04 | Sashi           | L   | 0.378      | -            | -                | -                | -         |    -3.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3275 | 2024-04-02 | Illuminar       | W   | 0.364      | -            | -                | -                | -         |     0.90 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3530 | 2024-03-17 | SINNERS         | L   | 0.259      | -            | -                | -                | -         |    -2.24 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3542 | 2024-03-16 | ECLOT           | L   | 0.253      | -            | -                | -                | -         |    -1.73 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3557 | 2024-03-15 | SINNERS         | W   | 0.247      | 0.345        | 0.037 (0.003)    | 0.809 (0.069)    | 1 (0.247) |     5.69 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,902.46)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.877 | $3,000.00      | $2,631.25       |
| 2024-06-02 |      0.773 | $3,048.00      | $2,354.86       |
| 2024-04-18 |      0.471 | $3,000.00      | $1,412.92       |
| 2024-04-06 |      0.390 | $3,000.00      | $1,171.25       |
| 2024-03-17 |      0.260 | $1,279.00      | $332.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
