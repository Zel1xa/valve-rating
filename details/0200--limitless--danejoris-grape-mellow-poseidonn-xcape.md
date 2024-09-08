### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [200](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  577.0<br />
<br />
Final Rank Value (577.0) = Starting Rank Value (626.3) + Head To Head Adjustments (-49.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.244[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 626.3
- 400 + ( ( 0.117 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 626.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     2260 | 2024-06-13 | Nouns            | L   | 0.622      | -            | -                | -                | -         |    -2.44 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           34 |     2289 | 2024-06-12 | regain           | L   | 0.617      | -            | -                | -                | -         |   -12.64 | Danejoris, DooM, grape, PoseidoNN, xCAPE    |
|           33 |     2291 | 2024-06-12 | E-Xolos LAZER    | L   | 0.616      | -            | -                | -                | -         |    -5.52 | Coastal, Danejoris, grape, PoseidoNN, xCAPE |
|           32 |     2318 | 2024-06-11 | Perseverance     | W   | 0.608      | 0.371        | 0.000 (0.000)    | 0.044 (0.010)    | 0 (0.000) |     7.67 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           31 |     2336 | 2024-06-10 | Final Form       | L   | 0.602      | -            | -                | -                | -         |   -11.28 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           30 |     2487 | 2024-06-07 | Vibe             | W   | 0.583      | 0.371        | 0.000 (0.000)    | 0.035 (0.008)    | 0 (0.000) |     4.50 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           29 |     2554 | 2024-06-06 | Homyno           | L   | 0.575      | -            | -                | -                | -         |    -7.43 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           28 |     2714 | 2024-06-03 | Asian Kings      | W   | 0.554      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.25 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           27 |     2977 | 2024-05-22 | LAG              | L   | 0.477      | -            | -                | -                | -         |    -4.69 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           26 |     2980 | 2024-05-22 | LAG              | L   | 0.477      | -            | -                | -                | -         |    -4.86 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           25 |     3020 | 2024-05-21 | Party Astronauts | L   | 0.470      | -            | -                | -                | -         |    -2.71 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           24 |     3023 | 2024-05-21 | Party Astronauts | L   | 0.470      | -            | -                | -                | -         |    -2.78 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           23 |     3094 | 2024-05-19 | Wildcard         | L   | 0.456      | -            | -                | -                | -         |    -1.52 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE  |
|           22 |     3224 | 2024-05-15 | timbermen        | L   | 0.430      | -            | -                | -                | -         |    -2.03 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           21 |     3231 | 2024-05-15 | timbermen        | L   | 0.430      | -            | -                | -                | -         |    -2.07 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           20 |     3406 | 2024-05-10 | M80              | L   | 0.397      | -            | -                | -                | -         |    -0.78 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           19 |     3407 | 2024-05-10 | M80              | L   | 0.397      | -            | -                | -                | -         |    -0.78 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           18 |     3420 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.391      | -            | -                | -                | -         |    -3.89 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           17 |     3423 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.390      | 0.477        | 0.006 (0.001)    | 0.540 (0.100)    | 0 (0.000) |     8.58 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           16 |     3441 | 2024-05-08 | Wildcard         | L   | 0.384      | -            | -                | -                | -         |    -1.25 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           15 |     3444 | 2024-05-08 | Wildcard         | L   | 0.383      | -            | -                | -                | -         |    -1.27 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           14 |     4018 | 2024-04-15 | Nouns            | L   | 0.231      | -            | -                | -                | -         |    -1.30 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           13 |     4019 | 2024-04-15 | Nouns            | L   | 0.230      | -            | -                | -                | -         |    -1.32 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           12 |     4077 | 2024-04-11 | BOSS             | L   | 0.204      | -            | -                | -                | -         |    -1.83 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           11 |     4079 | 2024-04-11 | BOSS             | L   | 0.203      | -            | -                | -                | -         |    -1.85 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           10 |     4295 | 2024-04-04 | Take Flyte       | L   | 0.157      | -            | -                | -                | -         |    -2.08 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            9 |     4299 | 2024-04-04 | Take Flyte       | W   | 0.157      | 0.477        | 0.002 (0.000)    | 0.230 (0.017)    | 0 (0.000) |     2.89 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            8 |     4341 | 2024-04-03 | Phoenix          | L   | 0.150      | -            | -                | -                | -         |    -1.92 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            7 |     4343 | 2024-04-03 | Phoenix          | L   | 0.150      | -            | -                | -                | -         |    -1.95 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            6 |     4470 | 2024-03-27 | MIGHT            | W   | 0.104      | 0.477        | 0.000 (0.000)    | 0.025 (0.001)    | 0 (0.000) |     1.05 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            5 |     4476 | 2024-03-27 | MIGHT            | W   | 0.104      | 0.477        | 0.000 (0.000)    | 0.025 (0.001)    | 0 (0.000) |     1.06 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            4 |     4520 | 2024-03-26 | Mythic           | L   | 0.097      | -            | -                | -                | -         |    -0.96 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            3 |     4525 | 2024-03-26 | Mythic           | W   | 0.097      | 0.477        | 0.007 (0.000)    | 0.276 (0.013)    | 0 (0.000) |     2.12 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            2 |     4712 | 2024-03-14 | NRG              | L   | 0.017      | -            | -                | -                | -         |    -0.14 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            1 |     4716 | 2024-03-14 | NRG              | L   | 0.017      | -            | -                | -                | -         |    -0.14 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($238.56)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
