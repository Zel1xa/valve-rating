### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [190](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  589.2<br />
<br />
Final Rank Value (589.2) = Starting Rank Value (657.6) + Head To Head Adjustments (-68.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 657.6
- 400 + ( ( 0.126 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 657.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |     1007 | 2024-06-13 | Nouns            | L   | 0.861      | -            | -                | -                | -         |    -2.85 | Danejoris, grape, Mellow, PoseidoNN, xCAPE |
|           38 |     1036 | 2024-06-12 | Detonate         | L   | 0.856      | -            | -                | -                | -         |   -16.33 | Danejoris, DooM, grape, PoseidoNN, xCAPE   |
|           37 |     1063 | 2024-06-11 | Perseverance     | W   | 0.847      | 0.371        | 0.000 (0.000)    | 0.066 (0.021)    | 0 (0.000) |    10.85 | Danejoris, grape, Mellow, PoseidoNN, xCAPE |
|           36 |     1079 | 2024-06-10 | Final Form       | L   | 0.841      | -            | -                | -                | -         |   -15.42 | Danejoris, grape, Mellow, PoseidoNN, xCAPE |
|           35 |     1224 | 2024-06-07 | Vibe             | W   | 0.822      | 0.371        | 0.000 (0.000)    | 0.073 (0.022)    | 0 (0.000) |     6.42 | Danejoris, grape, Mellow, PoseidoNN, xCAPE |
|           34 |     1291 | 2024-06-06 | Homyno           | L   | 0.814      | -            | -                | -                | -         |    -9.23 | Danejoris, grape, Mellow, PoseidoNN, xCAPE |
|           33 |     1450 | 2024-06-03 | Asian Kings      | W   | 0.793      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.77 | Danejoris, grape, Mellow, PoseidoNN, xCAPE |
|           32 |     1710 | 2024-05-22 | LAG              | L   | 0.716      | -            | -                | -                | -         |    -5.32 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           31 |     1713 | 2024-05-22 | LAG              | L   | 0.716      | -            | -                | -                | -         |    -5.57 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           30 |     1753 | 2024-05-21 | Party Astronauts | L   | 0.709      | -            | -                | -                | -         |    -3.25 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           29 |     1756 | 2024-05-21 | Party Astronauts | L   | 0.709      | -            | -                | -                | -         |    -3.36 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           28 |     1827 | 2024-05-19 | Wildcard         | L   | 0.695      | -            | -                | -                | -         |    -3.38 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE |
|           27 |     1956 | 2024-05-15 | Elevate          | L   | 0.669      | -            | -                | -                | -         |    -3.09 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           26 |     1963 | 2024-05-15 | Elevate          | L   | 0.669      | -            | -                | -                | -         |    -3.19 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           25 |     2138 | 2024-05-10 | M80              | L   | 0.636      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           24 |     2139 | 2024-05-10 | M80              | L   | 0.636      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           23 |     2152 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.629      | -            | -                | -                | -         |    -7.10 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           22 |     2155 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.629      | 0.477        | 0.010 (0.003)    | 0.106 (0.032)    | 0 (0.000) |    13.05 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           21 |     2173 | 2024-05-08 | Wildcard         | L   | 0.623      | -            | -                | -                | -         |    -3.28 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           20 |     2176 | 2024-05-08 | Wildcard         | L   | 0.622      | -            | -                | -                | -         |    -3.38 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           19 |     2748 | 2024-04-15 | Nouns            | L   | 0.469      | -            | -                | -                | -         |    -2.42 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           18 |     2749 | 2024-04-15 | Nouns            | L   | 0.469      | -            | -                | -                | -         |    -2.47 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           17 |     2807 | 2024-04-11 | BOSS             | L   | 0.442      | -            | -                | -                | -         |    -3.79 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           16 |     2809 | 2024-04-11 | BOSS             | L   | 0.442      | -            | -                | -                | -         |    -3.92 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           15 |     3025 | 2024-04-04 | Take Flyte       | L   | 0.396      | -            | -                | -                | -         |    -5.50 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           14 |     3029 | 2024-04-04 | Take Flyte       | W   | 0.396      | 0.477        | 0.002 (0.000)    | 0.249 (0.047)    | 0 (0.000) |     7.12 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           13 |     3071 | 2024-04-03 | Perseverance     | L   | 0.389      | -            | -                | -                | -         |    -4.81 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           12 |     3073 | 2024-04-03 | Perseverance     | L   | 0.389      | -            | -                | -                | -         |    -4.97 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           11 |     3200 | 2024-03-27 | MIGHT            | W   | 0.343      | 0.477        | 0.000 (0.000)    | 0.062 (0.010)    | 0 (0.000) |     3.67 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           10 |     3206 | 2024-03-27 | MIGHT            | W   | 0.343      | 0.477        | 0.000 (0.000)    | 0.062 (0.010)    | 0 (0.000) |     3.77 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            9 |     3248 | 2024-03-26 | Mythic           | L   | 0.336      | -            | -                | -                | -         |    -3.36 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            8 |     3252 | 2024-03-26 | Mythic           | W   | 0.336      | 0.477        | 0.010 (0.002)    | 0.311 (0.050)    | 0 (0.000) |     7.37 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            7 |     3436 | 2024-03-14 | NRG              | L   | 0.256      | -            | -                | -                | -         |    -1.98 | Danejoris, grape, Mellow, PoseidoNN, RiFT  |
|            6 |     3440 | 2024-03-14 | NRG              | L   | 0.256      | -            | -                | -                | -         |    -2.01 | Danejoris, grape, Mellow, PoseidoNN, RiFT  |
|            5 |     3647 | 2024-03-06 | Carpe Diem       | L   | 0.203      | -            | -                | -                | -         |    -2.99 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            4 |     3650 | 2024-03-06 | Carpe Diem       | L   | 0.203      | -            | -                | -                | -         |    -3.04 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            3 |     3895 | 2024-02-24 | NRG              | L   | 0.129      | -            | -                | -                | -         |    -1.01 | Danejoris, DooM, grape, Mellow, RiFT       |
|            2 |     3899 | 2024-02-24 | LAG              | W   | 0.128      | 0.143        | 0.012 (0.000)    | 0.353 (0.006)    | 0 (0.000) |     3.03 | Danejoris, DooM, grape, Mellow, RiFT       |
|            1 |     4115 | 2024-02-15 | OMiT             | L   | 0.069      | -            | -                | -                | -         |    -1.22 | Danejoris, DooM, grape, Mellow, RiFT       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($334.13)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
