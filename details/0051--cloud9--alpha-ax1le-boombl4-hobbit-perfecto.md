### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1066.3<br />
<br />
Final Rank Value (1066.3) = Starting Rank Value (1030.7) + Head To Head Adjustments (35.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.275[<sup>2</sup>](#table1)

The average of these factors is 0.308<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1030.7
- 400 + ( ( 0.308 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1030.7


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
|           19 |     2641 | 2024-04-20 | Sashi             | L   | 0.494      | -            | -                | -                | -         |    -6.45 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2679 | 2024-04-19 | BetBoom           | W   | 0.489      | 0.143        | 0.251 (0.018)    | 0.542 (0.038)    | -         |    13.42 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2689 | 2024-04-19 | Sashi             | L   | 0.488      | -            | -                | -                | -         |    -6.34 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     2963 | 2024-04-09 | FaZe              | L   | 0.425      | -            | -                | -                | -         |    -0.39 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3013 | 2024-04-08 | Wildcard          | W   | 0.419      | 0.624        | 0.006 (0.001)    | -                | 1 (0.419) |     0.72 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3043 | 2024-04-08 | FlyQuest          | L   | 0.412      | -            | -                | -                | -         |    -4.84 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3266 | 2024-03-28 | Vitality          | L   | 0.342      | -            | -                | -                | -         |    -0.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3350 | 2024-03-23 | Natus Vincere     | W   | 0.309      | 1.000        | 1.000 (0.309)    | 0.331 (0.102)    | 1 (0.309) |     9.68 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3372 | 2024-03-22 | G2                | W   | 0.301      | 1.000        | 1.000 (0.301)    | 0.498 (0.150)    | 1 (0.301) |     9.42 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3383 | 2024-03-21 | Gaimin Gladiators | W   | 0.296      | 1.000        | 0.038 (0.011)    | 0.351 (0.104)    | 1 (0.296) |     3.93 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3390 | 2024-03-21 | Spirit            | L   | 0.295      | -            | -                | -                | -         |    -0.08 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3440 | 2024-03-18 | SAW               | W   | 0.275      | 0.143        | 0.105 (0.004)    | 0.540 (0.021)    | 1 (0.275) |     5.93 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3457 | 2024-03-17 | Legacy            | W   | 0.270      | 0.143        | 0.122 (0.005)    | 0.643 (0.025)    | 1 (0.270) |     4.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3476 | 2024-03-17 | Gaimin Gladiators | W   | 0.267      | 0.143        | 0.038 (0.001)    | 0.351 (0.013)    | 1 (0.267) |     3.52 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3685 | 2024-03-08 | SAW               | L   | 0.209      | -            | -                | -                | -         |    -2.09 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3750 | 2024-03-06 | Rare Atom         | W   | 0.195      | -            | -                | -                | -         |     0.37 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4082 | 2024-02-20 | Vitality          | W   | 0.094      | 0.143        | 0.649 (0.009)    | 0.383 (0.005)    | 1 (0.094) |     2.94 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4100 | 2024-02-19 | Apeks             | W   | 0.089      | 0.143        | -                | 0.166 (0.002)    | 1 (0.089) |     0.92 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4109 | 2024-02-19 | PERA              | W   | 0.088      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.088) |     0.99 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,236.75)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.453 | $5,000.00      | $2,267.48       |
| 2024-03-31 |      0.362 | $45,000.00     | $16,300.00      |
| 2024-03-10 |      0.223 | $7,500.00      | $1,669.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
