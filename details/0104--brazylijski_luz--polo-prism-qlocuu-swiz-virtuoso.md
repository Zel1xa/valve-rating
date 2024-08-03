### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  846.0<br />
<br />
Final Rank Value (846.0) = Starting Rank Value (794.0) + Head To Head Adjustments (52.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.125[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.0
- 400 + ( ( 0.193 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 794.0


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
|           29 |      107 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.31 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      379 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.42 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      614 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.017 (0.008)    | 0.399 (0.199)    | 0 (0.000) |    18.58 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      723 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.605 (0.303)    | 0 (0.000) |    23.13 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1421 | 2024-06-04 | The Prodigies     | L   | 0.799      | -            | -                | -                | -         |   -20.51 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1453 | 2024-06-03 | Johnny Speeds     | L   | 0.793      | -            | -                | -                | -         |    -2.22 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1476 | 2024-06-02 | Serbia            | L   | 0.785      | -            | -                | -                | -         |   -13.83 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1566 | 2024-05-30 | Enterprise        | W   | 0.764      | 0.371        | 0.039 (0.011)    | 0.646 (0.183)    | 0 (0.000) |    14.56 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1584 | 2024-05-29 | SINNERS           | L   | 0.760      | -            | -                | -                | -         |    -5.66 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1634 | 2024-05-27 | Entropiq          | W   | 0.744      | -            | -                | -                | 0 (0.000) |     1.81 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1692 | 2024-05-23 | GL Academy        | W   | 0.720      | 0.379        | 0.007 (0.002)    | 0.104 (0.028)    | 0 (0.000) |     8.85 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1703 | 2024-05-23 | Zero Tenacity     | L   | 0.718      | -            | -                | -                | -         |    -4.07 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2231 | 2024-05-06 | Grannys Knockers  | L   | 0.604      | -            | -                | -                | -         |   -11.49 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2389 | 2024-04-28 | VP.Prodigy        | W   | 0.553      | 0.396        | 0.026 (0.006)    | 0.416 (0.091)    | 0 (0.000) |     9.48 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2397 | 2024-04-28 | Nexus             | W   | 0.551      | 0.396        | 0.014 (0.003)    | 0.441 (0.096)    | 0 (0.000) |     8.89 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2565 | 2024-04-20 | Sangal            | L   | 0.500      | -            | -                | -                | -         |    -2.45 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2599 | 2024-04-19 | Rebels            | W   | 0.494      | 0.500        | 0.038 (0.009)    | 0.605 (0.149)    | 0 (0.000) |    11.21 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2647 | 2024-04-18 | BetBoom           | L   | 0.487      | -            | -                | -                | -         |    -0.54 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2655 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.486      | 0.143        | 0.204 (0.014)    | 0.502 (0.035)    | 0 (0.000) |    15.11 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2861 | 2024-04-10 | Betera            | W   | 0.434      | -            | -                | -                | 0 (0.000) |     5.16 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     2917 | 2024-04-09 | FORZE             | L   | 0.427      | -            | -                | -                | -         |    -4.36 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3192 | 2024-03-28 | Aurora            | L   | 0.347      | -            | -                | -                | -         |    -0.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3457 | 2024-03-14 | Rebels            | W   | 0.254      | 0.500        | 0.038 (0.005)    | 0.605 (0.077)    | -         |     6.04 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3543 | 2024-03-11 | SINNERS           | W   | 0.233      | 0.500        | 0.037 (0.004)    | 0.784 (0.091)    | -         |     6.15 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3659 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.201      | -            | -                | -                | -         |    -1.63 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3779 | 2024-03-02 | Sashi             | L   | 0.172      | -            | -                | -                | -         |    -0.64 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3844 | 2024-02-27 | Spirit Academy    | L   | 0.147      | -            | -                | -                | -         |    -3.73 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     3920 | 2024-02-24 | The Chosen Few    | W   | 0.126      | -            | -                | -                | -         |     1.30 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4049 | 2024-02-18 | ARCRED            | W   | 0.086      | -            | -                | -                | -         |     1.64 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,499.10)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
