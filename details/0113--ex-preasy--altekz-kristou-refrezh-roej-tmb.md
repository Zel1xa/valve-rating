### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.0<br />
<br />
Final Rank Value (837.0) = Starting Rank Value (785.7) + Head To Head Adjustments (51.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 785.7
- 400 + ( ( 0.187 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 785.7


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
|           29 |     2817 | 2024-04-15 | Sashi             | L   | 0.480      | -            | -                | -                | -         |    -2.39 | Altekz, Kristou, refrezh, roeJ, TMB |
|           28 |     2845 | 2024-04-13 | 3DMAX             | L   | 0.467      | -            | -                | -                | -         |    -0.17 | Altekz, Kristou, refrezh, roeJ, TMB |
|           27 |     2997 | 2024-04-09 | kONO              | W   | 0.439      | 0.384        | 0.029 (0.005)    | 0.547 (0.092)    | 0 (0.000) |     6.58 | Altekz, Kristou, refrezh, roeJ, TMB |
|           26 |     3051 | 2024-04-07 | Zero Tenacity     | W   | 0.426      | 0.358        | 0.139 (0.021)    | 1.000 (0.153)    | 0 (0.000) |    10.93 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     3370 | 2024-03-22 | FORZE             | L   | 0.320      | -            | -                | -                | -         |    -3.75 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3449 | 2024-03-18 | Sampi             | W   | 0.292      | 0.371        | 0.028 (0.003)    | 1.000 (0.108)    | 0 (0.000) |     5.78 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3489 | 2024-03-16 | Passion UA        | W   | 0.280      | 0.371        | 0.172 (0.018)    | 1.000 (0.104)    | 0 (0.000) |     7.24 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3549 | 2024-03-14 | Entropiq          | W   | 0.266      | -            | -                | -                | 0 (0.000) |     1.74 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3623 | 2024-03-11 | Metizport         | L   | 0.248      | -            | -                | -                | -         |    -2.83 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           20 |     3633 | 2024-03-11 | HEROIC            | L   | 0.247      | -            | -                | -                | -         |    -0.11 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           19 |     3638 | 2024-03-11 | Permitta          | W   | 0.247      | 0.371        | 0.024 (0.002)    | 0.801 (0.073)    | 0 (0.000) |     5.35 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           18 |     3689 | 2024-03-09 | Fraud5            | W   | 0.233      | -            | -                | -                | 0 (0.000) |     2.18 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3732 | 2024-03-07 | Secret            | W   | 0.219      | -            | -                | -                | 0 (0.000) |     1.28 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3830 | 2024-03-03 | Gaimin Gladiators | W   | 0.195      | 0.143        | 0.040 (0.001)    | 0.361 (0.010)    | 0 (0.000) |     4.63 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3836 | 2024-03-03 | BetBoom           | W   | 0.195      | 0.143        | 0.257 (0.007)    | 0.551 (0.015)    | -         |     5.98 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3844 | 2024-03-03 | kONO              | W   | 0.195      | 0.143        | 0.029 (0.001)    | 0.547 (0.015)    | -         |     3.30 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3852 | 2024-03-03 | fnatic            | L   | 0.194      | -            | -                | -                | -         |    -0.24 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3855 | 2024-03-03 | MOUZ NXT          | L   | 0.193      | -            | -                | -                | -         |    -1.08 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3884 | 2024-03-01 | BetBoom           | L   | 0.182      | -            | -                | -                | -         |    -0.15 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3906 | 2024-02-28 | fnatic            | W   | 0.169      | 0.500        | 0.292 (0.025)    | 0.529 (0.045)    | -         |     5.11 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     4073 | 2024-02-21 | ex-Guild Eagles   | L   | 0.121      | -            | -                | -                | -         |    -1.72 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     4100 | 2024-02-20 | PERA              | W   | 0.115      | 0.143        | -                | 0.452 (0.007)    | 1 (0.115) |     2.48 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     4125 | 2024-02-19 | OG                | L   | 0.108      | -            | -                | -                | -         |    -0.80 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4129 | 2024-02-19 | HEROIC            | L   | 0.107      | -            | -                | -                | -         |    -0.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4362 | 2024-02-09 | Gaimin Gladiators | W   | 0.039      | -            | -                | -                | -         |     0.93 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4376 | 2024-02-08 | TSM               | W   | 0.033      | -            | -                | -                | -         |     0.36 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4382 | 2024-02-07 | Into the Breach   | W   | 0.026      | -            | -                | -                | -         |     0.21 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4391 | 2024-02-06 | Sangal            | W   | 0.020      | 0.371        | 0.221 (0.002)    | -                | -         |     0.55 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4402 | 2024-02-05 | Gaimin Gladiators | L   | 0.013      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,406.11)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.474 | $1,600.00      | $757.78         |
| 2024-03-18 |      0.292 | $11,000.00     | $3,217.50       |
| 2024-02-09 |      0.039 | $11,000.00     | $430.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
