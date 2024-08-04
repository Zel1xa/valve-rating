### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.9<br />
<br />
Final Rank Value (942.9) = Starting Rank Value (959.2) + Head To Head Adjustments (-16.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 959.2
- 400 + ( ( 0.273 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 959.2


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
|           32 |      533 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.20 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      565 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.68 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      793 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    11.24 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      852 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.560 (0.208)    | 0 (0.000) |    12.58 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      978 | 2024-06-18 | kONO            | L   | 0.885      | -            | -                | -                | -         |   -17.96 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      981 | 2024-06-17 | K10             | W   | 0.879      | -            | -                | -                | 0 (0.000) |     5.10 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1010 | 2024-06-16 | Verdant         | W   | 0.871      | 0.333        | 0.015 (0.004)    | 0.299 (0.087)    | 0 (0.000) |    10.17 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1553 | 2024-06-03 | Enterprise      | L   | 0.785      | -            | -                | -                | -         |   -14.11 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1562 | 2024-06-02 | ECLOT           | L   | 0.780      | -            | -                | -                | -         |    -6.56 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1568 | 2024-06-02 | SINNERS         | W   | 0.779      | 0.346        | 0.037 (0.010)    | 0.797 (0.215)    | 1 (0.779) |    15.47 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1577 | 2024-06-02 | Passion UA      | L   | 0.778      | -            | -                | -                | -         |    -9.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1594 | 2024-06-01 | ECLOT           | L   | 0.774      | -            | -                | -                | -         |    -6.69 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1637 | 2024-05-31 | SINNERS         | W   | 0.766      | 0.346        | 0.037 (0.010)    | 0.797 (0.211)    | 1 (0.766) |    16.00 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1641 | 2024-05-31 | Johnny Speeds   | W   | 0.765      | 0.371        | 0.122 (0.035)    | 0.941 (0.267)    | 0 (0.000) |    20.53 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1686 | 2024-05-29 | Rebels          | W   | 0.752      | 0.371        | 0.038 (0.011)    | 0.599 (0.167)    | 0 (0.000) |    14.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1699 | 2024-05-28 | GL Academy      | L   | 0.747      | -            | -                | -                | -         |   -17.33 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1769 | 2024-05-25 | Serbia          | L   | 0.725      | -            | -                | -                | -         |   -16.79 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1794 | 2024-05-23 | SINNERS         | L   | 0.713      | -            | -                | -                | -         |    -8.10 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1887 | 2024-05-21 | Rebels          | W   | 0.698      | 0.371        | 0.038 (0.010)    | 0.599 (0.155)    | 0 (0.000) |    12.38 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2174 | 2024-05-13 | Johnny Speeds   | L   | 0.646      | -            | -                | -                | -         |    -2.85 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2777 | 2024-04-18 | Johnny Speeds   | L   | 0.479      | -            | -                | -                | -         |    -2.11 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2824 | 2024-04-17 | Viperio         | W   | 0.471      | -            | -                | -                | -         |     2.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2847 | 2024-04-16 | Lilmix          | W   | 0.465      | -            | -                | -                | -         |     0.61 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2878 | 2024-04-14 | Sashi           | L   | 0.451      | -            | -                | -                | -         |    -3.96 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2992 | 2024-04-10 | SINNERS         | L   | 0.425      | -            | -                | -                | -         |    -3.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3112 | 2024-04-06 | Sashi           | L   | 0.398      | -            | -                | -                | -         |    -3.57 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3124 | 2024-04-05 | ECLOT           | W   | 0.391      | 0.333        | 0.062 (0.008)    | 0.558 (0.073)    | -         |     9.77 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3169 | 2024-04-04 | Sashi           | L   | 0.385      | -            | -                | -                | -         |    -3.42 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3248 | 2024-04-02 | Illuminar       | W   | 0.372      | -            | -                | -                | -         |     0.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3503 | 2024-03-17 | SINNERS         | L   | 0.266      | -            | -                | -                | -         |    -2.36 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3515 | 2024-03-16 | ECLOT           | L   | 0.260      | -            | -                | -                | -         |    -1.79 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3530 | 2024-03-15 | SINNERS         | W   | 0.254      | 0.345        | 0.037 (0.003)    | 0.797 (0.070)    | 1 (0.254) |     5.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,003.03)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.885 | $3,000.00      | $2,653.89       |
| 2024-06-02 |      0.780 | $3,048.00      | $2,377.86       |
| 2024-04-18 |      0.479 | $3,000.00      | $1,435.56       |
| 2024-04-06 |      0.398 | $3,000.00      | $1,193.89       |
| 2024-03-17 |      0.267 | $1,279.00      | $341.84         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
