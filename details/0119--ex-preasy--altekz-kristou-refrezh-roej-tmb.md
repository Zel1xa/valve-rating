### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  821.5<br />
<br />
Final Rank Value (821.5) = Starting Rank Value (775.7) + Head To Head Adjustments (45.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.7
- 400 + ( ( 0.184 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 775.7


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
|           27 |     2866 | 2024-04-15 | Sashi             | L   | 0.456      | -            | -                | -                | -         |    -2.14 | Altekz, Kristou, refrezh, roeJ, TMB |
|           26 |     2894 | 2024-04-13 | 3DMAX             | L   | 0.443      | -            | -                | -                | -         |    -0.15 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     3045 | 2024-04-09 | kONO              | W   | 0.416      | 0.384        | 0.028 (0.005)    | 0.536 (0.086)    | 0 (0.000) |     6.32 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3099 | 2024-04-07 | Zero Tenacity     | W   | 0.403      | 0.358        | 0.137 (0.020)    | 1.000 (0.144)    | 0 (0.000) |    10.52 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3405 | 2024-03-22 | FORZE             | L   | 0.297      | -            | -                | -                | -         |    -3.43 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3484 | 2024-03-18 | Sampi             | W   | 0.269      | 0.371        | 0.027 (0.003)    | 1.000 (0.100)    | 0 (0.000) |     5.41 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3524 | 2024-03-16 | Passion UA        | W   | 0.257      | 0.371        | 0.172 (0.016)    | 1.000 (0.095)    | 0 (0.000) |     6.68 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3580 | 2024-03-14 | Entropiq          | W   | 0.242      | -            | -                | -                | 0 (0.000) |     1.64 | Altekz, Kristou, refrezh, roeJ, TMB |
|           19 |     3653 | 2024-03-11 | Metizport         | L   | 0.225      | -            | -                | -                | -         |    -3.06 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           18 |     3663 | 2024-03-11 | HEROIC            | L   | 0.224      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3668 | 2024-03-11 | Permitta          | W   | 0.223      | 0.371        | 0.024 (0.002)    | 0.876 (0.072)    | 0 (0.000) |     4.99 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3718 | 2024-03-09 | Fraud5            | W   | 0.209      | -            | -                | -                | 0 (0.000) |     2.02 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3761 | 2024-03-07 | Secret            | W   | 0.196      | -            | -                | -                | 0 (0.000) |     1.20 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3854 | 2024-03-03 | Gaimin Gladiators | W   | 0.172      | 0.143        | 0.038 (0.001)    | 0.349 (0.009)    | 0 (0.000) |     4.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3860 | 2024-03-03 | BetBoom           | W   | 0.171      | 0.143        | 0.250 (0.006)    | 0.540 (0.013)    | -         |     5.25 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3868 | 2024-03-03 | kONO              | W   | 0.171      | 0.143        | 0.028 (0.001)    | 0.536 (0.013)    | -         |     2.91 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3876 | 2024-03-03 | fnatic            | L   | 0.170      | -            | -                | -                | -         |    -0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3879 | 2024-03-03 | MOUZ NXT          | L   | 0.169      | -            | -                | -                | -         |    -0.98 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3907 | 2024-03-01 | BetBoom           | L   | 0.158      | -            | -                | -                | -         |    -0.14 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3929 | 2024-02-28 | fnatic            | W   | 0.145      | 0.500        | 0.371 (0.027)    | 0.708 (0.051)    | -         |     4.51 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     4087 | 2024-02-21 | ex-Guild Eagles   | L   | 0.098      | -            | -                | -                | -         |    -1.39 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4114 | 2024-02-20 | PERA              | W   | 0.091      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.091) |     2.01 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4139 | 2024-02-19 | OG                | L   | 0.085      | -            | -                | -                | -         |    -0.60 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4143 | 2024-02-19 | HEROIC            | L   | 0.084      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4366 | 2024-02-09 | Gaimin Gladiators | W   | 0.016      | -            | -                | -                | -         |     0.36 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4380 | 2024-02-08 | TSM               | W   | 0.009      | -            | -                | -                | -         |     0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4386 | 2024-02-07 | Into the Breach   | W   | 0.002      | -            | -                | -                | -         |     0.01 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,848.89)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.450 | $1,600.00      | $720.00         |
| 2024-03-18 |      0.269 | $11,000.00     | $2,957.78       |
| 2024-02-09 |      0.016 | $11,000.00     | $171.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
