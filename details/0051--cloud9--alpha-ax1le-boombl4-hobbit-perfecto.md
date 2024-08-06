### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1064.8<br />
<br />
Final Rank Value (1064.8) = Starting Rank Value (1028.3) + Head To Head Adjustments (36.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.456[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.262[<sup>2</sup>](#table1)

The average of these factors is 0.306<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1028.3
- 400 + ( ( 0.306 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1028.3


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
|           19 |     2705 | 2024-04-20 | Sashi             | L   | 0.481      | -            | -                | -                | -         |    -6.17 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2743 | 2024-04-19 | BetBoom           | W   | 0.475      | 0.143        | 0.248 (0.017)    | 0.526 (0.036)    | -         |    13.04 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2753 | 2024-04-19 | Sashi             | L   | 0.474      | -            | -                | -                | -         |    -6.05 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     3027 | 2024-04-09 | FaZe              | L   | 0.412      | -            | -                | -                | -         |    -0.38 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3077 | 2024-04-08 | Wildcard          | W   | 0.405      | 0.624        | 0.048 (0.012)    | 0.428 (0.108)    | 1 (0.405) |     3.52 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3107 | 2024-04-08 | FlyQuest          | L   | 0.399      | -            | -                | -                | -         |    -4.70 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3330 | 2024-03-28 | Vitality          | L   | 0.328      | -            | -                | -                | -         |    -0.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3414 | 2024-03-23 | Natus Vincere     | W   | 0.296      | 1.000        | 1.000 (0.296)    | 0.365 (0.108)    | 1 (0.296) |     9.27 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3436 | 2024-03-22 | G2                | W   | 0.287      | 1.000        | 1.000 (0.287)    | 0.489 (0.140)    | 1 (0.287) |     9.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3447 | 2024-03-21 | Gaimin Gladiators | W   | 0.283      | 1.000        | 0.037 (0.010)    | 0.339 (0.096)    | 1 (0.283) |     3.74 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3454 | 2024-03-21 | Spirit            | L   | 0.282      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3504 | 2024-03-18 | SAW               | W   | 0.262      | 0.143        | 0.104 (0.004)    | 0.528 (0.020)    | 1 (0.262) |     5.64 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3521 | 2024-03-17 | Legacy            | W   | 0.256      | 0.143        | 0.122 (0.004)    | 0.634 (0.023)    | 1 (0.256) |     3.93 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3540 | 2024-03-17 | Gaimin Gladiators | W   | 0.254      | 0.143        | 0.037 (0.001)    | 0.339 (0.012)    | 1 (0.254) |     3.32 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3749 | 2024-03-08 | SAW               | L   | 0.196      | -            | -                | -                | -         |    -1.96 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3814 | 2024-03-06 | Rare Atom         | W   | 0.181      | -            | -                | -                | -         |     0.35 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4146 | 2024-02-20 | Vitality          | W   | 0.081      | 0.143        | 0.647 (0.007)    | 0.375 (0.004)    | 1 (0.081) |     2.52 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4164 | 2024-02-19 | Apeks             | W   | 0.076      | -            | -                | -                | 1 (0.076) |     0.78 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4173 | 2024-02-19 | PERA              | W   | 0.074      | 0.143        | 0.048 (0.001)    | 0.445 (0.005)    | 1 (0.074) |     0.85 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,470.08)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.440 | $5,000.00      | $2,200.81       |
| 2024-03-31 |      0.349 | $45,000.00     | $15,700.00      |
| 2024-03-10 |      0.209 | $7,500.00      | $1,569.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
