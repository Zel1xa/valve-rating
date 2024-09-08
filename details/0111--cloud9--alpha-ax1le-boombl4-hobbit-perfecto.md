### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [111](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  798.9<br />
<br />
Final Rank Value (798.9) = Starting Rank Value (786.2) + Head To Head Adjustments (12.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.052[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 786.2
- 400 + ( ( 0.199 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 786.2


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
|           14 |     3840 | 2024-04-20 | Sashi             | L   | 0.260      | -            | -                | -                | -         |    -1.51 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           13 |     3878 | 2024-04-19 | BetBoom           | W   | 0.255      | 0.143        | 0.229 (0.008)    | 0.535 (0.019)    | 0 (0.000) |     7.38 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           12 |     3888 | 2024-04-19 | Sashi             | L   | 0.253      | -            | -                | -                | -         |    -1.44 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           11 |     4162 | 2024-04-09 | FaZe              | L   | 0.191      | -            | -                | -                | -         |    -0.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     4212 | 2024-04-08 | Wildcard          | W   | 0.185      | 0.624        | 0.003 (0.000)    | 0.000 (0.000)    | 1 (0.185) |     1.11 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     4242 | 2024-04-08 | FlyQuest          | L   | 0.178      | -            | -                | -                | -         |    -1.20 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     4465 | 2024-03-28 | Vitality          | L   | 0.107      | -            | -                | -                | -         |    -0.01 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     4549 | 2024-03-23 | Natus Vincere     | W   | 0.075      | 1.000        | 1.000 (0.075)    | 0.473 (0.035)    | 1 (0.075) |     2.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     4571 | 2024-03-22 | G2                | W   | 0.066      | 1.000        | 1.000 (0.066)    | 0.481 (0.032)    | 1 (0.066) |     2.09 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     4582 | 2024-03-21 | Gaimin Gladiators | W   | 0.062      | 1.000        | 0.018 (0.001)    | 0.495 (0.031)    | 1 (0.062) |     1.26 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     4589 | 2024-03-21 | Spirit            | L   | 0.061      | -            | -                | -                | -         |    -0.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4639 | 2024-03-18 | SAW               | W   | 0.041      | 0.143        | 0.330 (0.002)    | 0.747 (0.004)    | 1 (0.041) |     1.27 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4656 | 2024-03-17 | Legacy            | W   | 0.035      | 0.143        | 0.092 (0.000)    | 0.730 (0.004)    | 1 (0.035) |     0.73 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4675 | 2024-03-17 | Gaimin Gladiators | W   | 0.033      | 0.143        | 0.018 (0.000)    | 0.495 (0.002)    | 1 (0.033) |     0.67 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,859.14)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.219 | $5,000.00      | $1,096.64       |
| 2024-03-31 |      0.128 | $45,000.00     | $5,762.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
