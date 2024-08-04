### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  847.8<br />
<br />
Final Rank Value (847.8) = Starting Rank Value (794.6) + Head To Head Adjustments (53.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.6
- 400 + ( ( 0.193 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 794.6


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
|           29 |      164 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      437 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      673 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.026 (0.013)    | 0.386 (0.193)    | 0 (0.000) |    19.00 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      784 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.600 (0.300)    | 0 (0.000) |    22.91 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1518 | 2024-06-04 | The Prodigies     | L   | 0.793      | -            | -                | -                | -         |   -20.36 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1550 | 2024-06-03 | Johnny Speeds     | L   | 0.786      | -            | -                | -                | -         |    -2.14 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1574 | 2024-06-02 | Serbia            | L   | 0.778      | -            | -                | -                | -         |   -13.78 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1665 | 2024-05-30 | Enterprise        | W   | 0.758      | 0.371        | 0.039 (0.011)    | 0.625 (0.175)    | 0 (0.000) |    14.39 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1684 | 2024-05-29 | SINNERS           | L   | 0.753      | -            | -                | -                | -         |    -4.97 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1733 | 2024-05-27 | Entropiq          | W   | 0.738      | -            | -                | -                | 0 (0.000) |     1.80 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1792 | 2024-05-23 | GL Academy        | W   | 0.714      | 0.379        | 0.007 (0.002)    | 0.100 (0.027)    | 0 (0.000) |     8.73 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1803 | 2024-05-23 | Zero Tenacity     | L   | 0.711      | -            | -                | -                | -         |    -4.02 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2333 | 2024-05-06 | Grannys Knockers  | L   | 0.598      | -            | -                | -                | -         |   -11.38 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2491 | 2024-04-28 | VP.Prodigy        | W   | 0.546      | 0.396        | 0.025 (0.006)    | 0.401 (0.087)    | 0 (0.000) |     9.34 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2499 | 2024-04-28 | Nexus             | W   | 0.545      | 0.396        | 0.014 (0.003)    | 0.465 (0.100)    | 0 (0.000) |     8.70 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2668 | 2024-04-20 | Sangal            | L   | 0.493      | -            | -                | -                | -         |    -2.35 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2702 | 2024-04-19 | Rebels            | W   | 0.487      | 0.500        | 0.038 (0.009)    | 0.600 (0.146)    | 0 (0.000) |    11.11 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2750 | 2024-04-18 | BetBoom           | L   | 0.480      | -            | -                | -                | -         |    -0.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2758 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.480      | 0.143        | 0.254 (0.017)    | 0.553 (0.038)    | 0 (0.000) |    14.97 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2964 | 2024-04-10 | Betera            | W   | 0.427      | -            | -                | -                | 0 (0.000) |     5.06 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     3020 | 2024-04-09 | FORZE             | L   | 0.420      | -            | -                | -                | -         |    -4.34 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3295 | 2024-03-28 | Aurora            | L   | 0.340      | -            | -                | -                | -         |    -0.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3566 | 2024-03-14 | Rebels            | W   | 0.247      | 0.500        | 0.038 (0.005)    | 0.600 (0.074)    | -         |     5.84 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3654 | 2024-03-11 | SINNERS           | W   | 0.227      | 0.500        | 0.037 (0.004)    | 0.797 (0.090)    | -         |     6.24 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3770 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.194      | -            | -                | -                | -         |    -1.59 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3890 | 2024-03-02 | Sashi             | L   | 0.166      | -            | -                | -                | -         |    -0.62 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3955 | 2024-02-27 | Spirit Academy    | L   | 0.140      | -            | -                | -                | -         |    -3.57 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     4031 | 2024-02-24 | The Chosen Few    | W   | 0.119      | -            | -                | -                | -         |     1.23 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4160 | 2024-02-18 | ARCRED            | W   | 0.080      | -            | -                | -                | -         |     1.51 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,479.44)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
