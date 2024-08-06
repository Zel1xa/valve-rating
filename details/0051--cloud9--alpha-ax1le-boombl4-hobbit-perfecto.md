### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1064.9<br />
<br />
Final Rank Value (1064.9) = Starting Rank Value (1028.6) + Head To Head Adjustments (36.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.456[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.262[<sup>2</sup>](#table1)

The average of these factors is 0.306<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1028.6
- 400 + ( ( 0.306 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1028.6


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
|           19 |     2712 | 2024-04-20 | Sashi             | L   | 0.480      | -            | -                | -                | -         |    -6.16 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2750 | 2024-04-19 | BetBoom           | W   | 0.475      | 0.143        | 0.248 (0.017)    | 0.514 (0.035)    | -         |    13.02 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2760 | 2024-04-19 | Sashi             | L   | 0.474      | -            | -                | -                | -         |    -6.04 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     3034 | 2024-04-09 | FaZe              | L   | 0.411      | -            | -                | -                | -         |    -0.38 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3084 | 2024-04-08 | Wildcard          | W   | 0.405      | 0.624        | 0.048 (0.012)    | 0.418 (0.106)    | 1 (0.405) |     3.50 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3114 | 2024-04-08 | FlyQuest          | L   | 0.399      | -            | -                | -                | -         |    -4.70 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3337 | 2024-03-28 | Vitality          | L   | 0.328      | -            | -                | -                | -         |    -0.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3421 | 2024-03-23 | Natus Vincere     | W   | 0.295      | 1.000        | 1.000 (0.295)    | 0.357 (0.105)    | 1 (0.295) |     9.25 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3443 | 2024-03-22 | G2                | W   | 0.287      | 1.000        | 1.000 (0.287)    | 0.478 (0.137)    | 1 (0.287) |     8.98 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3454 | 2024-03-21 | Gaimin Gladiators | W   | 0.282      | 1.000        | 0.037 (0.010)    | 0.331 (0.093)    | 1 (0.282) |     3.72 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3461 | 2024-03-21 | Spirit            | L   | 0.281      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3511 | 2024-03-18 | SAW               | W   | 0.261      | 0.143        | 0.104 (0.004)    | 0.516 (0.019)    | 1 (0.261) |     5.61 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3528 | 2024-03-17 | Legacy            | W   | 0.256      | 0.143        | 0.122 (0.004)    | 0.620 (0.023)    | 1 (0.256) |     3.91 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3547 | 2024-03-17 | Gaimin Gladiators | W   | 0.253      | 0.143        | 0.037 (0.001)    | 0.331 (0.012)    | 1 (0.253) |     3.30 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3756 | 2024-03-08 | SAW               | L   | 0.195      | -            | -                | -                | -         |    -1.97 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3821 | 2024-03-06 | Rare Atom         | W   | 0.181      | -            | -                | -                | -         |     0.35 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4153 | 2024-02-20 | Vitality          | W   | 0.080      | 0.143        | 0.647 (0.007)    | 0.367 (0.004)    | 1 (0.080) |     2.50 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4171 | 2024-02-19 | Apeks             | W   | 0.075      | -            | -                | -                | 1 (0.075) |     0.77 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4180 | 2024-02-19 | PERA              | W   | 0.074      | 0.143        | 0.048 (0.000)    | 0.435 (0.005)    | 1 (0.074) |     0.84 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,432.81)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.440 | $5,000.00      | $2,197.57       |
| 2024-03-31 |      0.348 | $45,000.00     | $15,670.83      |
| 2024-03-10 |      0.209 | $7,500.00      | $1,564.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
