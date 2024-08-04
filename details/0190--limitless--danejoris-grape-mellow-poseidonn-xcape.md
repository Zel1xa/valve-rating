### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [190](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  582.5<br />
<br />
Final Rank Value (582.5) = Starting Rank Value (656.7) + Head To Head Adjustments (-74.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.7
- 400 + ( ( 0.126 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 656.7


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
|           40 |     1069 | 2024-06-13 | Nouns            | L   | 0.856      | -            | -                | -                | -         |    -2.66 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           39 |     1098 | 2024-06-12 | Detonate         | L   | 0.850      | -            | -                | -                | -         |   -15.99 | Danejoris, DooM, grape, PoseidoNN, xCAPE    |
|           38 |     1100 | 2024-06-12 | E-Xolos LAZER    | L   | 0.849      | -            | -                | -                | -         |    -7.42 | Coastal, Danejoris, grape, PoseidoNN, xCAPE |
|           37 |     1127 | 2024-06-11 | Perseverance     | W   | 0.841      | 0.371        | 0.000 (0.000)    | 0.064 (0.020)    | 0 (0.000) |    10.76 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           36 |     1145 | 2024-06-10 | Final Form       | L   | 0.836      | -            | -                | -                | -         |   -15.34 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           35 |     1296 | 2024-06-07 | Vibe             | W   | 0.816      | 0.371        | 0.000 (0.000)    | 0.070 (0.021)    | 0 (0.000) |     6.37 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           34 |     1363 | 2024-06-06 | Homyno           | L   | 0.809      | -            | -                | -                | -         |    -9.21 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           33 |     1523 | 2024-06-03 | Asian Kings      | W   | 0.787      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.73 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           32 |     1786 | 2024-05-22 | LAG              | L   | 0.710      | -            | -                | -                | -         |    -5.42 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           31 |     1789 | 2024-05-22 | LAG              | L   | 0.710      | -            | -                | -                | -         |    -5.68 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           30 |     1829 | 2024-05-21 | Party Astronauts | L   | 0.704      | -            | -                | -                | -         |    -3.21 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           29 |     1832 | 2024-05-21 | Party Astronauts | L   | 0.704      | -            | -                | -                | -         |    -3.31 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           28 |     1903 | 2024-05-19 | Wildcard         | L   | 0.690      | -            | -                | -                | -         |    -3.34 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE  |
|           27 |     2033 | 2024-05-15 | Elevate          | L   | 0.664      | -            | -                | -                | -         |    -2.64 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           26 |     2040 | 2024-05-15 | Elevate          | L   | 0.663      | -            | -                | -                | -         |    -2.71 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           25 |     2215 | 2024-05-10 | M80              | L   | 0.630      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           24 |     2216 | 2024-05-10 | M80              | L   | 0.630      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           23 |     2229 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.624      | -            | -                | -                | -         |    -7.06 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           22 |     2232 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.623      | 0.477        | 0.010 (0.003)    | 0.101 (0.030)    | 0 (0.000) |    12.92 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           21 |     2250 | 2024-05-08 | Wildcard         | L   | 0.617      | -            | -                | -                | -         |    -3.23 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           20 |     2253 | 2024-05-08 | Wildcard         | L   | 0.617      | -            | -                | -                | -         |    -3.33 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           19 |     2827 | 2024-04-15 | Nouns            | L   | 0.464      | -            | -                | -                | -         |    -2.33 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           18 |     2828 | 2024-04-15 | Nouns            | L   | 0.464      | -            | -                | -                | -         |    -2.38 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           17 |     2886 | 2024-04-11 | BOSS             | L   | 0.437      | -            | -                | -                | -         |    -3.76 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           16 |     2888 | 2024-04-11 | BOSS             | L   | 0.437      | -            | -                | -                | -         |    -3.87 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           15 |     3104 | 2024-04-04 | Take Flyte       | L   | 0.390      | -            | -                | -                | -         |    -5.43 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           14 |     3108 | 2024-04-04 | Take Flyte       | W   | 0.390      | 0.477        | 0.002 (0.000)    | 0.240 (0.045)    | 0 (0.000) |     7.01 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           13 |     3150 | 2024-04-03 | Perseverance     | L   | 0.384      | -            | -                | -                | -         |    -4.76 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           12 |     3152 | 2024-04-03 | Perseverance     | L   | 0.383      | -            | -                | -                | -         |    -4.92 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           11 |     3279 | 2024-03-27 | MIGHT            | W   | 0.337      | 0.477        | 0.000 (0.000)    | 0.060 (0.010)    | 0 (0.000) |     3.60 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           10 |     3285 | 2024-03-27 | MIGHT            | W   | 0.337      | 0.477        | 0.000 (0.000)    | 0.060 (0.010)    | 0 (0.000) |     3.70 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            9 |     3329 | 2024-03-26 | Mythic           | L   | 0.331      | -            | -                | -                | -         |    -3.32 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            8 |     3334 | 2024-03-26 | Mythic           | W   | 0.330      | 0.477        | 0.010 (0.002)    | 0.299 (0.047)    | 0 (0.000) |     7.23 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            7 |     3521 | 2024-03-14 | NRG              | L   | 0.251      | -            | -                | -                | -         |    -1.95 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            6 |     3525 | 2024-03-14 | NRG              | L   | 0.250      | -            | -                | -                | -         |    -1.98 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            5 |     3734 | 2024-03-06 | Carpe Diem       | L   | 0.197      | -            | -                | -                | -         |    -2.91 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            4 |     3737 | 2024-03-06 | Carpe Diem       | L   | 0.197      | -            | -                | -                | -         |    -2.95 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            3 |     3982 | 2024-02-24 | NRG              | L   | 0.123      | -            | -                | -                | -         |    -0.97 | Danejoris, DooM, grape, Mellow, RiFT        |
|            2 |     3986 | 2024-02-24 | LAG              | W   | 0.123      | 0.143        | 0.012 (0.000)    | 0.340 (0.006)    | 0 (0.000) |     2.90 | Danejoris, DooM, grape, Mellow, RiFT        |
|            1 |     4203 | 2024-02-15 | OMiT             | L   | 0.064      | -            | -                | -                | -         |    -1.13 | Danejoris, DooM, grape, Mellow, RiFT        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($331.94)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
