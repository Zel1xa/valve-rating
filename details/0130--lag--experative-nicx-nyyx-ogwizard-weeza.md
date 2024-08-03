### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  770.6<br />
<br />
Final Rank Value (770.6) = Starting Rank Value (854.8) + Head To Head Adjustments (-84.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.125[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.8
- 400 + ( ( 0.222 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 854.8


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
|           54 |       75 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.10 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |       80 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -15.40 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      170 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -20.20 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      295 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.45 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      321 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.139 (0.066)    | 0 (0.000) |     9.32 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      324 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.139 (0.066)    | 0 (0.000) |    10.05 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      444 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -9.69 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      578 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.17 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      585 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -18.73 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      643 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -12.54 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      649 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.055 (0.026)    | 0.519 (0.248)    | 0 (0.000) |    19.25 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      690 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.485 (0.231)    | 0 (0.000) |    18.77 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |      694 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.485 (0.231)    | 0 (0.000) |    20.40 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           41 |     1006 | 2024-06-13 | Mythic           | L   | 0.862      | -            | -                | -                | -         |   -14.36 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1173 | 2024-06-08 | Homyno           | W   | 0.829      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.45 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1223 | 2024-06-07 | Wildcard         | L   | 0.822      | -            | -                | -                | -         |    -8.49 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1304 | 2024-06-06 | Vibe             | W   | 0.814      | -            | -                | -                | 0 (0.000) |     2.17 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1347 | 2024-06-05 | NRG              | L   | 0.809      | -            | -                | -                | -         |   -10.74 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1357 | 2024-06-05 | Limitless        | W   | 0.808      | -            | -                | -                | -         |    10.24 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1399 | 2024-06-04 | Limitless        | W   | 0.803      | -            | -                | -                | -         |    10.91 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1409 | 2024-06-04 | Retirement Home  | W   | 0.802      | -            | -                | -                | -         |     2.10 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1710 | 2024-05-22 | Limitless        | W   | 0.716      | -            | -                | -                | -         |     5.32 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1713 | 2024-05-22 | Limitless        | W   | 0.716      | -            | -                | -                | -         |     5.57 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     1718 | 2024-05-22 | Wildcard         | L   | 0.715      | -            | -                | -                | -         |    -7.30 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     1960 | 2024-05-15 | NRG              | L   | 0.669      | -            | -                | -                | -         |    -7.82 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     1967 | 2024-05-15 | NRG              | L   | 0.669      | -            | -                | -                | -         |    -8.26 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2013 | 2024-05-14 | Limitless        | W   | 0.662      | -            | -                | -                | -         |     8.30 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2019 | 2024-05-14 | Limitless        | L   | 0.662      | -            | -                | -                | -         |   -12.89 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2154 | 2024-05-09 | M80              | L   | 0.629      | -            | -                | -                | -         |    -1.85 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2159 | 2024-05-09 | M80              | L   | 0.629      | -            | -                | -                | -         |    -1.89 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2174 | 2024-05-08 | Party Astronauts | L   | 0.623      | -            | -                | -                | -         |    -7.31 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2839 | 2024-04-10 | Mythic           | W   | 0.436      | 0.477        | 0.010 (0.002)    | 0.311 (0.065)    | -         |     5.54 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2844 | 2024-04-10 | Mythic           | W   | 0.436      | 0.477        | -                | 0.311 (0.065)    | -         |     5.75 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2895 | 2024-04-09 | BOSS             | L   | 0.429      | -            | -                | -                | -         |    -7.50 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     2898 | 2024-04-09 | BOSS             | L   | 0.429      | -            | -                | -                | -         |    -7.78 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3026 | 2024-04-04 | Nouns            | W   | 0.396      | 0.477        | 0.057 (0.011)    | 0.566 (0.107)    | -         |     7.36 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3030 | 2024-04-04 | Nouns            | L   | 0.396      | -            | -                | -                | -         |    -5.20 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3072 | 2024-04-03 | Elevate          | L   | 0.389      | -            | -                | -                | -         |    -4.74 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3074 | 2024-04-03 | Elevate          | W   | 0.389      | 0.477        | 0.027 (0.005)    | 0.485 (0.090)    | -         |     7.68 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3246 | 2024-03-26 | Wildcard         | L   | 0.336      | -            | -                | -                | -         |    -4.49 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3250 | 2024-03-26 | Wildcard         | W   | 0.336      | 0.477        | 0.055 (0.009)    | 0.519 (0.083)    | -         |     6.22 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3328 | 2024-03-20 | Perseverance     | L   | 0.296      | -            | -                | -                | -         |    -6.25 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3330 | 2024-03-20 | Perseverance     | W   | 0.296      | -            | -                | -                | -         |     3.10 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3373 | 2024-03-17 | Akimbo           | W   | 0.276      | -            | -                | -                | 1 (0.276) |     3.23 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3375 | 2024-03-17 | Akimbo           | W   | 0.275      | -            | -                | -                | 1 (0.275) |     2.29 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3385 | 2024-03-17 | WICKED           | W   | 0.274      | -            | -                | -                | 1 (0.274) |     1.62 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3620 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.210      | -            | -                | -                | -         |     2.54 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3621 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.209      | -            | -                | -                | -         |    -4.11 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3648 | 2024-03-06 | MIGHT            | W   | 0.203      | -            | -                | -                | -         |     0.99 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3649 | 2024-03-06 | MIGHT            | L   | 0.203      | -            | -                | -                | -         |    -5.43 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3686 | 2024-03-05 | Take Flyte       | W   | 0.196      | -            | -                | -                | -         |     1.92 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3688 | 2024-03-05 | Take Flyte       | W   | 0.196      | -            | -                | -                | -         |     1.94 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     3899 | 2024-02-24 | Limitless        | L   | 0.128      | -            | -                | -                | -         |    -3.03 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4088 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.075      | -            | -                | -                | -         |    -1.50 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,024.84)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.835 | $3,000.00      | $2,505.97       |
| 2024-03-17 |      0.276 | $5,500.00      | $1,518.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
