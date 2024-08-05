### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1068.4<br />
<br />
Final Rank Value (1068.4) = Starting Rank Value (1031.6) + Head To Head Adjustments (36.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.457[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.267[<sup>2</sup>](#table1)

The average of these factors is 0.308<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1031.6
- 400 + ( ( 0.308 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1031.6


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
|           19 |     2699 | 2024-04-20 | Sashi             | L   | 0.485      | -            | -                | -                | -         |    -6.30 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2737 | 2024-04-19 | BetBoom           | W   | 0.480      | 0.143        | 0.249 (0.017)    | 0.529 (0.036)    | -         |    13.14 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2747 | 2024-04-19 | Sashi             | L   | 0.479      | -            | -                | -                | -         |    -6.19 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     3021 | 2024-04-09 | FaZe              | L   | 0.416      | -            | -                | -                | -         |    -0.39 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3071 | 2024-04-08 | Wildcard          | W   | 0.410      | 0.624        | 0.048 (0.012)    | 0.429 (0.110)    | 1 (0.410) |     3.50 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3101 | 2024-04-08 | FlyQuest          | L   | 0.403      | -            | -                | -                | -         |    -4.77 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3324 | 2024-03-28 | Vitality          | L   | 0.333      | -            | -                | -                | -         |    -0.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3408 | 2024-03-23 | Natus Vincere     | W   | 0.300      | 1.000        | 1.000 (0.300)    | 0.365 (0.110)    | 1 (0.300) |     9.40 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3430 | 2024-03-22 | G2                | W   | 0.292      | 1.000        | 1.000 (0.292)    | 0.490 (0.143)    | 1 (0.292) |     9.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3441 | 2024-03-21 | Gaimin Gladiators | W   | 0.287      | 1.000        | 0.037 (0.011)    | 0.342 (0.098)    | 1 (0.287) |     3.78 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3448 | 2024-03-21 | Spirit            | L   | 0.286      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3498 | 2024-03-18 | SAW               | W   | 0.266      | 0.143        | 0.104 (0.004)    | 0.530 (0.020)    | 1 (0.266) |     5.72 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3515 | 2024-03-17 | Legacy            | W   | 0.261      | 0.143        | 0.122 (0.005)    | 0.635 (0.024)    | 1 (0.261) |     3.97 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3534 | 2024-03-17 | Gaimin Gladiators | W   | 0.258      | 0.143        | 0.037 (0.001)    | 0.342 (0.013)    | 1 (0.258) |     3.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3743 | 2024-03-08 | SAW               | L   | 0.200      | -            | -                | -                | -         |    -2.01 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3808 | 2024-03-06 | Rare Atom         | W   | 0.186      | -            | -                | -                | -         |     0.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4140 | 2024-02-20 | Vitality          | W   | 0.085      | 0.143        | 0.648 (0.008)    | 0.376 (0.005)    | 1 (0.085) |     2.66 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4158 | 2024-02-19 | Apeks             | W   | 0.080      | -            | -                | -                | 1 (0.080) |     0.81 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4167 | 2024-02-19 | PERA              | W   | 0.079      | 0.143        | 0.048 (0.001)    | 0.446 (0.005)    | 1 (0.079) |     0.90 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,717.65)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.444 | $5,000.00      | $2,222.34       |
| 2024-03-31 |      0.353 | $45,000.00     | $15,893.75      |
| 2024-03-10 |      0.214 | $7,500.00      | $1,601.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
