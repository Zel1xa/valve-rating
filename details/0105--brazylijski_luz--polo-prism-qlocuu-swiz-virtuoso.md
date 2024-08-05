### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  847.1<br />
<br />
Final Rank Value (847.1) = Starting Rank Value (793.9) + Head To Head Adjustments (53.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.120[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 793.9
- 400 + ( ( 0.192 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 793.9


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
|           29 |      190 | 2024-07-31 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -4.09 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           28 |      462 | 2024-07-23 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.75 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           27 |      698 | 2024-07-17 | RUSH B            | W   | 1.000      | 0.500        | 0.026 (0.013)    | 0.380 (0.190)    | 0 (0.000) |    19.04 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           26 |      809 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.296)    | 0 (0.000) |    22.91 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1543 | 2024-06-04 | The Prodigies     | L   | 0.786      | -            | -                | -                | -         |   -20.18 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1575 | 2024-06-03 | Johnny Speeds     | L   | 0.779      | -            | -                | -                | -         |    -2.10 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1599 | 2024-06-02 | Serbia            | L   | 0.772      | -            | -                | -                | -         |   -13.63 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1690 | 2024-05-30 | Enterprise        | W   | 0.751      | 0.371        | 0.039 (0.011)    | 0.616 (0.171)    | 0 (0.000) |    14.34 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1709 | 2024-05-29 | SINNERS           | L   | 0.746      | -            | -                | -                | -         |    -4.82 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1758 | 2024-05-27 | Entropiq          | W   | 0.731      | -            | -                | -                | 0 (0.000) |     1.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     1817 | 2024-05-23 | GL Academy        | W   | 0.707      | 0.379        | 0.006 (0.002)    | 0.098 (0.026)    | 0 (0.000) |     8.67 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     1828 | 2024-05-23 | Zero Tenacity     | L   | 0.704      | -            | -                | -                | -         |    -3.96 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2358 | 2024-05-06 | Grannys Knockers  | L   | 0.591      | -            | -                | -                | -         |   -11.23 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2516 | 2024-04-28 | VP.Prodigy        | W   | 0.539      | 0.396        | 0.025 (0.005)    | 0.393 (0.084)    | 0 (0.000) |     9.25 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2524 | 2024-04-28 | Nexus             | W   | 0.538      | 0.396        | 0.014 (0.003)    | 0.458 (0.098)    | 0 (0.000) |     8.63 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2693 | 2024-04-20 | Sangal            | L   | 0.486      | -            | -                | -                | -         |    -2.29 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2727 | 2024-04-19 | Rebels            | W   | 0.480      | 0.500        | 0.038 (0.009)    | 0.591 (0.142)    | 0 (0.000) |    10.94 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2775 | 2024-04-18 | BetBoom           | L   | 0.473      | -            | -                | -                | -         |    -0.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     2783 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.473      | 0.143        | 0.254 (0.017)    | 0.544 (0.037)    | 0 (0.000) |    14.76 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     2989 | 2024-04-10 | Betera            | W   | 0.420      | -            | -                | -                | 0 (0.000) |     4.87 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     3045 | 2024-04-09 | FORZE             | L   | 0.414      | -            | -                | -                | -         |    -4.28 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3320 | 2024-03-28 | Aurora            | L   | 0.333      | -            | -                | -                | -         |    -0.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3591 | 2024-03-14 | Rebels            | W   | 0.241      | 0.500        | 0.038 (0.005)    | 0.591 (0.071)    | -         |     5.67 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3679 | 2024-03-11 | SINNERS           | W   | 0.220      | 0.500        | 0.037 (0.004)    | 0.809 (0.089)    | -         |     6.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3795 | 2024-03-06 | ALTERNATE aTTaX   | L   | 0.187      | -            | -                | -                | -         |    -1.53 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     3915 | 2024-03-02 | Sashi             | L   | 0.159      | -            | -                | -                | -         |    -0.59 | Furlan, phr, POLO, Prism, Qlocuu    |
|            3 |     3980 | 2024-02-27 | Spirit Academy    | L   | 0.133      | -            | -                | -                | -         |    -3.40 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     4056 | 2024-02-24 | The Chosen Few    | W   | 0.112      | -            | -                | -                | -         |     1.16 | Furlan, phr, POLO, Prism, Qlocuu    |
|            1 |     4185 | 2024-02-18 | ARCRED            | W   | 0.073      | -            | -                | -                | -         |     1.52 | Furlan, phr, POLO, Prism, Qlocuu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,458.96)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
