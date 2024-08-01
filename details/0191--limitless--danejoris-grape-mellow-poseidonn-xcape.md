### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [191](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [53]( ../standings_americas.md)<br />
<br />
Final Rank Value:  585.5<br />
<br />
Final Rank Value (585.5) = Starting Rank Value (660.2) + Head To Head Adjustments (-74.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.2
- 400 + ( ( 0.126 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 660.2


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
|           40 |      979 | 2024-06-13 | Nouns            | L   | 0.876      | -            | -                | -                | -         |    -2.78 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           39 |     1008 | 2024-06-12 | Detonate         | L   | 0.870      | -            | -                | -                | -         |   -16.41 | Danejoris, DooM, grape, PoseidoNN, xCAPE    |
|           38 |     1010 | 2024-06-12 | E-Xolos LAZER    | L   | 0.869      | -            | -                | -                | -         |    -7.50 | Coastal, Danejoris, grape, PoseidoNN, xCAPE |
|           37 |     1038 | 2024-06-11 | Perseverance     | W   | 0.862      | 0.371        | 0.000 (0.000)    | 0.064 (0.021)    | 0 (0.000) |    10.97 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           36 |     1057 | 2024-06-10 | Final Form       | L   | 0.856      | -            | -                | -                | -         |   -15.73 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           35 |     1213 | 2024-06-07 | Vibe             | W   | 0.837      | 0.371        | 0.000 (0.000)    | 0.070 (0.022)    | 0 (0.000) |     6.45 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           34 |     1286 | 2024-06-06 | Homyno           | L   | 0.829      | -            | -                | -                | -         |    -9.40 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           33 |     1449 | 2024-06-03 | Asian Kings      | W   | 0.808      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.78 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           32 |     1715 | 2024-05-22 | LAG              | L   | 0.731      | -            | -                | -                | -         |    -5.22 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           31 |     1718 | 2024-05-22 | LAG              | L   | 0.730      | -            | -                | -                | -         |    -5.47 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           30 |     1768 | 2024-05-21 | Party Astronauts | L   | 0.724      | -            | -                | -                | -         |    -3.21 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           29 |     1771 | 2024-05-21 | Party Astronauts | L   | 0.724      | -            | -                | -                | -         |    -3.31 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           28 |     1852 | 2024-05-19 | Wildcard         | L   | 0.710      | -            | -                | -                | -         |    -3.34 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE  |
|           27 |     1988 | 2024-05-15 | Elevate          | L   | 0.684      | -            | -                | -                | -         |    -2.63 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           26 |     1995 | 2024-05-15 | Elevate          | L   | 0.684      | -            | -                | -                | -         |    -2.70 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           25 |     2179 | 2024-05-10 | M80              | L   | 0.651      | -            | -                | -                | -         |    -0.60 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           24 |     2180 | 2024-05-10 | M80              | L   | 0.650      | -            | -                | -                | -         |    -0.60 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           23 |     2193 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.644      | -            | -                | -                | -         |    -7.19 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           22 |     2196 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.644      | 0.477        | 0.010 (0.003)    | 0.105 (0.032)    | 0 (0.000) |    13.44 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           21 |     2214 | 2024-05-08 | Wildcard         | L   | 0.637      | -            | -                | -                | -         |    -3.24 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           20 |     2217 | 2024-05-08 | Wildcard         | L   | 0.637      | -            | -                | -                | -         |    -3.34 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           19 |     2806 | 2024-04-15 | Nouns            | L   | 0.484      | -            | -                | -                | -         |    -2.36 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           18 |     2807 | 2024-04-15 | Nouns            | L   | 0.484      | -            | -                | -                | -         |    -2.42 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           17 |     2866 | 2024-04-11 | BOSS             | L   | 0.457      | -            | -                | -                | -         |    -3.78 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           16 |     2868 | 2024-04-11 | BOSS             | L   | 0.457      | -            | -                | -                | -         |    -3.90 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           15 |     3084 | 2024-04-04 | Take Flyte       | L   | 0.411      | -            | -                | -                | -         |    -5.71 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           14 |     3088 | 2024-04-04 | Take Flyte       | W   | 0.410      | 0.477        | 0.002 (0.000)    | 0.241 (0.047)    | 0 (0.000) |     7.39 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           13 |     3131 | 2024-04-03 | Perseverance     | L   | 0.404      | -            | -                | -                | -         |    -4.97 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           12 |     3133 | 2024-04-03 | Perseverance     | L   | 0.404      | -            | -                | -                | -         |    -5.14 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           11 |     3267 | 2024-03-27 | MIGHT            | W   | 0.357      | 0.477        | 0.000 (0.000)    | 0.061 (0.010)    | 0 (0.000) |     3.83 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           10 |     3273 | 2024-03-27 | MIGHT            | W   | 0.357      | 0.477        | 0.000 (0.000)    | 0.061 (0.010)    | 0 (0.000) |     3.94 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            9 |     3318 | 2024-03-26 | Mythic           | L   | 0.351      | -            | -                | -                | -         |    -3.46 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            8 |     3323 | 2024-03-26 | Mythic           | W   | 0.351      | 0.477        | 0.010 (0.002)    | 0.304 (0.051)    | 0 (0.000) |     7.74 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            7 |     3514 | 2024-03-14 | NRG              | L   | 0.271      | -            | -                | -                | -         |    -2.08 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            6 |     3518 | 2024-03-14 | NRG              | L   | 0.271      | -            | -                | -                | -         |    -2.12 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            5 |     3733 | 2024-03-06 | Carpe Diem       | L   | 0.217      | -            | -                | -                | -         |    -3.19 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            4 |     3736 | 2024-03-06 | Carpe Diem       | L   | 0.217      | -            | -                | -                | -         |    -3.25 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            3 |     3990 | 2024-02-24 | NRG              | L   | 0.143      | -            | -                | -                | -         |    -1.13 | Danejoris, DooM, grape, Mellow, RiFT        |
|            2 |     3994 | 2024-02-24 | LAG              | W   | 0.143      | 0.143        | 0.013 (0.000)    | 0.371 (0.008)    | 0 (0.000) |     3.42 | Danejoris, DooM, grape, Mellow, RiFT        |
|            1 |     4217 | 2024-02-15 | OMiT             | L   | 0.084      | -            | -                | -                | -         |    -1.48 | Danejoris, DooM, grape, Mellow, RiFT        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($340.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
