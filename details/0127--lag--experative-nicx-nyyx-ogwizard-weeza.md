### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  782.2<br />
<br />
Final Rank Value (782.2) = Starting Rank Value (865.1) + Head To Head Adjustments (-82.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.130[<sup>2</sup>](#table1)
- LAN Wins: 0.100[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 865.1
- 400 + ( ( 0.226 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 865.1


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
|           56 |       11 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.36 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           55 |       16 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -15.68 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      108 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -20.53 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      233 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.71 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      259 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.135 (0.064)    | 0 (0.000) |     9.14 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      263 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | -                | 0 (0.000) |     9.84 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      384 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -9.37 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      525 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.05 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      532 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -18.59 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      593 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -12.61 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      599 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.055 (0.026)    | 0.501 (0.239)    | 0 (0.000) |    19.18 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      645 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    19.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      650 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    20.98 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      978 | 2024-06-13 | Mythic           | L   | 0.877      | -            | -                | -                | -         |   -14.74 | based, Experative, nicx, Nyyx, ogwizard |
|           42 |     1154 | 2024-06-08 | Homyno           | W   | 0.843      | 0.371        | 0.008 (0.002)    | -                | 0 (0.000) |     8.34 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1212 | 2024-06-07 | Wildcard         | L   | 0.837      | -            | -                | -                | -         |    -8.67 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1300 | 2024-06-06 | Vibe             | W   | 0.828      | -            | -                | -                | 0 (0.000) |     2.08 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1343 | 2024-06-05 | NRG              | L   | 0.824      | -            | -                | -                | -         |   -10.91 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1354 | 2024-06-05 | Limitless        | W   | 0.823      | -            | -                | -                | -         |    10.18 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1397 | 2024-06-04 | Limitless        | W   | 0.817      | -            | -                | -                | -         |    10.85 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1407 | 2024-06-04 | Retirement Home  | W   | 0.816      | -            | -                | -                | -         |     2.00 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1715 | 2024-05-22 | Limitless        | W   | 0.731      | -            | -                | -                | -         |     5.22 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1718 | 2024-05-22 | Limitless        | W   | 0.730      | -            | -                | -                | -         |     5.47 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1723 | 2024-05-22 | Wildcard         | L   | 0.730      | -            | -                | -                | -         |    -7.52 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1796 | 2024-05-21 | BOSS             | W   | 0.722      | 0.384        | 0.014 (0.004)    | 0.334 (0.093)    | -         |    10.02 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     1992 | 2024-05-15 | NRG              | L   | 0.684      | -            | -                | -                | -         |    -7.88 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     1999 | 2024-05-15 | NRG              | L   | 0.684      | -            | -                | -                | -         |    -8.34 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2051 | 2024-05-14 | Limitless        | W   | 0.677      | -            | -                | -                | -         |     8.50 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2057 | 2024-05-14 | Limitless        | L   | 0.677      | -            | -                | -                | -         |   -13.16 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2195 | 2024-05-09 | M80              | L   | 0.644      | -            | -                | -                | -         |    -1.81 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2200 | 2024-05-09 | M80              | L   | 0.644      | -            | -                | -                | -         |    -1.84 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2215 | 2024-05-08 | Party Astronauts | L   | 0.637      | -            | -                | -                | -         |    -7.23 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2220 | 2024-05-08 | Party Astronauts | L   | 0.637      | -            | -                | -                | -         |    -7.62 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2898 | 2024-04-10 | Mythic           | W   | 0.451      | 0.477        | -                | 0.304 (0.065)    | -         |     5.63 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2903 | 2024-04-10 | Mythic           | W   | 0.450      | 0.477        | -                | 0.304 (0.065)    | -         |     5.84 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2954 | 2024-04-09 | BOSS             | L   | 0.444      | -            | -                | -                | -         |    -7.74 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     2957 | 2024-04-09 | BOSS             | L   | 0.444      | -            | -                | -                | -         |    -8.04 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3085 | 2024-04-04 | Nouns            | W   | 0.411      | 0.477        | 0.058 (0.011)    | 0.557 (0.109)    | -         |     7.64 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3089 | 2024-04-04 | Nouns            | L   | 0.410      | -            | -                | -                | -         |    -5.38 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3132 | 2024-04-03 | Elevate          | L   | 0.404      | -            | -                | -                | -         |    -4.12 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3134 | 2024-04-03 | Elevate          | W   | 0.404      | 0.477        | 0.027 (0.005)    | 0.505 (0.097)    | -         |     8.79 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3316 | 2024-03-26 | Wildcard         | L   | 0.351      | -            | -                | -                | -         |    -4.73 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3321 | 2024-03-26 | Wildcard         | W   | 0.351      | 0.477        | 0.055 (0.009)    | 0.501 (0.084)    | -         |     6.46 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3405 | 2024-03-20 | Perseverance     | L   | 0.310      | -            | -                | -                | -         |    -6.64 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3407 | 2024-03-20 | Perseverance     | W   | 0.310      | -            | -                | -                | -         |     3.18 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3450 | 2024-03-17 | Akimbo           | W   | 0.291      | -            | -                | -                | 1 (0.291) |     3.37 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3452 | 2024-03-17 | Akimbo           | W   | 0.290      | -            | -                | -                | 1 (0.290) |     2.38 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3462 | 2024-03-17 | WICKED           | W   | 0.289      | -            | -                | -                | 1 (0.289) |     1.66 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3706 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.224      | -            | -                | -                | -         |     2.70 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3707 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.224      | -            | -                | -                | -         |    -4.43 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3734 | 2024-03-06 | MIGHT            | W   | 0.217      | -            | -                | -                | -         |     1.03 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3735 | 2024-03-06 | MIGHT            | L   | 0.217      | -            | -                | -                | -         |    -5.86 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3772 | 2024-03-05 | Take Flyte       | W   | 0.211      | -            | -                | -                | -         |     2.00 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3774 | 2024-03-05 | Take Flyte       | W   | 0.211      | -            | -                | -                | -         |     2.03 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     3994 | 2024-02-24 | Limitless        | L   | 0.143      | -            | -                | -                | -         |    -3.42 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4190 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.090      | -            | -                | -                | -         |    -1.80 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,149.58)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.850 | $3,000.00      | $2,550.00       |
| 2024-03-17 |      0.291 | $5,500.00      | $1,599.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
