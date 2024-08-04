### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1274.6<br />
<br />
Final Rank Value (1274.6) = Starting Rank Value (1228.6) + Head To Head Adjustments (46.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.580[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.337[<sup>2</sup>](#table1)

The average of these factors is 0.405<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1228.6
- 400 + ( ( 0.405 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1228.6


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
|           54 |       98 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      104 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      148 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     2.07 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      152 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     2.12 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      571 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.75 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      582 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.311 (0.311)    | 0.380 (0.380)    | 1 (1.000) |    27.18 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      648 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -1.01 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1165 | 2024-06-09 | Wildcard         | W   | 0.834      | 0.477        | 0.055 (0.022)    | 0.502 (0.200)    | -         |     4.75 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1178 | 2024-06-09 | NRG              | L   | 0.832      | -            | -                | -                | -         |   -22.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1235 | 2024-06-08 | Legacy           | W   | 0.826      | 0.143        | 0.122 (0.014)    | -                | -         |     5.31 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1339 | 2024-06-06 | Wildcard         | W   | 0.814      | 0.477        | 0.055 (0.021)    | 0.502 (0.195)    | -         |     4.28 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1355 | 2024-06-06 | Wildcard         | W   | 0.812      | -            | -                | -                | -         |     4.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1362 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.812      | -            | -                | -                | -         |     1.22 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1408 | 2024-06-05 | Nouns            | W   | 0.807      | 0.477        | 0.057 (0.022)    | 0.547 (0.211)    | -         |     4.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1666 | 2024-05-28 | HEROIC           | L   | 0.752      | -            | -                | -                | -         |    -3.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1684 | 2024-05-27 | FaZe             | L   | 0.746      | -            | -                | -                | -         |    -1.43 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1739 | 2024-05-24 | Nouns            | W   | 0.727      | 0.384        | 0.057 (0.016)    | -                | -         |     4.09 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1754 | 2024-05-23 | Wildcard         | W   | 0.720      | 0.384        | 0.055 (0.015)    | -                | -         |     3.98 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1779 | 2024-05-22 | Party Astronauts | L   | 0.714      | -            | -                | -                | -         |   -19.01 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1783 | 2024-05-22 | Party Astronauts | W   | 0.713      | 0.477        | 0.041 (0.014)    | 0.532 (0.181)    | -         |     3.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1789 | 2024-05-22 | Mythic           | W   | 0.713      | -            | -                | -                | -         |     1.66 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1854 | 2024-05-20 | NRG              | W   | 0.701      | 0.477        | -                | 0.521 (0.174)    | -         |     3.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1858 | 2024-05-20 | NRG              | W   | 0.701      | 0.477        | -                | 0.521 (0.174)    | -         |     3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1869 | 2024-05-20 | E-Xolos LAZER    | W   | 0.699      | -            | -                | -                | -         |     1.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1892 | 2024-05-19 | BOSS             | W   | 0.693      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1893 | 2024-05-19 | BOSS             | W   | 0.693      | -            | -                | -                | -         |     1.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1918 | 2024-05-18 | Nouns            | L   | 0.686      | -            | -                | -                | -         |   -18.82 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     1952 | 2024-05-17 | Detonate         | W   | 0.680      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2024 | 2024-05-15 | Take Flyte       | W   | 0.667      | -            | -                | -                | -         |     0.86 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2031 | 2024-05-15 | Take Flyte       | W   | 0.667      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2074 | 2024-05-14 | Elevate          | W   | 0.661      | -            | -                | -                | -         |     3.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2081 | 2024-05-14 | Elevate          | W   | 0.661      | -            | -                | -                | -         |     3.74 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2203 | 2024-05-10 | Limitless        | W   | 0.634      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2204 | 2024-05-10 | Limitless        | W   | 0.634      | -            | -                | -                | -         |     0.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2219 | 2024-05-09 | LAG              | W   | 0.627      | -            | -                | -                | -         |     1.81 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2224 | 2024-05-09 | LAG              | W   | 0.627      | -            | -                | -                | -         |     1.84 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2451 | 2024-04-28 | G2               | L   | 0.552      | -            | -                | -                | -         |    -0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2479 | 2024-04-27 | TYLOO            | W   | 0.544      | -            | -                | -                | 1 (0.544) |     1.12 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2497 | 2024-04-26 | BetBoom          | L   | 0.539      | -            | -                | -                | -         |    -4.90 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2508 | 2024-04-26 | G2               | W   | 0.537      | 0.889        | 1.000 (0.477)    | 0.498 (0.238)    | 1 (0.537) |    16.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2531 | 2024-04-25 | Sharks           | W   | 0.531      | -            | -                | -                | 1 (0.531) |     1.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2565 | 2024-04-23 | BetBoom          | L   | 0.518      | -            | -                | -                | -         |    -4.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2651 | 2024-04-19 | Liquid           | W   | 0.494      | 0.143        | 0.316 (0.022)    | -                | -         |    12.85 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2658 | 2024-04-19 | Legacy           | W   | 0.493      | -            | -                | -                | -         |     3.93 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2701 | 2024-04-18 | Liquid           | L   | 0.487      | -            | -                | -                | -         |    -2.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2705 | 2024-04-18 | Elevate          | W   | 0.486      | -            | -                | -                | -         |     3.31 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3274 | 2024-03-27 | Perseverance     | W   | 0.340      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3280 | 2024-03-27 | Perseverance     | W   | 0.340      | -            | -                | -                | -         |     0.67 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3541 | 2024-03-13 | Wildcard         | L   | 0.248      | -            | -                | -                | -         |    -6.68 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3542 | 2024-03-13 | Wildcard         | W   | 0.247      | -            | -                | -                | -         |     1.13 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3797 | 2024-03-04 | Legacy           | L   | 0.185      | -            | -                | -                | -         |    -4.45 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3829 | 2024-03-03 | Wildcard         | W   | 0.178      | -            | -                | -                | 1 (0.178) |     0.82 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3843 | 2024-03-02 | Imperial         | L   | 0.172      | -            | -                | -                | -         |    -2.42 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3864 | 2024-03-01 | ODDIK            | W   | 0.166      | -            | -                | -                | 1 (0.166) |     1.12 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,259.17)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.834 | $25,000.00     | $20,840.28      |
| 2024-06-02 |      0.785 | $4,000.00      | $3,141.11       |
| 2024-05-24 |      0.727 | $20,000.00     | $14,544.44      |
| 2024-05-12 |      0.644 | $12,000.00     | $7,733.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
