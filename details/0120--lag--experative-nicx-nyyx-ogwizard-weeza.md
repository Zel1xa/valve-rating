### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
<br />
Final Rank Value:  803.6<br />
<br />
Final Rank Value (803.6) = Starting Rank Value (863.7) + Head To Head Adjustments (-60.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.126[<sup>2</sup>](#table1)
- LAN Wins: 0.101[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 863.7
- 400 + ( ( 0.225 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 863.7


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
|           53 |       79 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -20.78 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      204 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.53 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      230 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.135 (0.064)    | 0 (0.000) |     9.31 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      233 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.135 (0.064)    | 0 (0.000) |    10.04 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      353 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -9.43 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      487 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.15 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      494 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -18.70 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      555 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -12.50 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      561 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.055 (0.026)    | 0.501 (0.239)    | 0 (0.000) |    19.29 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      602 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    19.91 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      606 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.56 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |      943 | 2024-06-13 | Mythic           | L   | 0.881      | -            | -                | -                | -         |   -14.54 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1115 | 2024-06-08 | Homyno           | W   | 0.848      | 0.371        | 0.008 (0.002)    | -                | 0 (0.000) |     8.66 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1170 | 2024-06-07 | Wildcard         | L   | 0.841      | -            | -                | -                | -         |    -8.61 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1252 | 2024-06-06 | Vibe             | W   | 0.833      | -            | -                | -                | 0 (0.000) |     2.21 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1294 | 2024-06-05 | NRG              | L   | 0.828      | -            | -                | -                | -         |   -10.91 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1304 | 2024-06-05 | Limitless        | W   | 0.827      | -            | -                | -                | -         |    10.56 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1346 | 2024-06-04 | Limitless        | W   | 0.822      | -            | -                | -                | -         |    11.27 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1356 | 2024-06-04 | Retirement Home  | W   | 0.821      | -            | -                | -                | -         |     2.14 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1661 | 2024-05-22 | Limitless        | W   | 0.735      | 0.477        | -                | 0.170 (0.060)    | -         |     5.49 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1664 | 2024-05-22 | Limitless        | W   | 0.735      | 0.477        | -                | 0.170 (0.060)    | -         |     5.76 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1669 | 2024-05-22 | Wildcard         | L   | 0.734      | -            | -                | -                | -         |    -7.44 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     1912 | 2024-05-15 | NRG              | L   | 0.688      | -            | -                | -                | -         |    -8.02 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     1919 | 2024-05-15 | NRG              | L   | 0.688      | -            | -                | -                | -         |    -8.50 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     1965 | 2024-05-14 | Limitless        | W   | 0.681      | -            | -                | -                | -         |     8.60 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     1971 | 2024-05-14 | Limitless        | L   | 0.681      | -            | -                | -                | -         |   -13.19 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2106 | 2024-05-09 | M80              | L   | 0.648      | -            | -                | -                | -         |    -1.80 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2111 | 2024-05-09 | M80              | L   | 0.648      | -            | -                | -                | -         |    -1.83 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2126 | 2024-05-08 | Party Astronauts | L   | 0.642      | -            | -                | -                | -         |    -7.27 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2131 | 2024-05-08 | Party Astronauts | L   | 0.641      | -            | -                | -                | -         |    -7.66 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2793 | 2024-04-10 | Mythic           | W   | 0.455      | 0.477        | 0.010 (0.002)    | -                | -         |     5.65 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2798 | 2024-04-10 | Mythic           | W   | 0.455      | -            | -                | -                | -         |     5.88 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2849 | 2024-04-09 | BOSS             | L   | 0.448      | -            | -                | -                | -         |    -7.89 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     2852 | 2024-04-09 | BOSS             | L   | 0.448      | -            | -                | -                | -         |    -8.20 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     2980 | 2024-04-04 | Nouns            | W   | 0.415      | 0.477        | 0.058 (0.011)    | 0.546 (0.108)    | -         |     7.74 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     2984 | 2024-04-04 | Nouns            | L   | 0.415      | -            | -                | -                | -         |    -5.42 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3026 | 2024-04-03 | Elevate          | L   | 0.408      | -            | -                | -                | -         |    -4.16 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3028 | 2024-04-03 | Elevate          | W   | 0.408      | 0.477        | 0.027 (0.005)    | 0.505 (0.098)    | -         |     8.88 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3202 | 2024-03-26 | Wildcard         | L   | 0.355      | -            | -                | -                | -         |    -4.95 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3207 | 2024-03-26 | Wildcard         | W   | 0.355      | 0.477        | 0.055 (0.009)    | 0.501 (0.085)    | -         |     6.37 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3287 | 2024-03-20 | Perseverance     | L   | 0.315      | -            | -                | -                | -         |    -6.74 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3289 | 2024-03-20 | Perseverance     | W   | 0.315      | -            | -                | -                | -         |     3.21 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3332 | 2024-03-17 | Akimbo           | W   | 0.295      | -            | -                | -                | 1 (0.295) |     3.42 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3334 | 2024-03-17 | Akimbo           | W   | 0.294      | -            | -                | -                | 1 (0.294) |     2.42 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3344 | 2024-03-17 | WICKED           | W   | 0.293      | -            | -                | -                | 1 (0.293) |     1.69 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3582 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.229      | -            | -                | -                | -         |     2.77 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3583 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.228      | -            | -                | -                | -         |    -4.49 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3610 | 2024-03-06 | MIGHT            | W   | 0.222      | -            | -                | -                | -         |     1.06 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3611 | 2024-03-06 | MIGHT            | L   | 0.222      | -            | -                | -                | -         |    -5.97 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3648 | 2024-03-05 | Take Flyte       | W   | 0.215      | -            | -                | -                | -         |     2.06 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3650 | 2024-03-05 | Take Flyte       | W   | 0.215      | -            | -                | -                | -         |     2.09 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     3861 | 2024-02-24 | Limitless        | L   | 0.147      | -            | -                | -                | -         |    -3.51 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4051 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.094      | -            | -                | -                | -         |    -1.88 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,186.46)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.854 | $3,000.00      | $2,563.01       |
| 2024-03-17 |      0.295 | $5,500.00      | $1,623.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
