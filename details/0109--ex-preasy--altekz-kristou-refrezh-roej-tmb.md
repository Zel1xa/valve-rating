### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [109](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  841.7<br />
<br />
Final Rank Value (841.7) = Starting Rank Value (789.8) + Head To Head Adjustments (51.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.014[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.8
- 400 + ( ( 0.189 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 789.8


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
|           29 |     2713 | 2024-04-15 | Sashi             | L   | 0.484      | -            | -                | -                | -         |    -2.46 | Altekz, Kristou, refrezh, roeJ, TMB |
|           28 |     2741 | 2024-04-13 | 3DMAX             | L   | 0.471      | -            | -                | -                | -         |    -0.17 | Altekz, Kristou, refrezh, roeJ, TMB |
|           27 |     2892 | 2024-04-09 | kONO              | W   | 0.444      | 0.384        | 0.029 (0.005)    | 0.537 (0.092)    | 0 (0.000) |     6.46 | Altekz, Kristou, refrezh, roeJ, TMB |
|           26 |     2946 | 2024-04-07 | Zero Tenacity     | W   | 0.430      | 0.358        | 0.138 (0.021)    | 1.000 (0.154)    | 0 (0.000) |    11.04 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     3252 | 2024-03-22 | FORZE             | L   | 0.325      | -            | -                | -                | -         |    -3.82 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3331 | 2024-03-18 | Sampi             | W   | 0.297      | 0.371        | 0.028 (0.003)    | 1.000 (0.110)    | 0 (0.000) |     5.79 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3371 | 2024-03-16 | Passion UA        | W   | 0.285      | 0.371        | 0.171 (0.018)    | 1.000 (0.105)    | 0 (0.000) |     7.24 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3427 | 2024-03-14 | Entropiq          | W   | 0.270      | -            | -                | -                | 0 (0.000) |     1.74 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3500 | 2024-03-11 | Metizport         | L   | 0.253      | -            | -                | -                | -         |    -2.86 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           20 |     3510 | 2024-03-11 | HEROIC            | L   | 0.252      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           19 |     3515 | 2024-03-11 | Permitta          | W   | 0.251      | 0.371        | 0.024 (0.002)    | 0.799 (0.074)    | 0 (0.000) |     5.32 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           18 |     3565 | 2024-03-09 | Fraud5            | W   | 0.237      | -            | -                | -                | 0 (0.000) |     2.19 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3608 | 2024-03-07 | Secret            | W   | 0.224      | -            | -                | -                | 0 (0.000) |     1.28 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3701 | 2024-03-03 | Gaimin Gladiators | W   | 0.200      | 0.143        | 0.040 (0.001)    | 0.363 (0.010)    | 0 (0.000) |     4.72 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3707 | 2024-03-03 | BetBoom           | W   | 0.199      | 0.143        | 0.256 (0.007)    | 0.554 (0.016)    | -         |     6.11 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3715 | 2024-03-03 | kONO              | W   | 0.199      | 0.143        | -                | 0.537 (0.015)    | -         |     3.29 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3723 | 2024-03-03 | fnatic            | L   | 0.198      | -            | -                | -                | -         |    -0.08 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3726 | 2024-03-03 | MOUZ NXT          | L   | 0.197      | -            | -                | -                | -         |    -1.19 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3754 | 2024-03-01 | BetBoom           | L   | 0.186      | -            | -                | -                | -         |    -0.15 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3776 | 2024-02-28 | fnatic            | W   | 0.173      | 0.500        | 0.371 (0.032)    | 0.633 (0.055)    | -         |     5.38 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3934 | 2024-02-21 | ex-Guild Eagles   | L   | 0.125      | -            | -                | -                | -         |    -1.80 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3961 | 2024-02-20 | PERA              | W   | 0.119      | 0.143        | 0.048 (0.001)    | 0.452 (0.008)    | 1 (0.119) |     2.58 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     3986 | 2024-02-19 | OG                | L   | 0.113      | -            | -                | -                | -         |    -0.80 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     3990 | 2024-02-19 | HEROIC            | L   | 0.112      | -            | -                | -                | -         |    -0.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4213 | 2024-02-09 | Gaimin Gladiators | W   | 0.044      | -            | -                | -                | -         |     1.02 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4227 | 2024-02-08 | TSM               | W   | 0.037      | -            | -                | -                | -         |     0.40 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4233 | 2024-02-07 | Into the Breach   | W   | 0.030      | -            | -                | -                | -         |     0.25 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4242 | 2024-02-06 | Sangal            | W   | 0.024      | 0.371        | 0.219 (0.002)    | -                | -         |     0.67 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4253 | 2024-02-05 | Gaimin Gladiators | L   | 0.017      | -            | -                | -                | -         |    -0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,508.49)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.478 | $1,600.00      | $764.72         |
| 2024-03-18 |      0.297 | $11,000.00     | $3,265.22       |
| 2024-02-09 |      0.044 | $11,000.00     | $478.55         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
