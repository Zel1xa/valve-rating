### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  845.1<br />
<br />
Final Rank Value (845.1) = Starting Rank Value (792.6) + Head To Head Adjustments (52.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 792.6
- 400 + ( ( 0.192 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 792.6


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
|           29 |      132 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.16 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      402 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.81 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      638 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.017 (0.008)    | 0.386 (0.193)    | 0 (0.000) |    18.65 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      751 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.599 (0.300)    | 0 (0.000) |    22.94 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1486 | 2024-06-04 | The Prodigies     | L   | 0.795      | -            | -                | -                | -         |   -20.36 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1518 | 2024-06-03 | Johnny Speeds     | L   | 0.788      | -            | -                | -                | -         |    -2.20 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1542 | 2024-06-02 | Serbia            | L   | 0.780      | -            | -                | -                | -         |   -13.73 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1633 | 2024-05-30 | Enterprise        | W   | 0.759      | 0.371        | 0.039 (0.011)    | 0.625 (0.176)    | 0 (0.000) |    14.46 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1652 | 2024-05-29 | SINNERS           | L   | 0.755      | -            | -                | -                | -         |    -5.65 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1701 | 2024-05-27 | Entropiq          | W   | 0.739      | -            | -                | -                | 0 (0.000) |     1.82 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1760 | 2024-05-23 | GL Academy        | W   | 0.715      | 0.379        | 0.007 (0.002)    | 0.100 (0.027)    | 0 (0.000) |     8.81 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1771 | 2024-05-23 | Zero Tenacity     | L   | 0.713      | -            | -                | -                | -         |    -3.98 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2301 | 2024-05-06 | Grannys Knockers  | L   | 0.599      | -            | -                | -                | -         |   -11.38 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2459 | 2024-04-28 | VP.Prodigy        | W   | 0.548      | 0.396        | 0.026 (0.006)    | 0.401 (0.087)    | 0 (0.000) |     9.40 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2467 | 2024-04-28 | Nexus             | W   | 0.547      | 0.396        | 0.014 (0.003)    | 0.465 (0.101)    | 0 (0.000) |     8.78 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2636 | 2024-04-20 | Sangal            | L   | 0.495      | -            | -                | -                | -         |    -2.38 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2670 | 2024-04-19 | Rebels            | W   | 0.489      | 0.500        | 0.038 (0.009)    | 0.599 (0.146)    | 0 (0.000) |    11.16 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2718 | 2024-04-18 | BetBoom           | L   | 0.482      | -            | -                | -                | -         |    -0.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2726 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.482      | 0.143        | 0.222 (0.015)    | 0.553 (0.038)    | 0 (0.000) |    15.02 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2932 | 2024-04-10 | Betera            | W   | 0.429      | -            | -                | -                | 0 (0.000) |     5.12 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     2988 | 2024-04-09 | FORZE             | L   | 0.422      | -            | -                | -                | -         |    -4.31 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3263 | 2024-03-28 | Aurora            | L   | 0.342      | -            | -                | -                | -         |    -0.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3534 | 2024-03-14 | Rebels            | W   | 0.249      | 0.500        | 0.038 (0.005)    | 0.599 (0.075)    | -         |     5.90 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3622 | 2024-03-11 | SINNERS           | W   | 0.229      | 0.500        | 0.037 (0.004)    | 0.758 (0.087)    | -         |     6.01 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3738 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.196      | -            | -                | -                | -         |    -1.59 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3858 | 2024-03-02 | Sashi             | L   | 0.167      | -            | -                | -                | -         |    -0.63 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3923 | 2024-02-27 | Spirit Academy    | L   | 0.142      | -            | -                | -                | -         |    -3.61 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     3999 | 2024-02-24 | The Chosen Few    | W   | 0.121      | -            | -                | -                | -         |     1.26 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4128 | 2024-02-18 | ARCRED            | W   | 0.082      | -            | -                | -                | -         |     1.55 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,484.79)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
