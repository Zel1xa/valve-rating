### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1072.2<br />
<br />
Final Rank Value (1072.2) = Starting Rank Value (1035.9) + Head To Head Adjustments (36.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.280[<sup>2</sup>](#table1)

The average of these factors is 0.311<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1035.9
- 400 + ( ( 0.311 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1035.9


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
|           19 |     2570 | 2024-04-20 | Sashi             | L   | 0.499      | -            | -                | -                | -         |    -6.46 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2608 | 2024-04-19 | BetBoom           | W   | 0.493      | 0.143        | 0.252 (0.018)    | 0.563 (0.040)    | -         |    13.49 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2618 | 2024-04-19 | Sashi             | L   | 0.492      | -            | -                | -                | -         |    -6.35 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     2892 | 2024-04-09 | FaZe              | L   | 0.430      | -            | -                | -                | -         |    -0.39 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     2942 | 2024-04-08 | Wildcard          | W   | 0.424      | 0.624        | 0.006 (0.001)    | -                | 1 (0.424) |     0.71 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     2972 | 2024-04-08 | FlyQuest          | L   | 0.417      | -            | -                | -                | -         |    -4.96 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3195 | 2024-03-28 | Vitality          | L   | 0.346      | -            | -                | -                | -         |    -0.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3276 | 2024-03-23 | Natus Vincere     | W   | 0.314      | 1.000        | 1.000 (0.314)    | 0.343 (0.108)    | 1 (0.314) |     9.83 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3296 | 2024-03-22 | G2                | W   | 0.305      | 1.000        | 1.000 (0.305)    | 0.516 (0.157)    | 1 (0.305) |     9.57 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3307 | 2024-03-21 | Gaimin Gladiators | W   | 0.301      | 1.000        | 0.038 (0.012)    | 0.366 (0.110)    | 1 (0.301) |     3.99 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3314 | 2024-03-21 | Spirit            | L   | 0.300      | -            | -                | -                | -         |    -0.08 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3364 | 2024-03-18 | SAW               | W   | 0.280      | 0.143        | 0.106 (0.004)    | 0.560 (0.022)    | 1 (0.280) |     6.01 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3381 | 2024-03-17 | Legacy            | W   | 0.274      | 0.143        | 0.122 (0.005)    | 0.663 (0.026)    | 1 (0.274) |     4.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3400 | 2024-03-17 | Gaimin Gladiators | W   | 0.272      | 0.143        | 0.038 (0.001)    | 0.366 (0.014)    | 1 (0.272) |     3.58 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3606 | 2024-03-08 | SAW               | L   | 0.214      | -            | -                | -                | -         |    -2.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3671 | 2024-03-06 | Rare Atom         | W   | 0.199      | -            | -                | -                | -         |     0.37 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4003 | 2024-02-20 | Vitality          | W   | 0.099      | 0.143        | 0.650 (0.009)    | 0.396 (0.006)    | 1 (0.099) |     3.09 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4021 | 2024-02-19 | Apeks             | W   | 0.094      | 0.143        | -                | 0.174 (0.002)    | 1 (0.094) |     0.96 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4030 | 2024-02-19 | PERA              | W   | 0.092      | 0.143        | 0.048 (0.001)    | 0.468 (0.006)    | 1 (0.092) |     1.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,510.94)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.458 | $5,000.00      | $2,291.32       |
| 2024-03-31 |      0.367 | $45,000.00     | $16,514.58      |
| 2024-03-10 |      0.227 | $7,500.00      | $1,705.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
