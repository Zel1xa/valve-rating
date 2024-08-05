### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.7<br />
<br />
Final Rank Value (942.7) = Starting Rank Value (958.7) + Head To Head Adjustments (-16.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.7
- 400 + ( ( 0.273 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 958.7


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
|           32 |      538 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.21 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      570 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.68 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      798 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.536 (0.199)    | 0 (0.000) |    11.24 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      857 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.560 (0.207)    | 0 (0.000) |    12.60 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      983 | 2024-06-18 | kONO            | L   | 0.882      | -            | -                | -                | -         |   -17.91 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      986 | 2024-06-17 | K10             | W   | 0.876      | -            | -                | -                | 0 (0.000) |     5.09 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1015 | 2024-06-16 | Verdant         | W   | 0.869      | 0.333        | 0.015 (0.004)    | 0.299 (0.087)    | 0 (0.000) |    10.17 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1558 | 2024-06-03 | Enterprise      | L   | 0.782      | -            | -                | -                | -         |   -14.06 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1567 | 2024-06-02 | ECLOT           | L   | 0.777      | -            | -                | -                | -         |    -6.53 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1573 | 2024-06-02 | SINNERS         | W   | 0.777      | 0.346        | 0.037 (0.010)    | 0.797 (0.214)    | 1 (0.777) |    15.44 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1582 | 2024-06-02 | Passion UA      | L   | 0.775      | -            | -                | -                | -         |    -8.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1599 | 2024-06-01 | ECLOT           | L   | 0.771      | -            | -                | -                | -         |    -6.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1642 | 2024-05-31 | SINNERS         | W   | 0.763      | 0.346        | 0.037 (0.010)    | 0.797 (0.210)    | 1 (0.763) |    15.97 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1646 | 2024-05-31 | Johnny Speeds   | W   | 0.762      | 0.371        | 0.122 (0.034)    | 0.942 (0.266)    | 0 (0.000) |    20.46 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1691 | 2024-05-29 | Rebels          | W   | 0.750      | 0.371        | 0.038 (0.011)    | 0.600 (0.167)    | 0 (0.000) |    14.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1704 | 2024-05-28 | GL Academy      | L   | 0.745      | -            | -                | -                | -         |   -17.27 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1774 | 2024-05-25 | Serbia          | L   | 0.723      | -            | -                | -                | -         |   -16.73 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1799 | 2024-05-23 | SINNERS         | L   | 0.711      | -            | -                | -                | -         |    -8.05 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1892 | 2024-05-21 | Rebels          | W   | 0.695      | 0.371        | 0.038 (0.010)    | 0.600 (0.155)    | 0 (0.000) |    12.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2179 | 2024-05-13 | Johnny Speeds   | L   | 0.643      | -            | -                | -                | -         |    -2.84 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2782 | 2024-04-18 | Johnny Speeds   | L   | 0.476      | -            | -                | -                | -         |    -2.09 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2829 | 2024-04-17 | Viperio         | W   | 0.469      | -            | -                | -                | -         |     2.01 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2852 | 2024-04-16 | Lilmix          | W   | 0.462      | -            | -                | -                | -         |     0.61 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2883 | 2024-04-14 | Sashi           | L   | 0.449      | -            | -                | -                | -         |    -3.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2997 | 2024-04-10 | SINNERS         | L   | 0.422      | -            | -                | -                | -         |    -3.40 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3117 | 2024-04-06 | Sashi           | L   | 0.395      | -            | -                | -                | -         |    -3.54 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3129 | 2024-04-05 | ECLOT           | W   | 0.389      | 0.333        | 0.062 (0.008)    | 0.558 (0.072)    | -         |     9.70 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3174 | 2024-04-04 | Sashi           | L   | 0.383      | -            | -                | -                | -         |    -3.38 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3253 | 2024-04-02 | Illuminar       | W   | 0.369      | -            | -                | -                | -         |     0.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3508 | 2024-03-17 | SINNERS         | L   | 0.264      | -            | -                | -                | -         |    -2.33 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3520 | 2024-03-16 | ECLOT           | L   | 0.258      | -            | -                | -                | -         |    -1.77 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3535 | 2024-03-15 | SINNERS         | W   | 0.251      | 0.345        | 0.037 (0.003)    | 0.797 (0.069)    | 1 (0.251) |     5.75 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,967.25)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.882 | $3,000.00      | $2,645.83       |
| 2024-06-02 |      0.777 | $3,048.00      | $2,369.68       |
| 2024-04-18 |      0.476 | $3,000.00      | $1,427.50       |
| 2024-04-06 |      0.395 | $3,000.00      | $1,185.83       |
| 2024-03-17 |      0.265 | $1,279.00      | $338.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
