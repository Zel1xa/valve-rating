### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [182](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Americas]( ../../standings_americas_2024_09_07.md)<br />
Regional Rank: [48]( ../../standings_americas_2024_09_07.md)<br />
<br />
Final Rank Value:  628.4<br />
<br />
Final Rank Value (628.4) = Starting Rank Value (692.3) + Head To Head Adjustments (-63.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 692.3
- 400 + ( ( 0.149 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 692.3


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
|           47 |       69 | 2024-09-04 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |    -9.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           46 |       71 | 2024-09-04 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -10.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           45 |      332 | 2024-08-27 | Legacy           | L   | 1.000      | -            | -                | -                | -         |    -3.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           44 |      384 | 2024-08-26 | LAG              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.385 (0.055)    | 0 (0.000) |    17.31 | cbass, Champ, jchancE, serv0, z0mb1e |
|           43 |     1012 | 2024-08-07 | timbermen        | L   | 0.998      | -            | -                | -                | -         |    -5.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           42 |     1015 | 2024-08-07 | timbermen        | L   | 0.998      | -            | -                | -                | -         |    -6.27 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |     1067 | 2024-08-06 | BOSS             | W   | 0.992      | 0.477        | 0.013 (0.006)    | 0.414 (0.196)    | 0 (0.000) |    21.04 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |     1071 | 2024-08-06 | BOSS             | L   | 0.991      | -            | -                | -                | -         |    -9.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |     1128 | 2024-08-04 | Final Form       | L   | 0.978      | -            | -                | -                | -         |   -19.31 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |     1159 | 2024-08-03 | Wildcard         | L   | 0.970      | -            | -                | -                | -         |    -3.21 | cbass, Champ, jchancE, serv0, z0mb1e |
|           37 |     1263 | 2024-07-31 | Revenge Nation   | L   | 0.952      | -            | -                | -                | -         |   -13.49 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |     1268 | 2024-07-31 | Revenge Nation   | L   | 0.951      | -            | -                | -                | -         |   -14.66 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |     1513 | 2024-07-24 | InControl        | W   | 0.905      | 0.371        | -                | 0.115 (0.039)    | 0 (0.000) |     8.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |     1707 | 2024-07-18 | Wildcard         | L   | 0.865      | -            | -                | -                | -         |    -4.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |     1712 | 2024-07-18 | Wildcard         | L   | 0.865      | -            | -                | -                | -         |    -4.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |     1769 | 2024-07-17 | Party Astronauts | L   | 0.858      | -            | -                | -                | -         |    -5.58 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1773 | 2024-07-17 | Party Astronauts | L   | 0.858      | -            | -                | -                | -         |    -5.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1834 | 2024-07-16 | Phoenix          | W   | 0.852      | 0.477        | 0.003 (0.001)    | 0.222 (0.090)    | 0 (0.000) |    13.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1840 | 2024-07-16 | Phoenix          | W   | 0.851      | 0.477        | 0.003 (0.001)    | 0.222 (0.090)    | 0 (0.000) |    14.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1888 | 2024-07-15 | Nouns            | L   | 0.845      | -            | -                | -                | -         |    -4.78 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1892 | 2024-07-15 | Nouns            | L   | 0.845      | -            | -                | -                | -         |    -5.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|           26 |     2148 | 2024-06-15 | Akimbo           | W   | 0.645      | 0.143        | 0.010 (0.001)    | 0.301 (0.028)    | 0 (0.000) |    11.77 | cbass, Grave, jchancE, serv0, z0mb1e |
|           25 |     2184 | 2024-06-14 | E-Xolos LAZER    | W   | 0.638      | 0.143        | 0.008 (0.001)    | 0.474 (0.043)    | 0 (0.000) |    13.33 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     2939 | 2024-05-22 | Wildcard         | L   | 0.485      | -            | -                | -                | -         |    -1.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2942 | 2024-05-22 | Wildcard         | L   | 0.485      | -            | -                | -                | -         |    -1.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2989 | 2024-05-21 | timbermen        | L   | 0.478      | -            | -                | -                | -         |    -2.65 | cbass, Champ, jchancE, serv0, z0mb1e |
|           21 |     2993 | 2024-05-21 | timbermen        | L   | 0.478      | -            | -                | -                | -         |    -2.71 | cbass, Champ, jchancE, serv0, z0mb1e |
|           20 |     3026 | 2024-05-20 | MIGHT            | W   | 0.472      | -            | -                | -                | 0 (0.000) |     4.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     3030 | 2024-05-20 | MIGHT            | L   | 0.471      | -            | -                | -                | -         |   -10.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     3155 | 2024-05-16 | Carpe Diem       | L   | 0.445      | -            | -                | -                | -         |    -6.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     3156 | 2024-05-16 | Carpe Diem       | L   | 0.445      | -            | -                | -                | -         |    -6.23 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     3195 | 2024-05-15 | M80              | L   | 0.438      | -            | -                | -                | -         |    -1.06 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     3202 | 2024-05-15 | M80              | L   | 0.438      | -            | -                | -                | -         |    -1.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     3248 | 2024-05-14 | NRG              | L   | 0.431      | -            | -                | -                | -         |    -3.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3253 | 2024-05-14 | NRG              | L   | 0.431      | -            | -                | -                | -         |    -3.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3734 | 2024-04-23 | Nouns            | W   | 0.292      | 0.477        | 0.056 (0.008)    | 0.536 (0.075)    | 0 (0.000) |     7.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3736 | 2024-04-23 | Nouns            | L   | 0.291      | -            | -                | -                | -         |    -2.15 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     4074 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.205      | 0.477        | 0.002 (0.000)    | -                | 0 (0.000) |     2.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     4079 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.205      | -            | -                | -                | -         |    -2.49 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     4132 | 2024-04-09 | Party Astronauts | L   | 0.198      | -            | -                | -                | -         |    -1.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     4138 | 2024-04-09 | Party Astronauts | L   | 0.198      | -            | -                | -                | -         |    -1.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     4263 | 2024-04-04 | Limitless        | W   | 0.165      | 0.477        | 0.001 (0.000)    | 0.098 (0.008)    | -         |     2.18 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     4267 | 2024-04-04 | Limitless        | L   | 0.165      | -            | -                | -                | -         |    -3.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     4439 | 2024-03-27 | BOSS             | L   | 0.112      | -            | -                | -                | -         |    -1.32 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4442 | 2024-03-27 | BOSS             | W   | 0.112      | 0.477        | 0.013 (0.001)    | 0.414 (0.022)    | -         |     2.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4682 | 2024-03-14 | Mythic           | L   | 0.025      | -            | -                | -                | -         |    -0.31 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4685 | 2024-03-14 | Mythic           | L   | 0.025      | -            | -                | -                | -         |    -0.30 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($483.44)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
