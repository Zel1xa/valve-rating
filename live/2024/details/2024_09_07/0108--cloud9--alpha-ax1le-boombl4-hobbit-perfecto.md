### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [108](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [79]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  811.8<br />
<br />
Final Rank Value (811.8) = Starting Rank Value (797.9) + Head To Head Adjustments (13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.058[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 797.9
- 400 + ( ( 0.203 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 797.9


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
|           14 |     3808 | 2024-04-20 | Sashi             | L   | 0.268      | -            | -                | -                | -         |    -1.58 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           13 |     3846 | 2024-04-19 | BetBoom           | W   | 0.262      | 0.143        | 0.230 (0.009)    | 0.554 (0.021)    | 0 (0.000) |     7.62 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           12 |     3856 | 2024-04-19 | Sashi             | L   | 0.261      | -            | -                | -                | -         |    -1.50 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           11 |     4130 | 2024-04-09 | FaZe              | L   | 0.199      | -            | -                | -                | -         |    -0.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     4180 | 2024-04-08 | Wildcard          | W   | 0.193      | 0.624        | 0.003 (0.000)    | 0.000 (0.000)    | 1 (0.193) |     1.11 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     4210 | 2024-04-08 | FlyQuest          | L   | 0.186      | -            | -                | -                | -         |    -1.33 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     4433 | 2024-03-28 | Vitality          | L   | 0.115      | -            | -                | -                | -         |    -0.01 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     4517 | 2024-03-23 | Natus Vincere     | W   | 0.083      | 1.000        | 1.000 (0.083)    | 0.453 (0.038)    | 1 (0.083) |     2.61 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     4539 | 2024-03-22 | G2                | W   | 0.074      | 1.000        | 1.000 (0.074)    | 0.497 (0.037)    | 1 (0.074) |     2.34 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     4550 | 2024-03-21 | Gaimin Gladiators | W   | 0.070      | 1.000        | 0.018 (0.001)    | 0.511 (0.036)    | 1 (0.070) |     1.41 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     4557 | 2024-03-21 | Spirit            | L   | 0.069      | -            | -                | -                | -         |    -0.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4607 | 2024-03-18 | SAW               | W   | 0.049      | 0.143        | 0.328 (0.002)    | 0.771 (0.005)    | 1 (0.049) |     1.52 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4624 | 2024-03-17 | Legacy            | W   | 0.043      | 0.143        | 0.092 (0.001)    | 0.752 (0.005)    | 1 (0.043) |     0.90 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4643 | 2024-03-17 | Gaimin Gladiators | W   | 0.041      | 0.143        | 0.018 (0.000)    | 0.511 (0.003)    | 1 (0.041) |     0.83 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,254.98)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.227 | $5,000.00      | $1,136.23       |
| 2024-03-31 |      0.136 | $45,000.00     | $6,118.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
