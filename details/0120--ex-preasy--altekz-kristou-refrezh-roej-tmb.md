### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  818.6<br />
<br />
Final Rank Value (818.6) = Starting Rank Value (773.7) + Head To Head Adjustments (44.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.339[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.009[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 773.7
- 400 + ( ( 0.182 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 773.7


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
|           25 |     2894 | 2024-04-15 | Sashi             | L   | 0.447      | -            | -                | -                | -         |    -2.06 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     2922 | 2024-04-13 | 3DMAX             | L   | 0.434      | -            | -                | -                | -         |    -0.14 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3073 | 2024-04-09 | kONO              | W   | 0.406      | 0.384        | 0.028 (0.004)    | 0.565 (0.088)    | 0 (0.000) |     6.32 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3127 | 2024-04-07 | Zero Tenacity     | W   | 0.393      | 0.358        | 0.143 (0.020)    | 1.000 (0.141)    | 0 (0.000) |    10.34 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3433 | 2024-03-22 | FORZE             | L   | 0.288      | -            | -                | -                | -         |    -3.32 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3512 | 2024-03-18 | Sampi             | W   | 0.260      | 0.371        | 0.027 (0.003)    | 1.000 (0.096)    | 0 (0.000) |     5.25 | Altekz, Kristou, refrezh, roeJ, TMB |
|           19 |     3552 | 2024-03-16 | Passion UA        | W   | 0.247      | 0.371        | 0.173 (0.016)    | 1.000 (0.092)    | 0 (0.000) |     6.49 | Altekz, Kristou, refrezh, roeJ, TMB |
|           18 |     3608 | 2024-03-14 | Entropiq          | W   | 0.233      | -            | -                | -                | 0 (0.000) |     1.58 | Altekz, Kristou, refrezh, roeJ, TMB |
|           17 |     3681 | 2024-03-11 | Metizport         | L   | 0.216      | -            | -                | -                | -         |    -2.33 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3691 | 2024-03-11 | HEROIC            | L   | 0.215      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3696 | 2024-03-11 | Permitta          | W   | 0.214      | 0.371        | 0.023 (0.002)    | 0.940 (0.074)    | 0 (0.000) |     4.92 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3746 | 2024-03-09 | Fraud5            | W   | 0.200      | -            | -                | -                | 0 (0.000) |     1.95 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3789 | 2024-03-07 | Secret            | W   | 0.186      | -            | -                | -                | 0 (0.000) |     1.16 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3882 | 2024-03-03 | Gaimin Gladiators | W   | 0.163      | 0.143        | 0.037 (0.001)    | 0.339 (0.008)    | 0 (0.000) |     3.80 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3888 | 2024-03-03 | BetBoom           | W   | 0.162      | 0.143        | 0.248 (0.006)    | 0.526 (0.012)    | -         |     4.97 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3896 | 2024-03-03 | kONO              | W   | 0.162      | 0.143        | 0.028 (0.001)    | 0.565 (0.013)    | -         |     2.80 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3904 | 2024-03-03 | fnatic            | L   | 0.161      | -            | -                | -                | -         |    -0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3907 | 2024-03-03 | MOUZ NXT          | L   | 0.160      | -            | -                | -                | -         |    -0.90 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     3935 | 2024-03-01 | BetBoom           | L   | 0.149      | -            | -                | -                | -         |    -0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     3957 | 2024-02-28 | fnatic            | W   | 0.136      | 0.500        | 0.371 (0.025)    | 0.695 (0.047)    | -         |     4.22 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4115 | 2024-02-21 | ex-Guild Eagles   | L   | 0.088      | -            | -                | -                | -         |    -1.25 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4142 | 2024-02-20 | PERA              | W   | 0.082      | 0.143        | 0.048 (0.001)    | 0.445 (0.005)    | 1 (0.082) |     1.81 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4167 | 2024-02-19 | OG                | L   | 0.075      | -            | -                | -                | -         |    -0.54 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4171 | 2024-02-19 | HEROIC            | L   | 0.075      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4394 | 2024-02-09 | Gaimin Gladiators | W   | 0.006      | -            | -                | -                | -         |     0.15 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,632.56)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.441 | $1,600.00      | $705.33         |
| 2024-03-18 |      0.260 | $11,000.00     | $2,856.94       |
| 2024-02-09 |      0.006 | $11,000.00     | $70.28          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
