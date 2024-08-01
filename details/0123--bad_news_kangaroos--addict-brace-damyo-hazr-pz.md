### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, hazr, pz<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  792.1<br />
<br />
Final Rank Value (792.1) = Starting Rank Value (769.0) + Head To Head Adjustments (23.1)<br />

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
|           27 |     2325 | 2024-05-03 | FURIA       | L   | 0.599      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz      |
|           26 |     2374 | 2024-05-01 | ENCE        | L   | 0.586      | -            | -                | -                | -         |    -0.58 | ADDICT, BRACE, damyo, hazr, pz      |
|           25 |     2407 | 2024-04-30 | MOUZ        | L   | 0.578      | -            | -                | -                | -         |    -0.04 | ADDICT, BRACE, damyo, hazr, pz      |
|           24 |     2636 | 2024-04-20 | FlyQuest    | L   | 0.512      | -            | -                | -                | -         |    -1.56 | ADDICT, BRACE, damyo, hazr, pz      |
|           23 |     2640 | 2024-04-19 | Rooster     | W   | 0.510      | 0.143        | 0.010 (0.001)    | 0.281 (0.021)    | 0 (0.000) |     8.54 | ADDICT, BRACE, damyo, hazr, pz      |
|           22 |     2684 | 2024-04-19 | Mindfreak   | W   | 0.505      | 0.143        | 0.004 (0.000)    | 0.227 (0.016)    | 0 (0.000) |     6.12 | ADDICT, BRACE, damyo, hazr, pz      |
|           21 |     2689 | 2024-04-18 | Rooster     | L   | 0.504      | -            | -                | -                | -         |    -7.41 | ADDICT, BRACE, damyo, hazr, pz      |
|           20 |     2942 | 2024-04-10 | Rooster     | W   | 0.445      | 0.333        | 0.010 (0.002)    | 0.281 (0.042)    | 0 (0.000) |     7.48 | ADDICT, BRACE, damyo, hazr, pz      |
|           19 |     2949 | 2024-04-10 | Rooster     | L   | 0.444      | -            | -                | -                | -         |    -6.66 | ADDICT, BRACE, damyo, hazr, pz      |
|           18 |     3181 | 2024-04-03 | DXA         | W   | 0.398      | 0.333        | 0.002 (0.000)    | 0.228 (0.030)    | 0 (0.000) |     4.46 | ADDICT, BRACE, damyo, hazr, pz      |
|           17 |     3186 | 2024-04-03 | DXA         | W   | 0.398      | 0.333        | 0.002 (0.000)    | 0.228 (0.030)    | 0 (0.000) |     4.61 | ADDICT, BRACE, damyo, hazr, pz      |
|           16 |     3312 | 2024-03-27 | Mindfreak   | L   | 0.352      | -            | -                | -                | -         |    -7.31 | ADDICT, BRACE, damyo, hazr, pz      |
|           15 |     3317 | 2024-03-27 | Mindfreak   | W   | 0.351      | 0.333        | 0.004 (0.000)    | 0.053 (0.006)    | 0 (0.000) |     3.82 | ADDICT, BRACE, damyo, hazr, pz      |
|           14 |     3364 | 2024-03-23 | DXA         | W   | 0.325      | 0.315        | 0.002 (0.000)    | 0.228 (0.023)    | 1 (0.325) |     3.90 | ADDICT, BRACE, damyo, hazr, pz      |
|           13 |     3367 | 2024-03-23 | Arcade      | W   | 0.324      | 0.315        | 0.003 (0.000)    | 0.138 (0.014)    | 1 (0.324) |     3.81 | ADDICT, BRACE, damyo, hazr, pz      |
|           12 |     3425 | 2024-03-20 | Canon Event | W   | 0.304      | -            | -                | -                | 0 (0.000) |     1.78 | ADDICT, BRACE, damyo, hazr, pz      |
|           11 |     3426 | 2024-03-20 | Canon Event | W   | 0.304      | -            | -                | -                | -         |     1.81 | ADDICT, BRACE, damyo, hazr, pz      |
|           10 |     3496 | 2024-03-15 | Gods Reign  | L   | 0.277      | -            | -                | -                | -         |    -4.26 | ADDICT, BRACE, hazr, pz, yourwombat |
|            9 |     3517 | 2024-03-14 | GRDX        | W   | 0.270      | 0.432        | 0.002 (0.000)    | -                | 1 (0.270) |     1.81 | ADDICT, BRACE, hazr, pz, yourwombat |
|            8 |     3554 | 2024-03-14 | Aurora      | L   | 0.264      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat |
|            7 |     3769 | 2024-03-06 | Vantage     | W   | 0.212      | 0.333        | 0.002 (0.000)    | 0.075 (0.005)    | -         |     2.28 | ADDICT, BRACE, damyo, hazr, pz      |
|            6 |     3771 | 2024-03-06 | Vantage     | W   | 0.211      | 0.333        | -                | 0.075 (0.005)    | -         |     2.31 | ADDICT, BRACE, damyo, hazr, pz      |
|            5 |     4038 | 2024-02-22 | Rooster     | L   | 0.130      | -            | -                | -                | -         |    -1.96 | ADDICT, BRACE, Hatz, hazr, pz       |
|            4 |     4057 | 2024-02-22 | Vantage     | W   | 0.125      | -            | -                | -                | -         |     1.38 | ADDICT, BRACE, Hatz, hazr, pz       |
|            3 |     4060 | 2024-02-21 | FlyQuest    | L   | 0.123      | -            | -                | -                | -         |    -0.36 | ADDICT, BRACE, Hatz, hazr, pz       |
|            2 |     4082 | 2024-02-21 | FlyQuest    | L   | 0.118      | -            | -                | -                | -         |    -0.35 | ADDICT, BRACE, Hatz, hazr, pz       |
|            1 |     4088 | 2024-02-21 | FlyQuest    | L   | 0.118      | -            | -                | -                | -         |    -0.35 | ADDICT, BRACE, Hatz, hazr, pz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,660.39)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.844 | $1,050.00      | $885.79         |
| 2024-05-12 |      0.659 | $3,500.00      | $2,308.06       |
| 2024-03-23 |      0.325 | $3,308.00      | $1,073.49       |
| 2024-03-16 |      0.279 | $5,000.00      | $1,393.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
