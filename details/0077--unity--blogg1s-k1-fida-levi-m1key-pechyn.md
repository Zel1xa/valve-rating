### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  931.3<br />
<br />
Final Rank Value (931.3) = Starting Rank Value (958.8) + Head To Head Adjustments (-27.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.207[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.8
- 400 + ( ( 0.273 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 958.8


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
|           31 |      476 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -14.92 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      508 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.17 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      732 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.555 (0.206)    | 0 (0.000) |    11.72 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      788 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.032 (0.012)    | 0.580 (0.215)    | 0 (0.000) |    12.91 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           27 |      909 | 2024-06-18 | kONO            | L   | 0.891      | -            | -                | -                | -         |   -17.58 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |      912 | 2024-06-17 | K10             | W   | 0.885      | 0.333        | 0.008 (0.002)    | 0.138 (0.041)    | 0 (0.000) |     5.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1457 | 2024-06-03 | Enterprise      | L   | 0.791      | -            | -                | -                | -         |   -14.06 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1465 | 2024-06-02 | ECLOT           | L   | 0.786      | -            | -                | -                | -         |    -6.54 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1471 | 2024-06-02 | SINNERS         | W   | 0.786      | 0.346        | 0.037 (0.010)    | 0.784 (0.213)    | 1 (0.786) |    14.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1480 | 2024-06-02 | Passion UA      | L   | 0.784      | -            | -                | -                | -         |    -9.23 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1494 | 2024-06-01 | ECLOT           | L   | 0.780      | -            | -                | -                | -         |    -6.69 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1539 | 2024-05-31 | SINNERS         | W   | 0.772      | 0.346        | 0.037 (0.010)    | 0.784 (0.209)    | 1 (0.772) |    15.41 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1543 | 2024-05-31 | Johnny Speeds   | W   | 0.771      | 0.371        | 0.122 (0.035)    | 0.930 (0.266)    | 0 (0.000) |    20.64 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1588 | 2024-05-29 | Rebels          | W   | 0.759      | 0.371        | 0.038 (0.011)    | 0.605 (0.170)    | 0 (0.000) |    14.20 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1601 | 2024-05-28 | GL Academy      | L   | 0.754      | -            | -                | -                | -         |   -17.37 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1670 | 2024-05-25 | Serbia          | L   | 0.732      | -            | -                | -                | -         |   -16.83 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1695 | 2024-05-23 | SINNERS         | L   | 0.719      | -            | -                | -                | -         |    -9.05 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1788 | 2024-05-21 | Rebels          | W   | 0.704      | 0.371        | 0.038 (0.010)    | 0.605 (0.158)    | 0 (0.000) |    12.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2074 | 2024-05-13 | Johnny Speeds   | L   | 0.652      | -            | -                | -                | -         |    -2.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2675 | 2024-04-18 | Johnny Speeds   | L   | 0.485      | -            | -                | -                | -         |    -2.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2722 | 2024-04-17 | Viperio         | W   | 0.478      | -            | -                | -                | 0 (0.000) |     2.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2745 | 2024-04-16 | Lilmix          | W   | 0.471      | -            | -                | -                | -         |     0.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2776 | 2024-04-14 | Sashi           | L   | 0.458      | -            | -                | -                | -         |    -3.88 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2890 | 2024-04-10 | SINNERS         | L   | 0.431      | -            | -                | -                | -         |    -4.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3010 | 2024-04-06 | Sashi           | L   | 0.404      | -            | -                | -                | -         |    -3.52 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3022 | 2024-04-05 | ECLOT           | W   | 0.398      | 0.333        | 0.063 (0.008)    | 0.578 (0.077)    | -         |     9.95 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3067 | 2024-04-04 | Sashi           | L   | 0.392      | -            | -                | -                | -         |    -3.36 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3146 | 2024-04-02 | Illuminar       | W   | 0.378      | -            | -                | -                | -         |     0.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3396 | 2024-03-17 | SINNERS         | L   | 0.273      | -            | -                | -                | -         |    -2.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3408 | 2024-03-16 | ECLOT           | L   | 0.267      | -            | -                | -                | -         |    -1.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3422 | 2024-03-15 | SINNERS         | W   | 0.260      | 0.345        | 0.037 (0.003)    | 0.784 (0.070)    | 1 (0.260) |     5.44 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,086.33)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.891 | $3,000.00      | $2,672.64       |
| 2024-06-02 |      0.786 | $3,048.00      | $2,396.91       |
| 2024-04-18 |      0.485 | $3,000.00      | $1,454.31       |
| 2024-04-06 |      0.404 | $3,000.00      | $1,212.64       |
| 2024-03-17 |      0.274 | $1,279.00      | $349.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
