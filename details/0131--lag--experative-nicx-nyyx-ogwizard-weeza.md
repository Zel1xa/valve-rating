### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  769.7<br />
<br />
Final Rank Value (769.7) = Starting Rank Value (853.7) + Head To Head Adjustments (-84.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.125[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 853.7
- 400 + ( ( 0.222 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 853.7


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
|           55 |       97 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.90 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      102 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -15.18 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      193 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -20.19 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      318 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.44 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      344 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |     9.35 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      347 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |    10.08 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      467 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -9.44 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      601 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.09 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      608 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -18.64 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      669 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -12.41 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      675 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.055 (0.026)    | 0.502 (0.240)    | 0 (0.000) |    19.39 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      716 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    19.91 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      720 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1056 | 2024-06-13 | Mythic           | L   | 0.860      | -            | -                | -                | -         |   -14.15 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1228 | 2024-06-08 | Homyno           | W   | 0.827      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.56 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1283 | 2024-06-07 | Wildcard         | L   | 0.820      | -            | -                | -                | -         |    -8.28 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1365 | 2024-06-06 | Vibe             | W   | 0.812      | -            | -                | -                | 0 (0.000) |     2.22 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1407 | 2024-06-05 | NRG              | L   | 0.807      | -            | -                | -                | -         |   -10.50 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1417 | 2024-06-05 | Limitless        | W   | 0.806      | -            | -                | -                | -         |    10.35 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1459 | 2024-06-04 | Limitless        | W   | 0.801      | -            | -                | -                | -         |    11.02 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1469 | 2024-06-04 | Retirement Home  | W   | 0.800      | -            | -                | -                | -         |     2.16 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1774 | 2024-05-22 | Limitless        | W   | 0.714      | -            | -                | -                | -         |     5.44 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1777 | 2024-05-22 | Limitless        | W   | 0.714      | -            | -                | -                | -         |     5.70 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1782 | 2024-05-22 | Wildcard         | L   | 0.713      | -            | -                | -                | -         |    -7.08 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2025 | 2024-05-15 | NRG              | L   | 0.667      | -            | -                | -                | -         |    -7.66 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2032 | 2024-05-15 | NRG              | L   | 0.667      | -            | -                | -                | -         |    -8.09 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2078 | 2024-05-14 | Limitless        | W   | 0.661      | -            | -                | -                | -         |     8.39 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2084 | 2024-05-14 | Limitless        | L   | 0.661      | -            | -                | -                | -         |   -12.74 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2219 | 2024-05-09 | M80              | L   | 0.627      | -            | -                | -                | -         |    -1.81 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2224 | 2024-05-09 | M80              | L   | 0.627      | -            | -                | -                | -         |    -1.84 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2239 | 2024-05-08 | Party Astronauts | L   | 0.621      | -            | -                | -                | -         |    -7.04 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2244 | 2024-05-08 | Party Astronauts | L   | 0.621      | -            | -                | -                | -         |    -7.41 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2905 | 2024-04-10 | Mythic           | W   | 0.434      | 0.477        | 0.010 (0.002)    | 0.300 (0.062)    | -         |     5.48 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2910 | 2024-04-10 | Mythic           | W   | 0.434      | 0.477        | -                | 0.300 (0.062)    | -         |     5.68 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2961 | 2024-04-09 | BOSS             | L   | 0.427      | -            | -                | -                | -         |    -7.50 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     2964 | 2024-04-09 | BOSS             | L   | 0.427      | -            | -                | -                | -         |    -7.78 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3092 | 2024-04-04 | Nouns            | W   | 0.394      | 0.477        | 0.057 (0.011)    | 0.547 (0.103)    | -         |     7.39 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3096 | 2024-04-04 | Nouns            | L   | 0.394      | -            | -                | -                | -         |    -5.12 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3138 | 2024-04-03 | Elevate          | L   | 0.388      | -            | -                | -                | -         |    -3.97 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3140 | 2024-04-03 | Elevate          | W   | 0.387      | 0.477        | 0.027 (0.005)    | 0.505 (0.093)    | -         |     8.41 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3314 | 2024-03-26 | Wildcard         | L   | 0.335      | -            | -                | -                | -         |    -4.47 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3319 | 2024-03-26 | Wildcard         | W   | 0.334      | 0.477        | 0.055 (0.009)    | 0.502 (0.080)    | -         |     6.19 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3399 | 2024-03-20 | Perseverance     | L   | 0.294      | -            | -                | -                | -         |    -6.23 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3401 | 2024-03-20 | Perseverance     | W   | 0.294      | -            | -                | -                | -         |     3.07 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3444 | 2024-03-17 | Akimbo           | W   | 0.274      | -            | -                | -                | 1 (0.274) |     3.21 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3446 | 2024-03-17 | Akimbo           | W   | 0.273      | -            | -                | -                | 1 (0.273) |     2.28 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3456 | 2024-03-17 | WICKED           | W   | 0.272      | -            | -                | -                | 1 (0.272) |     1.61 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3693 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.208      | -            | -                | -                | -         |     2.52 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3694 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.207      | -            | -                | -                | -         |    -4.08 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3721 | 2024-03-06 | MIGHT            | W   | 0.201      | -            | -                | -                | -         |     0.98 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3722 | 2024-03-06 | MIGHT            | L   | 0.201      | -            | -                | -                | -         |    -5.39 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3759 | 2024-03-05 | Take Flyte       | W   | 0.195      | -            | -                | -                | -         |     1.90 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3761 | 2024-03-05 | Take Flyte       | W   | 0.194      | -            | -                | -                | -         |     1.92 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     3972 | 2024-02-24 | Limitless        | L   | 0.127      | -            | -                | -                | -         |    -2.99 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4161 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.073      | -            | -                | -                | -         |    -1.46 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,010.28)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.834 | $3,000.00      | $2,500.83       |
| 2024-03-17 |      0.274 | $5,500.00      | $1,509.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
