### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  781.6<br />
<br />
Final Rank Value (781.6) = Starting Rank Value (864.2) + Head To Head Adjustments (-82.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.130[<sup>2</sup>](#table1)
- LAN Wins: 0.100[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.2
- 400 + ( ( 0.226 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 864.2


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
|           56 |       15 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.35 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           55 |       20 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -15.67 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      112 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -20.53 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      237 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.70 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      263 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.135 (0.064)    | 0 (0.000) |     9.14 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      267 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | -                | 0 (0.000) |     9.84 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      388 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -9.37 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      529 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.04 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      536 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -18.58 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      597 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -12.61 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      603 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.055 (0.026)    | 0.501 (0.239)    | 0 (0.000) |    19.18 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      649 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    19.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      654 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    20.98 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      982 | 2024-06-13 | Mythic           | L   | 0.875      | -            | -                | -                | -         |   -14.71 | based, Experative, nicx, Nyyx, ogwizard |
|           42 |     1158 | 2024-06-08 | Homyno           | W   | 0.842      | 0.371        | 0.008 (0.002)    | -                | 0 (0.000) |     8.33 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1216 | 2024-06-07 | Wildcard         | L   | 0.835      | -            | -                | -                | -         |    -8.66 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1304 | 2024-06-06 | Vibe             | W   | 0.827      | -            | -                | -                | 0 (0.000) |     2.08 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1347 | 2024-06-05 | NRG              | L   | 0.822      | -            | -                | -                | -         |   -10.89 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1358 | 2024-06-05 | Limitless        | W   | 0.821      | -            | -                | -                | -         |    10.17 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1401 | 2024-06-04 | Limitless        | W   | 0.816      | -            | -                | -                | -         |    10.84 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1411 | 2024-06-04 | Retirement Home  | W   | 0.815      | -            | -                | -                | -         |     2.01 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1719 | 2024-05-22 | Limitless        | W   | 0.729      | -            | -                | -                | -         |     5.22 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1722 | 2024-05-22 | Limitless        | W   | 0.729      | -            | -                | -                | -         |     5.47 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1727 | 2024-05-22 | Wildcard         | L   | 0.728      | -            | -                | -                | -         |    -7.51 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1800 | 2024-05-21 | BOSS             | W   | 0.720      | 0.384        | 0.014 (0.004)    | 0.334 (0.092)    | -         |    10.01 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     1996 | 2024-05-15 | NRG              | L   | 0.682      | -            | -                | -                | -         |    -7.87 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2003 | 2024-05-15 | NRG              | L   | 0.682      | -            | -                | -                | -         |    -8.32 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2055 | 2024-05-14 | Limitless        | W   | 0.676      | -            | -                | -                | -         |     8.49 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2061 | 2024-05-14 | Limitless        | L   | 0.676      | -            | -                | -                | -         |   -13.13 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2199 | 2024-05-09 | M80              | L   | 0.642      | -            | -                | -                | -         |    -1.79 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2204 | 2024-05-09 | M80              | L   | 0.642      | -            | -                | -                | -         |    -1.82 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2219 | 2024-05-08 | Party Astronauts | L   | 0.636      | -            | -                | -                | -         |    -7.21 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2224 | 2024-05-08 | Party Astronauts | L   | 0.636      | -            | -                | -                | -         |    -7.60 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2902 | 2024-04-10 | Mythic           | W   | 0.449      | 0.477        | -                | 0.304 (0.065)    | -         |     5.61 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2907 | 2024-04-10 | Mythic           | W   | 0.449      | 0.477        | -                | 0.304 (0.065)    | -         |     5.83 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2958 | 2024-04-09 | BOSS             | L   | 0.443      | -            | -                | -                | -         |    -7.71 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     2961 | 2024-04-09 | BOSS             | L   | 0.442      | -            | -                | -                | -         |    -8.02 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3089 | 2024-04-04 | Nouns            | W   | 0.409      | 0.477        | 0.058 (0.011)    | 0.557 (0.109)    | -         |     7.62 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3093 | 2024-04-04 | Nouns            | L   | 0.409      | -            | -                | -                | -         |    -5.36 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3136 | 2024-04-03 | Elevate          | L   | 0.403      | -            | -                | -                | -         |    -4.11 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3138 | 2024-04-03 | Elevate          | W   | 0.402      | 0.477        | 0.027 (0.005)    | 0.505 (0.097)    | -         |     8.75 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3320 | 2024-03-26 | Wildcard         | L   | 0.350      | -            | -                | -                | -         |    -4.71 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3325 | 2024-03-26 | Wildcard         | W   | 0.349      | 0.477        | 0.055 (0.009)    | 0.501 (0.083)    | -         |     6.43 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3409 | 2024-03-20 | Perseverance     | L   | 0.309      | -            | -                | -                | -         |    -6.61 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3411 | 2024-03-20 | Perseverance     | W   | 0.309      | -            | -                | -                | -         |     3.17 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3454 | 2024-03-17 | Akimbo           | W   | 0.289      | -            | -                | -                | 1 (0.289) |     3.35 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3456 | 2024-03-17 | Akimbo           | W   | 0.288      | -            | -                | -                | 1 (0.288) |     2.37 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3466 | 2024-03-17 | WICKED           | W   | 0.287      | -            | -                | -                | 1 (0.287) |     1.65 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3710 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.223      | -            | -                | -                | -         |     2.68 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3711 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.223      | -            | -                | -                | -         |    -4.40 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3738 | 2024-03-06 | MIGHT            | W   | 0.216      | -            | -                | -                | -         |     1.03 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3739 | 2024-03-06 | MIGHT            | L   | 0.216      | -            | -                | -                | -         |    -5.82 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3776 | 2024-03-05 | Take Flyte       | W   | 0.210      | -            | -                | -                | -         |     1.99 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3778 | 2024-03-05 | Take Flyte       | W   | 0.209      | -            | -                | -                | -         |     2.02 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     3998 | 2024-02-24 | Limitless        | L   | 0.142      | -            | -                | -                | -         |    -3.38 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4194 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.088      | -            | -                | -                | -         |    -1.77 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,137.78)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.849 | $3,000.00      | $2,545.83       |
| 2024-03-17 |      0.289 | $5,500.00      | $1,591.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
