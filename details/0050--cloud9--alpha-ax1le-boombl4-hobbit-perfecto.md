### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1069.3<br />
<br />
Final Rank Value (1069.3) = Starting Rank Value (1032.3) + Head To Head Adjustments (37.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.458[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
- LAN Wins: 0.268[<sup>2</sup>](#table1)

The average of these factors is 0.309<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1032.3
- 400 + ( ( 0.309 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1032.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     2690 | 2024-04-20 | Sashi             | L   | 0.487      | -            | -                | -                | -         |    -6.35 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2728 | 2024-04-19 | BetBoom           | W   | 0.481      | 0.143        | 0.249 (0.017)    | 0.536 (0.037)    | -         |    13.18 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2738 | 2024-04-19 | Sashi             | L   | 0.480      | -            | -                | -                | -         |    -6.24 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     3012 | 2024-04-09 | FaZe              | L   | 0.418      | -            | -                | -                | -         |    -0.39 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3062 | 2024-04-08 | Wildcard          | W   | 0.411      | 0.624        | 0.048 (0.012)    | 0.435 (0.112)    | 1 (0.411) |     3.51 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3092 | 2024-04-08 | FlyQuest          | L   | 0.405      | -            | -                | -                | -         |    -4.79 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3315 | 2024-03-28 | Vitality          | L   | 0.334      | -            | -                | -                | -         |    -0.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3399 | 2024-03-23 | Natus Vincere     | W   | 0.302      | 1.000        | 1.000 (0.302)    | 0.370 (0.112)    | 1 (0.302) |     9.45 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3421 | 2024-03-22 | G2                | W   | 0.293      | 1.000        | 1.000 (0.293)    | 0.496 (0.145)    | 1 (0.293) |     9.18 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3432 | 2024-03-21 | Gaimin Gladiators | W   | 0.288      | 1.000        | 0.037 (0.011)    | 0.346 (0.100)    | 1 (0.288) |     3.79 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3439 | 2024-03-21 | Spirit            | L   | 0.287      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3489 | 2024-03-18 | SAW               | W   | 0.268      | 0.143        | 0.105 (0.004)    | 0.537 (0.021)    | 1 (0.268) |     5.75 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3506 | 2024-03-17 | Legacy            | W   | 0.262      | 0.143        | 0.122 (0.005)    | 0.642 (0.024)    | 1 (0.262) |     4.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3525 | 2024-03-17 | Gaimin Gladiators | W   | 0.260      | 0.143        | 0.037 (0.001)    | 0.346 (0.013)    | 1 (0.260) |     3.37 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3734 | 2024-03-08 | SAW               | L   | 0.202      | -            | -                | -                | -         |    -2.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3799 | 2024-03-06 | Rare Atom         | W   | 0.187      | -            | -                | -                | -         |     0.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4131 | 2024-02-20 | Vitality          | W   | 0.087      | 0.143        | 0.648 (0.008)    | 0.381 (0.005)    | 1 (0.087) |     2.71 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4149 | 2024-02-19 | Apeks             | W   | 0.082      | -            | -                | -                | 1 (0.082) |     0.83 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4158 | 2024-02-19 | PERA              | W   | 0.080      | 0.143        | 0.048 (0.001)    | 0.451 (0.005)    | 1 (0.080) |     0.91 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,805.50)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.446 | $5,000.00      | $2,229.98       |
| 2024-03-31 |      0.355 | $45,000.00     | $15,962.50      |
| 2024-03-10 |      0.215 | $7,500.00      | $1,613.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
