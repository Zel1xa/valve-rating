### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  847.4<br />
<br />
Final Rank Value (847.4) = Starting Rank Value (794.4) + Head To Head Adjustments (53.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.4
- 400 + ( ( 0.193 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 794.4


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
|           29 |      169 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      441 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      677 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.026 (0.013)    | 0.386 (0.193)    | 0 (0.000) |    19.00 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      788 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.600 (0.300)    | 0 (0.000) |    22.91 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1522 | 2024-06-04 | The Prodigies     | L   | 0.791      | -            | -                | -                | -         |   -20.30 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1554 | 2024-06-03 | Johnny Speeds     | L   | 0.784      | -            | -                | -                | -         |    -2.13 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1578 | 2024-06-02 | Serbia            | L   | 0.776      | -            | -                | -                | -         |   -13.73 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1669 | 2024-05-30 | Enterprise        | W   | 0.755      | 0.371        | 0.039 (0.011)    | 0.625 (0.175)    | 0 (0.000) |    14.35 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1688 | 2024-05-29 | SINNERS           | L   | 0.751      | -            | -                | -                | -         |    -4.95 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1737 | 2024-05-27 | Entropiq          | W   | 0.735      | -            | -                | -                | 0 (0.000) |     1.80 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1796 | 2024-05-23 | GL Academy        | W   | 0.711      | 0.379        | 0.006 (0.002)    | 0.100 (0.027)    | 0 (0.000) |     8.71 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1807 | 2024-05-23 | Zero Tenacity     | L   | 0.709      | -            | -                | -                | -         |    -4.00 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2337 | 2024-05-06 | Grannys Knockers  | L   | 0.595      | -            | -                | -                | -         |   -11.33 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2495 | 2024-04-28 | VP.Prodigy        | W   | 0.544      | 0.396        | 0.025 (0.005)    | 0.400 (0.086)    | 0 (0.000) |     9.31 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2503 | 2024-04-28 | Nexus             | W   | 0.542      | 0.396        | 0.014 (0.003)    | 0.465 (0.100)    | 0 (0.000) |     8.66 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2672 | 2024-04-20 | Sangal            | L   | 0.491      | -            | -                | -                | -         |    -2.33 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2706 | 2024-04-19 | Rebels            | W   | 0.485      | 0.500        | 0.038 (0.009)    | 0.600 (0.145)    | 0 (0.000) |    11.05 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2754 | 2024-04-18 | BetBoom           | L   | 0.478      | -            | -                | -                | -         |    -0.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2762 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.477      | 0.143        | 0.254 (0.017)    | 0.553 (0.038)    | 0 (0.000) |    14.90 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2968 | 2024-04-10 | Betera            | W   | 0.425      | -            | -                | -                | 0 (0.000) |     4.91 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     3024 | 2024-04-09 | FORZE             | L   | 0.418      | -            | -                | -                | -         |    -4.32 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3299 | 2024-03-28 | Aurora            | L   | 0.338      | -            | -                | -                | -         |    -0.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3570 | 2024-03-14 | Rebels            | W   | 0.245      | 0.500        | 0.038 (0.005)    | 0.600 (0.073)    | -         |     5.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3658 | 2024-03-11 | SINNERS           | W   | 0.224      | 0.500        | 0.037 (0.004)    | 0.797 (0.089)    | -         |     6.18 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3774 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.192      | -            | -                | -                | -         |    -1.57 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3894 | 2024-03-02 | Sashi             | L   | 0.163      | -            | -                | -                | -         |    -0.61 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3959 | 2024-02-27 | Spirit Academy    | L   | 0.138      | -            | -                | -                | -         |    -3.51 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     4035 | 2024-02-24 | The Chosen Few    | W   | 0.117      | -            | -                | -                | -         |     1.21 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4164 | 2024-02-18 | ARCRED            | W   | 0.077      | -            | -                | -                | -         |     1.46 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,472.29)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
