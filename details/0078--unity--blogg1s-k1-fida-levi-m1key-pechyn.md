### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  938.8<br />
<br />
Final Rank Value (938.8) = Starting Rank Value (957.5) + Head To Head Adjustments (-18.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.5
- 400 + ( ( 0.273 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 957.5


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
|           32 |      510 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.02 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      542 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.55 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      770 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    11.42 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      829 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.560 (0.208)    | 0 (0.000) |    12.55 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      955 | 2024-06-18 | kONO            | L   | 0.885      | -            | -                | -                | -         |   -17.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      958 | 2024-06-17 | K10             | W   | 0.880      | -            | -                | -                | 0 (0.000) |     5.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |      987 | 2024-06-16 | Verdant         | W   | 0.872      | 0.333        | 0.015 (0.004)    | 0.299 (0.087)    | 0 (0.000) |    10.34 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1530 | 2024-06-03 | Enterprise      | L   | 0.785      | -            | -                | -                | -         |   -13.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1539 | 2024-06-02 | ECLOT           | L   | 0.781      | -            | -                | -                | -         |    -6.49 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1545 | 2024-06-02 | SINNERS         | W   | 0.780      | 0.346        | 0.037 (0.010)    | 0.757 (0.204)    | 1 (0.780) |    14.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1554 | 2024-06-02 | Passion UA      | L   | 0.779      | -            | -                | -                | -         |    -9.01 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1571 | 2024-06-01 | ECLOT           | L   | 0.774      | -            | -                | -                | -         |    -6.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1614 | 2024-05-31 | SINNERS         | W   | 0.767      | 0.346        | 0.037 (0.010)    | 0.757 (0.201)    | 1 (0.767) |    15.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1618 | 2024-05-31 | Johnny Speeds   | W   | 0.765      | 0.371        | 0.122 (0.035)    | 0.902 (0.256)    | 0 (0.000) |    20.49 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1663 | 2024-05-29 | Rebels          | W   | 0.753      | 0.371        | 0.038 (0.011)    | 0.599 (0.167)    | 0 (0.000) |    14.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1676 | 2024-05-28 | GL Academy      | L   | 0.748      | -            | -                | -                | -         |   -17.24 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1746 | 2024-05-25 | Serbia          | L   | 0.726      | -            | -                | -                | -         |   -16.70 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1771 | 2024-05-23 | SINNERS         | L   | 0.714      | -            | -                | -                | -         |    -8.97 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1864 | 2024-05-21 | Rebels          | W   | 0.699      | 0.371        | 0.038 (0.010)    | 0.599 (0.155)    | 0 (0.000) |    12.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2151 | 2024-05-13 | Johnny Speeds   | L   | 0.647      | -            | -                | -                | -         |    -2.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2754 | 2024-04-18 | Johnny Speeds   | L   | 0.479      | -            | -                | -                | -         |    -2.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2801 | 2024-04-17 | Viperio         | W   | 0.472      | -            | -                | -                | -         |     2.06 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2824 | 2024-04-16 | Lilmix          | W   | 0.465      | -            | -                | -                | -         |     0.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2855 | 2024-04-14 | Sashi           | L   | 0.452      | -            | -                | -                | -         |    -3.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2969 | 2024-04-10 | SINNERS         | L   | 0.425      | -            | -                | -                | -         |    -4.17 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3089 | 2024-04-06 | Sashi           | L   | 0.399      | -            | -                | -                | -         |    -3.55 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3101 | 2024-04-05 | ECLOT           | W   | 0.392      | 0.333        | 0.062 (0.008)    | 0.559 (0.073)    | -         |     9.80 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3146 | 2024-04-04 | Sashi           | L   | 0.386      | -            | -                | -                | -         |    -3.40 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3225 | 2024-04-02 | Illuminar       | W   | 0.373      | -            | -                | -                | -         |     0.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3480 | 2024-03-17 | SINNERS         | L   | 0.267      | -            | -                | -                | -         |    -2.91 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3492 | 2024-03-16 | ECLOT           | L   | 0.261      | -            | -                | -                | -         |    -1.78 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3507 | 2024-03-15 | SINNERS         | W   | 0.255      | 0.345        | 0.037 (0.003)    | 0.757 (0.067)    | 1 (0.255) |     5.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,013.21)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.885 | $3,000.00      | $2,656.18       |
| 2024-06-02 |      0.781 | $3,048.00      | $2,380.19       |
| 2024-04-18 |      0.479 | $3,000.00      | $1,437.85       |
| 2024-04-06 |      0.399 | $3,000.00      | $1,196.18       |
| 2024-03-17 |      0.268 | $1,279.00      | $342.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
