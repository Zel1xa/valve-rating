### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  925.7<br />
<br />
Final Rank Value (925.7) = Starting Rank Value (959.7) + Head To Head Adjustments (-34.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.215[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 959.7
- 400 + ( ( 0.272 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 959.7


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
|           31 |      417 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -14.47 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      451 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -16.38 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      750 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.032 (0.012)    | 0.564 (0.209)    | 0 (0.000) |    11.71 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      877 | 2024-06-18 | kONO            | L   | 0.906      | -            | -                | -                | -         |   -17.46 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      880 | 2024-06-17 | K10             | W   | 0.900      | 0.333        | 0.008 (0.002)    | 0.133 (0.040)    | 0 (0.000) |     5.50 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |      906 | 2024-06-16 | Verdant         | W   | 0.892      | 0.333        | 0.015 (0.004)    | 0.305 (0.091)    | 0 (0.000) |    10.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1456 | 2024-06-03 | Enterprise      | L   | 0.806      | -            | -                | -                | -         |   -14.21 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1466 | 2024-06-02 | ECLOT           | L   | 0.801      | -            | -                | -                | -         |    -8.69 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1472 | 2024-06-02 | SINNERS         | W   | 0.800      | 0.346        | 0.038 (0.011)    | 0.768 (0.213)    | 1 (0.800) |    15.32 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1481 | 2024-06-02 | Passion UA      | L   | 0.799      | -            | -                | -                | -         |    -9.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1497 | 2024-06-01 | ECLOT           | L   | 0.794      | -            | -                | -                | -         |    -8.99 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1541 | 2024-05-31 | SINNERS         | W   | 0.787      | 0.346        | 0.038 (0.010)    | 0.768 (0.209)    | 1 (0.787) |    15.76 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1545 | 2024-05-31 | Johnny Speeds   | W   | 0.786      | 0.371        | 0.124 (0.036)    | 0.818 (0.238)    | 0 (0.000) |    21.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1590 | 2024-05-29 | Rebels          | W   | 0.773      | 0.371        | 0.040 (0.012)    | 0.635 (0.182)    | 0 (0.000) |    14.87 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1603 | 2024-05-28 | GL Academy      | L   | 0.768      | -            | -                | -                | -         |   -17.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1675 | 2024-05-25 | Serbia          | L   | 0.746      | -            | -                | -                | -         |   -17.02 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1700 | 2024-05-23 | SINNERS         | L   | 0.734      | -            | -                | -                | -         |    -9.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1809 | 2024-05-21 | Rebels          | W   | 0.719      | 0.371        | 0.040 (0.011)    | 0.635 (0.169)    | 0 (0.000) |    13.14 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2115 | 2024-05-13 | Johnny Speeds   | L   | 0.667      | -            | -                | -                | -         |    -2.87 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2731 | 2024-04-18 | Johnny Speeds   | L   | 0.499      | -            | -                | -                | -         |    -2.12 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2779 | 2024-04-17 | Viperio         | W   | 0.492      | -            | -                | -                | 0 (0.000) |     2.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2803 | 2024-04-16 | Lilmix          | W   | 0.486      | -            | -                | -                | -         |     0.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2834 | 2024-04-14 | Sashi           | L   | 0.472      | -            | -                | -                | -         |    -4.01 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2949 | 2024-04-10 | SINNERS         | L   | 0.446      | -            | -                | -                | -         |    -4.82 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3069 | 2024-04-06 | Sashi           | L   | 0.419      | -            | -                | -                | -         |    -3.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3081 | 2024-04-05 | ECLOT           | W   | 0.412      | 0.333        | 0.064 (0.009)    | 0.501 (0.069)    | -         |     8.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3127 | 2024-04-04 | Sashi           | L   | 0.406      | -            | -                | -                | -         |    -3.52 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3213 | 2024-04-02 | Illuminar       | W   | 0.393      | -            | -                | -                | -         |     0.99 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3473 | 2024-03-17 | SINNERS         | L   | 0.287      | -            | -                | -                | -         |    -3.49 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3485 | 2024-03-16 | ECLOT           | L   | 0.281      | -            | -                | -                | -         |    -2.93 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3500 | 2024-03-15 | SINNERS         | W   | 0.275      | 0.345        | 0.038 (0.004)    | 0.768 (0.073)    | 1 (0.275) |     5.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,281.91)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.906 | $3,000.00      | $2,716.67       |
| 2024-06-02 |      0.801 | $3,048.00      | $2,441.65       |
| 2024-04-18 |      0.499 | $3,000.00      | $1,498.33       |
| 2024-04-06 |      0.419 | $3,000.00      | $1,256.67       |
| 2024-03-17 |      0.288 | $1,279.00      | $368.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
