### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1275.3<br />
<br />
Final Rank Value (1275.3) = Starting Rank Value (1228.1) + Head To Head Adjustments (47.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.580[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.336[<sup>2</sup>](#table1)

The average of these factors is 0.405<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1228.1
- 400 + ( ( 0.405 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1228.1


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
|           54 |      109 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      115 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.10 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      159 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     2.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      163 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     2.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      582 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.71 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      593 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.310 (0.310)    | 0.380 (0.380)    | 1 (1.000) |    27.20 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      659 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.99 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1177 | 2024-06-09 | Wildcard         | W   | 0.830      | 0.477        | 0.055 (0.022)    | 0.503 (0.199)    | -         |     4.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1190 | 2024-06-09 | NRG              | L   | 0.828      | -            | -                | -                | -         |   -22.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1247 | 2024-06-08 | Legacy           | W   | 0.822      | 0.143        | 0.122 (0.014)    | -                | -         |     5.25 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1351 | 2024-06-06 | Wildcard         | W   | 0.810      | 0.477        | 0.055 (0.021)    | 0.503 (0.194)    | -         |     4.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1367 | 2024-06-06 | Wildcard         | W   | 0.808      | -            | -                | -                | -         |     4.72 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1374 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.808      | -            | -                | -                | -         |     1.21 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1420 | 2024-06-05 | Nouns            | W   | 0.804      | 0.477        | 0.057 (0.022)    | 0.548 (0.210)    | -         |     4.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1678 | 2024-05-28 | HEROIC           | L   | 0.748      | -            | -                | -                | -         |    -3.58 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1696 | 2024-05-27 | FaZe             | L   | 0.742      | -            | -                | -                | -         |    -1.42 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1751 | 2024-05-24 | Nouns            | W   | 0.723      | 0.384        | 0.057 (0.016)    | -                | -         |     4.04 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1766 | 2024-05-23 | Wildcard         | W   | 0.716      | 0.384        | 0.055 (0.015)    | -                | -         |     3.93 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1791 | 2024-05-22 | Party Astronauts | L   | 0.710      | -            | -                | -                | -         |   -18.93 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1795 | 2024-05-22 | Party Astronauts | W   | 0.710      | 0.477        | 0.041 (0.014)    | 0.531 (0.180)    | -         |     3.28 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1801 | 2024-05-22 | Mythic           | W   | 0.709      | -            | -                | -                | -         |     1.64 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1866 | 2024-05-20 | NRG              | W   | 0.697      | 0.477        | -                | 0.521 (0.173)    | -         |     3.10 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1870 | 2024-05-20 | NRG              | W   | 0.697      | 0.477        | -                | 0.521 (0.173)    | -         |     3.19 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1881 | 2024-05-20 | E-Xolos LAZER    | W   | 0.695      | -            | -                | -                | -         |     1.45 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1904 | 2024-05-19 | BOSS             | W   | 0.690      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1905 | 2024-05-19 | BOSS             | W   | 0.689      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1930 | 2024-05-18 | Nouns            | L   | 0.683      | -            | -                | -                | -         |   -18.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     1964 | 2024-05-17 | Detonate         | W   | 0.677      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2036 | 2024-05-15 | Take Flyte       | W   | 0.664      | -            | -                | -                | -         |     0.85 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2043 | 2024-05-15 | Take Flyte       | W   | 0.663      | -            | -                | -                | -         |     0.86 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2086 | 2024-05-14 | Elevate          | W   | 0.657      | -            | -                | -                | -         |     3.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2093 | 2024-05-14 | Elevate          | W   | 0.657      | -            | -                | -                | -         |     3.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2215 | 2024-05-10 | Limitless        | W   | 0.630      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2216 | 2024-05-10 | Limitless        | W   | 0.630      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2231 | 2024-05-09 | LAG              | W   | 0.624      | -            | -                | -                | -         |     1.79 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2236 | 2024-05-09 | LAG              | W   | 0.623      | -            | -                | -                | -         |     1.82 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2463 | 2024-04-28 | G2               | L   | 0.548      | -            | -                | -                | -         |    -0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2491 | 2024-04-27 | TYLOO            | W   | 0.541      | -            | -                | -                | 1 (0.541) |     1.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2509 | 2024-04-26 | BetBoom          | L   | 0.535      | -            | -                | -                | -         |    -4.91 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2521 | 2024-04-26 | G2               | W   | 0.533      | 0.889        | 1.000 (0.474)    | 0.498 (0.236)    | 1 (0.533) |    16.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2544 | 2024-04-25 | Sharks           | W   | 0.527      | -            | -                | -                | 1 (0.527) |     1.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2578 | 2024-04-23 | BetBoom          | L   | 0.515      | -            | -                | -                | -         |    -4.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2664 | 2024-04-19 | Liquid           | W   | 0.490      | 0.143        | 0.384 (0.027)    | -                | -         |    13.64 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2671 | 2024-04-19 | Legacy           | W   | 0.489      | -            | -                | -                | -         |     3.88 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2714 | 2024-04-18 | Liquid           | L   | 0.484      | -            | -                | -                | -         |    -1.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2718 | 2024-04-18 | Elevate          | W   | 0.482      | -            | -                | -                | -         |     3.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3287 | 2024-03-27 | Perseverance     | W   | 0.337      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3293 | 2024-03-27 | Perseverance     | W   | 0.337      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3554 | 2024-03-13 | Wildcard         | L   | 0.244      | -            | -                | -                | -         |    -6.58 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3555 | 2024-03-13 | Wildcard         | W   | 0.244      | -            | -                | -                | -         |     1.11 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3811 | 2024-03-04 | Legacy           | L   | 0.181      | -            | -                | -                | -         |    -4.37 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3843 | 2024-03-03 | Wildcard         | W   | 0.174      | -            | -                | -                | 1 (0.174) |     0.80 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3857 | 2024-03-02 | Imperial         | L   | 0.168      | -            | -                | -                | -         |    -2.38 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3878 | 2024-03-01 | ODDIK            | W   | 0.162      | -            | -                | -                | 1 (0.162) |     1.09 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,029.00)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.830 | $25,000.00     | $20,745.95      |
| 2024-06-02 |      0.782 | $4,000.00      | $3,126.02       |
| 2024-05-24 |      0.723 | $20,000.00     | $14,468.98      |
| 2024-05-12 |      0.641 | $12,000.00     | $7,688.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
