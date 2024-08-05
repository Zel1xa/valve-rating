### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [180](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.7<br />
<br />
Final Rank Value (640.7) = Starting Rank Value (712.7) + Head To Head Adjustments (-72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.7
- 400 + ( ( 0.153 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 712.7


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
|           44 |        0 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       31 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      135 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      140 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.12 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      388 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     5.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      579 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.04 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      584 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.73 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      641 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.35 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      645 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.63 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      706 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.283 (0.135)    | 0 (0.000) |    15.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      712 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.283 (0.135)    | 0 (0.000) |    17.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      758 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.83 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      761 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.06 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1017 | 2024-06-15 | Akimbo           | W   | 0.867      | 0.143        | 0.015 (0.002)    | 0.274 (0.034)    | 0 (0.000) |    17.67 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1053 | 2024-06-14 | E-Xolos LAZER    | W   | 0.860      | 0.143        | 0.011 (0.001)    | 0.390 (0.048)    | 0 (0.000) |    18.27 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1808 | 2024-05-22 | Wildcard         | L   | 0.707      | -            | -                | -                | -         |    -3.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1811 | 2024-05-22 | Wildcard         | L   | 0.707      | -            | -                | -                | -         |    -4.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1858 | 2024-05-21 | Elevate          | L   | 0.700      | -            | -                | -                | -         |    -3.33 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1862 | 2024-05-21 | Elevate          | L   | 0.700      | -            | -                | -                | -         |    -3.44 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1895 | 2024-05-20 | MIGHT            | W   | 0.694      | 0.477        | -                | 0.059 (0.020)    | 0 (0.000) |     6.76 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1899 | 2024-05-20 | MIGHT            | L   | 0.693      | -            | -                | -                | -         |   -15.48 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2024 | 2024-05-16 | Limitless        | L   | 0.667      | -            | -                | -                | -         |    -7.51 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2025 | 2024-05-16 | Limitless        | L   | 0.667      | -            | -                | -                | -         |    -7.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2064 | 2024-05-15 | M80              | L   | 0.660      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2071 | 2024-05-15 | M80              | L   | 0.660      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2117 | 2024-05-14 | NRG              | L   | 0.654      | -            | -                | -                | -         |    -4.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2122 | 2024-05-14 | NRG              | L   | 0.653      | -            | -                | -                | -         |    -5.20 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2603 | 2024-04-23 | Nouns            | W   | 0.514      | 0.477        | 0.057 (0.014)    | 0.561 (0.137)    | 0 (0.000) |    12.78 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2605 | 2024-04-23 | Nouns            | L   | 0.513      | -            | -                | -                | -         |    -3.37 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2943 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.427      | 0.477        | 0.010 (0.002)    | 0.101 (0.021)    | 0 (0.000) |     7.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2948 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.427      | -            | -                | -                | -         |    -5.71 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3001 | 2024-04-09 | Party Astronauts | L   | 0.420      | -            | -                | -                | -         |    -2.75 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3007 | 2024-04-09 | Party Astronauts | L   | 0.420      | -            | -                | -                | -         |    -2.82 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3132 | 2024-04-04 | Limitless        | W   | 0.387      | 0.477        | 0.001 (0.000)    | 0.167 (0.031)    | 0 (0.000) |     5.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3136 | 2024-04-04 | Limitless        | L   | 0.387      | -            | -                | -                | -         |    -6.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3308 | 2024-03-27 | BOSS             | L   | 0.334      | -            | -                | -                | -         |    -3.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3311 | 2024-03-27 | BOSS             | W   | 0.334      | 0.477        | 0.014 (0.002)    | 0.332 (0.053)    | 0 (0.000) |     6.66 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3551 | 2024-03-14 | Mythic           | L   | 0.247      | -            | -                | -                | -         |    -3.01 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3554 | 2024-03-14 | Mythic           | L   | 0.247      | -            | -                | -                | -         |    -3.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3801 | 2024-03-05 | LAG              | L   | 0.187      | -            | -                | -                | -         |    -1.94 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3803 | 2024-03-05 | LAG              | L   | 0.187      | -            | -                | -                | -         |    -1.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4058 | 2024-02-22 | Party Astronauts | L   | 0.106      | -            | -                | -                | -         |    -0.78 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4300 | 2024-02-13 | Phoenix          | W   | 0.047      | 0.477        | 0.004 (0.000)    | 0.283 (0.006)    | -         |     0.80 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4303 | 2024-02-13 | Phoenix          | L   | 0.047      | -            | -                | -                | -         |    -0.69 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($661.11)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
