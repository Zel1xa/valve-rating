### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  672.1<br />
<br />
Final Rank Value (672.1) = Starting Rank Value (710.9) + Head To Head Adjustments (-38.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 710.9
- 400 + ( ( 0.152 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 710.9


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
|           42 |       96 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -13.21 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      101 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.41 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      349 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      540 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.34 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      545 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.62 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      602 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.28 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      606 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.55 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      667 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.244 (0.117)    | 0 (0.000) |    15.61 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      673 | 2024-07-16 | Perseverance     | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.244 (0.117)    | 0 (0.000) |    17.05 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      719 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      722 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |      977 | 2024-06-15 | Akimbo           | W   | 0.874      | 0.143        | 0.015 (0.002)    | 0.275 (0.034)    | 0 (0.000) |    17.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1013 | 2024-06-14 | E-Xolos LAZER    | W   | 0.867      | 0.143        | 0.011 (0.001)    | 0.389 (0.048)    | 0 (0.000) |    18.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1768 | 2024-05-22 | Wildcard         | L   | 0.714      | -            | -                | -                | -         |    -3.49 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1771 | 2024-05-22 | Wildcard         | L   | 0.714      | -            | -                | -                | -         |    -3.61 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1818 | 2024-05-21 | Elevate          | L   | 0.708      | -            | -                | -                | -         |    -3.35 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1822 | 2024-05-21 | Elevate          | L   | 0.707      | -            | -                | -                | -         |    -3.45 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1855 | 2024-05-20 | MIGHT            | W   | 0.701      | 0.477        | -                | 0.060 (0.020)    | 0 (0.000) |     6.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1859 | 2024-05-20 | MIGHT            | L   | 0.701      | -            | -                | -                | -         |   -15.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     1984 | 2024-05-16 | Limitless        | L   | 0.674      | -            | -                | -                | -         |    -7.53 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     1985 | 2024-05-16 | Limitless        | L   | 0.674      | -            | -                | -                | -         |    -7.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2024 | 2024-05-15 | M80              | L   | 0.667      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2031 | 2024-05-15 | M80              | L   | 0.667      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2077 | 2024-05-14 | NRG              | L   | 0.661      | -            | -                | -                | -         |    -4.97 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2082 | 2024-05-14 | NRG              | L   | 0.661      | -            | -                | -                | -         |    -5.19 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2562 | 2024-04-23 | Nouns            | W   | 0.521      | 0.477        | 0.057 (0.014)    | 0.547 (0.136)    | 0 (0.000) |    13.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2564 | 2024-04-23 | Nouns            | L   | 0.521      | -            | -                | -                | -         |    -3.38 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2902 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.434      | 0.477        | 0.010 (0.002)    | 0.102 (0.021)    | 0 (0.000) |     8.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2907 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.434      | -            | -                | -                | -         |    -5.76 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     2960 | 2024-04-09 | Party Astronauts | L   | 0.427      | -            | -                | -                | -         |    -2.76 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     2966 | 2024-04-09 | Party Astronauts | L   | 0.427      | -            | -                | -                | -         |    -2.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3091 | 2024-04-04 | Limitless        | W   | 0.394      | 0.477        | 0.001 (0.000)    | 0.168 (0.032)    | 0 (0.000) |     5.49 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3095 | 2024-04-04 | Limitless        | L   | 0.394      | -            | -                | -                | -         |    -7.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3267 | 2024-03-27 | BOSS             | L   | 0.341      | -            | -                | -                | -         |    -4.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3270 | 2024-03-27 | BOSS             | W   | 0.341      | 0.477        | 0.014 (0.002)    | 0.333 (0.054)    | 0 (0.000) |     6.81 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3510 | 2024-03-14 | Mythic           | L   | 0.254      | -            | -                | -                | -         |    -3.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3513 | 2024-03-14 | Mythic           | L   | 0.254      | -            | -                | -                | -         |    -3.15 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3759 | 2024-03-05 | LAG              | L   | 0.195      | -            | -                | -                | -         |    -1.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3761 | 2024-03-05 | LAG              | L   | 0.194      | -            | -                | -                | -         |    -1.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4016 | 2024-02-22 | Party Astronauts | L   | 0.113      | -            | -                | -                | -         |    -0.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4257 | 2024-02-13 | Perseverance     | W   | 0.054      | 0.477        | 0.004 (0.000)    | 0.244 (0.006)    | -         |     0.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4260 | 2024-02-13 | Perseverance     | L   | 0.054      | -            | -                | -                | -         |    -0.79 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($666.89)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
