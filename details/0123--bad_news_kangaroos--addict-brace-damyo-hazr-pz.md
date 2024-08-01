### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, hazr, pz<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  792.0<br />
<br />
Final Rank Value (792.0) = Starting Rank Value (769.0) + Head To Head Adjustments (23.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.0
- 400 + ( ( 0.179 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 769.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2327 | 2024-05-03 | FURIA       | L   | 0.599      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz      |
|           26 |     2376 | 2024-05-01 | ENCE        | L   | 0.586      | -            | -                | -                | -         |    -0.58 | ADDICT, BRACE, damyo, hazr, pz      |
|           25 |     2409 | 2024-04-30 | MOUZ        | L   | 0.578      | -            | -                | -                | -         |    -0.04 | ADDICT, BRACE, damyo, hazr, pz      |
|           24 |     2638 | 2024-04-20 | FlyQuest    | L   | 0.511      | -            | -                | -                | -         |    -1.56 | ADDICT, BRACE, damyo, hazr, pz      |
|           23 |     2642 | 2024-04-19 | Rooster     | W   | 0.510      | 0.143        | 0.010 (0.001)    | 0.281 (0.021)    | 0 (0.000) |     8.54 | ADDICT, BRACE, damyo, hazr, pz      |
|           22 |     2686 | 2024-04-19 | Mindfreak   | W   | 0.505      | 0.143        | 0.004 (0.000)    | 0.227 (0.016)    | 0 (0.000) |     6.12 | ADDICT, BRACE, damyo, hazr, pz      |
|           21 |     2691 | 2024-04-18 | Rooster     | L   | 0.503      | -            | -                | -                | -         |    -7.41 | ADDICT, BRACE, damyo, hazr, pz      |
|           20 |     2944 | 2024-04-10 | Rooster     | W   | 0.444      | 0.333        | 0.010 (0.002)    | 0.281 (0.042)    | 0 (0.000) |     7.48 | ADDICT, BRACE, damyo, hazr, pz      |
|           19 |     2951 | 2024-04-10 | Rooster     | L   | 0.444      | -            | -                | -                | -         |    -6.66 | ADDICT, BRACE, damyo, hazr, pz      |
|           18 |     3183 | 2024-04-03 | DXA         | W   | 0.398      | 0.333        | 0.002 (0.000)    | 0.228 (0.030)    | 0 (0.000) |     4.46 | ADDICT, BRACE, damyo, hazr, pz      |
|           17 |     3188 | 2024-04-03 | DXA         | W   | 0.398      | 0.333        | 0.002 (0.000)    | 0.228 (0.030)    | 0 (0.000) |     4.61 | ADDICT, BRACE, damyo, hazr, pz      |
|           16 |     3314 | 2024-03-27 | Mindfreak   | L   | 0.351      | -            | -                | -                | -         |    -7.30 | ADDICT, BRACE, damyo, hazr, pz      |
|           15 |     3319 | 2024-03-27 | Mindfreak   | W   | 0.351      | 0.333        | 0.004 (0.000)    | 0.053 (0.006)    | 0 (0.000) |     3.82 | ADDICT, BRACE, damyo, hazr, pz      |
|           14 |     3366 | 2024-03-23 | DXA         | W   | 0.324      | 0.315        | 0.002 (0.000)    | 0.228 (0.023)    | 1 (0.324) |     3.89 | ADDICT, BRACE, damyo, hazr, pz      |
|           13 |     3369 | 2024-03-23 | Arcade      | W   | 0.324      | 0.315        | 0.003 (0.000)    | 0.138 (0.014)    | 1 (0.324) |     3.81 | ADDICT, BRACE, damyo, hazr, pz      |
|           12 |     3427 | 2024-03-20 | Canon Event | W   | 0.304      | -            | -                | -                | 0 (0.000) |     1.78 | ADDICT, BRACE, damyo, hazr, pz      |
|           11 |     3428 | 2024-03-20 | Canon Event | W   | 0.304      | -            | -                | -                | -         |     1.81 | ADDICT, BRACE, damyo, hazr, pz      |
|           10 |     3498 | 2024-03-15 | Gods Reign  | L   | 0.277      | -            | -                | -                | -         |    -4.26 | ADDICT, BRACE, hazr, pz, yourwombat |
|            9 |     3519 | 2024-03-14 | GRDX        | W   | 0.270      | 0.432        | 0.002 (0.000)    | -                | 1 (0.270) |     1.81 | ADDICT, BRACE, hazr, pz, yourwombat |
|            8 |     3556 | 2024-03-14 | Aurora      | L   | 0.264      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat |
|            7 |     3771 | 2024-03-06 | Vantage     | W   | 0.211      | 0.333        | 0.002 (0.000)    | 0.074 (0.005)    | -         |     2.27 | ADDICT, BRACE, damyo, hazr, pz      |
|            6 |     3773 | 2024-03-06 | Vantage     | W   | 0.211      | 0.333        | -                | 0.074 (0.005)    | -         |     2.31 | ADDICT, BRACE, damyo, hazr, pz      |
|            5 |     4040 | 2024-02-22 | Rooster     | L   | 0.130      | -            | -                | -                | -         |    -1.96 | ADDICT, BRACE, Hatz, hazr, pz       |
|            4 |     4059 | 2024-02-22 | Vantage     | W   | 0.124      | -            | -                | -                | -         |     1.38 | ADDICT, BRACE, Hatz, hazr, pz       |
|            3 |     4062 | 2024-02-21 | FlyQuest    | L   | 0.123      | -            | -                | -                | -         |    -0.36 | ADDICT, BRACE, Hatz, hazr, pz       |
|            2 |     4084 | 2024-02-21 | FlyQuest    | L   | 0.118      | -            | -                | -                | -         |    -0.35 | ADDICT, BRACE, Hatz, hazr, pz       |
|            1 |     4090 | 2024-02-21 | FlyQuest    | L   | 0.118      | -            | -                | -                | -         |    -0.35 | ADDICT, BRACE, Hatz, hazr, pz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,656.82)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.843 | $1,050.00      | $885.50         |
| 2024-05-12 |      0.659 | $3,500.00      | $2,307.08       |
| 2024-03-23 |      0.324 | $3,308.00      | $1,072.57       |
| 2024-03-16 |      0.278 | $5,000.00      | $1,391.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
