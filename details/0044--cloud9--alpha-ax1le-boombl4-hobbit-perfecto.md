### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1092.8<br />
<br />
Final Rank Value (1092.8) = Starting Rank Value (1056.0) + Head To Head Adjustments (36.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.460[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.300[<sup>2</sup>](#table1)

The average of these factors is 0.319<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1056.0
- 400 + ( ( 0.319 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1056.0


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
|           21 |     2624 | 2024-04-20 | Sashi             | L   | 0.514      | -            | -                | -                | -         |    -7.14 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           20 |     2663 | 2024-04-19 | BetBoom           | W   | 0.508      | 0.143        | 0.257 (0.019)    | 0.551 (0.040)    | -         |    13.76 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           19 |     2673 | 2024-04-19 | Sashi             | L   | 0.507      | -            | -                | -                | -         |    -7.04 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2951 | 2024-04-09 | FaZe              | L   | 0.445      | -            | -                | -                | -         |    -0.40 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           17 |     3001 | 2024-04-08 | Wildcard          | W   | 0.438      | 0.624        | 0.006 (0.002)    | -                | 1 (0.438) |     1.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           16 |     3031 | 2024-04-08 | FlyQuest          | L   | 0.432      | -            | -                | -                | -         |    -5.23 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3262 | 2024-03-28 | Vitality          | L   | 0.361      | -            | -                | -                | -         |    -0.17 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3351 | 2024-03-23 | Natus Vincere     | W   | 0.329      | 1.000        | 1.000 (0.329)    | 0.331 (0.109)    | 1 (0.329) |    10.29 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3373 | 2024-03-22 | G2                | W   | 0.320      | 1.000        | 1.000 (0.320)    | 0.500 (0.160)    | 1 (0.320) |    10.02 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3384 | 2024-03-21 | Gaimin Gladiators | W   | 0.315      | 1.000        | 0.040 (0.012)    | 0.361 (0.114)    | 1 (0.315) |     4.11 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3391 | 2024-03-21 | Spirit            | L   | 0.314      | -            | -                | -                | -         |    -0.09 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3441 | 2024-03-18 | SAW               | W   | 0.295      | 0.143        | 0.108 (0.005)    | 0.544 (0.023)    | 1 (0.295) |     6.24 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3458 | 2024-03-17 | Legacy            | W   | 0.289      | 0.143        | 0.119 (0.005)    | 0.562 (0.023)    | 1 (0.289) |     4.25 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3477 | 2024-03-17 | Gaimin Gladiators | W   | 0.287      | 0.143        | 0.040 (0.002)    | 0.361 (0.015)    | 1 (0.287) |     3.70 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3692 | 2024-03-08 | SAW               | L   | 0.229      | -            | -                | -                | -         |    -2.35 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3757 | 2024-03-06 | Rare Atom         | W   | 0.214      | -            | -                | -                | -         |     0.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     4104 | 2024-02-20 | Vitality          | W   | 0.114      | 0.143        | 0.591 (0.010)    | 0.385 (0.006)    | 1 (0.114) |     3.54 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     4122 | 2024-02-19 | Apeks             | W   | 0.109      | 0.143        | -                | 0.194 (0.003)    | 1 (0.109) |     1.09 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4131 | 2024-02-19 | PERA              | W   | 0.107      | 0.143        | 0.048 (0.001)    | 0.452 (0.007)    | 1 (0.107) |     1.12 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4399 | 2024-02-05 | Monte             | L   | 0.013      | -            | -                | -                | -         |    -0.24 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4420 | 2024-02-04 | MOUZ              | L   | 0.007      | -            | -                | -                | -         |    -0.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,899.25)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.473 | $5,000.00      | $2,364.70       |
| 2024-03-31 |      0.382 | $45,000.00     | $17,175.00      |
| 2024-03-10 |      0.242 | $7,500.00      | $1,815.10       |
| 2024-02-11 |      0.054 | $10,000.00     | $544.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
