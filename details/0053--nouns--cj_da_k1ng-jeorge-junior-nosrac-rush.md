### Roster Details<br />
Team Name: Nouns<br />
Roster: cJ dA K1nG, Jeorge, junior, nosraC, RUSH<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1039.6<br />
<br />
Final Rank Value (1039.6) = Starting Rank Value (912.9) + Head To Head Adjustments (126.6)<br />

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
|           77 |       67 | 2024-07-30 | BOSS             | W   | 1.000      | 0.477        | -                | 0.334 (0.159)    | 0 (0.000) |     7.50 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           76 |       68 | 2024-07-30 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.00 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           75 |      264 | 2024-07-24 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    12.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           74 |      268 | 2024-07-24 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    13.08 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           73 |      296 | 2024-07-23 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.32 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           72 |      298 | 2024-07-23 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.59 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           71 |      364 | 2024-07-21 | NRG              | L   | 1.000      | -            | -                | -                | -         |   -14.52 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           70 |      388 | 2024-07-20 | LAG              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.37 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           69 |      465 | 2024-07-18 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.88 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           68 |      471 | 2024-07-18 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.11 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           67 |      592 | 2024-07-16 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -23.27 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           66 |      598 | 2024-07-16 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     7.74 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           65 |      652 | 2024-07-15 | Take Flyte       | W   | 1.000      | -            | -                | -                | -         |     4.82 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           64 |      656 | 2024-07-15 | Take Flyte       | W   | 1.000      | -            | -                | -                | -         |     5.05 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           63 |      887 | 2024-06-16 | Legacy           | L   | 0.896      | -            | -                | -                | -         |   -10.68 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           62 |      891 | 2024-06-16 | Wildcard         | W   | 0.894      | 0.371        | 0.055 (0.018)    | 0.501 (0.166)    | -         |    13.76 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           61 |      921 | 2024-06-15 | E-Xolos LAZER    | W   | 0.887      | -            | -                | -                | -         |     7.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           60 |      983 | 2024-06-13 | Limitless        | W   | 0.874      | -            | -                | -                | -         |     2.78 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           59 |     1155 | 2024-06-08 | Wildcard         | L   | 0.842      | -            | -                | -                | -         |   -13.61 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           58 |     1156 | 2024-06-08 | Legacy           | L   | 0.842      | -            | -                | -                | -         |   -11.77 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           57 |     1215 | 2024-06-07 | Party Astronauts | W   | 0.836      | 0.477        | 0.042 (0.017)    | 0.532 (0.212)    | -         |    13.73 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           56 |     1225 | 2024-06-07 | Elevate          | W   | 0.835      | 0.384        | 0.027 (0.009)    | 0.505 (0.162)    | -         |    13.43 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           55 |     1229 | 2024-06-07 | Elevate          | L   | 0.834      | -            | -                | -                | -         |   -13.00 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           54 |     1246 | 2024-06-07 | Party Astronauts | L   | 0.833      | -            | -                | -                | -         |   -13.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           53 |     1276 | 2024-06-06 | Elevate          | W   | 0.829      | 0.477        | 0.027 (0.011)    | 0.505 (0.200)    | -         |    13.29 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           52 |     1348 | 2024-06-05 | M80              | L   | 0.822      | -            | -                | -                | -         |    -4.69 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           51 |     1400 | 2024-06-04 | NRG              | W   | 0.816      | 0.477        | -                | 0.519 (0.202)    | -         |    10.13 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           50 |     1412 | 2024-06-04 | TSM Shimmer      | W   | 0.815      | -            | -                | -                | -         |     4.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           49 |     1684 | 2024-05-24 | M80              | L   | 0.742      | -            | -                | -                | -         |    -4.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           48 |     1698 | 2024-05-23 | NRG              | W   | 0.736      | -            | -                | -                | -         |     9.80 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           47 |     1715 | 2024-05-22 | Party Astronauts | W   | 0.729      | 0.384        | 0.042 (0.012)    | -                | -         |    11.46 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           46 |     1771 | 2024-05-21 | FLUFFY AIMERS    | W   | 0.723      | -            | -                | -                | -         |     4.64 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           45 |     1774 | 2024-05-21 | FLUFFY AIMERS    | W   | 0.723      | -            | -                | -                | -         |     4.84 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           44 |     1864 | 2024-05-19 | FLUFFY AIMERS    | W   | 0.708      | -            | -                | -                | -         |     4.94 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           43 |     1887 | 2024-05-18 | NRG              | W   | 0.702      | -            | -                | -                | -         |    11.36 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           42 |     1888 | 2024-05-18 | M80              | W   | 0.701      | 0.303        | 0.190 (0.040)    | -                | -         |    19.33 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           41 |     1922 | 2024-05-17 | Wildcard         | W   | 0.696      | -            | -                | -                | -         |     3.78 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           40 |     1993 | 2024-05-15 | Limitless        | L   | 0.682      | -            | -                | -                | -         |   -14.85 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           39 |     1998 | 2024-05-15 | Limitless        | L   | 0.682      | -            | -                | -                | -         |   -15.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           38 |     2103 | 2024-05-13 | Wildcard         | L   | 0.669      | -            | -                | -                | -         |   -11.77 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           37 |     2104 | 2024-05-13 | Wildcard         | W   | 0.669      | 0.477        | 0.055 (0.018)    | 0.501 (0.160)    | -         |     9.45 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           36 |     2149 | 2024-05-11 | Elevate          | L   | 0.655      | -            | -                | -                | -         |    -9.20 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           35 |     2151 | 2024-05-11 | Mythic           | L   | 0.655      | -            | -                | -                | -         |   -15.01 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           34 |     2153 | 2024-05-11 | Elevate          | W   | 0.655      | -            | -                | -                | -         |    11.01 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           33 |     2198 | 2024-05-09 | BOSS             | W   | 0.642      | -            | -                | -                | -         |     6.49 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           32 |     2203 | 2024-05-09 | BOSS             | W   | 0.642      | -            | -                | -                | -         |     6.83 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           31 |     2223 | 2024-05-08 | Perseverance     | W   | 0.636      | -            | -                | -                | -         |     4.74 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           30 |     2225 | 2024-05-08 | Perseverance     | W   | 0.635      | -            | -                | -                | -         |     4.94 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           29 |     2548 | 2024-04-23 | Take Flyte       | L   | 0.536      | -            | -                | -                | -         |   -13.42 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           28 |     2550 | 2024-04-23 | Take Flyte       | W   | 0.536      | -            | -                | -                | -         |     3.42 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           27 |     2744 | 2024-04-17 | Elevate          | L   | 0.495      | -            | -                | -                | -         |    -6.78 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           26 |     2748 | 2024-04-17 | Perseverance     | W   | 0.495      | -            | -                | -                | -         |     3.72 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           25 |     2810 | 2024-04-15 | Limitless        | W   | 0.483      | -            | -                | -                | -         |     2.36 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           24 |     2811 | 2024-04-15 | Limitless        | W   | 0.482      | -            | -                | -                | -         |     2.41 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           23 |     2900 | 2024-04-10 | Elevate          | W   | 0.449      | -            | -                | -                | -         |     8.22 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           22 |     2906 | 2024-04-10 | Elevate          | W   | 0.449      | -            | -                | -                | -         |     8.54 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           21 |     2956 | 2024-04-09 | MIGHT            | W   | 0.443      | -            | -                | -                | -         |     1.40 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           20 |     2960 | 2024-04-09 | MIGHT            | W   | 0.442      | -            | -                | -                | -         |     1.42 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           19 |     3089 | 2024-04-04 | LAG              | L   | 0.409      | -            | -                | -                | -         |    -7.62 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           18 |     3093 | 2024-04-04 | LAG              | W   | 0.409      | -            | -                | -                | -         |     5.36 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           17 |     3134 | 2024-04-03 | Party Astronauts | L   | 0.403      | -            | -                | -                | -         |   -11.47 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           16 |     3191 | 2024-04-02 | BOSS             | W   | 0.396      | -            | -                | -                | -         |     4.22 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           15 |     3195 | 2024-04-02 | Party Astronauts | W   | 0.395      | -            | -                | -                | -         |     6.53 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           14 |     3270 | 2024-03-27 | NRG              | L   | 0.356      | -            | -                | -                | -         |    -6.82 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           13 |     3274 | 2024-03-27 | NRG              | W   | 0.356      | -            | -                | -                | -         |     4.47 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           12 |     3319 | 2024-03-26 | Party Astronauts | W   | 0.350      | -            | -                | -                | -         |     5.87 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           11 |     3324 | 2024-03-26 | Party Astronauts | W   | 0.349      | -            | -                | -                | -         |     6.04 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           10 |     3407 | 2024-03-20 | Mythic           | L   | 0.309      | -            | -                | -                | -         |    -6.49 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            9 |     3410 | 2024-03-20 | Mythic           | W   | 0.309      | -            | -                | -                | -         |     3.30 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            8 |     3519 | 2024-03-14 | M80              | W   | 0.269      | 0.477        | 0.065 (0.008)    | -                | -         |     1.43 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            7 |     3521 | 2024-03-14 | M80              | W   | 0.269      | -            | -                | -                | -         |     1.45 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            6 |     3860 | 2024-03-02 | Legacy           | L   | 0.188      | -            | -                | -                | -         |    -2.15 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            5 |     3889 | 2024-03-01 | FURIA            | L   | 0.181      | -            | -                | -                | -         |    -0.06 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            4 |     3954 | 2024-02-26 | Liquid           | L   | 0.156      | -            | -                | -                | -         |    -0.16 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            3 |     3971 | 2024-02-25 | BOSS             | W   | 0.149      | -            | -                | -                | -         |     1.73 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            2 |     3975 | 2024-02-25 | Liquid           | W   | 0.148      | -            | -                | -                | -         |     4.52 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            1 |     4431 | 2024-02-03 | Wildcard         | L   | 0.002      | -            | -                | -                | -         |    -0.05 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,012.82)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.896 | $4,000.00      | $3,582.78       |
| 2024-06-09 |      0.849 | $10,500.00     | $8,910.42       |
| 2024-05-24 |      0.742 | $5,000.00      | $3,711.11       |
| 2024-05-18 |      0.702 | $4,000.00      | $2,808.52       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
