### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, hazr, pz<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  780.7<br />
<br />
Final Rank Value (780.7) = Starting Rank Value (758.8) + Head To Head Adjustments (22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.8
- 400 + ( ( 0.174 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 758.8


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
|           27 |     2413 | 2024-05-03 | FURIA       | L   | 0.567      | -            | -                | -                | -         |    -0.15 | ADDICT, BRACE, damyo, hazr, pz      |
|           26 |     2460 | 2024-05-01 | ENCE        | L   | 0.554      | -            | -                | -                | -         |    -0.50 | ADDICT, BRACE, damyo, hazr, pz      |
|           25 |     2492 | 2024-04-30 | MOUZ        | L   | 0.546      | -            | -                | -                | -         |    -0.04 | ADDICT, BRACE, damyo, hazr, pz      |
|           24 |     2715 | 2024-04-20 | FlyQuest    | L   | 0.479      | -            | -                | -                | -         |    -1.56 | ADDICT, BRACE, damyo, hazr, pz      |
|           23 |     2719 | 2024-04-19 | Rooster     | W   | 0.478      | 0.143        | 0.010 (0.001)    | 0.255 (0.017)    | 0 (0.000) |     7.96 | ADDICT, BRACE, damyo, hazr, pz      |
|           22 |     2762 | 2024-04-19 | Mindfreak   | W   | 0.473      | 0.143        | 0.004 (0.000)    | 0.218 (0.015)    | 0 (0.000) |     5.88 | ADDICT, BRACE, damyo, hazr, pz      |
|           21 |     2767 | 2024-04-18 | Rooster     | L   | 0.471      | -            | -                | -                | -         |    -6.98 | ADDICT, BRACE, damyo, hazr, pz      |
|           20 |     3016 | 2024-04-10 | Rooster     | W   | 0.412      | 0.333        | 0.010 (0.001)    | 0.255 (0.035)    | 0 (0.000) |     6.90 | ADDICT, BRACE, damyo, hazr, pz      |
|           19 |     3023 | 2024-04-10 | Rooster     | L   | 0.412      | -            | -                | -                | -         |    -6.22 | ADDICT, BRACE, damyo, hazr, pz      |
|           18 |     3249 | 2024-04-03 | DXA         | W   | 0.366      | 0.333        | 0.002 (0.000)    | 0.217 (0.026)    | 0 (0.000) |     4.23 | ADDICT, BRACE, damyo, hazr, pz      |
|           17 |     3254 | 2024-04-03 | DXA         | W   | 0.365      | 0.333        | 0.002 (0.000)    | 0.217 (0.026)    | 0 (0.000) |     4.36 | ADDICT, BRACE, damyo, hazr, pz      |
|           16 |     3377 | 2024-03-27 | Mindfreak   | L   | 0.319      | -            | -                | -                | -         |    -6.54 | ADDICT, BRACE, damyo, hazr, pz      |
|           15 |     3382 | 2024-03-27 | Mindfreak   | W   | 0.319      | 0.333        | 0.004 (0.000)    | 0.047 (0.005)    | 0 (0.000) |     3.57 | ADDICT, BRACE, damyo, hazr, pz      |
|           14 |     3425 | 2024-03-23 | DXA         | W   | 0.292      | 0.315        | 0.002 (0.000)    | 0.217 (0.020)    | 1 (0.292) |     3.60 | ADDICT, BRACE, damyo, hazr, pz      |
|           13 |     3428 | 2024-03-23 | Arcade      | W   | 0.292      | 0.315        | 0.002 (0.000)    | 0.130 (0.012)    | 1 (0.292) |     3.49 | ADDICT, BRACE, damyo, hazr, pz      |
|           12 |     3486 | 2024-03-20 | Canon Event | W   | 0.272      | -            | -                | -                | 0 (0.000) |     1.68 | ADDICT, BRACE, damyo, hazr, pz      |
|           11 |     3487 | 2024-03-20 | Canon Event | W   | 0.272      | -            | -                | -                | -         |     1.70 | ADDICT, BRACE, damyo, hazr, pz      |
|           10 |     3557 | 2024-03-15 | Gods Reign  | L   | 0.245      | -            | -                | -                | -         |    -3.76 | ADDICT, BRACE, hazr, pz, yourwombat |
|            9 |     3578 | 2024-03-14 | GRDX        | W   | 0.238      | 0.432        | 0.002 (0.000)    | -                | 1 (0.238) |     1.66 | ADDICT, BRACE, hazr, pz, yourwombat |
|            8 |     3611 | 2024-03-14 | Aurora      | L   | 0.232      | -            | -                | -                | -         |    -0.04 | ADDICT, BRACE, hazr, pz, yourwombat |
|            7 |     3824 | 2024-03-06 | Vantage     | W   | 0.179      | 0.333        | 0.002 (0.000)    | 0.064 (0.004)    | -         |     1.98 | ADDICT, BRACE, damyo, hazr, pz      |
|            6 |     3826 | 2024-03-06 | Vantage     | W   | 0.179      | 0.333        | -                | 0.064 (0.004)    | -         |     2.01 | ADDICT, BRACE, damyo, hazr, pz      |
|            5 |     4080 | 2024-02-22 | Rooster     | L   | 0.098      | -            | -                | -                | -         |    -1.46 | ADDICT, BRACE, Hatz, hazr, pz       |
|            4 |     4098 | 2024-02-22 | Vantage     | W   | 0.092      | -            | -                | -                | -         |     1.04 | ADDICT, BRACE, Hatz, hazr, pz       |
|            3 |     4101 | 2024-02-21 | FlyQuest    | L   | 0.091      | -            | -                | -                | -         |    -0.29 | ADDICT, BRACE, Hatz, hazr, pz       |
|            2 |     4124 | 2024-02-21 | FlyQuest    | L   | 0.086      | -            | -                | -                | -         |    -0.27 | ADDICT, BRACE, Hatz, hazr, pz       |
|            1 |     4128 | 2024-02-21 | FlyQuest    | L   | 0.086      | -            | -                | -                | -         |    -0.27 | ADDICT, BRACE, Hatz, hazr, pz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,244.89)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.811 | $1,050.00      | $851.86         |
| 2024-05-12 |      0.627 | $3,500.00      | $2,194.95       |
| 2024-03-23 |      0.292 | $3,308.00      | $966.59         |
| 2024-03-16 |      0.246 | $5,000.00      | $1,231.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
