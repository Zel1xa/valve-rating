### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [106](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [77]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  815.9<br />
<br />
Final Rank Value (815.9) = Starting Rank Value (801.5) + Head To Head Adjustments (14.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.382[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 801.5
- 400 + ( ( 0.205 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 801.5


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
|           14 |     3803 | 2024-04-20 | Sashi             | L   | 0.272      | -            | -                | -                | -         |    -1.63 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           13 |     3841 | 2024-04-19 | BetBoom           | W   | 0.266      | 0.143        | 0.230 (0.009)    | 0.555 (0.021)    | 0 (0.000) |     7.72 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           12 |     3851 | 2024-04-19 | Sashi             | L   | 0.265      | -            | -                | -                | -         |    -1.55 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           11 |     4125 | 2024-04-09 | FaZe              | L   | 0.203      | -            | -                | -                | -         |    -0.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     4175 | 2024-04-08 | Wildcard          | W   | 0.197      | 0.624        | 0.003 (0.000)    | 0.000 (0.000)    | 1 (0.197) |     1.11 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     4205 | 2024-04-08 | FlyQuest          | L   | 0.190      | -            | -                | -                | -         |    -1.37 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     4428 | 2024-03-28 | Vitality          | L   | 0.119      | -            | -                | -                | -         |    -0.01 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     4512 | 2024-03-23 | Natus Vincere     | W   | 0.087      | 1.000        | 1.000 (0.087)    | 0.452 (0.039)    | 1 (0.087) |     2.74 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     4534 | 2024-03-22 | G2                | W   | 0.078      | 1.000        | 1.000 (0.078)    | 0.497 (0.039)    | 1 (0.078) |     2.46 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     4545 | 2024-03-21 | Gaimin Gladiators | W   | 0.074      | 1.000        | 0.019 (0.001)    | 0.511 (0.038)    | 1 (0.074) |     1.48 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     4552 | 2024-03-21 | Spirit            | L   | 0.073      | -            | -                | -                | -         |    -0.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4602 | 2024-03-18 | SAW               | W   | 0.053      | 0.143        | 0.326 (0.002)    | 0.770 (0.006)    | 1 (0.053) |     1.64 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4619 | 2024-03-17 | Legacy            | W   | 0.047      | 0.143        | 0.092 (0.001)    | 0.751 (0.005)    | 1 (0.047) |     0.97 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4638 | 2024-03-17 | Gaimin Gladiators | W   | 0.045      | 0.143        | 0.019 (0.000)    | 0.511 (0.003)    | 1 (0.045) |     0.91 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,455.21)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.231 | $5,000.00      | $1,156.25       |
| 2024-03-31 |      0.140 | $45,000.00     | $6,298.96       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
