### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.4<br />
<br />
Final Rank Value (944.4) = Starting Rank Value (959.2) + Head To Head Adjustments (-14.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.204[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 959.2
- 400 + ( ( 0.272 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 959.2


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
|           32 |      566 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.09 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      598 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.59 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      826 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.565 (0.209)    | 0 (0.000) |    11.29 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      885 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.549 (0.203)    | 0 (0.000) |    12.64 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     1011 | 2024-06-18 | kONO            | L   | 0.873      | -            | -                | -                | -         |   -17.68 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     1014 | 2024-06-17 | K10             | W   | 0.867      | -            | -                | -                | 0 (0.000) |     5.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1043 | 2024-06-16 | Verdant         | W   | 0.859      | 0.333        | 0.015 (0.004)    | 0.294 (0.084)    | 0 (0.000) |    10.14 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1586 | 2024-06-03 | Enterprise      | L   | 0.773      | -            | -                | -                | -         |   -13.78 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1595 | 2024-06-02 | ECLOT           | L   | 0.768      | -            | -                | -                | -         |    -6.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1601 | 2024-06-02 | SINNERS         | W   | 0.767      | 0.346        | 0.037 (0.010)    | 0.808 (0.214)    | 1 (0.767) |    15.36 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1610 | 2024-06-02 | Passion UA      | L   | 0.766      | -            | -                | -                | -         |    -8.75 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1627 | 2024-06-01 | ECLOT           | L   | 0.762      | -            | -                | -                | -         |    -6.55 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1670 | 2024-05-31 | SINNERS         | W   | 0.754      | 0.346        | 0.037 (0.010)    | 0.808 (0.211)    | 1 (0.754) |    15.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1674 | 2024-05-31 | Johnny Speeds   | W   | 0.753      | 0.371        | 0.122 (0.034)    | 1.000 (0.279)    | 0 (0.000) |    20.25 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1719 | 2024-05-29 | Rebels          | W   | 0.740      | 0.371        | 0.038 (0.010)    | 0.591 (0.162)    | 0 (0.000) |    13.82 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1732 | 2024-05-28 | GL Academy      | L   | 0.736      | -            | -                | -                | -         |   -17.10 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1802 | 2024-05-25 | Serbia          | L   | 0.713      | -            | -                | -                | -         |   -16.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1827 | 2024-05-23 | SINNERS         | L   | 0.701      | -            | -                | -                | -         |    -7.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1920 | 2024-05-21 | Rebels          | W   | 0.686      | 0.371        | 0.038 (0.010)    | 0.591 (0.150)    | 0 (0.000) |    12.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2207 | 2024-05-13 | Johnny Speeds   | L   | 0.634      | -            | -                | -                | -         |    -2.77 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2810 | 2024-04-18 | Johnny Speeds   | L   | 0.467      | -            | -                | -                | -         |    -2.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2857 | 2024-04-17 | Viperio         | W   | 0.460      | -            | -                | -                | -         |     1.97 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2880 | 2024-04-16 | Lilmix          | W   | 0.453      | -            | -                | -                | -         |     0.60 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2911 | 2024-04-14 | Sashi           | L   | 0.439      | -            | -                | -                | -         |    -3.83 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3025 | 2024-04-10 | SINNERS         | L   | 0.413      | -            | -                | -                | -         |    -3.26 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3145 | 2024-04-06 | Sashi           | L   | 0.386      | -            | -                | -                | -         |    -3.44 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3157 | 2024-04-05 | ECLOT           | W   | 0.379      | 0.333        | 0.061 (0.008)    | 0.549 (0.069)    | -         |     9.47 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3202 | 2024-04-04 | Sashi           | L   | 0.374      | -            | -                | -                | -         |    -3.29 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3281 | 2024-04-02 | Illuminar       | W   | 0.360      | -            | -                | -                | -         |     0.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3536 | 2024-03-17 | SINNERS         | L   | 0.254      | -            | -                | -                | -         |    -2.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3548 | 2024-03-16 | ECLOT           | L   | 0.249      | -            | -                | -                | -         |    -1.70 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3563 | 2024-03-15 | SINNERS         | W   | 0.242      | 0.345        | 0.037 (0.003)    | 0.808 (0.067)    | 1 (0.242) |     5.59 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,845.08)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.873 | $3,000.00      | $2,618.33       |
| 2024-06-02 |      0.768 | $3,048.00      | $2,341.74       |
| 2024-04-18 |      0.467 | $3,000.00      | $1,400.00       |
| 2024-04-06 |      0.386 | $3,000.00      | $1,158.33       |
| 2024-03-17 |      0.255 | $1,279.00      | $326.68         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
