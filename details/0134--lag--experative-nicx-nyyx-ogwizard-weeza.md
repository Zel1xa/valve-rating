### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  769.4<br />
<br />
Final Rank Value (769.4) = Starting Rank Value (853.0) + Head To Head Adjustments (-83.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.125[<sup>2</sup>](#table1)
- LAN Wins: 0.093[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 853.0
- 400 + ( ( 0.222 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 853.0


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
|           55 |      108 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.89 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      113 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -15.17 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      204 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -20.19 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      329 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.43 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      355 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |     9.35 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      358 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |    10.08 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      478 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -9.44 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      612 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.09 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      619 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -18.64 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      680 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -12.42 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      686 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.055 (0.026)    | 0.503 (0.240)    | 0 (0.000) |    19.39 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      727 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    19.92 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      731 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1068 | 2024-06-13 | Mythic           | L   | 0.857      | -            | -                | -                | -         |   -14.09 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1240 | 2024-06-08 | Homyno           | W   | 0.823      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.53 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1295 | 2024-06-07 | Wildcard         | L   | 0.817      | -            | -                | -                | -         |    -8.25 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1377 | 2024-06-06 | Vibe             | W   | 0.808      | -            | -                | -                | 0 (0.000) |     2.21 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1419 | 2024-06-05 | NRG              | L   | 0.804      | -            | -                | -                | -         |   -10.46 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1429 | 2024-06-05 | Limitless        | W   | 0.803      | -            | -                | -                | -         |    10.30 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1471 | 2024-06-04 | Limitless        | W   | 0.797      | -            | -                | -                | -         |    10.97 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1481 | 2024-06-04 | Retirement Home  | W   | 0.796      | -            | -                | -                | -         |     2.15 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1786 | 2024-05-22 | Limitless        | W   | 0.710      | -            | -                | -                | -         |     5.42 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1789 | 2024-05-22 | Limitless        | W   | 0.710      | -            | -                | -                | -         |     5.68 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1794 | 2024-05-22 | Wildcard         | L   | 0.710      | -            | -                | -                | -         |    -7.05 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2037 | 2024-05-15 | NRG              | L   | 0.664      | -            | -                | -                | -         |    -7.62 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2044 | 2024-05-15 | NRG              | L   | 0.663      | -            | -                | -                | -         |    -8.05 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2090 | 2024-05-14 | Limitless        | W   | 0.657      | -            | -                | -                | -         |     8.35 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2096 | 2024-05-14 | Limitless        | L   | 0.657      | -            | -                | -                | -         |   -12.66 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2231 | 2024-05-09 | M80              | L   | 0.624      | -            | -                | -                | -         |    -1.79 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2236 | 2024-05-09 | M80              | L   | 0.623      | -            | -                | -                | -         |    -1.82 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2251 | 2024-05-08 | Party Astronauts | L   | 0.617      | -            | -                | -                | -         |    -6.99 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2256 | 2024-05-08 | Party Astronauts | L   | 0.617      | -            | -                | -                | -         |    -7.36 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2918 | 2024-04-10 | Mythic           | W   | 0.430      | 0.477        | 0.010 (0.002)    | 0.299 (0.061)    | -         |     5.44 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2923 | 2024-04-10 | Mythic           | W   | 0.430      | 0.477        | -                | 0.299 (0.061)    | -         |     5.64 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2974 | 2024-04-09 | BOSS             | L   | 0.424      | -            | -                | -                | -         |    -7.43 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     2977 | 2024-04-09 | BOSS             | L   | 0.423      | -            | -                | -                | -         |    -7.70 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3105 | 2024-04-04 | Nouns            | W   | 0.390      | 0.477        | 0.057 (0.011)    | 0.548 (0.102)    | -         |     7.32 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3109 | 2024-04-04 | Nouns            | L   | 0.390      | -            | -                | -                | -         |    -5.06 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3151 | 2024-04-03 | Elevate          | L   | 0.384      | -            | -                | -                | -         |    -3.92 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3153 | 2024-04-03 | Elevate          | W   | 0.383      | 0.477        | 0.027 (0.005)    | 0.505 (0.092)    | -         |     8.33 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3327 | 2024-03-26 | Wildcard         | L   | 0.331      | -            | -                | -                | -         |    -4.42 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3332 | 2024-03-26 | Wildcard         | W   | 0.330      | 0.477        | 0.055 (0.009)    | 0.503 (0.079)    | -         |     6.12 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3412 | 2024-03-20 | Perseverance     | L   | 0.290      | -            | -                | -                | -         |    -6.14 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3414 | 2024-03-20 | Perseverance     | W   | 0.290      | -            | -                | -                | -         |     3.04 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3457 | 2024-03-17 | Akimbo           | W   | 0.271      | -            | -                | -                | 1 (0.271) |     3.17 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3459 | 2024-03-17 | Akimbo           | W   | 0.270      | -            | -                | -                | 1 (0.270) |     2.25 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3469 | 2024-03-17 | WICKED           | W   | 0.268      | -            | -                | -                | 1 (0.268) |     1.59 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3707 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.204      | -            | -                | -                | -         |     2.48 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3708 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.204      | -            | -                | -                | -         |    -4.00 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3735 | 2024-03-06 | MIGHT            | W   | 0.197      | -            | -                | -                | -         |     0.97 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3736 | 2024-03-06 | MIGHT            | L   | 0.197      | -            | -                | -                | -         |    -5.28 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3773 | 2024-03-05 | Take Flyte       | W   | 0.191      | -            | -                | -                | -         |     1.86 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3775 | 2024-03-05 | Take Flyte       | W   | 0.190      | -            | -                | -                | -         |     1.89 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     3986 | 2024-02-24 | Limitless        | L   | 0.123      | -            | -                | -                | -         |    -2.90 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4176 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.070      | -            | -                | -                | -         |    -1.39 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,978.21)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.830 | $3,000.00      | $2,489.51       |
| 2024-03-17 |      0.271 | $5,500.00      | $1,488.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
