### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  825.8<br />
<br />
Final Rank Value (825.8) = Starting Rank Value (777.6) + Head To Head Adjustments (48.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.011[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.6
- 400 + ( ( 0.185 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 777.6


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
|           28 |     2759 | 2024-04-15 | Sashi             | L   | 0.465      | -            | -                | -                | -         |    -2.17 | Altekz, Kristou, refrezh, roeJ, TMB |
|           27 |     2787 | 2024-04-13 | 3DMAX             | L   | 0.452      | -            | -                | -                | -         |    -0.16 | Altekz, Kristou, refrezh, roeJ, TMB |
|           26 |     2938 | 2024-04-09 | kONO              | W   | 0.424      | 0.384        | 0.028 (0.005)    | 0.555 (0.091)    | 0 (0.000) |     6.39 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     2992 | 2024-04-07 | Zero Tenacity     | W   | 0.411      | 0.358        | 0.137 (0.020)    | 1.000 (0.147)    | 0 (0.000) |    10.69 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3293 | 2024-03-22 | FORZE             | L   | 0.306      | -            | -                | -                | -         |    -3.56 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3372 | 2024-03-18 | Sampi             | W   | 0.278      | 0.371        | 0.028 (0.003)    | 1.000 (0.103)    | 0 (0.000) |     5.58 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3412 | 2024-03-16 | Passion UA        | W   | 0.266      | 0.371        | 0.172 (0.017)    | 1.000 (0.098)    | 0 (0.000) |     6.87 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3467 | 2024-03-14 | Entropiq          | W   | 0.251      | -            | -                | -                | 0 (0.000) |     1.69 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3538 | 2024-03-11 | Metizport         | L   | 0.234      | -            | -                | -                | -         |    -2.57 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           19 |     3548 | 2024-03-11 | HEROIC            | L   | 0.233      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           18 |     3553 | 2024-03-11 | Permitta          | W   | 0.232      | 0.371        | 0.024 (0.002)    | 0.887 (0.076)    | 0 (0.000) |     5.17 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3603 | 2024-03-09 | Fraud5            | W   | 0.218      | -            | -                | -                | 0 (0.000) |     2.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3646 | 2024-03-07 | Secret            | W   | 0.204      | -            | -                | -                | 0 (0.000) |     1.24 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3739 | 2024-03-03 | Gaimin Gladiators | W   | 0.181      | 0.143        | 0.038 (0.001)    | 0.366 (0.009)    | 0 (0.000) |     4.26 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3745 | 2024-03-03 | BetBoom           | W   | 0.180      | 0.143        | 0.252 (0.006)    | 0.563 (0.015)    | -         |     5.53 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3753 | 2024-03-03 | kONO              | W   | 0.180      | 0.143        | 0.028 (0.001)    | 0.555 (0.014)    | -         |     3.05 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3761 | 2024-03-03 | fnatic            | L   | 0.179      | -            | -                | -                | -         |    -0.22 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3764 | 2024-03-03 | MOUZ NXT          | L   | 0.178      | -            | -                | -                | -         |    -1.08 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3792 | 2024-03-01 | BetBoom           | L   | 0.167      | -            | -                | -                | -         |    -0.14 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3814 | 2024-02-28 | fnatic            | W   | 0.154      | 0.500        | 0.290 (0.022)    | 0.627 (0.048)    | -         |     4.66 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3972 | 2024-02-21 | ex-Guild Eagles   | L   | 0.106      | -            | -                | -                | -         |    -1.51 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     3999 | 2024-02-20 | PERA              | W   | 0.100      | 0.143        | 0.048 (0.001)    | 0.468 (0.007)    | 1 (0.100) |     2.19 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4024 | 2024-02-19 | OG                | L   | 0.094      | -            | -                | -                | -         |    -0.69 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4028 | 2024-02-19 | HEROIC            | L   | 0.093      | -            | -                | -                | -         |    -0.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4250 | 2024-02-09 | Gaimin Gladiators | W   | 0.024      | -            | -                | -                | -         |     0.57 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4264 | 2024-02-08 | TSM               | W   | 0.018      | -            | -                | -                | -         |     0.20 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4270 | 2024-02-07 | Into the Breach   | W   | 0.011      | -            | -                | -                | -         |     0.09 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4279 | 2024-02-06 | Sangal            | W   | 0.005      | -            | -                | -                | -         |     0.15 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,059.76)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.459 | $1,600.00      | $734.30         |
| 2024-03-18 |      0.278 | $11,000.00     | $3,056.06       |
| 2024-02-09 |      0.024 | $11,000.00     | $269.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
