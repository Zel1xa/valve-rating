### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  847.0<br />
<br />
Final Rank Value (847.0) = Starting Rank Value (794.1) + Head To Head Adjustments (52.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.1
- 400 + ( ( 0.192 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 794.1


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
|           29 |      181 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      454 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.76 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      690 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.026 (0.013)    | 0.385 (0.192)    | 0 (0.000) |    19.01 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      801 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.598 (0.299)    | 0 (0.000) |    22.92 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1535 | 2024-06-04 | The Prodigies     | L   | 0.787      | -            | -                | -                | -         |   -20.20 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1567 | 2024-06-03 | Johnny Speeds     | L   | 0.780      | -            | -                | -                | -         |    -2.10 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1591 | 2024-06-02 | Serbia            | L   | 0.773      | -            | -                | -                | -         |   -13.65 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1682 | 2024-05-30 | Enterprise        | W   | 0.752      | 0.371        | 0.039 (0.011)    | 0.624 (0.174)    | 0 (0.000) |    14.30 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1701 | 2024-05-29 | SINNERS           | L   | 0.748      | -            | -                | -                | -         |    -4.91 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1750 | 2024-05-27 | Entropiq          | W   | 0.732      | -            | -                | -                | 0 (0.000) |     1.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1809 | 2024-05-23 | GL Academy        | W   | 0.708      | 0.379        | 0.006 (0.002)    | 0.099 (0.027)    | 0 (0.000) |     8.68 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1820 | 2024-05-23 | Zero Tenacity     | L   | 0.705      | -            | -                | -                | -         |    -3.96 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2350 | 2024-05-06 | Grannys Knockers  | L   | 0.592      | -            | -                | -                | -         |   -11.26 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2508 | 2024-04-28 | VP.Prodigy        | W   | 0.541      | 0.396        | 0.025 (0.005)    | 0.398 (0.085)    | 0 (0.000) |     9.27 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2516 | 2024-04-28 | Nexus             | W   | 0.539      | 0.396        | 0.014 (0.003)    | 0.464 (0.099)    | 0 (0.000) |     8.64 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2685 | 2024-04-20 | Sangal            | L   | 0.487      | -            | -                | -                | -         |    -2.31 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2719 | 2024-04-19 | Rebels            | W   | 0.481      | 0.500        | 0.038 (0.009)    | 0.598 (0.144)    | 0 (0.000) |    10.98 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2767 | 2024-04-18 | BetBoom           | L   | 0.475      | -            | -                | -                | -         |    -0.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2775 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.474      | 0.143        | 0.254 (0.017)    | 0.551 (0.037)    | 0 (0.000) |    14.80 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2981 | 2024-04-10 | Betera            | W   | 0.421      | -            | -                | -                | 0 (0.000) |     4.88 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     3037 | 2024-04-09 | FORZE             | L   | 0.415      | -            | -                | -                | -         |    -4.29 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3312 | 2024-03-28 | Aurora            | L   | 0.334      | -            | -                | -                | -         |    -0.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3583 | 2024-03-14 | Rebels            | W   | 0.242      | 0.500        | 0.038 (0.005)    | 0.598 (0.072)    | -         |     5.71 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3671 | 2024-03-11 | SINNERS           | W   | 0.221      | 0.500        | 0.037 (0.004)    | 0.794 (0.088)    | -         |     6.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3787 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.188      | -            | -                | -                | -         |    -1.55 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3907 | 2024-03-02 | Sashi             | L   | 0.160      | -            | -                | -                | -         |    -0.60 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3972 | 2024-02-27 | Spirit Academy    | L   | 0.134      | -            | -                | -                | -         |    -3.43 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     4048 | 2024-02-24 | The Chosen Few    | W   | 0.113      | -            | -                | -                | -         |     1.17 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4177 | 2024-02-18 | ARCRED            | W   | 0.074      | -            | -                | -                | -         |     1.40 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,462.29)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
