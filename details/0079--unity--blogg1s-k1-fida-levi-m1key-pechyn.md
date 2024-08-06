### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  952.3<br />
<br />
Final Rank Value (952.3) = Starting Rank Value (958.9) + Head To Head Adjustments (-6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.203[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.9
- 400 + ( ( 0.272 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 958.9


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
|           33 |       10 | 2024-08-06 | NAVI Junior     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.20 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           32 |      583 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.01 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      615 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.55 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      843 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.553 (0.205)    | 0 (0.000) |    11.30 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      902 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.537 (0.199)    | 0 (0.000) |    12.70 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     1028 | 2024-06-18 | kONO            | L   | 0.871      | -            | -                | -                | -         |   -17.64 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     1031 | 2024-06-17 | K10             | W   | 0.865      | -            | -                | -                | 0 (0.000) |     5.01 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1060 | 2024-06-16 | Verdant         | W   | 0.858      | 0.333        | 0.015 (0.004)    | 0.287 (0.082)    | 0 (0.000) |    10.21 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1603 | 2024-06-03 | Enterprise      | L   | 0.771      | -            | -                | -                | -         |   -13.71 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1612 | 2024-06-02 | ECLOT           | L   | 0.767      | -            | -                | -                | -         |    -6.38 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1618 | 2024-06-02 | SINNERS         | W   | 0.766      | 0.346        | 0.037 (0.010)    | 0.800 (0.212)    | 1 (0.766) |    15.37 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1627 | 2024-06-02 | Passion UA      | L   | 0.764      | -            | -                | -                | -         |    -8.68 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1644 | 2024-06-01 | ECLOT           | L   | 0.760      | -            | -                | -                | -         |    -6.49 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1687 | 2024-05-31 | SINNERS         | W   | 0.752      | 0.346        | 0.037 (0.010)    | 0.800 (0.208)    | 1 (0.752) |    15.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1691 | 2024-05-31 | Johnny Speeds   | W   | 0.751      | 0.371        | 0.122 (0.034)    | 1.000 (0.278)    | 0 (0.000) |    20.25 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1736 | 2024-05-29 | Rebels          | W   | 0.739      | 0.371        | 0.038 (0.010)    | 0.578 (0.158)    | 0 (0.000) |    13.79 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1749 | 2024-05-28 | GL Academy      | L   | 0.734      | -            | -                | -                | -         |   -17.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1819 | 2024-05-25 | Serbia          | L   | 0.712      | -            | -                | -                | -         |   -16.39 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1844 | 2024-05-23 | SINNERS         | L   | 0.700      | -            | -                | -                | -         |    -7.76 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1937 | 2024-05-21 | Rebels          | W   | 0.684      | 0.371        | 0.038 (0.010)    | 0.578 (0.147)    | -         |    12.14 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2224 | 2024-05-13 | Johnny Speeds   | L   | 0.632      | -            | -                | -                | -         |    -2.73 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2827 | 2024-04-18 | Johnny Speeds   | L   | 0.465      | -            | -                | -                | -         |    -2.00 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2874 | 2024-04-17 | Viperio         | W   | 0.458      | -            | -                | -                | -         |     1.97 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2897 | 2024-04-16 | Lilmix          | W   | 0.451      | -            | -                | -                | -         |     0.60 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2928 | 2024-04-14 | Sashi           | L   | 0.438      | -            | -                | -                | -         |    -3.80 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3042 | 2024-04-10 | SINNERS         | L   | 0.411      | -            | -                | -                | -         |    -3.23 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3162 | 2024-04-06 | Sashi           | L   | 0.384      | -            | -                | -                | -         |    -3.41 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3174 | 2024-04-05 | ECLOT           | W   | 0.378      | 0.333        | 0.061 (0.008)    | 0.537 (0.068)    | -         |     9.46 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3219 | 2024-04-04 | Sashi           | L   | 0.372      | -            | -                | -                | -         |    -3.26 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3298 | 2024-04-02 | Illuminar       | W   | 0.358      | -            | -                | -                | -         |     0.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3553 | 2024-03-17 | SINNERS         | L   | 0.253      | -            | -                | -                | -         |    -2.17 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3565 | 2024-03-16 | ECLOT           | L   | 0.247      | -            | -                | -                | -         |    -1.67 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3580 | 2024-03-15 | SINNERS         | W   | 0.241      | 0.345        | 0.037 (0.003)    | 0.800 (0.066)    | 1 (0.241) |     5.57 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,822.87)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.871 | $3,000.00      | $2,613.33       |
| 2024-06-02 |      0.767 | $3,048.00      | $2,336.66       |
| 2024-04-18 |      0.465 | $3,000.00      | $1,395.00       |
| 2024-04-06 |      0.384 | $3,000.00      | $1,153.33       |
| 2024-03-17 |      0.254 | $1,279.00      | $324.55         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
