### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  823.0<br />
<br />
Final Rank Value (823.0) = Starting Rank Value (776.6) + Head To Head Adjustments (46.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.011[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.6
- 400 + ( ( 0.184 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 776.6


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
|           27 |     2861 | 2024-04-15 | Sashi             | L   | 0.459      | -            | -                | -                | -         |    -2.17 | Altekz, Kristou, refrezh, roeJ, TMB |
|           26 |     2889 | 2024-04-13 | 3DMAX             | L   | 0.446      | -            | -                | -                | -         |    -0.15 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     3040 | 2024-04-09 | kONO              | W   | 0.418      | 0.384        | 0.028 (0.005)    | 0.536 (0.086)    | 0 (0.000) |     6.34 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3094 | 2024-04-07 | Zero Tenacity     | W   | 0.405      | 0.358        | 0.137 (0.020)    | 1.000 (0.145)    | 0 (0.000) |    10.56 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3400 | 2024-03-22 | FORZE             | L   | 0.299      | -            | -                | -                | -         |    -3.48 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3479 | 2024-03-18 | Sampi             | W   | 0.272      | 0.371        | 0.027 (0.003)    | 1.000 (0.101)    | 0 (0.000) |     5.45 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3519 | 2024-03-16 | Passion UA        | W   | 0.259      | 0.371        | 0.172 (0.017)    | 1.000 (0.096)    | 0 (0.000) |     6.74 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3575 | 2024-03-14 | Entropiq          | W   | 0.245      | -            | -                | -                | 0 (0.000) |     1.65 | Altekz, Kristou, refrezh, roeJ, TMB |
|           19 |     3648 | 2024-03-11 | Metizport         | L   | 0.228      | -            | -                | -                | -         |    -3.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           18 |     3658 | 2024-03-11 | HEROIC            | L   | 0.226      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3663 | 2024-03-11 | Permitta          | W   | 0.226      | 0.371        | 0.024 (0.002)    | 0.876 (0.073)    | 0 (0.000) |     5.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3713 | 2024-03-09 | Fraud5            | W   | 0.212      | -            | -                | -                | 0 (0.000) |     2.04 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3756 | 2024-03-07 | Secret            | W   | 0.198      | -            | -                | -                | 0 (0.000) |     1.21 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3849 | 2024-03-03 | Gaimin Gladiators | W   | 0.174      | 0.143        | 0.038 (0.001)    | 0.351 (0.009)    | 0 (0.000) |     4.09 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3855 | 2024-03-03 | BetBoom           | W   | 0.174      | 0.143        | 0.251 (0.006)    | 0.541 (0.013)    | -         |     5.33 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3863 | 2024-03-03 | kONO              | W   | 0.174      | 0.143        | 0.028 (0.001)    | 0.536 (0.013)    | -         |     2.95 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3871 | 2024-03-03 | fnatic            | L   | 0.173      | -            | -                | -                | -         |    -0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3874 | 2024-03-03 | MOUZ NXT          | L   | 0.172      | -            | -                | -                | -         |    -1.00 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3902 | 2024-03-01 | BetBoom           | L   | 0.161      | -            | -                | -                | -         |    -0.14 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3924 | 2024-02-28 | fnatic            | W   | 0.148      | 0.500        | 0.371 (0.027)    | 0.708 (0.052)    | -         |     4.59 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     4082 | 2024-02-21 | ex-Guild Eagles   | L   | 0.100      | -            | -                | -                | -         |    -1.43 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4109 | 2024-02-20 | PERA              | W   | 0.094      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.094) |     2.06 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4134 | 2024-02-19 | OG                | L   | 0.087      | -            | -                | -                | -         |    -0.62 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4138 | 2024-02-19 | HEROIC            | L   | 0.086      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4361 | 2024-02-09 | Gaimin Gladiators | W   | 0.018      | -            | -                | -                | -         |     0.42 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4375 | 2024-02-08 | TSM               | W   | 0.012      | -            | -                | -                | -         |     0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4381 | 2024-02-07 | Into the Breach   | W   | 0.005      | -            | -                | -                | -         |     0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,912.26)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.453 | $1,600.00      | $724.30         |
| 2024-03-18 |      0.272 | $11,000.00     | $2,987.31       |
| 2024-02-09 |      0.018 | $11,000.00     | $200.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
