### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1289.4<br />
<br />
Final Rank Value (1289.4) = Starting Rank Value (1243.5) + Head To Head Adjustments (45.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.581[<sup>1</sup>](#table2)
- Bounty Collected: 0.496[<sup>2</sup>](#table1)
- Opponent Network: 0.214[<sup>2</sup>](#table1)
- LAN Wins: 0.350[<sup>2</sup>](#table1)

The average of these factors is 0.410<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1243.5
- 400 + ( ( 0.410 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1243.5


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
|           60 |       19 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Lake, reck, s1n, slaxz-, Swisher        |
|           59 |       25 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | Lake, reck, s1n, slaxz-, Swisher        |
|           58 |       69 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     1.93 | Lake, reck, s1n, slaxz-, Swisher        |
|           57 |       73 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     1.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           56 |      501 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.89 | Lake, reck, s1n, slaxz-, Swisher        |
|           55 |      512 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.318 (0.318)    | 0.366 (0.366)    | 1 (1.000) |    26.71 | Lake, reck, s1n, slaxz-, Swisher        |
|           54 |      578 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -1.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |     1095 | 2024-06-09 | Wildcard         | W   | 0.848      | 0.477        | 0.055 (0.022)    | 0.501 (0.203)    | -         |     4.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           52 |     1108 | 2024-06-09 | NRG              | L   | 0.846      | -            | -                | -                | -         |   -23.08 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           51 |     1167 | 2024-06-08 | Legacy           | W   | 0.841      | 0.143        | 0.119 (0.014)    | -                | -         |     5.48 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           50 |     1279 | 2024-06-06 | Wildcard         | W   | 0.829      | 0.477        | 0.055 (0.022)    | 0.501 (0.198)    | -         |     4.21 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           49 |     1296 | 2024-06-06 | Wildcard         | W   | 0.827      | -            | -                | -                | -         |     4.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           48 |     1303 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.827      | -            | -                | -                | -         |     1.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           47 |     1350 | 2024-06-05 | Nouns            | W   | 0.822      | 0.477        | 0.058 (0.023)    | 0.557 (0.218)    | -         |     4.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1611 | 2024-05-28 | HEROIC           | L   | 0.766      | -            | -                | -                | -         |    -3.99 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1629 | 2024-05-27 | FaZe             | L   | 0.761      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1686 | 2024-05-24 | Nouns            | W   | 0.742      | 0.384        | 0.058 (0.017)    | -                | -         |     4.02 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1701 | 2024-05-23 | Wildcard         | W   | 0.734      | 0.384        | 0.055 (0.016)    | -                | -         |     3.90 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1726 | 2024-05-22 | Party Astronauts | L   | 0.728      | -            | -                | -                | -         |   -19.55 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1730 | 2024-05-22 | Party Astronauts | W   | 0.728      | 0.477        | 0.042 (0.015)    | 0.532 (0.185)    | -         |     3.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1736 | 2024-05-22 | Mythic           | W   | 0.727      | -            | -                | -                | -         |     1.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1779 | 2024-05-21 | MIGHT            | W   | 0.722      | -            | -                | -                | -         |     0.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1782 | 2024-05-21 | MIGHT            | W   | 0.722      | -            | -                | -                | -         |     0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1817 | 2024-05-20 | NRG              | W   | 0.716      | 0.477        | -                | 0.519 (0.177)    | -         |     3.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1821 | 2024-05-20 | NRG              | W   | 0.715      | 0.477        | -                | 0.519 (0.177)    | -         |     3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1833 | 2024-05-20 | E-Xolos LAZER    | W   | 0.714      | -            | -                | -                | -         |     1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1859 | 2024-05-19 | BOSS             | W   | 0.708      | -            | -                | -                | -         |     1.50 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1862 | 2024-05-19 | BOSS             | W   | 0.708      | -            | -                | -                | -         |     1.53 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1864 | 2024-05-19 | FLUFFY AIMERS    | W   | 0.707      | -            | -                | -                | -         |     1.04 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1865 | 2024-05-19 | FLUFFY AIMERS    | W   | 0.707      | -            | -                | -                | -         |     1.05 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1890 | 2024-05-18 | Nouns            | L   | 0.701      | -            | -                | -                | -         |   -19.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1925 | 2024-05-17 | Detonate         | W   | 0.695      | -            | -                | -                | -         |     0.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1997 | 2024-05-15 | Take Flyte       | W   | 0.682      | -            | -                | -                | -         |     0.83 | malbsMd, reck, slaxz-, stamina, Swisher |
|           27 |     2004 | 2024-05-15 | Take Flyte       | W   | 0.682      | -            | -                | -                | -         |     0.83 | malbsMd, reck, slaxz-, stamina, Swisher |
|           26 |     2053 | 2024-05-14 | Elevate          | W   | 0.676      | -            | -                | -                | -         |     3.59 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           25 |     2060 | 2024-05-14 | Elevate          | W   | 0.675      | -            | -                | -                | -         |     3.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           24 |     2185 | 2024-05-10 | Limitless        | W   | 0.649      | -            | -                | -                | -         |     0.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2186 | 2024-05-10 | Limitless        | W   | 0.649      | -            | -                | -                | -         |     0.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2201 | 2024-05-09 | LAG              | W   | 0.642      | -            | -                | -                | -         |     1.79 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2206 | 2024-05-09 | LAG              | W   | 0.642      | -            | -                | -                | -         |     1.82 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2229 | 2024-05-08 | Carpe Diem       | W   | 0.635      | -            | -                | -                | -         |     0.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2230 | 2024-05-08 | Carpe Diem       | W   | 0.635      | -            | -                | -                | -         |     0.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2438 | 2024-04-28 | G2               | L   | 0.567      | -            | -                | -                | -         |    -0.38 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2466 | 2024-04-27 | TYLOO            | W   | 0.559      | -            | -                | -                | 1 (0.559) |     1.09 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2485 | 2024-04-26 | BetBoom          | L   | 0.554      | -            | -                | -                | -         |    -5.18 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2497 | 2024-04-26 | G2               | W   | 0.552      | 0.889        | 1.000 (0.490)    | 0.500 (0.245)    | 1 (0.552) |    17.04 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2519 | 2024-04-25 | Sharks           | W   | 0.546      | -            | -                | -                | 1 (0.546) |     1.21 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2554 | 2024-04-23 | BetBoom          | L   | 0.533      | -            | -                | -                | -         |    -4.98 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2645 | 2024-04-19 | Liquid           | W   | 0.509      | 0.143        | 0.321 (0.023)    | -                | -         |    13.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2652 | 2024-04-19 | Legacy           | W   | 0.508      | -            | -                | -                | -         |     3.96 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2696 | 2024-04-18 | Liquid           | L   | 0.502      | -            | -                | -                | -         |    -2.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2700 | 2024-04-18 | Elevate          | W   | 0.501      | -            | -                | -                | -         |     3.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3281 | 2024-03-27 | Perseverance     | W   | 0.355      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3287 | 2024-03-27 | Perseverance     | W   | 0.355      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3557 | 2024-03-13 | Wildcard         | L   | 0.263      | -            | -                | -                | -         |    -7.12 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3558 | 2024-03-13 | Wildcard         | W   | 0.262      | -            | -                | -                | -         |     1.15 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3821 | 2024-03-04 | Legacy           | L   | 0.200      | -            | -                | -                | -         |    -4.85 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3854 | 2024-03-03 | Wildcard         | W   | 0.193      | -            | -                | -                | 1 (0.193) |     0.86 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3867 | 2024-03-02 | Imperial         | L   | 0.186      | -            | -                | -                | -         |    -2.68 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3889 | 2024-03-01 | ODDIK            | W   | 0.181      | -            | -                | -                | 1 (0.181) |     1.22 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($62,157.22)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.848 | $25,000.00     | $21,208.33      |
| 2024-06-02 |      0.800 | $4,000.00      | $3,200.00       |
| 2024-05-24 |      0.742 | $20,000.00     | $14,838.89      |
| 2024-05-12 |      0.659 | $12,000.00     | $7,910.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
