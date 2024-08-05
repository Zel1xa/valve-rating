### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1072.0<br />
<br />
Final Rank Value (1072.0) = Starting Rank Value (1034.7) + Head To Head Adjustments (37.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.271[<sup>2</sup>](#table1)

The average of these factors is 0.310<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1034.7
- 400 + ( ( 0.310 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1034.7


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
|           19 |     2677 | 2024-04-20 | Sashi             | L   | 0.490      | -            | -                | -                | -         |    -6.46 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2715 | 2024-04-19 | BetBoom           | W   | 0.485      | 0.143        | 0.250 (0.017)    | 0.540 (0.037)    | -         |    13.25 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2725 | 2024-04-19 | Sashi             | L   | 0.483      | -            | -                | -                | -         |    -6.35 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     2999 | 2024-04-09 | FaZe              | L   | 0.421      | -            | -                | -                | -         |    -0.40 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3049 | 2024-04-08 | Wildcard          | W   | 0.415      | 0.624        | 0.048 (0.012)    | 0.437 (0.113)    | 1 (0.415) |     3.51 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3079 | 2024-04-08 | FlyQuest          | L   | 0.408      | -            | -                | -                | -         |    -4.85 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3302 | 2024-03-28 | Vitality          | L   | 0.338      | -            | -                | -                | -         |    -0.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3386 | 2024-03-23 | Natus Vincere     | W   | 0.305      | 1.000        | 1.000 (0.305)    | 0.371 (0.113)    | 1 (0.305) |     9.55 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3408 | 2024-03-22 | G2                | W   | 0.296      | 1.000        | 1.000 (0.296)    | 0.498 (0.148)    | 1 (0.296) |     9.29 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3419 | 2024-03-21 | Gaimin Gladiators | W   | 0.292      | 1.000        | 0.038 (0.011)    | 0.349 (0.102)    | 1 (0.292) |     3.83 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3426 | 2024-03-21 | Spirit            | L   | 0.291      | -            | -                | -                | -         |    -0.08 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3476 | 2024-03-18 | SAW               | W   | 0.271      | 0.143        | 0.105 (0.004)    | 0.539 (0.021)    | 1 (0.271) |     5.81 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3493 | 2024-03-17 | Legacy            | W   | 0.265      | 0.143        | 0.122 (0.005)    | 0.644 (0.024)    | 1 (0.265) |     4.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3512 | 2024-03-17 | Gaimin Gladiators | W   | 0.263      | 0.143        | 0.038 (0.001)    | 0.349 (0.013)    | 1 (0.263) |     3.41 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3721 | 2024-03-08 | SAW               | L   | 0.205      | -            | -                | -                | -         |    -2.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3786 | 2024-03-06 | Rare Atom         | W   | 0.190      | -            | -                | -                | -         |     0.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4118 | 2024-02-20 | Vitality          | W   | 0.090      | 0.143        | 0.648 (0.008)    | 0.382 (0.005)    | 1 (0.090) |     2.81 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4136 | 2024-02-19 | Apeks             | W   | 0.085      | -            | -                | -                | 1 (0.085) |     0.86 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4145 | 2024-02-19 | PERA              | W   | 0.083      | 0.143        | 0.048 (0.001)    | 0.453 (0.005)    | 1 (0.083) |     0.94 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,997.16)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.449 | $5,000.00      | $2,246.64       |
| 2024-03-31 |      0.358 | $45,000.00     | $16,112.50      |
| 2024-03-10 |      0.218 | $7,500.00      | $1,638.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
