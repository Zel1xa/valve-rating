### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.9<br />
<br />
Final Rank Value (640.9) = Starting Rank Value (712.9) + Head To Head Adjustments (-72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.9
- 400 + ( ( 0.153 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 712.9


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
|           44 |       23 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.08 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       55 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.25 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      159 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      164 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.11 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      412 | 2024-07-24 | InControl        | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.039 (0.015)    | 0 (0.000) |     5.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      603 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      608 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      665 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.38 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      669 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.66 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      730 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.277 (0.132)    | 0 (0.000) |    15.57 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      736 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.277 (0.132)    | 0 (0.000) |    17.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      782 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      785 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.09 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1041 | 2024-06-15 | Akimbo           | W   | 0.860      | 0.143        | 0.015 (0.002)    | 0.269 (0.033)    | 0 (0.000) |    17.51 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1077 | 2024-06-14 | E-Xolos LAZER    | W   | 0.853      | 0.143        | 0.011 (0.001)    | 0.384 (0.047)    | 0 (0.000) |    18.16 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1832 | 2024-05-22 | Wildcard         | L   | 0.701      | -            | -                | -                | -         |    -3.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1835 | 2024-05-22 | Wildcard         | L   | 0.700      | -            | -                | -                | -         |    -4.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1882 | 2024-05-21 | Elevate          | L   | 0.694      | -            | -                | -                | -         |    -3.31 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1886 | 2024-05-21 | Elevate          | L   | 0.693      | -            | -                | -                | -         |    -3.42 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1919 | 2024-05-20 | MIGHT            | W   | 0.687      | 0.477        | -                | 0.058 (0.019)    | 0 (0.000) |     6.67 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1923 | 2024-05-20 | MIGHT            | L   | 0.687      | -            | -                | -                | -         |   -15.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2048 | 2024-05-16 | Limitless        | L   | 0.660      | -            | -                | -                | -         |    -7.46 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2049 | 2024-05-16 | Limitless        | L   | 0.660      | -            | -                | -                | -         |    -7.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2088 | 2024-05-15 | M80              | L   | 0.654      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2095 | 2024-05-15 | M80              | L   | 0.653      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2141 | 2024-05-14 | NRG              | L   | 0.647      | -            | -                | -                | -         |    -4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2146 | 2024-05-14 | NRG              | L   | 0.647      | -            | -                | -                | -         |    -5.17 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2627 | 2024-04-23 | Nouns            | W   | 0.507      | 0.477        | 0.057 (0.014)    | 0.553 (0.134)    | 0 (0.000) |    12.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2629 | 2024-04-23 | Nouns            | L   | 0.507      | -            | -                | -                | -         |    -3.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2967 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.420      | 0.477        | 0.010 (0.002)    | 0.098 (0.020)    | 0 (0.000) |     7.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2972 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.420      | -            | -                | -                | -         |    -5.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3025 | 2024-04-09 | Party Astronauts | L   | 0.414      | -            | -                | -                | -         |    -2.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3031 | 2024-04-09 | Party Astronauts | L   | 0.413      | -            | -                | -                | -         |    -2.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3156 | 2024-04-04 | Limitless        | W   | 0.380      | 0.477        | 0.001 (0.000)    | 0.163 (0.030)    | 0 (0.000) |     5.26 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3160 | 2024-04-04 | Limitless        | L   | 0.380      | -            | -                | -                | -         |    -6.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3332 | 2024-03-27 | BOSS             | L   | 0.327      | -            | -                | -                | -         |    -3.89 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3335 | 2024-03-27 | BOSS             | W   | 0.327      | 0.477        | 0.014 (0.002)    | 0.326 (0.051)    | 0 (0.000) |     6.54 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3575 | 2024-03-14 | Mythic           | L   | 0.241      | -            | -                | -                | -         |    -2.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3578 | 2024-03-14 | Mythic           | L   | 0.240      | -            | -                | -                | -         |    -3.00 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3825 | 2024-03-05 | LAG              | L   | 0.181      | -            | -                | -                | -         |    -1.88 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3827 | 2024-03-05 | LAG              | L   | 0.180      | -            | -                | -                | -         |    -1.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4082 | 2024-02-22 | Party Astronauts | L   | 0.099      | -            | -                | -                | -         |    -0.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4324 | 2024-02-13 | Phoenix          | W   | 0.041      | 0.477        | 0.004 (0.000)    | -                | -         |     0.68 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4327 | 2024-02-13 | Phoenix          | L   | 0.040      | -            | -                | -                | -         |    -0.59 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($655.78)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
