### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1271.3<br />
<br />
Final Rank Value (1271.3) = Starting Rank Value (1225.0) + Head To Head Adjustments (46.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.333[<sup>2</sup>](#table1)

The average of these factors is 0.402<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1225.0
- 400 + ( ( 0.402 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1225.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |      159 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      165 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      209 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     2.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      213 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     2.16 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      632 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.65 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      643 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.373 (0.373)    | 1 (1.000) |    27.40 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      709 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1227 | 2024-06-09 | Wildcard         | W   | 0.822      | 0.477        | 0.048 (0.019)    | 0.429 (0.168)    | -         |     4.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1240 | 2024-06-09 | NRG              | L   | 0.820      | -            | -                | -                | -         |   -22.28 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1297 | 2024-06-08 | Legacy           | W   | 0.814      | 0.143        | 0.122 (0.014)    | -                | -         |     5.25 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1401 | 2024-06-06 | Wildcard         | W   | 0.802      | 0.477        | 0.048 (0.018)    | 0.429 (0.164)    | -         |     3.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1417 | 2024-06-06 | Wildcard         | W   | 0.800      | -            | -                | -                | -         |     4.18 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1424 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.800      | -            | -                | -                | -         |     1.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1470 | 2024-06-05 | Nouns            | W   | 0.795      | 0.477        | 0.057 (0.022)    | 0.553 (0.210)    | -         |     4.81 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1728 | 2024-05-28 | HEROIC           | L   | 0.740      | -            | -                | -                | -         |    -3.50 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1746 | 2024-05-27 | FaZe             | L   | 0.734      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1801 | 2024-05-24 | Nouns            | W   | 0.715      | 0.384        | 0.057 (0.016)    | -                | -         |     4.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1816 | 2024-05-23 | Wildcard         | W   | 0.708      | 0.384        | 0.048 (0.013)    | -                | -         |     3.42 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1841 | 2024-05-22 | Party Astronauts | L   | 0.702      | -            | -                | -                | -         |   -18.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1845 | 2024-05-22 | Party Astronauts | W   | 0.701      | 0.477        | 0.041 (0.014)    | 0.523 (0.175)    | -         |     3.25 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1851 | 2024-05-22 | Mythic           | W   | 0.700      | -            | -                | -                | -         |     1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1916 | 2024-05-20 | NRG              | W   | 0.689      | 0.477        | -                | 0.514 (0.169)    | -         |     3.06 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1920 | 2024-05-20 | NRG              | W   | 0.688      | 0.477        | -                | 0.514 (0.169)    | -         |     3.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1931 | 2024-05-20 | E-Xolos LAZER    | W   | 0.687      | -            | -                | -                | -         |     1.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1954 | 2024-05-19 | BOSS             | W   | 0.681      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1955 | 2024-05-19 | BOSS             | W   | 0.681      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1980 | 2024-05-18 | Nouns            | L   | 0.674      | -            | -                | -                | -         |   -18.39 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     2014 | 2024-05-17 | Detonate         | W   | 0.668      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2086 | 2024-05-15 | Take Flyte       | W   | 0.655      | -            | -                | -                | -         |     0.86 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2093 | 2024-05-15 | Take Flyte       | W   | 0.655      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2136 | 2024-05-14 | Elevate          | W   | 0.649      | -            | -                | -                | -         |     3.58 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2143 | 2024-05-14 | Elevate          | W   | 0.648      | -            | -                | -                | -         |     3.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2265 | 2024-05-10 | Limitless        | W   | 0.622      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2266 | 2024-05-10 | Limitless        | W   | 0.622      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2281 | 2024-05-09 | LAG              | W   | 0.615      | -            | -                | -                | -         |     1.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2286 | 2024-05-09 | LAG              | W   | 0.615      | -            | -                | -                | -         |     1.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2513 | 2024-04-28 | G2               | L   | 0.540      | -            | -                | -                | -         |    -0.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2541 | 2024-04-27 | TYLOO            | W   | 0.532      | -            | -                | -                | 1 (0.532) |     1.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2559 | 2024-04-26 | BetBoom          | L   | 0.527      | -            | -                | -                | -         |    -4.81 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2571 | 2024-04-26 | G2               | W   | 0.525      | 0.889        | 1.000 (0.466)    | 0.490 (0.228)    | 1 (0.525) |    16.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2594 | 2024-04-25 | Sharks           | W   | 0.519      | -            | -                | -                | 1 (0.519) |     1.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2628 | 2024-04-23 | BetBoom          | L   | 0.506      | -            | -                | -                | -         |    -4.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2714 | 2024-04-19 | Liquid           | W   | 0.482      | 0.143        | 0.383 (0.026)    | -                | -         |    13.46 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2721 | 2024-04-19 | Legacy           | W   | 0.481      | -            | -                | -                | -         |     3.83 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2764 | 2024-04-18 | Liquid           | L   | 0.475      | -            | -                | -                | -         |    -1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2768 | 2024-04-18 | Elevate          | W   | 0.474      | -            | -                | -                | -         |     3.31 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3337 | 2024-03-27 | Phoenix          | W   | 0.328      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3343 | 2024-03-27 | Phoenix          | W   | 0.328      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3604 | 2024-03-13 | Wildcard         | L   | 0.236      | -            | -                | -                | -         |    -6.50 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3605 | 2024-03-13 | Wildcard         | W   | 0.235      | -            | -                | -                | -         |     0.93 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3861 | 2024-03-04 | Legacy           | L   | 0.173      | -            | -                | -                | -         |    -4.16 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3893 | 2024-03-03 | Wildcard         | W   | 0.166      | -            | -                | -                | 1 (0.166) |     0.66 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3907 | 2024-03-02 | Imperial         | L   | 0.160      | -            | -                | -                | -         |    -2.28 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3928 | 2024-03-01 | ODDIK            | W   | 0.154      | -            | -                | -                | 1 (0.154) |     1.05 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,522.08)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.822 | $25,000.00     | $20,538.19      |
| 2024-06-02 |      0.773 | $4,000.00      | $3,092.78       |
| 2024-05-24 |      0.715 | $20,000.00     | $14,302.78      |
| 2024-05-12 |      0.632 | $12,000.00     | $7,588.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
