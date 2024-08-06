### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.2<br />
<br />
Final Rank Value (944.2) = Starting Rank Value (959.6) + Head To Head Adjustments (-15.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.204[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 959.6
- 400 + ( ( 0.273 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 959.6


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
|           32 |      562 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.12 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      594 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.61 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      822 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.566 (0.210)    | 0 (0.000) |    11.19 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      881 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.550 (0.204)    | 0 (0.000) |    12.60 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     1007 | 2024-06-18 | kONO            | L   | 0.875      | -            | -                | -                | -         |   -17.84 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     1010 | 2024-06-17 | K10             | W   | 0.870      | -            | -                | -                | 0 (0.000) |     5.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1039 | 2024-06-16 | Verdant         | W   | 0.862      | 0.333        | 0.015 (0.004)    | 0.294 (0.084)    | 0 (0.000) |    10.14 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1582 | 2024-06-03 | Enterprise      | L   | 0.775      | -            | -                | -                | -         |   -13.85 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1591 | 2024-06-02 | ECLOT           | L   | 0.771      | -            | -                | -                | -         |    -6.47 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1597 | 2024-06-02 | SINNERS         | W   | 0.770      | 0.346        | 0.037 (0.010)    | 0.808 (0.215)    | 1 (0.770) |    15.39 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1606 | 2024-06-02 | Passion UA      | L   | 0.769      | -            | -                | -                | -         |    -8.82 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1623 | 2024-06-01 | ECLOT           | L   | 0.764      | -            | -                | -                | -         |    -6.59 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1666 | 2024-05-31 | SINNERS         | W   | 0.757      | 0.346        | 0.037 (0.010)    | 0.808 (0.212)    | 1 (0.757) |    15.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1670 | 2024-05-31 | Johnny Speeds   | W   | 0.755      | 0.371        | 0.122 (0.034)    | 1.000 (0.280)    | 0 (0.000) |    20.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1715 | 2024-05-29 | Rebels          | W   | 0.743      | 0.371        | 0.038 (0.010)    | 0.591 (0.163)    | 0 (0.000) |    13.83 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1728 | 2024-05-28 | GL Academy      | L   | 0.738      | -            | -                | -                | -         |   -17.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1798 | 2024-05-25 | Serbia          | L   | 0.716      | -            | -                | -                | -         |   -16.59 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1823 | 2024-05-23 | SINNERS         | L   | 0.704      | -            | -                | -                | -         |    -7.86 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1916 | 2024-05-21 | Rebels          | W   | 0.689      | 0.371        | 0.038 (0.010)    | 0.591 (0.151)    | 0 (0.000) |    12.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2203 | 2024-05-13 | Johnny Speeds   | L   | 0.637      | -            | -                | -                | -         |    -2.80 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2806 | 2024-04-18 | Johnny Speeds   | L   | 0.469      | -            | -                | -                | -         |    -2.06 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2853 | 2024-04-17 | Viperio         | W   | 0.462      | -            | -                | -                | -         |     1.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2876 | 2024-04-16 | Lilmix          | W   | 0.455      | -            | -                | -                | -         |     0.60 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2907 | 2024-04-14 | Sashi           | L   | 0.442      | -            | -                | -                | -         |    -3.87 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3021 | 2024-04-10 | SINNERS         | L   | 0.415      | -            | -                | -                | -         |    -3.28 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3141 | 2024-04-06 | Sashi           | L   | 0.389      | -            | -                | -                | -         |    -3.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3153 | 2024-04-05 | ECLOT           | W   | 0.382      | 0.333        | 0.062 (0.008)    | 0.549 (0.070)    | -         |     9.53 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3198 | 2024-04-04 | Sashi           | L   | 0.376      | -            | -                | -                | -         |    -3.33 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3277 | 2024-04-02 | Illuminar       | W   | 0.363      | -            | -                | -                | -         |     0.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3532 | 2024-03-17 | SINNERS         | L   | 0.257      | -            | -                | -                | -         |    -2.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3544 | 2024-03-16 | ECLOT           | L   | 0.251      | -            | -                | -                | -         |    -1.72 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3559 | 2024-03-15 | SINNERS         | W   | 0.245      | 0.345        | 0.037 (0.003)    | 0.808 (0.068)    | 1 (0.245) |     5.65 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,878.40)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.875 | $3,000.00      | $2,625.83       |
| 2024-06-02 |      0.771 | $3,048.00      | $2,349.36       |
| 2024-04-18 |      0.469 | $3,000.00      | $1,407.50       |
| 2024-04-06 |      0.389 | $3,000.00      | $1,165.83       |
| 2024-03-17 |      0.258 | $1,279.00      | $329.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
