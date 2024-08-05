### Roster Details<br />
Team Name: Take Flyte<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  640.6<br />
<br />
Final Rank Value (640.6) = Starting Rank Value (712.5) + Head To Head Adjustments (-72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.5
- 400 + ( ( 0.153 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 712.5


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
|           44 |       12 | 2024-08-04 | Final Form       | L   | 1.000      | -            | -                | -                | -         |   -19.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           43 |       44 | 2024-08-03 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -5.26 | cbass, Champ, jchancE, serv0, z0mb1e |
|           42 |      148 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|           41 |      153 | 2024-07-31 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -14.13 | cbass, Grave, jchancE, serv0, z0mb1e |
|           40 |      401 | 2024-07-24 | The Nomads       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     5.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           39 |      592 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|           38 |      597 | 2024-07-18 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -9.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           37 |      654 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           36 |      658 | 2024-07-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.64 | cbass, Grave, jchancE, serv0, z0mb1e |
|           35 |      719 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.281 (0.134)    | 0 (0.000) |    15.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           34 |      725 | 2024-07-16 | Phoenix          | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.281 (0.134)    | 0 (0.000) |    17.02 | cbass, Grave, jchancE, serv0, z0mb1e |
|           33 |      771 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -4.84 | cbass, Grave, jchancE, serv0, z0mb1e |
|           32 |      774 | 2024-07-15 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.07 | cbass, Grave, jchancE, serv0, z0mb1e |
|           31 |     1030 | 2024-06-15 | Akimbo           | W   | 0.863      | 0.143        | 0.015 (0.002)    | 0.273 (0.034)    | 0 (0.000) |    17.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|           30 |     1066 | 2024-06-14 | E-Xolos LAZER    | W   | 0.857      | 0.143        | 0.011 (0.001)    | 0.389 (0.048)    | 0 (0.000) |    18.20 | cbass, Grave, jchancE, serv0, z0mb1e |
|           29 |     1821 | 2024-05-22 | Wildcard         | L   | 0.704      | -            | -                | -                | -         |    -3.99 | cbass, Grave, jchancE, serv0, z0mb1e |
|           28 |     1824 | 2024-05-22 | Wildcard         | L   | 0.704      | -            | -                | -                | -         |    -4.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|           27 |     1871 | 2024-05-21 | Elevate          | L   | 0.697      | -            | -                | -                | -         |    -3.32 | cbass, Champ, jchancE, serv0, z0mb1e |
|           26 |     1875 | 2024-05-21 | Elevate          | L   | 0.697      | -            | -                | -                | -         |    -3.42 | cbass, Champ, jchancE, serv0, z0mb1e |
|           25 |     1908 | 2024-05-20 | MIGHT            | W   | 0.690      | 0.477        | -                | 0.059 (0.019)    | 0 (0.000) |     6.72 | cbass, Grave, jchancE, serv0, z0mb1e |
|           24 |     1912 | 2024-05-20 | MIGHT            | L   | 0.690      | -            | -                | -                | -         |   -15.42 | cbass, Grave, jchancE, serv0, z0mb1e |
|           23 |     2037 | 2024-05-16 | Limitless        | L   | 0.664      | -            | -                | -                | -         |    -7.49 | cbass, Grave, jchancE, serv0, z0mb1e |
|           22 |     2038 | 2024-05-16 | Limitless        | L   | 0.663      | -            | -                | -                | -         |    -7.91 | cbass, Grave, jchancE, serv0, z0mb1e |
|           21 |     2077 | 2024-05-15 | M80              | L   | 0.657      | -            | -                | -                | -         |    -0.86 | cbass, Grave, jchancE, serv0, z0mb1e |
|           20 |     2084 | 2024-05-15 | M80              | L   | 0.657      | -            | -                | -                | -         |    -0.87 | cbass, Grave, jchancE, serv0, z0mb1e |
|           19 |     2130 | 2024-05-14 | NRG              | L   | 0.650      | -            | -                | -                | -         |    -4.96 | cbass, Grave, jchancE, serv0, z0mb1e |
|           18 |     2135 | 2024-05-14 | NRG              | L   | 0.650      | -            | -                | -                | -         |    -5.18 | cbass, Grave, jchancE, serv0, z0mb1e |
|           17 |     2616 | 2024-04-23 | Nouns            | W   | 0.510      | 0.477        | 0.057 (0.014)    | 0.560 (0.136)    | 0 (0.000) |    12.69 | cbass, Grave, jchancE, serv0, z0mb1e |
|           16 |     2618 | 2024-04-23 | Nouns            | L   | 0.510      | -            | -                | -                | -         |    -3.36 | cbass, Grave, jchancE, serv0, z0mb1e |
|           15 |     2956 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.424      | 0.477        | 0.010 (0.002)    | 0.100 (0.020)    | 0 (0.000) |     7.77 | cbass, Grave, jchancE, serv0, z0mb1e |
|           14 |     2961 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.423      | -            | -                | -                | -         |    -5.67 | cbass, Grave, jchancE, serv0, z0mb1e |
|           13 |     3014 | 2024-04-09 | Party Astronauts | L   | 0.417      | -            | -                | -                | -         |    -2.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|           12 |     3020 | 2024-04-09 | Party Astronauts | L   | 0.417      | -            | -                | -                | -         |    -2.81 | cbass, Grave, jchancE, serv0, z0mb1e |
|           11 |     3145 | 2024-04-04 | Limitless        | W   | 0.384      | 0.477        | 0.001 (0.000)    | 0.166 (0.030)    | 0 (0.000) |     5.31 | cbass, Grave, jchancE, serv0, z0mb1e |
|           10 |     3149 | 2024-04-04 | Limitless        | L   | 0.383      | -            | -                | -                | -         |    -6.92 | cbass, Grave, jchancE, serv0, z0mb1e |
|            9 |     3321 | 2024-03-27 | BOSS             | L   | 0.331      | -            | -                | -                | -         |    -3.95 | cbass, Grave, jchancE, serv0, z0mb1e |
|            8 |     3324 | 2024-03-27 | BOSS             | W   | 0.330      | 0.477        | 0.014 (0.002)    | 0.331 (0.052)    | 0 (0.000) |     6.59 | cbass, Grave, jchancE, serv0, z0mb1e |
|            7 |     3564 | 2024-03-14 | Mythic           | L   | 0.244      | -            | -                | -                | -         |    -2.98 | cbass, Grave, jchancE, serv0, z0mb1e |
|            6 |     3567 | 2024-03-14 | Mythic           | L   | 0.244      | -            | -                | -                | -         |    -3.03 | cbass, Grave, jchancE, serv0, z0mb1e |
|            5 |     3814 | 2024-03-05 | LAG              | L   | 0.184      | -            | -                | -                | -         |    -1.90 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     3816 | 2024-03-05 | LAG              | L   | 0.184      | -            | -                | -                | -         |    -1.93 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     4071 | 2024-02-22 | Party Astronauts | L   | 0.103      | -            | -                | -                | -         |    -0.75 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     4313 | 2024-02-13 | Phoenix          | W   | 0.044      | 0.477        | 0.004 (0.000)    | 0.281 (0.006)    | -         |     0.74 | cbass, Grave, jchancE, serv0, z0mb1e |
|            1 |     4316 | 2024-02-13 | Phoenix          | L   | 0.044      | -            | -                | -                | -         |    -0.64 | cbass, Grave, jchancE, serv0, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($658.44)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
