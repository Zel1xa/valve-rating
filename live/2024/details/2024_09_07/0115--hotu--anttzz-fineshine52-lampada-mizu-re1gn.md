### Roster Details<br />
Team Name: HOTU<br />
Roster: anttzz, fineshine52, lampada, mizu, Re1GN<br />
Global Rank: [115](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [83]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  793.7<br />
<br />
Final Rank Value (793.7) = Starting Rank Value (742.9) + Head To Head Adjustments (50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 742.9
- 400 + ( ( 0.175 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 742.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       34 | 2024-09-05 | MOUZ NXT       | W   | 1.000      | 0.372        | 0.111 (0.041)    | 0.844 (0.314)    | 0 (0.000) |    24.59 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            9 |       52 | 2024-09-05 | RUSH B         | W   | 1.000      | 0.384        | 0.026 (0.010)    | 0.316 (0.121)    | 0 (0.000) |    21.74 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            8 |      115 | 2024-09-03 | Enterprise     | W   | 1.000      | 0.372        | 0.039 (0.015)    | 0.720 (0.268)    | 0 (0.000) |    20.06 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            7 |      209 | 2024-08-30 | SINNERS        | L   | 1.000      | -            | -                | -                | -         |    -2.61 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            6 |      781 | 2024-08-15 | QUAZAR         | L   | 1.000      | -            | -                | -                | -         |   -24.60 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            5 |      789 | 2024-08-15 | KOI            | W   | 1.000      | 0.143        | 0.053 (0.008)    | 0.329 (0.047)    | 0 (0.000) |    23.64 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            4 |     2244 | 2024-06-13 | VP.Prodigy     | L   | 0.628      | -            | -                | -                | -         |    -6.53 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            3 |     2772 | 2024-05-31 | CYBERSHOKE     | L   | 0.541      | -            | -                | -                | -         |    -4.25 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            2 |     2780 | 2024-05-30 | Spirit Academy | L   | 0.536      | -            | -                | -                | -         |    -7.73 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            1 |     2810 | 2024-05-29 | LEON           | W   | 0.530      | 0.372        | 0.005 (0.001)    | 0.084 (0.017)    | 0 (0.000) |     6.44 | anttzz, fineshine52, lampada, mizu, swiftsteel |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,619.10)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
