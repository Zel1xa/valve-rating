### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  943.0<br />
<br />
Final Rank Value (943.0) = Starting Rank Value (959.1) + Head To Head Adjustments (-16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 959.1
- 400 + ( ( 0.273 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 959.1


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
|           32 |      534 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.20 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      566 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.68 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      794 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    11.24 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      853 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.560 (0.208)    | 0 (0.000) |    12.59 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      979 | 2024-06-18 | kONO            | L   | 0.884      | -            | -                | -                | -         |   -17.96 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      982 | 2024-06-17 | K10             | W   | 0.879      | -            | -                | -                | 0 (0.000) |     5.10 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1011 | 2024-06-16 | Verdant         | W   | 0.871      | 0.333        | 0.015 (0.004)    | 0.299 (0.087)    | 0 (0.000) |    10.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1554 | 2024-06-03 | Enterprise      | L   | 0.784      | -            | -                | -                | -         |   -14.11 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1563 | 2024-06-02 | ECLOT           | L   | 0.780      | -            | -                | -                | -         |    -6.56 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1569 | 2024-06-02 | SINNERS         | W   | 0.779      | 0.346        | 0.037 (0.010)    | 0.797 (0.215)    | 1 (0.779) |    15.47 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1578 | 2024-06-02 | Passion UA      | L   | 0.778      | -            | -                | -                | -         |    -9.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1595 | 2024-06-01 | ECLOT           | L   | 0.773      | -            | -                | -                | -         |    -6.69 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1638 | 2024-05-31 | SINNERS         | W   | 0.766      | 0.346        | 0.037 (0.010)    | 0.797 (0.211)    | 1 (0.766) |    16.01 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1642 | 2024-05-31 | Johnny Speeds   | W   | 0.764      | 0.371        | 0.122 (0.035)    | 0.941 (0.267)    | 0 (0.000) |    20.52 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1687 | 2024-05-29 | Rebels          | W   | 0.752      | 0.371        | 0.038 (0.011)    | 0.600 (0.167)    | 0 (0.000) |    14.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1700 | 2024-05-28 | GL Academy      | L   | 0.747      | -            | -                | -                | -         |   -17.32 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1770 | 2024-05-25 | Serbia          | L   | 0.725      | -            | -                | -                | -         |   -16.79 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1795 | 2024-05-23 | SINNERS         | L   | 0.713      | -            | -                | -                | -         |    -8.09 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1888 | 2024-05-21 | Rebels          | W   | 0.698      | 0.371        | 0.038 (0.010)    | 0.600 (0.155)    | 0 (0.000) |    12.39 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2175 | 2024-05-13 | Johnny Speeds   | L   | 0.646      | -            | -                | -                | -         |    -2.85 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2778 | 2024-04-18 | Johnny Speeds   | L   | 0.478      | -            | -                | -                | -         |    -2.11 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2825 | 2024-04-17 | Viperio         | W   | 0.471      | -            | -                | -                | -         |     2.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2848 | 2024-04-16 | Lilmix          | W   | 0.464      | -            | -                | -                | -         |     0.61 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2879 | 2024-04-14 | Sashi           | L   | 0.451      | -            | -                | -                | -         |    -3.95 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2993 | 2024-04-10 | SINNERS         | L   | 0.424      | -            | -                | -                | -         |    -3.42 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3113 | 2024-04-06 | Sashi           | L   | 0.398      | -            | -                | -                | -         |    -3.56 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3125 | 2024-04-05 | ECLOT           | W   | 0.391      | 0.333        | 0.062 (0.008)    | 0.558 (0.073)    | -         |     9.76 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3170 | 2024-04-04 | Sashi           | L   | 0.385      | -            | -                | -                | -         |    -3.41 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3249 | 2024-04-02 | Illuminar       | W   | 0.372      | -            | -                | -                | -         |     0.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3504 | 2024-03-17 | SINNERS         | L   | 0.266      | -            | -                | -                | -         |    -2.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3516 | 2024-03-16 | ECLOT           | L   | 0.260      | -            | -                | -                | -         |    -1.78 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3531 | 2024-03-15 | SINNERS         | W   | 0.254      | 0.345        | 0.037 (0.003)    | 0.797 (0.070)    | 1 (0.254) |     5.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,999.02)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.884 | $3,000.00      | $2,652.99       |
| 2024-06-02 |      0.780 | $3,048.00      | $2,376.95       |
| 2024-04-18 |      0.478 | $3,000.00      | $1,434.65       |
| 2024-04-06 |      0.398 | $3,000.00      | $1,192.99       |
| 2024-03-17 |      0.267 | $1,279.00      | $341.45         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
