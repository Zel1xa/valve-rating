### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1581.2<br />
<br />
Final Rank Value (1581.2) = Starting Rank Value (1506.2) + Head To Head Adjustments (75.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.667[<sup>1</sup>](#table2)
- Bounty Collected: 0.585[<sup>2</sup>](#table1)
- Opponent Network: 0.196[<sup>2</sup>](#table1)
- LAN Wins: 0.715[<sup>2</sup>](#table1)

The average of these factors is 0.541<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1506.2
- 400 + ( ( 0.541 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1506.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |       59 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.343 (0.199)    | 1 (1.000) |    28.12 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |       99 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.496 (0.288)    | 0.335 (0.195)    | 1 (1.000) |    21.58 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1570 | 2024-05-29 | G2               | L   | 0.762      | -            | -                | -                | -         |    -2.36 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1595 | 2024-05-28 | Falcons          | W   | 0.755      | 0.624        | 0.225 (0.106)    | 0.256 (0.120)    | 1 (0.755) |     8.70 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1613 | 2024-05-27 | 9z               | L   | 0.749      | -            | -                | -                | -         |   -20.24 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1624 | 2024-05-27 | Complexity       | W   | 0.747      | 0.624        | 0.313 (0.146)    | 0.394 (0.184)    | 1 (0.747) |    15.78 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1697 | 2024-05-23 | Eternal Fire     | L   | 0.719      | -            | -                | -                | -         |    -6.92 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1741 | 2024-05-22 | Astralis         | W   | 0.712      | 0.769        | 0.353 (0.193)    | 0.396 (0.216)    | -         |    16.75 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1786 | 2024-05-21 | ENCE             | W   | 0.705      | 0.769        | 0.170 (0.092)    | 0.415 (0.225)    | -         |     6.97 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1841 | 2024-05-19 | AMKAL            | W   | 0.692      | 0.769        | 0.130 (0.069)    | 0.494 (0.263)    | -         |     3.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1856 | 2024-05-18 | OG               | W   | 0.688      | 0.769        | 0.140 (0.074)    | -                | -         |     1.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2146 | 2024-05-10 | Astralis         | L   | 0.633      | -            | -                | -                | -         |    -4.79 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2189 | 2024-05-08 | FlyQuest         | W   | 0.619      | 0.889        | -                | 0.302 (0.166)    | 1 (0.619) |     3.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2257 | 2024-05-04 | MOUZ             | L   | 0.594      | -            | -                | -                | -         |    -3.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2319 | 2024-05-01 | Monte            | W   | 0.574      | -            | -                | -                | 1 (0.574) |     1.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2342 | 2024-04-30 | FURIA            | W   | 0.567      | 0.889        | 0.284 (0.143)    | 0.508 (0.256)    | 1 (0.567) |    12.39 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2585 | 2024-04-19 | M80              | L   | 0.496      | -            | -                | -                | -         |   -12.92 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2635 | 2024-04-18 | M80              | W   | 0.489      | -            | -                | -                | -         |     2.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2638 | 2024-04-18 | Legacy           | W   | 0.488      | -            | -                | -                | -         |     0.94 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2685 | 2024-04-17 | Akimbo           | W   | 0.482      | -            | -                | -                | -         |     0.23 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2690 | 2024-04-17 | straykids        | W   | 0.481      | -            | -                | -                | -         |     0.13 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2803 | 2024-04-12 | FaZe             | L   | 0.445      | -            | -                | -                | -         |    -3.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2888 | 2024-04-10 | MOUZ             | L   | 0.431      | -            | -                | -                | -         |    -2.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     2966 | 2024-04-08 | G2               | W   | 0.418      | 0.624        | 1.000 (0.261)    | 0.516 (0.134)    | 1 (0.418) |    12.32 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     2976 | 2024-04-07 | HEROIC           | W   | 0.417      | -            | -                | -                | 1 (0.417) |     7.72 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3640 | 2024-03-07 | SAW              | L   | 0.206      | -            | -                | -                | -         |    -5.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3722 | 2024-03-04 | Complexity       | L   | 0.188      | -            | -                | -                | -         |    -1.80 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3758 | 2024-03-03 | BOSS             | W   | 0.180      | -            | -                | -                | 1 (0.180) |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3771 | 2024-03-02 | FURIA            | L   | 0.173      | -            | -                | -                | -         |    -1.25 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3786 | 2024-03-01 | BESTIA           | W   | 0.168      | -            | -                | -                | -         |     0.32 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3857 | 2024-02-26 | Nouns            | W   | 0.143      | -            | -                | -                | -         |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3859 | 2024-02-26 | BOSS             | W   | 0.142      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3872 | 2024-02-25 | Wildcard         | W   | 0.136      | -            | -                | -                | -         |     0.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3877 | 2024-02-25 | Nouns            | L   | 0.135      | -            | -                | -                | -         |    -4.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     3936 | 2024-02-22 | Party Astronauts | W   | 0.116      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     3938 | 2024-02-22 | MIGHT            | W   | 0.115      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     3944 | 2024-02-22 | ex-CatEvil       | W   | 0.115      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,025.72)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.787 | $6,000.00      | $4,721.94       |
| 2024-05-23 |      0.719 | $100,000.00    | $71,907.41      |
| 2024-05-12 |      0.646 | $32,000.00     | $20,677.04      |
| 2024-04-14 |      0.458 | $10,000.00     | $4,582.64       |
| 2024-03-10 |      0.227 | $5,000.00      | $1,136.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
