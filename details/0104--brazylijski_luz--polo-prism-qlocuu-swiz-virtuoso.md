### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  845.5<br />
<br />
Final Rank Value (845.5) = Starting Rank Value (792.8) + Head To Head Adjustments (52.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 792.8
- 400 + ( ( 0.192 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 792.8


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
|           29 |      129 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.14 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      399 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.81 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      635 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.017 (0.008)    | 0.386 (0.193)    | 0 (0.000) |    18.66 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      748 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.599 (0.299)    | 0 (0.000) |    22.94 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1482 | 2024-06-04 | The Prodigies     | L   | 0.798      | -            | -                | -                | -         |   -20.44 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1514 | 2024-06-03 | Johnny Speeds     | L   | 0.791      | -            | -                | -                | -         |    -2.22 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1538 | 2024-06-02 | Serbia            | L   | 0.783      | -            | -                | -                | -         |   -13.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1629 | 2024-05-30 | Enterprise        | W   | 0.762      | 0.371        | 0.039 (0.011)    | 0.624 (0.176)    | 0 (0.000) |    14.52 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1648 | 2024-05-29 | SINNERS           | L   | 0.758      | -            | -                | -                | -         |    -5.68 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1697 | 2024-05-27 | Entropiq          | W   | 0.743      | -            | -                | -                | 0 (0.000) |     1.82 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1756 | 2024-05-23 | GL Academy        | W   | 0.719      | 0.379        | 0.007 (0.002)    | 0.101 (0.027)    | 0 (0.000) |     8.85 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1767 | 2024-05-23 | Zero Tenacity     | L   | 0.716      | -            | -                | -                | -         |    -4.00 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2297 | 2024-05-06 | Grannys Knockers  | L   | 0.603      | -            | -                | -                | -         |   -11.45 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2455 | 2024-04-28 | VP.Prodigy        | W   | 0.551      | 0.396        | 0.026 (0.006)    | 0.402 (0.088)    | 0 (0.000) |     9.45 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2463 | 2024-04-28 | Nexus             | W   | 0.550      | 0.396        | 0.014 (0.003)    | 0.465 (0.101)    | 0 (0.000) |     8.82 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2631 | 2024-04-20 | Sangal            | L   | 0.498      | -            | -                | -                | -         |    -2.41 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2665 | 2024-04-19 | Rebels            | W   | 0.492      | 0.500        | 0.038 (0.009)    | 0.599 (0.147)    | 0 (0.000) |    11.23 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2713 | 2024-04-18 | BetBoom           | L   | 0.485      | -            | -                | -                | -         |    -0.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2721 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.485      | 0.143        | 0.223 (0.015)    | 0.553 (0.038)    | 0 (0.000) |    15.12 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2927 | 2024-04-10 | Betera            | W   | 0.432      | -            | -                | -                | 0 (0.000) |     5.15 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     2983 | 2024-04-09 | FORZE             | L   | 0.425      | -            | -                | -                | -         |    -4.32 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3258 | 2024-03-28 | Aurora            | L   | 0.345      | -            | -                | -                | -         |    -0.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3529 | 2024-03-14 | Rebels            | W   | 0.252      | 0.500        | 0.038 (0.005)    | 0.599 (0.076)    | -         |     5.98 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3616 | 2024-03-11 | SINNERS           | W   | 0.232      | 0.500        | 0.037 (0.004)    | 0.758 (0.088)    | -         |     6.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3732 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.199      | -            | -                | -                | -         |    -1.62 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3852 | 2024-03-02 | Sashi             | L   | 0.170      | -            | -                | -                | -         |    -0.64 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3917 | 2024-02-27 | Spirit Academy    | L   | 0.145      | -            | -                | -                | -         |    -3.69 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     3993 | 2024-02-24 | The Chosen Few    | W   | 0.124      | -            | -                | -                | -         |     1.29 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4122 | 2024-02-18 | ARCRED            | W   | 0.085      | -            | -                | -                | -         |     1.60 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,493.96)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
