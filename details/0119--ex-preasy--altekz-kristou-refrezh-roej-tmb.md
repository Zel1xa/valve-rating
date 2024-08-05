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
Final Rank Value (820.1) = Starting Rank Value (775.1) + Head To Head Adjustments (45.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.1
- 400 + ( ( 0.183 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 775.1


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
|           26 |     2888 | 2024-04-15 | Sashi             | L   | 0.452      | -            | -                | -                | -         |    -2.10 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     2916 | 2024-04-13 | 3DMAX             | L   | 0.438      | -            | -                | -                | -         |    -0.14 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3067 | 2024-04-09 | kONO              | W   | 0.411      | 0.384        | 0.028 (0.004)    | 0.566 (0.089)    | 0 (0.000) |     6.28 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3121 | 2024-04-07 | Zero Tenacity     | W   | 0.398      | 0.358        | 0.143 (0.020)    | 1.000 (0.142)    | 0 (0.000) |    10.43 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3427 | 2024-03-22 | FORZE             | L   | 0.292      | -            | -                | -                | -         |    -3.37 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3506 | 2024-03-18 | Sampi             | W   | 0.264      | 0.371        | 0.027 (0.003)    | 1.000 (0.098)    | 0 (0.000) |     5.32 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3546 | 2024-03-16 | Passion UA        | W   | 0.252      | 0.371        | 0.173 (0.016)    | 1.000 (0.093)    | 0 (0.000) |     6.59 | Altekz, Kristou, refrezh, roeJ, TMB |
|           19 |     3602 | 2024-03-14 | Entropiq          | W   | 0.237      | -            | -                | -                | 0 (0.000) |     1.61 | Altekz, Kristou, refrezh, roeJ, TMB |
|           18 |     3675 | 2024-03-11 | Metizport         | L   | 0.220      | -            | -                | -                | -         |    -2.98 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3685 | 2024-03-11 | HEROIC            | L   | 0.219      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3690 | 2024-03-11 | Permitta          | W   | 0.218      | 0.371        | 0.024 (0.002)    | 0.902 (0.073)    | 0 (0.000) |     5.01 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3740 | 2024-03-09 | Fraud5            | W   | 0.204      | -            | -                | -                | 0 (0.000) |     1.98 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3783 | 2024-03-07 | Secret            | W   | 0.191      | -            | -                | -                | 0 (0.000) |     1.18 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3876 | 2024-03-03 | Gaimin Gladiators | W   | 0.167      | 0.143        | 0.037 (0.001)    | 0.342 (0.008)    | 0 (0.000) |     3.91 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3882 | 2024-03-03 | BetBoom           | W   | 0.167      | 0.143        | 0.249 (0.006)    | 0.529 (0.013)    | -         |     5.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3890 | 2024-03-03 | kONO              | W   | 0.166      | 0.143        | 0.028 (0.001)    | 0.566 (0.013)    | -         |     2.84 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3898 | 2024-03-03 | fnatic            | L   | 0.165      | -            | -                | -                | -         |    -0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3901 | 2024-03-03 | MOUZ NXT          | L   | 0.164      | -            | -                | -                | -         |    -0.93 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3929 | 2024-03-01 | BetBoom           | L   | 0.153      | -            | -                | -                | -         |    -0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     3951 | 2024-02-28 | fnatic            | W   | 0.140      | 0.500        | 0.371 (0.026)    | 0.697 (0.049)    | -         |     4.36 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4109 | 2024-02-21 | ex-Guild Eagles   | L   | 0.093      | -            | -                | -                | -         |    -1.31 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4136 | 2024-02-20 | PERA              | W   | 0.086      | 0.143        | 0.048 (0.001)    | 0.446 (0.005)    | 1 (0.086) |     1.90 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4161 | 2024-02-19 | OG                | L   | 0.080      | -            | -                | -                | -         |    -0.57 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4165 | 2024-02-19 | HEROIC            | L   | 0.079      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4388 | 2024-02-09 | Gaimin Gladiators | W   | 0.011      | -            | -                | -                | -         |     0.25 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4402 | 2024-02-08 | TSM               | W   | 0.004      | -            | -                | -                | -         |     0.04 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,734.17)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.445 | $1,600.00      | $712.22         |
| 2024-03-18 |      0.264 | $11,000.00     | $2,904.31       |
| 2024-02-09 |      0.011 | $11,000.00     | $117.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
