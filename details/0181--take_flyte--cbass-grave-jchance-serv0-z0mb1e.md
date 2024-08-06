### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.8<br />
<br />
Final Rank Value (640.8) = Starting Rank Value (712.8) + Head To Head Adjustments (-72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.8
- 400 + ( ( 0.152 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 712.8


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
|           44 |       27 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       59 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.25 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      163 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      168 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.11 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      416 | 2024-07-24 | InControl        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.039 (0.015)    | 0 (0.000) |     5.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      607 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      612 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.70 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      669 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.39 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      673 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.67 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      734 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.277 (0.132)    | 0 (0.000) |    15.57 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      740 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.277 (0.132)    | 0 (0.000) |    17.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      786 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      789 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1045 | 2024-06-15 | Akimbo           | W   | 0.858      | 0.143        | 0.015 (0.002)    | 0.269 (0.033)    | 0 (0.000) |    17.45 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1081 | 2024-06-14 | E-Xolos LAZER    | W   | 0.851      | 0.143        | 0.011 (0.001)    | 0.384 (0.047)    | 0 (0.000) |    18.10 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1836 | 2024-05-22 | Wildcard         | L   | 0.698      | -            | -                | -                | -         |    -3.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1839 | 2024-05-22 | Wildcard         | L   | 0.698      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1886 | 2024-05-21 | Elevate          | L   | 0.691      | -            | -                | -                | -         |    -3.30 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1890 | 2024-05-21 | Elevate          | L   | 0.691      | -            | -                | -                | -         |    -3.41 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1923 | 2024-05-20 | MIGHT            | W   | 0.684      | 0.477        | -                | 0.057 (0.019)    | 0 (0.000) |     6.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1927 | 2024-05-20 | MIGHT            | L   | 0.684      | -            | -                | -                | -         |   -15.31 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2052 | 2024-05-16 | Limitless        | L   | 0.658      | -            | -                | -                | -         |    -7.44 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2053 | 2024-05-16 | Limitless        | L   | 0.657      | -            | -                | -                | -         |    -7.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2092 | 2024-05-15 | M80              | L   | 0.651      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2099 | 2024-05-15 | M80              | L   | 0.651      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2145 | 2024-05-14 | NRG              | L   | 0.644      | -            | -                | -                | -         |    -4.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2150 | 2024-05-14 | NRG              | L   | 0.644      | -            | -                | -                | -         |    -5.16 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2631 | 2024-04-23 | Nouns            | W   | 0.504      | 0.477        | 0.057 (0.014)    | 0.553 (0.133)    | 0 (0.000) |    12.52 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2633 | 2024-04-23 | Nouns            | L   | 0.504      | -            | -                | -                | -         |    -3.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2971 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.418      | 0.477        | 0.010 (0.002)    | 0.097 (0.019)    | 0 (0.000) |     7.66 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2976 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.417      | -            | -                | -                | -         |    -5.60 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3029 | 2024-04-09 | Party Astronauts | L   | 0.411      | -            | -                | -                | -         |    -2.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3035 | 2024-04-09 | Party Astronauts | L   | 0.411      | -            | -                | -                | -         |    -2.79 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3160 | 2024-04-04 | Limitless        | W   | 0.378      | 0.477        | 0.001 (0.000)    | 0.163 (0.029)    | 0 (0.000) |     5.22 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3164 | 2024-04-04 | Limitless        | L   | 0.378      | -            | -                | -                | -         |    -6.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3336 | 2024-03-27 | BOSS             | L   | 0.325      | -            | -                | -                | -         |    -3.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3339 | 2024-03-27 | BOSS             | W   | 0.324      | 0.477        | 0.014 (0.002)    | 0.326 (0.050)    | 0 (0.000) |     6.49 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3579 | 2024-03-14 | Mythic           | L   | 0.238      | -            | -                | -                | -         |    -2.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3582 | 2024-03-14 | Mythic           | L   | 0.238      | -            | -                | -                | -         |    -2.97 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3829 | 2024-03-05 | LAG              | L   | 0.178      | -            | -                | -                | -         |    -1.85 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3831 | 2024-03-05 | LAG              | L   | 0.178      | -            | -                | -                | -         |    -1.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4086 | 2024-02-22 | Party Astronauts | L   | 0.097      | -            | -                | -                | -         |    -0.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4328 | 2024-02-13 | Phoenix          | W   | 0.038      | 0.477        | 0.004 (0.000)    | -                | -         |     0.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4331 | 2024-02-13 | Phoenix          | L   | 0.038      | -            | -                | -                | -         |    -0.56 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($653.78)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
