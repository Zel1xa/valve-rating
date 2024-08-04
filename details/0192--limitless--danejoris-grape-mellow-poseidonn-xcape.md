### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [192](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [53]( ../standings_americas.md)<br />
<br />
Final Rank Value:  581.3<br />
<br />
Final Rank Value (581.3) = Starting Rank Value (656.7) + Head To Head Adjustments (-75.4)<br />

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
- 400 + ( ( 0.126 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 656.7


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
|           40 |     1092 | 2024-06-13 | Nouns            | L   | 0.855      | -            | -                | -                | -         |    -2.60 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           39 |     1121 | 2024-06-12 | Detonate         | L   | 0.849      | -            | -                | -                | -         |   -15.93 | Danejoris, DooM, grape, PoseidoNN, xCAPE    |
|           38 |     1123 | 2024-06-12 | E-Xolos LAZER    | L   | 0.849      | -            | -                | -                | -         |    -7.35 | Coastal, Danejoris, grape, PoseidoNN, xCAPE |
|           37 |     1150 | 2024-06-11 | Perseverance     | W   | 0.841      | 0.371        | 0.000 (0.000)    | 0.064 (0.020)    | 0 (0.000) |    10.80 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           36 |     1168 | 2024-06-10 | Final Form       | L   | 0.835      | -            | -                | -                | -         |   -15.27 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           35 |     1319 | 2024-06-07 | Vibe             | W   | 0.816      | 0.371        | 0.000 (0.000)    | 0.070 (0.021)    | 0 (0.000) |     6.40 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           34 |     1386 | 2024-06-06 | Homyno           | L   | 0.808      | -            | -                | -                | -         |    -9.18 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           33 |     1546 | 2024-06-03 | Asian Kings      | W   | 0.787      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.76 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           32 |     1809 | 2024-05-22 | LAG              | L   | 0.710      | -            | -                | -                | -         |    -5.59 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           31 |     1812 | 2024-05-22 | LAG              | L   | 0.709      | -            | -                | -                | -         |    -5.86 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           30 |     1852 | 2024-05-21 | Party Astronauts | L   | 0.703      | -            | -                | -                | -         |    -3.22 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           29 |     1855 | 2024-05-21 | Party Astronauts | L   | 0.703      | -            | -                | -                | -         |    -3.32 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           28 |     1926 | 2024-05-19 | Wildcard         | L   | 0.689      | -            | -                | -                | -         |    -3.86 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE  |
|           27 |     2056 | 2024-05-15 | Elevate          | L   | 0.663      | -            | -                | -                | -         |    -2.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           26 |     2063 | 2024-05-15 | Elevate          | L   | 0.663      | -            | -                | -                | -         |    -2.69 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           25 |     2238 | 2024-05-10 | M80              | L   | 0.630      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           24 |     2239 | 2024-05-10 | M80              | L   | 0.629      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           23 |     2252 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.623      | -            | -                | -                | -         |    -7.03 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           22 |     2255 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.623      | 0.477        | 0.010 (0.003)    | 0.101 (0.030)    | 0 (0.000) |    12.92 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           21 |     2273 | 2024-05-08 | Wildcard         | L   | 0.616      | -            | -                | -                | -         |    -3.66 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           20 |     2276 | 2024-05-08 | Wildcard         | L   | 0.616      | -            | -                | -                | -         |    -3.78 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           19 |     2850 | 2024-04-15 | Nouns            | L   | 0.463      | -            | -                | -                | -         |    -2.33 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           18 |     2851 | 2024-04-15 | Nouns            | L   | 0.463      | -            | -                | -                | -         |    -2.38 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           17 |     2909 | 2024-04-11 | BOSS             | L   | 0.436      | -            | -                | -                | -         |    -3.74 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           16 |     2911 | 2024-04-11 | BOSS             | L   | 0.436      | -            | -                | -                | -         |    -3.85 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           15 |     3127 | 2024-04-04 | Take Flyte       | L   | 0.390      | -            | -                | -                | -         |    -5.39 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           14 |     3131 | 2024-04-04 | Take Flyte       | W   | 0.389      | 0.477        | 0.002 (0.000)    | 0.240 (0.045)    | 0 (0.000) |     7.03 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           13 |     3173 | 2024-04-03 | Phoenix          | L   | 0.383      | -            | -                | -                | -         |    -4.76 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           12 |     3175 | 2024-04-03 | Phoenix          | L   | 0.383      | -            | -                | -                | -         |    -4.92 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           11 |     3302 | 2024-03-27 | MIGHT            | W   | 0.337      | 0.477        | 0.000 (0.000)    | 0.060 (0.010)    | 0 (0.000) |     3.60 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           10 |     3308 | 2024-03-27 | MIGHT            | W   | 0.336      | 0.477        | 0.000 (0.000)    | 0.060 (0.010)    | 0 (0.000) |     3.69 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            9 |     3352 | 2024-03-26 | Mythic           | L   | 0.330      | -            | -                | -                | -         |    -3.31 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            8 |     3357 | 2024-03-26 | Mythic           | W   | 0.330      | 0.477        | 0.010 (0.002)    | 0.299 (0.047)    | 0 (0.000) |     7.22 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            7 |     3544 | 2024-03-14 | NRG              | L   | 0.250      | -            | -                | -                | -         |    -1.94 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            6 |     3548 | 2024-03-14 | NRG              | L   | 0.250      | -            | -                | -                | -         |    -1.97 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            5 |     3757 | 2024-03-06 | Carpe Diem       | L   | 0.197      | -            | -                | -                | -         |    -2.90 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            4 |     3760 | 2024-03-06 | Carpe Diem       | L   | 0.196      | -            | -                | -                | -         |    -2.94 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            3 |     4005 | 2024-02-24 | NRG              | L   | 0.122      | -            | -                | -                | -         |    -0.97 | Danejoris, DooM, grape, Mellow, RiFT        |
|            2 |     4009 | 2024-02-24 | LAG              | W   | 0.122      | 0.143        | 0.012 (0.000)    | 0.353 (0.006)    | 0 (0.000) |     2.83 | Danejoris, DooM, grape, Mellow, RiFT        |
|            1 |     4226 | 2024-02-15 | OMiT             | L   | 0.063      | -            | -                | -                | -         |    -1.11 | Danejoris, DooM, grape, Mellow, RiFT        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($331.63)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
