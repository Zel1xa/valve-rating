### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1269.9<br />
<br />
Final Rank Value (1269.9) = Starting Rank Value (1223.2) + Head To Head Adjustments (46.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.196[<sup>2</sup>](#table1)
- LAN Wins: 0.331[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1223.2
- 400 + ( ( 0.400 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1223.2


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
|           54 |      179 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      185 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      229 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.14 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      233 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.19 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      652 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.64 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      663 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.341 (0.341)    | 0.364 (0.364)    | 1 (1.000) |    27.41 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      729 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1247 | 2024-06-09 | Wildcard         | W   | 0.816      | 0.477        | 0.048 (0.019)    | 0.418 (0.163)    | -         |     4.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1260 | 2024-06-09 | NRG              | L   | 0.814      | -            | -                | -                | -         |   -22.12 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1317 | 2024-06-08 | Legacy           | W   | 0.808      | 0.143        | 0.122 (0.014)    | -                | -         |     5.21 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1421 | 2024-06-06 | Wildcard         | W   | 0.796      | 0.477        | 0.048 (0.018)    | 0.418 (0.159)    | -         |     3.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1437 | 2024-06-06 | Wildcard         | W   | 0.794      | -            | -                | -                | -         |     4.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1444 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.794      | -            | -                | -                | -         |     1.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1490 | 2024-06-05 | Nouns            | W   | 0.790      | 0.477        | 0.057 (0.021)    | 0.541 (0.204)    | -         |     4.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1748 | 2024-05-28 | HEROIC           | L   | 0.734      | -            | -                | -                | -         |    -3.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1766 | 2024-05-27 | FaZe             | L   | 0.728      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1821 | 2024-05-24 | Nouns            | W   | 0.709      | 0.384        | 0.057 (0.016)    | -                | -         |     4.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1836 | 2024-05-23 | Wildcard         | W   | 0.702      | 0.384        | 0.048 (0.013)    | -                | -         |     3.40 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1861 | 2024-05-22 | Party Astronauts | L   | 0.696      | -            | -                | -                | -         |   -18.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1865 | 2024-05-22 | Party Astronauts | W   | 0.696      | 0.477        | 0.041 (0.014)    | 0.510 (0.169)    | -         |     3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1871 | 2024-05-22 | Mythic           | W   | 0.695      | -            | -                | -                | -         |     1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1936 | 2024-05-20 | NRG              | W   | 0.683      | 0.477        | -                | 0.502 (0.164)    | -         |     3.05 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1940 | 2024-05-20 | NRG              | W   | 0.683      | 0.477        | -                | 0.502 (0.163)    | -         |     3.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1951 | 2024-05-20 | E-Xolos LAZER    | W   | 0.681      | -            | -                | -                | -         |     1.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1974 | 2024-05-19 | BOSS             | W   | 0.676      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1975 | 2024-05-19 | BOSS             | W   | 0.675      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     2000 | 2024-05-18 | Nouns            | L   | 0.669      | -            | -                | -                | -         |   -18.22 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     2034 | 2024-05-17 | DETONATE         | W   | 0.662      | -            | -                | -                | -         |     0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2106 | 2024-05-15 | Take Flyte       | W   | 0.650      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2113 | 2024-05-15 | Take Flyte       | W   | 0.649      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2156 | 2024-05-14 | Elevate          | W   | 0.643      | -            | -                | -                | -         |     3.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2163 | 2024-05-14 | Elevate          | W   | 0.643      | -            | -                | -                | -         |     3.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2285 | 2024-05-10 | Limitless        | W   | 0.616      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2286 | 2024-05-10 | Limitless        | W   | 0.616      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2301 | 2024-05-09 | LAG              | W   | 0.610      | -            | -                | -                | -         |     1.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2306 | 2024-05-09 | LAG              | W   | 0.609      | -            | -                | -                | -         |     1.72 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2533 | 2024-04-28 | G2               | L   | 0.534      | -            | -                | -                | -         |    -0.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2561 | 2024-04-27 | TYLOO            | W   | 0.527      | -            | -                | -                | 1 (0.527) |     1.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2579 | 2024-04-26 | BetBoom          | L   | 0.521      | -            | -                | -                | -         |    -4.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2591 | 2024-04-26 | G2               | W   | 0.519      | 0.889        | 1.000 (0.461)    | 0.478 (0.221)    | 1 (0.519) |    16.07 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2614 | 2024-04-25 | Sharks           | W   | 0.513      | -            | -                | -                | 1 (0.513) |     1.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2648 | 2024-04-23 | BetBoom          | L   | 0.501      | -            | -                | -                | -         |    -4.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2734 | 2024-04-19 | Liquid           | W   | 0.476      | 0.143        | 0.383 (0.026)    | -                | -         |    13.31 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2741 | 2024-04-19 | Legacy           | W   | 0.475      | -            | -                | -                | -         |     3.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2784 | 2024-04-18 | Liquid           | L   | 0.470      | -            | -                | -                | -         |    -1.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2788 | 2024-04-18 | Elevate          | W   | 0.468      | -            | -                | -                | -         |     3.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3357 | 2024-03-27 | Phoenix          | W   | 0.323      | -            | -                | -                | -         |     0.64 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3363 | 2024-03-27 | Phoenix          | W   | 0.323      | -            | -                | -                | -         |     0.64 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3624 | 2024-03-13 | Wildcard         | L   | 0.230      | -            | -                | -                | -         |    -6.33 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3625 | 2024-03-13 | Wildcard         | W   | 0.230      | -            | -                | -                | -         |     0.91 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3881 | 2024-03-04 | Legacy           | L   | 0.167      | -            | -                | -                | -         |    -4.03 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3913 | 2024-03-03 | Wildcard         | W   | 0.160      | -            | -                | -                | 1 (0.160) |     0.64 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3927 | 2024-03-02 | Imperial         | L   | 0.154      | -            | -                | -                | -         |    -2.22 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3948 | 2024-03-01 | ODDIK            | W   | 0.148      | -            | -                | -                | 1 (0.148) |     1.01 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,174.72)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.816 | $25,000.00     | $20,395.83      |
| 2024-06-02 |      0.767 | $4,000.00      | $3,070.00       |
| 2024-05-24 |      0.709 | $20,000.00     | $14,188.89      |
| 2024-05-12 |      0.627 | $12,000.00     | $7,520.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
