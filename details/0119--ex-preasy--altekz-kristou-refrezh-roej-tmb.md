### Roster Details<br />
Team Name: ex-Preasy<br />
Roster: Altekz, Kristou, refrezh, roeJ, TMB<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  819.1<br />
<br />
Final Rank Value (819.1) = Starting Rank Value (774.4) + Head To Head Adjustments (44.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.340[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.4
- 400 + ( ( 0.183 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 774.4


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
|           26 |     2890 | 2024-04-15 | Sashi             | L   | 0.450      | -            | -                | -                | -         |    -2.08 | Altekz, Kristou, refrezh, roeJ, TMB |
|           25 |     2918 | 2024-04-13 | 3DMAX             | L   | 0.437      | -            | -                | -                | -         |    -0.14 | Altekz, Kristou, refrezh, roeJ, TMB |
|           24 |     3069 | 2024-04-09 | kONO              | W   | 0.409      | 0.384        | 0.028 (0.004)    | 0.566 (0.089)    | 0 (0.000) |     6.27 | Altekz, Kristou, refrezh, roeJ, TMB |
|           23 |     3123 | 2024-04-07 | Zero Tenacity     | W   | 0.396      | 0.358        | 0.143 (0.020)    | 1.000 (0.142)    | 0 (0.000) |    10.39 | Altekz, Kristou, refrezh, roeJ, TMB |
|           22 |     3429 | 2024-03-22 | FORZE             | L   | 0.290      | -            | -                | -                | -         |    -3.35 | Altekz, Kristou, refrezh, roeJ, TMB |
|           21 |     3508 | 2024-03-18 | Sampi             | W   | 0.262      | 0.371        | 0.027 (0.003)    | 1.000 (0.097)    | 0 (0.000) |     5.29 | Altekz, Kristou, refrezh, roeJ, TMB |
|           20 |     3548 | 2024-03-16 | Passion UA        | W   | 0.250      | 0.371        | 0.173 (0.016)    | 1.000 (0.093)    | 0 (0.000) |     6.55 | Altekz, Kristou, refrezh, roeJ, TMB |
|           19 |     3604 | 2024-03-14 | Entropiq          | W   | 0.236      | -            | -                | -                | 0 (0.000) |     1.60 | Altekz, Kristou, refrezh, roeJ, TMB |
|           18 |     3677 | 2024-03-11 | Metizport         | L   | 0.218      | -            | -                | -                | -         |    -2.96 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           17 |     3687 | 2024-03-11 | HEROIC            | L   | 0.217      | -            | -                | -                | -         |    -0.10 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           16 |     3692 | 2024-03-11 | Permitta          | W   | 0.216      | 0.371        | 0.023 (0.002)    | 0.901 (0.072)    | 0 (0.000) |     4.97 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           15 |     3742 | 2024-03-09 | Fraud5            | W   | 0.202      | -            | -                | -                | 0 (0.000) |     1.97 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           14 |     3785 | 2024-03-07 | Secret            | W   | 0.189      | -            | -                | -                | 0 (0.000) |     1.17 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           13 |     3878 | 2024-03-03 | Gaimin Gladiators | W   | 0.165      | 0.143        | 0.037 (0.001)    | 0.340 (0.008)    | 0 (0.000) |     3.86 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           12 |     3884 | 2024-03-03 | BetBoom           | W   | 0.165      | 0.143        | 0.249 (0.006)    | 0.527 (0.012)    | -         |     5.05 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           11 |     3892 | 2024-03-03 | kONO              | W   | 0.164      | 0.143        | 0.028 (0.001)    | 0.566 (0.013)    | -         |     2.81 | Altekz, dupreeh, refrezh, roeJ, TMB |
|           10 |     3900 | 2024-03-03 | fnatic            | L   | 0.163      | -            | -                | -                | -         |    -0.07 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            9 |     3903 | 2024-03-03 | MOUZ NXT          | L   | 0.162      | -            | -                | -                | -         |    -0.92 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            8 |     3931 | 2024-03-01 | BetBoom           | L   | 0.152      | -            | -                | -                | -         |    -0.13 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            7 |     3953 | 2024-02-28 | fnatic            | W   | 0.138      | 0.500        | 0.371 (0.026)    | 0.696 (0.048)    | -         |     4.30 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            6 |     4111 | 2024-02-21 | ex-Guild Eagles   | L   | 0.091      | -            | -                | -                | -         |    -1.29 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            5 |     4138 | 2024-02-20 | PERA              | W   | 0.084      | 0.143        | 0.048 (0.001)    | 0.445 (0.005)    | 1 (0.084) |     1.87 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            4 |     4163 | 2024-02-19 | OG                | L   | 0.078      | -            | -                | -                | -         |    -0.56 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            3 |     4167 | 2024-02-19 | HEROIC            | L   | 0.077      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            2 |     4390 | 2024-02-09 | Gaimin Gladiators | W   | 0.009      | -            | -                | -                | -         |     0.21 | Altekz, dupreeh, refrezh, roeJ, TMB |
|            1 |     4404 | 2024-02-08 | TSM               | W   | 0.002      | -            | -                | -                | -         |     0.03 | Altekz, dupreeh, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,691.56)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.443 | $1,600.00      | $709.33         |
| 2024-03-18 |      0.262 | $11,000.00     | $2,884.44       |
| 2024-02-09 |      0.009 | $11,000.00     | $97.78          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
