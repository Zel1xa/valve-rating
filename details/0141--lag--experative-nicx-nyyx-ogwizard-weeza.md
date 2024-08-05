### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [141](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  754.8<br />
<br />
Final Rank Value (754.8) = Starting Rank Value (839.2) + Head To Head Adjustments (-84.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.112[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 839.2
- 400 + ( ( 0.214 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 839.2


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
|           55 |      149 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.26 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      154 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.47 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      245 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -19.54 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      370 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.02 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      396 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.133 (0.063)    | 0 (0.000) |     9.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      399 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.133 (0.063)    | 0 (0.000) |    10.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      519 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.76 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      653 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.36 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      660 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.86 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      721 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -17.99 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      727 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.237 (0.113)    | 0 (0.000) |    13.31 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      768 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.519 (0.248)    | 0 (0.000) |    20.25 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      772 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.519 (0.248)    | 0 (0.000) |    21.90 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1109 | 2024-06-13 | Mythic           | L   | 0.850      | -            | -                | -                | -         |   -13.70 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1281 | 2024-06-08 | Homyno           | W   | 0.816      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.72 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1336 | 2024-06-07 | Wildcard         | L   | 0.810      | -            | -                | -                | -         |    -8.69 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1418 | 2024-06-06 | Vibe             | W   | 0.801      | -            | -                | -                | 0 (0.000) |     2.29 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1460 | 2024-06-05 | NRG              | L   | 0.797      | -            | -                | -                | -         |   -10.10 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1470 | 2024-06-05 | Limitless        | W   | 0.796      | -            | -                | -                | -         |    10.45 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1512 | 2024-06-04 | Limitless        | W   | 0.790      | -            | -                | -                | -         |    11.13 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1522 | 2024-06-04 | Retirement Home  | W   | 0.789      | -            | -                | -                | -         |     2.24 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1827 | 2024-05-22 | Limitless        | W   | 0.704      | -            | -                | -                | -         |     5.56 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1830 | 2024-05-22 | Limitless        | W   | 0.703      | -            | -                | -                | -         |     5.83 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1835 | 2024-05-22 | Wildcard         | L   | 0.703      | -            | -                | -                | -         |    -7.59 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2078 | 2024-05-15 | NRG              | L   | 0.657      | -            | -                | -                | -         |    -7.34 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2085 | 2024-05-15 | NRG              | L   | 0.657      | -            | -                | -                | -         |    -7.75 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2131 | 2024-05-14 | Limitless        | W   | 0.650      | -            | -                | -                | -         |     8.54 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2137 | 2024-05-14 | Limitless        | L   | 0.650      | -            | -                | -                | -         |   -12.25 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2272 | 2024-05-09 | M80              | L   | 0.617      | -            | -                | -                | -         |    -1.70 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2277 | 2024-05-09 | M80              | L   | 0.617      | -            | -                | -                | -         |    -1.73 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2292 | 2024-05-08 | Party Astronauts | L   | 0.610      | -            | -                | -                | -         |    -6.72 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2297 | 2024-05-08 | Party Astronauts | L   | 0.610      | -            | -                | -                | -         |    -7.07 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2959 | 2024-04-10 | Mythic           | W   | 0.424      | 0.477        | 0.010 (0.002)    | 0.297 (0.060)    | -         |     5.55 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2964 | 2024-04-10 | Mythic           | W   | 0.423      | 0.477        | -                | 0.297 (0.060)    | -         |     5.75 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     3015 | 2024-04-09 | BOSS             | L   | 0.417      | -            | -                | -                | -         |    -7.09 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     3018 | 2024-04-09 | BOSS             | L   | 0.417      | -            | -                | -                | -         |    -7.35 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3146 | 2024-04-04 | Nouns            | W   | 0.384      | 0.477        | 0.057 (0.010)    | 0.560 (0.102)    | -         |     7.38 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3150 | 2024-04-04 | Nouns            | L   | 0.383      | -            | -                | -                | -         |    -4.78 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3192 | 2024-04-03 | Elevate          | L   | 0.377      | -            | -                | -                | -         |    -3.61 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3194 | 2024-04-03 | Elevate          | W   | 0.377      | 0.477        | 0.027 (0.005)    | 0.519 (0.093)    | -         |     8.43 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3368 | 2024-03-26 | Wildcard         | L   | 0.324      | -            | -                | -                | -         |    -4.59 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3373 | 2024-03-26 | Wildcard         | W   | 0.324      | 0.477        | 0.048 (0.007)    | 0.435 (0.067)    | -         |     5.72 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3453 | 2024-03-20 | Phoenix          | L   | 0.284      | -            | -                | -                | -         |    -5.86 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3455 | 2024-03-20 | Phoenix          | W   | 0.283      | -            | -                | -                | -         |     3.11 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3498 | 2024-03-17 | Akimbo           | W   | 0.264      | -            | -                | -                | 1 (0.264) |     3.24 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3500 | 2024-03-17 | Akimbo           | W   | 0.263      | -            | -                | -                | 1 (0.263) |     2.31 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3510 | 2024-03-17 | WICKED           | W   | 0.262      | -            | -                | -                | 1 (0.262) |     1.65 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3748 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.197      | -            | -                | -                | -         |     2.50 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3749 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.197      | -            | -                | -                | -         |    -3.77 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3776 | 2024-03-06 | MIGHT            | W   | 0.191      | -            | -                | -                | -         |     0.99 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3777 | 2024-03-06 | MIGHT            | L   | 0.190      | -            | -                | -                | -         |    -5.05 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3814 | 2024-03-05 | Take Flyte       | W   | 0.184      | -            | -                | -                | -         |     1.90 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3816 | 2024-03-05 | Take Flyte       | W   | 0.184      | -            | -                | -                | -         |     1.93 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     4027 | 2024-02-24 | Limitless        | L   | 0.116      | -            | -                | -                | -         |    -2.69 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4217 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.063      | -            | -                | -                | -         |    -1.22 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,920.56)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.823 | $3,000.00      | $2,469.17       |
| 2024-03-17 |      0.264 | $5,500.00      | $1,451.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
