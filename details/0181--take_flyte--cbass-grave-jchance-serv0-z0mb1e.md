### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.5<br />
<br />
Final Rank Value (640.5) = Starting Rank Value (712.5) + Head To Head Adjustments (-72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
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
|           44 |       20 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       52 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      156 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      161 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      409 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      600 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.04 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      605 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      662 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.37 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      666 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      727 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.278 (0.132)    | 0 (0.000) |    15.58 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      733 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.278 (0.132)    | 0 (0.000) |    17.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      779 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      782 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1038 | 2024-06-15 | Akimbo           | W   | 0.862      | 0.143        | 0.015 (0.002)    | 0.270 (0.033)    | 0 (0.000) |    17.57 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1074 | 2024-06-14 | E-Xolos LAZER    | W   | 0.856      | 0.143        | 0.011 (0.001)    | 0.384 (0.047)    | 0 (0.000) |    18.18 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1829 | 2024-05-22 | Wildcard         | L   | 0.703      | -            | -                | -                | -         |    -3.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1832 | 2024-05-22 | Wildcard         | L   | 0.703      | -            | -                | -                | -         |    -4.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1879 | 2024-05-21 | Elevate          | L   | 0.696      | -            | -                | -                | -         |    -3.31 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1883 | 2024-05-21 | Elevate          | L   | 0.696      | -            | -                | -                | -         |    -3.42 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1916 | 2024-05-20 | MIGHT            | W   | 0.689      | 0.477        | -                | 0.058 (0.019)    | 0 (0.000) |     6.70 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1920 | 2024-05-20 | MIGHT            | L   | 0.689      | -            | -                | -                | -         |   -15.40 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2045 | 2024-05-16 | Limitless        | L   | 0.662      | -            | -                | -                | -         |    -7.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2046 | 2024-05-16 | Limitless        | L   | 0.662      | -            | -                | -                | -         |    -7.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2085 | 2024-05-15 | M80              | L   | 0.656      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2092 | 2024-05-15 | M80              | L   | 0.656      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2138 | 2024-05-14 | NRG              | L   | 0.649      | -            | -                | -                | -         |    -4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2143 | 2024-05-14 | NRG              | L   | 0.649      | -            | -                | -                | -         |    -5.18 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2624 | 2024-04-23 | Nouns            | W   | 0.509      | 0.477        | 0.057 (0.014)    | 0.553 (0.134)    | 0 (0.000) |    12.66 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2626 | 2024-04-23 | Nouns            | L   | 0.509      | -            | -                | -                | -         |    -3.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2964 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.423      | 0.477        | 0.010 (0.002)    | 0.098 (0.020)    | 0 (0.000) |     7.76 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2969 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.422      | -            | -                | -                | -         |    -5.65 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3022 | 2024-04-09 | Party Astronauts | L   | 0.416      | -            | -                | -                | -         |    -2.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3028 | 2024-04-09 | Party Astronauts | L   | 0.416      | -            | -                | -                | -         |    -2.81 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3153 | 2024-04-04 | Limitless        | W   | 0.383      | 0.477        | 0.001 (0.000)    | 0.164 (0.030)    | 0 (0.000) |     5.30 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3157 | 2024-04-04 | Limitless        | L   | 0.382      | -            | -                | -                | -         |    -6.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3329 | 2024-03-27 | BOSS             | L   | 0.329      | -            | -                | -                | -         |    -3.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3332 | 2024-03-27 | BOSS             | W   | 0.329      | 0.477        | 0.014 (0.002)    | 0.327 (0.051)    | 0 (0.000) |     6.56 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3572 | 2024-03-14 | Mythic           | L   | 0.243      | -            | -                | -                | -         |    -2.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3575 | 2024-03-14 | Mythic           | L   | 0.242      | -            | -                | -                | -         |    -3.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3822 | 2024-03-05 | LAG              | L   | 0.183      | -            | -                | -                | -         |    -1.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3824 | 2024-03-05 | LAG              | L   | 0.182      | -            | -                | -                | -         |    -1.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4079 | 2024-02-22 | Party Astronauts | L   | 0.102      | -            | -                | -                | -         |    -0.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4321 | 2024-02-13 | Phoenix          | W   | 0.043      | 0.477        | 0.004 (0.000)    | 0.278 (0.006)    | -         |     0.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4324 | 2024-02-13 | Phoenix          | L   | 0.043      | -            | -                | -                | -         |    -0.63 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($657.56)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
