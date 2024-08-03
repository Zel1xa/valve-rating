### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, phzy, Sonic, stanislaw, susp<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1046.4<br />
<br />
Final Rank Value (1046.4) = Starting Rank Value (912.0) + Head To Head Adjustments (134.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.020[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 912.0
- 400 + ( ( 0.250 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 912.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |       78 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.485 (0.231)    | 0 (0.000) |     9.47 | JBa, phzy, Sonic, stanislaw, susp        |
|           67 |       84 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.485 (0.231)    | 0 (0.000) |    10.21 | JBa, phzy, Sonic, stanislaw, susp        |
|           66 |      417 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | -                | 0.538 (0.163)    | 0 (0.000) |    15.41 | JBa, phzy, Sonic, stanislaw, susp        |
|           65 |      418 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.485 (0.147)    | 0 (0.000) |    12.80 | JBa, phzy, Sonic, stanislaw, susp        |
|           64 |      443 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.550 (0.167)    | 0 (0.000) |    15.59 | JBa, phzy, Sonic, stanislaw, susp        |
|           63 |      517 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.35 | JBa, phzy, Sonic, stanislaw, susp        |
|           62 |      522 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.63 | JBa, phzy, Sonic, stanislaw, susp        |
|           61 |      587 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.17 | JBa, phzy, Sonic, stanislaw, susp        |
|           60 |      590 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.53 | JBa, phzy, Sonic, stanislaw, susp        |
|           59 |      643 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | -                | 0.353 (0.168)    | -         |    12.54 | JBa, phzy, Sonic, stanislaw, susp        |
|           58 |      649 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -19.25 | JBa, phzy, Sonic, stanislaw, susp        |
|           57 |      919 | 2024-06-16 | Nouns            | L   | 0.881      | -            | -                | -                | -         |   -13.59 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           56 |      941 | 2024-06-15 | Mythic           | W   | 0.875      | -            | -                | -                | -         |     8.13 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           55 |     1004 | 2024-06-13 | Final Form       | W   | 0.863      | -            | -                | -                | -         |     3.89 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1111 | 2024-06-09 | M80              | L   | 0.835      | -            | -                | -                | -         |    -4.72 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1171 | 2024-06-08 | Nouns            | W   | 0.829      | 0.477        | 0.057 (0.023)    | 0.566 (0.224)    | -         |    13.63 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1176 | 2024-06-08 | Party Astronauts | L   | 0.828      | -            | -                | -                | -         |   -12.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1223 | 2024-06-07 | LAG              | W   | 0.822      | -            | -                | -                | -         |     8.49 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1279 | 2024-06-06 | M80              | L   | 0.816      | -            | -                | -                | -         |    -4.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1289 | 2024-06-06 | NRG              | L   | 0.815      | -            | -                | -                | -         |   -15.14 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1295 | 2024-06-06 | M80              | L   | 0.814      | -            | -                | -                | -         |    -4.74 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1314 | 2024-06-06 | NRG              | W   | 0.813      | -            | -                | -                | -         |    10.11 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1350 | 2024-06-05 | Party Astronauts | W   | 0.809      | 0.477        | 0.041 (0.016)    | 0.550 (0.212)    | -         |    12.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1404 | 2024-06-04 | Homyno           | W   | 0.802      | -            | -                | -                | -         |     5.05 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1690 | 2024-05-23 | M80              | L   | 0.721      | -            | -                | -                | -         |    -3.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1704 | 2024-05-22 | Take Flyte       | W   | 0.716      | -            | -                | -                | -         |     3.52 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1707 | 2024-05-22 | Take Flyte       | W   | 0.716      | -            | -                | -                | -         |     3.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1718 | 2024-05-22 | LAG              | W   | 0.715      | -            | -                | -                | -         |     7.30 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1764 | 2024-05-21 | Limitless        | W   | 0.708      | -            | -                | -                | -         |     6.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           39 |     1768 | 2024-05-21 | Limitless        | W   | 0.708      | -            | -                | -                | -         |     6.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     1827 | 2024-05-19 | Limitless        | W   | 0.695      | -            | -                | -                | -         |     3.38 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     1955 | 2024-05-15 | BOSS             | W   | 0.669      | -            | -                | -                | -         |     6.84 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     1965 | 2024-05-15 | BOSS             | W   | 0.669      | -            | -                | -                | -         |     7.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2010 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.663      | -            | -                | -                | -         |     5.81 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2015 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.662      | -            | -                | -                | -         |     6.10 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2060 | 2024-05-13 | Nouns            | W   | 0.656      | 0.477        | 0.057 (0.018)    | 0.566 (0.177)    | -         |    11.40 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2061 | 2024-05-13 | Nouns            | L   | 0.656      | -            | -                | -                | -         |    -9.41 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2105 | 2024-05-11 | Elevate          | L   | 0.642      | -            | -                | -                | -         |    -9.43 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2107 | 2024-05-11 | Mythic           | L   | 0.642      | -            | -                | -                | -         |   -14.22 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2157 | 2024-05-09 | MIGHT            | W   | 0.629      | -            | -                | -                | -         |     1.95 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2160 | 2024-05-09 | MIGHT            | W   | 0.629      | -            | -                | -                | -         |     1.99 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2173 | 2024-05-08 | Limitless        | W   | 0.623      | -            | -                | -                | -         |     3.28 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           26 |     2176 | 2024-05-08 | Limitless        | W   | 0.622      | -            | -                | -                | -         |     3.38 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           25 |     2289 | 2024-05-02 | Party Astronauts | W   | 0.582      | 0.477        | 0.041 (0.011)    | 0.550 (0.153)    | -         |    10.36 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2290 | 2024-05-02 | Party Astronauts | L   | 0.582      | -            | -                | -                | -         |    -8.12 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2453 | 2024-04-25 | NRG              | W   | 0.536      | -            | -                | -                | -         |     7.50 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2455 | 2024-04-25 | NRG              | L   | 0.536      | -            | -                | -                | -         |    -9.60 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2495 | 2024-04-23 | Elevate          | W   | 0.523      | 0.477        | 0.027 (0.007)    | -                | -         |     8.99 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     2497 | 2024-04-23 | Elevate          | L   | 0.522      | -            | -                | -                | -         |    -7.62 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           19 |     2689 | 2024-04-17 | Elevate          | L   | 0.481      | -            | -                | -                | -         |    -7.32 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           18 |     3207 | 2024-03-27 | Mythic           | W   | 0.342      | -            | -                | -                | -         |     3.52 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3213 | 2024-03-27 | Mythic           | W   | 0.342      | -            | -                | -                | -         |     3.61 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3246 | 2024-03-26 | LAG              | W   | 0.336      | -            | -                | -                | -         |     4.49 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3250 | 2024-03-26 | LAG              | L   | 0.336      | -            | -                | -                | -         |    -6.22 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3442 | 2024-03-14 | Perseverance     | W   | 0.256      | -            | -                | -                | -         |     2.18 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3445 | 2024-03-14 | Perseverance     | W   | 0.255      | -            | -                | -                | -         |     2.21 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3469 | 2024-03-13 | M80              | W   | 0.249      | 0.477        | 0.188 (0.022)    | -                | -         |     6.74 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3470 | 2024-03-13 | M80              | L   | 0.249      | -            | -                | -                | -         |    -1.12 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3517 | 2024-03-12 | Mythic           | L   | 0.242      | -            | -                | -                | -         |    -5.12 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3757 | 2024-03-03 | M80              | L   | 0.180      | -            | -                | -                | -         |    -0.82 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3769 | 2024-03-02 | BESTIA           | W   | 0.174      | -            | -                | -                | 1 (0.174) |     3.51 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3789 | 2024-03-01 | RED Canids       | L   | 0.168      | -            | -                | -                | -         |    -2.07 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3872 | 2024-02-25 | Liquid           | L   | 0.136      | -            | -                | -                | -         |    -0.15 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3876 | 2024-02-25 | BOSS             | L   | 0.135      | -            | -                | -                | -         |    -2.74 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     3893 | 2024-02-24 | NRG              | W   | 0.129      | -            | -                | -                | -         |     1.71 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     3894 | 2024-02-24 | Party Astronauts | W   | 0.129      | -            | -                | -                | -         |     2.15 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     3903 | 2024-02-24 | Akimbo           | W   | 0.128      | -            | -                | -                | -         |     1.21 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     3942 | 2024-02-22 | NRG              | L   | 0.115      | -            | -                | -                | -         |    -2.11 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,853.47)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.882 | $1,500.00      | $1,323.61       |
| 2024-06-09 |      0.835 | $15,000.00     | $12,529.86      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
