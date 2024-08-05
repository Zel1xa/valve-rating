### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1271.4<br />
<br />
Final Rank Value (1271.4) = Starting Rank Value (1225.1) + Head To Head Adjustments (46.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.495[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.333[<sup>2</sup>](#table1)

The average of these factors is 0.402<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1225.1
- 400 + ( ( 0.402 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1225.1


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
|           54 |      158 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      164 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      208 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     2.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      212 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     2.16 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      631 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.65 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      642 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.373 (0.373)    | 1 (1.000) |    27.40 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      708 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1226 | 2024-06-09 | Wildcard         | W   | 0.822      | 0.477        | 0.048 (0.019)    | 0.429 (0.168)    | -         |     4.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1239 | 2024-06-09 | NRG              | L   | 0.820      | -            | -                | -                | -         |   -22.30 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1296 | 2024-06-08 | Legacy           | W   | 0.814      | 0.143        | 0.122 (0.014)    | -                | -         |     5.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1400 | 2024-06-06 | Wildcard         | W   | 0.802      | 0.477        | 0.048 (0.018)    | 0.429 (0.164)    | -         |     3.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1416 | 2024-06-06 | Wildcard         | W   | 0.801      | -            | -                | -                | -         |     4.18 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1423 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.800      | -            | -                | -                | -         |     1.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1469 | 2024-06-05 | Nouns            | W   | 0.796      | 0.477        | 0.057 (0.022)    | 0.553 (0.210)    | -         |     4.81 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1727 | 2024-05-28 | HEROIC           | L   | 0.740      | -            | -                | -                | -         |    -3.50 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1745 | 2024-05-27 | FaZe             | L   | 0.734      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1800 | 2024-05-24 | Nouns            | W   | 0.716      | 0.384        | 0.057 (0.016)    | -                | -         |     4.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1815 | 2024-05-23 | Wildcard         | W   | 0.708      | 0.384        | 0.048 (0.013)    | -                | -         |     3.42 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1840 | 2024-05-22 | Party Astronauts | L   | 0.702      | -            | -                | -                | -         |   -18.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1844 | 2024-05-22 | Party Astronauts | W   | 0.702      | 0.477        | 0.041 (0.014)    | 0.523 (0.175)    | -         |     3.25 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1850 | 2024-05-22 | Mythic           | W   | 0.701      | -            | -                | -                | -         |     1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1915 | 2024-05-20 | NRG              | W   | 0.689      | 0.477        | -                | 0.514 (0.169)    | -         |     3.07 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1919 | 2024-05-20 | NRG              | W   | 0.689      | 0.477        | -                | 0.514 (0.169)    | -         |     3.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1930 | 2024-05-20 | E-Xolos LAZER    | W   | 0.688      | -            | -                | -                | -         |     1.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1953 | 2024-05-19 | BOSS             | W   | 0.682      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1954 | 2024-05-19 | BOSS             | W   | 0.681      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1979 | 2024-05-18 | Nouns            | L   | 0.675      | -            | -                | -                | -         |   -18.40 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     2013 | 2024-05-17 | Detonate         | W   | 0.669      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2085 | 2024-05-15 | Take Flyte       | W   | 0.656      | -            | -                | -                | -         |     0.86 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2092 | 2024-05-15 | Take Flyte       | W   | 0.656      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2135 | 2024-05-14 | Elevate          | W   | 0.649      | -            | -                | -                | -         |     3.59 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2142 | 2024-05-14 | Elevate          | W   | 0.649      | -            | -                | -                | -         |     3.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2264 | 2024-05-10 | Limitless        | W   | 0.623      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2265 | 2024-05-10 | Limitless        | W   | 0.622      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2280 | 2024-05-09 | LAG              | W   | 0.616      | -            | -                | -                | -         |     1.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2285 | 2024-05-09 | LAG              | W   | 0.616      | -            | -                | -                | -         |     1.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2512 | 2024-04-28 | G2               | L   | 0.540      | -            | -                | -                | -         |    -0.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2540 | 2024-04-27 | TYLOO            | W   | 0.533      | -            | -                | -                | 1 (0.533) |     1.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2558 | 2024-04-26 | BetBoom          | L   | 0.527      | -            | -                | -                | -         |    -4.81 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2570 | 2024-04-26 | G2               | W   | 0.525      | 0.889        | 1.000 (0.467)    | 0.490 (0.229)    | 1 (0.525) |    16.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2593 | 2024-04-25 | Sharks           | W   | 0.519      | -            | -                | -                | 1 (0.519) |     1.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2627 | 2024-04-23 | BetBoom          | L   | 0.507      | -            | -                | -                | -         |    -4.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2713 | 2024-04-19 | Liquid           | W   | 0.482      | 0.143        | 0.383 (0.026)    | -                | -         |    13.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2720 | 2024-04-19 | Legacy           | W   | 0.481      | -            | -                | -                | -         |     3.83 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2763 | 2024-04-18 | Liquid           | L   | 0.476      | -            | -                | -                | -         |    -1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2767 | 2024-04-18 | Elevate          | W   | 0.475      | -            | -                | -                | -         |     3.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3336 | 2024-03-27 | Phoenix          | W   | 0.329      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3342 | 2024-03-27 | Phoenix          | W   | 0.329      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3603 | 2024-03-13 | Wildcard         | L   | 0.236      | -            | -                | -                | -         |    -6.51 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3604 | 2024-03-13 | Wildcard         | W   | 0.236      | -            | -                | -                | -         |     0.93 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3860 | 2024-03-04 | Legacy           | L   | 0.174      | -            | -                | -                | -         |    -4.17 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3892 | 2024-03-03 | Wildcard         | W   | 0.166      | -            | -                | -                | 1 (0.166) |     0.66 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3906 | 2024-03-02 | Imperial         | L   | 0.160      | -            | -                | -                | -         |    -2.29 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3927 | 2024-03-01 | ODDIK            | W   | 0.154      | -            | -                | -                | 1 (0.154) |     1.05 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,547.50)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.822 | $25,000.00     | $20,548.61      |
| 2024-06-02 |      0.774 | $4,000.00      | $3,094.44       |
| 2024-05-24 |      0.716 | $20,000.00     | $14,311.11      |
| 2024-05-12 |      0.633 | $12,000.00     | $7,593.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
