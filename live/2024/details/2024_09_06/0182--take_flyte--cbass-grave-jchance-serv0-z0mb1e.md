### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [182](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Americas]( ../../standings_americas_2024_09_06.md)<br />
Regional Rank: [48]( ../../standings_americas_2024_09_06.md)<br />
<br />
Final Rank Value:  628.5<br />
<br />
Final Rank Value (628.5) = Starting Rank Value (692.5) + Head To Head Adjustments (-64.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.065[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 692.5
- 400 + ( ( 0.150 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 692.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       64 | 2024-09-04 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |    -9.47 | cbass, Grave, jchancE, serv0, z0mb1e |
|           46 |       66 | 2024-09-04 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -10.22 | cbass, Grave, jchancE, serv0, z0mb1e |
|           45 |      327 | 2024-08-27 | Legacy           | L   | 1.000      | -            | -                | -                | -         |    -3.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|           44 |      379 | 2024-08-26 | LAG              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.385 (0.055)    | 0 (0.000) |    17.33 | cbass, Champ, jchancE, serv0, z0mb1e |
|           43 |     1007 | 2024-08-07 | timbermen        | L   | 1.000      | -            | -                | -                | -         |    -5.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           42 |     1010 | 2024-08-07 | timbermen        | L   | 1.000      | -            | -                | -                | -         |    -6.28 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |     1062 | 2024-08-06 | BOSS             | W   | 0.996      | 0.477        | 0.013 (0.006)    | 0.413 (0.196)    | 0 (0.000) |    21.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |     1066 | 2024-08-06 | BOSS             | L   | 0.995      | -            | -                | -                | -         |    -9.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |     1123 | 2024-08-04 | Final Form       | L   | 0.982      | -            | -                | -                | -         |   -19.37 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |     1154 | 2024-08-03 | Wildcard         | L   | 0.974      | -            | -                | -                | -         |    -3.22 | cbass, Champ, jchancE, serv0, z0mb1e |
|           37 |     1258 | 2024-07-31 | Revenge Nation   | L   | 0.956      | -            | -                | -                | -         |   -13.51 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |     1263 | 2024-07-31 | Revenge Nation   | L   | 0.955      | -            | -                | -                | -         |   -14.69 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |     1508 | 2024-07-24 | InControl        | W   | 0.909      | 0.371        | -                | 0.115 (0.039)    | 0 (0.000) |     8.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |     1702 | 2024-07-18 | Wildcard         | L   | 0.869      | -            | -                | -                | -         |    -4.25 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |     1707 | 2024-07-18 | Wildcard         | L   | 0.869      | -            | -                | -                | -         |    -4.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |     1764 | 2024-07-17 | Party Astronauts | L   | 0.862      | -            | -                | -                | -         |    -5.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1768 | 2024-07-17 | Party Astronauts | L   | 0.862      | -            | -                | -                | -         |    -5.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1829 | 2024-07-16 | Phoenix          | W   | 0.856      | 0.477        | 0.003 (0.001)    | 0.223 (0.091)    | 0 (0.000) |    13.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1835 | 2024-07-16 | Phoenix          | W   | 0.855      | 0.477        | 0.003 (0.001)    | 0.223 (0.091)    | 0 (0.000) |    14.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1883 | 2024-07-15 | Nouns            | L   | 0.849      | -            | -                | -                | -         |    -4.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1887 | 2024-07-15 | Nouns            | L   | 0.849      | -            | -                | -                | -         |    -5.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|           26 |     2143 | 2024-06-15 | Akimbo           | W   | 0.649      | 0.143        | 0.010 (0.001)    | 0.300 (0.028)    | 0 (0.000) |    11.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           25 |     2179 | 2024-06-14 | E-Xolos LAZER    | W   | 0.642      | 0.143        | 0.008 (0.001)    | 0.474 (0.043)    | 0 (0.000) |    13.42 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     2934 | 2024-05-22 | Wildcard         | L   | 0.489      | -            | -                | -                | -         |    -1.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2937 | 2024-05-22 | Wildcard         | L   | 0.489      | -            | -                | -                | -         |    -1.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2984 | 2024-05-21 | timbermen        | L   | 0.482      | -            | -                | -                | -         |    -2.66 | cbass, Champ, jchancE, serv0, z0mb1e |
|           21 |     2988 | 2024-05-21 | timbermen        | L   | 0.482      | -            | -                | -                | -         |    -2.73 | cbass, Champ, jchancE, serv0, z0mb1e |
|           20 |     3021 | 2024-05-20 | MIGHT            | W   | 0.476      | -            | -                | -                | 0 (0.000) |     4.20 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     3025 | 2024-05-20 | MIGHT            | L   | 0.475      | -            | -                | -                | -         |   -11.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     3150 | 2024-05-16 | Carpe Diem       | L   | 0.449      | -            | -                | -                | -         |    -6.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     3151 | 2024-05-16 | Carpe Diem       | L   | 0.449      | -            | -                | -                | -         |    -6.29 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     3190 | 2024-05-15 | M80              | L   | 0.442      | -            | -                | -                | -         |    -1.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     3197 | 2024-05-15 | M80              | L   | 0.442      | -            | -                | -                | -         |    -1.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     3243 | 2024-05-14 | NRG              | L   | 0.435      | -            | -                | -                | -         |    -3.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3248 | 2024-05-14 | NRG              | L   | 0.435      | -            | -                | -                | -         |    -3.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3729 | 2024-04-23 | Nouns            | W   | 0.296      | 0.477        | 0.056 (0.008)    | 0.536 (0.075)    | 0 (0.000) |     7.15 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3731 | 2024-04-23 | Nouns            | L   | 0.295      | -            | -                | -                | -         |    -2.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     4069 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.209      | 0.477        | 0.002 (0.000)    | -                | 0 (0.000) |     2.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     4074 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.209      | -            | -                | -                | -         |    -2.53 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     4127 | 2024-04-09 | Party Astronauts | L   | 0.202      | -            | -                | -                | -         |    -1.66 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     4133 | 2024-04-09 | Party Astronauts | L   | 0.202      | -            | -                | -                | -         |    -1.68 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     4258 | 2024-04-04 | Limitless        | W   | 0.169      | 0.477        | 0.001 (0.000)    | 0.099 (0.008)    | -         |     2.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     4262 | 2024-04-04 | Limitless        | L   | 0.169      | -            | -                | -                | -         |    -3.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     4434 | 2024-03-27 | BOSS             | L   | 0.116      | -            | -                | -                | -         |    -1.37 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4437 | 2024-03-27 | BOSS             | W   | 0.116      | 0.477        | 0.013 (0.001)    | 0.413 (0.023)    | -         |     2.29 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4677 | 2024-03-14 | Mythic           | L   | 0.029      | -            | -                | -                | -         |    -0.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4680 | 2024-03-14 | Mythic           | L   | 0.029      | -            | -                | -                | -         |    -0.35 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($486.65)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
