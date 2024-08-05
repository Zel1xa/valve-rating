### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1271.9<br />
<br />
Final Rank Value (1271.9) = Starting Rank Value (1225.6) + Head To Head Adjustments (46.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.495[<sup>2</sup>](#table1)
- Opponent Network: 0.205[<sup>2</sup>](#table1)
- LAN Wins: 0.334[<sup>2</sup>](#table1)

The average of these factors is 0.403<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1225.6
- 400 + ( ( 0.403 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1225.6


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
|           54 |      150 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.04 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      156 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      200 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     2.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      204 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     2.16 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      623 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.66 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      634 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.378 (0.378)    | 1 (1.000) |    27.39 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      700 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1218 | 2024-06-09 | Wildcard         | W   | 0.823      | 0.477        | 0.048 (0.019)    | 0.435 (0.171)    | -         |     4.27 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1231 | 2024-06-09 | NRG              | L   | 0.821      | -            | -                | -                | -         |   -22.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1288 | 2024-06-08 | Legacy           | W   | 0.815      | 0.143        | 0.122 (0.014)    | -                | -         |     5.27 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1392 | 2024-06-06 | Wildcard         | W   | 0.803      | 0.477        | 0.048 (0.018)    | 0.435 (0.167)    | -         |     3.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1408 | 2024-06-06 | Wildcard         | W   | 0.802      | -            | -                | -                | -         |     4.18 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1415 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.801      | -            | -                | -                | -         |     1.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1461 | 2024-06-05 | Nouns            | W   | 0.797      | 0.477        | 0.057 (0.022)    | 0.560 (0.213)    | -         |     4.82 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1719 | 2024-05-28 | HEROIC           | L   | 0.741      | -            | -                | -                | -         |    -3.50 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1737 | 2024-05-27 | FaZe             | L   | 0.735      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1792 | 2024-05-24 | Nouns            | W   | 0.717      | 0.384        | 0.057 (0.016)    | -                | -         |     4.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1807 | 2024-05-23 | Wildcard         | W   | 0.709      | 0.384        | 0.048 (0.013)    | -                | -         |     3.43 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1832 | 2024-05-22 | Party Astronauts | L   | 0.703      | -            | -                | -                | -         |   -18.75 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1836 | 2024-05-22 | Party Astronauts | W   | 0.703      | 0.477        | 0.041 (0.014)    | 0.529 (0.177)    | -         |     3.25 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1842 | 2024-05-22 | Mythic           | W   | 0.702      | -            | -                | -                | -         |     1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1907 | 2024-05-20 | NRG              | W   | 0.690      | 0.477        | -                | 0.520 (0.171)    | -         |     3.07 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1911 | 2024-05-20 | NRG              | W   | 0.690      | 0.477        | -                | 0.520 (0.171)    | -         |     3.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1922 | 2024-05-20 | E-Xolos LAZER    | W   | 0.689      | -            | -                | -                | -         |     1.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1945 | 2024-05-19 | BOSS             | W   | 0.683      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1946 | 2024-05-19 | BOSS             | W   | 0.682      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1971 | 2024-05-18 | Nouns            | L   | 0.676      | -            | -                | -                | -         |   -18.43 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     2005 | 2024-05-17 | Detonate         | W   | 0.670      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2077 | 2024-05-15 | Take Flyte       | W   | 0.657      | -            | -                | -                | -         |     0.86 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2084 | 2024-05-15 | Take Flyte       | W   | 0.657      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2127 | 2024-05-14 | Elevate          | W   | 0.650      | -            | -                | -                | -         |     3.59 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2134 | 2024-05-14 | Elevate          | W   | 0.650      | -            | -                | -                | -         |     3.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2256 | 2024-05-10 | Limitless        | W   | 0.624      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2257 | 2024-05-10 | Limitless        | W   | 0.623      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2272 | 2024-05-09 | LAG              | W   | 0.617      | -            | -                | -                | -         |     1.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2277 | 2024-05-09 | LAG              | W   | 0.617      | -            | -                | -                | -         |     1.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2504 | 2024-04-28 | G2               | L   | 0.541      | -            | -                | -                | -         |    -0.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2532 | 2024-04-27 | TYLOO            | W   | 0.534      | -            | -                | -                | 1 (0.534) |     1.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2550 | 2024-04-26 | BetBoom          | L   | 0.528      | -            | -                | -                | -         |    -4.82 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2562 | 2024-04-26 | G2               | W   | 0.526      | 0.889        | 1.000 (0.468)    | 0.496 (0.232)    | 1 (0.526) |    16.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2585 | 2024-04-25 | Sharks           | W   | 0.521      | -            | -                | -                | 1 (0.521) |     1.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2619 | 2024-04-23 | BetBoom          | L   | 0.508      | -            | -                | -                | -         |    -4.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2705 | 2024-04-19 | Liquid           | W   | 0.483      | 0.143        | 0.384 (0.026)    | -                | -         |    13.50 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2712 | 2024-04-19 | Legacy           | W   | 0.482      | -            | -                | -                | -         |     3.85 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2755 | 2024-04-18 | Liquid           | L   | 0.477      | -            | -                | -                | -         |    -1.64 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2759 | 2024-04-18 | Elevate          | W   | 0.476      | -            | -                | -                | -         |     3.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3328 | 2024-03-27 | Phoenix          | W   | 0.330      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3334 | 2024-03-27 | Phoenix          | W   | 0.330      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3595 | 2024-03-13 | Wildcard         | L   | 0.237      | -            | -                | -                | -         |    -6.54 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3596 | 2024-03-13 | Wildcard         | W   | 0.237      | -            | -                | -                | -         |     0.93 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3852 | 2024-03-04 | Legacy           | L   | 0.175      | -            | -                | -                | -         |    -4.20 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3884 | 2024-03-03 | Wildcard         | W   | 0.168      | -            | -                | -                | 1 (0.168) |     0.67 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3898 | 2024-03-02 | Imperial         | L   | 0.161      | -            | -                | -                | -         |    -2.30 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3919 | 2024-03-01 | ODDIK            | W   | 0.155      | -            | -                | -                | 1 (0.155) |     1.06 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,615.28)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.823 | $25,000.00     | $20,576.39      |
| 2024-06-02 |      0.775 | $4,000.00      | $3,098.89       |
| 2024-05-24 |      0.717 | $20,000.00     | $14,333.33      |
| 2024-05-12 |      0.634 | $12,000.00     | $7,606.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
