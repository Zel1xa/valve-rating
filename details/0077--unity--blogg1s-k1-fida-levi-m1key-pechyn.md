### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  951.7<br />
<br />
Final Rank Value (951.7) = Starting Rank Value (958.7) + Head To Head Adjustments (-7.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.203[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.7
- 400 + ( ( 0.272 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 958.7


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
|           33 |        2 | 2024-08-06 | NAVI Junior     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.18 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           32 |      568 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.06 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      600 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.59 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      828 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.553 (0.205)    | 0 (0.000) |    11.31 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      887 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.537 (0.199)    | 0 (0.000) |    12.67 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     1013 | 2024-06-18 | kONO            | L   | 0.872      | -            | -                | -                | -         |   -17.64 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     1016 | 2024-06-17 | K10             | W   | 0.866      | -            | -                | -                | 0 (0.000) |     5.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     1045 | 2024-06-16 | Verdant         | W   | 0.859      | 0.333        | 0.015 (0.004)    | 0.287 (0.082)    | 0 (0.000) |    10.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1588 | 2024-06-03 | Enterprise      | L   | 0.772      | -            | -                | -                | -         |   -13.76 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1597 | 2024-06-02 | ECLOT           | L   | 0.767      | -            | -                | -                | -         |    -6.40 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1603 | 2024-06-02 | SINNERS         | W   | 0.767      | 0.346        | 0.037 (0.010)    | 0.790 (0.209)    | 1 (0.767) |    15.36 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1612 | 2024-06-02 | Passion UA      | L   | 0.765      | -            | -                | -                | -         |    -8.73 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1629 | 2024-06-01 | ECLOT           | L   | 0.761      | -            | -                | -                | -         |    -6.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1672 | 2024-05-31 | SINNERS         | W   | 0.753      | 0.346        | 0.037 (0.010)    | 0.790 (0.206)    | 1 (0.753) |    15.88 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1676 | 2024-05-31 | Johnny Speeds   | W   | 0.752      | 0.371        | 0.122 (0.034)    | 1.000 (0.279)    | 0 (0.000) |    20.25 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1721 | 2024-05-29 | Rebels          | W   | 0.739      | 0.371        | 0.038 (0.010)    | 0.578 (0.158)    | 0 (0.000) |    13.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1734 | 2024-05-28 | GL Academy      | L   | 0.735      | -            | -                | -                | -         |   -17.03 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1804 | 2024-05-25 | Serbia          | L   | 0.713      | -            | -                | -                | -         |   -16.45 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1829 | 2024-05-23 | SINNERS         | L   | 0.700      | -            | -                | -                | -         |    -7.79 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1922 | 2024-05-21 | Rebels          | W   | 0.685      | 0.371        | 0.038 (0.010)    | 0.578 (0.147)    | -         |    12.15 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2209 | 2024-05-13 | Johnny Speeds   | L   | 0.633      | -            | -                | -                | -         |    -2.75 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2812 | 2024-04-18 | Johnny Speeds   | L   | 0.466      | -            | -                | -                | -         |    -2.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2859 | 2024-04-17 | Viperio         | W   | 0.459      | -            | -                | -                | -         |     1.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2882 | 2024-04-16 | Lilmix          | W   | 0.452      | -            | -                | -                | -         |     0.60 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2913 | 2024-04-14 | Sashi           | L   | 0.439      | -            | -                | -                | -         |    -3.82 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     3027 | 2024-04-10 | SINNERS         | L   | 0.412      | -            | -                | -                | -         |    -3.24 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3147 | 2024-04-06 | Sashi           | L   | 0.385      | -            | -                | -                | -         |    -3.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3159 | 2024-04-05 | ECLOT           | W   | 0.379      | 0.333        | 0.061 (0.008)    | 0.537 (0.068)    | -         |     9.47 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3204 | 2024-04-04 | Sashi           | L   | 0.373      | -            | -                | -                | -         |    -3.28 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3283 | 2024-04-02 | Illuminar       | W   | 0.359      | -            | -                | -                | -         |     0.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3538 | 2024-03-17 | SINNERS         | L   | 0.254      | -            | -                | -                | -         |    -2.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3550 | 2024-03-16 | ECLOT           | L   | 0.248      | -            | -                | -                | -         |    -1.68 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3565 | 2024-03-15 | SINNERS         | W   | 0.241      | 0.345        | 0.037 (0.003)    | 0.790 (0.066)    | 1 (0.241) |     5.58 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,832.74)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.872 | $3,000.00      | $2,615.56       |
| 2024-06-02 |      0.767 | $3,048.00      | $2,338.92       |
| 2024-04-18 |      0.466 | $3,000.00      | $1,397.22       |
| 2024-04-06 |      0.385 | $3,000.00      | $1,155.56       |
| 2024-03-17 |      0.254 | $1,279.00      | $325.49         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
