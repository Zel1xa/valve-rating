### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  938.5<br />
<br />
Final Rank Value (938.5) = Starting Rank Value (957.6) + Head To Head Adjustments (-19.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.6
- 400 + ( ( 0.273 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 957.6


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
|           32 |      502 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.08 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      534 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.55 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      762 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    11.43 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      821 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.560 (0.208)    | 0 (0.000) |    12.53 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      947 | 2024-06-18 | kONO            | L   | 0.886      | -            | -                | -                | -         |   -17.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      950 | 2024-06-17 | K10             | W   | 0.880      | -            | -                | -                | 0 (0.000) |     5.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |      979 | 2024-06-16 | Verdant         | W   | 0.873      | 0.333        | 0.015 (0.004)    | 0.299 (0.087)    | 0 (0.000) |    10.31 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1522 | 2024-06-03 | Enterprise      | L   | 0.786      | -            | -                | -                | -         |   -13.99 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1531 | 2024-06-02 | ECLOT           | L   | 0.782      | -            | -                | -                | -         |    -6.52 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1537 | 2024-06-02 | SINNERS         | W   | 0.781      | 0.346        | 0.037 (0.010)    | 0.758 (0.205)    | 1 (0.781) |    14.80 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1546 | 2024-06-02 | Passion UA      | L   | 0.779      | -            | -                | -                | -         |    -9.04 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1563 | 2024-06-01 | ECLOT           | L   | 0.775      | -            | -                | -                | -         |    -6.67 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1606 | 2024-05-31 | SINNERS         | W   | 0.767      | 0.346        | 0.037 (0.010)    | 0.758 (0.201)    | 1 (0.767) |    15.29 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1610 | 2024-05-31 | Johnny Speeds   | W   | 0.766      | 0.371        | 0.122 (0.035)    | 0.901 (0.256)    | 0 (0.000) |    20.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1655 | 2024-05-29 | Rebels          | W   | 0.754      | 0.371        | 0.038 (0.011)    | 0.599 (0.167)    | 0 (0.000) |    14.20 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1668 | 2024-05-28 | GL Academy      | L   | 0.749      | -            | -                | -                | -         |   -17.25 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1738 | 2024-05-25 | Serbia          | L   | 0.727      | -            | -                | -                | -         |   -16.72 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1763 | 2024-05-23 | SINNERS         | L   | 0.715      | -            | -                | -                | -         |    -9.01 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1856 | 2024-05-21 | Rebels          | W   | 0.699      | 0.371        | 0.038 (0.010)    | 0.599 (0.155)    | 0 (0.000) |    12.49 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2143 | 2024-05-13 | Johnny Speeds   | L   | 0.647      | -            | -                | -                | -         |    -2.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2746 | 2024-04-18 | Johnny Speeds   | L   | 0.480      | -            | -                | -                | -         |    -2.17 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2793 | 2024-04-17 | Viperio         | W   | 0.473      | -            | -                | -                | -         |     2.06 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2816 | 2024-04-16 | Lilmix          | W   | 0.466      | -            | -                | -                | -         |     0.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2847 | 2024-04-14 | Sashi           | L   | 0.453      | -            | -                | -                | -         |    -3.96 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2961 | 2024-04-10 | SINNERS         | L   | 0.426      | -            | -                | -                | -         |    -4.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3081 | 2024-04-06 | Sashi           | L   | 0.399      | -            | -                | -                | -         |    -3.59 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3093 | 2024-04-05 | ECLOT           | W   | 0.393      | 0.333        | 0.062 (0.008)    | 0.559 (0.073)    | -         |     9.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3138 | 2024-04-04 | Sashi           | L   | 0.387      | -            | -                | -                | -         |    -3.44 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3217 | 2024-04-02 | Illuminar       | W   | 0.373      | -            | -                | -                | -         |     0.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3472 | 2024-03-17 | SINNERS         | L   | 0.268      | -            | -                | -                | -         |    -2.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3484 | 2024-03-16 | ECLOT           | L   | 0.262      | -            | -                | -                | -         |    -1.79 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3499 | 2024-03-15 | SINNERS         | W   | 0.256      | 0.345        | 0.037 (0.003)    | 0.758 (0.067)    | 1 (0.256) |     5.31 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,022.78)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.886 | $3,000.00      | $2,658.33       |
| 2024-06-02 |      0.782 | $3,048.00      | $2,382.38       |
| 2024-04-18 |      0.480 | $3,000.00      | $1,440.00       |
| 2024-04-06 |      0.399 | $3,000.00      | $1,198.33       |
| 2024-03-17 |      0.269 | $1,279.00      | $343.73         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
