### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1097.1<br />
<br />
Final Rank Value (1097.1) = Starting Rank Value (1060.0) + Head To Head Adjustments (37.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.460[<sup>1</sup>](#table2)
- Bounty Collected: 0.466[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.304[<sup>2</sup>](#table1)

The average of these factors is 0.320<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1060.0
- 400 + ( ( 0.320 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1060.0


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
|           21 |     2524 | 2024-04-20 | Sashi             | L   | 0.518      | -            | -                | -                | -         |    -7.27 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           20 |     2562 | 2024-04-19 | BetBoom           | W   | 0.512      | 0.143        | 0.256 (0.019)    | 0.554 (0.041)    | -         |    13.94 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           19 |     2572 | 2024-04-19 | Sashi             | L   | 0.511      | -            | -                | -                | -         |    -7.18 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2846 | 2024-04-09 | FaZe              | L   | 0.449      | -            | -                | -                | -         |    -0.39 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           17 |     2896 | 2024-04-08 | Wildcard          | W   | 0.443      | 0.624        | 0.006 (0.002)    | -                | 1 (0.443) |     1.01 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           16 |     2926 | 2024-04-08 | FlyQuest          | L   | 0.436      | -            | -                | -                | -         |    -5.23 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3149 | 2024-03-28 | Vitality          | L   | 0.365      | -            | -                | -                | -         |    -0.16 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3233 | 2024-03-23 | Natus Vincere     | W   | 0.333      | 1.000        | 1.000 (0.333)    | 0.331 (0.110)    | 1 (0.333) |    10.42 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3255 | 2024-03-22 | G2                | W   | 0.324      | 1.000        | 1.000 (0.324)    | 0.492 (0.160)    | 1 (0.324) |    10.15 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3266 | 2024-03-21 | Gaimin Gladiators | W   | 0.320      | 1.000        | 0.040 (0.013)    | 0.363 (0.116)    | 1 (0.320) |     4.15 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3273 | 2024-03-21 | Spirit            | L   | 0.319      | -            | -                | -                | -         |    -0.09 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3323 | 2024-03-18 | SAW               | W   | 0.299      | 0.143        | 0.107 (0.005)    | 0.545 (0.023)    | 1 (0.299) |     6.32 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3340 | 2024-03-17 | Legacy            | W   | 0.293      | 0.143        | 0.118 (0.005)    | 0.562 (0.024)    | 1 (0.293) |     4.06 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3359 | 2024-03-17 | Gaimin Gladiators | W   | 0.291      | 0.143        | 0.040 (0.002)    | 0.363 (0.015)    | 1 (0.291) |     3.73 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3568 | 2024-03-08 | SAW               | L   | 0.233      | -            | -                | -                | -         |    -2.43 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3633 | 2024-03-06 | Rare Atom         | W   | 0.218      | -            | -                | -                | -         |     0.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3965 | 2024-02-20 | Vitality          | W   | 0.118      | 0.143        | 0.654 (0.011)    | 0.385 (0.006)    | 1 (0.118) |     3.68 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3983 | 2024-02-19 | Apeks             | W   | 0.113      | 0.143        | -                | 0.176 (0.003)    | 1 (0.113) |     1.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     3992 | 2024-02-19 | PERA              | W   | 0.111      | 0.143        | 0.048 (0.001)    | 0.452 (0.007)    | 1 (0.111) |     1.17 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4250 | 2024-02-05 | Monte             | L   | 0.018      | -            | -                | -                | -         |    -0.32 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4271 | 2024-02-04 | MOUZ              | L   | 0.011      | -            | -                | -                | -         |    -0.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,192.06)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.477 | $5,000.00      | $2,386.39       |
| 2024-03-31 |      0.386 | $45,000.00     | $17,370.21      |
| 2024-03-10 |      0.246 | $7,500.00      | $1,847.64       |
| 2024-02-11 |      0.059 | $10,000.00     | $587.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
