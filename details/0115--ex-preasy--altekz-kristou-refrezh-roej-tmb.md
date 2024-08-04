### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  826.0<br />
<br />
Final Rank Value (826.0) = Starting Rank Value (778.2) + Head To Head Adjustments (47.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.011[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.2
- 400 + ( ( 0.185 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 778.2


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
|           28 |     2825 | 2024-04-15 | Sashi             | L   | 0.464      | -            | -                | -                | -         |    -2.26 | Altekz, Kristou, refrezh, roeJ, TMB |
|           27 |     2853 | 2024-04-13 | 3DMAX             | L   | 0.451      | -            | -                | -                | -         |    -0.16 | Altekz, Kristou, refrezh, roeJ, TMB |
|           26 |     3004 | 2024-04-09 | kONO              | W   | 0.423      | 0.384        | 0.028 (0.005)    | 0.536 (0.087)    | 0 (0.000) |     6.36 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     3058 | 2024-04-07 | Zero Tenacity     | W   | 0.410      | 0.358        | 0.137 (0.020)    | 1.000 (0.147)    | 0 (0.000) |    10.64 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3364 | 2024-03-22 | FORZE             | L   | 0.304      | -            | -                | -                | -         |    -3.55 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3443 | 2024-03-18 | Sampi             | W   | 0.276      | 0.371        | 0.027 (0.003)    | 1.000 (0.102)    | 0 (0.000) |     5.50 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3483 | 2024-03-16 | Passion UA        | W   | 0.264      | 0.371        | 0.172 (0.017)    | 1.000 (0.098)    | 0 (0.000) |     6.81 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3539 | 2024-03-14 | Entropiq          | W   | 0.249      | -            | -                | -                | 0 (0.000) |     1.67 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3611 | 2024-03-11 | Metizport         | L   | 0.232      | -            | -                | -                | -         |    -2.56 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           19 |     3621 | 2024-03-11 | HEROIC            | L   | 0.231      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           18 |     3626 | 2024-03-11 | Permitta          | W   | 0.230      | 0.371        | 0.024 (0.002)    | 0.876 (0.075)    | 0 (0.000) |     5.12 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3676 | 2024-03-09 | Fraud5            | W   | 0.216      | -            | -                | -                | 0 (0.000) |     2.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3719 | 2024-03-07 | Secret            | W   | 0.203      | -            | -                | -                | 0 (0.000) |     1.23 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3812 | 2024-03-03 | Gaimin Gladiators | W   | 0.179      | 0.143        | 0.038 (0.001)    | 0.353 (0.009)    | 0 (0.000) |     4.19 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3818 | 2024-03-03 | BetBoom           | W   | 0.179      | 0.143        | 0.252 (0.006)    | 0.543 (0.014)    | -         |     5.47 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3826 | 2024-03-03 | kONO              | W   | 0.178      | 0.143        | 0.028 (0.001)    | 0.536 (0.014)    | -         |     3.01 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3834 | 2024-03-03 | fnatic            | L   | 0.177      | -            | -                | -                | -         |    -0.08 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3837 | 2024-03-03 | MOUZ NXT          | L   | 0.176      | -            | -                | -                | -         |    -1.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3865 | 2024-03-01 | BetBoom           | L   | 0.166      | -            | -                | -                | -         |    -0.14 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3887 | 2024-02-28 | fnatic            | W   | 0.152      | 0.500        | 0.371 (0.028)    | 0.709 (0.054)    | -         |     4.73 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     4045 | 2024-02-21 | ex-Guild Eagles   | L   | 0.105      | -            | -                | -                | -         |    -1.49 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     4072 | 2024-02-20 | PERA              | W   | 0.098      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.098) |     2.15 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4097 | 2024-02-19 | OG                | L   | 0.092      | -            | -                | -                | -         |    -0.66 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4101 | 2024-02-19 | HEROIC            | L   | 0.091      | -            | -                | -                | -         |    -0.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4323 | 2024-02-09 | Gaimin Gladiators | W   | 0.023      | -            | -                | -                | -         |     0.53 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4337 | 2024-02-08 | TSM               | W   | 0.016      | -            | -                | -                | -         |     0.18 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4343 | 2024-02-07 | Into the Breach   | W   | 0.009      | -            | -                | -                | -         |     0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4352 | 2024-02-06 | Sangal            | W   | 0.003      | -            | -                | -                | -         |     0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,019.33)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.457 | $1,600.00      | $731.56         |
| 2024-03-18 |      0.276 | $11,000.00     | $3,037.22       |
| 2024-02-09 |      0.023 | $11,000.00     | $250.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
