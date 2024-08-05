### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.4<br />
<br />
Final Rank Value (640.4) = Starting Rank Value (712.5) + Head To Head Adjustments (-72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.5
- 400 + ( ( 0.152 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 712.5


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
|           44 |       21 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       53 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      157 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      162 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      410 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      601 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.04 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      606 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      663 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.37 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      667 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      728 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.278 (0.132)    | 0 (0.000) |    15.58 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      734 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.278 (0.132)    | 0 (0.000) |    17.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      780 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      783 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1039 | 2024-06-15 | Akimbo           | W   | 0.862      | 0.143        | 0.015 (0.002)    | 0.270 (0.033)    | 0 (0.000) |    17.56 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1075 | 2024-06-14 | E-Xolos LAZER    | W   | 0.855      | 0.143        | 0.011 (0.001)    | 0.384 (0.047)    | 0 (0.000) |    18.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1830 | 2024-05-22 | Wildcard         | L   | 0.702      | -            | -                | -                | -         |    -3.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1833 | 2024-05-22 | Wildcard         | L   | 0.702      | -            | -                | -                | -         |    -4.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1880 | 2024-05-21 | Elevate          | L   | 0.695      | -            | -                | -                | -         |    -3.31 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1884 | 2024-05-21 | Elevate          | L   | 0.695      | -            | -                | -                | -         |    -3.42 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1917 | 2024-05-20 | MIGHT            | W   | 0.689      | 0.477        | -                | 0.058 (0.019)    | 0 (0.000) |     6.70 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1921 | 2024-05-20 | MIGHT            | L   | 0.688      | -            | -                | -                | -         |   -15.39 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2046 | 2024-05-16 | Limitless        | L   | 0.662      | -            | -                | -                | -         |    -7.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2047 | 2024-05-16 | Limitless        | L   | 0.662      | -            | -                | -                | -         |    -7.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2086 | 2024-05-15 | M80              | L   | 0.655      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2093 | 2024-05-15 | M80              | L   | 0.655      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2139 | 2024-05-14 | NRG              | L   | 0.649      | -            | -                | -                | -         |    -4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2144 | 2024-05-14 | NRG              | L   | 0.648      | -            | -                | -                | -         |    -5.18 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2625 | 2024-04-23 | Nouns            | W   | 0.509      | 0.477        | 0.057 (0.014)    | 0.553 (0.134)    | 0 (0.000) |    12.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2627 | 2024-04-23 | Nouns            | L   | 0.508      | -            | -                | -                | -         |    -3.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2965 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.422      | 0.477        | 0.010 (0.002)    | 0.098 (0.020)    | 0 (0.000) |     7.75 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2970 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.422      | -            | -                | -                | -         |    -5.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3023 | 2024-04-09 | Party Astronauts | L   | 0.415      | -            | -                | -                | -         |    -2.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3029 | 2024-04-09 | Party Astronauts | L   | 0.415      | -            | -                | -                | -         |    -2.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3154 | 2024-04-04 | Limitless        | W   | 0.382      | 0.477        | 0.001 (0.000)    | 0.164 (0.030)    | 0 (0.000) |     5.29 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3158 | 2024-04-04 | Limitless        | L   | 0.382      | -            | -                | -                | -         |    -6.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3330 | 2024-03-27 | BOSS             | L   | 0.329      | -            | -                | -                | -         |    -3.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3333 | 2024-03-27 | BOSS             | W   | 0.329      | 0.477        | 0.014 (0.002)    | 0.327 (0.051)    | 0 (0.000) |     6.55 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3573 | 2024-03-14 | Mythic           | L   | 0.242      | -            | -                | -                | -         |    -2.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3576 | 2024-03-14 | Mythic           | L   | 0.242      | -            | -                | -                | -         |    -3.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3823 | 2024-03-05 | LAG              | L   | 0.182      | -            | -                | -                | -         |    -1.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3825 | 2024-03-05 | LAG              | L   | 0.182      | -            | -                | -                | -         |    -1.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4080 | 2024-02-22 | Party Astronauts | L   | 0.101      | -            | -                | -                | -         |    -0.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4322 | 2024-02-13 | Phoenix          | W   | 0.042      | 0.477        | 0.004 (0.000)    | 0.278 (0.006)    | -         |     0.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4325 | 2024-02-13 | Phoenix          | L   | 0.042      | -            | -                | -                | -         |    -0.62 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($657.22)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
