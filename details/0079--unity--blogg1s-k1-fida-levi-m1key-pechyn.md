### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.3<br />
<br />
Final Rank Value (944.3) = Starting Rank Value (958.8) + Head To Head Adjustments (-14.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.203[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.8
- 400 + ( ( 0.272 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 958.8


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
|           32 |      570 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.10 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      602 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.59 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      830 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.553 (0.205)    | 0 (0.000) |    11.29 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      889 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.537 (0.199)    | 0 (0.000) |    12.66 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     1015 | 2024-06-18 | kONO            | L   | 0.873      | -            | -                | -                | -         |   -17.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     1018 | 2024-06-17 | K10             | W   | 0.867      | -            | -                | -                | 0 (0.000) |     5.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1047 | 2024-06-16 | Verdant         | W   | 0.859      | 0.333        | 0.015 (0.004)    | 0.287 (0.082)    | 0 (0.000) |    10.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1590 | 2024-06-03 | Enterprise      | L   | 0.772      | -            | -                | -                | -         |   -13.78 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1599 | 2024-06-02 | ECLOT           | L   | 0.768      | -            | -                | -                | -         |    -6.41 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1605 | 2024-06-02 | SINNERS         | W   | 0.767      | 0.346        | 0.037 (0.010)    | 0.790 (0.210)    | 1 (0.767) |    15.37 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1614 | 2024-06-02 | Passion UA      | L   | 0.766      | -            | -                | -                | -         |    -8.74 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1631 | 2024-06-01 | ECLOT           | L   | 0.761      | -            | -                | -                | -         |    -6.53 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1674 | 2024-05-31 | SINNERS         | W   | 0.754      | 0.346        | 0.037 (0.010)    | 0.790 (0.206)    | 1 (0.754) |    15.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1678 | 2024-05-31 | Johnny Speeds   | W   | 0.752      | 0.371        | 0.122 (0.034)    | 1.000 (0.279)    | 0 (0.000) |    20.25 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1723 | 2024-05-29 | Rebels          | W   | 0.740      | 0.371        | 0.038 (0.010)    | 0.578 (0.158)    | 0 (0.000) |    13.83 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1736 | 2024-05-28 | GL Academy      | L   | 0.735      | -            | -                | -                | -         |   -17.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1806 | 2024-05-25 | Serbia          | L   | 0.713      | -            | -                | -                | -         |   -16.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1831 | 2024-05-23 | SINNERS         | L   | 0.701      | -            | -                | -                | -         |    -7.80 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1924 | 2024-05-21 | Rebels          | W   | 0.686      | 0.371        | 0.038 (0.010)    | 0.578 (0.147)    | 0 (0.000) |    12.17 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2211 | 2024-05-13 | Johnny Speeds   | L   | 0.634      | -            | -                | -                | -         |    -2.77 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2814 | 2024-04-18 | Johnny Speeds   | L   | 0.466      | -            | -                | -                | -         |    -2.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2861 | 2024-04-17 | Viperio         | W   | 0.459      | -            | -                | -                | -         |     1.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2884 | 2024-04-16 | Lilmix          | W   | 0.453      | -            | -                | -                | -         |     0.60 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2915 | 2024-04-14 | Sashi           | L   | 0.439      | -            | -                | -                | -         |    -3.83 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3029 | 2024-04-10 | SINNERS         | L   | 0.412      | -            | -                | -                | -         |    -3.25 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3149 | 2024-04-06 | Sashi           | L   | 0.386      | -            | -                | -                | -         |    -3.44 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3161 | 2024-04-05 | ECLOT           | W   | 0.379      | 0.333        | 0.061 (0.008)    | 0.537 (0.068)    | -         |     9.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3206 | 2024-04-04 | Sashi           | L   | 0.373      | -            | -                | -                | -         |    -3.29 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3285 | 2024-04-02 | Illuminar       | W   | 0.360      | -            | -                | -                | -         |     0.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3540 | 2024-03-17 | SINNERS         | L   | 0.254      | -            | -                | -                | -         |    -2.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3552 | 2024-03-16 | ECLOT           | L   | 0.248      | -            | -                | -                | -         |    -1.69 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3567 | 2024-03-15 | SINNERS         | W   | 0.242      | 0.345        | 0.037 (0.003)    | 0.790 (0.066)    | 1 (0.242) |     5.59 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,841.38)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.873 | $3,000.00      | $2,617.50       |
| 2024-06-02 |      0.768 | $3,048.00      | $2,340.89       |
| 2024-04-18 |      0.466 | $3,000.00      | $1,399.17       |
| 2024-04-06 |      0.386 | $3,000.00      | $1,157.50       |
| 2024-03-17 |      0.255 | $1,279.00      | $326.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
