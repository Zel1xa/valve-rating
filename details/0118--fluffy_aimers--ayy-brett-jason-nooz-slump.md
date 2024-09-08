### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: ayy, brett, jason, nooz, slump<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
<br />
Final Rank Value:  783.0<br />
<br />
Final Rank Value (783.0) = Starting Rank Value (766.4) + Head To Head Adjustments (16.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 766.4
- 400 + ( ( 0.189 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 766.4


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
|           57 |      101 | 2024-09-04 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.230 (0.110)    | 0 (0.000) |     9.51 | ayy, brett, jason, nooz, slump           |
|           56 |      103 | 2024-09-04 | Take Flyte       | W   | 1.000      | 0.477        | 0.002 (0.001)    | 0.230 (0.110)    | 0 (0.000) |    10.26 | ayy, brett, jason, nooz, slump           |
|           55 |      193 | 2024-09-01 | Liquid           | L   | 1.000      | -            | -                | -                | -         |    -0.25 | brett, jason, MarKE, nooz, slump         |
|           54 |      209 | 2024-08-31 | LAG              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.371 (0.053)    | 0 (0.000) |    11.39 | brett, jason, MarKE, nooz, slump         |
|           53 |      211 | 2024-08-31 | Liquid           | L   | 1.000      | -            | -                | -                | -         |    -0.20 | brett, jason, MarKE, nooz, slump         |
|           52 |      300 | 2024-08-28 | Legacy           | L   | 1.000      | -            | -                | -                | -         |    -5.85 | brett, jason, MarKE, nooz, slump         |
|           51 |      306 | 2024-08-28 | E-Xolos LAZER    | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.460 (0.066)    | 0 (0.000) |    16.68 | brett, jason, MarKE, nooz, slump         |
|           50 |      365 | 2024-08-27 | Party Astronauts | W   | 1.000      | 0.143        | 0.033 (0.005)    | 0.484 (0.069)    | 0 (0.000) |    23.43 | brett, jason, MarKE, nooz, slump         |
|           49 |      413 | 2024-08-26 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.20 | brett, jason, MarKE, nooz, slump         |
|           48 |      435 | 2024-08-26 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.38 | brett, jason, MarKE, nooz, slump         |
|           47 |      700 | 2024-08-19 | Priority         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.04 | brett, jason, MarKE, nooz, slump         |
|           46 |      701 | 2024-08-19 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.91 | brett, jason, MarKE, nooz, slump         |
|           45 |      703 | 2024-08-19 | undefined        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.98 | brett, jason, MarKE, nooz, slump         |
|           44 |      854 | 2024-08-13 | Limitless        | L   | 1.000      | -            | -                | -                | -         |   -24.07 | bezymecc, brett, jason, sacrifice, slump |
|           43 |      857 | 2024-08-13 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     6.92 | bezymecc, brett, jason, sacrifice, slump |
|           42 |      861 | 2024-08-13 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -4.22 | bezymecc, brett, jason, sacrifice, slump |
|           41 |      864 | 2024-08-13 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -4.40 | bezymecc, brett, jason, sacrifice, slump |
|           40 |      905 | 2024-08-12 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -14.56 | bezymecc, brett, jason, sacrifice, slump |
|           39 |     1017 | 2024-08-08 | Final Form       | W   | 0.996      | 0.371        | -                | 0.137 (0.050)    | -         |     8.53 | bezymecc, brett, jason, sacrifice, slump |
|           38 |     1097 | 2024-08-06 | M80              | L   | 0.984      | -            | -                | -                | -         |    -2.50 | bezymecc, brett, jason, sacrifice, slump |
|           37 |     1101 | 2024-08-06 | M80              | L   | 0.983      | -            | -                | -                | -         |    -2.56 | bezymecc, brett, jason, sacrifice, slump |
|           36 |     1161 | 2024-08-04 | Homyno           | W   | 0.969      | 0.371        | 0.004 (0.001)    | 0.143 (0.051)    | -         |    11.66 | bezymecc, brett, jason, sacrifice, slump |
|           35 |     1304 | 2024-07-31 | Mythic           | L   | 0.943      | -            | -                | -                | -         |   -15.26 | bezymecc, brett, jason, sacrifice, slump |
|           34 |     1306 | 2024-07-31 | Mythic           | W   | 0.943      | 0.477        | 0.007 (0.003)    | 0.276 (0.124)    | -         |    14.49 | bezymecc, brett, jason, sacrifice, slump |
|           33 |     1504 | 2024-07-25 | NoVum            | W   | 0.903      | -            | -                | -                | -         |     4.03 | bezymecc, brett, jason, sacrifice, slump |
|           32 |     1542 | 2024-07-24 | E-Xolos LAZER    | L   | 0.897      | -            | -                | -                | -         |   -12.56 | bezymecc, brett, jason, sacrifice, slump |
|           31 |     1546 | 2024-07-24 | E-Xolos LAZER    | W   | 0.897      | 0.477        | 0.008 (0.003)    | 0.460 (0.197)    | -         |    15.94 | bezymecc, brett, jason, sacrifice, slump |
|           30 |     1577 | 2024-07-23 | Party Astronauts | L   | 0.890      | -            | -                | -                | -         |    -7.55 | bezymecc, brett, jason, sacrifice, slump |
|           29 |     1579 | 2024-07-23 | Party Astronauts | W   | 0.890      | 0.477        | 0.033 (0.014)    | 0.484 (0.205)    | -         |    21.00 | bezymecc, brett, jason, sacrifice, slump |
|           28 |     1865 | 2024-07-16 | NRG              | L   | 0.844      | -            | -                | -                | -         |    -6.77 | bezymecc, brett, jason, sacrifice, slump |
|           27 |     1870 | 2024-07-16 | NRG              | L   | 0.843      | -            | -                | -                | -         |    -7.17 | bezymecc, brett, jason, sacrifice, slump |
|           26 |     2214 | 2024-06-14 | timbermen        | L   | 0.630      | -            | -                | -                | -         |    -4.75 | brett, jason, nooz, PNDLM, sacrifice     |
|           25 |     2448 | 2024-06-08 | Perseverance     | W   | 0.588      | -            | -                | -                | -         |     4.48 | brett, jason, nooz, PNDLM, sacrifice     |
|           24 |     2539 | 2024-06-06 | Akimbo           | L   | 0.577      | -            | -                | -                | -         |    -9.54 | brett, jason, nooz, PNDLM, sacrifice     |
|           23 |     2556 | 2024-06-06 | NRG              | L   | 0.575      | -            | -                | -                | -         |    -6.02 | brett, jason, nooz, PNDLM, sacrifice     |
|           22 |     2565 | 2024-06-06 | M80              | L   | 0.575      | -            | -                | -                | -         |    -1.84 | brett, jason, nooz, PNDLM, sacrifice     |
|           21 |     2624 | 2024-06-05 | NRG              | L   | 0.568      | -            | -                | -                | -         |    -6.30 | brett, jason, nooz, PNDLM, sacrifice     |
|           20 |     2707 | 2024-06-03 | Akimbo           | W   | 0.555      | -            | -                | -                | -         |     5.58 | brett, jason, nooz, PNDLM, sacrifice     |
|           19 |     3019 | 2024-05-21 | Nouns            | L   | 0.471      | -            | -                | -                | -         |    -4.13 | brett, jason, nooz, PNDLM, sacrifice     |
|           18 |     3022 | 2024-05-21 | Nouns            | L   | 0.470      | -            | -                | -                | -         |    -4.27 | brett, jason, nooz, PNDLM, sacrifice     |
|           17 |     3059 | 2024-05-20 | Phoenix          | W   | 0.463      | 0.477        | 0.003 (0.001)    | -                | -         |     6.75 | brett, jason, nooz, PNDLM, sacrifice     |
|           16 |     3063 | 2024-05-20 | Phoenix          | L   | 0.463      | -            | -                | -                | -         |    -8.03 | brett, jason, nooz, PNDLM, sacrifice     |
|           15 |     3098 | 2024-05-19 | Nouns            | L   | 0.455      | -            | -                | -                | -         |    -4.30 | brett, jason, nooz, PNDLM, sacrifice     |
|           14 |     3152 | 2024-05-17 | timbermen        | L   | 0.444      | -            | -                | -                | -         |    -3.68 | brett, jason, nooz, PNDLM, sacrifice     |
|           13 |     3153 | 2024-05-17 | timbermen        | L   | 0.443      | -            | -                | -                | -         |    -3.79 | brett, jason, nooz, PNDLM, sacrifice     |
|           12 |     3186 | 2024-05-16 | Party Astronauts | L   | 0.437      | -            | -                | -                | -         |    -4.85 | brett, jason, nooz, PNDLM, sacrifice     |
|           11 |     3189 | 2024-05-16 | Party Astronauts | L   | 0.437      | -            | -                | -                | -         |    -5.02 | brett, jason, nooz, PNDLM, sacrifice     |
|           10 |     3222 | 2024-05-15 | MIGHT            | W   | 0.430      | -            | -                | -                | -         |     2.35 | brett, jason, nooz, PNDLM, sacrifice     |
|            9 |     3229 | 2024-05-15 | MIGHT            | W   | 0.430      | -            | -                | -                | -         |     2.40 | brett, jason, nooz, PNDLM, sacrifice     |
|            8 |     3278 | 2024-05-14 | Wildcard         | L   | 0.424      | -            | -                | -                | -         |    -2.93 | ayy, jason, nooz, PNDLM, sacrifice       |
|            7 |     3283 | 2024-05-14 | Wildcard         | L   | 0.423      | -            | -                | -                | -         |    -3.01 | ayy, jason, nooz, PNDLM, sacrifice       |
|            6 |     3420 | 2024-05-09 | Limitless        | W   | 0.391      | -            | -                | -                | -         |     3.89 | ayy, jason, nooz, PNDLM, sacrifice       |
|            5 |     3423 | 2024-05-09 | Limitless        | L   | 0.390      | -            | -                | -                | -         |    -8.58 | ayy, jason, nooz, PNDLM, sacrifice       |
|            4 |     3802 | 2024-04-21 | For Fun          | W   | 0.270      | -            | -                | -                | 1 (0.270) |     2.59 | ayy, brett, Fr3nk1e, jason, PNDLM        |
|            3 |     3804 | 2024-04-21 | Will to Win      | W   | 0.269      | -            | -                | -                | 1 (0.269) |     1.61 | ayy, brett, Fr3nk1e, jason, PNDLM        |
|            2 |     4111 | 2024-04-10 | Take Flyte       | W   | 0.197      | -            | -                | -                | -         |     2.41 | ayy, jason, nooz, PNDLM, sacrifice       |
|            1 |     4297 | 2024-04-04 | BOSS             | L   | 0.157      | -            | -                | -                | -         |    -2.39 | ayy, intra, jason, nooz, sacrifice       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,893.97)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.596 | $1,200.00      | $715.67         |
| 2024-04-21 |      0.270 | $4,357.00      | $1,178.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
