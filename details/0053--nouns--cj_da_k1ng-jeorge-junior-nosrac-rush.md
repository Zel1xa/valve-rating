### Roster Details<br />
Team Name: Nouns<br />
Roster: cJ dA K1nG, Jeorge, junior, nosraC, RUSH<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1039.5<br />
<br />
Final Rank Value (1039.5) = Starting Rank Value (912.9) + Head To Head Adjustments (126.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.193[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.249<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 912.9
- 400 + ( ( 0.249 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 912.9


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
|           77 |       70 | 2024-07-30 | BOSS             | W   | 1.000      | 0.477        | -                | 0.334 (0.159)    | 0 (0.000) |     7.50 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           76 |       71 | 2024-07-30 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.00 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           75 |      266 | 2024-07-24 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    12.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           74 |      270 | 2024-07-24 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    13.08 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           73 |      298 | 2024-07-23 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.32 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           72 |      300 | 2024-07-23 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.59 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           71 |      366 | 2024-07-21 | NRG              | L   | 1.000      | -            | -                | -                | -         |   -14.52 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           70 |      390 | 2024-07-20 | LAG              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.37 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           69 |      467 | 2024-07-18 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.88 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           68 |      473 | 2024-07-18 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.11 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           67 |      594 | 2024-07-16 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -23.27 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           66 |      600 | 2024-07-16 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     7.74 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           65 |      654 | 2024-07-15 | Take Flyte       | W   | 1.000      | -            | -                | -                | -         |     4.82 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           64 |      658 | 2024-07-15 | Take Flyte       | W   | 1.000      | -            | -                | -                | -         |     5.05 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           63 |      889 | 2024-06-16 | Legacy           | L   | 0.895      | -            | -                | -                | -         |   -10.68 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           62 |      893 | 2024-06-16 | Wildcard         | W   | 0.894      | 0.371        | 0.055 (0.018)    | 0.501 (0.166)    | -         |    13.76 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           61 |      923 | 2024-06-15 | E-Xolos LAZER    | W   | 0.887      | -            | -                | -                | -         |     7.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           60 |      985 | 2024-06-13 | Limitless        | W   | 0.874      | -            | -                | -                | -         |     2.78 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           59 |     1157 | 2024-06-08 | Wildcard         | L   | 0.842      | -            | -                | -                | -         |   -13.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           58 |     1158 | 2024-06-08 | Legacy           | L   | 0.842      | -            | -                | -                | -         |   -11.77 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           57 |     1217 | 2024-06-07 | Party Astronauts | W   | 0.835      | 0.477        | 0.042 (0.017)    | 0.532 (0.212)    | -         |    13.73 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           56 |     1227 | 2024-06-07 | Elevate          | W   | 0.834      | 0.384        | 0.027 (0.009)    | 0.505 (0.162)    | -         |    13.43 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           55 |     1231 | 2024-06-07 | Elevate          | L   | 0.834      | -            | -                | -                | -         |   -12.99 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           54 |     1248 | 2024-06-07 | Party Astronauts | L   | 0.833      | -            | -                | -                | -         |   -13.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           53 |     1278 | 2024-06-06 | Elevate          | W   | 0.829      | 0.477        | 0.027 (0.011)    | 0.505 (0.200)    | -         |    13.28 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           52 |     1350 | 2024-06-05 | M80              | L   | 0.822      | -            | -                | -                | -         |    -4.69 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           51 |     1402 | 2024-06-04 | NRG              | W   | 0.816      | 0.477        | -                | 0.519 (0.202)    | -         |    10.13 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           50 |     1414 | 2024-06-04 | TSM Shimmer      | W   | 0.814      | -            | -                | -                | -         |     4.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           49 |     1686 | 2024-05-24 | M80              | L   | 0.742      | -            | -                | -                | -         |    -4.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           48 |     1700 | 2024-05-23 | NRG              | W   | 0.735      | -            | -                | -                | -         |     9.80 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           47 |     1717 | 2024-05-22 | Party Astronauts | W   | 0.729      | 0.384        | 0.042 (0.012)    | -                | -         |    11.46 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           46 |     1773 | 2024-05-21 | FLUFFY AIMERS    | W   | 0.722      | -            | -                | -                | -         |     4.64 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           45 |     1776 | 2024-05-21 | FLUFFY AIMERS    | W   | 0.722      | -            | -                | -                | -         |     4.83 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           44 |     1866 | 2024-05-19 | FLUFFY AIMERS    | W   | 0.707      | -            | -                | -                | -         |     4.94 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           43 |     1889 | 2024-05-18 | NRG              | W   | 0.702      | -            | -                | -                | -         |    11.36 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           42 |     1890 | 2024-05-18 | M80              | W   | 0.701      | 0.303        | 0.190 (0.040)    | -                | -         |    19.32 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           41 |     1924 | 2024-05-17 | Wildcard         | W   | 0.695      | -            | -                | -                | -         |     3.76 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           40 |     1995 | 2024-05-15 | Limitless        | L   | 0.682      | -            | -                | -                | -         |   -14.84 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           39 |     2000 | 2024-05-15 | Limitless        | L   | 0.682      | -            | -                | -                | -         |   -15.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           38 |     2105 | 2024-05-13 | Wildcard         | L   | 0.669      | -            | -                | -                | -         |   -11.76 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           37 |     2106 | 2024-05-13 | Wildcard         | W   | 0.669      | 0.477        | 0.055 (0.018)    | 0.501 (0.160)    | -         |     9.44 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           36 |     2151 | 2024-05-11 | Elevate          | L   | 0.655      | -            | -                | -                | -         |    -9.20 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           35 |     2153 | 2024-05-11 | Mythic           | L   | 0.655      | -            | -                | -                | -         |   -15.00 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           34 |     2155 | 2024-05-11 | Elevate          | W   | 0.655      | -            | -                | -                | -         |    11.01 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           33 |     2200 | 2024-05-09 | BOSS             | W   | 0.642      | -            | -                | -                | -         |     6.49 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           32 |     2205 | 2024-05-09 | BOSS             | W   | 0.642      | -            | -                | -                | -         |     6.82 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           31 |     2225 | 2024-05-08 | Perseverance     | W   | 0.635      | -            | -                | -                | -         |     4.74 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           30 |     2227 | 2024-05-08 | Perseverance     | W   | 0.635      | -            | -                | -                | -         |     4.94 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           29 |     2550 | 2024-04-23 | Take Flyte       | L   | 0.536      | -            | -                | -                | -         |   -13.42 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           28 |     2552 | 2024-04-23 | Take Flyte       | W   | 0.535      | -            | -                | -                | -         |     3.42 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           27 |     2746 | 2024-04-17 | Elevate          | L   | 0.495      | -            | -                | -                | -         |    -6.78 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           26 |     2750 | 2024-04-17 | Perseverance     | W   | 0.494      | -            | -                | -                | -         |     3.72 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           25 |     2812 | 2024-04-15 | Limitless        | W   | 0.482      | -            | -                | -                | -         |     2.36 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           24 |     2813 | 2024-04-15 | Limitless        | W   | 0.482      | -            | -                | -                | -         |     2.41 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           23 |     2902 | 2024-04-10 | Elevate          | W   | 0.449      | -            | -                | -                | -         |     8.21 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           22 |     2908 | 2024-04-10 | Elevate          | W   | 0.449      | -            | -                | -                | -         |     8.53 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           21 |     2958 | 2024-04-09 | MIGHT            | W   | 0.442      | -            | -                | -                | -         |     1.40 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           20 |     2962 | 2024-04-09 | MIGHT            | W   | 0.442      | -            | -                | -                | -         |     1.42 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           19 |     3091 | 2024-04-04 | LAG              | L   | 0.409      | -            | -                | -                | -         |    -7.62 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           18 |     3095 | 2024-04-04 | LAG              | W   | 0.409      | -            | -                | -                | -         |     5.36 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           17 |     3136 | 2024-04-03 | Party Astronauts | L   | 0.402      | -            | -                | -                | -         |   -11.46 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           16 |     3193 | 2024-04-02 | BOSS             | W   | 0.396      | -            | -                | -                | -         |     4.22 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           15 |     3197 | 2024-04-02 | Party Astronauts | W   | 0.394      | -            | -                | -                | -         |     6.52 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           14 |     3272 | 2024-03-27 | NRG              | L   | 0.356      | -            | -                | -                | -         |    -6.81 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           13 |     3276 | 2024-03-27 | NRG              | W   | 0.356      | -            | -                | -                | -         |     4.47 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           12 |     3321 | 2024-03-26 | Party Astronauts | W   | 0.349      | -            | -                | -                | -         |     5.86 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           11 |     3326 | 2024-03-26 | Party Astronauts | W   | 0.349      | -            | -                | -                | -         |     6.04 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           10 |     3409 | 2024-03-20 | Mythic           | L   | 0.309      | -            | -                | -                | -         |    -6.48 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            9 |     3412 | 2024-03-20 | Mythic           | W   | 0.309      | -            | -                | -                | -         |     3.29 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            8 |     3521 | 2024-03-14 | M80              | W   | 0.269      | 0.477        | 0.065 (0.008)    | -                | -         |     1.43 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            7 |     3523 | 2024-03-14 | M80              | W   | 0.269      | -            | -                | -                | -         |     1.45 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            6 |     3862 | 2024-03-02 | Legacy           | L   | 0.187      | -            | -                | -                | -         |    -2.15 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            5 |     3891 | 2024-03-01 | FURIA            | L   | 0.180      | -            | -                | -                | -         |    -0.06 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            4 |     3956 | 2024-02-26 | Liquid           | L   | 0.156      | -            | -                | -                | -         |    -0.16 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            3 |     3973 | 2024-02-25 | BOSS             | W   | 0.149      | -            | -                | -                | -         |     1.73 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            2 |     3977 | 2024-02-25 | Liquid           | W   | 0.148      | -            | -                | -                | -         |     4.51 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            1 |     4433 | 2024-02-03 | Wildcard         | L   | 0.002      | -            | -                | -                | -         |    -0.05 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,006.30)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.895 | $4,000.00      | $3,581.67       |
| 2024-06-09 |      0.848 | $10,500.00     | $8,907.50       |
| 2024-05-24 |      0.742 | $5,000.00      | $3,709.72       |
| 2024-05-18 |      0.702 | $4,000.00      | $2,807.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
