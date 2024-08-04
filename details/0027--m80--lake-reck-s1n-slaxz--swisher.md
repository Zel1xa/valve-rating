### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1274.0<br />
<br />
Final Rank Value (1274.0) = Starting Rank Value (1227.9) + Head To Head Adjustments (46.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.580[<sup>1</sup>](#table2)
- Bounty Collected: 0.492[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.336[<sup>2</sup>](#table1)

The average of these factors is 0.405<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1227.9
- 400 + ( ( 0.405 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1227.9


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
|           54 |      101 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.10 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      107 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      151 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     2.08 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      155 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     2.12 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      574 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.74 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      585 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.310 (0.310)    | 0.380 (0.380)    | 1 (1.000) |    27.17 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      651 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -1.01 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1169 | 2024-06-09 | Wildcard         | W   | 0.831      | 0.477        | 0.055 (0.022)    | 0.503 (0.199)    | -         |     4.74 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1182 | 2024-06-09 | NRG              | L   | 0.829      | -            | -                | -                | -         |   -22.51 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1239 | 2024-06-08 | Legacy           | W   | 0.823      | 0.143        | 0.122 (0.014)    | -                | -         |     5.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1343 | 2024-06-06 | Wildcard         | W   | 0.811      | 0.477        | 0.055 (0.021)    | 0.503 (0.194)    | -         |     4.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1359 | 2024-06-06 | Wildcard         | W   | 0.809      | -            | -                | -                | -         |     4.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1366 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.809      | -            | -                | -                | -         |     1.22 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1412 | 2024-06-05 | Nouns            | W   | 0.804      | 0.477        | 0.057 (0.022)    | 0.548 (0.210)    | -         |     4.75 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1670 | 2024-05-28 | HEROIC           | L   | 0.749      | -            | -                | -                | -         |    -3.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1688 | 2024-05-27 | FaZe             | L   | 0.743      | -            | -                | -                | -         |    -1.44 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1743 | 2024-05-24 | Nouns            | W   | 0.724      | 0.384        | 0.057 (0.016)    | -                | -         |     4.07 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1758 | 2024-05-23 | Wildcard         | W   | 0.717      | 0.384        | 0.055 (0.015)    | -                | -         |     3.96 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1783 | 2024-05-22 | Party Astronauts | L   | 0.711      | -            | -                | -                | -         |   -18.93 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1787 | 2024-05-22 | Party Astronauts | W   | 0.710      | 0.477        | 0.041 (0.014)    | 0.531 (0.180)    | -         |     3.31 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1793 | 2024-05-22 | Mythic           | W   | 0.709      | -            | -                | -                | -         |     1.66 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1858 | 2024-05-20 | NRG              | W   | 0.698      | 0.477        | -                | 0.521 (0.173)    | -         |     3.12 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1862 | 2024-05-20 | NRG              | W   | 0.698      | 0.477        | -                | 0.521 (0.173)    | -         |     3.22 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1873 | 2024-05-20 | E-Xolos LAZER    | W   | 0.696      | -            | -                | -                | -         |     1.46 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1896 | 2024-05-19 | BOSS             | W   | 0.690      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1897 | 2024-05-19 | BOSS             | W   | 0.690      | -            | -                | -                | -         |     1.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1922 | 2024-05-18 | Nouns            | L   | 0.683      | -            | -                | -                | -         |   -18.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     1956 | 2024-05-17 | Detonate         | W   | 0.677      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2028 | 2024-05-15 | Take Flyte       | W   | 0.664      | -            | -                | -                | -         |     0.86 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2035 | 2024-05-15 | Take Flyte       | W   | 0.664      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2078 | 2024-05-14 | Elevate          | W   | 0.658      | -            | -                | -                | -         |     3.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2085 | 2024-05-14 | Elevate          | W   | 0.657      | -            | -                | -                | -         |     3.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2207 | 2024-05-10 | Limitless        | W   | 0.631      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2208 | 2024-05-10 | Limitless        | W   | 0.631      | -            | -                | -                | -         |     0.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2223 | 2024-05-09 | LAG              | W   | 0.624      | -            | -                | -                | -         |     1.80 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2228 | 2024-05-09 | LAG              | W   | 0.624      | -            | -                | -                | -         |     1.84 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2455 | 2024-04-28 | G2               | L   | 0.549      | -            | -                | -                | -         |    -0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2483 | 2024-04-27 | TYLOO            | W   | 0.541      | -            | -                | -                | 1 (0.541) |     1.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2501 | 2024-04-26 | BetBoom          | L   | 0.536      | -            | -                | -                | -         |    -4.88 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2513 | 2024-04-26 | G2               | W   | 0.534      | 0.889        | 1.000 (0.474)    | 0.498 (0.236)    | 1 (0.534) |    16.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2536 | 2024-04-25 | Sharks           | W   | 0.528      | -            | -                | -                | 1 (0.528) |     1.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2570 | 2024-04-23 | BetBoom          | L   | 0.515      | -            | -                | -                | -         |    -4.68 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2656 | 2024-04-19 | Liquid           | W   | 0.491      | 0.143        | 0.315 (0.022)    | -                | -         |    12.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2663 | 2024-04-19 | Legacy           | W   | 0.490      | -            | -                | -                | -         |     3.90 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2706 | 2024-04-18 | Liquid           | L   | 0.484      | -            | -                | -                | -         |    -2.59 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2710 | 2024-04-18 | Elevate          | W   | 0.483      | -            | -                | -                | -         |     3.30 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3279 | 2024-03-27 | Perseverance     | W   | 0.337      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3285 | 2024-03-27 | Perseverance     | W   | 0.337      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3546 | 2024-03-13 | Wildcard         | L   | 0.245      | -            | -                | -                | -         |    -6.59 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3547 | 2024-03-13 | Wildcard         | W   | 0.244      | -            | -                | -                | -         |     1.12 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3803 | 2024-03-04 | Legacy           | L   | 0.182      | -            | -                | -                | -         |    -4.38 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3835 | 2024-03-03 | Wildcard         | W   | 0.175      | -            | -                | -                | 1 (0.175) |     0.81 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3849 | 2024-03-02 | Imperial         | L   | 0.169      | -            | -                | -                | -         |    -2.39 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3870 | 2024-03-01 | ODDIK            | W   | 0.163      | -            | -                | -                | 1 (0.163) |     1.10 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,072.78)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.831 | $25,000.00     | $20,763.89      |
| 2024-06-02 |      0.782 | $4,000.00      | $3,128.89       |
| 2024-05-24 |      0.724 | $20,000.00     | $14,483.33      |
| 2024-05-12 |      0.641 | $12,000.00     | $7,696.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
