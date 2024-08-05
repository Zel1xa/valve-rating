### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  583.4<br />
<br />
Final Rank Value (583.4) = Starting Rank Value (660.3) + Head To Head Adjustments (-76.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.3
- 400 + ( ( 0.126 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 660.3


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
|           40 |      944 | 2024-06-13 | Nouns            | L   | 0.880      | -            | -                | -                | -         |    -2.65 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           39 |      973 | 2024-06-12 | Detonate         | L   | 0.875      | -            | -                | -                | -         |   -16.43 | Danejoris, DooM, grape, PoseidoNN, xCAPE    |
|           38 |      975 | 2024-06-12 | E-Xolos LAZER    | L   | 0.874      | -            | -                | -                | -         |    -8.02 | Coastal, Danejoris, grape, PoseidoNN, xCAPE |
|           37 |     1002 | 2024-06-11 | Perseverance     | W   | 0.866      | 0.371        | 0.000 (0.000)    | 0.064 (0.021)    | 0 (0.000) |    11.05 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           36 |     1020 | 2024-06-10 | Final Form       | L   | 0.860      | -            | -                | -                | -         |   -15.80 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           35 |     1171 | 2024-06-07 | Vibe             | W   | 0.841      | 0.371        | 0.000 (0.000)    | 0.070 (0.022)    | 0 (0.000) |     6.51 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           34 |     1238 | 2024-06-06 | Homyno           | L   | 0.833      | -            | -                | -                | -         |    -9.42 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           33 |     1398 | 2024-06-03 | Asian Kings      | W   | 0.812      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.85 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           32 |     1661 | 2024-05-22 | LAG              | L   | 0.735      | -            | -                | -                | -         |    -5.49 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           31 |     1664 | 2024-05-22 | LAG              | L   | 0.735      | -            | -                | -                | -         |    -5.76 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           30 |     1704 | 2024-05-21 | Party Astronauts | L   | 0.728      | -            | -                | -                | -         |    -3.25 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           29 |     1707 | 2024-05-21 | Party Astronauts | L   | 0.728      | -            | -                | -                | -         |    -3.35 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           28 |     1778 | 2024-05-19 | Wildcard         | L   | 0.714      | -            | -                | -                | -         |    -3.48 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE  |
|           27 |     1908 | 2024-05-15 | Elevate          | L   | 0.688      | -            | -                | -                | -         |    -2.67 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           26 |     1915 | 2024-05-15 | Elevate          | L   | 0.688      | -            | -                | -                | -         |    -2.74 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           25 |     2090 | 2024-05-10 | M80              | L   | 0.655      | -            | -                | -                | -         |    -0.60 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           24 |     2091 | 2024-05-10 | M80              | L   | 0.655      | -            | -                | -                | -         |    -0.60 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           23 |     2104 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.648      | -            | -                | -                | -         |    -7.22 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           22 |     2107 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.648      | 0.477        | 0.010 (0.003)    | 0.105 (0.033)    | 0 (0.000) |    13.55 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           21 |     2125 | 2024-05-08 | Wildcard         | L   | 0.642      | -            | -                | -                | -         |    -3.41 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           20 |     2128 | 2024-05-08 | Wildcard         | L   | 0.641      | -            | -                | -                | -         |    -3.52 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           19 |     2702 | 2024-04-15 | Nouns            | L   | 0.489      | -            | -                | -                | -         |    -2.38 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           18 |     2703 | 2024-04-15 | Nouns            | L   | 0.488      | -            | -                | -                | -         |    -2.44 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           17 |     2761 | 2024-04-11 | BOSS             | L   | 0.461      | -            | -                | -                | -         |    -3.89 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           16 |     2763 | 2024-04-11 | BOSS             | L   | 0.461      | -            | -                | -                | -         |    -4.02 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           15 |     2979 | 2024-04-04 | Take Flyte       | L   | 0.415      | -            | -                | -                | -         |    -5.76 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           14 |     2983 | 2024-04-04 | Take Flyte       | W   | 0.415      | 0.477        | 0.002 (0.000)    | 0.241 (0.048)    | 0 (0.000) |     7.47 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           13 |     3025 | 2024-04-03 | Perseverance     | L   | 0.408      | -            | -                | -                | -         |    -5.05 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           12 |     3027 | 2024-04-03 | Perseverance     | L   | 0.408      | -            | -                | -                | -         |    -5.23 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           11 |     3154 | 2024-03-27 | MIGHT            | W   | 0.362      | 0.477        | 0.000 (0.000)    | 0.062 (0.011)    | 0 (0.000) |     3.88 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           10 |     3160 | 2024-03-27 | MIGHT            | W   | 0.362      | 0.477        | 0.000 (0.000)    | 0.062 (0.011)    | 0 (0.000) |     3.99 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            9 |     3204 | 2024-03-26 | Mythic           | L   | 0.355      | -            | -                | -                | -         |    -3.54 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            8 |     3209 | 2024-03-26 | Mythic           | W   | 0.355      | 0.477        | 0.010 (0.002)    | 0.266 (0.045)    | 0 (0.000) |     7.80 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            7 |     3396 | 2024-03-14 | NRG              | L   | 0.275      | -            | -                | -                | -         |    -2.19 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            6 |     3400 | 2024-03-14 | NRG              | L   | 0.275      | -            | -                | -                | -         |    -2.22 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            5 |     3609 | 2024-03-06 | Carpe Diem       | L   | 0.222      | -            | -                | -                | -         |    -3.26 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            4 |     3612 | 2024-03-06 | Carpe Diem       | L   | 0.222      | -            | -                | -                | -         |    -3.32 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            3 |     3857 | 2024-02-24 | NRG              | L   | 0.148      | -            | -                | -                | -         |    -1.20 | Danejoris, DooM, grape, Mellow, RiFT        |
|            2 |     3861 | 2024-02-24 | LAG              | W   | 0.147      | 0.143        | 0.013 (0.000)    | 0.344 (0.007)    | 0 (0.000) |     3.51 | Danejoris, DooM, grape, Mellow, RiFT        |
|            1 |     4078 | 2024-02-15 | OMiT             | L   | 0.088      | -            | -                | -                | -         |    -1.56 | Danejoris, DooM, grape, Mellow, RiFT        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($341.74)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
