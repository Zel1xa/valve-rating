### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.8<br />
<br />
Final Rank Value (942.8) = Starting Rank Value (958.8) + Head To Head Adjustments (-16.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.8
- 400 + ( ( 0.273 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 958.8


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
|           32 |      551 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.21 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      583 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.68 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      811 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.574 (0.213)    | 0 (0.000) |    11.23 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      870 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.557 (0.207)    | 0 (0.000) |    12.61 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      996 | 2024-06-18 | kONO            | L   | 0.879      | -            | -                | -                | -         |   -17.86 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      999 | 2024-06-17 | K10             | W   | 0.873      | -            | -                | -                | 0 (0.000) |     5.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1028 | 2024-06-16 | Verdant         | W   | 0.865      | 0.333        | 0.015 (0.004)    | 0.298 (0.086)    | 0 (0.000) |    10.15 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1571 | 2024-06-03 | Enterprise      | L   | 0.779      | -            | -                | -                | -         |   -14.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1580 | 2024-06-02 | ECLOT           | L   | 0.774      | -            | -                | -                | -         |    -6.50 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1586 | 2024-06-02 | SINNERS         | W   | 0.773      | 0.346        | 0.037 (0.010)    | 0.794 (0.212)    | 1 (0.773) |    15.38 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1595 | 2024-06-02 | Passion UA      | L   | 0.772      | -            | -                | -                | -         |    -8.93 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1612 | 2024-06-01 | ECLOT           | L   | 0.767      | -            | -                | -                | -         |    -6.62 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1655 | 2024-05-31 | SINNERS         | W   | 0.760      | 0.346        | 0.037 (0.010)    | 0.794 (0.209)    | 1 (0.760) |    15.91 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1659 | 2024-05-31 | Johnny Speeds   | W   | 0.759      | 0.371        | 0.122 (0.034)    | 0.940 (0.264)    | 0 (0.000) |    20.39 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1704 | 2024-05-29 | Rebels          | W   | 0.746      | 0.371        | 0.038 (0.011)    | 0.598 (0.165)    | 0 (0.000) |    13.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1717 | 2024-05-28 | GL Academy      | L   | 0.741      | -            | -                | -                | -         |   -17.20 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1787 | 2024-05-25 | Serbia          | L   | 0.719      | -            | -                | -                | -         |   -16.64 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1812 | 2024-05-23 | SINNERS         | L   | 0.707      | -            | -                | -                | -         |    -8.00 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1905 | 2024-05-21 | Rebels          | W   | 0.692      | 0.371        | 0.038 (0.010)    | 0.598 (0.153)    | 0 (0.000) |    12.27 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2192 | 2024-05-13 | Johnny Speeds   | L   | 0.640      | -            | -                | -                | -         |    -2.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2795 | 2024-04-18 | Johnny Speeds   | L   | 0.472      | -            | -                | -                | -         |    -2.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2842 | 2024-04-17 | Viperio         | W   | 0.465      | -            | -                | -                | -         |     2.00 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2865 | 2024-04-16 | Lilmix          | W   | 0.459      | -            | -                | -                | -         |     0.61 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2896 | 2024-04-14 | Sashi           | L   | 0.445      | -            | -                | -                | -         |    -3.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3010 | 2024-04-10 | SINNERS         | L   | 0.419      | -            | -                | -                | -         |    -3.38 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3130 | 2024-04-06 | Sashi           | L   | 0.392      | -            | -                | -                | -         |    -3.50 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3142 | 2024-04-05 | ECLOT           | W   | 0.385      | 0.333        | 0.062 (0.008)    | 0.557 (0.071)    | -         |     9.61 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3187 | 2024-04-04 | Sashi           | L   | 0.379      | -            | -                | -                | -         |    -3.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3266 | 2024-04-02 | Illuminar       | W   | 0.366      | -            | -                | -                | -         |     0.91 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3521 | 2024-03-17 | SINNERS         | L   | 0.260      | -            | -                | -                | -         |    -2.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3533 | 2024-03-16 | ECLOT           | L   | 0.254      | -            | -                | -                | -         |    -1.74 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3548 | 2024-03-15 | SINNERS         | W   | 0.248      | 0.345        | 0.037 (0.003)    | 0.794 (0.068)    | 1 (0.248) |     5.67 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,922.82)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.879 | $3,000.00      | $2,635.83       |
| 2024-06-02 |      0.774 | $3,048.00      | $2,359.52       |
| 2024-04-18 |      0.472 | $3,000.00      | $1,417.50       |
| 2024-04-06 |      0.392 | $3,000.00      | $1,175.83       |
| 2024-03-17 |      0.261 | $1,279.00      | $334.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
