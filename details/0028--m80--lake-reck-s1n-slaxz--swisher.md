### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1269.9<br />
<br />
Final Rank Value (1269.9) = Starting Rank Value (1223.3) + Head To Head Adjustments (46.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.197[<sup>2</sup>](#table1)
- LAN Wins: 0.331[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1223.3
- 400 + ( ( 0.400 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1223.3


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
|           54 |      167 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      173 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      217 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.14 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      221 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.18 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      640 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.64 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      651 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.341 (0.341)    | 0.364 (0.364)    | 1 (1.000) |    27.41 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      717 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1235 | 2024-06-09 | Wildcard         | W   | 0.816      | 0.477        | 0.048 (0.019)    | 0.418 (0.163)    | -         |     4.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1248 | 2024-06-09 | NRG              | L   | 0.814      | -            | -                | -                | -         |   -22.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1305 | 2024-06-08 | Legacy           | W   | 0.809      | 0.143        | 0.122 (0.014)    | -                | -         |     5.21 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1409 | 2024-06-06 | Wildcard         | W   | 0.797      | 0.477        | 0.048 (0.018)    | 0.418 (0.159)    | -         |     3.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1425 | 2024-06-06 | Wildcard         | W   | 0.795      | -            | -                | -                | -         |     4.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1432 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.795      | -            | -                | -                | -         |     1.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1478 | 2024-06-05 | Nouns            | W   | 0.790      | 0.477        | 0.057 (0.021)    | 0.541 (0.204)    | -         |     4.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1736 | 2024-05-28 | HEROIC           | L   | 0.734      | -            | -                | -                | -         |    -3.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1754 | 2024-05-27 | FaZe             | L   | 0.729      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1809 | 2024-05-24 | Nouns            | W   | 0.710      | 0.384        | 0.057 (0.016)    | -                | -         |     4.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1824 | 2024-05-23 | Wildcard         | W   | 0.702      | 0.384        | 0.048 (0.013)    | -                | -         |     3.40 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1849 | 2024-05-22 | Party Astronauts | L   | 0.696      | -            | -                | -                | -         |   -18.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1853 | 2024-05-22 | Party Astronauts | W   | 0.696      | 0.477        | 0.041 (0.014)    | 0.510 (0.169)    | -         |     3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1859 | 2024-05-22 | Mythic           | W   | 0.695      | -            | -                | -                | -         |     1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1924 | 2024-05-20 | NRG              | W   | 0.684      | 0.477        | -                | 0.502 (0.164)    | -         |     3.05 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1928 | 2024-05-20 | NRG              | W   | 0.683      | 0.477        | -                | 0.502 (0.164)    | -         |     3.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1939 | 2024-05-20 | E-Xolos LAZER    | W   | 0.682      | -            | -                | -                | -         |     1.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1962 | 2024-05-19 | BOSS             | W   | 0.676      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1963 | 2024-05-19 | BOSS             | W   | 0.676      | -            | -                | -                | -         |     1.55 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1988 | 2024-05-18 | Nouns            | L   | 0.669      | -            | -                | -                | -         |   -18.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     2022 | 2024-05-17 | DETONATE         | W   | 0.663      | -            | -                | -                | -         |     0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2094 | 2024-05-15 | Take Flyte       | W   | 0.650      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2101 | 2024-05-15 | Take Flyte       | W   | 0.650      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2144 | 2024-05-14 | Elevate          | W   | 0.644      | -            | -                | -                | -         |     3.58 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2151 | 2024-05-14 | Elevate          | W   | 0.643      | -            | -                | -                | -         |     3.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2273 | 2024-05-10 | Limitless        | W   | 0.617      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2274 | 2024-05-10 | Limitless        | W   | 0.617      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2289 | 2024-05-09 | LAG              | W   | 0.610      | -            | -                | -                | -         |     1.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2294 | 2024-05-09 | LAG              | W   | 0.610      | -            | -                | -                | -         |     1.72 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2521 | 2024-04-28 | G2               | L   | 0.534      | -            | -                | -                | -         |    -0.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2549 | 2024-04-27 | TYLOO            | W   | 0.527      | -            | -                | -                | 1 (0.527) |     1.09 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2567 | 2024-04-26 | BetBoom          | L   | 0.522      | -            | -                | -                | -         |    -4.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2579 | 2024-04-26 | G2               | W   | 0.519      | 0.889        | 1.000 (0.462)    | 0.478 (0.221)    | 1 (0.519) |    16.08 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2602 | 2024-04-25 | Sharks           | W   | 0.514      | -            | -                | -                | 1 (0.514) |     1.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2636 | 2024-04-23 | BetBoom          | L   | 0.501      | -            | -                | -                | -         |    -4.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2722 | 2024-04-19 | Liquid           | W   | 0.477      | 0.143        | 0.383 (0.026)    | -                | -         |    13.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2729 | 2024-04-19 | Legacy           | W   | 0.476      | -            | -                | -                | -         |     3.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2772 | 2024-04-18 | Liquid           | L   | 0.470      | -            | -                | -                | -         |    -1.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2776 | 2024-04-18 | Elevate          | W   | 0.469      | -            | -                | -                | -         |     3.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3345 | 2024-03-27 | Phoenix          | W   | 0.323      | -            | -                | -                | -         |     0.64 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3351 | 2024-03-27 | Phoenix          | W   | 0.323      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3612 | 2024-03-13 | Wildcard         | L   | 0.230      | -            | -                | -                | -         |    -6.35 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3613 | 2024-03-13 | Wildcard         | W   | 0.230      | -            | -                | -                | -         |     0.91 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3869 | 2024-03-04 | Legacy           | L   | 0.168      | -            | -                | -                | -         |    -4.04 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3901 | 2024-03-03 | Wildcard         | W   | 0.161      | -            | -                | -                | 1 (0.161) |     0.64 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3915 | 2024-03-02 | Imperial         | L   | 0.154      | -            | -                | -                | -         |    -2.22 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3936 | 2024-03-01 | ODDIK            | W   | 0.148      | -            | -                | -                | 1 (0.148) |     1.01 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,202.96)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.816 | $25,000.00     | $20,407.41      |
| 2024-06-02 |      0.768 | $4,000.00      | $3,071.85       |
| 2024-05-24 |      0.710 | $20,000.00     | $14,198.15      |
| 2024-05-12 |      0.627 | $12,000.00     | $7,525.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
