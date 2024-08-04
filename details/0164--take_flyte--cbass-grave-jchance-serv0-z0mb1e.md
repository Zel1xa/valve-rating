### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [164](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  671.9<br />
<br />
Final Rank Value (671.9) = Starting Rank Value (710.7) + Head To Head Adjustments (-38.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 710.7
- 400 + ( ( 0.152 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 710.7


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
|           42 |      107 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -13.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      112 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.41 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      360 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      551 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.34 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      556 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.62 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      613 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.28 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      617 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.56 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      678 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.244 (0.116)    | 0 (0.000) |    15.61 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      684 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.244 (0.116)    | 0 (0.000) |    17.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      730 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      733 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |      989 | 2024-06-15 | Akimbo           | W   | 0.870      | 0.143        | 0.015 (0.002)    | 0.274 (0.034)    | 0 (0.000) |    17.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1025 | 2024-06-14 | E-Xolos LAZER    | W   | 0.863      | 0.143        | 0.011 (0.001)    | 0.389 (0.048)    | 0 (0.000) |    18.32 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1780 | 2024-05-22 | Wildcard         | L   | 0.711      | -            | -                | -                | -         |    -3.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1783 | 2024-05-22 | Wildcard         | L   | 0.710      | -            | -                | -                | -         |    -3.60 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1830 | 2024-05-21 | Elevate          | L   | 0.704      | -            | -                | -                | -         |    -3.33 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1834 | 2024-05-21 | Elevate          | L   | 0.703      | -            | -                | -                | -         |    -3.44 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1867 | 2024-05-20 | MIGHT            | W   | 0.697      | 0.477        | -                | 0.060 (0.020)    | 0 (0.000) |     6.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1871 | 2024-05-20 | MIGHT            | L   | 0.697      | -            | -                | -                | -         |   -15.52 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     1996 | 2024-05-16 | Limitless        | L   | 0.670      | -            | -                | -                | -         |    -7.50 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     1997 | 2024-05-16 | Limitless        | L   | 0.670      | -            | -                | -                | -         |    -7.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2036 | 2024-05-15 | M80              | L   | 0.664      | -            | -                | -                | -         |    -0.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2043 | 2024-05-15 | M80              | L   | 0.663      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2089 | 2024-05-14 | NRG              | L   | 0.657      | -            | -                | -                | -         |    -4.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2094 | 2024-05-14 | NRG              | L   | 0.657      | -            | -                | -                | -         |    -5.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2575 | 2024-04-23 | Nouns            | W   | 0.517      | 0.477        | 0.057 (0.014)    | 0.548 (0.135)    | 0 (0.000) |    12.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2577 | 2024-04-23 | Nouns            | L   | 0.517      | -            | -                | -                | -         |    -3.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2915 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.430      | 0.477        | 0.010 (0.002)    | 0.101 (0.021)    | 0 (0.000) |     7.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2920 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.430      | -            | -                | -                | -         |    -5.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     2973 | 2024-04-09 | Party Astronauts | L   | 0.424      | -            | -                | -                | -         |    -2.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     2979 | 2024-04-09 | Party Astronauts | L   | 0.423      | -            | -                | -                | -         |    -2.81 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3104 | 2024-04-04 | Limitless        | W   | 0.390      | 0.477        | 0.001 (0.000)    | 0.167 (0.031)    | 0 (0.000) |     5.43 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3108 | 2024-04-04 | Limitless        | L   | 0.390      | -            | -                | -                | -         |    -7.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3280 | 2024-03-27 | BOSS             | L   | 0.337      | -            | -                | -                | -         |    -4.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3283 | 2024-03-27 | BOSS             | W   | 0.337      | 0.477        | 0.014 (0.002)    | 0.333 (0.053)    | 0 (0.000) |     6.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3523 | 2024-03-14 | Mythic           | L   | 0.251      | -            | -                | -                | -         |    -3.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3526 | 2024-03-14 | Mythic           | L   | 0.250      | -            | -                | -                | -         |    -3.11 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3773 | 2024-03-05 | LAG              | L   | 0.191      | -            | -                | -                | -         |    -1.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3775 | 2024-03-05 | LAG              | L   | 0.190      | -            | -                | -                | -         |    -1.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4030 | 2024-02-22 | Party Astronauts | L   | 0.110      | -            | -                | -                | -         |    -0.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4272 | 2024-02-13 | Perseverance     | W   | 0.051      | 0.477        | 0.004 (0.000)    | 0.244 (0.006)    | -         |     0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4275 | 2024-02-13 | Perseverance     | L   | 0.050      | -            | -                | -                | -         |    -0.74 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($663.87)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
