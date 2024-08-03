### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1275.1<br />
<br />
Final Rank Value (1275.1) = Starting Rank Value (1232.4) + Head To Head Adjustments (42.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.580[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.338[<sup>2</sup>](#table1)

The average of these factors is 0.407<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1232.4
- 400 + ( ( 0.407 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1232.4


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
|           54 |       76 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.10 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |       82 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      125 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.367 (0.175)    | 0 (0.000) |     2.02 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      129 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.367 (0.175)    | 0 (0.000) |     2.07 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      548 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.74 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      559 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.313 (0.313)    | 0.394 (0.394)    | 1 (1.000) |    27.13 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      624 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.99 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1111 | 2024-06-09 | Wildcard         | W   | 0.835      | 0.477        | 0.055 (0.022)    | 0.519 (0.207)    | -         |     4.72 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1123 | 2024-06-09 | NRG              | L   | 0.833      | -            | -                | -                | -         |   -22.68 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1178 | 2024-06-08 | Legacy           | W   | 0.828      | 0.143        | 0.122 (0.014)    | -                | -         |     5.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1279 | 2024-06-06 | Wildcard         | W   | 0.816      | 0.477        | 0.055 (0.021)    | 0.519 (0.202)    | -         |     4.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1295 | 2024-06-06 | Wildcard         | W   | 0.814      | -            | -                | -                | -         |     4.74 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1302 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.814      | -            | -                | -                | -         |     1.21 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1348 | 2024-06-05 | Nouns            | W   | 0.809      | 0.477        | 0.057 (0.022)    | 0.566 (0.218)    | -         |     4.65 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1603 | 2024-05-28 | HEROIC           | L   | 0.753      | -            | -                | -                | -         |    -3.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1621 | 2024-05-27 | FaZe             | L   | 0.748      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1675 | 2024-05-24 | Nouns            | W   | 0.729      | 0.384        | 0.057 (0.016)    | -                | -         |     3.98 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1690 | 2024-05-23 | Wildcard         | W   | 0.721      | 0.384        | 0.055 (0.015)    | -                | -         |     3.94 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1715 | 2024-05-22 | Party Astronauts | L   | 0.715      | -            | -                | -                | -         |   -19.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1719 | 2024-05-22 | Party Astronauts | W   | 0.715      | 0.477        | 0.041 (0.014)    | 0.550 (0.188)    | -         |     3.27 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1725 | 2024-05-22 | Mythic           | W   | 0.714      | -            | -                | -                | -         |     1.66 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1790 | 2024-05-20 | NRG              | W   | 0.703      | 0.477        | -                | 0.538 (0.180)    | -         |     3.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1794 | 2024-05-20 | NRG              | W   | 0.702      | 0.477        | -                | 0.538 (0.180)    | -         |     3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1805 | 2024-05-20 | E-Xolos LAZER    | W   | 0.701      | -            | -                | -                | -         |     1.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1828 | 2024-05-19 | BOSS             | W   | 0.695      | -            | -                | -                | -         |     1.53 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1829 | 2024-05-19 | BOSS             | W   | 0.695      | -            | -                | -                | -         |     1.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1853 | 2024-05-18 | Nouns            | L   | 0.688      | -            | -                | -                | -         |   -18.97 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     1887 | 2024-05-17 | Detonate         | W   | 0.682      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     1959 | 2024-05-15 | Take Flyte       | W   | 0.669      | -            | -                | -                | -         |     0.86 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     1966 | 2024-05-15 | Take Flyte       | W   | 0.669      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2009 | 2024-05-14 | Elevate          | W   | 0.663      | -            | -                | -                | -         |     3.09 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2016 | 2024-05-14 | Elevate          | W   | 0.662      | -            | -                | -                | -         |     3.18 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2138 | 2024-05-10 | Limitless        | W   | 0.636      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2139 | 2024-05-10 | Limitless        | W   | 0.636      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2154 | 2024-05-09 | LAG              | W   | 0.629      | -            | -                | -                | -         |     1.85 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2159 | 2024-05-09 | LAG              | W   | 0.629      | -            | -                | -                | -         |     1.89 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2385 | 2024-04-28 | G2               | L   | 0.554      | -            | -                | -                | -         |    -0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2413 | 2024-04-27 | TYLOO            | W   | 0.546      | -            | -                | -                | 1 (0.546) |     1.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2431 | 2024-04-26 | BetBoom          | L   | 0.541      | -            | -                | -                | -         |    -4.99 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2443 | 2024-04-26 | G2               | W   | 0.539      | 0.889        | 1.000 (0.479)    | 0.516 (0.247)    | 1 (0.539) |    16.66 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2465 | 2024-04-25 | Sharks           | W   | 0.533      | -            | -                | -                | 1 (0.533) |     1.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2499 | 2024-04-23 | BetBoom          | L   | 0.520      | -            | -                | -                | -         |    -4.80 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2585 | 2024-04-19 | Liquid           | W   | 0.496      | 0.143        | 0.316 (0.022)    | -                | -         |    12.92 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2592 | 2024-04-19 | Legacy           | W   | 0.495      | -            | -                | -                | -         |     3.86 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2635 | 2024-04-18 | Liquid           | L   | 0.489      | -            | -                | -                | -         |    -2.59 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2639 | 2024-04-18 | Elevate          | W   | 0.488      | -            | -                | -                | -         |     2.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3208 | 2024-03-27 | Perseverance     | W   | 0.342      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3214 | 2024-03-27 | Perseverance     | W   | 0.342      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3469 | 2024-03-13 | Wildcard         | L   | 0.249      | -            | -                | -                | -         |    -6.74 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3470 | 2024-03-13 | Wildcard         | W   | 0.249      | -            | -                | -                | -         |     1.12 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3724 | 2024-03-04 | Legacy           | L   | 0.187      | -            | -                | -                | -         |    -4.53 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3757 | 2024-03-03 | Wildcard         | W   | 0.180      | -            | -                | -                | 1 (0.180) |     0.82 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3770 | 2024-03-02 | Imperial         | L   | 0.173      | -            | -                | -                | -         |    -2.70 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3791 | 2024-03-01 | ODDIK            | W   | 0.168      | -            | -                | -                | 1 (0.168) |     1.08 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,363.66)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.835 | $25,000.00     | $20,883.10      |
| 2024-06-02 |      0.787 | $4,000.00      | $3,147.96       |
| 2024-05-24 |      0.729 | $20,000.00     | $14,578.70      |
| 2024-05-12 |      0.646 | $12,000.00     | $7,753.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
