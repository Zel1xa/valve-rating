### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  846.9<br />
<br />
Final Rank Value (846.9) = Starting Rank Value (793.6) + Head To Head Adjustments (53.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.119[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 793.6
- 400 + ( ( 0.192 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 793.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      197 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      469 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.72 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      705 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.026 (0.013)    | 0.379 (0.190)    | 0 (0.000) |    19.05 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      816 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.295)    | 0 (0.000) |    22.95 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1550 | 2024-06-04 | The Prodigies     | L   | 0.781      | -            | -                | -                | -         |   -20.05 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1582 | 2024-06-03 | Johnny Speeds     | L   | 0.775      | -            | -                | -                | -         |    -2.07 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1606 | 2024-06-02 | Serbia            | L   | 0.767      | -            | -                | -                | -         |   -13.50 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1697 | 2024-05-30 | Enterprise        | W   | 0.746      | 0.371        | 0.039 (0.011)    | 0.616 (0.170)    | 0 (0.000) |    14.33 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1716 | 2024-05-29 | SINNERS           | L   | 0.742      | -            | -                | -                | -         |    -4.76 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1765 | 2024-05-27 | Entropiq          | W   | 0.726      | -            | -                | -                | 0 (0.000) |     1.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1824 | 2024-05-23 | GL Academy        | W   | 0.702      | 0.379        | 0.006 (0.002)    | 0.097 (0.026)    | 0 (0.000) |     8.62 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1835 | 2024-05-23 | Zero Tenacity     | L   | 0.699      | -            | -                | -                | -         |    -3.85 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2365 | 2024-05-06 | Grannys Knockers  | L   | 0.586      | -            | -                | -                | -         |   -11.13 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2523 | 2024-04-28 | VP.Prodigy        | W   | 0.535      | 0.396        | 0.025 (0.005)    | 0.392 (0.083)    | 0 (0.000) |     9.21 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2531 | 2024-04-28 | Nexus             | W   | 0.533      | 0.396        | 0.014 (0.003)    | 0.457 (0.097)    | 0 (0.000) |     8.65 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2700 | 2024-04-20 | Sangal            | L   | 0.482      | -            | -                | -                | -         |    -2.24 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2734 | 2024-04-19 | Rebels            | W   | 0.476      | 0.500        | 0.038 (0.009)    | 0.591 (0.141)    | 0 (0.000) |    10.87 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2782 | 2024-04-18 | BetBoom           | L   | 0.469      | -            | -                | -                | -         |    -0.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2790 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.468      | 0.143        | 0.254 (0.017)    | 0.543 (0.036)    | 0 (0.000) |    14.62 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2996 | 2024-04-10 | Betera            | W   | 0.416      | -            | -                | -                | 0 (0.000) |     4.82 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     3052 | 2024-04-09 | FORZE             | L   | 0.409      | -            | -                | -                | -         |    -4.25 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3327 | 2024-03-28 | Aurora            | L   | 0.329      | -            | -                | -                | -         |    -0.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3598 | 2024-03-14 | Rebels            | W   | 0.236      | 0.500        | 0.038 (0.004)    | 0.591 (0.070)    | -         |     5.58 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3686 | 2024-03-11 | SINNERS           | W   | 0.215      | 0.500        | 0.037 (0.004)    | 0.808 (0.087)    | -         |     5.95 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3802 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.182      | -            | -                | -                | -         |    -1.50 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3922 | 2024-03-02 | Sashi             | L   | 0.154      | -            | -                | -                | -         |    -0.57 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3987 | 2024-02-27 | Spirit Academy    | L   | 0.129      | -            | -                | -                | -         |    -3.28 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     4063 | 2024-02-24 | The Chosen Few    | W   | 0.107      | -            | -                | -                | -         |     1.11 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4192 | 2024-02-18 | ARCRED            | W   | 0.068      | -            | -                | -                | -         |     1.42 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,444.79)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
