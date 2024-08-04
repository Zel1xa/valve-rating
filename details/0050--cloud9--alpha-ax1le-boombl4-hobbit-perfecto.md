### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1074.0<br />
<br />
Final Rank Value (1074.0) = Starting Rank Value (1036.5) + Head To Head Adjustments (37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.274[<sup>2</sup>](#table1)

The average of these factors is 0.311<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1036.5
- 400 + ( ( 0.311 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1036.5


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
|           19 |     2673 | 2024-04-20 | Sashi             | L   | 0.493      | -            | -                | -                | -         |    -6.53 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2711 | 2024-04-19 | BetBoom           | W   | 0.487      | 0.143        | 0.251 (0.017)    | 0.541 (0.038)    | -         |    13.30 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2721 | 2024-04-19 | Sashi             | L   | 0.486      | -            | -                | -                | -         |    -6.42 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     2995 | 2024-04-09 | FaZe              | L   | 0.424      | -            | -                | -                | -         |    -0.40 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3045 | 2024-04-08 | Wildcard          | W   | 0.417      | 0.624        | 0.048 (0.012)    | 0.438 (0.114)    | 1 (0.417) |     3.50 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3075 | 2024-04-08 | FlyQuest          | L   | 0.411      | -            | -                | -                | -         |    -4.90 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3298 | 2024-03-28 | Vitality          | L   | 0.340      | -            | -                | -                | -         |    -0.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3382 | 2024-03-23 | Natus Vincere     | W   | 0.307      | 1.000        | 1.000 (0.307)    | 0.371 (0.114)    | 1 (0.307) |     9.63 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3404 | 2024-03-22 | G2                | W   | 0.299      | 1.000        | 1.000 (0.299)    | 0.498 (0.149)    | 1 (0.299) |     9.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3415 | 2024-03-21 | Gaimin Gladiators | W   | 0.294      | 1.000        | 0.038 (0.011)    | 0.350 (0.103)    | 1 (0.294) |     3.85 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3422 | 2024-03-21 | Spirit            | L   | 0.293      | -            | -                | -                | -         |    -0.08 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3472 | 2024-03-18 | SAW               | W   | 0.273      | 0.143        | 0.105 (0.004)    | 0.540 (0.021)    | 1 (0.273) |     5.85 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3489 | 2024-03-17 | Legacy            | W   | 0.268      | 0.143        | 0.122 (0.005)    | 0.643 (0.025)    | 1 (0.268) |     4.05 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3508 | 2024-03-17 | Gaimin Gladiators | W   | 0.265      | 0.143        | 0.038 (0.001)    | 0.350 (0.013)    | 1 (0.265) |     3.43 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3717 | 2024-03-08 | SAW               | L   | 0.207      | -            | -                | -                | -         |    -2.10 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3782 | 2024-03-06 | Rare Atom         | W   | 0.193      | -            | -                | -                | -         |     0.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4114 | 2024-02-20 | Vitality          | W   | 0.092      | 0.143        | 0.649 (0.009)    | 0.383 (0.005)    | 1 (0.092) |     2.88 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4132 | 2024-02-19 | Apeks             | W   | 0.087      | -            | -                | -                | 1 (0.087) |     0.88 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4141 | 2024-02-19 | PERA              | W   | 0.086      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.086) |     0.96 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,134.26)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.452 | $5,000.00      | $2,258.56       |
| 2024-03-31 |      0.360 | $45,000.00     | $16,219.79      |
| 2024-03-10 |      0.221 | $7,500.00      | $1,655.90       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
