### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1153.4<br />
<br />
Final Rank Value (1153.4) = Starting Rank Value (1084.9) + Head To Head Adjustments (68.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.565[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.206[<sup>2</sup>](#table1)
- LAN Wins: 0.182[<sup>2</sup>](#table1)

The average of these factors is 0.354<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1084.9
- 400 + ( ( 0.354 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1084.9


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
|           60 |      574 | 2024-08-22 | Falcons          | L   | 1.000      | -            | -                | -                | -         |    -4.29 | Lake, reck, s1n, slaxz-, Swisher        |
|           59 |      738 | 2024-08-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -19.84 | Lake, reck, s1n, slaxz-, Swisher        |
|           58 |      753 | 2024-08-17 | undefined        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.25 | Lake, reck, s1n, slaxz-, Swisher        |
|           57 |      863 | 2024-08-13 | InControl        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.89 | Lake, reck, s1n, slaxz-, Swisher        |
|           56 |      904 | 2024-08-12 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.55 | Lake, reck, s1n, slaxz-, Swisher        |
|           55 |      907 | 2024-08-12 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.62 | Lake, reck, s1n, slaxz-, Swisher        |
|           54 |     1043 | 2024-08-07 | LAG              | W   | 0.990      | 0.477        | -                | 0.371 (0.175)    | 0 (0.000) |     2.11 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |     1046 | 2024-08-07 | LAG              | W   | 0.990      | 0.477        | -                | 0.371 (0.175)    | 0 (0.000) |     2.15 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |     1097 | 2024-08-06 | FLUFFY AIMERS    | W   | 0.984      | 0.477        | -                | 0.540 (0.253)    | -         |     2.50 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |     1101 | 2024-08-06 | FLUFFY AIMERS    | W   | 0.983      | 0.477        | -                | 0.540 (0.253)    | -         |     2.56 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |     1297 | 2024-07-31 | Limitless        | W   | 0.944      | -            | -                | -                | -         |     0.70 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |     1303 | 2024-07-31 | Limitless        | W   | 0.943      | -            | -                | -                | -         |     0.70 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |     1347 | 2024-07-30 | E-Xolos LAZER    | W   | 0.937      | 0.477        | -                | 0.460 (0.206)    | -         |     3.04 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1351 | 2024-07-30 | E-Xolos LAZER    | W   | 0.937      | 0.477        | -                | 0.460 (0.206)    | -         |     3.13 | Lake, reck, s1n, slaxz-, Swisher        |
|           46 |     1770 | 2024-07-18 | The MongolZ      | L   | 0.854      | -            | -                | -                | -         |    -0.81 | Lake, reck, s1n, slaxz-, Swisher        |
|           45 |     1781 | 2024-07-18 | Complexity       | W   | 0.853      | 1.000        | 0.337 (0.287)    | 0.367 (0.313)    | 1 (0.853) |    23.58 | Lake, reck, s1n, slaxz-, Swisher        |
|           44 |     1847 | 2024-07-17 | Vitality         | L   | 0.847      | -            | -                | -                | -         |    -0.35 | Lake, reck, s1n, slaxz-, Swisher        |
|           43 |     2368 | 2024-06-09 | Wildcard         | W   | 0.596      | 0.477        | 0.100 (0.028)    | 0.608 (0.173)    | -         |     6.04 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     2381 | 2024-06-09 | NRG              | L   | 0.594      | -            | -                | -                | -         |   -15.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     2438 | 2024-06-08 | Legacy           | W   | 0.589      | 0.143        | 0.092 (0.008)    | -                | -         |     4.08 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     2542 | 2024-06-06 | Wildcard         | W   | 0.577      | 0.477        | 0.100 (0.028)    | 0.608 (0.167)    | -         |     5.84 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     2558 | 2024-06-06 | Wildcard         | W   | 0.575      | 0.143        | 0.100 (0.008)    | -                | -         |     6.40 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     2565 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.575      | -            | -                | -                | -         |     1.84 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     2611 | 2024-06-05 | Nouns            | W   | 0.570      | 0.477        | 0.056 (0.015)    | 0.519 (0.141)    | -         |     4.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     2869 | 2024-05-28 | HEROIC           | L   | 0.514      | -            | -                | -                | -         |    -2.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     2887 | 2024-05-27 | FaZe             | L   | 0.509      | -            | -                | -                | -         |    -0.43 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     2942 | 2024-05-24 | Nouns            | W   | 0.490      | 0.384        | 0.056 (0.011)    | -                | -         |     3.89 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     2957 | 2024-05-23 | Wildcard         | W   | 0.482      | 0.384        | 0.100 (0.019)    | -                | -         |     5.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     2982 | 2024-05-22 | Party Astronauts | L   | 0.476      | -            | -                | -                | -         |   -11.88 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     2986 | 2024-05-22 | Party Astronauts | W   | 0.476      | -            | -                | -                | -         |     3.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     2992 | 2024-05-22 | Mythic           | W   | 0.475      | -            | -                | -                | -         |     1.95 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     3057 | 2024-05-20 | NRG              | W   | 0.464      | -            | -                | -                | -         |     2.96 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     3061 | 2024-05-20 | NRG              | W   | 0.463      | -            | -                | -                | -         |     3.04 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     3072 | 2024-05-20 | E-Xolos LAZER    | W   | 0.462      | -            | -                | -                | -         |     1.87 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     3095 | 2024-05-19 | BOSS             | W   | 0.456      | -            | -                | -                | -         |     1.82 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           25 |     3096 | 2024-05-19 | BOSS             | W   | 0.456      | -            | -                | -                | -         |     1.85 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           24 |     3121 | 2024-05-18 | Nouns            | L   | 0.449      | -            | -                | -                | -         |   -11.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     3155 | 2024-05-17 | regain           | W   | 0.443      | -            | -                | -                | -         |     0.38 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     3227 | 2024-05-15 | Take Flyte       | W   | 0.430      | -            | -                | -                | -         |     1.09 | malbsMd, reck, slaxz-, stamina, Swisher |
|           21 |     3234 | 2024-05-15 | Take Flyte       | W   | 0.430      | -            | -                | -                | -         |     1.10 | malbsMd, reck, slaxz-, stamina, Swisher |
|           20 |     3277 | 2024-05-14 | timbermen        | W   | 0.424      | -            | -                | -                | -         |     3.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     3284 | 2024-05-14 | timbermen        | W   | 0.423      | -            | -                | -                | -         |     3.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     3406 | 2024-05-10 | Limitless        | W   | 0.397      | -            | -                | -                | -         |     0.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     3407 | 2024-05-10 | Limitless        | W   | 0.397      | -            | -                | -                | -         |     0.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     3422 | 2024-05-09 | LAG              | W   | 0.390      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     3427 | 2024-05-09 | LAG              | W   | 0.390      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     3654 | 2024-04-28 | G2               | L   | 0.315      | -            | -                | -                | -         |    -0.08 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     3682 | 2024-04-27 | TYLOO            | W   | 0.307      | -            | -                | -                | 1 (0.307) |     0.96 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     3700 | 2024-04-26 | BetBoom          | L   | 0.302      | -            | -                | -                | -         |    -3.09 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     3712 | 2024-04-26 | G2               | W   | 0.300      | 0.889        | 1.000 (0.266)    | -                | 1 (0.300) |     9.36 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     3735 | 2024-04-25 | Sharks           | W   | 0.294      | -            | -                | -                | 1 (0.294) |     1.02 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     3769 | 2024-04-23 | BetBoom          | L   | 0.281      | -            | -                | -                | -         |    -2.91 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3855 | 2024-04-19 | Liquid           | W   | 0.257      | 0.143        | 0.370 (0.014)    | -                | -         |     7.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            7 |     3862 | 2024-04-19 | Legacy           | W   | 0.256      | -            | -                | -                | -         |     2.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            6 |     3905 | 2024-04-18 | Liquid           | L   | 0.250      | -            | -                | -                | -         |    -0.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            5 |     3909 | 2024-04-18 | timbermen        | W   | 0.249      | -            | -                | -                | -         |     2.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            4 |     4478 | 2024-03-27 | Phoenix          | W   | 0.103      | -            | -                | -                | -         |     0.33 | malbsMd, reck, s1n, stamina, Swisher    |
|            3 |     4484 | 2024-03-27 | Phoenix          | W   | 0.103      | -            | -                | -                | -         |     0.33 | malbsMd, reck, s1n, stamina, Swisher    |
|            2 |     4745 | 2024-03-13 | Wildcard         | L   | 0.011      | -            | -                | -                | -         |    -0.20 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     4746 | 2024-03-13 | Wildcard         | W   | 0.010      | -            | -                | -                | -         |     0.13 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($51,409.44)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-08-18 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-21 |      0.875 | $15,000.00     | $13,120.83      |
| 2024-06-09 |      0.596 | $25,000.00     | $14,909.72      |
| 2024-06-02 |      0.548 | $4,000.00      | $2,192.22       |
| 2024-05-24 |      0.490 | $20,000.00     | $9,800.00       |
| 2024-05-12 |      0.407 | $12,000.00     | $4,886.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
