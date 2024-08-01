### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  835.7<br />
<br />
Final Rank Value (835.7) = Starting Rank Value (784.8) + Head To Head Adjustments (50.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 784.8
- 400 + ( ( 0.187 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 784.8


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
|           29 |     2823 | 2024-04-15 | Sashi             | L   | 0.478      | -            | -                | -                | -         |    -2.38 | Altekz, Kristou, refrezh, roeJ, TMB |
|           28 |     2851 | 2024-04-13 | 3DMAX             | L   | 0.465      | -            | -                | -                | -         |    -0.17 | Altekz, Kristou, refrezh, roeJ, TMB |
|           27 |     3003 | 2024-04-09 | kONO              | W   | 0.438      | 0.384        | 0.029 (0.005)    | 0.547 (0.092)    | 0 (0.000) |     6.56 | Altekz, Kristou, refrezh, roeJ, TMB |
|           26 |     3057 | 2024-04-07 | Zero Tenacity     | W   | 0.424      | 0.358        | 0.139 (0.021)    | 1.000 (0.152)    | 0 (0.000) |    10.90 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     3376 | 2024-03-22 | FORZE             | L   | 0.319      | -            | -                | -                | -         |    -3.73 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3455 | 2024-03-18 | Sampi             | W   | 0.291      | 0.371        | 0.028 (0.003)    | 1.000 (0.108)    | 0 (0.000) |     5.75 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3495 | 2024-03-16 | Passion UA        | W   | 0.279      | 0.371        | 0.173 (0.018)    | 1.000 (0.103)    | 0 (0.000) |     7.20 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3555 | 2024-03-14 | Entropiq          | W   | 0.264      | -            | -                | -                | 0 (0.000) |     1.74 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3629 | 2024-03-11 | Metizport         | L   | 0.247      | -            | -                | -                | -         |    -2.80 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           20 |     3639 | 2024-03-11 | HEROIC            | L   | 0.246      | -            | -                | -                | -         |    -0.11 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           19 |     3644 | 2024-03-11 | Permitta          | W   | 0.245      | 0.371        | 0.024 (0.002)    | 0.801 (0.073)    | 0 (0.000) |     5.29 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           18 |     3695 | 2024-03-09 | Fraud5            | W   | 0.231      | -            | -                | -                | 0 (0.000) |     2.17 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3738 | 2024-03-07 | Secret            | W   | 0.217      | -            | -                | -                | 0 (0.000) |     1.27 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3836 | 2024-03-03 | Gaimin Gladiators | W   | 0.194      | 0.143        | 0.040 (0.001)    | 0.360 (0.010)    | 0 (0.000) |     4.59 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3842 | 2024-03-03 | BetBoom           | W   | 0.193      | 0.143        | 0.257 (0.007)    | 0.551 (0.015)    | -         |     5.93 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3850 | 2024-03-03 | kONO              | W   | 0.193      | 0.143        | 0.029 (0.001)    | 0.547 (0.015)    | -         |     3.27 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3858 | 2024-03-03 | fnatic            | L   | 0.192      | -            | -                | -                | -         |    -0.24 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3861 | 2024-03-03 | MOUZ NXT          | L   | 0.191      | -            | -                | -                | -         |    -1.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3890 | 2024-03-01 | BetBoom           | L   | 0.180      | -            | -                | -                | -         |    -0.15 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3912 | 2024-02-28 | fnatic            | W   | 0.167      | 0.500        | 0.292 (0.024)    | 0.568 (0.047)    | -         |     5.06 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     4079 | 2024-02-21 | ex-Guild Eagles   | L   | 0.119      | -            | -                | -                | -         |    -1.70 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     4106 | 2024-02-20 | PERA              | W   | 0.113      | 0.143        | -                | 0.452 (0.007)    | 1 (0.113) |     2.45 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     4131 | 2024-02-19 | OG                | L   | 0.107      | -            | -                | -                | -         |    -0.79 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4135 | 2024-02-19 | HEROIC            | L   | 0.106      | -            | -                | -                | -         |    -0.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4368 | 2024-02-09 | Gaimin Gladiators | W   | 0.037      | -            | -                | -                | -         |     0.88 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4382 | 2024-02-08 | TSM               | W   | 0.031      | -            | -                | -                | -         |     0.34 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4388 | 2024-02-07 | Into the Breach   | W   | 0.024      | -            | -                | -                | -         |     0.20 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4397 | 2024-02-06 | Sangal            | W   | 0.018      | 0.371        | 0.221 (0.001)    | -                | -         |     0.51 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4408 | 2024-02-05 | Gaimin Gladiators | L   | 0.011      | -            | -                | -                | -         |    -0.09 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,366.78)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.472 | $1,600.00      | $755.11         |
| 2024-03-18 |      0.291 | $11,000.00     | $3,199.17       |
| 2024-02-09 |      0.037 | $11,000.00     | $412.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
