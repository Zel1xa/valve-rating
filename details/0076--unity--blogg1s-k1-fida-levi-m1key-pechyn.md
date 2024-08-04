### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  938.8<br />
<br />
Final Rank Value (938.8) = Starting Rank Value (958.2) + Head To Head Adjustments (-19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.340[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.207[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 958.2
- 400 + ( ( 0.273 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 958.2


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
|           32 |      499 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.07 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |      531 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -17.55 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      759 | 2024-07-15 | kONO            | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    11.43 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      817 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.032 (0.012)    | 0.561 (0.208)    | 0 (0.000) |    12.52 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      943 | 2024-06-18 | kONO            | L   | 0.889      | -            | -                | -                | -         |   -17.87 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      946 | 2024-06-17 | K10             | W   | 0.883      | -            | -                | -                | 0 (0.000) |     5.24 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |      975 | 2024-06-16 | Verdant         | W   | 0.876      | 0.333        | 0.015 (0.004)    | 0.299 (0.087)    | 0 (0.000) |    10.33 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1518 | 2024-06-03 | Enterprise      | L   | 0.789      | -            | -                | -                | -         |   -14.04 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1527 | 2024-06-02 | ECLOT           | L   | 0.785      | -            | -                | -                | -         |    -6.55 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1533 | 2024-06-02 | SINNERS         | W   | 0.784      | 0.346        | 0.037 (0.010)    | 0.758 (0.205)    | 1 (0.784) |    14.85 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1542 | 2024-06-02 | Passion UA      | L   | 0.782      | -            | -                | -                | -         |    -9.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1559 | 2024-06-01 | ECLOT           | L   | 0.778      | -            | -                | -                | -         |    -6.70 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1602 | 2024-05-31 | SINNERS         | W   | 0.771      | 0.346        | 0.037 (0.010)    | 0.758 (0.202)    | 1 (0.771) |    15.34 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1606 | 2024-05-31 | Johnny Speeds   | W   | 0.769      | 0.371        | 0.122 (0.035)    | 0.901 (0.257)    | 0 (0.000) |    20.59 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1651 | 2024-05-29 | Rebels          | W   | 0.757      | 0.371        | 0.038 (0.011)    | 0.599 (0.168)    | 0 (0.000) |    14.26 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1664 | 2024-05-28 | GL Academy      | L   | 0.752      | -            | -                | -                | -         |   -17.32 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1734 | 2024-05-25 | Serbia          | L   | 0.730      | -            | -                | -                | -         |   -16.79 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1759 | 2024-05-23 | SINNERS         | L   | 0.718      | -            | -                | -                | -         |    -9.06 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1852 | 2024-05-21 | Rebels          | W   | 0.703      | 0.371        | 0.038 (0.010)    | 0.599 (0.156)    | 0 (0.000) |    12.55 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2139 | 2024-05-13 | Johnny Speeds   | L   | 0.651      | -            | -                | -                | -         |    -2.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2741 | 2024-04-18 | Johnny Speeds   | L   | 0.483      | -            | -                | -                | -         |    -2.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2788 | 2024-04-17 | Viperio         | W   | 0.476      | -            | -                | -                | -         |     2.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2811 | 2024-04-16 | Lilmix          | W   | 0.469      | -            | -                | -                | -         |     0.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2842 | 2024-04-14 | Sashi           | L   | 0.456      | -            | -                | -                | -         |    -4.00 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2956 | 2024-04-10 | SINNERS         | L   | 0.429      | -            | -                | -                | -         |    -4.21 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3076 | 2024-04-06 | Sashi           | L   | 0.403      | -            | -                | -                | -         |    -3.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3088 | 2024-04-05 | ECLOT           | W   | 0.396      | 0.333        | 0.063 (0.008)    | 0.559 (0.074)    | -         |     9.88 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3133 | 2024-04-04 | Sashi           | L   | 0.390      | -            | -                | -                | -         |    -3.47 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3212 | 2024-04-02 | Illuminar       | W   | 0.377      | -            | -                | -                | -         |     0.94 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3467 | 2024-03-17 | SINNERS         | L   | 0.271      | -            | -                | -                | -         |    -2.95 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3479 | 2024-03-16 | ECLOT           | L   | 0.265      | -            | -                | -                | -         |    -1.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3494 | 2024-03-15 | SINNERS         | W   | 0.259      | 0.345        | 0.037 (0.003)    | 0.758 (0.068)    | 1 (0.259) |     5.38 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,063.50)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.889 | $3,000.00      | $2,667.50       |
| 2024-06-02 |      0.785 | $3,048.00      | $2,391.69       |
| 2024-04-18 |      0.483 | $3,000.00      | $1,449.17       |
| 2024-04-06 |      0.403 | $3,000.00      | $1,207.50       |
| 2024-03-17 |      0.272 | $1,279.00      | $347.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
