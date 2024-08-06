### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1066.9<br />
<br />
Final Rank Value (1066.9) = Starting Rank Value (1030.2) + Head To Head Adjustments (36.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.457[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.265[<sup>2</sup>](#table1)

The average of these factors is 0.307<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1030.2
- 400 + ( ( 0.307 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1030.2


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
|           19 |     2701 | 2024-04-20 | Sashi             | L   | 0.483      | -            | -                | -                | -         |    -6.25 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2739 | 2024-04-19 | BetBoom           | W   | 0.478      | 0.143        | 0.249 (0.017)    | 0.527 (0.036)    | -         |    13.10 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2749 | 2024-04-19 | Sashi             | L   | 0.477      | -            | -                | -                | -         |    -6.13 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     3023 | 2024-04-09 | FaZe              | L   | 0.415      | -            | -                | -                | -         |    -0.39 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3073 | 2024-04-08 | Wildcard          | W   | 0.408      | 0.624        | 0.048 (0.012)    | 0.428 (0.109)    | 1 (0.408) |     3.52 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3103 | 2024-04-08 | FlyQuest          | L   | 0.402      | -            | -                | -                | -         |    -4.74 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3326 | 2024-03-28 | Vitality          | L   | 0.331      | -            | -                | -                | -         |    -0.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3410 | 2024-03-23 | Natus Vincere     | W   | 0.298      | 1.000        | 1.000 (0.298)    | 0.365 (0.109)    | 1 (0.298) |     9.34 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3432 | 2024-03-22 | G2                | W   | 0.290      | 1.000        | 1.000 (0.290)    | 0.489 (0.142)    | 1 (0.290) |     9.08 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3443 | 2024-03-21 | Gaimin Gladiators | W   | 0.285      | 1.000        | 0.037 (0.011)    | 0.340 (0.097)    | 1 (0.285) |     3.76 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3450 | 2024-03-21 | Spirit            | L   | 0.284      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3500 | 2024-03-18 | SAW               | W   | 0.264      | 0.143        | 0.104 (0.004)    | 0.529 (0.020)    | 1 (0.264) |     5.68 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3517 | 2024-03-17 | Legacy            | W   | 0.259      | 0.143        | 0.122 (0.005)    | 0.634 (0.023)    | 1 (0.259) |     3.96 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3536 | 2024-03-17 | Gaimin Gladiators | W   | 0.256      | 0.143        | 0.037 (0.001)    | 0.340 (0.012)    | 1 (0.256) |     3.34 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3745 | 2024-03-08 | SAW               | L   | 0.198      | -            | -                | -                | -         |    -1.99 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3810 | 2024-03-06 | Rare Atom         | W   | 0.184      | -            | -                | -                | -         |     0.35 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4142 | 2024-02-20 | Vitality          | W   | 0.083      | 0.143        | 0.647 (0.008)    | 0.376 (0.004)    | 1 (0.083) |     2.60 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4160 | 2024-02-19 | Apeks             | W   | 0.078      | -            | -                | -                | 1 (0.078) |     0.80 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4169 | 2024-02-19 | PERA              | W   | 0.077      | 0.143        | 0.048 (0.001)    | 0.445 (0.005)    | 1 (0.077) |     0.88 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,613.83)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.443 | $5,000.00      | $2,213.31       |
| 2024-03-31 |      0.351 | $45,000.00     | $15,812.50      |
| 2024-03-10 |      0.212 | $7,500.00      | $1,588.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
