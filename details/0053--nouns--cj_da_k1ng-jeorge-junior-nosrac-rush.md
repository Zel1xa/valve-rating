### Roster Details<br />
Team Name: Nouns<br />
Roster: cJ dA K1nG, Jeorge, junior, nosraC, RUSH<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1040.2<br />
<br />
Final Rank Value (1040.2) = Starting Rank Value (913.6) + Head To Head Adjustments (126.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.193[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.249<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.6
- 400 + ( ( 0.249 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 913.6


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
|           77 |       63 | 2024-07-30 | BOSS             | W   | 1.000      | 0.477        | -                | 0.334 (0.159)    | 0 (0.000) |     7.49 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           76 |       64 | 2024-07-30 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.00 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           75 |      260 | 2024-07-24 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    12.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           74 |      264 | 2024-07-24 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    13.08 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           73 |      292 | 2024-07-23 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.32 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           72 |      294 | 2024-07-23 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.59 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           71 |      360 | 2024-07-21 | NRG              | L   | 1.000      | -            | -                | -                | -         |   -14.52 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           70 |      384 | 2024-07-20 | LAG              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.37 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           69 |      461 | 2024-07-18 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.87 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           68 |      467 | 2024-07-18 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           67 |      588 | 2024-07-16 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -23.27 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           66 |      594 | 2024-07-16 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     7.73 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           65 |      648 | 2024-07-15 | Take Flyte       | W   | 1.000      | -            | -                | -                | -         |     4.82 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           64 |      652 | 2024-07-15 | Take Flyte       | W   | 1.000      | -            | -                | -                | -         |     5.05 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           63 |      883 | 2024-06-16 | Legacy           | L   | 0.897      | -            | -                | -                | -         |   -10.69 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           62 |      887 | 2024-06-16 | Wildcard         | W   | 0.895      | 0.371        | 0.055 (0.018)    | 0.501 (0.166)    | -         |    13.78 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           61 |      917 | 2024-06-15 | E-Xolos LAZER    | W   | 0.888      | -            | -                | -                | -         |     7.03 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           60 |      979 | 2024-06-13 | Limitless        | W   | 0.876      | -            | -                | -                | -         |     2.78 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           59 |     1151 | 2024-06-08 | Wildcard         | L   | 0.844      | -            | -                | -                | -         |   -13.63 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           58 |     1152 | 2024-06-08 | Legacy           | L   | 0.843      | -            | -                | -                | -         |   -11.79 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           57 |     1211 | 2024-06-07 | Party Astronauts | W   | 0.837      | 0.477        | 0.042 (0.017)    | 0.532 (0.212)    | -         |    13.76 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           56 |     1221 | 2024-06-07 | Elevate          | W   | 0.836      | 0.384        | 0.027 (0.009)    | 0.505 (0.162)    | -         |    13.45 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           55 |     1225 | 2024-06-07 | Elevate          | L   | 0.836      | -            | -                | -                | -         |   -13.02 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           54 |     1242 | 2024-06-07 | Party Astronauts | L   | 0.835      | -            | -                | -                | -         |   -13.62 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           53 |     1272 | 2024-06-06 | Elevate          | W   | 0.830      | 0.477        | 0.027 (0.011)    | 0.505 (0.200)    | -         |    13.31 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           52 |     1344 | 2024-06-05 | M80              | L   | 0.824      | -            | -                | -                | -         |    -4.72 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           51 |     1396 | 2024-06-04 | NRG              | W   | 0.817      | 0.477        | -                | 0.519 (0.202)    | -         |    10.15 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           50 |     1408 | 2024-06-04 | TSM Shimmer      | W   | 0.816      | -            | -                | -                | -         |     4.60 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           49 |     1680 | 2024-05-24 | M80              | L   | 0.744      | -            | -                | -                | -         |    -4.04 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           48 |     1694 | 2024-05-23 | NRG              | W   | 0.737      | -            | -                | -                | -         |     9.82 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           47 |     1711 | 2024-05-22 | Party Astronauts | W   | 0.731      | 0.384        | 0.042 (0.012)    | -                | -         |    11.48 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           46 |     1767 | 2024-05-21 | FLUFFY AIMERS    | W   | 0.724      | -            | -                | -                | -         |     4.64 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           45 |     1770 | 2024-05-21 | FLUFFY AIMERS    | W   | 0.724      | -            | -                | -                | -         |     4.84 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           44 |     1860 | 2024-05-19 | FLUFFY AIMERS    | W   | 0.709      | -            | -                | -                | -         |     4.95 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           43 |     1883 | 2024-05-18 | NRG              | W   | 0.704      | -            | -                | -                | -         |    11.38 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           42 |     1884 | 2024-05-18 | M80              | W   | 0.703      | 0.303        | 0.190 (0.040)    | -                | -         |    19.36 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           41 |     1918 | 2024-05-17 | Wildcard         | W   | 0.697      | -            | -                | -                | -         |     3.83 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           40 |     1989 | 2024-05-15 | Limitless        | L   | 0.684      | -            | -                | -                | -         |   -14.88 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           39 |     1994 | 2024-05-15 | Limitless        | L   | 0.684      | -            | -                | -                | -         |   -15.64 | cJ dA K1nG, Jeorge, junior, nosraC, RUSH   |
|           38 |     2099 | 2024-05-13 | Wildcard         | L   | 0.671      | -            | -                | -                | -         |   -11.79 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           37 |     2100 | 2024-05-13 | Wildcard         | W   | 0.670      | 0.477        | 0.055 (0.018)    | 0.501 (0.160)    | -         |     9.47 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           36 |     2145 | 2024-05-11 | Elevate          | L   | 0.657      | -            | -                | -                | -         |    -9.21 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           35 |     2147 | 2024-05-11 | Mythic           | L   | 0.657      | -            | -                | -                | -         |   -15.04 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           34 |     2149 | 2024-05-11 | Elevate          | W   | 0.656      | -            | -                | -                | -         |    11.04 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           33 |     2194 | 2024-05-09 | BOSS             | W   | 0.644      | -            | -                | -                | -         |     6.50 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           32 |     2199 | 2024-05-09 | BOSS             | W   | 0.644      | -            | -                | -                | -         |     6.83 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           31 |     2219 | 2024-05-08 | Perseverance     | W   | 0.637      | -            | -                | -                | -         |     4.75 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           30 |     2221 | 2024-05-08 | Perseverance     | W   | 0.637      | -            | -                | -                | -         |     4.95 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           29 |     2544 | 2024-04-23 | Take Flyte       | L   | 0.537      | -            | -                | -                | -         |   -13.46 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           28 |     2546 | 2024-04-23 | Take Flyte       | W   | 0.537      | -            | -                | -                | -         |     3.43 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           27 |     2740 | 2024-04-17 | Elevate          | L   | 0.497      | -            | -                | -                | -         |    -6.80 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           26 |     2744 | 2024-04-17 | Perseverance     | W   | 0.496      | -            | -                | -                | -         |     3.73 | cJ dA K1nG, CLASIA, Jeorge, junior, nosraC |
|           25 |     2806 | 2024-04-15 | Limitless        | W   | 0.484      | -            | -                | -                | -         |     2.36 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           24 |     2807 | 2024-04-15 | Limitless        | W   | 0.484      | -            | -                | -                | -         |     2.42 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           23 |     2896 | 2024-04-10 | Elevate          | W   | 0.451      | -            | -                | -                | -         |     8.25 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           22 |     2902 | 2024-04-10 | Elevate          | W   | 0.450      | -            | -                | -                | -         |     8.57 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           21 |     2952 | 2024-04-09 | MIGHT            | W   | 0.444      | -            | -                | -                | -         |     1.40 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           20 |     2956 | 2024-04-09 | MIGHT            | W   | 0.444      | -            | -                | -                | -         |     1.42 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           19 |     3085 | 2024-04-04 | LAG              | L   | 0.411      | -            | -                | -                | -         |    -7.64 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           18 |     3089 | 2024-04-04 | LAG              | W   | 0.410      | -            | -                | -                | -         |     5.38 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           17 |     3130 | 2024-04-03 | Party Astronauts | L   | 0.404      | -            | -                | -                | -         |   -11.51 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           16 |     3187 | 2024-04-02 | BOSS             | W   | 0.397      | -            | -                | -                | -         |     4.24 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           15 |     3191 | 2024-04-02 | Party Astronauts | W   | 0.396      | -            | -                | -                | -         |     6.55 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           14 |     3266 | 2024-03-27 | NRG              | L   | 0.358      | -            | -                | -                | -         |    -6.84 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           13 |     3270 | 2024-03-27 | NRG              | W   | 0.357      | -            | -                | -                | -         |     4.49 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           12 |     3315 | 2024-03-26 | Party Astronauts | W   | 0.351      | -            | -                | -                | -         |     5.89 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           11 |     3320 | 2024-03-26 | Party Astronauts | W   | 0.351      | -            | -                | -                | -         |     6.07 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|           10 |     3403 | 2024-03-20 | Mythic           | L   | 0.311      | -            | -                | -                | -         |    -6.51 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            9 |     3406 | 2024-03-20 | Mythic           | W   | 0.310      | -            | -                | -                | -         |     3.31 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            8 |     3515 | 2024-03-14 | M80              | W   | 0.271      | 0.477        | 0.065 (0.008)    | -                | -         |     1.44 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            7 |     3517 | 2024-03-14 | M80              | W   | 0.271      | -            | -                | -                | -         |     1.45 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            6 |     3856 | 2024-03-02 | Legacy           | L   | 0.189      | -            | -                | -                | -         |    -2.16 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            5 |     3885 | 2024-03-01 | FURIA            | L   | 0.182      | -            | -                | -                | -         |    -0.06 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            4 |     3950 | 2024-02-26 | Liquid           | L   | 0.157      | -            | -                | -                | -         |    -0.24 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            3 |     3967 | 2024-02-25 | BOSS             | W   | 0.151      | -            | -                | -                | -         |     1.75 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            2 |     3971 | 2024-02-25 | Liquid           | W   | 0.150      | -            | -                | -                | -         |     4.49 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |
|            1 |     4427 | 2024-02-03 | Wildcard         | L   | 0.003      | -            | -                | -                | -         |    -0.09 | cJ dA K1nG, Jeorge, junior, MarKE, nosraC  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,045.46)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.897 | $4,000.00      | $3,588.33       |
| 2024-06-09 |      0.850 | $10,500.00     | $8,925.00       |
| 2024-05-24 |      0.744 | $5,000.00      | $3,718.06       |
| 2024-05-18 |      0.704 | $4,000.00      | $2,814.07       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
