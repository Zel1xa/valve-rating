### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  818.6<br />
<br />
Final Rank Value (818.6) = Starting Rank Value (773.9) + Head To Head Adjustments (44.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.339[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
- LAN Wins: 0.009[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 773.9
- 400 + ( ( 0.182 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 773.9


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
|           25 |     2896 | 2024-04-15 | Sashi             | L   | 0.446      | -            | -                | -                | -         |    -2.06 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     2924 | 2024-04-13 | 3DMAX             | L   | 0.433      | -            | -                | -                | -         |    -0.14 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3075 | 2024-04-09 | kONO              | W   | 0.405      | 0.384        | 0.028 (0.004)    | 0.553 (0.086)    | 0 (0.000) |     6.32 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3129 | 2024-04-07 | Zero Tenacity     | W   | 0.392      | 0.358        | 0.143 (0.020)    | 1.000 (0.141)    | 0 (0.000) |    10.30 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3435 | 2024-03-22 | FORZE             | L   | 0.287      | -            | -                | -                | -         |    -3.29 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3514 | 2024-03-18 | Sampi             | W   | 0.259      | 0.371        | 0.027 (0.003)    | 1.000 (0.096)    | 0 (0.000) |     5.22 | Altekz, Kristou, refrezh, roeJ, TMB |
|           19 |     3554 | 2024-03-16 | Passion UA        | W   | 0.247      | 0.371        | 0.173 (0.016)    | 1.000 (0.091)    | 0 (0.000) |     6.47 | Altekz, Kristou, refrezh, roeJ, TMB |
|           18 |     3610 | 2024-03-14 | Entropiq          | W   | 0.232      | -            | -                | -                | 0 (0.000) |     1.58 | Altekz, Kristou, refrezh, roeJ, TMB |
|           17 |     3683 | 2024-03-11 | Metizport         | L   | 0.215      | -            | -                | -                | -         |    -2.32 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3693 | 2024-03-11 | HEROIC            | L   | 0.214      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3698 | 2024-03-11 | Permitta          | W   | 0.213      | 0.371        | 0.023 (0.002)    | 0.919 (0.072)    | 0 (0.000) |     4.90 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3748 | 2024-03-09 | Fraud5            | W   | 0.199      | -            | -                | -                | 0 (0.000) |     1.95 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3791 | 2024-03-07 | Secret            | W   | 0.185      | -            | -                | -                | 0 (0.000) |     1.15 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3884 | 2024-03-03 | Gaimin Gladiators | W   | 0.162      | 0.143        | 0.037 (0.001)    | 0.331 (0.008)    | 0 (0.000) |     3.78 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3890 | 2024-03-03 | BetBoom           | W   | 0.161      | 0.143        | 0.248 (0.006)    | 0.514 (0.012)    | -         |     4.94 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3898 | 2024-03-03 | kONO              | W   | 0.161      | 0.143        | 0.028 (0.001)    | 0.553 (0.013)    | -         |     2.79 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3906 | 2024-03-03 | fnatic            | L   | 0.160      | -            | -                | -                | -         |    -0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3909 | 2024-03-03 | MOUZ NXT          | L   | 0.159      | -            | -                | -                | -         |    -0.90 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     3937 | 2024-03-01 | BetBoom           | L   | 0.148      | -            | -                | -                | -         |    -0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     3959 | 2024-02-28 | fnatic            | W   | 0.135      | 0.500        | 0.371 (0.025)    | 0.680 (0.046)    | -         |     4.20 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4117 | 2024-02-21 | ex-Guild Eagles   | L   | 0.087      | -            | -                | -                | -         |    -1.23 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4144 | 2024-02-20 | PERA              | W   | 0.081      | 0.143        | 0.047 (0.001)    | 0.435 (0.005)    | 1 (0.081) |     1.79 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4169 | 2024-02-19 | OG                | L   | 0.074      | -            | -                | -                | -         |    -0.53 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4173 | 2024-02-19 | HEROIC            | L   | 0.074      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4396 | 2024-02-09 | Gaimin Gladiators | W   | 0.005      | -            | -                | -                | -         |     0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,610.70)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.440 | $1,600.00      | $703.85         |
| 2024-03-18 |      0.259 | $11,000.00     | $2,846.76       |
| 2024-02-09 |      0.005 | $11,000.00     | $60.09          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
