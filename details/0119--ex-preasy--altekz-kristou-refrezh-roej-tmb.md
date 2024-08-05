### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  820.1<br />
<br />
Final Rank Value (820.1) = Starting Rank Value (774.9) + Head To Head Adjustments (45.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.9
- 400 + ( ( 0.183 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 774.9


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
|           26 |     2879 | 2024-04-15 | Sashi             | L   | 0.453      | -            | -                | -                | -         |    -2.11 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     2907 | 2024-04-13 | 3DMAX             | L   | 0.440      | -            | -                | -                | -         |    -0.15 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3058 | 2024-04-09 | kONO              | W   | 0.412      | 0.384        | 0.028 (0.004)    | 0.574 (0.091)    | 0 (0.000) |     6.30 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3112 | 2024-04-07 | Zero Tenacity     | W   | 0.399      | 0.358        | 0.137 (0.020)    | 1.000 (0.143)    | 0 (0.000) |    10.45 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3418 | 2024-03-22 | FORZE             | L   | 0.293      | -            | -                | -                | -         |    -3.39 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3497 | 2024-03-18 | Sampi             | W   | 0.266      | 0.371        | 0.027 (0.003)    | 1.000 (0.098)    | 0 (0.000) |     5.35 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3537 | 2024-03-16 | Passion UA        | W   | 0.253      | 0.371        | 0.173 (0.016)    | 1.000 (0.094)    | 0 (0.000) |     6.61 | Altekz, Kristou, refrezh, roeJ, TMB |
|           19 |     3593 | 2024-03-14 | Entropiq          | W   | 0.239      | -            | -                | -                | 0 (0.000) |     1.62 | Altekz, Kristou, refrezh, roeJ, TMB |
|           18 |     3666 | 2024-03-11 | Metizport         | L   | 0.222      | -            | -                | -                | -         |    -3.01 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3676 | 2024-03-11 | HEROIC            | L   | 0.220      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3681 | 2024-03-11 | Permitta          | W   | 0.220      | 0.371        | 0.024 (0.002)    | 0.873 (0.071)    | 0 (0.000) |     4.92 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3731 | 2024-03-09 | Fraud5            | W   | 0.206      | -            | -                | -                | 0 (0.000) |     2.00 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3774 | 2024-03-07 | Secret            | W   | 0.192      | -            | -                | -                | 0 (0.000) |     1.19 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3867 | 2024-03-03 | Gaimin Gladiators | W   | 0.168      | 0.143        | 0.037 (0.001)    | 0.346 (0.008)    | 0 (0.000) |     3.94 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3873 | 2024-03-03 | BetBoom           | W   | 0.168      | 0.143        | 0.249 (0.006)    | 0.536 (0.013)    | -         |     5.15 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3881 | 2024-03-03 | kONO              | W   | 0.168      | 0.143        | 0.028 (0.001)    | 0.574 (0.014)    | -         |     2.86 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3889 | 2024-03-03 | fnatic            | L   | 0.167      | -            | -                | -                | -         |    -0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3892 | 2024-03-03 | MOUZ NXT          | L   | 0.166      | -            | -                | -                | -         |    -0.94 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3920 | 2024-03-01 | BetBoom           | L   | 0.155      | -            | -                | -                | -         |    -0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     3942 | 2024-02-28 | fnatic            | W   | 0.142      | 0.500        | 0.371 (0.026)    | 0.706 (0.050)    | -         |     4.41 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4100 | 2024-02-21 | ex-Guild Eagles   | L   | 0.094      | -            | -                | -                | -         |    -1.34 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4127 | 2024-02-20 | PERA              | W   | 0.088      | 0.143        | 0.048 (0.001)    | 0.451 (0.006)    | 1 (0.088) |     1.94 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4152 | 2024-02-19 | OG                | L   | 0.081      | -            | -                | -                | -         |    -0.58 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4156 | 2024-02-19 | HEROIC            | L   | 0.080      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4379 | 2024-02-09 | Gaimin Gladiators | W   | 0.012      | -            | -                | -                | -         |     0.28 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4393 | 2024-02-08 | TSM               | W   | 0.006      | -            | -                | -                | -         |     0.06 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,770.22)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.447 | $1,600.00      | $714.67         |
| 2024-03-18 |      0.266 | $11,000.00     | $2,921.11       |
| 2024-02-09 |      0.012 | $11,000.00     | $134.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
