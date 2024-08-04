### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  671.9<br />
<br />
Final Rank Value (671.9) = Starting Rank Value (710.7) + Head To Head Adjustments (-38.8)<br />

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
|           42 |       99 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -13.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      104 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.41 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      352 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      543 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.34 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      548 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.62 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      605 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.29 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      609 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.56 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      670 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.244 (0.116)    | 0 (0.000) |    15.61 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      676 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.244 (0.116)    | 0 (0.000) |    17.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      722 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      725 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |      981 | 2024-06-15 | Akimbo           | W   | 0.871      | 0.143        | 0.015 (0.002)    | 0.274 (0.034)    | 0 (0.000) |    17.75 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1017 | 2024-06-14 | E-Xolos LAZER    | W   | 0.864      | 0.143        | 0.011 (0.001)    | 0.389 (0.048)    | 0 (0.000) |    18.33 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1772 | 2024-05-22 | Wildcard         | L   | 0.711      | -            | -                | -                | -         |    -3.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1775 | 2024-05-22 | Wildcard         | L   | 0.711      | -            | -                | -                | -         |    -3.60 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1822 | 2024-05-21 | Elevate          | L   | 0.704      | -            | -                | -                | -         |    -3.33 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1826 | 2024-05-21 | Elevate          | L   | 0.704      | -            | -                | -                | -         |    -3.44 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1859 | 2024-05-20 | MIGHT            | W   | 0.698      | 0.477        | -                | 0.060 (0.020)    | 0 (0.000) |     6.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1863 | 2024-05-20 | MIGHT            | L   | 0.698      | -            | -                | -                | -         |   -15.53 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     1988 | 2024-05-16 | Limitless        | L   | 0.671      | -            | -                | -                | -         |    -7.51 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     1989 | 2024-05-16 | Limitless        | L   | 0.671      | -            | -                | -                | -         |    -7.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2028 | 2024-05-15 | M80              | L   | 0.664      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2035 | 2024-05-15 | M80              | L   | 0.664      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2081 | 2024-05-14 | NRG              | L   | 0.658      | -            | -                | -                | -         |    -4.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2086 | 2024-05-14 | NRG              | L   | 0.657      | -            | -                | -                | -         |    -5.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2567 | 2024-04-23 | Nouns            | W   | 0.518      | 0.477        | 0.057 (0.014)    | 0.548 (0.135)    | 0 (0.000) |    12.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2569 | 2024-04-23 | Nouns            | L   | 0.517      | -            | -                | -                | -         |    -3.37 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2907 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.431      | 0.477        | 0.010 (0.002)    | 0.101 (0.021)    | 0 (0.000) |     7.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2912 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.431      | -            | -                | -                | -         |    -5.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     2965 | 2024-04-09 | Party Astronauts | L   | 0.424      | -            | -                | -                | -         |    -2.75 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     2971 | 2024-04-09 | Party Astronauts | L   | 0.424      | -            | -                | -                | -         |    -2.81 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3096 | 2024-04-04 | Limitless        | W   | 0.391      | 0.477        | 0.001 (0.000)    | 0.167 (0.031)    | 0 (0.000) |     5.45 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3100 | 2024-04-04 | Limitless        | L   | 0.391      | -            | -                | -                | -         |    -7.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3272 | 2024-03-27 | BOSS             | L   | 0.338      | -            | -                | -                | -         |    -4.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3275 | 2024-03-27 | BOSS             | W   | 0.338      | 0.477        | 0.014 (0.002)    | 0.333 (0.054)    | 0 (0.000) |     6.75 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3515 | 2024-03-14 | Mythic           | L   | 0.251      | -            | -                | -                | -         |    -3.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3518 | 2024-03-14 | Mythic           | L   | 0.251      | -            | -                | -                | -         |    -3.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3765 | 2024-03-05 | LAG              | L   | 0.191      | -            | -                | -                | -         |    -1.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3767 | 2024-03-05 | LAG              | L   | 0.191      | -            | -                | -                | -         |    -1.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4022 | 2024-02-22 | Party Astronauts | L   | 0.110      | -            | -                | -                | -         |    -0.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4264 | 2024-02-13 | Perseverance     | W   | 0.051      | 0.477        | 0.004 (0.000)    | 0.244 (0.006)    | -         |     0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4267 | 2024-02-13 | Perseverance     | L   | 0.051      | -            | -                | -                | -         |    -0.75 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($664.44)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
