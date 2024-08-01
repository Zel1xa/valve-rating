### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  924.8<br />
<br />
Final Rank Value (924.8) = Starting Rank Value (958.7) + Head To Head Adjustments (-33.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.214[<sup>2</sup>](#table1)

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
|           31 |      421 | 2024-07-20 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -14.47 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |      455 | 2024-07-19 | Enterprise      | L   | 1.000      | -            | -                | -                | -         |   -16.38 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |      754 | 2024-07-11 | ALTERNATE aTTaX | W   | 1.000      | 0.371        | 0.032 (0.012)    | 0.563 (0.209)    | 0 (0.000) |    11.72 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |      881 | 2024-06-18 | kONO            | L   | 0.904      | -            | -                | -                | -         |   -17.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |      884 | 2024-06-17 | K10             | W   | 0.898      | 0.333        | 0.008 (0.002)    | 0.133 (0.040)    | 0 (0.000) |     5.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |      910 | 2024-06-16 | Verdant         | W   | 0.891      | 0.333        | 0.015 (0.004)    | 0.305 (0.090)    | 0 (0.000) |    10.89 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     1460 | 2024-06-03 | Enterprise      | L   | 0.804      | -            | -                | -                | -         |   -14.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     1470 | 2024-06-02 | ECLOT           | L   | 0.800      | -            | -                | -                | -         |    -8.68 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     1476 | 2024-06-02 | SINNERS         | W   | 0.799      | 0.346        | 0.038 (0.011)    | 0.768 (0.212)    | 1 (0.799) |    15.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     1485 | 2024-06-02 | Passion UA      | L   | 0.797      | -            | -                | -                | -         |    -9.14 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     1501 | 2024-06-01 | ECLOT           | L   | 0.793      | -            | -                | -                | -         |    -8.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     1545 | 2024-05-31 | SINNERS         | W   | 0.786      | 0.346        | 0.038 (0.010)    | 0.768 (0.209)    | 1 (0.786) |    15.73 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     1549 | 2024-05-31 | Johnny Speeds   | W   | 0.784      | 0.371        | 0.124 (0.036)    | 0.819 (0.238)    | 0 (0.000) |    21.12 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     1594 | 2024-05-29 | Rebels          | W   | 0.772      | 0.371        | 0.040 (0.012)    | 0.635 (0.182)    | 0 (0.000) |    14.84 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     1607 | 2024-05-28 | GL Academy      | L   | 0.767      | -            | -                | -                | -         |   -17.47 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     1679 | 2024-05-25 | Serbia          | L   | 0.745      | -            | -                | -                | -         |   -16.98 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     1704 | 2024-05-23 | SINNERS         | L   | 0.733      | -            | -                | -                | -         |    -9.16 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     1813 | 2024-05-21 | Rebels          | W   | 0.718      | 0.371        | 0.040 (0.011)    | 0.635 (0.169)    | 0 (0.000) |    13.11 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     2119 | 2024-05-13 | Johnny Speeds   | L   | 0.666      | -            | -                | -                | -         |    -2.87 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     2735 | 2024-04-18 | Johnny Speeds   | L   | 0.498      | -            | -                | -                | -         |    -2.12 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     2783 | 2024-04-17 | Viperio         | W   | 0.491      | -            | -                | -                | 0 (0.000) |     2.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     2807 | 2024-04-16 | Lilmix          | W   | 0.484      | -            | -                | -                | -         |     0.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     2838 | 2024-04-14 | Sashi           | L   | 0.471      | -            | -                | -                | -         |    -3.99 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     2953 | 2024-04-10 | SINNERS         | L   | 0.444      | -            | -                | -                | -         |    -4.81 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     3073 | 2024-04-06 | Sashi           | L   | 0.417      | -            | -                | -                | -         |    -3.65 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     3085 | 2024-04-05 | ECLOT           | W   | 0.411      | 0.333        | 0.064 (0.009)    | 0.501 (0.069)    | -         |     8.91 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     3131 | 2024-04-04 | Sashi           | L   | 0.405      | -            | -                | -                | -         |    -3.51 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     3217 | 2024-04-02 | Illuminar       | W   | 0.392      | -            | -                | -                | -         |     0.99 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     3477 | 2024-03-17 | SINNERS         | L   | 0.286      | -            | -                | -                | -         |    -3.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     3489 | 2024-03-16 | ECLOT           | L   | 0.280      | -            | -                | -                | -         |    -2.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     3504 | 2024-03-15 | SINNERS         | W   | 0.274      | 0.345        | 0.038 (0.004)    | 0.768 (0.072)    | 1 (0.274) |     5.32 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,263.40)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.904 | $3,000.00      | $2,712.50       |
| 2024-06-02 |      0.800 | $3,048.00      | $2,437.41       |
| 2024-04-18 |      0.498 | $3,000.00      | $1,494.17       |
| 2024-04-06 |      0.417 | $3,000.00      | $1,252.50       |
| 2024-03-17 |      0.287 | $1,279.00      | $366.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
