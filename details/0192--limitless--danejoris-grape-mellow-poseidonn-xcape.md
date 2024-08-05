### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [192](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [53]( ../standings_americas.md)<br />
<br />
Final Rank Value:  581.9<br />
<br />
Final Rank Value (581.9) = Starting Rank Value (656.6) + Head To Head Adjustments (-74.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.6
- 400 + ( ( 0.125 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 656.6


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
|           40 |     1110 | 2024-06-13 | Nouns            | L   | 0.849      | -            | -                | -                | -         |    -2.60 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           39 |     1139 | 2024-06-12 | Detonate         | L   | 0.843      | -            | -                | -                | -         |   -15.84 | Danejoris, DooM, grape, PoseidoNN, xCAPE    |
|           38 |     1141 | 2024-06-12 | E-Xolos LAZER    | L   | 0.843      | -            | -                | -                | -         |    -7.29 | Coastal, Danejoris, grape, PoseidoNN, xCAPE |
|           37 |     1168 | 2024-06-11 | Perseverance     | W   | 0.835      | 0.371        | 0.000 (0.000)    | 0.064 (0.020)    | 0 (0.000) |    10.71 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           36 |     1186 | 2024-06-10 | Final Form       | L   | 0.829      | -            | -                | -                | -         |   -14.97 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           35 |     1337 | 2024-06-07 | Vibe             | W   | 0.810      | 0.371        | 0.000 (0.000)    | 0.070 (0.021)    | 0 (0.000) |     6.34 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           34 |     1404 | 2024-06-06 | Homyno           | L   | 0.802      | -            | -                | -                | -         |    -9.13 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           33 |     1564 | 2024-06-03 | Asian Kings      | W   | 0.781      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.71 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           32 |     1827 | 2024-05-22 | LAG              | L   | 0.704      | -            | -                | -                | -         |    -5.56 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           31 |     1830 | 2024-05-22 | LAG              | L   | 0.703      | -            | -                | -                | -         |    -5.83 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           30 |     1870 | 2024-05-21 | Party Astronauts | L   | 0.697      | -            | -                | -                | -         |    -3.19 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           29 |     1873 | 2024-05-21 | Party Astronauts | L   | 0.697      | -            | -                | -                | -         |    -3.29 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           28 |     1944 | 2024-05-19 | Wildcard         | L   | 0.683      | -            | -                | -                | -         |    -3.85 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE  |
|           27 |     2074 | 2024-05-15 | Elevate          | L   | 0.657      | -            | -                | -                | -         |    -2.61 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           26 |     2081 | 2024-05-15 | Elevate          | L   | 0.657      | -            | -                | -                | -         |    -2.67 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           25 |     2256 | 2024-05-10 | M80              | L   | 0.624      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           24 |     2257 | 2024-05-10 | M80              | L   | 0.623      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           23 |     2270 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.617      | -            | -                | -                | -         |    -6.98 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           22 |     2273 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.617      | 0.477        | 0.010 (0.003)    | 0.100 (0.029)    | 0 (0.000) |    12.78 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           21 |     2291 | 2024-05-08 | Wildcard         | L   | 0.610      | -            | -                | -                | -         |    -3.65 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           20 |     2294 | 2024-05-08 | Wildcard         | L   | 0.610      | -            | -                | -                | -         |    -3.77 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           19 |     2868 | 2024-04-15 | Nouns            | L   | 0.457      | -            | -                | -                | -         |    -2.31 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           18 |     2869 | 2024-04-15 | Nouns            | L   | 0.457      | -            | -                | -                | -         |    -2.36 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           17 |     2927 | 2024-04-11 | BOSS             | L   | 0.430      | -            | -                | -                | -         |    -3.70 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           16 |     2929 | 2024-04-11 | BOSS             | L   | 0.430      | -            | -                | -                | -         |    -3.81 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           15 |     3145 | 2024-04-04 | Take Flyte       | L   | 0.384      | -            | -                | -                | -         |    -5.31 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           14 |     3149 | 2024-04-04 | Take Flyte       | W   | 0.383      | 0.477        | 0.002 (0.000)    | 0.239 (0.044)    | 0 (0.000) |     6.92 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           13 |     3191 | 2024-04-03 | Phoenix          | L   | 0.377      | -            | -                | -                | -         |    -4.68 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           12 |     3193 | 2024-04-03 | Phoenix          | L   | 0.377      | -            | -                | -                | -         |    -4.83 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           11 |     3320 | 2024-03-27 | MIGHT            | W   | 0.331      | 0.477        | 0.000 (0.000)    | 0.059 (0.009)    | 0 (0.000) |     3.52 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           10 |     3326 | 2024-03-27 | MIGHT            | W   | 0.330      | 0.477        | 0.000 (0.000)    | 0.059 (0.009)    | 0 (0.000) |     3.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            9 |     3370 | 2024-03-26 | Mythic           | L   | 0.324      | -            | -                | -                | -         |    -3.25 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            8 |     3375 | 2024-03-26 | Mythic           | W   | 0.324      | 0.477        | 0.010 (0.001)    | 0.297 (0.046)    | 0 (0.000) |     7.08 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            7 |     3562 | 2024-03-14 | NRG              | L   | 0.244      | -            | -                | -                | -         |    -1.89 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            6 |     3566 | 2024-03-14 | NRG              | L   | 0.244      | -            | -                | -                | -         |    -1.92 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            5 |     3775 | 2024-03-06 | Carpe Diem       | L   | 0.191      | -            | -                | -                | -         |    -2.81 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            4 |     3778 | 2024-03-06 | Carpe Diem       | L   | 0.190      | -            | -                | -                | -         |    -2.85 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            3 |     4023 | 2024-02-24 | NRG              | L   | 0.116      | -            | -                | -                | -         |    -0.92 | Danejoris, DooM, grape, Mellow, RiFT        |
|            2 |     4027 | 2024-02-24 | LAG              | W   | 0.116      | 0.143        | 0.012 (0.000)    | 0.351 (0.006)    | 0 (0.000) |     2.69 | Danejoris, DooM, grape, Mellow, RiFT        |
|            1 |     4244 | 2024-02-15 | OMiT             | L   | 0.057      | -            | -                | -                | -         |    -1.00 | Danejoris, DooM, grape, Mellow, RiFT        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($329.22)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
