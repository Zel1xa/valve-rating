### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [182](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
<br />
Final Rank Value:  623.9<br />
<br />
Final Rank Value (623.9) = Starting Rank Value (687.6) + Head To Head Adjustments (-63.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 687.6
- 400 + ( ( 0.149 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 687.6


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
|           47 |      101 | 2024-09-04 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |    -9.51 | cbass, Grave, jchancE, serv0, z0mb1e |
|           46 |      103 | 2024-09-04 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -10.26 | cbass, Grave, jchancE, serv0, z0mb1e |
|           45 |      364 | 2024-08-27 | Legacy           | L   | 1.000      | -            | -                | -                | -         |    -3.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|           44 |      416 | 2024-08-26 | LAG              | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.371 (0.053)    | 0 (0.000) |    17.32 | cbass, Champ, jchancE, serv0, z0mb1e |
|           43 |     1044 | 2024-08-07 | timbermen        | L   | 0.990      | -            | -                | -                | -         |    -5.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           42 |     1047 | 2024-08-07 | timbermen        | L   | 0.990      | -            | -                | -                | -         |    -6.27 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |     1099 | 2024-08-06 | BOSS             | W   | 0.984      | 0.477        | 0.013 (0.006)    | 0.401 (0.188)    | 0 (0.000) |    20.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |     1103 | 2024-08-06 | BOSS             | L   | 0.983      | -            | -                | -                | -         |    -9.78 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |     1160 | 2024-08-04 | Final Form       | L   | 0.970      | -            | -                | -                | -         |   -19.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |     1191 | 2024-08-03 | Wildcard         | L   | 0.963      | -            | -                | -                | -         |    -3.16 | cbass, Champ, jchancE, serv0, z0mb1e |
|           37 |     1295 | 2024-07-31 | Revenge Nation   | L   | 0.944      | -            | -                | -                | -         |   -13.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |     1300 | 2024-07-31 | Revenge Nation   | L   | 0.943      | -            | -                | -                | -         |   -14.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |     1545 | 2024-07-24 | InControl        | W   | 0.897      | 0.371        | -                | 0.112 (0.037)    | 0 (0.000) |     8.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |     1739 | 2024-07-18 | Wildcard         | L   | 0.857      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |     1742 | 2024-07-18 | Wildcard         | L   | 0.857      | -            | -                | -                | -         |    -4.30 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |     1801 | 2024-07-17 | Party Astronauts | L   | 0.850      | -            | -                | -                | -         |    -5.60 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1805 | 2024-07-17 | Party Astronauts | L   | 0.850      | -            | -                | -                | -         |    -5.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1866 | 2024-07-16 | Phoenix          | W   | 0.844      | 0.477        | 0.003 (0.001)    | 0.214 (0.086)    | 0 (0.000) |    12.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1872 | 2024-07-16 | Phoenix          | W   | 0.843      | 0.477        | 0.003 (0.001)    | 0.214 (0.086)    | 0 (0.000) |    13.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1920 | 2024-07-15 | Nouns            | L   | 0.837      | -            | -                | -                | -         |    -4.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1924 | 2024-07-15 | Nouns            | L   | 0.837      | -            | -                | -                | -         |    -5.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           26 |     2180 | 2024-06-15 | Akimbo           | W   | 0.637      | 0.143        | 0.010 (0.001)    | 0.291 (0.026)    | 0 (0.000) |    11.61 | cbass, Grave, jchancE, serv0, z0mb1e |
|           25 |     2216 | 2024-06-14 | E-Xolos LAZER    | W   | 0.630      | 0.143        | 0.008 (0.001)    | 0.460 (0.041)    | 0 (0.000) |    13.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     2971 | 2024-05-22 | Wildcard         | L   | 0.477      | -            | -                | -                | -         |    -1.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2974 | 2024-05-22 | Wildcard         | L   | 0.477      | -            | -                | -                | -         |    -1.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     3021 | 2024-05-21 | timbermen        | L   | 0.470      | -            | -                | -                | -         |    -2.65 | cbass, Champ, jchancE, serv0, z0mb1e |
|           21 |     3025 | 2024-05-21 | timbermen        | L   | 0.470      | -            | -                | -                | -         |    -2.71 | cbass, Champ, jchancE, serv0, z0mb1e |
|           20 |     3058 | 2024-05-20 | MIGHT            | W   | 0.464      | -            | -                | -                | 0 (0.000) |     4.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     3062 | 2024-05-20 | MIGHT            | L   | 0.463      | -            | -                | -                | -         |   -10.69 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     3187 | 2024-05-16 | Carpe Diem       | L   | 0.437      | -            | -                | -                | -         |    -5.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     3188 | 2024-05-16 | Carpe Diem       | L   | 0.437      | -            | -                | -                | -         |    -6.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     3227 | 2024-05-15 | M80              | L   | 0.430      | -            | -                | -                | -         |    -1.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     3234 | 2024-05-15 | M80              | L   | 0.430      | -            | -                | -                | -         |    -1.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     3280 | 2024-05-14 | NRG              | L   | 0.424      | -            | -                | -                | -         |    -3.68 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3285 | 2024-05-14 | NRG              | L   | 0.423      | -            | -                | -                | -         |    -3.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3766 | 2024-04-23 | Nouns            | W   | 0.284      | 0.477        | 0.056 (0.008)    | 0.519 (0.070)    | 0 (0.000) |     6.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3768 | 2024-04-23 | Nouns            | L   | 0.283      | -            | -                | -                | -         |    -2.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     4106 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.197      | 0.477        | 0.002 (0.000)    | -                | 0 (0.000) |     2.55 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     4111 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.197      | -            | -                | -                | -         |    -2.41 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     4164 | 2024-04-09 | Party Astronauts | L   | 0.190      | -            | -                | -                | -         |    -1.58 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     4170 | 2024-04-09 | Party Astronauts | L   | 0.190      | -            | -                | -                | -         |    -1.60 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     4295 | 2024-04-04 | Limitless        | W   | 0.157      | 0.477        | 0.001 (0.000)    | 0.094 (0.007)    | -         |     2.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     4299 | 2024-04-04 | Limitless        | L   | 0.157      | -            | -                | -                | -         |    -2.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     4471 | 2024-03-27 | BOSS             | L   | 0.104      | -            | -                | -                | -         |    -1.24 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4474 | 2024-03-27 | BOSS             | W   | 0.104      | 0.477        | 0.013 (0.001)    | 0.401 (0.020)    | -         |     2.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4714 | 2024-03-14 | Mythic           | L   | 0.017      | -            | -                | -                | -         |    -0.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4717 | 2024-03-14 | Mythic           | L   | 0.017      | -            | -                | -                | -         |    -0.21 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($477.11)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
